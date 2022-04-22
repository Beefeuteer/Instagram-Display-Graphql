# Instagram-Display-Graphql
 \
 \
You need to fill the .env to make this project work. \
 \
+To get the APP_ID and APP_SECRET you need to create an "instagram basic display" app from this site https://developers.facebook.com \
+After filling APP_ID and APP_SECRET Go to terminal and run "npm run dev" \
+Open the http:localhost:4000/get-auth-code on your browser \
+From the site that is open click to "connect to instagram" button on the top left \
+Then click allow. After that you will see 200 OK on the top left. Stay on the site and check the url for the code= \
+Get the code between "code=" and "#" sign at the end. \
+Then paste it to the AUTHORIZATIO_CODE on the .env file.
 \
+After that open http://localhost:4000/graphql on your browser.
+Go back to the project and find the text file inside named "query for apollographql" \
+Copy and paste all the text inside of it to the site that is on your browser. \
+click query GetShortToken and paste it to "SHORT_LIVED_AT =" on the .env \
+then run the GetLongLivedToken and paste it to "LONG_LIVED_AT = " on the .env \
 \
+After everything is filled you can use the "getProfileData" and "getMediaData" on the query to get the information about the profile. \

********* .env ********* \
INSTAGRAM_APP_ID = \
INSTAGRAM_APP_SECRET = \
REDIRECT_URI = https://httpstat.us/200 \
AUTHORIZATION_CODE = \
SHORT_LIVED_AT = \
LONG_LIVED_AT = \
********* .env ********* \
  
