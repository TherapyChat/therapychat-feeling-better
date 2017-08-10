[![Build status](https://travis-ci.org/TherapyChat/therapychat-feeling-better.svg?branch=master)](https://travis-ci.org/TherapyChat/therapychat-feeling-better)

# &lt;therapychat-feeling-better&gt;

`<therapychat-feeling-better>` is a call to action component composed by title, subtitle and button.

![Sample](sample.png)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="therapychat-feeling-better.html">
    <therapychat-feeling-better></therapychat-feeling-better>
  </template>
</custom-element-demo>
```
-->
```html
<therapychat-feeling-better></therapychat-feeling-better>

<!-- default properties -->

<therapychat-feeling-better
  bottom-title="empieza a sentirte mejor"
  button-href="https://app.therapychat.com/signup"
  button-target=""
  button-text="Hablar ahora"
  button-title="Hablar ahora"
  subtitle="Pregunta a nuestro psicólogo sin compromiso"
  top-title="TherapyChat"
></therapychat-feeling-better>

<!-- open in new window -->

<therapychat-feeling-better
  button-target="_blank"
></therapychat-feeling-better>

<!-- show separator between title and subtitle -->

<therapychat-feeling-better
  separator
></therapychat-feeling-better>
```

## Installation

```bash
bower install -save therapychat-feeling-better
```

## License

therapychat-feeling-better is available under the `Apache License 2.0`. See the [LICENSE](./LICENSE) file for more info.

## Changelog

See [CHANGELOG](./CHANGELOG.md) file.
