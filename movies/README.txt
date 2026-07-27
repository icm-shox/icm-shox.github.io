ICM-SHOX movies
===============

Put your video files here. The Movies section of index.html expects:

  movie01.mp4
  movie02.mp4
  movie03.mp4
  movie04.mp4

To change a filename or add more players, edit the <video> blocks in the
"Movies" section of index.html (search for id="movies"). Each player is a
standard HTML5 <video> element:

  <video controls preload="metadata" poster="images/pic01.jpg" ...>
      <source src="movies/movie01.mp4" type="video/mp4" />
  </video>

Tips:
- MP4 (H.264) plays in every modern browser. WebM also works (type="video/webm").
- The "poster" image is the still shown before playback -- swap in a real frame.
- Update the caption text (the <em> line under each video) to describe each movie.
- Movies published with the papers are available in the journal/arXiv
  supplementary materials; personal movies can simply be copied into this folder.