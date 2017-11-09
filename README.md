# Hello Recipeers!

![from zapier](https://cdn.zapier.com/storage/blog/1493b5cec9773fe7017b5980f40b8fa8.1800x1000.jpg)

<br>

**-Recipeers is a social media app for discovering and sharing recipes.** by [Amanda Freeman](https://github.com/mandafae),  [Dylan Thorwaldson](https://github.com/DTThor), [Michael Quiroz](https://github.com/cocomjolk), and [Rachel Cavin](https://github.com/Rmcavin). It was built in a week for our Galvanize quarter 2 project.

**-Our goal** was to create a platform for users to find, share, and try new and interesting recipes with friends and followers. 

Food is a common and popular topic on social media but existing options don't facilitate easy recipe sharing.

## Technologies:

Server:
* Node.js
* Express

Middleware:
* body parser
* method override
* cookie session
* cookie parser

Database:
* PostgreSQL
* Knex - used as SQL query builder

Additional:
* [Heroku](http://www.heroku.com) - used for deployment
* [Cloudinary](https://cloudinary.com/) - for image upload and storage
* [Materialize](http://materializecss.com/)

<hr>

### Challenges:

* Routes

* Joins - Determining how to create complex joins using knex. Translating working SQL queries to knex.

* Cloudinary - picture storage and display, upload widget

* Git feature branch workflow

* Authorization and Authentication

* Data not being passed around correctly between files, JSONB data storage

* Consistent image sizing and styling

<hr>

<br>

# Recipeers Walkthrough:

<br>

 ## 1. Create a profile

 <br>

 ![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508518616/createProfile_hakybt.png)
 <br><br>
 ![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508518592/createUsername2_l9mkzg.png)
 <br><br>
 ![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508518582/filloutForm2_tc1xh9.png)
 <br><br>
 ![cscreenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508518574/profilePic_f4zdui.png)

<br>

 ##  2. Add your own recipe

<br>

![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508519496/Snip20171020_2_uwxhgs.png)
<br><br>
![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508519499/Snip20171020_4_zcll6c.png)


<br>

##  3. Browse recipes

<br>

![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508521264/browse_n0ry3p.png)
![screenshot](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508522858/recipe1_aghyfq.png)

<br>


##  4. See your friends' recipes

<br>

![create profile](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508521259/homepage_jfjfmw.png)
![create profile](http://res.cloudinary.com/dcc5vb7ot/image/upload/v1508522859/recipe2_yq07ys.png)

<br>


# *Discover your inner chef. Become a Recipeer!*
