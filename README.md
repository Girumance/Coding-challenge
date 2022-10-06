
## Overview

This coding challenge consists of a single page web application that:
- Fetches osm data of a location from [Openstreetmap api](https://www.openstreetmap.org/api/0.6/map), given with the coordinates as (geolocation box)
- Has an integrated custom [express](https://expressjs.com/) server from which calls to the external API are performed
- Converts the data into GeoJSON using [Osmtogeojson](https://github.com/tyrasd/osmtogeojson)
- Flips latitude and longitude using [Geojson-flip](https://www.npmjs.com/package/geojson-flip)
- Displays the dataset on a map using [Leaflet](https://leafletjs.com/) and [React-leaflet](https://react-leaflet.js.org/)
- Shares state across components using [Redux](https://redux.js.org/)
- Uses [Tailwindcss](https://tailwindcss.com/) as a CSS framework
- Is designed having in mind modularity & scalability; Follows the latest coding standards guidelines
- Correctly performs data & error validation
- Tests the correct rendering of the form components using [testing-library-react](https://testing-library.com/docs/react-testing-library/intro/)


## Run locally :hammer_and_wrench:

To run the app locally, clone the repo and install the app using:

```
  $ git clone https://github.com/Girumance/Coding-challenge.git
  $ cd coding-challenge
  $ cd client
  $ npm install
  $ cd ..
  $ npm install
  $ npm run dev
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Unity testing :hammer_and_wrench:

To run the tests, after the installation run:

```
  $ cd client
  $ npm run test
```
