# pagedown-rails

[PageDown](https://code.google.com/p/pagedown/) for the Rails asset pipeline.

## Installation

Add this line to the assets group in your Gemfile:

```ruby
gem 'pagedown-rails', '~> 1.1.2'
```

Add the necessary libraries to `app/assets/javascripts/application.js`:

```js
//= require markdown.converter
//= require markdown.sanitizer
//= require markdown.editor
```

Add the necessary libraries to `app/assets/stylesheets/application.css`:

```css
/*
 *= require markdown
 */
```

### To create markdown editor:

```js
var converter = Markdown.getSanitizingConverter();
var editor = new Markdown.Editor(converter);
editor.run();
```

```html
<div class='wmd-panel'>
  <div id='wmd-button-bar'></div>
  <textarea class='wmd-input'></textarea>
</div>
```

## What's included?

* markdown.converter
* markdown.sanitizer
* markdown.editor
* css styles

Copyright Richard Hubers, released under the MIT License.
