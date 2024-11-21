# bestblueyparty

A human-readable random string generator.

Example output:

```
dubious-jellybean-jungle
scary-crush
mr-buzzing-dream
silky-slipper-with-style
a-good-8-bit-crown
beautiful-jokes
dancing-money
alert-food
miraculous-gentlemen
starry-button-if-you-will
true-shoe
cleanest-sandwiches
sorry-friend
woolly-danger-of-wonder
best-hugs-at-your-service
eternal-daughters-with-style
pet-sleeves
beastly-shape
shy-answer-in-a-sec
big-ol-boy-of-wonder
```

Use it as a library:

```go
import "github.com/rahji/bestblueyparty"

fmt.Println(bestblueyparty.Generate()) // best-hugs-at-your-service
```

Use it on the CLI:

```bash
# Generate a random string
bestblueyparty

# Generate 25 random strings
bestblueyparty -r 25

# See also
bestblueyparty -h
```

## Help Out

This is a fork of the [Charm](https://charm.sh) library [hotdiva2000](https://github.com/charmbracelet/hotdiva2000).
The idea is to replace the words with more kid-friendly ones. I'm going to experiment with a process that will allow
people to add new words via GitHub and when they're approved, to re-build the package automatically. In the meantime,
make a pull-request - it needs more words.

## License

[MIT](https://github.com/rahji/bestblueyparty/raw/main/LICENSE)
