# secure-random

`<secure-random>` A polymer element to retrieve a subscription key from Firebase.

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/secure-random)

[Source](http://github.com/hekahouse/secure-random/)


## Install

    bower install --save HekaHouse/secure-random

## Example

    <secure-random
      subscription-key-path="https://YOUR-FIREBASE.firebaseio.com/SUBSCRIPTIONS/"
      subscription-id="SUBSCRIPTION-ID"
      subscription-key="{{subscriptionKey}}">
    </secure-random>

In the above example replace YOUR-FIREBASE SUBSCRIPTIONS and SUBSCRIPTION-ID with appropriate values from your Firebase.

## Note

Upon successful retrieval subscriptionKey is populated with relevant key

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

secure-random depends only on firebase-element from Google

## Related
