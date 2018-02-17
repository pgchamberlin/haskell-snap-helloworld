# Haskell Snap HelloWorld
Trying out making a web service using Haskell and the Snap framework

## Installation

With Haskell installed you should be able to install things using `cabal`. There's a slimmed down Snap, `snap-core`, but for some reason I chose to install the motherlode `snap` as well as `snap-templates`, which gives you the cli.

I followed the (quick start guide)[http://snapframework.com/docs/quickstart] which approximates to the following to install:

```
cabal install snap snap-templates
snap init barebones
```

And once that's done you can build and run the ready-rolled "Hello, World!" that distributes with Snap:

```
cabal install
<project name> -p 8080
```

If you're playing with this repo then the project name is probably `haskell-snap-helloworld`.

## Modification

The `Main` module is in `scr/Main.hs` so go play there :)
