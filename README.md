# Changes

This theme was adapted to be able to use it locally in a browser or an Electron app.

In order to use it locally some changes need to be made as seen in this example `config.toml` file:

```toml
baseURL = '/'
languageCode = 'en-us'
title = 'My New Hugo Site'
relativeURLs = true
uglyURLs = true

# Change the default theme to be use when building the site with Hugo
theme = "relearn" # or theme = "hugo-theme-relearn-local"

# For search functionality
[outputs]
  home = ["HTML", "RSS", "JSON"]
  section = ["HTML", "RSS", "PRINT"]
  page = ["HTML", "RSS", "PRINT"]

[params]
  # Change default color scheme with a variant one. Eg. can be "red", "blue", "green" or an array like [ "blue", "green" ].
  themeVariant = [ "relearn-dark", "relearn-light" ]

  # Hide breadcrumbs in the header and only show the current page title
  disableBreadcrumb = false

  # Hide Next and Previous page buttons normally displayed full height beside content
  disableNextPrev = false
```

# Hugo Relearn Theme

A theme for [Hugo](https://gohugo.io/) designed for documentation.

![Overview](https://github.com/McShelby/hugo-theme-relearn/raw/main/images/screenshot.png)

## Motivation

The theme is a fork of the great [Learn theme](https://github.com/matcornic/hugo-theme-learn) with the aim of fixing long outstanding bugs and adepting to latest Hugo features. As far as possible this theme tries to be a drop-in replacement for the Learn theme.

## Main features

- Usable offline, no external dependencies
- Support for Internet Explorer 11
- Responsive design
- Configurable hidden pages
- Automatic next/prev buttons to navigate through menu entries
- Automatic Search
- Print whole chapters or even the complete site
- Multilingual mode for English, Arabic, Simplified Chinese, Traditional Chinesse, Dutch, French, German, Hindi, Indonesian, Italian, Japanese, Korean, Polish, Portuguese, Russian, Spanish, Turkish, Vietnamese
- Unrestricted menu configuration relating to amount of items and level of nesting
- Font Awesome icons
- Tagging support
- Image resizing, shadow…
- Syntax highlighting
- Attachments files
- List child pages
- Math and chemical formulae using the MathJax library
- Mermaid diagrams for flowcharts, sequences, gantts, pie, etc.
- Swagger UI for OpenAPI Specifications
- Customizable look and feel
- Predefined (light, dark) and customizable color variants
- Buttons
- Tip/Note/Info/Warning boxes
- Expand
- Tabs
- File inclusion
## Installation

Visit the [installation instructions](https://mcshelby.github.io/hugo-theme-relearn/basics/installation) to learn how to setup the theme in your Hugo installation.

## Usage

Visit the [documentation](https://mcshelby.github.io/hugo-theme-relearn/) to learn about all available features and how to use them.

## Changelog

See the [changelog](https://mcshelby.github.io/hugo-theme-relearn/basics/history) for a complete list of releases.

## Contribution

You are most welcome to contribute to the source code but please visit the [contribution guidelines](https://github.com/McShelby/hugo-theme-relearn/blob/main/.github/contributing.md) first.

## License

This theme is licensed under the [MIT License](https://github.com/McShelby/hugo-theme-relearn/blob/main/LICENSE).

## Credits

Special thanks to [everyone who has contributed](https://github.com/McShelby/hugo-theme-relearn/graphs/contributors) to this project.

Many thanks to [Mathieu Cornic](https://github.com/matcornic) for his work on porting the [Learn theme](https://github.com/matcornic/hugo-theme-learn) to Hugo.

Many thanks to [Andy Miller](https://github.com/rhukster) for initially creating the [Learn theme](https://github.com/getgrav/grav-theme-learn2) for Grav.
