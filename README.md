# E-Commerce Site
## 
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)


## Table of Contents:
<ol>
<li><a href="#description">Description</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#testing">Testing</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#questions">Questions</a></li>
<li><a href="#license">License</a></li>
</ol>

## Description:
Tasked with building the back end for an e-commerce site by modifying existing starter code.  Configured some Express.js APIs to use Sequelize to interact with a MySQL database.   Using the APIs a user can manipulate all of the data in the table.   The user can view all the information in tables, , create a new part of the table, alter an existing part of a table, or delete part of a table.

## Installation :
The application can be run in the termianl inside of your chosen coding application. It uses Javascript and Node as the languages to access it. 
The user must make sure to use the following code so that the inquirer is available to them:
```bash
npm i
```
The user then create a database by sccessing the db folder, with the schema.sql information.  Once the databse has been created, the user can use the following command to seed the database with tables and information:
```bash
node seeds
```
The application is invoked by using the following command:
```bash
node server.js
```

The application is also connected with a mySQL workbench, where there are four interrelated tables that are stored in an ecommerce database.  The database is called ecommerce_db, with the tables called category, product, tag, and product_tag.  

## Usage: 
The user will open the command terminal inside the chosen coding platform.  The user will then run node server.js inside the command line.  Then the server will be listening at localhost:3001   After running that code, the user can then view, create, delete, and alter the tables via Postman.  

The user has options to do the following things with the database: 
<ul> 
<li>View Categories</li>
<li>View One Category</li>
<li>Create a Category</li>
<li>Change a Category</li>
<li>Delete a Category</li>
<li>View Products</li>
<li>View One Product</li>
<li>Create a Product</li>
<li>Change a Product</li>
<li>Delete a Product</li>
<li>View Tags</li>
<li>View One Tag</li>
<li>Create a Tag</li>
<li>Change a Tag</li>
<li>Delete a Tag</li>
</ul>
<br>

<!-- 
### Here is the Website Walk Through:
<iframe src="https://drive.google.com/file/d/1dT3BC9Hmb9ngt6NrSiYmEZNNk15_hGIr/preview" width="640" height="480">embedded video</iframe> -->

### Here is the same video link:
<a href =https://drive.google.com/file/d/1dT3BC9Hmb9ngt6NrSiYmEZNNk15_hGIr/view>Walk Through Video</a>

## Testing:
N/A

## Contributing

Pull requests are always welcome.  When contributing to this repository, please first discuss the change you wish to make via email or issue.  
After approval, please follow the "fork-and-pull" Git workflow.
<ol>
<li>Fork the repo on GitHub</li>
<li>Clone the project to your own machine</li>
<li>Commit changes to your own branch</li>
<li>Push your work back up to your fork</li>
<li>Submit a Pull request so that we can review your changes</li>
</ol>

## Questions :

If you have any questions, feel free to reach out to me.   My email is ckhilpisch@gmail.com.

## License :

MIT License
Informataion avaiable here: 
https://opensource.org/licenses/MIT