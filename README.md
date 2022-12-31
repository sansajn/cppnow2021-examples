# cppnow2021-examples
Examples to be shown at C++Now 2021 by Lucian.

To build *concurrency-tutorial* install *SCons* package with

```bash
sudo apt install scons
```

command and build samples with

```bash
cd concurrency-tutorial
scons -j16
```

commands.

> **note**: Tracy support is automatically enable in case tracy is installed to `~/usr/local` directory. For more details see [Tracy profiler integration](https://sansajn.github.io/post/2022/12/29/tracy-as-library.html) tutorial.
