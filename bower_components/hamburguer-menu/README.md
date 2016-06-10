# &lt;hamburguer-menu&gt;

> <🍔/> A Polymer element for Off-canvas Menu.


## Demo

[Check it live!](http://afonsopacifer.github.io/hamburguer-menu/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install hamburguer-menu/hamburguer-menu --save
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/hamburguer-menu/hamburguer-menu.html">
```

3. Start using it!

```html
<hamburguer-menu>
  <menu-item text="link 1"></menu-item>
  <menu-item text="link 2"></menu-item>
  <menu-item text="link 3"></menu-item>
</hamburguer-menu>
```

## Attributes

Attribute  | Type        | Default             | Description
---        | ---         | ---                 | ---
`text`   | *String*    | `link`    | Sets the corner text content.
`href` | *String*   | `#`             | Defines the destination url.
`target`     | *String*    | `_self`   | Defines the hyperlink target.

**Example:**

```html
<hamburguer-menu>
  <menu-item text="link 1" href="#" target="_blank"></menu-item>
  <menu-item text="link 2" href="#" target="_self"></menu-item>
</hamburguer-menu>
```

## Development

1. Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
$ [sudo] npm install -g bower polymer-cli
```

2. Install local dependencies:

```sh
$ bower install
```

3. Start the development server on http://localhost:8080/:

```sh
$ polyserve
```

**View docs:**<br>
http://localhost:8080/components/hamburguer-menu/

**View demo:**<br>
http://localhost:8080/components/hamburguer-menu/demo/

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Find on our [issues](https://github.com/afonsopacifer/hamburguer-menu/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/hamburguer-menu/blob/master/CONTRIBUTING.md).

## History
See [Releases](https://github.com/afonsopacifer/hamburguer-menu/releases) for detailed changelog.

## License
[MIT License](https://github.com/afonsopacifer/hamburguer-menu/blob/master/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.com/)
