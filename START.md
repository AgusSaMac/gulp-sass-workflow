# To begin a project

The steps to begin a project are as follows:

1. `npm init` create the package.json
2. Open the package.json and in the devDependencies add the following:
```
"devDependencies": {
"autoprefixer": "^10.4.13",
    "cssnano": "^6.0.0",
    "gulp": "^4.0.2",
    "gulp-autoprefixer": "^8.0.0",
    "gulp-avif": "^1.1.1",
    "gulp-cache": "^1.1.3",
    "gulp-clean": "^0.4.0",
    "gulp-cssnano": "^2.1.3",
    "gulp-concat": "^2.6.1",
    "gulp-imagemin": "^8.0.0",
    "gulp-plumber": "^1.2.1",
    "gulp-postcss": "^9.0.1",
    "gulp-sass": "^5.1.0",
    "gulp-sourcemaps": "^3.0.0",
    "gulp-terser-js": "^5.2.2",
    "gulp-webp": "^4.0.1",
    "postcss": "^8.4.14",
    "sass": "^1.60.0"
  }
```

3. Use `npm i` or `npm install` to install the dependencies.
4. It is recomended to use `npm outdated` to check for newer versions. ***WARNING:*** New updates may break your workflow make sure to check the notes of the publisher.