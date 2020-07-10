# teacss-docs

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

This is a small website about how to use [teacss](https://github.com/boomyjee/teacss)

## Use
just open /index.html file

## Develompment
If you want to change html files
you can run /build/index.php file.

But before use it you should get /tools/ folder from (teacss project)[https://github.com/boomyjee/teacss],
put it into `/build` folder and change line 4 in `/build/style.tea` file:
```css
@import "tools/donut/donut.tea";
```

If you see nothing in the right top corner please add this line
between ```body``` tags in `/build/index.php` file:
```html
<h1>Build page for teacss-docs</h1>
```


### License

Plugin is [MIT licensed](./LICENSE).
