# wc-bind-var

## Installation

Bower dependency:
```
    "wc-bind-var": "https://github.com/seabourne/wc-bind-var.git"
```


## Usage

```
<link rel="import" href="../../../bower_components/wc-bind-var/bind-var.html">
```

A helper component for `dom-bind` that takes a literal (template) value and binds it to a variable for use in subsequent components within the `dom-bind`

```
  <template is="dom-bind">
    <bind-var in="<%= var %>" out="{{value}}" />
    <my-component property-named="{{value}}" />
  </template

```
