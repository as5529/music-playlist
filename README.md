This project is for think41 online interview.
Approach for the given assesment :

1. Implement Navigation
   I9 build a simple music playlist app using HTML,CSS, and Javascript where users can add their favorite songs to a list.
   Once a song is added they can easily move between them using next and prev button. behind the scene, I track the currently playing song using a currentIndex variable.
   Clicking next increases the index and wraps around to first song when reaches the end. Similarly previous button gors back.

2. Jump to any song
   I added this ability by making all the songs clickable by add an onclick event to them. So when a song is clicked it updates the current song
   display by calling a function that sets that song as active. This makes easy fpor users to navigate direcly to song they want without having cycle through using buttons.

3. Deleteing songs
   To delete a song first we need to know which song to delete and we will add another onclick event to these song which will be linked to the
   delete function where we will remove the song from the playlist and update the currentIndex, as if the song being deleted will be the currsong then
   we will moive to the next song and if the sng being deleted will be the prev to curr song we will move the index -1.   
