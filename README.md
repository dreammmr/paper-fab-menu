
##&lt;paper-fab-menu&gt;

Material design: [Floating Action Button](https://www.google.com/design/spec/components/buttons-floating-action-button.html)

`paper-fab-menu` is a floating action button with menu items. It contains an image placed in the center and
comes in two sizes: regular size and a smaller size by applying the attribute `mini`. When
the user touches the button, a ripple effect emanates from the center of the button and expends the menu items it contains.

You may import `iron-icons` to use with this element, or provide a URL to a custom icon.
See `iron-iconset` for more information about how to use a custom icon set.

There are two ways to show the paper-fab-button: `vertical` or `horizontal`.

[Live Example](http://spacee.xyz/paper-fab-menu/demo.html)

Example:

<paper-fab-menu icon="add" position="vertical">
	<paper-fab-menu-item label="Polymer" icon="polymer" ></paper-fab-menu-item>
	<paper-fab-menu-item label="Favorites" icon="star" ></paper-fab-menu-item>
	<paper-fab-menu-item label="Refresh" icon="refresh" ></paper-fab-menu-item>
</paper-fab-menu>
```

### <paper-fab-menu> - Properties

The following properties are available for styling:

| Property Name | Description | Default |
| --- | --- | --- |
| `icon` | The icon of the main paper-button | `''` |
| `color` | The background color of the main paper button | `--accent-color` |
| `position` | The position of the items: `vertical` or `horizontal` | `vertical` |

### <paper-fab-menu-item> - Properties

The following properties are available for styling:

| Property Name | Description | Default |
| --- | --- | --- |
| `icon` | The icon of the paper menu item | `''` |
| `color` | The background color of the paper menu item | `--accent-color` |
| `label` | The tooltip label of the paper menu item | `''` |
| `tooltip-position` | The position of the tooltip | `left` |


