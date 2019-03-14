# datedash.doc

The datedash documentation website

## Running Locally

1. Clone the `datedash.doc` `git` repository
    ```bash {.copy-clip}
    git clone https://github.com/flavioespinoza/datedash.doc.git
    ```

2. Install required `gems` with `bundle`
    ```bash {.copy-clip}
    sudo bundle
    ```

3. Install `node modules` with `npm`
    ```bash {.copy-clip}
    npm install
    ```

4. Build & run server.
    ```bash {.copy-clip}
    bundle exec jekyll serve
    ```

5. Navigate to local server in Chrome or Firefox browser
    http://localhost:4000

## Incrementing the datedash `version`

1. Clone the `datedash` `git` repository
    ```bash {.copy-clip}
    git clone https://github.com/flavioespinoza/datedash.git
    ```

2. In your local `datedash` directory generate new documentation `HTML` file by running
    ```bash {.copy-clip}
    npm run site
    ```

3. Copy the generated `HTML` file from `datedash/doc` directory.
    ```bash {.copy-clip}
    # copy
    datedash/doc/<version>.html 
    ```

4. Paste the generated `HTML` file to `datedash.doc/docs` directory.
    ```bash {.copy-clip}
    # paste
    datedash.doc/docs/<version>.html 
    ```

5. Update `_config.yml` for the release.
    ```bash {.copy-clip}
    npm run build:config <version>
    ```
