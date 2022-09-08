 # Read & Talk

<p align="center">
    <img src="https://img.shields.io/static/v1?label=|&message=HTML5&color=a33550&style=plastic&logo=html5"/>
    <img src="https://img.shields.io/static/v1?label=|&message=CSS3&color=a33550&style=plastic&logo=css3"/>
<!--     <img src="https://img.shields.io/static/v1?label=|&message=SASS&color=2b625f&style=plastic&logo=sass"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=BOOTSTRAP&color=316c5e&style=plastic&logo=bootstrap"/> -->
    <img src="https://img.shields.io/static/v1?label=|&message=JAVASCRIPT&color=35a34d&style=plastic&logo=javascript"/>
    <img src="https://img.shields.io/static/v1?label=|&message=NODE.JS&color=35a34d&style=plastic&logo=node.js"/>
    <img src="https://img.shields.io/static/v1?label=|&message=EXPRESS&color=35a34d&style=plastic&logo=express"/>
    <img src="https://img.shields.io/static/v1?label=|&message=EJS&color=35a34d&style=plastic&logo=ejs"/>
    <!-- <img src="https://img.shields.io/static/v1?label=|&message=REACT.JS&color=35a34d&style=plastic&logo=react"/> -->
    <!-- <img src="https://img.shields.io/static/v1?label=|&message=REACT.NATIVE&color=35a34d&style=plastic&logo=react"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=TYPESCRIPT&color=4a935c&style=plastic&logo=typescript"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=PYTHON&color=52985b&style=plastic&logo=python"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=JAVA&color=cdf998&style=plastic&logo=java"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=SOLIDITY&color=8fbc56&style=plastic&logo=solidity"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=SELENIUM&color=cdf998&style=plastic&logo=selenium"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=AWS&color=98bf53&style=plastic&logo=amazon"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=WORDPRESS&color=cdd148&style=plastic&logo=wordpress"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=ADOBE&color=98bf53&style=plastic&logo=adobe"/> -->
    <img src="https://img.shields.io/static/v1?label=|&message=MONGO-DB&color=359ba3&style=plastic&logo=mongodb"/>
<!--     <img src="https://img.shields.io/static/v1?label=|&message=WEBPACK&color=bbb111&style=plastic&logo=webpack"/> -->
<!--     <img src="https://img.shields.io/static/v1?label=|&message=LINUX&color=bbb111&style=plastic&logo=linux"/> -->
    <img src="https://img.shields.io/static/v1?label=|&message=GIT&color=359ba3&style=plastic&logo=git"/>
<!--     <img src="https://img.shields.io/static/v1?label=|&message=FIREBASE&color=cbb148&style=plastic&logo=firebase"/> -->
</p>

https://read-and-talk.herokuapp.com/

Join online book clubs and be a part of communities that read and discuss your favorite novels.

## How It's Made:

On the backend, Read & Talk implements the MVC architectural paradigm to seperate the model, view, and control components of the server. This simplifies workflow and problem-solving, especially when working as a team. In addition, we seperated the routes into its own file to enhance the benefits from this seperation of concerns. Our server of choice for this project was MongoDB, for which we used Mongoose to create schemas.

On the frontend, Read & Talk uses EJS as a templating engine, which is rendered server-side using data asychronously retrieved from the database. In several pages, we used partials to display standard page components, including navigation.

Upon first entering our site, the user is presented with a sign up page. This is configured using the passport.js module. After the user creates a free account or logs in, they have access to a list of clubs. These clubs are created by other users, and joining a community enables options that allow the user to discuss and rate books. In addition, the user may to create clubs of their own. To do so, they fill out the form which, on submission, sends a POST request to our server and creates the club document in our database.

## Optimizations:

Future iterations of Read & Talk will see expansions to community features, including the introduction of comment and friend systems. In addition, while we used Google's Embedded Viewer API to display book information on each club page, this can be expanded to display additional content. For example, each club page will have an image containing the book cover, the author(s) name, synopsis of the story, and additional works from the author(s).

## Lessons Learned:

We learned a lot completing this website, which included both frontend and backend programming. It was extremely beneficial to write the code for both sides, as it helped us further our understanding backend architectural paradigms.