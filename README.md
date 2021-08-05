1. `docker-compose up -d`でコンテナを立ち上げる
2. `docker-compose exec app bash` でコンテナに入る
3. `yarn create @vitejs/next` してプロジェクトを作る
4. `vanilla` `vanilla-ts` を選ぶ
5. あとは指示通りに`cd vite-project` からの `yarn` からの `yarn dev --host`　でサーバーが動く

これで環境ができるので `src > main.ts` にタイプスクリプト書いていけばいいよ
