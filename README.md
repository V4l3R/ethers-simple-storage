// Ctrl + Shift + V : Preview README

# Ethers Simple Storage FCC

This is a project based on the FreeCodeCamp tutorial

To run it:

1. Install ganache on your desktop and run it
2. Fill the .env.exemple file with the private key of a ganache's wallet
3. Rename .env.exemple file to .env
4. Run "yarn compile" command in the command prompt
5. Run "node deploy.js" command in the command prompt

To use an encrypted key:

1. Fill the PRIVATE_KEY_PASSWORD field in the .env file with a password of your choice
2. Comment in the line of code below "Deploy without encrypted key" in deploy.js
3. Comment out the line of code below "Deploy with encrypted key" in deploy.js
