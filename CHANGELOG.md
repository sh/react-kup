### changelog

#### 0.5

- `.component` method renamed to `.build`
- the `.text` method now uses `React.DOM.text` which gets wrapped in a `span` tag.
- added AMD support
- react-kup now comes with a version of react (0.13.3) because the configuration caused confusion
- supports both react-classes and react-elements as arguments to `.build`
- supports react-elements as argument to `k.{tag}`
