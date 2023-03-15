This is a very simple extension which turns on "Parsoid Read Views".

It doesn't really do much other than ensuring the ParserOptions
`useParsoid` flag is true when viewing Article pages.

Add:
```
wfLoadExtension( 'ParsoidReadViews' );
```
to your `LocalSettings.php` to enable; you can also then disable it
with:
```
$wgParsoidReadViewsEnable = false;
```
if you need to.

Running `npm test` and `composer test` will run automated code checks.
