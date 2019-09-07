#Creating a Scaffold web APP in node JS
```
echo 1 | sails new HW2_Application_DUMMY
```
#Uploading to git
```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/gmchowdary/HW2_Application_DUMMY_WEB_APP.git
git push -u origin master
```


#Commands to execute on webserver to setup a webapp
```
sudo apt-get update -y
sudo apt-get install nodejs npm -y
sudo npm install -g sails
```

#Cloning a git repository
```
mkdir ~/srv
cd ~/srv
git clone https://github.com/gmchowdary/HW2_Application_DUMMY_WEB_APP.git
cd HW2_Application_DUMMY_WEB_APP
npm install --save
```
#starting the process
```
sudo npm install forever -g
forever -w start app.js
```
