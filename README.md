# \<seven-segment\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/WaveElements/seven-segment)

Polymer 2 seven-segment display

## Installation

```
bower install WaveElements/seven-segment --save 
```

## Usage

Use element `<seven-segment>` for single seven-segment display, and element `<seven-segments>` for displaying several symbols

See source and demo for usage

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="seven-segment.html">
    <link rel="import" href="seven-segments.html">
    <style>
      seven-segment {
        /* defaults */
        --seven-segment-color-on:  #FF0000;
        --seven-segment-color-off: #DDDDDD;
        --seven-segment-background-color: #FFFFFF;
        --seven-segment-width: 3rem;
      }
    </style>
    <seven-segment value="0" decimal></seven-segment>
    <seven-segment value="5"></seven-segment><br>
    <seven-segments value="2+2=22"></seven-segments>
  </template>
</custom-element-demo>
```
-->
```html
<style>
  seven-segment {
    /* defaults */
    --seven-segment-color-on:  #FF0000;
    --seven-segment-color-off: #DDDDDD;
    --seven-segment-background-color: #FFFFFF;
    --seven-segment-width: 3rem;
  }
</style>

<seven-segment value="0" decimal></seven-segment>
<seven-segment value="5"></seven-segment><br>
<seven-segments value="2+2=22"></seven-segments>
```
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

P.s.s

You can use <a target="_blank" href="https://docs.google.com/spreadsheets/d/1bjvQTReHz-7FZHLloPMIDj6eM_Z2qGyczVn1_DqBJnQ/">google spreadsheet</a> for calculate HEX values for symbols