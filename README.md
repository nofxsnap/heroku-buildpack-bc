# Heroku Buildpack - Tesseract

Added the libraries to use [bc](http://www.gnu.org/software/bc/) 1.0.6 on Heroku.

This buildpack is built to be used through [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi).
In your app you need to:


```
heroku config:set
BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi
```

Then, create a `.buildpacks` file inside your app:

```
https://github.com/heroku/_YOUR_MAIN_BUILDPACK
https://github.com/Helabs/heroku-buildpack-bc.git
```

See the documentation of heroku-build-multi for a detailed explanation
how to use it.

## License

MIT License.
