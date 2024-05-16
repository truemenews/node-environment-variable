| 1. Introduction
----------------
    1.1 You need to use enviroment in node

    1.2 You can review guide flow
 


| 2. Struct
--------------

    src
    |__index.js
    |       |__use: process.env.QUOC_ENV
    |
    |
    |__.env.development
    |       |__define: QUOC_ENV="Hello Quoc in .env.development"
    |
    |__package.json
    |       |__scripts
    |           |__"dev:env": "sh -ac '. ./.env.development; npm run dev'"
    |



-----------------------


| 3. Step by step do it
-----------------------

    3.1 Clone/download node-enviroment-variable folder to your computer
        3.1.1 Download from browser
            3.1.1.1 Goto folder > D:\YourFolder\node-enviroment-variable
            3.1.1.2 you run: npm run dev:env
            3.1.1.3 You run: http://127.0.0.1:3000/ on Chrome
            3.1.1.4 You saw: "Hello Quoc in .env.development"





