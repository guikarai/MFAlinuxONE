# MFA for SSH on LinuxONE on IBM Z and LinuxONE

## What is MFA?
MFA stands for Multifactor authentication.

Multifactor authentication (MFA) is a security technology that requires multiple methods of authentication from independent categories of credentials to verify a user's identity for a login or other transaction. 

Multifactor authentication combines two or more independent credentials: 
* what the user knows: such as a password
* what the user has : such as a security token
* and what the user is : by using biometric verification methods

Pluggable Authentication Modules allow Linux to work with various type of "Authenticator" and other OTP tools to add two-factor security to your system.

With MFA, we add another authentication layer, making Linux based systems more secure. In addition to traditional username and password-based authentication, it uses more secure methods like an SSH key pair and TOTP to log into the system. By implementing these measures, it improves system security and make Linux devices harder to break into.

## MFA solutions
There are multiple MFA solution available in the market. There is choice to protect log into a linux systems. Some to select their enterprise Linux MFA solution, while other to select a solution that will help them to combine log in security and online accounts protection from the same package.

You can find below a list of MFA solution able to secure both access to key online accounts and system login:
1. IBM Verify (Variable)
3. IBM MFA (z/OS)
4. Google Authenticator (Android / iOS)
5. Lastpass Authenticator (Android / iOS)
6. Authy (Android / iOS)
7. 2FA Authenticator (Android / iOS)
8. Duo Mobile (Android / iOS)
9. Microsoft Authenticator (Android / iOS)
10. Step Two (iOS)
11. Aegis Authenticator (Android)
12. Apple Two-Factor Authentication

For the following we will use Google Authenticator.

## Setting up multi-factor authentication on Linux on IBM Z and LinuxONE
