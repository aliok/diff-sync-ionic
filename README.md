Differential Synchronization - Ionic/Angular Example
============================================

## Problem

Usage of the AeroGear Sync Server with an Ionic/Angular client

## Solution

The AeroGear Sync Server an implementation of [Google's Differential Synchonrization](http://research.google.com/pubs/pub35605.html) by Neil Fraser.

AeroGear.js provides a client library to interact with the server, using both the JSON Patch and Diff-Merge-Patch protocols.

This demo will utilize the JSON Patch part of the library.


## Working Code Example

This demo is an [Ionic Framework]<http://ionicframework.com/> application.  Follow the directions below to get the example working.

### Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [AeroGear Sync Server - JSON Patch Version](https://github.com/aerogear/aerogear-sync-server#starting-the-json-patch-server)

### Installation

* Install Bower : `npm install -g bower`
* Install Gulp : `npm install -g gulp`
* Install Cordova and Ionic: `npm install -g cordova ionic`
* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

### Running / Development

Start up the Sync Server (see [here](https://github.com/aerogear/aerogear-sync-server#starting-the-json-patch-server)).

Once the Sync Server is running, do:

* `ionic serve`
* Visit your app at [http://localhost:8100](http://localhost:8100).

### Running on iOS

Start up the Sync Server (see [here](https://github.com/aerogear/aerogear-sync-server#starting-the-json-patch-server)).

Once the Sync Server is running, do:

* `ionic add platform ios` (once)
* Run on connected device or emulator : `ionic run ios`
* Run on emulator : `ionic emulate ios` 

For more information, see [Ionic's CLI documentation](http://ionicframework.com/docs/cli/run.html).

### Running on Android

Start up the Sync Server (see [here](https://github.com/aerogear/aerogear-sync-server#starting-the-json-patch-server)).

Once the Sync Server is running, do:

* `ionic add platform android` (once)
* Run on connected device or emulator : `ionic run android`
* Run on emulator : `ionic emulate android`

For more information, see [Ionic's CLI documentation](http://ionicframework.com/docs/cli/run.html).

### Building

* `ionic build ios` OR `ionic build android`
 
For more information, see [Ionic's CLI documentation](http://ionicframework.com/docs/cli/run.html).

### Further Reading / Useful Links

* [AeroGear Sync Server](https://github.com/aerogear/aerogear-sync-server)
* [Ionic framework](http://ionicframework.com/)
* [Ionic CLI](http://ionicframework.com/docs/cli/)


### Notes

This project is a port of official cookbook example of Aerogear Sync project. For the Ember based example, see <https://github.com/aerogear/aerogear-js-cookbook/tree/master/diff-sync-ember>.

And, yes, even this README.md file is copied from [there](https://github.com/aerogear/aerogear-js-cookbook/blob/master/diff-sync-ember/README.md).

Code here is only demonstration purposes. In a real world Angular project, you would have things separated.
Also, you'd employ [promises](https://docs.angularjs.org/api/ng/service/$q) and prefer [*'controller-as syntax'*](https://github.com/johnpapa/angular-styleguide#style-y032).

I didn't do those to keep things simple and only focus on Aerogear sync. 
You look like a cool Angular expert; you do the Angular best practices in your awesome project.

### License

Apache License 2.0.

See LICENSE file for more.

TODO: Youtube video
