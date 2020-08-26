Project

1.  Node
    - Node 10.16.2 LTS

2.  Libs
    - express
    - cors
    - multer
    - nodemon
        - package.json - `"dev": "nodemon ./src/index.js"`
        - npm run dev

3.  Start
    -  Clone project [https://github.com/bucceroni/acr-cloud.git](https://github.com/bucceroni/acr-cloud.git)
    -  `npm install`
    -  `npm run dev (nodemon)` || `npm start`

4.  Test
    - File: `./test.mp4`

5.  Postman
    -  [https://www.getpostman.com/collections/2fcf4ccbd68fb94e6c02](https://www.getpostman.com/collections/2fcf4ccbd68fb94e6c02)
    -  GET : `http://localhost:5000/music`
    -  POST: `http://localhost:5000/music -> import file -> body -> form-data -> key=upFile type=file`