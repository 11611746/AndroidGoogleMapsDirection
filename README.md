# AndroidGoogleMapsDirection



You need to enable the following services
*MAPS SDK API
*DIRECTION API  (For Routing and polylines)
*BILLING (The routing... and polylines will only work if the Billing is enable)

*Create a new API Key and restrict key to MAPS SDK ANDROID and DIRECTION
*Copy the APIKEY and past it in MapsActivity.java and google_maps_api.xml file

*ADD the following Dependencies   
/*Google Maps Services*/
    implementation 'com.google.android.gms:play-services-maps:17.0.0'
    implementation 'com.google.android.gms:play-services-location:17.0.0'
    implementation 'com.google.maps.android:android-maps-utils:1.2.1'
    
/*This dependency will help us to find out the shortest path and will show directions using Polyline*/    
    implementation 'com.github.jd-alexander:library:1.1.0'    
        


*ADD some following permission in the manifest file
      <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
      <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
      <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
      <uses-permission android:name="android.permission.INTERNET" />
      <uses-permission android:name="com.google.android.providers.gsf.permission.READ_GSERVICES" />
      
      
