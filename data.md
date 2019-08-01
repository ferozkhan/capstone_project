<h2> Data for the solution </h2>

<h4>To find the optimal location for the new outlet, following steps will be taken.</h4>

<h2>Data collection</h2>

Most of the will be collected using foursquare api points. 
<ul>
 <li>To get user check-ins: https://api.foursquare.com/v2/venues/VENUE_ID/stats</li>
 <li>To search location: https://api.foursquare.com/v2/venues/search</li>
 <li>To explore outlet sorroundings: https://api.foursquare.com/v2/venues/explore</li>
</ul>

Outlets with higher check-ins and tips will be considred first. And their sorrounding will be explored to collect nearby venue details.
Then those venue details will be used to find potential optimal location for the new outlet.

Optimal location will be the one which has the highest similarity score with the sorroundigs of one of the existing and most busy outlet. 
