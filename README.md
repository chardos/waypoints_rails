# waypoints_rails

Simple asset pipeline management for [Waypoints.js](http://imakewebthings.com/waypoints/)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'waypoints_rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install waypoints_rails

## Usage

In your application.js, include one of the following:
``` ruby
//= require waypoints/jquery.waypoints.js
//= require waypoints/jquery.waypoints.min.js
//= require waypoints/noframework.waypoints.js
//= require waypoints/noframework.waypoints.min.js
//= require waypoints/waypoints.debug.js
//= require waypoints/zepto.waypoints.js
//= require waypoints/zepto.waypoints.min.js
```

And then, for optional waypoints shortcuts, require any of the following:
``` ruby
//= require waypoints/shortcuts/infinite.js
//= require waypoints/shortcuts/infinite.min.js
//= require waypoints/shortcuts/inview.js
//= require waypoints/shortcuts/inview.min.js
//= require waypoints/shortcuts/sticky.js
//= require waypoints/shortcuts/sticky.min.js
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/waypoints_rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request


Built by the team at [Nifty](https://www.niftyforms.com/).
