# Meet the TWEET App!

Tweet allows you to navigate between other users, follow and unfollow them using handsome and friendly interface that built with React Hooks and styled components.

## Home page

Home page is represented by custom component called Kaleidoscope that renders the application name with random styles every 2 seconds.


## Tweets Page

The Tweets page fetches an array of objects (users) from backend (in this example using mockapi.io) and then renders a user card for each if them. One request is limited by 3 objects. By clicking on “Load more” button you can send one more request.

## Filter

Filter allows you to sort by all users, users you’re following, and users you can follow.

## User card

 The user card contains an information about users 

- number of followers
- number of tweets
- avatar

and also a “Follow/Unfollow” button.

When you entering our application you get a “following” field on your local storage imitating an authorization. The field contains an array of users you’re following and when you click on “Follow/Unfollow” button the array and the counter of followers updating according to action you both on UI and backend. 