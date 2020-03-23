# tinymce-langs

support Tinymce5 langs cdn https://www.jsdelivr.com/package/npm/tinymce-langs?path=langs

## Why

Currently Tinymce5 langs does not have cdn. So create an npm package, let lang supports cdn.

## Use

All cnd in [jsdelivr](https://www.jsdelivr.com/package/npm/tinymce-langs?path=langs)

- [zh_CN](https://cdn.jsdelivr.net/npm/tinymce-langs/langs/zh_CN.js)
- [ja](https://cdn.jsdelivr.net/npm/tinymce-langs/langs/ja.js)
- ...

```
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  language: 'zh_CN', // select language
  language_url: 'https://cdn.jsdelivr.net/npm/tinymce-langs/langs/zh_CN.js'  // site absolute URL
});
```