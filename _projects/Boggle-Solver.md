---
layout: project
title: Boggle Solver
featured_image: "/photos/BoggleSolver/Logo.png"
image_gallery: [/photos/BoggleSolver/Demo.mp4, /photos/BoggleSolver/animated.gif]
source_code: "https://github.com/CameronTrumpy/BoggleSolver"
summary: "Java based solver for use with multiplayer Boggle mobile game."
---
In 2019, I wrote a Java program which works alongside an emulated android device. This program quickly and accurately searches all word combinations possible given a match's auto generated boggle board, and then enters all words in at much faster than human speeds. It outperformed human opponents by 1000% and was able to easily win in game tournaments against high skill opponents. I didn't want to ruin anyone else's experience in playing the game, so I only tested it against human players who I knew.
<figure class="video_container">
  <video controls="true" allowfullscreen="true">
    <source src="/photos/BoggleSolver/Demo.mp4" type="video/mp4">
  </video>
</figure>
 Because the program utilizes the same dictionary set that is used by the game, it can achieve close to a perfect score on any given board, as long as the maximum number of words isn't too large. It searches the board arranged as a 2D array, and combines the use of a 2D traversal algorithm that compares sections of words to the dictionary until a full word is discovered in that location.
