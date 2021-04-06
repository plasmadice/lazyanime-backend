# Usage

`npm i` to install all needed dependancies
`npm start` to start the frontend

### Details

- Encrypted data is sent from the frontend to this server where it is decrypted using a key.
- Uses a version of crypto-js to encrypt data as it's sent out, and decrypt it on the server side.
- Only data stored is user's FTP client connection info (which is removed if you hit "Disconnect" or are timed out and attempt to connect.
- Official URL: https://lazyanime.com/
- Netlify URL: https://elastic-panini-7bfc59.netlify.com/

### Tech:

- Frontend - Gatsby hosted on Netlify - https://github.com/plasmadice/lazy-ftp
- Backend - Node.js hosted on Heroku - https://github.com/plasmadice/lazyanime-backend

### Future Feature list

- Download media through browser
- Optionally convert videos to mp4 to view in browser
- Credentials-store usint postgresql
- Needs more error reporting
