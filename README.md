## Tether

[![GitHub
version](https://badge.fury.io/gh/HubSpot%2Ftether.svg)](http://badge.fury.io/gh/HubSpot%2Ftether)

Tether is a JavaScript library specifically designed to efficiently hold an element that has been absolutely positioned next to another element on your webpage in place.

Although elements can be positioned manually, if you wanted them to change positions when resizing the screen later on, you would have had to craft each of those elements with that potential purpose in mind. Because when you do have multiple positioned elements all suddenly reacting differently, your work load will exponentially increase.

Tether's goal is to ease this kind of work by providing optimal functionality when placing any type of unique element (like tooltips or banners) on to the screen, so that you don't have to worry about document flow. These elements can be attached with a simple constructor and has various options available, additionally providing you with several options like the ability to reposition elements even after a certain scroll threshold has been reached, or to keep an element confined to one specific area.

It thus aims for a canonical implementation of this type of positioning, so that you can ultimately build products, not positioning libraries. Please take a look at the attached documentation for a more detailed explanation of why you should think of Tether when starting your next project.

## Install

__npm__
```sh
$ npm install tether
```

__bower__
```sh
$ bower install tether
```

## Usage

[![Tether Docs](http://i.imgur.com/YCx8cLr.png)](http://github.hubspot.com/tether/#usage)

[Demo & API Documentation](http://github.hubspot.com/tether/)


## Contributing

We encourage contributions of all kinds. If you would like to contribute in some way, please review our [guidelines for contributing](CONTRIBUTING.md).


## License
Copyright &copy; 2014-2016 HubSpot - [MIT License](LICENSE)
