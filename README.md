# &lt;instagram-card&gt;

> Web component to show a card of your profile in Instagram using [Polymer](http://polymer-project.org).

> Maintained by [Kessiler Rodrigues](https://github.com/kessiler).


## Demo

![Example](card-example.png)

> @NOTE : Data can not be displayed, because Instagram has a limit of 5000 requests per hour.

[Check it live!](http://kessiler.github.io/instagram-card)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install instagram-card --save
```

Or [download as ZIP](https://github.com/kessiler/instagram-card/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Instagram custom element:

    ```html
    <link rel="import" href="bower_components/instagram-card/dist/instagram-card.html">
    ```

3. Start using it!

    ```html
    <instagram-card></instagram-card>
    ```
    
    
## Options

Attribute     | Options     | Default             | Description
---           | ---         | ---                 | ---
`clientId`    | *string*    | `39040169`  		  | your id from instagram.
`accessToken` | *string*    | `39040169.f59def8.219f3923300a4b0aa8dcb88ec3964ea2` | key token of your user.

> @NOTE: If you do not know your clientId, you can search it [HERE!](http://jelled.com/instagram/lookup-user-id)


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT License](http://opensource.org/licenses/MIT)
