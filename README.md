
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
