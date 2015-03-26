# autocomplete-iframe
the iframe that we put inside the autocomplete dropdown

## how to use with your custom gecko

1. configure your computer's web server to serve this file from someplace on localhost
2. grab the `hack-and-slash` branch of gecko-dev and replace [this line](https://github.com/the-super-friends/gecko-dev/blob/hack-and-slash/toolkit/content/widgets/autocomplete.xml#L1474) with the path to your copy of the file
3. build gecko-dev and bask in our collective glory

## documenting the postmessage API with the autocomplete code

https://gist.github.com/6a68/48bf56e5b66e8631b522
