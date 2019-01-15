# astalib-cmd
Command line application using astalib

## Dependencies

git clone git@github.com:edupaz2/astalib.git

## Build instructions
```
g++ -Wall -I./astalib/include/ -L./astalib -Wl,-rpath=astalib/ main.cpp -lastalib -o main
```

