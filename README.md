# tracing-logcat

tracing-logcat is a library that provides an Android logcat output for the `tracing` library. It directly communicates with Android's `logd` process instead of using `liblog.so`, making it suitable for use with statically linked executables.

See [`examples/`](./examples/) for examples of how to use this library.

## Contributing

([AI policy](https://github.com/chenxiaolong/chenxiaolong/blob/master/AI_POLICY.md))

Bug fix pull requests are welcome and much appreciated!

If you are interested in implementing a new feature and would like to see it included in tracing-logcat, please open an issue to discuss it first.

## License

tracing-logcat is licensed under Apache 2.0. Please see [`LICENSE`](./LICENSE) for the full license text.
