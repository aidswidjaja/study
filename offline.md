---
title: Offline Copies
layout: default
nav_order: 10
---

# Offline Copies
## This guide assumes you have a basic understanding of Ruby development environments and Unix terminal commands

Some content like Cheat Sheets and Student-made Quizzes are downloadable as PDFs.

You also require the following dependencies:
- [RubyGems](https://rubygems.org/)
- [Ruby](https://www.ruby-lang.org/en/)
- [Bundler](https://bundler.io/)
- [Git](https://git-scm.com/) - which is preinstalled on many systems already

If you're on Mac, you might want to not affect the pre-installed system Ruby. You can use [RVM](https://rvm.io) to install multiple different versions of Ruby. You might also want to get [Homebrew](https://brew.sh) if you would like to make the process easier, but it isn't neccessary.


1. **Use a different version of Ruby (optional):**
```
rvm list
    # shows all installed versions
rvm use x.x.x
    # where x.x.x is the Ruby version number
which ruby
    # confirms which Ruby version you are now using
```

1. **Clone the repository:**
```
cd DIRECTORY-NAME 
    # replace DIRECTORY-NAME with the directory where you want to store the contents
    # or leave empty for user root directory 
    # (i.e C:\Users\Adrian and Jacinta on Windows
    # and ~/Macintosh HD/Users/Adrian on Mac are your root directories)
git clone https://github.com/aidswidaja/study
```
1. **Download the theme:**
```
cd study 
    # or replace 'study' with the name of your directory (if you have renamed it)
    # if you moved your directory under another folder, cd into that first
    # (i.e if you moved it under Documents, cd ~/Documents/study)
    # (i.e or if you renamed the folder to examstuff, cd ~/Documents/examstuff)
gem install just-the-docs
```
1. **View it in your web browser:**
```
jekyll serve
    # or
bundle exec jekyll serve
```
then navigate to `localhost:4000` in your preferred web browser. 

1. **Get the latest version of the document**
```
git pull origin master
```

If you have no idea about what any of this means, please don't try anything and [email me instead](mailto:adrian.marcus.widjaja@gmail.com?[ASC Enquiry]).