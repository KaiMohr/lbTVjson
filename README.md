# Android TV Leanback Support

## Getting Started

- Open the project in [Android Studio][studio].
- Compile and deploy to your Android TV device (such as a Nexus Player).

Need more information about getting started with Android TV? Check the [official docs][getting-started].

## Explore the sample

- Choose a layout
  - Videos grouped by [category][mainfragment] (See BrowseFragment in [screenshots][screenshots])
  - Freeform [vertical grid][verticalgridfragment] of videos (See Vertical Grid Fragment in [screenshots][screenshots])
- Customize video cards with a [Card Presenter][cardpresenter] (See Card Views in [screenshots][screenshots])
- Display in-depth [details][detailsfragment] about your video
- Play a video
  - [Playback with ExoPlayer2][playbackfragment]
  - [Add extra buttons to control playback][videoplayerglue]
- [Display an error][errorfragment]
- Make your app globally searchable
  - Review searchable training [document][searchable]
     - Creating a [content provider][videoprovider]
     - Defining [searchable.xml][searchable.xml]
     - Receive search intent in [manifest][manifestsearch]
- [Search][searchfragment] within your app
- [Onboard][onboardingfragment] new users (explain new features)
- Customize [preference and settings][settingsfragment]
- Add a wizard with [guided steps][guidedstep]


## Additonal Resouroces

- [Android TV Introduction](http://www.android.com/tv/)
- [Android TV Developer Documentation](http://developer.android.com/tv)
- [Android TV Apps in Google Play Store][store-apps]

## Dependencies

If you use Android Studio as recommended, the following dependencies will **automatically** be installed by Gradle.

- Android SDK v7 appcompat library
- Android SDK v17 leanback support library
- Android SDK v7 recyclerview library

# lbTVjson
