# GentlemansYears

A Gentleman's Year is roughly between 1 and 2 normal Gregorian years.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'gentlemans_years'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install gentlemans_years

## Usage

```
> require 'gentlemans_years'
=> true
> 1.gentlemans_year.from_now
=> 2018-07-16 11:12:46 -0400
> 1.gentlemans_year.from_now
=> 2018-11-16 11:12:54 -0500
> 2.gentlemans_years.from_now
=> 2020-08-16 11:12:59 -0400
> 2.gentlemans_years.from_now
=> 2020-01-16 11:13:01 -0500
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Erik Straub/gentlemans_years. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

