# Daily Game, by Kevin Patto

## Development branch

This is the development branch. This is where large changes are staged for merging to the main branch.

## Login System Update

After merging to dev, this update will sufficiently implement a login with these features:

- User can create account.
- User’s account is saved to database.
- User’s username cannot be blank, minimum of three characters.
- Password is securely stored. Administrators should not be able to see password in plaintext, or be able to find out what password is.
- Password has restrictions: at least 12 characters, one special character, one capital character, one number, and not similar to other user data (username, email).
- Invalid inputs during account creation are clearly labeled to user (password too short, username taken, username too short, etc.).