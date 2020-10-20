# _Library_

#### _Library Project for Epicodus, October 16th, 2020_

#### By _**Mike Manchee, Johnny Duverseau, and Natalie Murphy**_

## Description

  
<!-- Brainstorming
Library
Let's move on to a new program to catalog a library's books and let patrons check them out. Here are some user stories to get you started:

Librarian:
-Create, read, update, delete, and list books in the catalog, so that we can keep track of our inventory.
-Search for a book by author or title, so that I can find a book when there are a lot of books in the library.
-Enter multiple authors for a book, so that I can include accurate information in my catalog. (Hint: make an authors table and a books table with a many-to-many relationship.)
-see a list of overdue books, so that I can call up the patron who checked them out and tell them to bring them back - OR ELSE!

Patron:
- Check a book out, so that I can take it home with me.
- Know how many copies of a book are on the shelf, so that I can see if any are available. (Hint: make a copies table; a book should have many copies.)
- See a history of all the books I checked out, so that I can look up the name of that awesome sci-fi novel I read three years ago. (Hint: make a checkouts table that is a join table between patrons and copies.)
- Know when a book I checked out is due, so that I know when to return it.

 -->
### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
|  1.  ... | ... | ... |



## Setup/Installation Requirements

### Project from GitHub
* Download option
  * Download files from GitHub repository by click Code and Download Zip
  * Extract files into a single directory 
  * Run GitBASH in directory
  * Type "dotnet restore" to get bin and obj files
  * Type "dotnet run" in GitBash to run the program
  * Add database per the instructions below.
  * Have fun with Library <!-- TITLE HERE -->

* Cloning options
  * For cloning please use the following GitHub [tutorial](https://docs.github.com/en/enterprise/2.16/user/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
  * Place files into a single directory 
  * Run GitBASH in directory
  * Type "dotnet restore" to get bin and obj files
  * Type "dotnet run" in GitBash to run the program
  * Add database per the instructions below.
  * Have fun with Library <!-- TITLE HERE -->

### Database Setup
* Go to appsettings.json and change the password if needed.

* Setup with SQL migrations
  * In the terminal, navigate to the project folder
  * Type "dotnet ef migrations add Initial" and wait for migration file to be built
  * Type "dotnet ef database update" and wait for build confirmation
  
* Setup with SQL statements 
  * Enter the following code into your SQL database and run.
  ``` SQL
  
  ```

* Setup with SQL Import
  * MySQL
    * In the Navigator > Administration window, select Data Import/Restore.
    * In Import Options select Import from Self-Contained File.
    * Navigate to library.sql.
    * Under Default Schema to be Imported To, select the New button.
      * Enter 'library' as the name of your database.
      * Click Ok.
    * Click Start Import.

## Known Bugs

No Known Bugs

## Technologies Used
Project Specifics
* Identity

Main Programs
* MySQL
* C# / ASP.NET Core
* Entity
* Identity
* MVC
* MSTest
* CSS
  * Bootstrap
  * Font Awesome [Link Here](https://www.w3schools.com/icons/fontawesome_icons_intro.asp)


### Other Links
[GitHub](https://blog.agood.cloud/img/common/github.png)
[Mike's GitHub](https://github.com/mmanchee)

### License

Copyright (c) 2020 **_{Mike Manchee, Johnny Duverseau, and Natalie Murphy}_**
Licensed under MIT