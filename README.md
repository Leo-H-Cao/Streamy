# Streaming App

A streaming clone of the Twitch built with React, Redux, RTMP Server, RESTful API. A user can navigate and see different streams; if authenticated through Google authorization he can create, modify or delete their own streams.

# The app consists of:

streams\api - where we fetch and save data

streams\client - the UI where we can create and view streams (note: the Google authorization only handles access to Create, Edit and Delete - without the authorization you can still run the client and watch a stream)

streams\rtmpserver - hosting the stream from OBS Studio

# and is dependent on (besides the node modules)

OBS Studio - open source for video streaming and recording

Google APIs - only for signin with 'gapi.auth2'

This project was design by Stephen Grider for 'Modern React with Redux' on Udemy. Coded & modified by Leo Cao.
