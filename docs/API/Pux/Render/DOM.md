## Module Pux.Render.DOM

#### `renderToDOM`

``` purescript
renderToDOM :: forall eff. String -> ReactClass -> Eff (chan :: Chan, dom :: DOM | eff) Unit
```

Renders an application in the DOM element found using given `ElementId`.


