# redwood-relay-templates

Production copies of [generator templates](https://redwoodjs.com/docs/cli-commands#generate-alias-g) for Redwood with:
 
- Relay for data fetching client-side
- Conforming to the [Object Identification](https://graphql.org/learn/global-object-identification/) GraphQL pattern
- Using Redwood forms for the create/edit form
- Uses the Redwood [Experimental SDL Code Generation](https://redwoodjs.com/docs/typescript/generated-types#experimental-sdl-code-generation) for types
- Supports [Artsy-style](https://artsy.github.io/blog/2018/10/19/where-art-thou-my-error/) error handling (e.g via `union` types)

Builds on the infra which you can read up on in [orta/relay-redwood-app-example](https://github.com/orta/relay-redwood-app-example).

This is a direct port from puzzmo.com's codebase, so expect to make modifications in your own projects.