# bowser-polymer 

A polymer element that wraps bowser and exposes a few useful bindable properties.

To install use: `bower install --save bowser-polymer`

[ LIVE DEMO AND API ](https://www.webcomponents.org/element/LssPolymerElements/bowser-polymer)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LssPolymerElements/bowser-polymer)

<!---
```
<custom-element-demo>
  <template is="dom-bind">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bowser-polymer.html">
    <link rel="import" href="../../demo/index.html">
    <div>
      <template is="dom-bind">
        <next-code-block></next-code-block>
      </template>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
        <h3>Bowser Demo</h3>

        <bowser-polymer name="{{name}}" version="{{version}}" is-chrome="{{isChrome}}" is-msedge="{{isMsedge}}" is-msie="{{isMsie}}"
            is-firefox="{{isFirefox}}" is-android="{{isAndroid}}" is-ios="{{isIos}}" is-opera="{{isOpera}}" is-mobile="{{isMobile}}"
            is-tablet="{{isTablet}}"></bowser-polymer>
        <h1>Properties</h1>
        <ul>
            <li> Name: [[name]]</li>
            <li> Version: [[version]]</li>
            <li> isChrome: [[isChrome]]</li>
            <li> isMsedge: [[isMsedge]]</li>
            <li> isMsie: [[isMsie]]</li>
            <li> isFirefox: [[isFirefox]]</li>
            <li> isAndroid: [[isAndroid]]</li>
            <li> isIos: [[isIos]]</li>
            <li> isOpera: [[isOpera]]</li>
            <li> isMobile: [[isMobile]]</li>
            <li> isTablet: [[isTablet]]</li>
        </ul>
```


