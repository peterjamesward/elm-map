# elm-map

Spare yourself from dropping in a large blob of JS whenever you want to add a map viewer to your site!

This package has no JS dependencies meaning you don't need to mess with ports or web components to make it work.[^1]

[Here's an example of it in action.](https://realia.se/map?a=AQADAAAAAAAAAAAAAAAAAAAAAEAIAAAAAAAAAAEAAAAXS3VuZ3NnYXRhbiAxLCBTdG9ja2hvbG0AAAAXS3VuZ3NnYXRhbiAxLCBTdG9ja2hvbG0AAAAAAHBFaUJMZFc1bmMyZGhkR0Z1SURFc0lGTjBiMk5yYUc5c2JTd2dVM1psY21sblpTSXdFaTRLRkFvU0NlVzBzNVZjblY5R0VXT0tkNVpnVUtZbEVBRXFGQW9TQ1gwTXhVcG5uVjlHRWNxTVpVVUNVZF9PAAAAAABwRWlCTGRXNW5jMmRoZEdGdUlERXNJRk4wYjJOcmFHOXNiU3dnVTNabGNtbG5aU0l3RWk0S0ZBb1NDZVcwczVWY25WOUdFV09LZDVaZ1VLWWxFQUVxRkFvU0NYME14VXBublY5R0VjcU1aVVVDVWRfTwADAAAAAw)

## Caveats

This map viewer doesn't have many of the features and styling options other map viewers like Mapbox offer. While some features don't exist simply because I haven't had time to add them, I suspect everyone will have their own specific use cases that will be difficult for this package to completely satisfy without making it difficult to use and a lot slower.

For that reason, I recommend cloning this package and changing it to suit your needs[^2]! If you add cool features consider making a PR. Some of it might still be general purpose enough to for other people to use.

Also, people I've shown the map viewer to (around half) report that it's laggy on their device. No one has said it's unusably laggy but it's still not ideal. Performance improvements are ongoing but I recommend trying out the example viewer and deciding for yourself if the performance is good enough for your use case.

## Special thanks

Thanks to [realia.se](https://realia.se/) for letting me implement this during work hours!

Also thanks to

[^1]: This package does depend on Mapbox servers to provide vector tiles. You'll need to create an account with them and generate an API key.

[^2]: Contact me on Elm slack (martin.stewart) or email me at martinsstewart@gmail.com if you like to hire me to implement a specific feature.