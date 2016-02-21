# SynIgniter
Better way to develop a modular application using PHP.


**Directory structure:**
* application/modules/sample/views
* application/modules/sample/controllers
* application/modules/sample/models
* application/modules/sample/js
* application/modules/sample/scss

## Instalation
For now, just download to your web server, set write permission and enjoy!
```
# Clone the project
git clone git@github.com:thenets/SynIgniter.git

# Set write permission
chmod -R 775 SynIgniter

# Rename to your application
mv SynIgniter my_app
```


### Recomendation: (optional)
If you want a better debug for SCSS, you can install the SASS Gem in developer enviroment:
```
# Install Ruby and gem manager
\curl -sSL https://get.rvm.io | bash -s stable --ruby

# Install SASS gem
sudo su -c "gem install sass"
```


### Future
- Documentation
- SASS support
- Coffee Script support
- (Any ideas? Let me know! :D )


### FAQ:

**Why the CSS and JS get ERROR 404?**

Probably your server are using some filter or mod_rewrite and don't allow SynIgniter to know the application path. To solve this problem, just go to "application/config/config.php" and set your application URL at "$config['base_url']".


### Special thanks
- Thanks a lot to wiredesignz, who create the CI HMVC, the base of my project! õ/
