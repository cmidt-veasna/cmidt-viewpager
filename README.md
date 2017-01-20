# cmidt-viewpager

Polymer ViewPager support unlimited page content. If anyone happen to be working on Android before, Polymer Cmidt ViewPager is working in similar fashion.

## Install the CMIDT ViewPager

1. Make sure bower is installed.
2. Run the following command: `bower install https://github.com/cmidt-veasna/cmidt-viewpager.git --save`

## Define ViewPager

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="cmidt-viewpager.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cmidt-viewpager items="[1,2,3,4]" style="height:200px">
	<template>
      <div>
        <div style="width:30px; margin: 32px auto;">[[item]]</div>
      </div>
    </template>
</cmidt-viewpager>
```

For more information visit https://cmidt-veasna.github.io/polymer/components/cmidt-viewpager/

## Running Tests

```
$ polymer test
```

ViewPager is already define certain test scenario however it does not cover all the case. We will Update it in the future. To test
ViewPager run `polymer test` to under Cmidt ViewPager.
