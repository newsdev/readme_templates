# Javascript Library

## Description

*Brief description.  Links to additional documentation.*

*Current example: [Blutack](https://github.com/newsdev/blutack)*

* [Features](#features)
* [Requirements](#requirements)
* [Support](#support)
* [Installation](#installation)
* [Usage](#usage)
* [Tests](#tests)
* [Upcoming Features](#upcoming-features)
* [Other Relevant Documentation](#other-relevant-documentation)
* [License](#license)

## Features

* List
* noteworthy
* features

## Requirements

* Other JS libraries?
* Additional services?

## Support

*Instructions on how to get help with this project or report problems.  Are Github issues a good mechanism?*

*Also outline who will be maintaining this project in the future..*

## Installation

*Source file(s) to download. Build instructions, if any.  Can it be installed via NPM or Bower?  For example:*

Add Interactive News' Bower registry to your `.bowerrc` file:

    {
      "registry": {
        "search": [
          ...
          "http://bower.newsdev.net"
        ]
      }
      ...
    }

Add my-js-lib to your bower.json:

    {
      "name": "your_app",
      "dependencies": {
        "my-js-lib": "1.2.0"
        ...
      }
    }

And:

    bower install

For more information, see the [Bower docs](http://bower.io/).

## Usage

*API documentation and examples* 

Get started with MyLib by instantiating a Foo:

    var myFoo = new Foo(options)

### Options

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>type</th>
      <th>default</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>bar</td>
      <td>string</td>
      <td>'Hello, world.'</td>
      <td>Customize your `bar`.</td>
    </tr>
    <tr>
      <td>baz</td>
      <td>integer</td>
      <td>99</td>
      <td>Maximum number of `baz` to try before giving up.</td>
    </tr>
    <tr>
      <td>qux</td>
      <td>function</td>
      <td></td>
      <td>Callback to execute if 'baz' is successful.</td>
    </tr>
  </tbody>
</table>


### Instance Methods

#### .show(element, [css])

Shows an **element** (expressed as a reference to a DOM node, a jQuery selector, or a jQuery-wrapped node).  Additionally, set the CSS properties from the key-value pairs listed in **css**.  Returns reference to the shown DOM node (equivalent to `$(element).get(0)`).

    myFoo.show('.some-element', { backgroundColor: 'green' });

#### .on(eventName, callback)

Listen by **eventName** for one of the [Foo-specific events](#events) listed below, and execute **callback**.  Callback context (`this`) is the instance of Foo to which the listener was attached.

    myFoo.on('baz', function() {
      this.show('.another-element');
    });

### Events

The following events can be triggered by an instance of Foo.

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>bar</td>
      <td>Triggered each time `bar` happens.</td>
    </tr>
    <tr>
      <td>baz</td>
      <td>Fires when `baz` is ready.</td>
    </tr>
  </tbody>
</table>

## Tests

*Are there tests?  How do I run them?*

## Upcoming Features

*What are you working on next?  Are there milestones in the Github issues worth referencing?*

## Other Relevant Documentation

*Links here to external documentation that might help someone using or developing in this project.  For example:*

* [Bower](http://bower.io) - A package manager for the web
* [jQuery](https://jQuery.com) - You'd better know by now

## License

*Include and licence information here.*