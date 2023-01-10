# ZeroPlasticList

This is the home of zero-plastic-list.de.

### Deployment to zero-plastic-list.de

Just commit to master branch. The changes will be automatically deployed on the webserver. This takes around 30s.

### Dev Enviroment @ Gitpod

Just open the repo with gitpod.

### Dev Enviroment @ Local

Not tested, but should work ;)
1. `composer install`
2. `bin/grav install`
3. `php -S 0.0.0.0:8000 system/router.php`
4. Open `http://localhost:8000` in your browser

### Add/Edit pages
The pages are managed with markdown files. You can find them here: `/user/pages/`.
This system is based on Grav cms. For more details to edit pages take a look here: 
https://learn.getgrav.org/17/content/content-pages