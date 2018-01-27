# Deploying to the internets
---

**Learning objective**: Understand the significance of Git and why GitHub is relevant to our interests.

---

So at this point, we have a good sense of **how** an HTTP request works, but the main question that remains is this: **how do we get our webpage to the internets?!**

To answer this question, we must do two things: 

1. Build our own simple HTML page
2. Push it to GitHub.

## Building a basic HTML page
---
At this point, we know that the server from our last section (say, **Google's** server) will return to us a response that is encoded in a specific way (a **language** if you will).

But! **Where is this data stored?**

As it turns out, it is stored in files and folders, in the same way we store data on our computers.

So in order for us to "build" our own HTML page, we must do two things:

1. Create a folder to store our HTML data
2. Create a file **within that folder** and write out HTML.

## Pushing to GitHub
---

Ok, now we have an HTML page! And get this: we can even load it in Chrome and see it rendered! How do we get this online?

In one word: **GitHub**.

#### What is GitHub anyways?
---

GitHub is a service that allows developers to **push** their local **git repositories** online. As a courtesy, they also have their own server that will **host** HTML/CSS/JavaScript files that are found in the pushed repos.

But first, a few definitions:

#### Git
---
Git is an open source software that allows developers to collaborate on large software projects. 

With Git, developers can **commit** code at certain checkpoints. So for example, if you are building a website that requires:

1. a form,
2. a slideshow,
3. and a server request, 

You would implement the form then **commit** that code. Then, you would implement the slideshow and **commit**. Finally, you would implement the server requestand **commit** once more. 

This is useful because if, for any reason your updates to the slideshow breaks your form code, you can easily **roll back** to your last commit (the form implementation) and that code would remain pristine and unbroken. 

#### Git Repository 
---
When you take a piece of code and start tracking it with Git, you are turning it into a git **repository**. Your git repository will store all your commits, keep track of your code, give you commands that allow you to roll back to a previous commit, etc.

#### Pushing to GitHub
---

The final piece is this: your awesome git repo has let's say 500 commits on it. This is awesome! 

But now calamity strikes! Your computer inexplicably dies the morning of your big presentation. Here's the main question: **are you screwed?**

In one word: **Yes**. 

Incidentally, this is **exactly** the problem GitHUb solves. As it turns out, Git allows you to **push** your git repos to other places. Either your friends computer, or your spare home computer, etc. GitHub is basically a cloud storage system that lets you store your git repos online for **free** and also share it with other developers.
