<<<<<<< HEAD
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.google.maps.android/android-maps-utils/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.google.maps.android/android-maps-utils)

# Google Maps Android API utility library

## Introduction

This open-source library contains classes that are useful for a wide
range of applications using the [Google Maps Android
API](http://developer.android.com/google/play-services/maps.html).

The library is under heavy development, but ready for use. Check the
[issue tracker][issues] to see what's happening.


## Usage

When you use Gradle add the following dependency with the latest version
to your `build.gradle` file to use the library:

```groovy
dependencies {
    compile 'com.google.maps.android:android-maps-utils:x.y.z'
}
```


## Read more and get started

Read more on the [website][website].

[issues]: https://github.com/googlemaps/android-maps-utils/issues
[website]: http://googlemaps.github.io/android-maps-utils/



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/googlemaps/android-maps-utils/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

=======
# JavaDoc regeneration

Check out the repository into two different directories. One needs to be
on master, one needs to be on gh-pages.

    $ javadoc -nodeprecated -stylesheetfile ../amu-web/css/javadoc-base.css -nonavbar -bottom '<script src="//www.google.com/js/gweb/analytics/autotrack.js"></script><script>new gweb.analytics.AutoTrack({profile: "UA-12846745-19",heatMapper: true});</script>' -top '<a class="back" href="javascript:history.back()">Back</a> <a class="back" href="/android-maps-utils/" target="_top">Back to site</a>' -notimestamp -d ../amu-web/javadoc/ $(find library/src/ -name '*.java')

# Staging edits

    $ sudo gem install jekyll
    $ jekyll serve --baseurl

Navigate to http://$HOST:4000/android-maps-utils/

![Analytics](https://maps-ga-beacon.appspot.com/UA-12846745-20/android-maps-utils/gh-pages/readme?pixel)
>>>>>>> refs/remotes/googlemaps/gh-pages
