Concept behind Seeker is simple, just like we host phishing pages to get credentials why not host a fake page that requests your loction just like many popular location based websites.

Seeker Hosts a fake website on In Built PHP Server and uses Ngrok, website asks for Location Permission and if the user allows it, we can get :

Longitude
Latitude
Accuracy
Altitude - Not always available
Direction - Only available if user is moving
Speed - Only available if user is moving
Along with Location Information we also get Device Information without any permissions :

# geolocate_seek

Thanks thewhiteh4t/seeker
