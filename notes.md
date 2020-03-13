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



## Favorites
1. JS stores the active user as currentUser, and it instatiates with favorites list from the server.

2. When each story is drawn into HTML, the bookmark class should reflect the story's favorited status.

3. When adding a favorite, story should be added to both server favorites and currentUser.favorites.

4. When removing a favorite, story should be removed from both server favorites and currentUser.favorites. (<- Removing from arrays is hard! Replace entire array?)