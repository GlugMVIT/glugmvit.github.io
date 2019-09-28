## Contribute

You can help this project by authoring a post, reporting problems & suggestions, localizing it or contributing to the code.

### Report a problem or suggestion

Go to our [issue tracker](https://github.com/glugmvit/glugmvit.github.io/issues) and check if your problem/suggestion is already reported. If not, create a new issue with a descriptive title and detail your suggestion or steps to reproduce the problem.

### About the project

This is a website built with **Jekyll**, a website generator that’s designed for building minimal, static blogs to be hosted on **GitHub Pages**. Jekyll takes your content written in **Markdown**, passes it through your templates and produces a complete static website, ready to be served. GitHub Pages conveniently serves the website directly from your GitHub repository so that you don’t have to deal with hosting.
 
You need to follow certain steps before making any changes to the code or adding any post.The steps are:
   - Install Jekyll locally via the command line.
   - Clone a starting point to your local machine, install Jekyll locally via the command line, make updates to your website, build it locally, and then serve it.
   - Fork a starting point, make changes, and then serve it.

   For the above steps to be done you need to be familiar with git and github. For installation, you may go through the following link: (https://jekyllrb.com/docs/)

## Knowing Jekyll:

 1. There are various folders in the folder structure.The different folders are _layouts,_pages,_posts,assets etc.The files present are _config.yml,Gemfile,Gemfile.lock etc.Jekyll uses the Liquid templating language to process templates. There are two important things to know about using Liquid.First, a YAML front-matter block is at the beginning of every content file. It specifies the layout of the page and other variables, like title, date and tags. It may include custom page variables that you’ve created, too.
 
 2. Liquid template tags are used to execute loops and conditional statements and to output content.Liquid markup uses double curly braces to output content. The two common template tags are page.title and content(enclosed in double curly braces), which output the title and content of the blog post.Single curly braces and modules are used for conditionals and loops and for displaying includes.

 3. Layouts of a page are templates that wrap around your content.There is no front matter to the HTML files,just content is replaced with content variable.You can add images to the _images folder and you can also make use of preprocessor support. Advanced features of Jekyll includes the concept of Data files(in YAML and JSON) form which can be used to store datasets.Collections can be used to define your own document types in Jekyll.

 To gain insight, you can refer to [Jekyll tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/) 


## To add a post:

Using _Github editor_ :
 
 1. You can easily write your blog post by adding content in the _posts folder by adding   your blog post in the form of a markdown file.Markdown is a way of formatting your writing for reading on the web: it’s a set of easy-to-remember symbols that show where text formatting should be added (e.g. a * in front of text means to format it as a bulleted list item).

 2. For Jekyll in particular, Markdown means you can write webpages and blog posts in a way that’s comfortable to authors (e.g. no need to look up/add in HTML tags while trying to write an essay), but have that writing show up formatted nicely on the web (i.e. a text-to-HTML convertor).You can add your content without any formatting also.To know more about markdown files,check this out:[Markdown reference](http://kramdown.gettalong.org/quickref.html).
 
 3. Make sure any Markdown cheatsheets you look at are for the “kramdown” flavor of Markdown, which is what GitHub Pages (where we’ll be hosting our website) supports. (There are various [“flavors” of Markdown](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors) that have subtle differences in what various symbols do, but for the most part frequently used symbols like those that create heading formatting are the same.

 4. Change the file name to include today’s date and the title of your post. Jekyll requires posts to be named year-month-day-title.md.Update the title at the top of the Markdown file. Those variables at the top of the blog post are called front matter.There are various [front matter variables](http://jekyllrb.com/docs/frontmatter/) available.

 5. If you’d like to create new blog posts in the browser on GitHub.com, simply hit the “+” icon in _posts/. Just remember to format the file name correctly and to include the front-matter block so that the file gets processed by Jekyll. 

 _Using a local editor_ :

 1. Create a new post in the _posts folder. Remember to name it in the format year-month-day-title.md, and include the front matter at the top of the post.

 2. Commit the post’s Markdown file, and push to your GitHub repository.That’s it! Just wait for GitHub Pages to rebuild your website. This typically takes under 10 seconds, assuming you don’t have a huge amount of content.

 You can add a page in a similar way and the following can be done:
  
   * layout: Keep this as-is (it should say page).
   * title: Change this to the desired page title (unlike posts, no quotation marks around the title).
   * permalink: change the text between the two forward slash marks to the word (or phrase—but you’ll need to use hyphens and not spaces!) that you want to follow your site’s main URL to reach the page. For example, permalink: /about/ locates a page at localhost:4000/yourwebsitefoldername/about/

## To make changes and create issues:

1. We have made this website in a simple way and any developer can suggest new ideas and make changes accordingly.You can raise issues if you feel that the working of any part in this website is not proper.For simple questions and queries,you can easily connect with us through various social media platforms. Make sure you raise a relevant issue and create a proper pull request and it will definitely be considered.

2. You can suggest changes first and then open an issue or send a pull request.These suggestions can be made by connecting with our team of developers through emails and social media platforms.Once you get positive feedbacks from the team,you can go ahead with it. 

3. Ensure the bug was not already reported by searching on GitHub under Issues.
If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

4. For fixing a bug, open a new pull request with the patch of code and make sure to include details describing the changes you made and the bug your code fixes clearly.Also,changes like formatting of text and adding styles to font may not be accepted because these changes do not add anything substantial to the website.  


## Hosting on Github and Pull requests:

For everyone who have made changes and want to see their site running,you can follow these steps:
 
  - **To test stuff locally**:
     
     * Start local site: Type bundle exec jekyll serve --watch at the command line
     * Visit local site: Open localhost:4000/yourwebfoldername(or glugmvit.github.io/ in a web browser (e.g.localhost:4000/JekyllDemo/). Don’t forget the trailing slash!
     * See changes on the local site as you make them: While the site is running, after  
     * making changes to website files: save the files and refresh the webpage to see the    changes—except for the _config.yml file, for which you must stop running the          website and restart running the website to see changes.
     * Stop local site: Hit control-c on the command line.
  
  - **To move local changes to your live site**
     * Install the [Github desktop app](https://help.github.com/en/desktop/getting-started-with-github-desktop/installing-github-desktop)
     * Make the desired changes to your website’s local files.
     * Open the GitHub Desktop app, make sure your website is chosen in the left sidebar’s   list of repositories, and write your commit message summary (and description if       desired).
     * Click “Commit to gh-pages” in the lower left.
     * After the commit has completed, click “Sync” in the upper right.
     * Allow 10-90 seconds for your changes to reach GitHub’s web servers, then visit your   website and refresh the page to see your changes live.

## Contribute to the code

If you know how to code, we welcome you to send fixes and new features, but in order to be efficient we ask you to follow the following procedure:

* Fork this repo using the button at the top.
* Clone your forked repo locally.

``$ git clone git@github.com:yourname/glugmvit.github.io.git``

* Don't modify or work on the master branch, we'll use it to always be in sync with webogram upstream.

```
$ git remote add upstream git@github.com:glugmvit/glugmvit.github.io.git
$ git fetch upstream
```

* Always create a new issue when you plan to work on a bug or new feature and wait for other devs input before start coding.
* Once the new feature is approved or the problem confirmed, go to your local copy and create a new branch to work on it. Use a descriptive name for it, include the issue number for reference.

``$ git checkout -b improve-contacts-99``

* Do your coding and push it to your fork. Include as few commits as possible (one should be enough) and a good description. Always include a reference to the issue with "Fix #number".

```
$ git add .
$ git commit -m "Improved contact list. Fix #99"
$ git push origin improve-contacts-99
```

* Do a new pull request from your "improve-contacts-99" branch to webogram "master".

#### How to implement changes suggested on a pull request

Sometimes when you submit a PR, you will be asked to correct some code. You can make the changes on your work branch and commit normally and the PR will be automatically updated.

``$ git commit -am "Ops, fixing typo"``

Once everything is OK, you will be asked to merge all commit messages into one to keep history clean.

``$ git rebase -i master``

Edit the file and mark as fixup (f) all commits you want to merge with the first one:

```
pick 1c85e07 Improved contact list. Fix #99
f c595f79 Ops, fixing typo
```

Once rebased you can force a push to your fork branch and the PR will be automatically updated.

``$ git push origin improve-contacts-99 --force``

#### How to keep your local branches updated

To keep your local master branch updated with upstream master, regularly do:

```
$ git fetch upstream
$ git checkout master
$ git pull --rebase upstream master
```

To update the branch you are coding in:

```
$ git checkout improve-contacts-99
$ git rebase master
```
