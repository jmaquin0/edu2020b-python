# Basic Concepts: Fork, Clone and Branch

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

Hit Ctrl+Shift+P in VSCode, type **clone**, paste the https clone url in the field box and finally select the created **Repositories** folder as the project location

![][3]
**Figure 3.** Clone repository

Hit the open button

![][4]
**Figure 4.** Open project

Install **open in browser** extension

![][5]
**Figure 5.** Install extension

Right click on the file **index.html**, select **Open in Other Browsers** and pick you favorite web browser

![][6]
**Figure 6.** Local Website

Github allows you to use your github repository as a website host if you create an additional branch named **gh-pages**. The forked repository already has a gh-pages branch but you will have to delete it and create it again in order to visualize your slides in a website

![][7]
**Figure 7.** Delete branch

![][8]
**Figure 8.** Create branch

Go to your web browser and open the url: 
https://d4n13lbc.github.io/reveal.js/

![][9]
**Figure 9.** Example website from GitHub

##  Activities
1. Check the reveal.js repository and do a presentation about another github open source project

1. Delete the created GitHub repository

## References
* https://revealjs.com

[1]: images/1_fork_highlighted.png
[2]: images/2_clone_url_highlighted.png
[3]: images/3_clone_repository.png
[4]: images/4_open_project.png
[5]: images/5_install_extension.png
[6]: images/6_local_website.png
[7]: images/7_delete_branch_highlighted.png
[8]: images/8_create_branch_highlighted.png
[9]: images/9_example_website.png