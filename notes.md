# Hack OR Snooze API

## Users

## Stories
Request for stories returns a JSON string.
 {
      "author": "andrei",
      "createdAt": "2020-03-12T17:10:05.760Z",
      "storyId": "c94c7611-ba19-4df4-84a6-1d084d006b16",
      "title": "Itsa the Mario Bros",
      "updatedAt": "2020-03-12T17:10:05.760Z",
      "url": "https://pics.me.me/hey-its-a-the-mario-bros-mama-why-a-you-14044396.png",
      "username": "andrei"
    },

## JWT
 All endpoints require authentication using JSON Web Tokens (JWT), with the exception of reading stories and creating users, which are open to the public.

