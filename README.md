# &lt;x-heart&gt;

Web Component build with [Polymer](http://polymer-project.org) to display Heart

> Maintained by [Mateus Ortiz](https://github.com/mateusortiz).

## Demo

> [Check it live](http://mateusortiz.github.io/x-heart).

## Install

Install with [Bower](http://bower.io/):

```sh
$ bower install --save x-heart
``` 

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/x-heart.html">
    ```

3. Start using it!

    ```html
    <x-heart></x-heart>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)