# Infocoin

> _On hold for now_
>
> This project is being ported to the elixir library [Aurum](https://github.com/alex0112/aurum)

An easy way to view your ROI in Coinbase

## Usage

```ruby
#!/usr/bin/env ruby
require 'infocoin'

btc = Currency.new(symbol: :BTC)

p "Bitcoin losses: $#{btc.usd_lost}"
p "Bitcoin gains: $#{btc.usd_gained}"
```

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'infocoin'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install infocoin

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/alex0112/infocoin.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
