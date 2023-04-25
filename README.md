# ckeditor5-line-height

Plugin for CKEditor5 to change your lingheight.

## Get Started

Install:

```bash
npm install --save ckeditor5-line-height
```

or using yarn:

```bash
yarn add ckeditor5-line-height
```

Use it in your application:

```js
import LineHeight from "ckeditor5-line-height/src/lineheight";
```

Add it to your editor:

```js
ClassicEditor
    .create( document.querySelector( '#editor' ), {
        plugins: [
            ...,
            LineHeight, // add it to your plugins array
        ],
        lineHeight: { // specify your otions in the lineHeight config object. Default values are [ 0, 0.5, 1, 1.5, 2 ]
            options: [ 0.5, 1, 1.5, 2, 2.5 ]
        }
        toolbar: [
            ...,
            'lineHeight', // add the button to your toolbar
        ]
    } )
```

## License

Licensed under the terms of [GNU General Public License Version 3](http://www.gnu.org/licenses/gpl.html).
