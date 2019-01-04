### SSERPDROW
We were tasked with creating an application where users(companies/organizations)can create web pages and blogposts. Visitors can view all web pages and blog posts for all companies without logging in.

# Team Prompt :
Build an application for Swedish web-conglomerate Sserpdrow! Your application's "users" will be companies/organizations that want to have their own company blog and web pages and they are going to use your application to CRUD their own "blog posts" and "web pages". When a user logs in, they should see a dashboard that lets them CRUD their "blog posts" and "web pages". Your application will also likely have “visitors” that just go to your site and want to consume (read) the content that your “users” (companies/organizations) have provided. When a "visitor" goes to your site, they should be shown a list of companies/organizations to view.

Live application link:https://team-zorro.github.io/team-zorro-client/
Back end repository: https://github.com/Team-Zorro/team-zorro-server.git

### Planning Docs

ERD
[Alt ERD](IMG_5984.JPG?raw=true)

## API Routes
API end-points
Verb	URI Pattern	Controller#Action
POST	/sign-up	users#signup
POST	/sign-in	users#signin
DELETE	/sign-out/:id	users#signout
PATCH	/change-password/:id	users#changepw
GET	/blogs	blogs#index
POST	/blogs	blogs#create
PATCH	/blogs/:id	blogs#update
DELETE	/blogs/:id	blogs#destroy
GET	/websites	websites#index
POST	/websites	websites#create
PATCH	/websites/:id	websites#update
DELETE	/websites/:id	websites#destroy
