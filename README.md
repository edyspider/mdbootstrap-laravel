# mdbootstrap-laravel
How to install [MDBootstrap](https://mdbootstrap.com/) in [Laravel](https://laravel.com/) [5.8](https://laravel.com/docs/5.8).

---

## Getting Started
Use the following steps in order to install mdbootstrap in laravel 5.8.

### Step 1:
Install dependecies.

```cmd
npm install mdbootstrap
```

### Step 2:
Delete **.git** folder in node_modules.
 
 ```` "node_modules\mdbootstrap\.git" ````

### Step 3:
Update ```` "resources\js\bootstrap.js" ```` file.

```js
require('mdbootstrap');
```

### Step 4:
Update ```` "resources\sass\app.scss" ```` file.

```scss
// MDBootstrap
@import '~mdbootstrap/scss/mdb';
```

### Step 5:
Compile.

```cmd
npm run dev
```

### Step 6:
In your master layout add:

```html
<script src="{{ asset('js/app.js') }}"></script>
<link rel="stylesheet" href="{{ asset('css/app.css') }}">
```

---

## Authors

* [**EdySpider**](https://github.com/edyspider)

See also the list of [contributors](https://github.com/edyspider/mdbootstrap-laravel/graphs/contributors) who participated in this project.

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](https://github.com/edyspider/mdbootstrap-laravel/blob/master/LICENSE)**
- Copyright 2018 © <a href="https://github.com/edyspider" target="_blank">EdySpider</a>.

---

## Credits
[markhilton](https://gist.github.com/markhilton): [mdbootstrap-laravel-spark.md](https://gist.github.com/markhilton/092a53b91df347792db2f5d2cdf83b23)
