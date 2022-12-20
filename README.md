# salmonDec2022
Trying Salmon Dec 2022, see https://www.biostars.org/p/98756/#9549038 and https://www.biostars.org/p/389360/

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/salmonDec2022/HEAD)

### Technical details

Use `mylocate libboost_iostreams.so` to search for the version of `libboost_iostreams.so` installed.  

```shell
mylocate libboost_iostreams.so
```

For some reason, the binder build I based this on was using `mylocate` instead of `locate` to do the same thing. I think it has to do with permissions and building the database. Anyways, it works if you use `mylocate` in place of the typical `locate` command.