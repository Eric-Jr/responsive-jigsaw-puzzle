
# Responsive jQuery Jigsaw Puzzle

A responsive javascript jigsaw plugin utilizing jQuery UI.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
<!-- Polyfill JS -->
<script src="https://cdn.polyfill.io/v2/polyfill.min.js?features=default"></script>

<!-- jQuery/jQuery UI -->
<link href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.10.4/themes/smoothness/jquery-ui.css" />
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js" type="text/javascript"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.10.4/jquery-ui.min.js" type="text/javascript"></script>

<!-- TouchPunch JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui-touch-punch/0.2.3/jquery.ui.touch-punch.min.js" type="text/javascript"></script>
```

### Installing

A step by step series of examples that tell you how to get a development env running

1. Include the main plugin files:

```
<!-- CSS -->
<link rel="stylesheet" href="../path/to/file/puzzle.css">

<!-- Javascript -->
<script src="../path/to/file/puzzle.js"></script>
```

2. Create a variable and initialize the plugin.

```
var puzzle = new Puzzle({options});
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

You can include the `debug` option to output useful information to the console.

## Built With

* [jQuery](http://jquery.com/) - jQuery UI dependency
* [jQuery UI](http://jqueryui.com/) - Used for drag and drop functionality
* [jQuery UI Touch Punch](http://touchpunch.furf.com/) - Adds touch events to jQuery UI drag/drop
* [Polyfill IO](https://polyfill.io/v2/docs/) - Extends vanilla JS support in IE


## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Eric Harris** - *Initial work* - [Eric-Jr](https://github.com/Eric-Jr)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments