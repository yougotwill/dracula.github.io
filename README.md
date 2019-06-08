# draculatheme.com

> This branch contains the source code for [draculatheme.com](https://draculatheme.com).

![Screenshot](src/assets/img/readme.png)

## How it works?

We use [Metalsmith](http://www.metalsmith.io/), a static generator in NodeJS.

## Getting Started

1. Install [NodeJS](http://nodejs.org/download/) (>= 4.3.0), if you don't have it yet.

2. Now clone this repository:

    ```sh
    $ git clone https://github.com/dracula/dracula-theme.git
    ```

3. Then go to the project's folder:

    ```sh
    $ cd dracula-theme
    ```

4. Move to the `site` branch:

    ```sh
    $ git checkout site
    ```

5. Install all dependencies:

    ```sh
    $ npm install
    ```

5. And finally run:

    ```sh
    $ npm run watch
    ```
   Now you can see the website running in `localhost:8000` :D

6. If you're a collaborator, you can publish the site to GitHub Pages by running:

    ```sh
    $ npm run deploy
    ```

## License

[MIT License](./LICENSE) © Dracula Theme
