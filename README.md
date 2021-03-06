# Mist GPS for Android

Example software for getting started with Mist Node development. It demonstrates creating a Mist Node as an Android service.

## Prerequisites

* Android Studio (tested in 2.2.2)
* Wish - Peer-to-peer platform (download .apk)
* Mist - IoT layer for Wish (download .apk)

Download and install Wish and Mist.

You need to create a user in the Mist application when you first start it up. Swipe to the Users-tab and click the plus-sign in the bottom right corner. Write a user name you want to use, and an identity will be generated for you.

## First run

1. Clone this repository and open it in Android Studio
2. Attach a phone with Android 4.4 or newer
3. Deploy
4. Open the Mist UI on the device to see the GPS service (if you can't see the service, try to manually refresh the page by pulling down on the list and releasing)

## Known limitations

This is based on an android port of the Mist library, and is very limited in its capabilities, and you can probably break it is several ways. We will improve this API in due time. Currently this is only used for helping developers get started without access to Mist based hardware.
