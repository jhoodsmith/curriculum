# Vote

Create a `vote` object.

It should have a  `question` attribute should be a string.

The `result` attribute should be a hash with keys of the given answers and value of the number of votes that key has receieved

```ruby
vote = Vote.new("Who should run for president in 2016?")
vote.cast("Hillary")
vote.cast("Ada")
vote.cast("Ada")
vote.results # => {"Hillary" => 1, "Ada" => 2}
```

Silver
------

Create the following methods:

- `winner` Returns a string of the top entry
- `vote_count` Returns the number of total votes

Gold
-----

Create a `stats` method that prints the current status

```ruby
vote.stats

# 3 Votes total
# Ada (1 vote)
# Hillary (2 votes)
#
# Ada is currently in the lead
```
