# Rush Monorepo

Playing with monorepos.

## apps/landing

A create-react-app that uses `libs/components`.

## libs/components

Shared components (built with tsdx), used by `apps/landing`.

## Deployment

This application's `landing` app can be deployed to Netlify with the following build command:

```
npm i -g @microsoft/rush && rush install && rush build && rush deploy --overwrite -p landing && cd common/deploy/apps/landing && rushx build
```
