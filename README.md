
# Demo Repo to reproduce https://github.com/ionic-team/ionic-framework/issues/27564

## Repro steps

1. Clone repo
2. Run npm install
3. Run npm run dev:ssr
4. Open app in the browser.

## How this was created

1. Followed [SSR with Angular Universal And Ionic](https://ionic.io/blog/ssr-with-angular-universal-and-ionic) (installed non-dev version of `isntalled `)
2. Bumped version of `@types/node`
3. Added `<ion-item>` to home page