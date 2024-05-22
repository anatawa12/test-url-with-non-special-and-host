# test URL with non-special scheme and has host

I recently found that some URL implementation parse `vcc://vpm/addRepo?url=https%3A%2F%2Fvpm.anatawa12.com%2Fvpm.json`
as URL with `//vpm/addRepo` as pathname and no host and 
other implementation parse it as URL with `vpm` as host and `addRepo` as pathname.

This page is to test how the URL parser in the browser parses the URL.

[view it on github pages](https://anatawa12.github.io/test-url-with-non-special-and-host)
