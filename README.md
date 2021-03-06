# Opener

Quickly open and close the applications you use every day.

### Installation

If you have Go installed:

```
go get -u github.com/jonathanwthom/opener
cd $GOPATH/src/github.com/jonathanwthom/opener
go install
```
Don't forget to add $GOPATH to $PATH to be able to call this app.

### Usage

In the root of your filesystem, create a file called applications.json.

`touch ~/applications.json`

In that file, list the names of the files you want to use in an array, like [this](https://github.com/JonathanWThom/opener/blob/master/applications.json).

To open all the applications in your list, simply run `opener`.
When you want to close them, run `opener -c`.

### Notes

This program was built on a my Mac, so probably only works on Unix systems.

If it doesn't work as intended, please open an issue!

### TODO:

* Better error handling/more informative messages;
* Add profiles;
* Check if app already running;

### License

MIT
