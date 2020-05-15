# Live-Data-Backend

Main backend requests:

`POST https://live-data-covid19.herokuapp.com/api/v0/save-my-location BODY: "{uuid: {{UUID}} coordinates: {longitude: {{LON}},latitude: {{LAT}}}}"`

`GET https://live-data-covid19.herokuapp.com/api/v0/get-intersection?uuid={{UUID}}`

`GET https://live-data-covid19.herokuapp.com/api/v0/busy-times/:placeId`

`GET https://live-data-covid19.herokuapp.com/api/v0/get-user-positions?radius={{RADIUS}}&latitude={{LATITUDE}}&longitude={{LONGITUDE}}&uuid={{UUID}}`

List of APIs/Services:

- Mapbox (Provides map and allows for temporary geocoding)
- MongoDB Atlas ($200 credit from Github Developer Student Pack)
- Google Places ($200 monthly credit to spend on)
- Open Route (Limit of 250,000 monthly requests, no way to upgrade, provides routing for free, since google maps is expensive)
- HERE (Limit of 5000 monthly users, no way to upgrade unless contacting company, provides dynamically generated routes to avoid crowds of people )
- Redis (No Cost, I think)
- Heroku (No Cost, I think)
