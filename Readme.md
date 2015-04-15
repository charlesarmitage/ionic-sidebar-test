##Yeoman scaffold##

0. Have node-js & npm installed
1. Run: mkdir ionic-sidebar-test
2. Run: cd ionic-sidebar-test
3. Run: npm install -g generator-ionic-gulp
4. Run: yo ionic-gulp
5. Select the latest version of angular (e.g. 1.3.15)
6. Run: sudo gem install sass - to install sass
7. Run: gulp

App is hosted in web server and available in browser at:
http://localhost:9000/#/app/home

##Phonegap build##

1. Run: gulp -b
2. Run: cp config.xml www/
3. phonegap run android

TODO: Add copying config.xml to gulp build
