# PayRex Ruby

PayRex Ruby library provides Ruby applications an easy access to the PayRex API. Explore various Ruby classes that represents PayRex API resources on object instantiation.

## Requirements

Ruby 2.3+.

## Gems

If you want to use the package, run the following command:

```sh
gem install payrex-ruby
```

If you want to build the gem from source:

```sh
gem build payrex-ruby.gemspec
```

## Getting Started

Simple usage looks like:

```ruby
require "payrex-ruby"

payrex_client = Payrex::Client.new("sk_test_...")
payrex_client.payment_intent.retrieve("pi_...")
```
