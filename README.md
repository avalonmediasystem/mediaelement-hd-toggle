# Mediaelement::HDToggle

This gem is a mediaelement.js plugin that adds an HD toggle button to the control bar. It allows users to toggle between 2 specified qualities. 

## Installation

Add this line to your application's Gemfile:

    gem 'mediaelement-hd-toggle'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mediaelement-hd-toggle

## Usage

Load the gem assets after mediaelement_rails assets
Add "hd-toggle" to the features option in mediaelement player
By default the options are:
  hdToggleLabel: "HD",
  hdToggleOn: true,
  hdToggleBetween: ["high", "medium"]


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
