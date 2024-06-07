# Release Steps

```sh
npm install
npm run build
rsync -a ./dist/ root@164.90.206.1:/var/www/cicd/
```