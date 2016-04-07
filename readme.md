# Instructions
Utilize a Feature Branch Git Workflow to work with your teammates to make two deployments to a live server on DigitalOcean. You should use git hooks to handle your actual code deployment.

## Release One

`index.php` should have a form with two inputs['title','file'].
`info.php` should display all PHP configuration information.
`readme.md` should detail out your process for deployment. This should include all steps that follow a **feature branch deployment** pattern.

File Structure
* index.php
* info.php
* readme.md

## Release Two

`index.php` Apply the bootstrap UI framework and dress up the page appropriately. The form should be configured to submit to `uploader.php`.
`uploader.php` should save the file to the `./uploadFolder` directory.
`readme.md` In addition to your deployment processes please detail out your installation process for configuring .

File Structure
* index.php
* uploader.php
* readme.md
* ./uploadFolder
