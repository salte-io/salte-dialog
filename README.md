[![Gitter](https://badges.gitter.im/salte-io/salte-dialog.svg)](https://gitter.im/salte-io/salte-dialog?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/salte-io/salte-dialog)
[![Build status](https://travis-ci.org/salte-io/salte-dialog.svg?branch=master)](https://travis-ci.org/salte-io/salte-dialog)

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
