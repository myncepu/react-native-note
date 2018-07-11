## Typecasting? Coercion.

- Explicit vs. Implicit coercion
  - const x = 42
  - const explicit = String(x)	  // explicit === '42'
  - const implicit = x + ''	  // implicit === '42'

- == vs. ===
  - == coerces the types
  - === requires equivalent types

## Platform Extensions

```
// FancyButton.android.js
// FancyButton.ios.js

import FancyButton from './FancyButton'
// if ios: use FancyButton.ios.js
// if android: use FancyButton.android.js
```

## Boilerplates

- [Snowflake](https://github.com/bartonhammond/snowflake) A React-Native Android iOS Starter App/ BoilerPlate / Example with Redux, RN Router, & Jest with the Snowflake Hapi Server running locally or on RedHat OpenShift for the backend, or a Parse Server running locally or remotely on Heroku
- [Pepperoni](http://getpepperoni.com) React Native App Starter Kit for Android and iOS
- [Ignite](https://infinite.red/ignite) The hottest CLI for React Native, boilerplates, plugins, generators, and more!

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
