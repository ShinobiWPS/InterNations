# What's missing from the my setup

## Webpack Aliases
```
module.exports = {
  resolve: {
    extensions: ['js', 'ts'],
    alias: {
      '@': path.resolve(__dirname, 'src'),
      '@assets': path.resolve(__dirname, 'src/assets'),
      '@components': path.resolve(__dirname, 'src/components'),
      // ...etc
    },
  },
}
```

## Client State management
- ReactN - [link](https://www.npmjs.com/package/reactn)

## Offline
- CRA serviceWorker - [link](https://create-react-app.dev/docs/making-a-progressive-web-app/)
## Fetching
- Ky - [link](https://github.com/sindresorhus/ky)

## CSS solutions
- static imported CSS or:
- Linaria - [link](https://github.com/callstack/linaria)


## Commit conventions
- I would use this syntax "🐛Sidebar menu wasn't opening" (need to setup CommitLint)


- files in `styles` folder contain the `styles` string so that you are able to call a file via the editor based on name
