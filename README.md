# How to host a resume on GitHub using Markdown and GitHub Pages
This project descirbes practical steps on how to host a resume on GitHub and demonstrates the general priniciple of current technical writing as explained in [Andrew Etter's book of Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

## Prerequisites

Requirements include : 
- [My resume formatted in Markdown](https://makumatj.github.io/)
- [Markdown tutorial to help you understand how to use it](https://www.markdowntutorial.com/)

## Instructions
### 1. Complete the step by step tutorial on Markdown
After the tutorial , you should be ready to starting writing in Markdown. Now go to [https://dillinger.io/](https://dillinger.io/) and start writing your resume until it is complete. Save the markdown formatted resume on your computer.
### 2. Go on GitHub and create a new public repository and name it _yourusername.github.io_
To create a new repository simply click on the add file button and click on create new file within the drop down menu. Name it _yourusername.github.io_ then scroll down and make sure it is public, then finally click on commit new file.
### 3. Add your markdown resume to the repository you just created
Now that your repository is created, it is time to put in your resume. Click on add file located at the top right of your commits and click on upload files. Upload your resume on there.

### 4. Update the name of resume to index.md
After your upload is complete, you will have to change the name of your resume.md file to index.md. Do this by clicking on  your resume.md file, and at the top right corner of the editor click the pencil button. This will allow you to change the name at the top. Finally scroll down and click on commit to save.

### 5. Enable GitHub Pages for the static website
Since we would want a static website for the resume, it has to be hosted with GitHub Pages. GitHub Pages allow you to host personal and project pages directly from a GitHub repository. It is also free and everything can be done on GitHub.

To enable GitHub Pages for the resume, go to your repository’s Settings page.
Scroll until you find the GitHub Pages section. There are two subsections here: Source and Theme Chooser. In the Theme Chooser tab. Here, you’ll select a design template for your static site. 
All of the theme options are from Jekyll. If you don’t know Jekyll, that’s ok. This guide will walk you through the necessary configuration. Honestly, I have no idea how Jekyll works beyond GitHub Pages templates.

### 6. Choose a theme for your resume
Resumes are very important tools that can make or break you when it comes to job hunting. They give your future employers an idea of who you are - so choosing an attractive theme can be very important! For this guide, we’ll be using the “Merlot” theme because that’s what I personally prefer for my resume, you can always choose any theme that works for you.
Before we continue, you might have noticed a few things that happened in the background that you should know about…

Jekyll theme was set to “Merlot”.
GitHub Pages confirms your theme selection by creating a file called _config.yml. By default, this file will only contain a theme field with your selection. To learn more about Jekyll theme configurations please visit: [https://jekyllrb.com/docs/configuration/](https://jekyllrb.com/docs/configuration/)


### 7. Animated GIF of how my resume looks like
![Webp net-gifmaker](https://user-images.githubusercontent.com/101964459/159418198-62cd9ad3-fe37-42b7-bcf5-b8733465ec4b.gif)

## Relating the above instructions to the priniciples of current technical writing as explained in Andrew Etter's book "Modern Technical Writing"
The instructions above were mainly inspired by certain principles that were found in Andrew Etter's book Modern Technical Writing and I would like to relate them to some of the principles in the book.

**1. Make a static website using Jekyll theme**
According to Andrew Etter, static websites can be very important when it comes to creating resume's and other important things on your GitHub mainly because of how portable, fast simple and secure they can be. To create a static website, you do not need to install anything. You can always host a static website on GitHub Pages and if you recall, that was what we did instructions 5 and 6.

**2. Use a Lightweight Markup**
Andrew Etter, in his book described that, using lightweight markups like markdown can make reading and writing less difficult as compared to XML-based languages like XHTML, DocBook, etc since they make contributions impossible for other people. They also require specialized knowledge of odd tags,etc. This inspired the writing of our resume in Markdown.

**3. Use distributed version control**
Andrew Etter says for technical writers, using distributed version control systems like  GitHub and GitHub Enterprise have better performance, allow for offline work, and are superior for concurrent work on the same file. Some other importance of using them especially GitHub is:
- You can store your documentation in the same repository as its corresponding product source code. 
- Documentation and code branches stay in sync.
- Developers are more likely to contribute if they don't have to clone a separate repository.

Because of all of these advantages, it is always best to host your resume on Github just like what we have done.

## More resources:
-  [Andrew Etter's book on Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
-  [Markdown tutorial to help you understand how to use it](https://www.markdowntutorial.com/)
-  [What is Jekyll?](https://jekyllrb.com/)

## Authors & Acknowledgment
 - I wish to express my profound gratitude to **Stewart Wilcox**, **Singh, Arman Preet**, **Gao,Hong**, **Kroeker,Adam** and **Stoeke,Cain** for their remarks, suggestions, and some helpful conversations about GitHub and Markdown, which has considerably improved this project.
  - A big thank you to **Billie Thompson**  who provided the README Template at [PurpleBooth](https://github.com/PurpleBooth)
  - **Andrew Etter** the author of  Modern Technical Writing was also very helpful
 
### FAQs
**Why is Markdown better than a word processor?**
- This is because using lightweight markups like Markdown can make reading and writing less difficult to understand and makes it easy for others to contribute.

**Why is my resume not showing up?**
- This is because most GitHub repository can take up to 20 minutes to update a change
