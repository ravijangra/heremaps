# heremaps

1. Import the OAuth-Usage.postman_collection in Postman Client
2. Select "GET HERE Map OAUTH Token" request
3. Go to Authorization and update following parameters by your own credentials received from your HERE Maps account
- Consumer Key
- Consumer Secret
4. Send the Request

YOU SHOULD GET A access_token successfully

How to use the token

1. Select "Get Base Tiles" request
2. Go to Authorization and update the access token received in previous request
3. Send the Request

YOU SHOULD GET the map tile successfully
  
