# Website for DialogOS (www.dialogos.app)

This is the main website for DialogOS. It is available both in English and German. The preferred browser language is automatically determined by some Javascript in `index.html`, and the user is then redirected to the desired language.

Please ensure that content in the `en` and `de` subdirectories is always kept synchronous.

## Compiling the website locally

To compile the website on your own computer, first install the necessary themes as follows:

```
sudo bundle install
```

Then you can compile the website to HTML and view it like this:

```
exec bundle jekyll serve
```


