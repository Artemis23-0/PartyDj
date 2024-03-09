# Party DJ

## Proposed Architecture
The architecture of this application will be composed of an HTML, CSS, JS, and Python front end and a MongoDB (NoSQL) backend.
Spotify Web Development APIs will be used as well for functionality that is otherwise out of scope for this project.

## Database Schema (Initial)
The schema itself is relatively simple. Each user will have a profile, which is a username and password. Each user will also have "collaboration sessions" attached to their profile. 
These collaboration sessions have the users who were a part of the session as well as the songs played.

## Routes & HTTP Methods (Initial)
Login Page -- POST, GET
Queue Page -- POST, GET, UPDATE
Past Sessions -- GET

## Routes & Webpage Functionality (Initial)
Login Page -- User authentication
Queue Page -- Create session, join session, view queue, add/remove/skip/play/reorder song, search, song recommendations
Past Sessions -- View past sessions and songs in those sessions
