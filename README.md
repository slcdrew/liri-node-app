# liri-node-app
LIRI is a node based Javascript application using Spotify, Concert This and OMDB API endpoints. 


LIRI is like iPhone's SIRI but it uses a Language interpretation and Recognition Interface instead of Speech Recognition. LIRI is a command line app that  takes in parameters and gives you back data.

### Commands to run LIRI
* node liri.js spotify-this-song `<song name here>`
* node liri.js movie-this `<movie title here>`
* node liri.js concert-this `<band or artists name here>`
* node liri.js do-what-it-says

### Spotify This
Uses the Spotify API to retrieve information about the song entered by the user:
* Song title
* Album
* Artist
* URL to Spotify to preview song

If user does not enter a song "The Sign" by Ace of Base will appear.

### Movie This
Uses the OMDB API to retrieve information about a movie entered by the user:
* Movie Title
* Release Year
* IMDB Rating
* Rotton Tomatoes Rating
* Country
* Language
* Plot
* Lead Actors

If user does not enter a movie title "Mr. Nobody" will be used.

### Concert This
Uses the Bands In Town API to find upcoming concert or show information for an artist or band entered by the user:
* Lineup
* Venue
* Venue Date
* Location

### Do What This Says
Reads information contained in the random.txt file and 'does what it says'. In this example it will run the Spotify function and populate the phrase 'spotify-this-song' and song title I Want It That Way.
