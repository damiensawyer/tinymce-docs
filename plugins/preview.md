---
layout: default
title: Preview Plugin
title_nav: Preview
description: Shows a popup of the current content in read-only format.
keywords: view preview plugin_preview_height plugin_preview_width
controls: toolbar button, menu item
---

This plugin adds a preview button to the toolbar. Pressing the button opens a dialog box showing the current content in a preview mode. It also adds a menu item `Preview` under the `View` menu dropdown.

**Type:** `String`

##### Example

```js
tinymce.init({
  selector: "textarea",  // change this value according to your HTML
  plugins: "preview",
  menubar: "view",
  toolbar: "preview"
});
```

### Options

These settings affect the execution of the `preview` plugin. The height and width of the preview dialog box may be set here.

### `plugin_preview_height`

This option allows you to set the height of the preview window that appears when using the `preview` plugin.

**Type:** `Number`

**Default Value:** `500`

##### Example

```js
tinymce.init({
  selector: "textarea",  // change this value according to your HTML
  plugins: "preview",
  menubar: "view",
  toolbar: "preview",
  plugin_preview_height: 500
});
```

### `plugin_preview_width`

This option allows you to set the width of the preview window that appears when using the `preview` plugin.

**Type:** `Number`

**Default Value:** `650`

##### Example

```js
tinymce.init({
    selector: "textarea",  // change this value according to your HTML
    plugins: "preview",
    menubar: "view",
    toolbar: "preview",
    plugin_preview_width: 650
});
```
