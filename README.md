# Laravel nginx mysql php7.4 Docker starter

set up laravel nginx mysql project with docker

<br/>

<span style="color:red">note:</span> before run docker command you have to create `.env` file in root directory. you can rename `.env.example` and use it

command list
- `docker-compose up`

attach to laravel container shell and run `composer create-project laravel/laravel .`<br/>
when installation's done, open `localhost:8080` in your browser


<br/>
<br/>

## 日本語
# laravel nginx mysql php7.4 dockerテンプレート

laravelとdockerでnginxサーバーで起動用のスタートテンプレートです。

<br/>

<span style="color:red">注意：</span> dockerコマンド叩く前に`.env`ファイルを作成する必要あります、`.env.example`を参考にしてください。

`docker-compose up`をルートディレクトリで実行して、コンテナーが立ち上がったら、laravelのappコンテナーにshell attachし、`composer create-project laravel/laravel . `を実行するとlaravelプロジェクトがインストールされます。 
