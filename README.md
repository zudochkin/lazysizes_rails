# LazysizesRails

Simple wrapper for [lazysizes](https://github.com/aFarkas/lazysizes)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'lazysizes_rails'
```

And then execute:

    $ bundle

## Usage

* add to your **application.js** this line `//= require lazysizes_rails` or `//= require lazysizes_rails.min.js` if your want use minified version
* put necessary images into **app/assets/images** folder
* and show images with **image_tag** helper

```ruby
<%= image_tag 'low_quality_src.jpeg', data:
  { src: image_path('normal_quality_src.jpeg') }, class: 'lazyload' 
%>
```

## Contributing

1. Fork it ( https://github.com/vredniy/lazysizes_rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
