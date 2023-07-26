# authtoken

User Authentication Management using JSON WEB Token, Email Verification Process, and Google OAuth Libraries from Scratch.

**Development Flow:**

=> In Frontend, Login & Sign Up Page Created

=> JSON Web Token Implementation in Frontend and Backend using bcrypt, dotenv, jsonwebtoken packages
    a) **FrontEnd**: In signup, login & user-info pages
    b) **BackEnd** In signup, login & user-info update pages
    
=> Email Verification Process using Twillio Sendgrid mail & uuid packages
    a) **FrontEnd**: In signup, verifyemail, pleasevarify, sendemails & user-info pages
    b) **BackEnd** In signup, verifyemail & user-info update pages

=> Reset Password Steps
    a) **FrontEnd**: In ForgetPwd, ResetPwd pages
    b) **BackEnd** In ForgetPwd, ResetPwd  update pages

=> OAuth using google api libraries
    a) **FrontEnd**: In oAuthurl, getUser, OauthClient, updateoath pages
    b) **BackEnd** In oAuthurl, Callback  pages


 Three Main Authentication Strategy Classes

  1 )   The knowledge test
  2 )   The ownership test
  3 )   The biological test


Knowledge-Based Authentication

Verifying users' identities based on whether or not they know something

  • A password
  ● A PIN
  • ● A security question


Main Problems with Knowledge-Based Authentication
  • Reliant on the strength of the password
  • Can be guessable or searchable



Ownership-Based Authentication
Verifying users' identities based on whether or not they have something:

    An email address
  ● A mobile phone
  ● An OTP fob or app


Main Problems with Ownership-Based Authentication
  • Some rely indirectly on knowledge-based strategies (that is,
    someone could guess your email password)
    Physical devices can be stolen
    Physical devices can be lost

Two-Factor Authentication
Combines more than one authentication method usually knowledge based and ownership based

=> authenticator app or methods

IP & Location Based Authentication


Biological-Based Authentication
Verifying users' identities based on hard-to-fake biological characteristics
   ● Facial recognition
  ● Fingerprint readers
  ● Eye scans

