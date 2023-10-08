# Nimitii_Android
Using service: Cognito, provided by: awscloudformation             
What do you want to do? Walkthrough all the auth configurations                              
Select the authentication/authorization services that you want to use: User Sign-Up & Sign-In only (Best used with a cloud API only)                  
Do you want to add User Pool Groups? No                                                                                                             
Do you want to add an admin queries API? No                                                                                                          
Multifactor authentication (MFA) user login options: OFF                                                                                             
Email based user registration/forgot password: Enabled (Requires per-user email entry at registration)                                             
Please specify an email verification subject: Nimiti OTP                                                                                          
Please specify an email verification message: Your Nimiti Account Verification OTP is {####}                                                    
Do you want to override the default password policy for this User Pool? No                                                                      
Specify the app's refresh token expiration period (in days): 1                                                                                 
Do you want to specify the user attributes this app can read and write? Yes                                                                   
Specify read attributes: Email, Name, Picture                                                                                                
Specify write attributes: Name, Picture                                                                                                    
Do you want to enable any of the following capabilities? Custom Auth Challenge Flow (basic scaffolding - not for production)               
Do you want to use an OAuth flow? No                                                                                                    
Warning! Your existing IdentityPool: undefined will be deleted upon the next “amplify push”!                                            
? Do you want to configure Lambda Triggers for Cognito? No                                                                              
Successfully added resource nimitiAuthDefineAuthChallenge locally.                                                                      
Next steps:                                                                                                                             
Check out sample function code generated in <project-dir>/amplify/backend/function/nimitiAuthDefineAuthChallenge/src                    
"amplify function build" builds all of your functions currently in the project                                                          
"amplify mock function <functionName>" runs your function locally                                                                      
"amplify push" builds all of your local backend resources and provisions them in the cloud                                             
"amplify publish" builds all of your local backend and front-end resources (if you added hosting category) and provisions them in the cloud     
Successfully added the Lambda function locally                                                                                                    
? Do you want to edit your boilerplate-define-challenge function now? No                                                                              
? Enter the answer to your custom auth challenge Yes                                                                                                  
Successfully added resource nimitiAuthCreateAuthChallenge locally.                                                                                    
Next steps:                                                                                                                                           
Check out sample function code generated in <project-dir>/amplify/backend/function/nimitiAuthCreateAuthChallenge/src                                   
"amplify function build" builds all of your functions currently in the project                                                                         
"amplify mock function <functionName>" runs your function locally                                                                                      
"amplify push" builds all of your local backend resources and provisions them in the cloud                                                             
"amplify publish" builds all of your local backend and front-end resources (if you added hosting category) and provisions them in the cloud            
Successfully added the Lambda function locally                                                                                                         
? Do you want to edit your boilerplate-create-challenge function now? No                                                                                 
Successfully added resource nimitiAuthVerifyAuthChallengeResponse locally.                                                                               
Next steps:                                                                                                                                               
Check out sample function code generated in <project-dir>/amplify/backend/function/nimitiAuthVerifyAuthChallengeResponse/src                              
"amplify function build" builds all of your functions currently in the project                                                                           
"amplify mock function <functionName>" runs your function locally                                                                                       
"amplify push" builds all of your local backend resources and provisions them in the cloud                                                          
"amplify publish" builds all of your local backend and front-end resources (if you added hosting category) and provisions them in the cloud         
Successfully added the Lambda function locally                                                                                                      
? Do you want to edit your boilerplate-verify function now? No                                                                                      
Successfully updated auth resource nimitiAuth locally                                                                                               
Some next steps:                                                                                                                                     
"amplify push" will build all your local backend resources and provision it in the cloud                                                                
"amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud           
Successfully updated resource nimitiAuth locally                                                                                                        
Some next steps:                                                                                                                                        
"amplify push" will build all your local backend resources and provision it in the cloud                                                                
"amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud               
PS C:\Users\Geeta Crafts\Documents\GitHub\Nimitii_Android> amplify push                                                                                     
- Fetching updates to backend environment: main from the cloud.