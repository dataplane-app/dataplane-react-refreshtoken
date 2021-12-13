# React library to refresh tokens

A React library to silently refresh access tokens in the background using a refresh token. 

- Silent refresh of JWT access tokens
- cookies or localstorage
- React router - private and public routing

Github: https://github.com/dataplane-app/dataplane-react-refreshtoken


# Development 

Install yalc globally
```
yarn global add yalc
```

In NPM package - first run
```
yarn
yarn build
yalc publish
```

In NPM package repo to update
```
yarn build && yalc push
```

In app that needs to reference the npm dependency
```
yalc link @dataplane/dataplane-react-refreshtoken
```

To remove from repo
```
yalc remove @dataplane/dataplane-react-refreshtoken
```

