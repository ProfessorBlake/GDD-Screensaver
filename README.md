# GDD-Screensaver
Scrolls through slides of GDD information for use on classroom screens.

# How to Use
Launch the website (https://professorblake.github.io/GDD-Screensaver/) and then click the "GO" button to make the broswer fullscreen and begin the slideshow.
You can advance the slides by pressing any key, but you may need to click the marquee along the bottom of the screen first because the "skip" function is on
the controller page, not the embeded pages.

# How to Update
- Clone the repo and create a new branch for your slide.
- Create a new folder inside "Slides". Create your website inside this folder.
- In the root level index.html file, add your new slide to the array of slides in the JavaScript section at the bottom:
```
var slidesArr = [
     "GDD",
     "Upcoming",
      Spotlight",
     "StudyAbroad"
]
```
- Push your branch and make a pull request. Someone should then test the branch for bugs, and merge when it's ready.
