# spotipy-trending-playlists
I wrote this project for my 'web 3.0' final exam. I used python with the 'spotipy' library to retrieve data from Spotify and get information about tracks in most popular playlists. 

The aim of this project was to highlight a condition observed through years of use. 
Spotify relies on his capabilities of "deliver the right music at the right time". To do that they developed a complex system for extract data and predict 
users' next choices, maximizing their satisfaction. 

At a first glance we can observe that Spotify has "packed playlists" and "personalized playlists" both contents are organized by a mix of: 
  - Collaborative filtering: the system chooses which data to display according to similar users’ previous choices. (there isn’t information about how similar users     are verified, however they seem to rely on last.fm matching process).
  - Natural Language Processing: Elements like spoken language and country of origin have a huge impact on the way cultural products are chosen and displayed in         Spotify.
  - Audio Models: There are no in-depth information about how this model works (at this time) but we can observe from results that some of the available metadata       are information for the speed of the track the time signature and the key. Moreover we can observe some unconventional parameters for a track's "danceability",     "energy" o "speechiness". 
    
    In my humble opinion this last feature is pretty interesting. This need to find some labels to describe objectively something that is strongly intimate shows
    off how hard define a cultural product is. Before the huge digitalization process the relationship with music (or arts in general) was an intimate process of
    exploration. The brandization Spotify operated through the last years hugely affected the way music is consumed. Framed into a (western-life) everyday routine
    tracks are sorted and displayed in pre-made boxes for "morning motivation" or "workouts". In any of these cases lots of instructions intercourse from the moment     data are acquired to the moment they are delivered to users. 
    
    These instructions rule the way music is clustered and how the algorithm will choose the file to extract, but my question is: 
    isn't such a rigid system inherently biased?
    
    Some researches just tried to approach this field but the aim was to describe how it works and formulate questions about the state of art. I think that we           should operate on a much deeper level and discuss the structure itself. Spotify is the most used streaming service, the user's easiest way to grant access to
    large music catalogues. Seems clear that, if the system is biased, the culture delivered won't be 'tailored' and choices will be limited by a number of 
    unneeded instruction. 
    
    The experiment I have just completed is a preliminary work, useful to describe the state of art, according to this perspective.
    Data science and machine learning gave us great opportunities in cultural fields but we can't just limit ourselves to observe these newborn systems. We should 
    take a step back and discuss about the alternative models and their possible impact. I strongly believe in the 'democratization' carried by the net revolution,
    in terms of cultural education the removal of geographical limits is priceless. Trying to 'predict the feel' that a cultural product can give to a user 
    can generate an unfair system. So my interest is to find a system that doesn't rely on compex analysis of standardized parameters, making the machine learn and
    analyze only that few parameters that would make it able to chain contents. In other words, train it to build sequence of songs based on user's statements and 
    in-depth song analysis. 
    
    But, to be able to do that we first need to demonstrate this trend and measure how reliable these parameters are. 
    
    This preliminary research gets empirical foundations for theorical assumptions, showing that Spotify's model tend to cycle back and forth the same clusters.
    
** For code info and full in-depth please check the "Data-Process" file ** 
