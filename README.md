# Cryptic Mushroom Website

Cryptic Mushroom Website built with Jekyll 4.0.0

## Getting Started

### Linux

#### 1A) On Linux Install Ruby

`sudo apt install ruby-full`

#### 1B) On Windows

You need to install [Ruby](https://rubyinstaller.org/). Make sure you get at least 2.6.X. Jekyll 4.0.0 is a little funny with 2.7+ and is getting a patch soon.

#### 2) Clone the repo

`git clone https://github.com/Cryptic-Mushroom/CM-Website.git`

#### 3) Install bundler

`gem install bundler`

#### 4) Navigate to the root of the directory and type:

`bundle install`
This should install all the package needed for development.

## Compiling

You can either build the website or serve it.

### Build

`bundle exec jekyll build`

This will build the website and generate everything in the `_site` directory.

### Serve

`bundle exec jekyll serve`

This will start a web server and serve the website on `http://127.0.0.1:4000`

## Contributing

Please make sure all your code is formatted properly and neatly and double check for any errors. Verify that your HTML elements work on multiple browsers. When you have verified everything, push your changes and the live website `crypticmushroom.com` will update from GitHub whenever possible.
