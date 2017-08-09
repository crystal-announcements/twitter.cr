# twitter.cr

## Installation

Add this to your application's shard.yml:
```yml
dependencies:
  twitter:
    github: crystal-announcements/twitter.cr
```

## Usage

```crystal
require "twitter"


c = Twitter::REST::Client.new consumer_key, consumer_secret, access_token, access_token_secret

c.home_timeline
```
