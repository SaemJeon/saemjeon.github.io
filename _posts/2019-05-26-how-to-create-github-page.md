---
title: How To Create a Your Personal Webiste with GitHub Page and Jekyll
tags: [Website]
style: 
color: 
description: GitHub page is a great way to host your own website for free. Creating your personal website is easy with GitHub and Jekyll.
---

I've always wanted to build my own website, but I didn't know where to start. Creating own website from scratch to have a good UI and functionality can be time consuming. After some research, I found out that creating and hosting a website can be done easily by utilizing Jekyll and GitHub. Here are the steps of how I created my website (the one you are reading this post on).

## 1. Create GitHub repositroy
Make sure you name your GitHub repository with the following naming convention: `<GitHub username>.github.io`. This will be your URL to your website. 

## 2. Download Jekyll theme
Download Jekyll theme of your choice from [Jekyll Themes.](https://jekyll-themes.com){:target="_blank"} There are various themes you can choose from. Some themes are more suited for your purpose than others. 

## 3. Clone your GitHub repository to your local
Clone your GitHub repository you created in step 1 to your local folder. 
```
git clone https://github.com/username/username.github.io.git
```

## 4. Unzip the Jekyll theme and use the installation guide
Unzip the downloaded Jekyll theme and put all the files in your local folder created in step 3. Using the installation guide specific to the theme and remove some folders and files. For example, I am using portfolYOU theme, and the installation guide I used can be found [here.](https://youssefraafatnasry.me/portfolYOU/docs/){:target="_blank"}

## 5. Update the content of your website
Update the content of your website to include your information. I had to update `about.md` file under `pages` folder. Also, I added projects to `_projects` folder and update entire _data folder. There are few more locations you need to update to personalize, but you can easily figure out which ones to update.

## 6. Insall Ruby on your local
Install Ruby on your local if you don't have Ruby already installed. You can find the instruction from [Ruby Installation Guide.](https://jekyllrb.com/docs/installation/){:target="_blank"}

## 7. Compile your website
Once Ruby and Jekyll are installed from previous step, complite your website.
```
bundle exec jekyll serve
```
If this command gives you an error, do the following first.
```
bundle install
```

## 8. Check your website
Browse `http://127.0.0.1:4000/` to see your website!

---
It is very easy to create your own website! Using Jekyll and GitHub, you do not need to spend a lot of time trying to implement a pretty UI or good functionality. Jekyll has everything you need to get you started.