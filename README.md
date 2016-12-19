Tiny HTTPd
=================

Tiny HTTP Server by Wesley Tsai.

Features
-

* Including bootstrap/jquery/owl.carousel/semantic/googlefonts-gstatic/FontAwesome.

Installation
-

Use the npm to install the required modules.

cd ___`<project directory>`/___

npm install


***

### Run the app.js

    node app.js

History
-

所有index.html修改的紀錄都會備份到github:
https://github.com/jogoadmin/jogosite/commits/master

echo "# jogosite" >> README.md
git init
git add README.md
git commit -m "first commit"
git config --global user.email "wesleyboy42@gmail.com"
git config --global user.name "Wesley Tsai"
git commit -m "first commit"
git remote add origin https://github.com/jogoadmin/jogosite.git
git push -u origin master
git add index.html
git commit -m "first version for homepage."
git push -u origin master
git remote show origin

git clone https://User:Passwd@github.com/jogoadmin/jogosite.git
git add index.html
git commit -m "Test version for homepage."
git push https://User:Passwd@github.com/jogoadmin/jogosite.git --all

Rollback the commits to a specific commit version
git reset --hard 83c9cef
git push -f origin HEAD^:master

License
-
Licensed under the MIT License

Authors
-
Copyright(c) 2015 Wesley Tsai < <wesleyboy42@gmail.com> >
