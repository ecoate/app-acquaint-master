Sandbox xamarin application.

In order to get this running from complete scratch, I
* downloaded the acquaint template from xamarin
* opened the native solution in VS 2015 update 2
* nuget package restore
* fire up emulator
* download gapps for the emulator
* dropped gapps zip on emulator home, installed/restarted
* got the api key situation figured out
* https://developer.xamarin.com/guides/android/platform_features/maps_and_location/maps/obtaining_a_google_maps_api_key/
* tweaked the code - none of the sample addresses were returning proper locations, so now we're defaulting to CNU for all the maps
