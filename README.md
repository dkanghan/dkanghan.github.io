# Hosting a Resume file on Static Site Generator

## Purpose
This document is going to help in how to write, format and host a resume on static website with the use of different softwares. The resume file will be written 
in markdown language. Hence, you will require a markdown editor to write and github pages and jekyll to format and host a static website. This will also contain the 
concepts and ideas given in Andrew Etter’s book Modern Technical Writing and we will relate to the steps which we will follow.

### Prerequisites

Requirements to work on this project are:
* **Markdown Editor** :- You would require a basic markdown editor which can be used to write the README file in markdown format.
> Some of the good Markdown Editors are [Markdown Pad](http://www.markdownpad.com/)(as suggested by Andrew Etter) or [stackio](https://stackedit.io/)(an online collaborative markdown editor), If you're looking to use Markdown in one of the softwares you can also use [Visual Studio Code](https://code.visualstudio.com/).
* **Resume formatted in Markdown** :- We would want a resume in markdown format, and a tutorial on how to use markdown is given in **More Resources** section.

### Instructions
1. **Making a Resume** :- You would want to make a resume in a lightweight markup languages. Markdown language being one of the most used lightweight markup language, We will also use this in our project to carry out the desired goal. Hence, We will use this resume to host in our static website.
 
 ![Markdown](https://github.com/dkanghan/Resume/blob/gh-pages/media/Md.gif)

2. **GitHub Account** :- You will require a Github Account as Github is one of the most extensively used Distributed Version Control system on the market. In his book, Etter says, "DVCS (Distributed Version Control) provides higher performance, supports offline work, and is preferable for simultaneous work on the same file. The most essential reason for technical writers to utilise DVCS is that developers prefer them." DVC's help keeping updated documents and their previous version accessible for users to go back and correct the errors or make the changes in the new version.

3. **Repository** :- 
   * After creating the account in GitHub, You will create a new repository by clicking on the new near the repositories.
 
 ![new repo](https://github.com/dkanghan/Resume/blob/gh-pages/media/Github.png)
 
   * Give your repository a name
 
 ![repo name](https://github.com/dkanghan/Resume/blob/gh-pages/media/Create%20Repo%20GIF.gif)
  

4. **Hosting Resume on Jekyll** :- To host your resume, we will require a static site generator such as jekyll and Github Pages to host the resume there.
   
   * You would require to create a new jekyll server for your static website by using 
**jekyll new < name of server >**
   
   ![jekyll](https://github.com/dkanghan/Resume/blob/gh-pages/media/Jekyll%20new%20Gif.gif)
   
   * Once, you create a server. You should go to the _post folder and create a new folder for your resume.
  >  Note :- The new folder that you create must follow the requirement of the folder name and content according to how jekyll works. 
  >>  * i.e,name of the folder :-  yyyy-mm-dd-name
  >> * content of the folder must include the font markers.
   
   ![jekyll folder](https://github.com/dkanghan/Resume/blob/gh-pages/media/_post.png)
   ![Folder Name](https://github.com/dkanghan/Resume/blob/gh-pages/media/resume%20file%20gif.gif)

5.  **Hosting Resume to Remote Server** :- Andrew Etter mentioned in his book, "You should build and host a website, not distribute PDFs, but it bears repeating. Even the best documentation, like software, eventually goes out of date."As a result, we can create a static website and host it on Github Pages. Static websites, according to Etter, are simple, portable, safe, and lack database or server-side requirements. Github Pages is a great static site generator that also includes various Jekyll themes. If you wish to utilise your own custom theme, see the **More Resources** section. 

 ![Hosting Resume](https://github.com/dkanghan/Resume/blob/gh-pages/media/Hosted%20resume.gif)

### More Resources
1. **Markdown Tutorials** :- [Markdown Tutorial](https://www.markdowntutorial.com/) is easy to go through tutorial which helps you learn markdown language from the very basic.
2. **Modern Technical Writing : An Introduction to Software Documentation** :- This [book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by Andrew Etter is very helpful to understand the principles of Modern Technical Writing.
3. **Custom Jekyll theme** :-  If you  plan on using a custom theme for your website follow [this](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).
   
### Author
- Dharmit Anghan
### Acknowledgements
- **Kim, Gyuri** :- Peer Reviewed README file  
- **Ahir, Md Ahiduzzaman** :- Peer Reviewed README file
- **How, Yun Ji** :- Peer Reviewed README file
- **Billie Thompson** :- Provided README Template - [PurpleBooth](https://github.com/PurpleBooth/a-good-readme-template)
### FAQs
1. Why is Markdown document better than a word document?  

	 *According to Andrew Etter, "Documentation with any sort of lifespan needs to be kept in version control, which Word's DOCX file format (a compressed collection of XML files) actively opposes." Using Markdown helps two principles mentioned by etter in use*
	    
      * *To Store the document under version control.*
	   
      *  *To Deploy the documentation using a static site generator*
2. Why should we use Distributed Version Control System?
   
   *According to Etter, "DVCS have better performance, allow for offline work, and are superior for concurrent work on the same file. For technical writers, the most importanct reason to use DVCS is that developer prefer them." Hence, the usability of DVCS can be proved in a long run where multiple users commit and update a project. DVCSC can handle that kind of structure and keep the documentation secure.*
    
