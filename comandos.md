npx nx generate @nrwl/js:library data-access --unitTestRunner=jest --directory=user
npm i -D @nrwl/express
npx nx generate @nrwl/express:application back-end
npm i -D @nrwl/web
npx nx generate @nrwl/web:application front-end
