# ExpressRESTfulAPI
## Backend Destination APIs Architecture
![Frame 1](https://github.com/Nurtur-Capstone-Project/Nurtur-API/assets/85015643/0836c350-26fb-4006-b62a-7604e0ac9454)


## How to install

1. Install npm dependencies
```
npm install
```
2. Run prisma model
```
prisma migrate dev
```
3. Set environment variables
```
APP_URL=http://localhost
PORT=3000
SECRET_KEY=secret

DB_CONNECTION=your_type_DB
DB_HOST=your_host_DB
DB_PORT=your_port_DB
DB_NAME=your_DB_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
DATABASE_URL="${DB_CONNECTION}://${DB_USERNAME}:${DB_PASSWORD}@${DB_HOST}:${DB_PORT}/${DB_NAME}"

MAIL_SERVICE=gmail
MAIL_HOST=smtp.gmail.com
MAIL_PORT=465
MAIL_USERNAME=
MAIL_PASSWORD=
```
4. Run application
```
npm run dev
```
5. Open the application in the browser, [http://localhost:3000/](http://localhost:3000/)
## Example Test on local 
![GET_API](https://github.com/Nurtur-Capstone-Project/Nurtur-API/assets/85015643/f74920cf-d934-4136-994f-3388bd730181)
![CURRENT_API](https://github.com/Nurtur-Capstone-Project/Nurtur-API/assets/85015643/18a1bd63-4dab-4487-a715-cd0a33472795)
![LOGIN_API](https://github.com/Nurtur-Capstone-Project/Nurtur-API/assets/85015643/c7c0136b-e524-47d3-b664-793ca6261564)


