# Railsthemes

This is a gem that helps you install a theme for your Rails app from RailsThemes.com. First, purchase a theme from the website. Then, install this gem and run it. You will get a download code, and you can pass this to the installer to install the theme (see below usage.) The themes at RailsThemes.com work for Rails 3.1+ (any that use the asset pipeline.)

## Installation

Add this line to your application's Gemfile:

    gem 'railsthemes'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install railsthemes

## Usage

Desired usage:

    $ railsthemes install download_code

## Other notes

This has been tested with Ruby 1.8.7, and should work with higher versions. 1.8.7 is the lowest version that Rails 3.1+ uses.

Not sure if this will work for Windows users due to invoking tar on the command-line instead of using native Ruby. This is something that we can change going forward, just a matter of time.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request