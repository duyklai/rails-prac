Basic rails project execrise to help learn ins-and-outs of rails. Article forum features article listing, basic user interface (create, edit, delete), commenting, basic authentication (one layer), and taggings. 
Hosted locally and accessed by running: 

$ bin/rails server

And opening a web browser and entering in http://localhost:3000. New user can browse around the website and comment.

Only logged in user can create articles, edit, tag, and delete articles/tags. The first user (you) on the website can access the user create page with http://localhost:3000/authors/new and create his/her account. From there, the previous user can create other new user accounts as the "new user" link above no longer works when you are logged out. 