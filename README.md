FloatingLayout
===========

This project is an Extension from TouchSoftly https://github.com/t0mm13b/TouchSoftly
I am going to solve the following problems of the library 

1. The floating layout doesn't receive actions or touch events, the actions goes to the views under the one which drawn by this library. 
2. The layout disappear when the activity which launched the service killed.

Goals :

1. The FloatingLayout should receive actions besides other activities of other apps should takes their own actions and events
2. The layout shouldn't disappear until I want to disappear it, not when the activity that launchess the service be killed 