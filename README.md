# haskell-snap-helloworld
Trying out making a web service using Haskell and the Snap framework

## Installation

With Haskell installed you should be able to install things using `cabal`. There's a slimmed down Snap, `snap-core`, but for some reason I chose to install the motherlode `snap` as well as `snap-templates` (which gives you the `snap` CLI).

```
cabal install snap snap-templates
snap init barebones
```

Once this is done you can build and run the ready-rolled "Hello, World!" that distributes with Snap:

```
cabal install
<project name> -p 8080
```

If you're playing with this repo then the project name is probably `haskell-snap-helloworld`.
