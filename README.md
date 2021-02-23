# storyForWebsite
Story like gadget generated only with Javascript

It's not an efficient way of making a story for a website, but I did it as an exercise.

I generate all the CSS with javaScript and used javaScript for actions on the story bar. Google Chrome works fine, but if you change to Firefox or another browser, you may experience some/or a lot of frame drops.

Functions:
- when a story is clicked, the link rotates, and the background appears with the video for the first story, and images for the story 2 and 3; The text associated with each story appears too
- there's a timeline that loads depending on the time you set for each story. When the time you set for a story ends, if there's a video playing, the video will be stopped and will be forwarded to the next story chronologically. If you started with story 2, story 1 will not be playing; if you have played a story, the white border around each story link from the beginning will disappear
- in reality, there are 2 timelines, when 1 is playing the other one is hiding. This helps to restart each animation of the red timeline and be able to animate it again
