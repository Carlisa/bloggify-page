
# bloggify-page

 [![Patreon](https://img.shields.io/badge/Support%20me%20on-Patreon-%23e6461a.svg)][patreon] [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/bloggify-page.svg)](https://www.npmjs.com/package/bloggify-page) [![Downloads](https://img.shields.io/npm/dt/bloggify-page.svg)](https://www.npmjs.com/package/bloggify-page) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> The Bloggify page class.

## :cloud: Installation

```sh
$ npm i --save bloggify-page
```


## :clipboard: Example



```js
const BloggifyPage = require("bloggify-page");


let home = new BloggifyPage({
    title: "Home"
  , content: "Hey there!"
  , metadata: {
        customField: "Hello Mars!"
    }
});

console.log(home);
// BloggifyPage {
//   title: 'Home',
//   slug: 'Home',
//   url: '/Home',
//   content: 'Hey there!',
//   customField: 'Hello Mars!',
//   raw_content: 'Hey there!' }
```

## :memo: Documentation


### `bloggifyPage(a, b)`
The Bloggify page class.

#### Params
- **Number** `a`: Param descrpition.
- **Number** `b`: Param descrpition.

#### Return
- **Number** Return description.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :moneybag: Donations

Another way to support the development of my open-source modules is
to [set up a recurring donation, via Patreon][patreon]. :rocket:

[PayPal donations][paypal-donations] are appreciated too! Each dollar helps.

Thanks! :heart:

## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`bloggify-article`](https://github.com/IonicaBizau/bloggify-article#readme)—The Bloggify article class.
 - [`bloggify-viewer`](https://github.com/IonicaBizau/bloggify-viewer#readme)—Connects the CRUD operations with the renderer.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[patreon]: https://www.patreon.com/ionicabizau
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
