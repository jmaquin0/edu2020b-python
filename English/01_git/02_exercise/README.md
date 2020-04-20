# Basic Concepts

## Exercise 1

In this exercise we will learn the concepts
of fork, brach, and clone. We will also learn about a technology for creating slides that can be stored in github and viewed in any internet browser.

Go to the url https://github.com and create a Github account.

Log in your account.

Go to the url https://github.com/hakimel/reveal.js and Fork the repository into your personal account

![][1]
**Figure 1.** Fork

Go to your forked repository and copy the https clone url. The ssh url allows you to perform actions in your repository without having to enter the password each time, we will explain later how to create an use a ssh key.

![][2]
**Figure 2.** Clone URL

Create a new folder called **Repositories** in your Documents folder

Do a git clone of the forked url
```console
➜  git clone https://github.com/d4n13lbc/reveal.js.git
Cloning into 'reveal.js'...
remote: Enumerating objects: 173, done.
remote: Counting objects: 100% (173/173), done.
remote: Compressing objects: 100% (93/93), done.
remote: Total 13001 (delta 90), reused 136 (delta 74), pack-reused 12828
Receiving objects: 100% (13001/13001), 11.21 MiB | 2.25 MiB/s, done.
Resolving deltas: 100% (7285/7285), done.
```

Get into the reveal.js folder and open the index.html file in your favorite browser

```console
➜ cd reveal.js
➜ firefox index.html
```

Github allows you to use your github repository as a website host if you create an additional branch named **gh-pages**. The forked repository already has a gh-pages branch but you will have to delete it and create it again in order to visualize your slides in a website

![][3]
**Figure 3.** Delete branch

![][4]
**Figure 4.** Create branch

```console
➜ firefox https://d4n13lbc.github.io/reveal.js/#/1
```

![][5]
**Figure 5.** Example website

##  Activities
1. Check the reveal.js repository and do a presentation about another github open source project

1. Delete the created GitHub repository

## References
* https://revealjs.com

[1]: images/1_fork.png
[2]: images/2_clone_url.png
[3]: images/3_delete_branch.png
[4]: images/4_create_branch.png
[5]: images/5_example_website.png
