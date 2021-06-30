# inputs.js

A small utility class designed to help you hook up HTML input elements 
to any given script via callback functions. Basically a little convenience
layer around `addEventListener()`.

## Features

- Converts numerical input values into floats, checkbox values into booleans
- Let's you easily hook callbacks to input elements, possibly in bulk
- Can automatically set properties on an objects when input values change

## Markup requirements

- Set the `data-inputs` attribute on all input elements you want to hook up
- Optionally give the `data-inputs` attribute a value to create groups of inputs
- Optionally set the `data-inputs-id` attribute to give inputs custom identifiers (otherwise defaults to the `id`)
- Optionally set the `data-inputs-event` attribute to listen to an event other than `change`

## How to use

Sorry, I'll fill this space with some proper documentation soon.
For now, just check out the `index.html` for some pointers.

