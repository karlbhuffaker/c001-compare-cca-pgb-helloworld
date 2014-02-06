c001-compare-cca-pgb-helloworld
===============================

Comparison of Chrome Cordova App (CCA) and Phonegap Build (pgb) and phonegap (pg) on windows for making Android Apps


Feb 6th, 2014

So on Feb 3rd I heard about Chrome Corodva Apps (CCA). Bit confused by the difference between webkit and chrome, but excited to find out that Google is looking into the whole html-javascript to mobile and desktop Apps situation that has been mainly phonegap for a few years. 

I have made thousands of personal Apps, but presently only have one on Google play store called "Teacher Browser". A multi-view Google Docs App, for monitoring several browser windows at once. Strange but it does work better when I load it from Chrome instead of from the standard Phonegap App, so I will look into the new cca platform.

First, as always, what is it like for beginners. Notice in cca that the config.xml file is outside of the www folder!

What about the index files: You can see them in this repo

pgb-index.html is simple since it is just a webpage (Phonegap Build)
pg-index.html is sort of confusing with several CSS fancy features that I have never liked (phonegap on your desktop)
cca-index.html is very simple and makes sense to any webpage designer (Chrome Cordova App)


Icons:

pgb - easy load one image on the website, unless you have a config.xml file then you manually load the images
pg -res icon or screen folders with subfolders. Well organized but a huge pain getting all those images sorted
cca - in www/assets folder one image and then a few more in the www/assets/icons folder 


Plugins:

pgb- just mention the plugin in the config.xml file and that is it start using it right away
pg - use command line to install the plugin from a file or git repo and the command line does all the work for you. Very cool
cca - Can use the command line for cordova style plugins but also has a few API's pre installed. Not yet sure how to use these. But will try to find out.




First Look Summary:

pgb- really simple, don't like that you can't zoom your app, but still great for students
pg - Lots of power, not easy to use on windows but you can make batch/cmd files to make this easier.
cca - looks great, looks easy. Sure wish Google would make an API that works with ADMOB. Real potential here to make this have the power of phonegap with some of the simplicity of Phonegap Build. 

My opinion winner Jan 6th, 2014. Phonegap Build for students.


Note: I will make a few more Chrome Cordova App repos if you search cca-helloworld




************************************************************************************************************

###Disclaimer: I spend my time getting complex things working in simple ways. I have no idea if I am doing anything correctly so please beware if you use my work. If you like this App and can hum, play or sing please help the musically illiterate, use a flash capable computer to add your favorite song at http://www.rocksetta.com 










