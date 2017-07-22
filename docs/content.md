AUSTIN COMMUNITY COLLEGE
CONTINUING EDUCATION

Programming For E-Commerce Websites
(24 hours)

ITSX 3016

COURSE SYLLABUS

Required Material: None

Type of Course: Short Course

Description:  This technical programming class takes the student through the design and development of an E-Commerce shopping cart system, using PHP and MySQL. Prerequisites: Introduction to E-Commerce and Introduction to Programming Languages or knowledge of computer programming in at least one language.


Evaluation: Students will be evaluated on their competency in performing a variety of
hands-on exercises created to insure the student has achieved all course objectives
through the course, and class participation. In order to grant CEU credit for a course
the students must be able to complete assessment exercises for each part of the course
given by the instructor. The instructor will validate each participant’s achievement of the
course objectives by signing and awarding individual certificates of completion.

Objectives:  
•	Describe the underlying technologies of an E-Commerce software system
•	Describe the database structure of an E-Commerce shopping cart script
•	Define basic password protection functions in PHP/MySQL
•	Explain category and product management functions of an E-Commerce system
•	Describe the HTML and PHP/MySQL code needed for checkout and Paypal integration
•	Explain the code for PHP session handling
•	Create a requirements document that describes the functionality of a medium sized E-Commerce system
•	Examine, review and document Paypal integration techniques

Rationale:  Commercialism of the World Wide Web has led to the need for programmers with the ability to write and maintain E-Commerce software. This course provides students with technical knowledge and the basic skills needed to understand complex E-Commerce software.

Course Outline:

I. Introduction to E-Commerce Programming (4 hours)

A. Concepts
B. Technologies
C. File Structure
D. MySQL Database Structure

II. Shopping Cart Back-end (4 hours)

A. Password Protection
B. Product Catalog
C. Managing Categories and Products
D. Managing Orders and Special Offers

III. Shopping Cart Front-end (4 hours)

A. Viewing Product Catalog
B. Product Search
C. Cart
D. Checkout Form and Functions (HTML and PHP)
E. Paypal Integration 

IV. Security Functions (4 hrs.)
A.	Setting up security
B.	PHP Session Handling
V. Program Requirements Document (4 hrs.)
A.	Create a Requirements Document
VI.  Final Project (4 hr.)
A.	Examine, Review and Document Paypal Integration Techniques

Students are responsible for knowing the start and end dates of the classes they take in the program. To find out the end date of your class you should go to http://continue.austincc.edu/webmaster and click on the class name to view the schedule for that class. You may also have received an emailed receipt with the start and end dates in the receipt, but if not you must go to the website above to determine the last day of class.
The class dates are also posted here in Moodle in the calendar.

All the materials for the class are listed under each topic on the main page of the course. Work your way from the first topic to the last. When you have questions, post your question on the Q & A forum.

Ask a lot of questions, that is why I am here smile


The class consists of reading course text and doing exercises. All exercises that need to be handed in for a grade are clearly marked as such.

Your grade in this class is based on assignments, and a final project grade. The assignments are marked with the maximum number of points they are worth.

Your ACC student account lets you view your grades in all classes. Always check your official grades using the ACC Online Student Services website. The grades here in my system are for my purposes only.

Some guidelines to follow while taking the class:

Please read the following before starting the course!


* My office hours are Monday through Friday from 6am to 12pm. All message board posts that are entered at night and on weekends will be answered during my office hours either the next day or the following Monday. Online Instructors do not provide telephone support, but I do have a Chat application here that we can use if you need more support.

* Extensions are only available for this class for students who have a real emergency. If you take more than one class at a time, and cannot finish the work, please don't ask for an extension.

* All questions are to be asked on the Q & A forum that is available at the top of the main course page.


* To go from page to page of the course please use the navigation buttons at the top of the pages.

* Be sure to fill out the online Student Evaluation form before the last day of class. You will find a link to the form on the Table of Contents page.


* Paper certificates can be ordered from Marcela only. Send her an email with your name, class information and mailing address after the class is over and the grades have been posted. She will have a paper certificate mailed to you.


Before you start this program, decide how you will take and organize your notes. You will not have access to the classes after the end date of the class, just as you do not continue to have access to a classroom based class after it ends! So, devise a strategy now for organizing your notes for the different classes in a way that leaves you with a working resource later in your career. Here are some recommendations:

Evernote: http://evernote.com/
Code Snipping Apps: http://speckyboy.com/2011/06/14/10-free-desktop-applications-for-managing-your-code-snippets/
Start thinking about your professional portfolio sooner, rather than later.

The account you will receive on ACC's student Web server can be used as your portfolio. Or you can use a different solution for a portfolio. This is your choice, but take some time over the course of the program to think about how you are going to display your best work to potential employers. It is much easier in the long run to do this work a little at a time, rather than trying to put something together at the very end of the program.


Some things to know about this website - this is my personal/business website, and is not part of the ACC computer systems. I use the Moodle Learning Management System, which is a large, complex LMS. The other Instructors have their own methods of delivering their classes, so always check the ACC website at http://continue.austincc.edu/webmaster to find out how to start an online class.
Enjoy!

Introduction

This course is for students with a basic knowledge of PHP and MySQL. It shows how to create a shopping cart script with PHP and MySQL, for students who have not yet dealt with the complexity of a system such as this.
Before you begin

In this shopping cart course we WILL NOT:

Describe how to design an online store from scratch
Describe how to write in PHP, install and/or configure PHP and MySQL
It is assumed that you already have basic understanding of PHP and MySQL. The object of the course is not to memorize the PHP or MySQL code, but to study the code to understand as much of this higher level code as possible. You are advised to download the script and view it using a text editor, so you can also see how a large PHP/MySQL script is laid out, and get a feeling for the size of the project. Over time you can also study sections of the code in more detail to gain a greater understanding of the program. This is unlikely to happen during a three week long class, so plan on further study after this class is over if you want to master all of the code.


We'll start by installing applications that set up a development environment for you on your local computer. Full instructions are provided by the vendors, and you should be able to install and set up the applications without any trouble. Post any questions you have in the class forum, along with detailed information about the error messages you are getting, so I can help quickly and efficiently.

After installing the needed applications we will begin exploring the PHP and MySQL code that makes up the shopping cart script. You will see database diagrams and the PHP code that makes up the script. You will also install the script on your computer to get a first hand view of the application in action. By the end of the course you will understand what goes into programming a small E-Commerce system. In addition you'll learn how to use very important tools, such as PHPMyAdmin for MySQL database creation. These skills will be a valuable addition to your skills as a Webmaster and Web Developer.
Shop-Script FREE

Shop-Script FREE is a relatively small shopping cart system with basic functionality needed for an online store. It is being used here because of this simplicity.

The Shop Script Free PHP tutorial was written by Vladimir V. Tuporshin. Proceed to the next page to download the script files...

Server side scripting languages, such as PHP, require a Web Server to operate. This section will help you install and configure a Web Server, along with the languages and tools you need to develop and run PHP/MYSQL scripts on your home computer.

The XAMPP bundle, found at https://www.apachefriends.org/index.html was chosen because it includes distributions for both Mac and Windows machines. Windows users can alternately use the EasyPHP distribution, which is detailed in the Shop Script Free User Guide that is included with the shopping cart system download.

XAMPP and EasyPHP both include the Apache Web Server, PHP, the PHPMyAdmin application and a MySQL database. Once installed, you will have your own Web Server on your computer, and will be able to run PHP/MySQL applications without needing a separate Web Hosting account.

Once you install and configure XAMPP or EasyPHP you will then download and install the shopping cart software.

Basic online store concepts

The online store consists of two sections:

Front end (storefront):
This is a public part of your system where visitors can browse the products catalog, add items to the shopping cart and place orders.
Back end (administrative mode):
This is a section of your store which should be restricted from public access. The back end provides tools for managing the products catalog, viewing customer orders, configuring store settings, etc.
There could be hundreds of e-commerce features supported by a certain online store, but here we will cover core facilities required to start selling online:

Product management
Shopping cart
Order management

Other facilities, such as a customer registration system, credit card processing, shipping quotes with UPS, FedEx and other carriers, discounts, gift certificates and other features are important, but are additional e-commerce features. They help you increase sales once you have already started selling online, but they are not necessary for starting an online business.


We will review each of core store facilities one by one. We will start with the product catalog management, then the shopping cart engine (the ability to add products to cart) and then the checkout facility with PayPal Website Payments Standard integration.

Technologies

To better understand this tutorial you will require to have basic knowledge of the following technologies:

PHP (www.php.net)
Version 4.1.0 or higher

PHP

MySQL (www.mysql.com)
Version 3.23.x or higher

MySQL

Smarty template engine (smarty.net)

Smarty is a powerful open source template engine. It offers comprehensive tools to separate PHP source files from HTML design templates. If you design your PHP store using Smarty, it will allow you to easily customize its look & feel in minutes.

The latest version of Smarty can be downloaded from the Smarty website. However, if you have already downloaded Shop-Script FREE, you do not need to download the Smarty engine separately, since it is already included in the Shop-Script FREE archive.
Smarty is distributed under the LGPL.

File structure

files

After unzipping the shopping cart download, take a look at the directory structure of the folders included in the system:


cfg: This folder contains store configuration files, such as the MySQL database connection settings, and the administrator login and password (md5).
This folder must be protected from public HTTP access!
If you use the Apache Web server, folder protection is performed using the .htaccess files, which are already included in the archive.


If you use some other Web server software, e.g. IIS, please refer to its manual and support resources to learn more about protecting folders from public access.



extra: this folder contains auxiliary routines, for example, the administrator's password reminder.


images: This folder holds the shopping cart images, e.g. add to cart button, company logos, etc.


includes: this folder contains many files responsible for different shopping cart functions, e.g. product detailed information page, shopping cart info page, administrative mode screens, etc.


All files in this folder are automatically included and executed by the core index.php script when you run your online store.


includes/database: this folder contains files with the definitions of the database functions. The file mysql.php, defines calls to MySQL functions, e.g. mysql_query(), mysql_connect().


If you would like to use a database system other than MySQL (e.g. mSQL, MS SQL Server, Oracle, etc.), you may edit this file and update the functions calls (e.g. replace mysql_ prefix with msql_, mssql_). For different database management systems, changing certain SQL queries may also be required (e.g. installation queries).


languages: language files are stored in this folder. To make the store interface multilingual we put definitions of all language phrases in a separate file. This gives the ability for the store administrator to easily translate the store interface in a preferable language and/or to correct spelling of individual phrases depending on store specificity.


products_pictures: product images and category thumbnails are uploaded and stored in this folder.


smarty: Smarty source files.


templates: HTML template files (both storefront and back end).


templates_c: this folder is used for Smarty template compilation (temporary files are created in this folder by the Smarty engine).


The root folder of Shop-Script FREE archive contains core files which are responsible for online store functions:

index.php is the core front end script; the whole storefront operates through this file
admin.php operates the shopping cart back end
category.php - product category management tools
products.php - product management tools

Database Exercise

Now that you have seen a diagram of the database tables you should run PHPMyAdmin, and look at the MySQL database from that perspective. You can examine the 5 tables that make up the database, and look at the data types allowed for each variable in the tables.

Expanding the functionality of the system might include having to add more tables to the database to hold data needed for any custom modifications.

Take screen shots of the phpMyAdmin screen on your computer, and upload the image below...

Upload your document here - maximum of 3 files.

Back-end 

Password protection: administrative mode

For simplicity here we assume that there is only one administrative mode access level, in other words, there will be only one user who has full access to all back end functions. Thus there will be only one combination of login and password allowing to access back end.


In Shop-Script FREE administrative mode is accessible through admin.php script.
We use sessions to protect the back end from unauthorized access. When someone runs admin.php, the script checks whether the authorization form was passed or not:

<?php
//CHECK #1
//Check whether or not session data match data in the configuration file.
//In $_SESSION variable we store administrator Login name and MD5-hashed password.
if ((isset($_SESSION["log"]) && isset($_SESSION["pass"])) &&
(strcmp($_SESSION["log"], ADMIN_LOGIN) ||
strcmp($_SESSION["pass"], ADMIN_PASS)))
{ //information does not match - unset session variables
unset($_SESSION["log"]);
unset($_SESSION["pass"]);
}

//CHECK #2
//in case of unauthorized access redirect customer to authorization form
if (!isset($_SESSION["log"]) || !isset($_SESSION["pass"])) //unauthorized
{
//show authorization form
header("Location: access_admin.php");
}
?>

Here the ADMIN_LOGIN and ADMIN_PASS (in CHECK #1) are constants which define a combination of administrator login and password. These constants are defined during Shop-Script FREE script installation and saved in the file connect.inc.php located in protected cfg/ folder.


To enhance security, ADMIN_LOGIN is stored and saved in session variables in BASE64 (encoded with base64_encode() function), and ADMIN_PASS is stored in this file and in sessions as an MD5 hash ( function md5() ).


Variable $_SESSION["log"] indicates whether the visitor input correct the login/password and has been authorized as an administrator or not.


CHECK #1 (see source code fragment above) will unset $_SESSION["log"] in case it does not match ADMIN_LOGIN information in the configuration file.
If $_SESSION["log"] variable is not defined, CHECK #2 will redirect the customer to access_admin.php page.


When the user inputs login and password in this form, the information is saved into a $_SESSION array and the user is redirected to admin.php to pass CHECKs #1 and #2:


<?php
if (isset($_POST["authorize"]))
{
if (!strcmp(base64_encode($_POST["login"]), ADMIN_LOGIN) &&
!strcmp(md5($_POST["password"]), ADMIN_PASS))
{ //login ok
$_SESSION["log"] = ADMIN_LOGIN;
$_SESSION["pass"] = ADMIN_PASS;
//redirect to the admin interface
header("Location: admin.php");
}
else
$errorStr = "Incorrect login and/or password";
}
?>

If the correct login information is provided, the customer is granted access to the back end resources and the back end homepage.

Designing the products catalog - database structure

To make the products catalog user-friendly, we create a category-based product catalog with unlimited category nesting, with the following features:

Category list is stored in a separate database table CATEGORY.
Product list is stored in a single database table PRODUCT.
A single product can be placed to a certain category.
Category nesting is unlimited.
Let us review these issues one by one:


dbcat
The category list is stored in the CATEGORY table with the following structure:

Here categoryID is an integer with an auto increment primary key, which indicates a category.Other fields contain information about the category, e.g. name, description and thumbnail.

products_count and products_count_admin columns contain information on how many products are there in a certain category.

products_count indicates a number of products within the category and all its child categories - this number of products is shown in the storefront to customers to make navigation easier.

products_count_admin shows how many products are there in the current category, excluding child categories, and this information is shown in the back end. These fields are updated each time you add or delete products.

Product list is stored in the PRODUCT table with the following structure:

prod 



productID is an integer with an auto increment primary key. Other columns contain product information, e.g. product name, stock information, enabled/disabled for sale, description.

categoryID column in the PRODUCT table is a foreign key. For example, if "mp3-players" category's categoryID is 536, and "Apple iPod" product record's categoryID equals 536, this means that "Apple iPod" appears in the "mp3 players" category. If the categoryID equals zero (0), the product does not belong to any category.

Category nesting.
To implement unlimited category nesting we add a parent column to the CATEGORY table. This column stores the categoryID of a certain category's parent category.
If a parent field equals zero (0), this is a root category.

For example, for three categories:

The first categoryID = 1, parent = 0 (which means this is a root category)
The second categoryID = 2, the third categoryID = 3


cat-tree 

Viewing the product catalog and category tree:
Product catalog management is one of the core tools of store's back end.

As described earlier, category nesting is unlimited. To implement this we use a recursive function fillTheCList (recursive means that this function calls itself within its body), which saves the category list in an array, and displays it using Smarty templates. Here is PHP source fragment (includes/admin/sub/catalog_products_categories.php file):

<?php

function fillTheCList($parent, $level) //completely expand category tree and save it into array. Here $parent is currently processed category,and $level indicates category's sublevel:0 for root (core) categories, 1 for their subcategories, etc.
{
//select all subcategories of currently processed category
$q = db_query("SELECT categoryID, name, products_count, products_count_admin, parent FROM CATEGORY WHERE categoryID<>0 and parent=$parent ORDER BY name") or die (db_error());
$a = array(); //save fetched results into this array
//now process fetched results (subcategories)
while ($row = db_fetch_row($q))
{
//add 'level' information to subcategory details
$row[5] = $level;
//add subcategory to $a array
$a[] = $row;
//now recurrently call this function again to process all child categories
//of current category and save results to $b array
$b = fillTheCList($row[0], $level+1);
//add $b to the end of $a
for ($j=0; $j < count($b); $j++)
{
$a[] = $b[$j];
}
}
return $a;

} //fillTheCList

?>

Calling the function:
 $categories = fillTheCList(0,0); 
will save the expanded categories tree into the $categories array.
This array is displayed using Smarty templates (templates/tmpl1/admin/catalog_products_categories.tpl.html):


<table>

{section name=i loop=$categories}

<tr>

<td>
{section name=j loop=$categories[i].level max=$categories[i].level} {/section}
<a href="admin.php?dpt=catalog&sub=products_categories&categoryID={$categories[i].categoryID}">{$categories[i].name}</a>
</td>
<td>({$categories[i].products_count})</td>

<td align="right">
<font color="red">[</font>

<a class="small" href="javascript:open_window('category.php?c_id={$categories[i].categoryID}',400,400);">edit</a>

<font color="red">]</font>
</td>

</tr>

{/section}

</table>
Viewing the product list:

Viewing products is easy because they are stored in the PRODUCT table without any hierarchical structure. We only fetch products from the current category:


SELECT productID, name, customers_rating, Price, in_stock, picture, big_picture, thumbnail, items_sold, enabled, product_code FROM PRODUCT WHERE categoryID=`$current_categoryID` ORDER BY name;



We save the result to the $products array and present them using Smarty:


{if $products_count eq 0}

<p align="center">{$smarty.const.STRING_EMPTY_CATEGORY}</p>

{else}

<form action="admin.php" method="POST">

<table border="1" width="90%">

<tr>

<td>{$smarty.const.ADMIN_ENABLED}</td>
<td>{$smarty.const.ADMIN_PRODUCT_CODE}</td>
<td>{$smarty.const.ADMIN_PRODUCT_NAME}</td>
<td>{$smarty.const.ADMIN_PRODUCT_RATING}</td>
<td>{$smarty.const.ADMIN_PRODUCT_PRICE}, {$currency_iso_3}</td>
<td>{$smarty.const.ADMIN_PRODUCT_INSTOCK}</td>
<td>{$smarty.const.ADMIN_PRODUCT_PICTURE}</td>
<td>{$smarty.const.ADMIN_PRODUCT_BIGPICTURE}</td>
<td>{$smarty.const.ADMIN_PRODUCT_THUMBNAIL}</td>
<td>{$smarty.const.ADMIN_PRODUCT_SOLD}</td>
<td> </td>
<td> </td>

</tr>

{section name=i loop=$products}

<tr>
<td align="center">
<input type="checkbox" name="enable_{$products[i][0]}" {if $products[i][9] eq 1}value="on" checked{else}value="off"{/if}>
</td>

<td>
<a href="javascript:open_window('products.php?productID={$products[i][0]}',550,600);">{$products[i][10]}</a>
</td>

<td>
<a href="javascript:open_window('products.php?productID={$products[i][0]}',550,600);">{$products[i][1]}</a>
</td>

<td align="right">{$products[i][2]}</td>

<td align="center">
<input type=text name="price_{$products[i][0]}" size="5" value={$products[i][3]}>
</td>

<td align="center">
<input type="checkbox" name="instock_{$products[i][0]}" size="5"{if $products[i][4]>0} checked{/if}>
</td>

<td align="center">
{if $products[i][5] ne ""}{$smarty.const.ANSWER_YES}{else}{$smarty.const.ANSWER_NO}{/if}
</td>
<td align="center">
{if $products[i][6] ne ""}{$smarty.const.ANSWER_YES}{else}{$smarty.const.ANSWER_NO}{/if}
</td>
<td align="center">
{if $products[i][7] ne ""}{$smarty.const.ANSWER_YES}{else}{$smarty.const.ANSWER_NO}{/if}
</td>

<td align="right">{$products[i][8]}</td>

<td align="center">
{if $products[i][5] ne ""}
<a href="admin.php?dpt=catalog&sub=special&new_offer={$products[i][0]}"><img src="images/admin_special_offer.gif" border="0" alt="{$smarty.const.ADMIN_ADD_SPECIAL_OFFERS}"></a>
{else}
{/if}
</td>

<td>
<a href="javascript:confirmDelete({$products[i][0]}, '{$smarty.const.QUESTION_DELETE_CONFIRMATION}', 'admin.php?dpt=catalog&sub=products_categories&categoryID={$categoryID}&terminate=');"><img src="images/remove.jpg" border="0" alt="{$smarty.const.DELETE_BUTTON}"></a>
</td>

</tr>

{/section}

</table>

<input type="hidden" name="categoryID" value="{$categoryID}">
<input type="submit" value="{$smarty.const.SAVE_BUTTON}">

</form>

{/if}
Managing products & categories:

To edit a certain category or product, the administrator clicks the appropriate "Category edit" or "Product name" link.

Adding / editing / deleting product categories:


This form manages the category name, description, thumbnail and position in the category hierarchy:


cat-form




<form enctype="multipart/form-data" action="category.php" method="POST">

<table width="100%" border="0">

<tr>
<td align="right">
Parent:</td>
<td>
<select name="parent">
<option value="0">Root</option>
<option value="4">Sample category 1</option>
<option value="20"> Child category 1</option>
<option value="76"> Child category 2</option>
< all categories are shown in this select box >
</select>
</td>
</tr>

<tr>
<td align="right">Category name:</td>
<td><input type="text" name="name" value="" size=13></td>
</tr>

<tr>
<td align="right">Logo:</td>
<td><input type="file" name="picture"></td>
</tr>

<tr>
<td> </td>
<td>
(picture not uploaded)</td>
</tr>

<tr>
<td align="right">Description<br>(HTML)</td>
<td><textarea name="desc" rows="7" cols="22"></textarea></td>
</tr>

</table>

<p align="center">
<input type="submit" value="Save">
<input type="hidden" name="save" value="yes">
<input type="button" value="Cancel" onClick="window.close();">
</p>

</form>
Adding a category:

The following PHP is executed when the form is submitted, saving the category in the database (category.php):


<?php

if (isset($_POST["save"]) && $_POST["name"])
//save changes
{
db_query("INSERT INTO CATEGORY
(name, parent, products_count, description, picture, products_count_admin) VALUES
('".$_POST["name"]."',".((int)$_POST["parent"]).",0,'".$_POST["desc"]."','',0);"
) or die (db_error());
}

?>
Editing category details:

The administrator uses the same form as when adding a category.
The only difference is that in this case we add a hidden "categoryID" field to the form to indicate that clicking the "Save" button should update the existing category details, but not add a new one (category.php):


<?php

if (isset($_POST["save"]) && strlen($_POST["name"])>0)
//save changes. Note that 'category name' is mandatory field - if it is not filled in, category will not be saved in the database
{

//if category is moved to any of its subcategories -
//it is necessary to lift all of its subcategories one level up

if (category_Moves_To_Its_SubDirectories($_POST["must_delete"], $_POST["parent"]))
{
//lift up is 'child' required

//get parent ID
$q = db_query("SELECT parent FROM CATEGORY WHERE categoryID<>0 and categoryID='".$_POST["must_delete"]."'") or die (db_error());
$r = db_fetch_row($q);

//lift up
db_query("UPDATE CATEGORY SET parent='$r[0]' WHERE parent='".$_POST["must_delete"]."'") or die (db_error());

//move edited category
db_query("UPDATE CATEGORY SET name='".str_replace("<","&lt;",$_POST["name"])."', description='".$_POST["desc"]."', parent='".$_POST["parent"]."' WHERE categoryID='".$_POST["must_delete"]."'") or die (db_error());

}
else //just move the category
{
db_query("UPDATE CATEGORY SET name='".str_replace("<","&lt;",$_POST["name"])."', description='".$_POST["desc"]."', parent='".$_POST["parent"]."' WHERE categoryID='".$_POST["must_delete"]."'") or die (db_error());
}

if (isset($_FILES["picture"]) && $_FILES["picture"]["name"]) //upload category thumbnail
{

//old thumbnail
$q = db_query("SELECT picture FROM CATEGORY WHERE categoryID='$pid' and categoryID<>0") or die (db_error());
$row = db_fetch_row($q);

//upload new thumbnail
$picture_name = str_replace(" ","_", $_FILES["picture"]["name"]);
if (!move_uploaded_file($_FILES["picture"]["tmp_name"], "./products_pictures/$picture_name")) //failed to upload
{
echo "<center><font color=red>".ERROR_FAILED_TO_UPLOAD_FILE."</font>\n<br><br>\n";
}
else //update information in the database
{
db_query("UPDATE CATEGORY SET picture='$picture_name' WHERE categoryID='$pid'") or die (db_error());
}

//remove old picture...
if ($row[0] && strcmp($row[0], $picture_name) && file_exists("./products_pictures/$row[0]"))
unlink("./products_pictures/$row[0]");

}
}

?>
Deleting categories:

When clicking the "Delete" button for a certain category, the following actions are performed:

All products from this category are moved to Root folder.
To do this we only have to execute the following SQL-query:

UPDATE `PRODUCT` SET categoryID=`0` WHERE categoryID=`$categoryID_to_delete`;

Delete the category thumbnail using the PHP function unlink()
Delete the category record from the `SS_categories` table:

DELETE FROM `CATEGORY` WHERE categoryID=`$categoryID_to_delete`;

Repeat steps 1, 2 and 3 for all child categories of the category that has been deleted.

Adding / editing / deleting products:

This form allows managing the product name, descriptions, images, etc.
This is the form and its HTML code (products.php):


prod-form



<form enctype="multipart/form-data" action="products.php" method="POST">

<table width="100%" border="0" cellpadding="3" cellspacing="0">

<tr>
<td align="right">Parent:</td>
<td>
<select name="categoryID">
<option value="0">Root</option>
<option value="4">Sample category 1</option>
<option value="20"> Child category 1</option>
<option value="76"> Child category 2</option>
< all categories are shown in this select box >
</select>
</td>
</tr>

<tr>
<td align="right">Product name</td>
<td><input type="text" name="name" value=""></td>
</tr>

<tr>
<td align="right">Product code</td>
<td><input type="text" name="product_code" value=""></td>
</tr>


<tr>
<td align="right">Price, USD<br>(number only):</td>
<td><input type="text" name="price" value=0></td>
</tr>

<tr>
<td align="right">List price, USD<br>(number only):</td>
<td><input type="text" name="list_price" value=0></td>
</tr>

<tr>
<td align="right">In stock:</td>
<td><input type="checkbox" name="in_stock" checked></td>
</tr>

<tr>
<td align="right">Picture</td>
<td><input type="file" name="picture"></td>
<tr><td></td><td>
(picture not uploaded)</td>
</tr>
<tr>
<td align="right">Thumbnail</td>
<td><input type="file" name="thumbnail"></td>
<tr><td></td><td>
(picture not uploaded)</td>
</tr>
<tr>
<td align="right">Enlarged picture</td>
<td valign="top"><input type="file" name="big_picture"></td>
<tr><td></td><td valign="top">
(picture not uploaded)</td>
</tr>


<tr>
<td align="right">Description<br>(HTML):</td>
<td><textarea name="description" rows="15" cols="40"></textarea></td>
</tr>

<tr>
<td align="right">Brief description<br>(HTML):</td>
<td><textarea name="brief_description" rows="7" cols="40"></textarea></td>
</tr>

</table>


<p><center>
<input type="submit" value="Save">
<input type="hidden" name="save_product" value="0">
<input type="button" value="Cancel" onClick="window.close();">
</center></p>
</form>
Adding products:

Clicking the "Save" button executes the following SQL query to save the product into the database (products.php):

INSERT INTO `PRODUCT` (categoryID, name, description, customers_rating, Price, in_stock, customer_votes, items_sold, enabled, brief_description, list_price, product_code) VALUES ('".$_POST["categoryID"]."','".$_POST["name"]."','".$_POST["description"]."', 0, '".$_POST["price"]."', ".$instock.", 0, 0, 1, '".$_POST["brief_description"]."', '".$_POST["list_price"]."', '".$_POST["product_code"]."');

Editing product details:

We use the same form as above, but in this case we pass the productID along with the form to indicate that clicking the "Save" button should update the existing product details, but not add a new one (products.php):



<?php

if (!isset($_POST["price"]) || !$_POST["price"] || $_POST["price"] < 0)
$_POST["price"] = 0; //price can not be negative

if (!isset($_POST["name"]) || trim($_POST["name"])=="") $_POST["name"] = "not defined";

$instock = (isset($_POST["in_stock"])) ? 1 : 0;

if ($_POST["save_product"]) { //if $_POST["save_product"] != 0 then update item

//delete old product photos if they're being replaced
$q = db_query("SELECT picture, big_picture, thumbnail FROM ".PRODUCTS_TABLE." WHERE productID='".$_POST["save_product"]."'") or die (db_error());
$row = db_fetch_row($q);

//generating query

$s = "UPDATE ".PRODUCTS_TABLE." SET categoryID='".$_POST["categoryID"]."', name='".$_POST["name"]."', Price='".$_POST["price"]."', description='".$_POST["description"]."', in_stock=".$instock.", customers_rating='".$_POST["rating"]."', brief_description='".$_POST["brief_description"]."', list_price='".$_POST["list_price"]."', product_code='".$_POST["product_code"]."'";

$s1 = "";

//old pictures?
if (isset($_FILES["picture"]) && $_FILES["picture"]["name"])
{
//delete old picture
if ($row[0] && file_exists("./products_pictures/".$row[0]))
unlink("./products_pictures/".$row[0]);
}
if (isset($_FILES["big_picture"]) && $_FILES["big_picture"]["name"])
{
//delete old picture
if ($row[1] && file_exists("./products_pictures/".$row[1]))
unlink("./products_pictures/".$row[1]);
}
if (isset($_FILES["thumbnail"]) && $_FILES["thumbnail"]["name"])
{
//delete old picture
if ($row[2] && file_exists("./products_pictures/".$row[2]))
unlink("./products_pictures/".$row[2]);
}

}

?>
Deleting products:

When clicking the "Delete" button for a certain product it is deleted from the database using following SQL query:


DELETE FROM `PRODUCT` WHERE productID=`$productID_to_delete`;

Managing orders

We will review the basic facility of viewing the orders list and the ability to delete orders.


orders

To learn how orders do get into ORDER database table please read the "Checkout process" description.


The order list can be easily fetched from the ORDER table using following SQL query:


SELECT orderID, order_time, cust_firstname, cust_lastname, cust_email, cust_country, cust_zip, cust_state, cust_city, cust_address, cust_phone FROM `ORDER` ORDER BY `orderID`;



This query will return all orders sorted by the orderID field (ORDER table primary key) in ascending order. Now we can easily show all fetched orders on a web page using Smarty.


When showing the order list make sure to transform the orders data to a safe form by replacing < and > symbols to &lt; and &gt; accordingly. Please refer to the Security page for more details.


If you would like to delete a certain order, simply click the "Delete" button in the order record, and the following SQL query will be executed:


DELETE FROM `ORDER` WHERE orderID=`$orderID_to_delete`;



Of course, there could be more advanced features for order management, e.g. order statuses, invoices, shipping labels and more. Usually such functions are supported in commercial shopping cart software, because they are far more difficult to implement and require advanced PHP programming skills.

Front-end

Displaying the products catalog to customers:

Presenting the products catalog:


To navigate in the products catalog the customer can use the category tree.


When clicking a certain category link, the customer is directed to

index.php?categoryID=X

where X is the integer ID of the category, e.g. 5.

The script should perform the following operations if the categoryID parameter is passed:

Validates the categoryID parameter value and transforms it to an integer number to avoid SQL injections vulnerability.
Searches for a requested category in the database.
If the category was not found in the database, the visitor is redirected to storefront homepage (index.php).
If the category was found, the visitor is shown a list of products within the selected category with the ability to order certain products.
cat


A list of products within the current category can be easily fetched from the database using following SQL query:


SELECT * FROM `PRODUCT` WHERE categoryID = `$current_categoryID`;

Clicking a certain product link brings the visitor to the detailed product information page - index.php?productID=XX.


XX indicates unique integer ID of the product.
Just like with the category, the script should validate the productID parameter value, search for a product in the database, and then fetch all required information from the database and present it to the visitor:


Clicking the "Add to cart" button will add this product to the customer's shopping cart.

Products search

The product search function requires only a small search form and executing a single SQL-query.


This is the form HTML template (search_form.tpl.html):

<form action="index.php" method="get">

<tr>
<td>Search:</td>
<td><input type="text" name="searchstring" size="7" value=""></td>
<td><input type="image" border="0" src="images/search.gif"></td>
</tr>

</form>

When this form is submitted, the product search is performed using an SQL query (includes/search_simple.php):

SELECT * FROM `PRODUCT` WHERE Enabled=1 AND (name LIKE '%".$_GET["searchstring"]."%' OR description LIKE '%".$_GET["searchstring"]."%' OR brief_description LIKE '%".$_GET["searchstring"]."%');

This query will return a list of products matching the search criteria.

Please note that the query presented above is just an example. You should keep in mind that you have to validate input $_GET data before executing a query (with mysql_escape_string() functions, for example). Please refer to the Security section for more details.


If you would like to highlight the search criteria when displaying search results you can simply add Smarty modifiers to the product templates (here is an example with the product name - this technique makes the search string bold):


{$product_name|replace:"$searchstring":"<b>$searchstring</b>"}

The search results highlighting is not implemented by default, but you can easily add this functionality by editing the product_brief.tpl.html and product_detailed.tpl.html template files.


Please note that the product search functionality is a bit more complex - see includes/search_simple.php source file for more information.

Shopping cart:

To implement a virtual shopping cart function we use sessions. For each visitor a new session is initiated. We can use a simple array to store the product that the customer has added to his shopping cart.


If a visitor clicks the "Add to cart" button, the following PHP code is executed (includes/shopping_cart.php):


<?php

if (isset($_GET["add2cart"]) && (int)$_GET["add2cart"]>0) //add product to cart with productID=$add2cart
{
$q = db_query("select in_stock from ".PRODUCTS_TABLE." where productID='".(int)$_GET["add2cart"]."'") or die (db_error());
$is = db_fetch_row($q); $is = $is[0];

//$_SESSION['gids'] contains product IDs
//$_SESSION['counts'] contains item quantities ($_SESSION['counts'][$i] corresponds to $_SESSION['gids'][$i])
//$_SESSION['gids'][$i] == 0 means $i-element is 'empty' (does not refer to any product)
if (!isset($_SESSION["gids"]))
{
$_SESSION["gids"] = array();
$_SESSION["counts"] = array();
}
//check for current product in visitor's shopping cart content
$i=0;
while ($i<count($_SESSION["gids"]) && $_SESSION["gids"][$i] != $_GET["add2cart"]) $i++;
if ($i < count($_SESSION["gids"])) //increase current product's item quantity
{
$_SESSION["counts"][$i]++;
}
else //no such product in the cart - add it
{
$_SESSION["gids"][] = $_GET["add2cart"];
$_SESSION["counts"][] = 1;
}
}

?>

Here we use two arrays to store the products in the shopping cart:


$_SESSION["gids"] contains productID values of the products which are currently in the customer's shopping cart.


$_SESSION["counts"] contains item quantity information - how many items of a certain product are in the customer's cart.



Here is how you remove a product from the cart:


<?php

if (isset($_GET["remove"]) && (int)$_GET["remove"] > 0) //remove product with productID == $remove
{
$i=0;
while ($i<count($_SESSION["gids"]) && $_SESSION["gids"][$i] != (int)$_GET["remove"])
$i++;
if ($i<count($_SESSION["gids"]))
$_SESSION["gids"][$i] = 0;
}

?>

To remove all products from the cart execute this code:


<?php
unset($_SESSION["gids"]);
unset($_SESSION["counts"]);
?>

Displaying shopping cart content:

To display the shopping cart content to the customer, we load the cart content from the session to the Smarty variable, and then it can be presented to the customer using this Smarty template (shopping_cart.tpl.html):


{section loop=$cart_content name=i}
<tr>
<td>{if $cart_content[i].product_code ne ""}[{$cart_content[i].product_code}] {/if}{$cart_content[i].name}</td>
<td><input type="text" name="count_{$cart_content[i].id}" size="5" value="{$cart_content[i].quantity}"></td>
<td>{$cart_content[i].cost}</td>
<td>
<a href="index.php?shopping_cart=yes&remove={$cart_content[i].id}"><img src="images/remove.jpg" border="0" alt="{$smarty.const.DELETE_BUTTON}"></a>
</td>
</tr>
{/section}
Checkout

The shopping cart content is stored in the session until the visitor closes his/her browser window (in this case session is terminated) or places an order (we clear shopping cart content stored in session).

Checkout

The purpose of the checkout process is to collect customer information, save the order to the database and email the store administrator an order notification.

Collecting customer information:

The simplest checkout process consists of only one step - the customer is only prompted to enter his contact information and click the "Place order!" button.

When pushing the "Proceed to checkout" button on shopping cart page, the customer is redirected to index.php?order_custinfo=yes page:

Integrating PayPal:

In order to add the PayPal payment option to your store you need to add a PayPal "Buy now!" button to the last page of the checkout process (the page that is shown after the order has been saved to the database).



<form action="https://www.paypal.com/cgi-bin/webscr" method="POST">

To pay with PayPal please click on the PayPal icon below:

<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="your@paypal.email">
<input type="hidden" name="item_name" value="Order #{$order_id}">
<input type="hidden" name="amount" value="{$order_amount}">
<input type="hidden" name="currency_code" value="{$currency_iso_3}">
<input type="image" name="submit" src="http://images.paypal.com/images/x-click-but01.gif" alt="Pay with PayPal">

</form>


Nothing else is required - you are now ready to accept PayPal payments.

A detailed Integration Guide with the payment form specifications can be found on the PayPal website:


https://www.x.com/developers/paypal/documentation-tools/paypal-payments-standard/integration-guide/cart_upload

Security issues:

When designing an e-commerce website you should pay attention to the security issues and vulnerability of your website to hacker attacks.

Website security is a very big subject so we will discuss a few of the most important:

SQL-injections

SQL injection is the name for a general class of attacks that can allow users to retrieve data, alter server settings, or even take over your server. SQL injection is not an SQL Server problem, but a problem with improperly written applications.

Here is it how it works. Assume that you have a getproduct.php script which shows product information when you pass the productID parameter to the script:

<?php

/* ... database connection section ... */

$q = mysql_query("SELECT * FROM `PRODUCT` WHERE productID=".$_GET["productID"])
or die (mysql_error());
$row = mysql_fetch_row($q);

...

?>

Running getproduct.php?productID=5 will fetch a product from the database with the productID equal to 5, and show its information.

But what happens if you run getproduct.php as:
getproduct.php?productID=5;show tables;
getproduct.php?productID=5;delete from some_important_table;
In this case the output is only limited by the skills of the hacker.

How do you protect yourself from SQL injections? The answer is proper data validation. Before executing an SQL query you must make sure it is safe to execute. Check the input data and transform it to a safe form if required.

For example, where an input variable is assumed to be an integer number, don't hesitate to add the following line before running an SQL query:

$input_variable = (int) $input_variable;

For transforming string data you can use the mysql_escape_string() function:

$input_variable = mysql_escape_string( $input_variable );

When dealing with string data, transform it into safe mode according to the magic_quotes_gpc and magic_quotes_runtime values defined in the PHP settings on your server. Be careful with escape symbols such as ', ", .

Cross side scripting (XSS)

Cross site scripting (XSS) is a type of computer security exploit where information from one context, where it is not trusted, can be inserted into another context, where it is. From the trusted context, an attack can be launched.

Here is an example:
When placing an order a customer inputs following string into the `Name` field of the checkout form:

Hack <script>window.alert('You`ve been hacked!');</script> attempt!

After the order is saved into the database, the administrator verifies the order information in the back end. When viewing the order details, the administrator will see Hack attempt! in the `Customer name` field information and the alert window.

alert 

Controlling XSS attempts is easy. You should transform data to a safe form before outputting it, namely replace all potentially insecure symbols. I encourage you to always replace < and > with &lt; and &gt; accordingly.

Make data validation and proper customization a rule when designing web applications. This is very important!

Creating downloadable CSV files using PHP

The "idea" is to allow the shop owner to download data from the orders database as a comma separated file that he/she can open in Excel.

CSV (comma-separated values) is the most widely supported format for transferring tabular data between applications. The ability to export data in CSV format is a useful feature for many programs, and is becoming increasingly common in web applications. This page explains how to use PHP to create CSV files, and how to ensure that your visitor’s browser offers to download the file instead of displaying it.

The code

The following code assumes that the data to be exported are stored in a MySQL database, but it can easily be modified to work with other data sources, and hence serves as a general template:

csv


The string ‘data.csv’ on line 3 is the name the browser will suggest for the downloaded file. The array literal on line 9 contains the column headings; this line should be omitted altogether if you do not wish to include column headings. The strings on lines 12 to 14 should be changed to the appropriate connection parameters and query string for your database. In a real application the database connection parameters should be defined as constants in a separate configuration file.

How it works

The code needs to tell the browser that it is producing a CSV file and that the file should be offered for download, rather than displayed in the browser. Line 2 produces an HTTP header telling the browser that the MIME type of the content is text/csv, the official MIME type for CSV files.

Line 3 produces a ‘Content-Disposition’ header. The Content-Disposition header was defined in RFC 2183 and was intended to be used in e-mails, but was also adopted by web browsers. In web browsers the value ‘attachment’ instructs the browser to offer the file for download with the suggested name — the file might otherwise be displayed in the browser window as if it were normal text.

PHP 5.1 introduced the fputcsv function, which outputs an array of data to a file pointer as comma-separated values. Because fputcsv can only write to file pointers, line 6 opens the output stream as if it were a file. Line 9 then outputs column headers, while line 17 loops over the rows of data and outputs them.

Keep in mind that the final project is a research project as well as a coding project. That mean that all of the code needed for the modification may not be right here on this page, and will require research.

MySQLi vs. MySQL

PHP 7 introduces new MySQLi functions that replace the old MySQL database query functions. Luckily, a smart programmer wrote a PHP class that replaces the old functions with the newer versions. All that is needed is to include the PHP class file in your script. (Instructions are available at the download site). Download the PHP class from https://www.phpclasses.org/package/9199-PHP-Replace-mysql-functions-using-the-mysqli-extension.html
Resources:


http://stackoverflow.com/questions/16251625/how-to-create-and-download-a-csv-file-from-php-script

http://www.php.net

Final Project 

Web merchants rely on software to provide both user facing functionality (ordering) and financial management. Shopping cart systems have evolved to include accounting functions, or provide hooks into external accounting systems. This project will add functionality to the shopping script to let merchants download order data in CSV format. 

The next section (Process) will outline the assignment details. Your class is three weeks long. Plan on scheduling the chat sessions with your team ASAP!. 

You’ll be formed into one group. 
Modify the admin area of the PHP Shop Script to display a button for the merchant to use to download a CSV file of order data. The file should include the item ordered, date ordered, quantity ordered, and the customer name. You do not have to search for any specific dates in the database, and can have the script simply download all orders on file.
Each student will hand in a .zip file that contains screen shots of the new functionality in action. 

You will be graded on your contribution to the success of the team, as well as your individual deliverables.

A "failed" project does not necessarily mean a failing grade. This is a learning experience. If you find, after working feverishly, that you cannot get the code to work correctly, you still have a complete project, as long as you hand in the deliverables.
I strongly urge you to conduct your first chat meeting as soon as possible after the class starts. The purpose of the chat session is to be sure all students have the script installed and working, and discuss a plan for designing the code needed to modify the system. Be sure to read the course page right before this WebQuest section for tips on how to work with CSV.
You can meet with your group as many times as you want during the project. 

