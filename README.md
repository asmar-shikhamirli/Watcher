# Watcher
Watcher is a movie recommendation and review app build using React for the front-end, express for the back-end, 
flask for handelling the recommendations and similar movies section, mongoDB for the database<br />


This project uses SurpriseLib for dealing with Cosine similarity based nearest neighbours algorithm for generating recommendations. <br />
For implimentation purpose dummy users are created using moviewlens 100K dataset. Each user has at least 20 movie ratings. 
<hr />

You can find the deployed version of the application from here: https://watcher-go.herokuapp.com/
# Features

Recommendations are based on similar users(UserBased Collaborative Filtering) and similar movies (itemBased colaborative filtering)
<br/>(in deployment the item based model exceeds the available memory limit on the free tier of Heroku so this has not been included)
<br/>
<br/>

<hr/>

## Similar Movies
If you like a movie you can easily look for more movies similar to the one you liked in the sililar-movies section available for all the movie-pages


<hr/>


## signin/sugnup with email <br>
Signin in with Google, Signin with Github have been tested in developement but have not been added to the deployed build yet.
<br/>


<hr/>

## Follow users to see their activity in your Feed<br />

  
  <hr />

## Search Movies and See their description, imdb ratings, budget, Earnings, director, cast etc.


  <hr />


## Add Movies to WishList
 

# Setup And Usage
Clone the repo or download and unzip it <br />
Use command propmt to navigate to the extracted folder<br />
Run <br />
<code> npm install </code><br />
navigate to the Client folder and run <br />
<code> npm install </code> <br />

For Developement <br />

#### For deployment npm was used so avoid using yarn to avoid the .loc file conflicts in deployment

in the root folder<br/>
<code>
// in  the root folder in the cmd run <br/>
npm run dev   <br/>// this will run both the client and the server in the same command prompt
</code> <br />
Otherwise to run the client and server seperately <br />
in the root folder run<br />
<code>nodemon server.js</code><br />
in another command prompt in the client folder run<br />
<code>npm start </code><br />

# Login Credentials
You can use either one of these methods 
<ul>
<li>
you can login with your Google or GitHub account
</li>
<li>
you can Sign up using any valid email (dosent have to be a valid email)
</li>
<li>
you can use this dummy user<br />
email : shikhamirova.29@gmail.com <br />
Password : salam123
</li>
</ul>
## To be done 
<ul>
  <li>Implement the notifications </li>
  <li>Implement chat with other users </li>
  <li>Edit user profile</li>
  <li>Delete reviews</li>
</ul>
