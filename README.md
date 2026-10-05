<!-- tyhp-readme:start -->
# tyhpdef/spatie-laravel-medialibrary

Tyhp type definitions for `spatie/laravel-medialibrary` `11.23.8`.

```bash
composer require --dev tyhpdef/spatie-laravel-medialibrary:11.23.8
```

This is a metapackage. Composer also installs `tyhpdef/spatie-laravel-medialibrary-impl` (type files).
Require **this** name, not `tyhpdef/spatie-laravel-medialibrary-impl`.

See https://tyhplang.com.

## Maintain `spatie/laravel-medialibrary`? Ship the types yourself

If you are a Packagist maintainer of `spatie/laravel-medialibrary`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/spatie-laravel-medialibrary-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `spatie/laravel-medialibrary` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/spatie-laravel-medialibrary": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `spatie/laravel-medialibrary` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `spatie/laravel-medialibrary` with a real constraint,
   `"replace": { "tyhpdef/spatie-laravel-medialibrary": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `spatie/laravel-medialibrary` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/spatie-laravel-medialibrary` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
