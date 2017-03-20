


    ███╗   ███╗██╗   ██╗███████╗██╗ ██████╗██╗     ██╗███████╗████████╗███████╗██████╗ 
    ████╗ ████║██║   ██║██╔════╝██║██╔════╝██║     ██║██╔════╝╚══██╔══╝██╔════╝██╔══██╗
    ██╔████╔██║██║   ██║███████╗██║██║     ██║     ██║███████╗   ██║   █████╗  ██████╔╝
    ██║╚██╔╝██║██║   ██║╚════██║██║██║     ██║     ██║╚════██║   ██║   ██╔══╝  ██╔══██╗
    ██║ ╚═╝ ██║╚██████╔╝███████║██║╚██████╗███████╗██║███████║   ██║   ███████╗██║  ██║
    ╚═╝     ╚═╝ ╚═════╝ ╚══════╝╚═╝ ╚═════╝╚══════╝╚═╝╚══════╝   ╚═╝   ╚══════╝╚═╝  ╚═╝
      

 
 
 Music Lister automatically generates spotify playlists and places them in a users account. This
 project was created to learn and brush up on various development languages and tools. Please
 feel free to play with this code and try to make something to cool and we can build something fun 
 together.
 

## Installation


#### Spotify 
You must have a Spotify account (free or premium)

#### Node.js Setup
These examples run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. You can also follow [this gist](https://gist.github.com/isaacs/579814) for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

    $ npm install

	
## Running Music Lister
In order to run Music Lister, CD to 'MusicLister' directory in the folder you cloned to and run app.js with node

    $ cd c:/MusicLister/
    $ node app.js

Then, open `http://localhost:5000` in a browser.

### Using your own credentials
The examples contains a working client ID and secret key. Note, however, that they might be rate limited if they are used frequently. If you are planning to create an application, it is recommend you register your app and get your own credentials instead of using the ones in this project.

Go to [My Applications on Spotify Developer](https://developer.spotify.com/my-applications) and create your application. For the examples, we registered these Redirect URIs:

* http://localhost:5000(needed for the implicit grant flow)
* http://localhost:5000/callback

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in the examples with the ones you get from My Applications.

