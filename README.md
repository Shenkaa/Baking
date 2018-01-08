# Baking

This is the third project in Udacity's Android Developer Nanodegree. In this Baking App, a user can select a recipe (provided by Udacity's resident baker-in-chief, Miriam), see the needed ingredients and video-guided steps for how to complete it.

Some of the app features:
* Tablet support
* Fullscreen video
* Can be used offline (with limitations)
* Widget with the ingredients of the last seen recipe

## Informations

Due to the high data consumption of the videos, the app can only be synchronized and videos / images displayed when `WiFi` is turned on. After a successful synchronization, the app can be used offline, but currently without videos and pictures.

## ToDo List

- [ ] Reduce the high data consumption of mp4 "streaming", especially on metered networks,
- [ ] or give the ability to download all clips of the selected recipe.

## Third-Party Libraries

* [ExoPlayer](http://google.github.io/ExoPlayer/)
* [Butter Knife](http://jakewharton.github.io/butterknife/)
* [Glide](http://bumptech.github.io/glide/)
* [Schematic](https://github.com/SimonVT/schematic)

## Credits

* App icon generated with [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/index.html)

## License

Licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
