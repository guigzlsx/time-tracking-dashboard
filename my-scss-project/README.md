# My SCSS Project

This project uses the 7-1 architecture pattern for organizing SCSS files. The structure is modular and scalable, making it easy to maintain and update.

## Project Structure

The project is structured as follows:

- `abstracts`: This folder contains the `_variables.scss` and `_functions.scss` files. These files contain SCSS variables and functions that are used throughout the project.

- `base`: This folder contains the `_reset.scss` and `_typography.scss` files. These files reset the default styles and set the base styles for typography.

- `components`: This folder contains component-specific styles, such as `_buttons.scss`.

- `layout`: This folder contains layout-specific styles, such as `_header.scss` and `_footer.scss`.

- `pages`: This folder contains page-specific styles, such as `_home.scss`.

- `themes`: This folder contains theme-specific styles, such as `_theme.scss`.

- `vendors`: This folder contains styles from third-party libraries and frameworks, such as `_bootstrap.scss`.

- `main.scss`: This is the main SCSS file that imports all other SCSS files. The compiled CSS of this file is used in the HTML.

## Usage

To use this project, import the `main.scss` file into your HTML. This file imports all other SCSS files, so you don't need to import them individually.

## Contributing

Contributions are welcome. Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)