# wasm-emscripten-binaryen Loaded onto Gitpod.io


This repository can load a fully running version of emscripten using the browser based docker called Gitpod.io



1. First login to Github
2. Load ```Gitpod.io/#``` with this repository  using this link    https://gitpod.io/#github.com/hpssjellis/gitpod-wasm-emscripten-binaryen
3. Watch the magic as Gitpod.io loads the entire emscripten framework and loads a Hello World example and puts you in the ```myExample``` folder
4. Happy coding!

When you have made a .c file called myFile.c run it using this command

```

emcc myFile.c -o myFile.html

```


A C++ file would be ran this way

```
em++ myFile.cpp -o myFile.html

```

## You must use the main terminal since other terminals do not have the PATH set.

Note on a new terminal the path might be needed to be set with this command

```
export PATH="/w/workspace/gitpod-wasm-emscripten-binaryen/emsdk:/workspace/gitpod-wasm-emscripten-binaryen/emsdk/upstream/emscripten:orkspace/wasm-emscripten-binaryen/emsdk/upstream/emscripten:$PATH"
```


Or edit the 

```
tasks:
  - before: printf 'export PATH="%s:$PATH"\n' "/usr/games" >> $HOME/.bashrc && exit
```

.




.


Examples at   https://emscripten.org/docs/porting/connecting_cpp_and_javascript/embind.html#a-quick-example


