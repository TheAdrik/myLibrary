# myLibrary

### myLibrary is the simple library catalog with admin panel, made with VueJS, NodeJS and Firebase.

Project demo is available at: https://bit.ly/2KAgE55 (login: zvpsbpmf@q.cb, password: SJZB4Agw).

# Getting started

This app is built using [vue-cli webpack](https://github.com/vuejs-templates/webpack), so to get started first you have to do is:
``` bash
# install dependencies
> npm install
```
After installing dependencies, you'll need to setup connection with Firebase database. To do this, [create Firebase project](https://console.firebase.google.com/), copy your config and paste it in Main.vue file, then create new Firebase user with email/password authentication and setup database:
### Database structure
```
XXX
  |
  books
      |
      |- YYY
      |    |- Author
      |    |- Imglink
      |    |- Isbn
      |    |- Status
      |    |- Title
      |
      |- ZZZ
      |    |- ...
      ...  ...
```
Next run your application:
```|
# serve with hot reload at localhost:8080
> npm run dev
```

Other commands available are:
``` bash
# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run single unit tests
npm run unit

# run continous unit tests
npm run units

# run e2e tests
npm run e2e

# run all tests
npm test
```

# License

```
Copyright (c) 2018 Adrian Orłów

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
