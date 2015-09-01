# eria

An isomorphic Node.js stack

## Usage

```shell
// start a project using eria
$ eria init eria-example

// here we go, create a component via the cli tool
$ eria new CounterComponent

// then it will notify you which Action and Store you want to associate it with
// if they exist then we do nothing, or we shall create them
// if you leave it black then we shall find one by the component name
// like `CounterActions` for `CounterComponent` 
$    Which Actions you want to use:
$    Which Store you want to use:

// you can also create Actions and Store yourself
$ eria new CustomActions
$ eria new CustomStore
```

## License

MIT.
