# Get Fruit [ Game ]

## Layers

1. Presentation

   > Render canvas, print game, appearance game...

2. Game

   > Archive data state and logic of game(define rules)

3. Inputs

   > Get input events

4. Networking

   > Share information of server-side for all clients. Sync information's

## Entities

### Create Game

- addPlayer

```
type command = {
    playerId: String
    positionX: Number
    positionY: Number
}

addPlayer(command) { }
```

- addFruit

```
type command = {
    fruitId: String
    positionX: Number
    positionY: Number
}

addFruit (command) { }
```

- removePlayer

```
type command = {
    playerId: String
}

removePlayer (command) { }
```

- removeFruit

```
type command = {
    fruitId: String
}

removeFruit (command) { }
```

- detectCollision

```
type command = {
    playerId: String
}

detectCollision (command) { }
```

### Create Keyboard Listener

- handleKeyDown
>