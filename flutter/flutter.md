# Flutter

## Installing and updating
The installation instructions are found here: 
[https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install). 

You can keep the installation up-to date using the flutter doctor.

```sh
$ flutter doctor
```

and upgrade when needed:
```
$ flutter upgrade
```

## Development process
Scaffolding a new application using the command line:

```sh
$ flutter create my_app
```

Then run the app using

```sh
$ flutter run
```

If Chrome is installed, you can run it as a web app using

```sh
$ flutter config --enable-web
```

## Widgets
Everything in Flutter is a widget. There are many widgets you can use and you
can find them here: [https://flutter.dev/docs/reference/widgets](https://flutter.dev/docs/reference/widgets)

They can be catagorized in 14 categories [ https://flutter.dev/docs/development/ui/widgets](https://flutter.dev/docs/development/ui/widgets).

Flutter applications don't use a DOM but an element tree instead. The element
tree is a tiny copy of the elements on screen. Flutter maintains one with
the current state and one with batched changes applied.

Flutter periodically diffs the two and will only rerender the parts that
have changed. When using statufull widgets updating somtimes fails, and then
widget keys can solve updating problems.

A nice explanation on widget keys can be found [here](http://bit.ly/FlutterKeys).

