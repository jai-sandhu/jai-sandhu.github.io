# Hosting a resume on Github Pages

## Intro
If you have ever wanted to learn how to host a page on the web. GitHub Pages is a great place to start. It's simple, convenient, and completely free. So you won't need to sacrifice a day without coffee to host a website. You will be using Andrew Etter's book _Modern Technical Writing_ as a side project. It gives great examples and guidelines to follow, explaining why to host online content, and how to do it.  

## Getting started
To get started, you need to get your self a Github account. If you haven't had any experience with GitHub, its known as a code hosting platform that uses a Distributed Version Control System (DVCS). DVCS's is a version control type where everything done to the code is saved. It gives you the full history of whats happened to the each file. It also makes it so all changes are mirrored on every developers computer thats part of the project. Etter explains "The basics are that DVCS have better performance, allow for offline work, and are superior for concurrent work on the same file." All you need to know for now is that this is the website you will be using to host your resume. Specifically using a feature called GitHub pages. More on this later.  

## Making a respository
There are many different mediums to use GitHub, I will be giving all the steps in the website version. You can follow along or use your own preferred method. After you have created your account, you need to create a repository. This is where you will be doing all of your work, think of it as the main folder in which you will be entering all your content into. To create a repository, you simply need to click the green "New" button located on the top left. This will take you to a new page where you enter your repositories name. It is inportant that you format your repositories name, or else you will not be able to use GitHub Pages. Use the format _<span>username.github.io<span>_. Before you click create repository at the bottom, I recommend that you checkmark the option to create a README file.  
## index.md<span> file
Now that the repository is set up, you will need to create an index.md file. This is where all of the content for your resume will reside. First you need to make your resume, what you include is up to you, but how you should go about doing it is something I can help with. Using a lightweight markup language is necessary for GitHub Pages. Specifically using GitHub flavoured Markdown. Markdown is an easy to use Word. Andew Etter says that markdown is an incredible, easy to learn markup language throgh its clean syntax and limited set of features. If you learn to use markdown now, it will help you in the future. Most developer documentations use Markdown as their primary writing tool. So think of this as killing 2 birds with 1 stone. I've provided a link to a markdown beginners tutorial that U recommend looking at.  
## GitHub Editors
Okay, so now you have the knowledge to write markdown and a place to store it on GitHub. But where will you be writing it, Though GitHub has an editor, it doesnt provide you with a live preview of what you're writing and how the final output will look. There are many tools you can use to do this. I personally use Visual Studio Code, with the markdown preview extension. You can also clone your repostory right into Visual Studio and push all your changes right from the terminal. If this is your first time reading language such as push, clone, or terminal. Don't feel overwhelmed, you can skip over this and just copy paste straight from your markdown file into the file in your GitHub Repository.  

## Entering your resume into GitHub
To enter your markdown formatted resume into the index.md file. You open up the index file, click the edit button on the top right of the page, paste your resume, and then click commit to save the file. This now lives on the GitHub site until taken down. You can now host your resume on a static website on the web. Andrew Etter say his love for static sites comes from "their speed, simplicity, portability, and security." The power of static sites also allows us to be able to enter what we want and instantly get a pretty output. Just have to choose which theme you'd like and it will automatically generate the static site using the content in your index.md file.  
## How to create static site
To start the process, go to settings in your repository, scroll down until you get to GitHub pages (make sure under source that main is selected), click change theme under Theme choose and select your preferred theme. Its that simple, you can view your resume online by going to _<span>username.github.io<span>_ in your browser. This may take some time before you see the selected theme on the webpage, it might just be your resume in regular markdown. But after some time the theme will show up. And this is where the power of static site generators through GitHub Pages. GitHub pages uses Jekyll to generate GitHub pages themes.  
## See the difference
You can see the difference Jekyll makes through the pictures below. Showing a before Jekyll site and an after Jekyll site. This visual difference will hopefully allow you to be more presentable to any hiring manager. Especially if others who are applying for the same job arent taking advantage of static sites.  


**Without Jekyll:**  
<img src="https://github.com/jai-sandhu/jai-sandhu.github.io/blob/main/media/pic.png" width="480">

&nbsp;  

**With Jekyll:**  
![Resume with Jekyll GIF](https://github.com/jai-sandhu/jai-sandhu.github.io/blob/main/media/gif.gif)


# also explain how to go into yml file and change things in it, ex. titel and other thigns you might want to add



## More Resources
1. [Markdown tutorial](https://www.markdowntutorial.com/)
2. [Andrew Etter's _Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
3. [Getting started with GitHub Pages](https://pages.github.com/)
4. [Git for beginners](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
&nbsp;  

## Authors and Acknowledgments  
GitHub pages Jekyll Theme template author: [Parker Moore](https://github.com/parkr)  
Group Members (Group 10):
1. Jai Sandhu
2. David Le
3. Connor hryhoruk
4. Huayi Chen  

## FAQ  
1. Why is markdown better than Word processor?  
   a.

2. How do I get GIF's to work on my Markdown file?  
   a. 

