# Nimitii_Android

https://docs.aws.amazon.com/cognito/index.html
https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools.html
https://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
https://docs.aws.amazon.com/cli/latest/reference/cognito-idp/index.html

https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html
https://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html

Do you want to use the default authentication and security configuration?                     
  Default configuration                                                       
  Default configuration with Social Provider (Federation)                     
> Manual configuration                                                       
  I want to learn more.

Select the authentication/authorization services that you want to use: (Use arrow keys)  
  User Sign-Up, Sign-In, connected with AWS IAM controls (Enables per-user Storage features for images or other content, Analytics, and more)    
> User Sign-Up & Sign-In only (Best used with a cloud API only)                                                                              
  I want to learn more.

Please provide a friendly name for your resource that will be used to label this category in the project: nimitiAuthentication

Please provide a name for your user pool: nimitiAuthenticationUserPool

How do you want users to be able to sign in? (Press <space> to select, <a> to toggle all, <i> to invert selection)        
> (*) Email                                                                                                      
  ( ) Username                                                                                                 
  ( ) Phone number

Do you want to add User Pool Groups? (Use arrow keys)            
  Yes                                                        
> No                                                                
  I want to learn more.

Do you want to add an admin queries API?           
  Yes                                  
> No                                     
  I want to learn more.

Multifactor authentication (MFA) user login options: (Use arrow keys)                                        
> OFF                                                                 
  ON (Required for all logins, can not be enabled later)            
  OPTIONAL (Individual users can use MFA)                           
  I want to learn more.


Email based user registration/forgot password: (Use arrow keys)     
> Enabled (Requires per-user email entry at registration)       
  Disabled (Uses SMS/TOTP as an alternative)


Please specify an email verification subject: (Your verification code)

Please specify an email verification message: NIMITI One Time Paswword for password reset is {####}

Do you want to override the default password policy for this User Pool? (y/N)

Enter the minimum password length for this User Pool: (8)

Select the password character requirements for your userpool:                                    
(*) Requires Lowercase                                                      
(*) Requires Uppercase                                                             
(*) Requires Numbers                                                             
(*) Requires Symbols

Warning: you will not be able to edit these selections.                               
What attributes are required for signing up?                                      
(*) Email                                                                         
( ) Family Name (This attribute is not supported by Login With Amazon.)         
( ) Middle Name (This attribute is not supported by Google, Login With Amazon, Signinwithapple.)   
( ) Gender (This attribute is not supported by Login With Amazon, Signinwithapple.)             
( ) Locale (This attribute is not supported by Facebook, Google, Signinwithapple.)                      
( ) Given Name (This attribute is not supported by Login With Amazon.)                            
(*) Name (This attribute is not supported by Signinwithapple.)                             
> (Move up and down to reveal more choices)

Specify the app's refresh token expiration period (in days): 1

Do you want to specify the user attributes this app can read and write? (y/N) y
Specify read attributes:              
(*) Email                                
( ) Family Name                            
( ) Middle Name                             
( ) Gender                                  
( ) Locale                                
( ) Given Name                             
(*) Name                                   
> (Move up and down to reveal more choices)


Specify write attributes:              
Do you want to enable any of the following capabilities? (Press <space> to select, <a> to toggle all, <i> to invert selection)                  
( ) Add Google reCaptcha Challenge                                                                                                      
( ) Email Verification Link with Redirect                        
( ) Add User to Group                                      
( ) Email Domain Filtering (denylist)                  
( ) Email Domain Filtering (allowlist)                
( ) Custom Auth Challenge Flow (basic scaffolding - not for production)       
( ) Override ID Token Claims


Do you want to use an OAuth flow? (Use arrow keys)   
Yes                                             
No                                            
I want to learn more.

? Do you want to configure Lambda Triggers for Cognito? (Y/n)



Final Result
The current configured provider is Amazon Cognito.                                 
Do you want to use the default authentication and security configuration? Manual configuration               
Select the authentication/authorization services that you want to use: User Sign-Up & Sign-In only (Best used with a cloud API only)    
Please provide a friendly name for your resource that will be used to label this category in the project: nimitiAuthentication          
Please provide a name for your user pool: nimitiAuthenticationUserPool                                                                 
Warning: you will not be able to edit these selections.                                                                            
How do you want users to be able to sign in? Email                                                                                   
Do you want to add User Pool Groups? No                                                                                           
Do you want to add an admin queries API? No                                                                                  
Multifactor authentication (MFA) user login options: OFF                                                                    
Email based user registration/forgot password: Enabled (Requires per-user email entry at registration)                  
Please specify an email verification subject: Nimiti OTP                                   
Please specify an email verification message: NIMITI One Time Paswword for password reset is {####}         
Do you want to override the default password policy for this User Pool? Yes                              
Enter the minimum password length for this User Pool: 8                                
Select the password character requirements for your userpool: Requires Lowercase, Requires Uppercase, Requires Numbers, Requires Symbols      
Warning: you will not be able to edit these selections.                                   
What attributes are required for signing up? Email, Name (This attribute is not supported by Signinwithapple.)            
Specify the app's refresh token expiration period (in days): 1                                                 
Do you want to specify the user attributes this app can read and write? Yes                                  
Specify read attributes: Email, Name                                                                       
Specify write attributes:                                                                                 
Do you want to enable any of the following capabilities?                                                 
Do you want to use an OAuth flow? No                                                                     
? Do you want to configure Lambda Triggers for Cognito? No                                               
Successfully added auth resource nimitiAuthentication locally