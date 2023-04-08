# Always-Be-Shoppin

## Purpose

A back end for an e-commerce site that takes a working Express.js API and is configured to use Sequelize to interact with a MySQL database.

When given a functional Express.js API, I am able to successfully add my database name, MySQL username and password to an environment variable file which allows me to connect to a database using Sequelize. Once conneted, I enter schema and seed commands and a development database is created and is seeded with test data. When a command is entered in the commandline to invoke the application, the server is started and the Sequelize models are synced to the MySQL database. When the API GET routes for Tags, Products, and Categories are opened in Insomnia, then the data for each of these routes is displayed in formmated JSON. When the API POST, PUT, and DELETE routes are tested in Insomnia, then I am able to create, update, and delete all Tags, Categories, and Products in the database successfully, which is then displayed inplayed in a formatted JSON. This was achieved by using JavaScript and npms. 

## Examples

Tag, ProductTag, Category, and Product Models:

![Screen Shot 2023-04-08 at 5 26 39 PM](https://user-images.githubusercontent.com/116764540/230743175-78c1ed33-f34f-425a-8f80-fa8f939d0d97.png)

![Screen Shot 2023-04-08 at 5 27 58 PM](https://user-images.githubusercontent.com/116764540/230743196-8ffbc176-1101-4bca-bcd4-ce42877b00cc.png)

![Screen Shot 2023-04-08 at 5 25 55 PM](https://user-images.githubusercontent.com/116764540/230743144-6c62e9ad-7866-4708-8e02-c8009ff9b51b.png)

![Screen Shot 2023-04-08 at 5 28 15 PM](https://user-images.githubusercontent.com/116764540/230743208-1b4476e9-fe64-4ea0-95c2-874fae8c81ce.png)

Tag, Category, and Product Routes:

![Screen Shot 2023-04-08 at 5 31 05 PM](https://user-images.githubusercontent.com/116764540/230743298-b122d36e-32bc-4851-8516-923397d19ed5.png)

![Screen Shot 2023-04-08 at 5 30 45 PM](https://user-images.githubusercontent.com/116764540/230743288-500c6705-d1fd-40f6-8fe9-de50a817c87b.png)

![Screen Shot 2023-04-08 at 5 31 36 PM](https://user-images.githubusercontent.com/116764540/230743315-c33c3fa4-4820-415b-af00-a9e5dadcebf7.png)

GET all Tags in Insomnia:

![Screen Shot 2023-04-08 at 5 28 50 PM](https://user-images.githubusercontent.com/116764540/230743225-d99abba4-324e-4276-bc30-a0aea0a0eb47.png)

CREATE a Category:

![Screen Shot 2023-04-08 at 5 29 38 PM](https://user-images.githubusercontent.com/116764540/230743248-e7eaa494-1ab7-4287-9650-0d01ef734bca.png)

## License

MIT License

Copyright (c) 2022 Kelley Flinn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Technologies Used

Language: JavaScript

NPM: Express.js

NPM: MySQL2

NPM: Sequelize 

NPM: dotenv


## Link to Video Demo

https://drive.google.com/file/d/1Ruz20hXmZwoQ2b249gTmzsJyG-KiWP3a/view
