# d3_basics

I feel like learning d3 today so thats what i'm doing
Also a good chance to get good with using .md files
https://www.udemy.com/the-advanced-web-developer-bootcamp/learn/lecture/7706404#overview

### Basic d3 dom stuff

- select elements in the dom with

  - d3.select() //selects single
  - d3.selectAll() //selects multiple
  - returns Selection obj
  - selection.nodes() - returns an array of matching html elements or selection.node
  - most of the time in d3 you dont want to access the elements directly you wanrt to interact with the d3 selection method
  - selection.style() - css styles
  - selection.attr()
  - selection.text() //.html for inner html
    selection.classed() takes a space seperates list and checks whether they should be added or removed

* Passing callback functions into d3 selection methods
  - can pass callbacks instead of primitive values
  - good for selection of multiple elements
  - d3 callbacks second argument is the index of the current element in selection

- set attributes, inner text and properties with

- get attributes and property values with

- Chain d3 methods together to make more complex changes to the dom

- Add Event listeners

  - On() method -- selection.on(eventType, callback)
  - cant add listens of the same type to the same element twice

  - d3.event is a property that contains all the event information when referenced inside an event handler

- Use d3.event to access the event object inside the event listener

- Add and remove Dom elements with D3

######## the guy teaching the video was sooooo boring to listen to so ima check out another tutorial
