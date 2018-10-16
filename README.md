# \<vo-location-selector\>
Responsive Toolbar for selecting a lat long location on a map. It supports the following actions:
- Search location using [AGIV Geolocation API](https://loc.geopunt.be/)
- Go the current location with the [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)
- Choose a location from the map (The map tool should handle this after the event is fired)

* wide view

![wide-view](https://github.com/DOV-Vlaanderen/polymer2-vo-location-selector/blob/assets/assets/images/vo-location-selector.png?raw=true)
* narrow view

![narrow-view](https://github.com/DOV-Vlaanderen/polymer2-vo-location-selector/blob/assets/assets/images/vo-location-selector-narrow.png?raw=true)
* narrow view opened

![narrow-view-open](https://github.com/DOV-Vlaanderen/polymer2-vo-location-selector/blob/assets/assets/images/vo-location-selector-narrow-open.png?raw=true)

Example:

```html

    <location-selector><vo-location-selector>

```

# \<vo-location-selector-vertical\>

* has the same functionality as above widget. The main difference is that the toolbar is aligned vertically and the searchbar is fixed at the bottom.

```html

    <vo-location-selector-vertical button-bar-theme="" opened="true"></vo-location-selector-vertical>

```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```
