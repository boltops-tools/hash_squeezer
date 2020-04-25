# HashSqueezer

Squeeze hash and removes nil and empty arrays values, even if they are nested.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'hash_squeezer'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install hash_squeezer

## Usage

```ruby
data = {
  a: 1,
  b: nil,
  c: [],
  d: {e: nil},
}
HashSqueezer.squeeze(data) => {a: 1}
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/boltops-tools/hash_squeezer.
