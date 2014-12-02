# Rails Project

## Description

*Brief description.  Link to deployed app.  Links to additional documentation.*

*Current example: [Deck](https://github.com/newsdev/deck)*

* [Features](#features)
* [Requirements](#requirements)
* [Support](#support)
* [Development Instructions](#development-instructions)
    * [Setup](#setup)
    * [Project-specific development information](#project-specific-development-information)
* [Tests](#tests)
* [Deployment](#deployment)
* [Upcoming Features](#upcoming-features)
* [Other Relevant Documentation](#other-relevant-documentation)
* [Sunset Plans](#sunset-plans)
* [License](#license)

## Features

* List
* noteworthy
* features

## Requirements

* ruby version
* additional requirements

## Support

*Instructions on how to get help with this project or report problems.  Are Github issues a good mechanism?*

*Also outline who will be maintaining this project in the future.  Are there plans to freeze or sunset it?  Link to [Sunset Plans](#sunset-plans) if so.*

## Development Instructions

### Setup

*How to download and run the app.  For example:* 

Check out the repo and cd into the local directory.

    git clone git@github.com:newsdev/rails_project.git
    cd rails_project

Install the gems:

    bundle install

Run the Rails server:

    rails s

Project will be available at http://localhost.nytimes.com:3000/.

(For information on setting up your localhost to use the nytimes.com domain, click [here](snippets/hosts.md).)

### Project-specific development information

*Are there rake tasks to run in the development workflow?  Guard?  Want to talk about how the project is organized?  What else foes the developer need to know?*

    And include some code.

## Tests

*Are there tests?  Rails?  JS?  How do I run them?*

## Deployment

*Any relevant informtion about how and where the app is deployed.  For example:*

This project is deployed using [Blade](https://github.com/newsdev/blade-chef/).  The production environment, at http://my_project.adm.int.newsdev.net, is **admin**:

    bl deploy my-project -e admin -b master

The development branch can be deployed to the staging environment, at http://my_project.stg.int.newsdev.net.

## Upcoming Features

*What are you working on next?  Are there milestones in the Github issues worth referencing?*

## Other Relevant Documentation

*Links here to external documentation that might help someone using or developing in this project.  For example:*

* [Badcom](https://www.github.com/newsdev/badcom) - Gem for streamlining INT admin development
* [Adcom](https://www.github.com/newsdev/adcom) - JS/CSS framework for building admins

## Sunset plans

*Include any information about plans to sunset the app here.*

## License

*Include and licence information here.*