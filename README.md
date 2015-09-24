### tweet-search.rb

Search tweets for a given user for a string and return matching tweets.
Go to [https://apps.twitter.com](https://apps.twitter.com) to generate an app token, then store it in a local yml file - 'twitter-account.yml' is the default file name.

Usage:
```bash
ruby tweet-search.rb @user text_string
```

Example run:
```
ruby tweet-search.rb @adampats "#mesos"
Found @adampats!

=== Tweet matches ===

- Thu Aug 20 19:15:29 +0000 2015 -
Dominant Resource Fairness: how #mesos manages resources - https://t.co/M76Y5sd5Yg  #mesoscon #metal

- Thu Aug 20 16:37:02 +0000 2015 -
Deploy a #mesos cluster in 7 commands with docker - https://t.co/jQIr685wgI #mesoscon

- Thu Aug 20 13:53:13 +0000 2015 -
This tweet brought to you by, #Mesos.

#mesoscon @linuxfoundation

Done.
```

* TODO: Add tweet.url to the response JSON
* TODO: Get more tweets than the user_timeline limit of 200
* TODO: Fix tweet text truncation
