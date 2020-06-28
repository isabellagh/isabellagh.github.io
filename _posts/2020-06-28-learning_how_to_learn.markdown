---
layout: post
title:      "Learning how to learn"
date:       2020-06-28 18:15:08 +0000
permalink:  learning_how_to_learn
---


   I started the Bootcamp weeks ago and so much has happened. Despite all the covid19 "missing and end" still going on, it has been an amazing time learning from variables to object-oriented and classes and @@all that. I am still trying to learn how to organize my time/day by being a working mom, wife, and part-time software engineering student. I have learned so much about ruby, and the more I know, the more I know how much I don't know. I am learning how to learn. Learning how to study the lessons and labs, I just found out, the hard way, that if I start my project at the beginning of the lessons I can practice each subject, understanding in a real object and at the same time work on something presentable for the project. I was so focused on finishing the labs that I didn't really create anything and so some of the subjects I learned were forgotten. I was constantly going back and forth on the lessons, which I am sure it is normal, so I can grasp what I am trying to code. Well, we definitely get better making errors, and since fixing errors is gonna be my future job routine I think I am on the right path. I am excited about coding, learning new concepts, and getting the code to work, especially, It really puts a smile on my face.

    During my cli project, I started with too many ideas. I changed my mind a couple of times until finally end up with a Baltimore food truck finder, which my husband asked me if I could make an app for the food truck of the restaurant he works for and I liked the idea. I thought about working on getting data from other food trucks first. That way I would learn about scraping data from web sites and later on build the personalized app for a single food truck. 
 I think I over complicated the project and took me a long time to start coding. I also wasted a lot of time trying to set up my environment, with no success. My project had to be done on IDE, which is kind of dangerous because it does not automatically save your work. My advice is to set up the environment as soon as possible and work on your projects through your text editor. Anyways, my project did not meet my expectations but it helped me to understand how coding really works and taught me how to learn for the next projects. 

   Something that will help you very much and make your work a lot faster is knowing how to set up your work environment with Ide and create a git repository. I am going to go over some of the most important steps to make your code work.

    Simple and Important things to know for your CLI project.
1. First, you have to find a `Sandbox` on your cli project learn page (it can be any sandbox you want);

2. Once you have your sandbox opened, go to the terminal and type: `bundle gem <name_of_your_project>`   This command will make all the folders you need to start. 
2a. `Do you want to generate tests with your gem?`  It will ask you if you want to create test files, you do not need them for the project itself but it is good to make your own tests. 
2b. `Do you want to license your code permissively under the MIT license?` "This means that any other developer or company will be legally allowed to use your code for free as long as they admit you created it."  It is definitely good to say yes.
2c. `Do you want to include a code of conduct in gems you generate?` "Having a code of conduct means agreeing to the responsibility of enforcing it, so be sure that you are prepared to do that. Be sure that your email address is specified as a contact in the generated code of conduct so that people know who to contact in case of a violation." You also want to say 'yes' for this last question.

3. After it finishes running the bundle gem it will creat your workspace. You should have a folder called `Development` even before the bundle gem. Inside the 'Development' folder is your `bin` folder (`console` and `setup` files inside of it). Should have a `lib` folder (with a `file.rb ` named after the name you chose in bundler gem, a `folder` named after the name you chose in bundler gem (this folder is where all your "classes" files will be created) with a `version.rb` file inside of it. 

4. Bundle gem creates and sets up all the other files: `CODE_OF_CONDUCT`, `gemfile`, `gitignore`, `LICENSE.txt`, `rakefile`, `README.md` (you have to type your own), and  `work.gemspec`. 

5. Learn how to navigate with Bash Ide on this page: "https://learn.co/lessons/navigating-with-bash-ide". It is super helpful as well.

6. After you have some code up and running you should create a git repository on github. You have to go to your github account, you can create it on your command line but I personally think going to github is gonna remind you to save your work later on. Click on the `+` sign on the top right of your page and then `new repository`. You have to give a  `Repository name` It can be the name of your project folder or some other name that relates to your project. you can make the repository public or private. Ok, you have created your repository, now you have to let your Bash Ide (command line) know by copying and pasting the code snippet that looks like `git remote add origin https://github.com/iyour_name/test.git` after running the code snippet you go back to github and copy the push command `git push -u origin master` (you only need this once).

7. Ok. now you are all set. Remember to save your code by typing in the command line `git add .` , `git commit -m 'message_name'` and last `git push`. Type one at a time in this order and your code will be sent to your github repository. It is always good to make sure your code is there, you can go to your repository page and check your files, just in case. 

I hope this blog can help you get started on your CLI project.  

Happy codding!






