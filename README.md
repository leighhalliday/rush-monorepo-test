# Rush Monorepo

Playing with monorepos.

## apps/landing

A create-react-app that uses `libs/components`.

## libs/components

Shared components (built with tsdx), used by `apps/landing`.

## Deployment

My attempt to far, which is not working... the build command on Netlify.

```
npm i @microsoft/rush && rush install && rush build && rush deploy --overwrite -p landing && cd common/deploy/apps/landing && yarn run build
```
