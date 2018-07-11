## Typecasting? Coercion.

- Explicit vs. Implicit coercion
  - const x = 42
  - const explicit = String(x)	  // explicit === '42'
  - const implicit = x + ''	  // implicit === '42'

- == vs. ===
  - == coerces the types
  - === requires equivalent types

## Platform Extensions

// FancyButton.android.js
// FancyButton.ios.js

import FancyButton from './FancyButton'
// if ios: use FancyButton.ios.js
// if android: use FancyButton.android.js

## Boilerplates

[Snowflake](https://github.com/bartonhammond/snowflake)
[Pepperoni](http://getpepperoni.com)
[Ignite](https://infinite.red/ignite)

## Resources

[Awesome React Native components, news, tools, and learning material!](http://www.awesome-react-native.com)

## GraphQL

### GraphQL file structure

src
├── Components
└── Graphql
    ├── MutationCreateEvent.js
    ├── MutationDeleteEvent.js
    ├── QueryAllEvent.js
    ├── QueryGetEvent.js
    └── SubscriptionEventComment.js
