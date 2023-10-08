# Nimitii_Android

Services Used
1. AWS Cognito(Authentication)
2. AWS Amplify(User Management)
3. AWS Simple Storage Service(Storage)
4. AWS AppSync(GraphQl)
5. AWS GateWay(Rest API)
6. Lambda(Perform certain operation)
7. AWS Rekognition(Collection,search Face)
8. AWS DynamoDb(Store User Data,Note Data, Face Data)

Tried in the way
1. AWS Cloud Watch
2. AWS X-Ray
3. AWS CLoud Formation
4. Amazon Textract

## **AWS Lambda**
1. nimitiAuthPreSignUp
    1. Add Initial Note
    2. Move Image from cache folder
    3. Update Path in congnito(Doing it here will give error as the user is not created)
    4. Auto confirm and verify user
2. nimitiAuthPostSignUp
    1. Copy Object from cache to signUp
    2. Delete Object from cache
    3. Update ImagePath and pileId Attribute
    4. Get Face Data and save it in Rekognition CollectionId
    5. Save the FaceId To the DynamoDb along with the userId
      (So that the user and sub user can be retrieved on search and the sub user data can be delted at the time of signUp)
3. nimitiGatewaySearchMyFace
   1. Check if user face(Notify User with user id.)
   2. Check if sub user face(Notify User with user id.)
   3. Otherwise return null
4. nimitiGatewayAddSubUser
   1. Check if user face(Notify User)
   2. Check if sub user face(Notify User)
   3. Move Image from cache to sub User folder
   4. Add the sub user
   5. Index the face to sub User collection and update index
5. nimitiCreateRekognitionCollection