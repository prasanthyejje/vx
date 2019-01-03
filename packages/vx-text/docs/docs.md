# @vx/text

<a title="@vx/text npm downloads" href="https://www.npmjs.com/package/@vx/text">
  <img src="https://img.shields.io/npm/dm/@vx/text.svg?style=flat-square" />
</a>

The `@vx/text` provides a better SVG `<Text>` component with the following features

* Word-wrapping (when `width` prop is defined)
* Vertical alignment (`verticalAnchor` prop)
* Rotation (`angle` prop)
* Scale-to-fit text (`scaleToFit` prop)

## Example

Simple demo to show off a useful feature. Since svg `<text>` itself does not support `verticalAnchor`, normally text rendered at `0,0` would be outside the viewport and thus not visible. By using `<Text>` with the `verticalAnchor="start"` prop, the text will now be visible as you'd expect.

```jsx
import React from 'react';
import { render } from 'react-dom';
import { Text } from '@vx/text';

const App = () => (
  <svg>
    <Text verticalAnchor="start">Hello world</Text>
  </svg>
);

render(<App />, document.getElementById('root'));
```


## Installation

```
npm install --save @vx/text
```


## Components



  - [Text](#text-)

## API



### &lt;Text /&gt;


<a name="Text__angle" href="#Text__angle">#</a> *Text*.**angle**&lt;number&gt;  

<a name="Text__capHeight" href="#Text__capHeight">#</a> *Text*.**capHeight**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>'0.71em'</td></td></table>

<a name="Text__dx" href="#Text__dx">#</a> *Text*.**dx**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>0</td></td></table>

<a name="Text__dy" href="#Text__dy">#</a> *Text*.**dy**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>0</td></td></table>

<a name="Text__innerRef" href="#Text__innerRef">#</a> *Text*.**innerRef**&lt;func&gt;  

<a name="Text__lineHeight" href="#Text__lineHeight">#</a> *Text*.**lineHeight**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>'1em'</td></td></table>

<a name="Text__scaleToFit" href="#Text__scaleToFit">#</a> *Text*.**scaleToFit**&lt;bool&gt;  <table><tr><td><strong>Default</strong></td><td>false</td></td></table>

<a name="Text__style" href="#Text__style">#</a> *Text*.**style**&lt;object&gt;  

<a name="Text__textAnchor" href="#Text__textAnchor">#</a> *Text*.**textAnchor**&lt;enum('start'|'middle'|'end'|'inherit')&gt;  <table><tr><td><strong>Default</strong></td><td>'start'</td></td></table>

<a name="Text__verticalAnchor" href="#Text__verticalAnchor">#</a> *Text*.**verticalAnchor**&lt;enum('start'|'middle'|'end')&gt;  <table><tr><td><strong>Default</strong></td><td>'end'</td></td></table>

<a name="Text__x" href="#Text__x">#</a> *Text*.**x**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>0</td></td></table>

<a name="Text__y" href="#Text__y">#</a> *Text*.**y**&lt;union(number|string)&gt;  <table><tr><td><strong>Default</strong></td><td>0</td></td></table>