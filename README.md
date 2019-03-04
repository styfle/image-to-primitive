[cover](./assets/cover.png?raw=true)

# Image to Primitive

Serverless service reproducing images with primitive shapes written in [Golang](https://golang.org/).

## Deploy your own

You'll want to fork this repository and deploy your own image to primitive.

1. Click the fork button at the top right of GitHub
2. Clone the repo to your local machine with `git clone URL_OF_FORKED_REPO_HERE`
3. You may want to increate [number of primitive](https://github.com/sophearak/image-to-primitive/blob/master/primitive.go#L99), [output size](https://github.com/sophearak/image-to-primitive/blob/master/primitive.go#L142).
4. Deploy by running `now` from the CLI (if you don't already have it, run `npm install -g now`)

Alternatively, you can do a one-click to deploy with the button below.

[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/sophearak/image-to-primitive)

Credits

- Primitive by Michael Fogleman [https://github.com/fogleman/primitive](https://github.com/fogleman/primitive)
- The Go gopher was designed by Renee French. [https://github.com/styfle/og-image](http://reneefrench.blogspot.com/)
- Go Gopher vector illustration by Hugo Arganda @argandas [http://about.me/argandas](http://about.me/argandas)