[![Gitter](https://badges.gitter.im/salte-io/salte-dialog.svg)](https://gitter.im/salte-io/salte-dialog?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/salte-io/salte-dialog)
[![Build status](https://travis-ci.org/salte-io/salte-dialog.svg?branch=master)](https://travis-ci.org/salte-io/salte-dialog)
  
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/salte-iosalte-dialog)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/salte-iosalte-dialog.svg)](https://vaadin.com/directory/component/salte-iosalte-dialog)

# \<salte-dialog\>

`salte-dialog` is an material dialog with a few extra conveniences.

<!---
```
<custom-element-demo height="600">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="salte-dialog.html">
    <style>
      body {
        font-family: 'Roboto', 'Noto', sans-serif;
      }

      salte-dialog {
        --salte-dialog-header-background: #673ab7;
        --paper-button: {
          color: #673ab7;
        };
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<salte-dialog opened modal>
  <h2>My Header</h2>
  <span>Content</span>
  <div class="buttons">
    <paper-button dialog-dismiss>Cancel</paper-button>
    <paper-button dialog-confirm>Accept</paper-button>
  </div>
</salte-dialog>
```
