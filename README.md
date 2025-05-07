# Website Backend

This is the hugo respository of the academic website of the Intelligent Video & Perception Group. You can follow this guidance to edit and publish content on our website.

### 1. Install Hugo

Install hugo from official site: https://gohugo.io/

### 2. Clone this Repo

`git clone git@github.com:PKU-IVP/website_backend.git`

### 3. Edit the Content

`cd website_backend`

Start a local hugo server for website preview:

`hugo server --watch`

Then you can view the site on `http://localhost:1313`

You can edit the content by markdown in `\content` directory, the modification will be updated on local site in real time

For more usage of hugo, you can view:

https://gohugo.io/documentation/

https://olowolo.com/post/hugo-quick-start/

### 4. Generate and Deploy

After modification, generate the static page (html/css style):

`hugo`

Then you can get the static source on `\public` folder

Clone the github page repo:

`git clone https://github.com/PKU-IVP/pku-ivp.github.io`

Copy the new content to github page repo:

`cp -r .\public\* The_directory_of_pku-ivp.github.io`

Deployment:

`cd The_directory_of_pku-ivp.github.io `

`git add .`

`git commit -m "[+]Update website with XXXX"`

`git push -u origin master`

### 5. Don't Forget to Update this repo
