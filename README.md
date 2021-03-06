[![npm version](https://img.shields.io/npm/v/vuejs-carousel.svg)](https://www.npmjs.com/package/vuejs-carousel)
[![Downloads](https://img.shields.io/npm/dt/vuejs-carousel.svg)](https://www.npmjs.com/package/vuejs-carousel)
[![License](https://img.shields.io/npm/l/vuejs-carousel.svg)](https://www.npmjs.com/package/vuejs-carousel)

[![Code Climate](https://codeclimate.com/github/ludo237/vuejs-carousel/badges/gpa.svg)](https://codeclimate.com/github/ludo237/vuejs-carousel)
[![Test Coverage](https://codeclimate.com/github/ludo237/vuejs-carousel/badges/coverage.svg)](https://codeclimate.com/github/ludo237/vuejs-carousel/coverage)
[![Issue Count](https://codeclimate.com/github/ludo237/vuejs-carousel/badges/issue_count.svg)](https://codeclimate.com/github/ludo237/vuejs-carousel)

[![bitHound Overall Score](https://www.bithound.io/github/ludo237/vuejs-carousel/badges/score.svg)](https://www.bithound.io/github/ludo237/vuejs-carousel)
[![bitHound Dependencies](https://www.bithound.io/github/ludo237/vuejs-carousel/badges/dependencies.svg)](https://www.bithound.io/github/ludo237/vuejs-carousel/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/ludo237/vuejs-carousel/badges/devDependencies.svg)](https://www.bithound.io/github/ludo237/vuejs-carousel/master/dependencies/npm)
[![bitHound Code](https://www.bithound.io/github/ludo237/vuejs-carousel/badges/code.svg)](https://www.bithound.io/github/ludo237/vuejs-carousel)

# VueJs Carousel

    Easy to use VueJS component for Photo galleries, built with VueJS and web standards in mind

## How to install

- Either download or clone this repository
- Run `npm install` this will install all the necessary tools from NPM
- Run `npm run dev` this will create the dist folder
- Grab the file inside the dist folder and follow the [How to use section](#how-to-use)


## How to use
This carousel is pretty easy to use. Put the source code inside your page:

     <script src="dist/carousel.js"></script>

Add the component to your page:

    <div id="your-application-id">
      <carousel source="your-api-source"></carousel>
    </div>

Try it with a source, for example you can use [Json Placeholder](http://jsonplaceholder.typicode.com/photos?_limit=10)


## Configuration
The current state of the component uses an array of `photos` object and it expects this attributes:

- albumId
- id
- thumbnailUrl
- title
- url

**Be Aware**: If you have a different API structure you have to change the code a little bit in particular
you have to change the attributes of `selectedPhoto` and of `photos`. I will try to make this as dynamic as 
possibile but I'm still learning Javascript.


## License

See [License file](LICENSE) for further details.

## Changelog

See [Changelog File](CHANGELOG) for further details.
