# Google-places-API

Google places API demo app for android which lists surrounding Restaurants, Malls, ATM etc..

#### Setup :
1. Register for Google Places API Access key. Follow the steps [here] (https://developers.google.com/places/documentation/). And get one yourself.
2. Since I'm using Map in this app, get Access key for Maps as well. Here is the [documentation] (https://developers.google.com/maps/documentation/android/).

Add your Google places Access key in MainActivity.java, and also update location values.
        
    https://maps.googleapis.com/maps/api/place/nearbysearch/json?location=your_lat,your_long&radius=100000&sensor=true&key=your_key_here&types=
    
    
Add your map key in details.xml

    <com.google.android.maps.MapView
    android:layout_marginTop="10dp"
    android:id="@+id/mapView"
    android:layout_width="fill_parent"
    android:layout_height="250dp"
    android:apiKey="your_map_key"
    android:clickable="true" />


#### Dependency :
* Add [Action Bar Sherlock] (https://github.com/PradeepMS/ActionBarSherlock) library project.


### Screen shots :
![Alt text](http://pradeepms.do.am/GitHub-Images/placeUI.png "Main UI")
![Alt text](http://pradeepms.do.am/GitHub-Images/placeDetail.png "Detail UI")



