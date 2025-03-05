# TeamsPlayers
# Teams and Players SwiftUI App

This SwiftUI app displays a list of teams and their players. The data is organized using an object-oriented programming (OOP) model with a `Player` struct, a `Team` class, and an `enum` to categorize team types (e.g., National, Club, Academy). The app also uses `ObservableObject` to manage the state and update the UI dynamically when the data changes.

## Features

- **Team Types**: Teams are categorized as National, Club, or Academy using an enum.
- **Player Data**: Each team has a list of players, where each player has a name and position.
- **Dynamic UI**: The list updates dynamically using `@Published` properties and `ObservableObject`.
- **State Management**: State management is done using the `@StateObject` and `@Published` property wrappers to reflect changes in the UI as the data updates.
