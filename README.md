# Hosting a resume on Github Pages

## Intro
If you have ever wanted to learn how to host a page on the web. GitHub Pages is a great place to start. It's simple, convenient, and completely free. So you won't need to sacrifice a day without coffee to make it happen. We will be using Andrew Etter's book _Modern Technical Writing_ as a reference. It gives great examples and guidelines to follow, explaining why to host online content, and how to do it.  

## Getting started
To get started, you need to get your self a Github account. If you haven't had any experience with GitHub, it's known as a code hosting platform that uses Distributed Version Control System (DVCS). DVCS gives you the full history of what's happened to each file. It also makes it so all changes are mirrored on every developer's computer that's part of the project. Etter explains "The basics are that DVCS have better performance, allow for offline work, and are superior for concurrent work on the same file." All you need to know for now is that this is the website you will be using to host your resume. Specifically using a feature called GitHub pages. More on this later.  

## Making a respository
There are many different mediums to use GitHub, I will be giving all the steps in the website version. After you have created your account, you need to create a repository. This is where you will be doing all of your work, think of it as the main folder in which you will be entering all your content. To create a repository:
 1. Click the green "New" button located on the top left.  
 2. Insert repository name. (It is important that you format your repositories name, or else you will not be able to use GitHub Pages. Use the format _YourUserName.github.io<span>_)
 3. Click create repository.  

## index.md<span> file
Now that the repository is set up, you will need to create an index.md<span> file. This is where all of the content for your resume will reside. First, you need to make your resume, what you include is up to you. Using a lightweight markup language is necessary for GitHub Pages. Specifically using GitHub flavoured Markdown, so keep in mind to create using these tools. Andrew Etter says that Markdown is an incredible, easy to learn markup language through its clean syntax and limited set of features. If you learn to use Markdown now, it will help you in the future. Most developer documentations use Markdown as their primary writing tool, so think of this as killing two birds with one stone. I've provided a link to a beginner's Markdown tutorial in resources that I recommend looking at if you are new to it. To add the index.md<span> file:  
1. Click the green "Add file" button on the top right.
2. Insert index.md as the name for the file. 
3. Click add file. 

## GitHub Editors
You know how to write Markdown now and have a place to store it on GitHub. But where will you be writing it, though GitHub has an editor, it doesn't provide you with a live preview of what you're writing or how the final output will look. There are many tools you can use to do this. I use Visual Studio Code, with the markdown preview extension. You can also clone your repository right into Visual Studio and push all your changes right from the terminal. If this is your first time reading languages such as push, clone, or terminal. Don't feel overwhelmed, you can skip over this and just copy-paste straight from your Markdown file into the file in your GitHub Repository. This is just if you have the knowledge of git and want to take full advantage.   

## Entering your resume into GitHub
To enter your Markdown formatted resume into the index.md<span> file:  
1. Open up the index file
2. Click the edit button on the top right of the page.
3. Paste your resume.
4. Click commit to save the file.  

This now lives on the GitHub site until taken down. You can now host your resume on a static website on the web. Andrew Etter mentions his love for static sites comes from "their speed, simplicity, portability, and security." The power of static sites makes it so you can enter anything correctly formatted and get a beautiful output on a static site. You just have to choose which theme you'd like and it will automatically generate the static site using the content in your index.md<span> file. 

## How to create a static site
1. go to settings in your repository
2. Scroll down until you get to GitHub pages (make sure under source that main is selected)
3. Click change theme under Theme Chooser
4. Select your preferred theme
5. Click save.  

It's that simple, you can view your resume online by going to _YourUserName.github.io<span>_ in your browser. This may take some time before you see the selected theme on the webpage, it might just be your resume in regular Markdown. But after some time the theme will show up. This is where the power of static site generators through GitHub Pages is seen. GitHub Pages uses Jekyll to generate the themes, Jekyll is a language just like Java, C++, etc. but specifically dealing with static site generators. 

## See the difference
You can see the difference Jekyll makes through the media below. Showing a before Jekyll site and an after Jekyll site. This visual difference will allow you to be more presentable to any hiring manager. Especially if others who are applying for the same job aren't taking advantage of static sites.  


**Without Jekyll:**  
<img src="https://github.com/jai-sandhu/jai-sandhu.github.io/blob/main/media/pic.png" width="480">

&nbsp;  

**With Jekyll:**  
![Resume with Jekyll GIF](https://github.com/jai-sandhu/jai-sandhu.github.io/blob/main/media/gif.gif)

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
1. Why is Markdown better than Word processor?  
   a. It all really comes down to preference, and what you are doing. Markdown is great for fast, simple work such as note taking or documentation. While Word excels in helping do what the user wants through its distinguished UI. [More on this](https://techup.lawyer/why-and-how-to-use-markdown-instead-of-or-in-addition-to-word.html)

2. How do I get GIF's to work on my Markdown file?  
   a. You can follow the format "![](GIF link)". You can even host you're own GIF on GitHub. [More on this](https://medium.com/@josephcardillo/how-to-add-gifs-to-your-github-readme-89c74da2ce47)

