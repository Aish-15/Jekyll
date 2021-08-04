---
layout: post
title:  "Introduction to JupyterHub!"
date:   2021-08-04 12:22:34 -0400
categories: jekyll update
---

What is JupyterHub?

It is a website that helps to do professional coding, interactive computing notebooks.
It is the best way to serve Jupyter notebook for multiple users.
It is a multi-user Hub that spawns, manages, and proxy's multiple instances of the single-user Jupyter notebook server.
It can be used by students, faculty, corporate industries for data engineers.

What makes up JupyterHub?

4 subsystems make up Jupyter Hub!

1. A Hub
2. A configurable http proxy
3. Multiple single user Jupyter notebook servers.
4. An authenticator.

How does the subsystems help?

1. The Hub launches a proxy.
2. The proxy forwards all requests to the Hub by default.
3. The Hub handles user login and spawns single-user servers on demand.
4. The Hub configures the proxy to forward URL prefixes to the single-user notebook servers.

How to use the institution setup JupyterHub?

UNCG has setup a JupyterHub for the institution. Click here to launch the website.
The website requires the UNCG faculty or students to log into the website using the institution credentials (iSpartan ID).
If you are new to the website, you may explore the website using the quick links on the right side. Otherwise, simply click on “Sign in with Spartan ID.”



    This website is interesting as it has got several information loaded in it.
    If you would like to learn more about on how to use Jupyter notebooks, simply click on “ A gallery of interesting Jupyter Notebooks”.
    This link launches the GitHub page where you get to explore different types of Jupyter notebooks from introduction to advanced.
    Similar to this link, there are other links available that help you explore in different fields of the website.
    Do Not Panic! UNCG 6-Tech online service is available in case you encounter any problem or require any assistance using the website.

What to do after signing in?

After you successfully sign in, the website provides 4 different servers.

1. The minimal environment
2. Datascience environment
3. Spark environment
4. Jupyter Notebook Deep Learning Stack

Choose the server that fits your requirement and click on start.

Mininal environment!

For this tutorial, let us explore the minimal environment.

Once you click on start, it takes some time to launch the server. If you are a new user, it may take upto few seconds for setting up your server. As JupyterHub is an online programming server, it needs to create an instance under your account and pull the resources to your account.

Oops! but this looks like a Spark environment.

How do we change this? Simply click on Hub $-&gt;$ control panel.

Now, click on "Stop my Server". This stops the server you are currently working on and take you back to the environment selection tab.


Now, click on the server you would like to work on. In this case, let us use the minimal environment for our understanding.

First things first!

As this is an online programming service, it only comes with basic libraries. You may click on “+” icon and open the terminal.

In the terminal, using the “pip”, download as many libraries as you want for your project.

The main advantage of JupyterHub is, it lets you download most libraries as it is online and does not require additional compilers to read the libraries!

Lets look at some different libraries installed through 'pip' command

    The 'ggplot' library used in R language for data interpretation.

    The 'glmnet' library from R language that can also be used in python.

    The 'Pendulum' library used in python language.

We have another approach to install libraries for R language. +Click on R "Console"

    The installed packages look like this:

Along with the pros, there are cons associated with jupyterhub. Once you download the libraries required for your project, they are only valid for that session. Which means, you may have to redownload the libraries every time you log in to the website.
How to start using the notebook?

This website is flexible enough to let you create new Jupyter notebooks as well as import your previously created notebooks.
You may import your previously created Jupyter notebooks by clicking on this icon.
Otherwise, simple click on the above icon and create a new Jupyter notebook. You are all set to create your project.

Save your Jupyter notebook

After creating your notebook, click on File -> Save Notebook. The successfully saved notebooks can be viewed and edited every time you login to your account. Every time you make changes to your notebook, you must save the changes using the shortcut “ctrl+s”. Instead of manually saving each notebook, simply click on Save all. It saves all your notebooks.

Log out of your server!

To log out from your account on JupyterHub, click on Hub -> log out. This successfully logs you out of the server.

For any help related to using this website, you may click on this link: https://uncg.service-now.com/support

