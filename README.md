Feed Me!
========

*Feed Me!* is a mashup of the following APIs:

* [Yelp](http://www.yelp.com/developers/documentation)
* [IP-API Gelocation](http://ip-api.com)
* [Google Maps Embed](https://developers.google.com/maps/documentation/embed/guide)

The typical process of execution is as follows:

1. The user's location is established using the IP-API Geolocation API.
2. Along with user input, the location is passed to the PHP script (api_call.php)
3. api_call.php processes the request to the Yelp API and returns an Array of JSON Objects.
4. The JSON Array is processed in the script.js file on the return of the AJAX $.post request.
5. A Google map is constructed using the location details returned from the Yelp API response.
6. The DOM is then updated with the relevant data.

I will be hosting this intial beta version (essential just an API mashup/experiment) on a personal server tonight (9/5).

[Demo](http://feed-me.paultheberge.com)
