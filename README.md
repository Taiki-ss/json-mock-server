# json-mock-server

## What
フロント開発においてバックエンドAPIの実装が間に合ってない場合に使用するJSONを返すMockServer

## How
1. `sample-data/data.json`にresponseしたいJSONを記載。
2. `npm run mock`で`localhost:3100/{data.jsonのキー名}`にアクセスするとJSONが返る。
