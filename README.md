How to use
========

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://github.com/Goddchen/mvn-repo/raw/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile "com.actionbarsherlock:actionbarsherlock:4.3.1"
        compile "com.android:volley:1.0"
        compile "com.actionbarsherlock:viewpagerindicator:2.4.1"
        compile "com.jeremyfeinstein.slidingmenu:slidingmenu:1.3-SNAPSHOT"
        compile "org.holoeverywhere:holoeverywhere:1.6.8"
        compile "org.holoeverywhere:addon-preferences:1.6.8"
        compile "org.holoeverywhere:addon-slider:1.6.8"
    }
