## Installing Bon

### Linux

To build Bon, you need to first install the LLVM dev toolchain (i.e. install the llvm-dev package using apt in Ubuntu, or build from source from [here](http://releases.llvm.org)). Currently, the only version tested is 4.0.1, so your mileage may vary if you build against a different version.

```bash
$ git clone https://github.com/FBMachine/bon.git
$ cd bon
$ ./build.sh
$ source ~/.profile
```

To test that everything installed properly:

```bash
$ bon --version
$ bon examples/hello.bon
Hello, world!
```



### Other platforms

Bon is in a very early stage of development, so there are no other supported platforms (though MacOS __may__ just work). Help with testing and supporting other platforms would be greatly appreciated.


