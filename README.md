<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
</p>

# GraphQL Summit Bootcamp

Welcome to the GraphQL Summit Bootcamp! We're really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Topics

- [GraphQL Subscriptions](https://github.com/graphqlworkshop/summit-bootcamp#graphql-subscriptions)
- [Apollo Tooling](https://github.com/graphqlworkshop/summit-bootcamp#apollo-tooling)
- [Apollo Federation](https://github.com/graphqlworkshop/summit-bootcamp#apollo-federation)
- [Federation Lab](https://github.com/graphqlworkshop/summit-bootcamp#federation-lab)

## GraphQL Subscriptions 🎧

### Slides

- [Intro Slides](https://slides.com/moonhighway/summit-bootcamp)

### Samples

- [Intro Slides](https://slides.com/moonhighway/summit-bootcamp)

### Helpful Links

- [Intro Slides](https://slides.com/moonhighway/summit-bootcamp)

## Apollo Tooling 🛠

## Apollo Federation 🚀

## Federation Lab 👩🏻‍🔬

```
ENGINE_API_KEY=
```

#### Download the Schema

`npx apollo schema:download --endpoint=https://snowtooth.moonhighway.com graphql-schema.json`

#### Generate Types

`npx apollo codegen:generate --localSchemaFile=graphql-schema.json --target=typescript --includes=src/**/*.ts --tagName=gql --addTypename --globalTypesFile=src/types/graphql-global-types.ts types`

## TypeScript Resources

- [TypeScript & Apollo - Apollo Docs](https://www.apollographql.com/docs/react/development-testing/static-typing/)
- [React TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet)
