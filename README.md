[Font Awesome](https://github.com/FortAwesome/Font-Awesome) as a [PolymerElements/iron-iconset-svg](https://github.com/PolymerElements/iron-iconset-svg) component.

# Set Up pubsec.yaml
````sh
# bower
bower install fontawesome-iconset
# npm
npm install fontawesome-iconset
````
# Use

Be sure you import next items from your repositories something like

<link rel="import" href="iron-icon.html">
<link rel="import" href="iron-iconset-svg.html">

Link your custom component alongside with other Polymer dependencies (in index.html for instance)
````html
<link rel="import" href="packages/polymer_fontawesome/fa-all.html">
````
Use the iconset
````html
<iron-icon icon="fa:line-chart"></iron-icon>
````
You also can refer to an specific category of icons:
````html
<link rel="import" href="packages/polymer_fontawesome/fa-gender.html">
````
And use it like this:
````html
<iron-icon icon="fa-gender:venus"></iron-icon>
````

# Update

To update to the latest version of FontAwesome, just install node modules and run "update"
````sh
npm install
npm run update
````
Soon there will be a production script to export only the icons to be used (like the original [font-awesome-polymer-icons-generator](https://github.com/philya/font-awesome-polymer-icons-generator) but in node).
