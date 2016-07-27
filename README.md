# Persistent::Cache

Persistent cache behaves like a hash, with a pluggable back-end. This gem only implements STORAGE_RAM, and in doing so has no dependencies such as sqlite, etc. Please see the persistent-cache gem for support for more back-ends and a comprehensive README.

## Installation

Add this line to your application's Gemfile:

    gem 'persistent-cache-ram'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install persistent-cache

## Usage

    require 'persistent-cache'

    Please see the persistent-cache gem for usage instructions. This is a STORAGE_RAM only implementation.

## Contributing

Please send feedback and comments to the authors at:

Ernst van Graan <ernst.van.graan@hetzner.co.za>

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
