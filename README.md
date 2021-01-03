# Streaming App

A streaming clone of the Twitch built with React, Redux + Redux Thunk, RTMP Server, RESTful API. A user can navigate and see different streams; if authenticated through Google authorization he can create, modify or delete their own streams.

This project was designed by Stephen Grider for 'Modern React with Redux' on Udemy. Coded & modified by Leo Cao.

# The app consists of:

streams\api - where we fetch and save data

streams\client - the UI where we can create and view streams (note: the Google authorization only handles access to Create, Edit and Delete - without the authorization you can still run the client and watch a stream)

streams\rtmpserver - hosting the stream from OBS Studio

# and is dependent on (besides the node modules)

OBS Studio - open source for video streaming and recording

Google APIs - only for signin with 'gapi.auth2'

# Steps to run

1. Start the web server
   2.Start the RTMP server
2. Starte OBS on your system and setup a scene with audio and video sources
3. Start the react app
4. Navigate to localhost:3000 to access the app on a browser
