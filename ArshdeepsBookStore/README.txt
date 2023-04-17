Arshdeep Singh
0791162

2023-03-02
1505
Srarted Assignment 2 in-class on the lab computer.
Set up the ASP.NET MVC w/core 1.3 (out of support)
HTTPS enabled , individual account authentication , no razor yet
Reviewd the folders and the content with the professor 

and finally 1507
i made my first change in the project,
in startup.cs file i changed the line 33 , where i removed "options => options.SignIn.RequireConfirmedAccount = true".

1510
Created a Repository on GitHub and updated the Readme file
and I have made my Repo Private


and after saving the file I fired up my project to see if it works fine.

1510
It worked great, and workin fine.
1516
I changed the welcome message on the home page and tested the file by running it again.

1523
Reviewed the route pattern in the startup.cs

1544
I had to make my projectagain because my github was not responding.
I was unable to push my changes through.

2023-03-03
1534
Next day and ruuning the application with no problems.

1540
Change the data in the layout.cshtml ,so it can automatically be updated at the end of the year.

03-09-2023 1438
cloned the reposotory and fired up the project.

1442
Starting to install new bootstrap file by downloading one from bootsswatch.com
first I downloaded the bootstrap theme which I want to implement and the I changed the original bootstraps name in the project and
added the new file to the css folder
the theme is "Sketchy"
by following the instruction in the slides

1450
following the instructions from thye slides Made changes to the two files,
_layout.cshtml and _LoginPartial.cshtml

1500
After Making all the changes , tried running the project.
Running Perfectly fine.
also upadating the navigation bar.
Where Changing the name of "Home" to "Books", for our Future Books Database.

1520
Made Changes to Layout.cshtl because it wasnt Working.

1548
Added a dropdown menu link in the layout.cshtml file
and ran it its working fine.

3/10/2023
1526
Added new projects and About to run now
its running fine
just waiting for the professor to mark it now

3/27/2023
1620
Starting the project again annd still fixing the dependencies from the assignmnet1

1630
Created 3 Dependencies according to the instructions given in the slides and also also Moved the Data folde4r to the "ArshdeepsBooks.DataAccess
"
1635
Installed NuGet Package : identity.entityframeWork Core

1640
Deleted the default class1 in the all projects also modified the NameSpace
\
1645
Moved the Models folder to ArshdeepsBooks.Model, Added Preferences to the project
Lastly we renamed the Models folder to ViewModels

1655
Firstly I modified the startup.cs file and encountered the errors and then resolved them with the given instructions
Went to Error.cshtml and changed the namespace accordingly
now I am gonna fire up the engines and try to run the Project

1700
Ran the project and its running file

1705
Created a new class called SD.cs in the Utility project
and modified the property of the class to public static

Added prefernces to the projects-
DataAcees 
Main project

Added A new Area called Customer and
Modified the pattern of Startup.cs

moved homeController to the contoller folder in the Area "Customer"
and the deleted the folders called Data and Model in the Customer Area

1719
Edited the homeContoller.cs tp explicit define the customer and 
moved the Home folder from views to the view in the "Customer"

1726
Modified the homeconroller's Namespace

1729
Trying to run the Application

1740
Application Running Fine 

1742
Moved two files from Views to Customer called _viewImports.cshtml & _viewsstrat.cshtml

1800
Added A new Area called Admin
Moved two files from Views to Admin called _viewImports.cshtml & _viewsstrat.cshtml
Deleted the folders called Data and Model in the Admin Area
Deleted the Controllers folder from the main project

18.02
Ran the application and working fine
part 1 of the assignmnet is officailly completed.

3/30/2023
19.33
Staarting the part 2 assignmnet,
firstly I have made changes to the appsetting.json file and added the migrations
"20230330233239_AddDefaultIdentityMigration.cs"
"20230331003528_AddCategoryToDb.cs"
And these are the timestamps

19.45
After First step , i encountered 6 errors and solved them later through migrations 
and then updated the database by running 
"update database" command

2000
First we made a class called category.cs 
then added migration and solved error which occured in 
"applicationDbContext.cs"

2040
aDDED Category.cs file and had a lots of errors, it wasnt showing in the table.
so I had to delete the cs file and then add again and after that i ran the migrayion command and also upadated the
database
now its showing the field of category in the table

2045
Part 1 of the assignmnet is completed, now on to the second part.

2052
Added a new interface called "IRepository.cs" in the subfolder "IRepository" of folder "Repository"
which we all made in this step
and the few errors occured in the IRepository.cs file and I solved them with 
"Using" statements

2100
Now according to the Instructions
I added a new class in the repository folder called "Repository.cs"
I made changes according to the slides and then changed the using statements

2112
CategoryRepository.cs and ICategoryRepository.cs files are made as per then instructions
and made the required changes to make it work, followed the instruction givern in the slides

2115
Added a new intrface called "ISP_Call.cs" in IRepository folder and installe4d  the package to 
solve the errors

2119
Added a class in the Repository folder called "SP_Call.cs" and fix the using statements to match my namespaces

2126
pai ek hor interface Bananta called "IunitOfWork.cs" and made changes to it accordingly

2135
Made another class"UnitOfWork.cs "in the Repository folder and
later made changes to the "startup.cs" file accordingly, modified configuration service modifer method

2145
Just finished the final step and ran the application and it is running Smoothly , no errors faced.
Just waiting for the Preofessor to Mark it.
:)

4/06/2023
19.45
I am starting my application all over again because my last projects werent showing up in my github
due to the reason that i have checked yes to the option where they asked to place solution file and project on the same directory
due to that my prevciois projects were not connected to the main project and solution file.
I have tried debug that  as well by placing the soilution file in every project and changing the path for the solution file
bit it still did not work
so I decieded to Make it all over again and my Readme file is from the last attempt and I will be working on it till I get to the 3rd part.
thanks

2200
This is my First Commit after starting the whole project and I am on part second 

4/13/2023
Started the assignment again after the whole new bwgining and copy two files to make the project run

1540
Fixed the Interface ISO.cs because of the mistake from the last project attempts

1545
Created a file called SP_Call.cs the zi have tranfered all the data from the slides to the file and it has been working without errors

1550
Created a File called IUnitOfWork as a interface and updated the data according to the slides 

1800
Started the assignmnet againafter the class and Created the New file called UnitOfWork.cs, its a class inm the Repository folder
and editing the File According to the slides

1816
updating the StartUp.cs file according to the slides
initially the file didnt work,
so i had to make the class public in the UnitOfWorks.cs and Extend the class in the UnitOfWork.cs

1833
Craeted a New Controller called CategoryController.cs in the Areas/Admin folder
and then updated according to the slides and faced an error
Error was that one of the functions called GetAll() wasnt defiend
So i had to extend the interface ICategoryRepository.cs with the <Category>
and it started workin just fine.

1844
Added a new folder called Category in the Area/Admin/Views
and then We added a "view" in the Category folder called Index.cshtml
and insterted the data inside the Index.cshtml page, provided in tye slides

1850
Ran the Application and it is working fine so far
open the category page and it all good.

Layout Updated along with the navigation. by updating the_Layout.cshtml page

1900
cRAETED a new File .js in the wwwroot/js called category.js
then added the data thats provided by professor and also added that js file to the index.cshtml file
which made in the previous step.

Ran the Application and its working like a Charm  so far.
1930

Added buttons in category file : DELETE, EDIT AND CREATE NEW CATEGORY BUTTON

Then added a new view called Upser.cshtml

1940
Created a partial view for Edit and Back button and modified them according to instructions
_CreateAndBackToListButton.cshtml
_EditAndBackToListButton.cshtml

Modified asp-action in index.cshtml
Added validations for the filed category name

2015
Added The Void Save Method in IUnitOfWork
Removed the Save() Mwethod CategoryRepository.cs
Moved the Save method with return Statement


2025
Added A delete fUNCTION CALLED function Delete(url) in the category.js file
for deleting the Added Category in the page

then added a method calld  public IActionResult Delete in the CategoryController.cs

2040
aFTER ALL  thios I tried to Run the application everything was fine
untill I tied to update one of the Category 
then i found out I have issue with one of the methods with upsert in CategoryContoller.cs

 Aftwr fIXING THAT Application is workin alright and Its deleting and updating .
 With that Part 2 of the assignmnet is done

 On to the next Part 3
 2140
 Starting at the Part 3 , I created a file called Covertype.cs in the ArshdeepsBooks.Model 
 and then changed the data according to the file called Category.cs   

 4/14/2023
 1400
 created a file called Covertype.cs in the ArshdeepBooks.Models
 and the added public DbSet<CoverType> CoverTypes { get; set; } in theapplication Dbcontext.cs
 and then added the migrations

 Migration created this file 
 "20230414191744_AddCoverTypeToDb.Designer"

 1937
 Created afile called CoverTypeRepository.cs in the Repository, as a class
 and then added the data using the part 2 as a refernece.

 1940
 Just like the last step 
 now i Made a file called ICoverTypeRepository.cs as a interface in the IRepository and then
 made chnagex to it by taking ICategoryRepository.cs Reference

 1942
 Now Made Some Modifications in the files Called "UnitOfWorks.cs" & "IUnitOfWorks.cs"
 to add the new files parameteres
 The changes I made were " public ICoverTypeRepository CoverType { get; private set; }" , " ICoverTypeRepository CoverType { get; }" Respectivelty

 Deleted the File Calle3d Product.cs, beecause I jumped steps and created it early. I was worried bracsue it can cause
 issues when i will try to update the database. I am about to do that.

 1950
 I encountered an error when i update the database , in my IUnitofWork file
 I was missing a using statement
 so far everystep is working
 
 1957
 Now i added the Covertype into navigation , so we can access it easliy.

 2003
 We created a file called index.cshtml in the covertype folder that we also created in the views folder 
 just lije we did for category option.
 I tried running the program and it is showing a new page in the nav bar

 2008
 And now in wwwroot/js/ i created a file called covertype.js,
 which will consist all the javascript code for the CoverType

 2025
 added a new Controller called CoverTypeController.cs and 
 the modified according to Categorycontroller.cs

2030
Now using the COverTypeController.cs file I created a upsert file for the covertype
and then modified after.

4/26/2023

1628
Added A class called product.cs in the .models project and the fillowed the instructions jusk like Categorty.cs.

1630
made chnges to the ApplicationDb "public DbSet<Product> Products { get; set; }" and adding Migrations ,
with command "add-migration addProductToDb"
checked the products, it is showing in the Database table

Here is the TimeStamp for adding Product to database "20230417203027_addProductToDb.Designer.cs"

1636
Then I added Validation to the Product.cs fields as asked in the slides 
such as on Title, ISBN etc.
Then ran migration again and updated the database
"20230417204011_addValidationToProduct.Designer.cs" Here is the TimeStamp for Validations

1649
Created two files Called ProduxtRepository as class and then IproductRepository.cs as a interface
and then made the chnges to the files according to the slides