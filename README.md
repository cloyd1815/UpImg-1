# UpImg
> UpImg is an open source image-upload tool, based in the language of Go. Images are currently stored in the images/ directory. [Here](http://boboman13.net:8080 "UpImg Example") is an example installation.

[![Build Status](https://travis-ci.org/boboman13/UpImg.png?branch=master)](https://travis-ci.org/boboman13/UpImg)

### Compilation
```bash
$ go get github.com/boboman13/UpImg
$ cd $GOPATH/UpImg/src/main

$ go build
```

### Software Usage
Make sure that the `main` file is located in the root directory of the UpImg install (~/UpImg/). Running `ls` should show the `static` and `src` directories. Once this is completed, `mkdir images` will create the images directory.
```bash
$ ./main
```

### Contributing
Simply fork the project, edit changes to your local repository, and submit a pull request to contribute to the project. We follow basic coding standards, and keep in mind the goals of the project before submitting a pull request.

If the fork, add-on, or modification to the code does not reflect on the project's goals, the pull request will (probably) not be accepted. If this happens, in its stead, you may notify the UpImg manager (@boboman13) to have the fork noted and linked to in the readme. Note: follow the LICENSE!

### Project Core Goals
* **Cleanliness**: Keep the source code clean and easy to read. In addition, keep the user interface very easy to manipulate and use. Try to make image uploads as seamless as possible.
* **Speed**: Make sure UpImg is fast. It'll be bottlenecked by network speeds, but lets try and cut out everywhere we can with speed. (This includes Javascript UI)
* **Usability**: There should be no learning curve for the software. The config should be kept minimal and the upload should be a one-stop shop.