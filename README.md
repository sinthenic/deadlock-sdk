# deadlock-sdk

source2 sdk for deadlock, automatically generated using [source2gen](https://github.com/neverlosecc/source2gen).

## generation

```
git clone --recurse-submodules https://github.com/neverlosecc/source2gen.git
conan build -o "game=DEADLOCK" --build=missing .
```

run deadlock, then execute `source2gen-loader.exe` to inject and generate the sdk.
