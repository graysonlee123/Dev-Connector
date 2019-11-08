# Dev Connector
Dev Connector is a social site that allows developers to connect via discussion. Features registering, logging in, web tokens, react / redux. MERN stack application.

### Visit the deployed site [here](https://serene-crag-08288.herokuapp.com/)

## Dummy Account

Login with the dummy account if you'd like to check out the site without signing up.

Username: `test@test.com` <br/>
Password: `password`

## Routes
A list of the back-end routes includes:
- Register / Login
- Create / update profiles
- Get all profiles / by user id
- Get logged in user's profile
- Delete profile and user
- Add experience / education
- Delete experience / education
- Get user's GitHub repos
- Add post / delete post
- Get all posts / get post by id
- Delete post by id
- Like / unlike post by id
- Add / delete comment

## Dependencies
Axios | Moment | React | React Moment | React Redux | React Router DOM | Redux Thunk | UUID

## Pages

### Login / Register
Allows the user to create an account, or login to their existing account. Some routes throughout the site are protected and require authentication to access.

### Developers
Allows a user to view all the registered users on the site. This is the easiest way for people to connect, as profiles provide things like Twitter accounts and personal websites.

### Posts
View the most relevant discussion going on in Dev Connector. One can like, dislike, or comment on another user's post by viewing a post's discussion.

### Dashboard
The dashboard is where a logged in user goes to update their profile. Here, they can add experience, education, and edit their public appearance. In the *Edit Profile* page, the user can set a title, company, website, github username, and links to find themselves around the web.
