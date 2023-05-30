# ckeditor5-line-heights

Plugin for CKEditor5 to change your lingheight.

## Get Started

Install:

```bash
npm install --save ckeditor5-line-heights
```

or using yarn:

```bash
yarn add ckeditor5-line-heights
```

Use it in your application:

```js
import LineHeight from "ckeditor5-line-heights/src/lineheight";
```

Add it to your editor:

```js
ClassicEditor
    .create( document.querySelector( '#editor' ), {
        plugins: [
            ...,
            LineHeight, //添加到你的插件列表
        ],
        lineHeight: { // 自定义你自己的行高数值
            options: [ 0.5, 1, 1.5, 2, 2.5 ]
        }
        toolbar: [
            ...,
            'lineHeight', // 添加到你的工具栏
        ]
    } )
```

## License

Licensed under the terms of [GNU General Public License Version 3](http://www.gnu.org/licenses/gpl.html).
