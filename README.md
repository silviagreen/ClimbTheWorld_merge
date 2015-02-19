
Dependences
===

	dependencies {
    compile project(':cardsUILib')
    compile project(':facebookSDK')
    compile project(':staggeredgrid_etsy')
    compile project(':tooltip_library')
    compile 'com.google.code.gson:gson:2.3.1'
    compile 'com.google.guava:guava:18.0'
    compile 'com.android.support:appcompat-v7:21.0.3'
    compile 'com.android.support:support-v4:21.+'
    compile 'com.google.android.gms:play-services:+'
    compile files('libs/Parse-1.8.0.jar')
    compile files('libs/ormlite-android-4.46.jar')
    compile files('libs/ormlite-core-4.46.jar')
    compile files('libs/sqliteassethelper-2.0.1.jar')
    compile files('libs/universal-image-loader-1.8.6.jar')
    compile files('libs/httpcore-4.3.3.jar')
    compile files('libs/httpmime-4.3.6.jar')
}
	

Add the following projects as modules:
* tooltip_library: https://github.com/sephiroth74/android-target-tooltip
* cardsUILib: https://github.com/nadavfima/cardsui-for-android
* facebookSDK: https://developers.facebook.com/
* staggeredgrid_etsy: https://github.com/etsy/AndroidStaggeredGrid

Jar files:
* Parse: https://parse.com/downloads/android/Parse/latest
* ORMLite: http://ormlite.com/
* Universal: Image Loader https://github.com/nostra13/Android-Universal-Image-Loader
* SQLite Asset Helper: https://github.com/jgilfelt/android-sqlite-asset-helper
* http: 
