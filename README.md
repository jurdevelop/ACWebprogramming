# Introduction project
With these codes you can make a website that shows playlists from different genres. The user can see information about the playlist and click on the link to visit the playlist. There is also a JavaScript function on the website that make possible that the user can filter the playlists by genre.

There is also an Spotify API inside the website. With this API it is possible to get standard information from a Spotify account. You can always change the scope of the data that you want from the Spotify API. As example you can make a Spotify playlist generator if you want to challenge yourself with the API.

## Get started with the Spotify API

## 1) Create an App, if you want your own App on Spotify
- Visit https://developer.spotify.com/ 
- Log in and create an app
- Enter http//localhost:8888/callback as the redirect uri
- Save your changes
- Copy down the following: Redirect uri, client id, client secret

## 1.1) You can use my client id, client secret that is written down in my project plan. Redirect URI is already setup 

## 2)  Install Auth Server
- Open the folder `API` in the terminal of your Macbook or Windows
- Navigate in the terminal to authorization_code folder `cd authorization_code`
- Install the dependencies `npm install` if this is not working then use this code `sudo npm install` (be carefull this gives you all te rights of your computer)
- Paste in the redirect uri, client id, and client secret you copied in step 1 or from my project plan in the file `app.js`. You can find this in foldor authorization_code

## 3) Run the API
- Open the folder `API` in the terminal of your Macbook or Windows
- Navigate in the terminal to authorization_code folder `cd authorization_code`
- Run the Server by using this code `node app.js`
- Now the API is active on http://localhost:8888 OR visit the API with the onepage website.

### How the API works

### 1)  Use the App
- Use the onepage website Discover the codes are in the ZIP file and use the Spotify API button 
  OR visit http://localhost:8888
- Click 'Log in with Spotify' and log in
- You can now see information about your Spotify user profile and visit your profile page