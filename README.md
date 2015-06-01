# castable-video-player

An element with player controls for [google-castable-video](https://github.com/GoogleWebComponents/google-castable-video) web component.


## Installation

Install via [Bower](http://bower.io/) using:

    bower install castable-video-player


## Usage

Using the component is easy. First import the component source:

    <link rel="import" href="/bower_components/castable-video-player/castable-video-player.html">

Then add the code where you want the player to appear:

    <castable-video-player>
      <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/big_buck_bunny_1080p.mp4" type="video/mp4">
    </castable-video-player>


You can set the player size:

    <castable-video-player width="100%" height="400px">
      <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/big_buck_bunny_1080p.mp4" type="video/mp4">
    </castable-video-player>

