## SampleUpdateData

```
linhas 6 e 14 de ./app/version-check/server/sampleUpdateData.js
infoUrl: 'https://rocket.chat',
este ficheiro nao e utilizado
```

```
linha 33 de ./app/version-check/server/functions/getNewUpdates.js
const { data } = HTTP.get('https://releases.rocket.chat/updates/check', {
chamado na linha 15 de ./app/version-check/server/functions/checkVersionUpdate.js
notifica admins de que ha nova versao, nao afeta utilizadores normais
```