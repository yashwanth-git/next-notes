# Next Notes
This is a personal notes on Next 12

## Setup
As I am focussing on exploring `yarn` adding yarn commands below

```
yarn create next-app
```

For typescript support

```
yarn create next-app --typescript
```

Avoiding manual setup thats overhead. [Can explore if need arise]

`pages/` directory holds all the pages
`public/` directory holds static assets

## Features
### Pages 

- `pages/index.js` is the entry point of the app. Extensions can be js, ts, jsx, tsx
- Any file with proper extension will be accessible with the name given [`pages/about.js` points to about page] 
- Pages with dynamic routes can be provided by using `pages/posts/[id]` 