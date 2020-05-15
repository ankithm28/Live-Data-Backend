# Live-Data-Backend

Main backend requests:

`POST https://live-data-covid19.herokuapp.com/api/v0/save-my-location BODY: "{uuid: {{UUID}} coordinates: {longitude: {{LON}},latitude: {{LAT}}}}"`

`GET https://live-data-covid19.herokuapp.com/api/v0/get-intersection?uuid={{UUID}}`

`GET https://live-data-covid19.herokuapp.com/api/v0/busy-times/:placeId`

`GET https://live-data-covid19.herokuapp.com/api/v0/get-user-positions?radius={{RADIUS}}&latitude={{LATITUDE}}&longitude={{LONGITUDE}}&uuid={{UUID}}`

List of APIS/Services:

- Mapbox
- MongoDB Atlas
- Google Places
- Open Route
- HERE
- Redis
