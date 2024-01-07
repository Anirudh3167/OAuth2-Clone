# OAuth2-Clone
Preforms the OAuth authentication just like the others.

UNDER DEVELOPMENT

# How it works?
## Approach
It is a three step approach :-
1. A re-direct will occur from the source app.
2. User will be asked authentication just like the google OAuth
3. In case of no account. A new account is created
4. An acknowledgment will be sent to the source app with the JWT tokens.

## Security
Two tokens will be sent :-
1. Access Token (expires in 15 mins)
2. Refresh Token (expires in 90 days)

## Others
1. User will have the account in this app.
2. They can see their previous logins and places where the authentication is used.

# Pages
1. Re-direct page.
2. New user creation pages (2 pages)
3. Dashboard (Show offs)
4. Previous logins
5. Logout from the account