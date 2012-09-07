# pagedown-rails

[PageDown](https://code.google.com/p/pagedown/) for the Rails asset pipeline.

## Installation

Add this line to the assets group in your Gemfile:

```ruby
gem 'pagedown-rails'
```

Add the necessary libraries to `app/assets/javascripts/application.js`:

```js
//= require markdown.converter
//= require markdown.sanitizer
```

## What's included?

* markdown.converter
* markdown.sanitizer
* markdown.editor

Copyright Richard Hubers, released under the MIT License.
