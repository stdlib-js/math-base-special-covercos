<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Covercosine

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Compute the [coversed cosine][coversed-cosine].

<section class="intro">

The [coversed cosine][coversed-cosine] is defined as

<!-- <equation class="equation" label="eq:covercosine" align="center" raw="\operatorname{covercos}(\theta) = 1 + \sin \theta" alt="Coversed cosine."> -->

<div class="equation" align="center" data-raw-text="\operatorname{covercos}(\theta) = 1 + \sin \theta" data-equation="eq:covercosine">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@bb29798906e119fcb2af99e94b60407a270c9b32/lib/node_modules/@stdlib/math/base/special/covercos/docs/img/equation_covercosine.svg" alt="Coversed cosine.">
    <br>
</div>

<!-- </equation> -->

</section>

<!-- /.intro -->



<section class="usage">

## Usage

To use in Observable,

```javascript
covercos = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-covercos@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var covercos = require( 'path/to/vendor/umd/math-base-special-covercos/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-covercos@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.covercos;
})();
</script>
```

#### covercos( x )

Computes the [coversed cosine][coversed-cosine] (in radians).

```javascript
var v = covercos( 0.0 );
// returns 1.0

v = covercos( 3.141592653589793/2.0 );
// returns 2.0

v = covercos( -3.141592653589793/6.0 );
// returns 0.5
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/array-base-linspace@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-two-pi@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-covercos@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var x = linspace( 0.0, TWO_PI, 100 );

var i;
for ( i = 0; i < x.length; i++ ) {
    console.log( covercos( x[ i ] ) );
}

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/math/base/special/coversin`][@stdlib/math/base/special/coversin]</span><span class="delimiter">: </span><span class="description">compute the coversed sine.</span>
-   <span class="package-name">[`@stdlib/math/base/special/vercos`][@stdlib/math/base/special/vercos]</span><span class="delimiter">: </span><span class="description">compute the versed cosine.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-special-covercos.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-special-covercos

[test-image]: https://github.com/stdlib-js/math-base-special-covercos/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/math-base-special-covercos/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-special-covercos/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-special-covercos?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-special-covercos.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-special-covercos/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-special-covercos/tree/deno
[umd-url]: https://github.com/stdlib-js/math-base-special-covercos/tree/umd
[esm-url]: https://github.com/stdlib-js/math-base-special-covercos/tree/esm
[branches-url]: https://github.com/stdlib-js/math-base-special-covercos/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-special-covercos/main/LICENSE

[coversed-cosine]: https://en.wikipedia.org/wiki/Versine

<!-- <related-links> -->

[@stdlib/math/base/special/coversin]: https://github.com/stdlib-js/math-base-special-coversin/tree/umd

[@stdlib/math/base/special/vercos]: https://github.com/stdlib-js/math-base-special-vercos/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
