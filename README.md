# The default registry of Fix programming language

## Overview

This repository provides the default registry file that is referred to by the dependency management feature of the [fixlang](https://github.com/tttmmmyyyy/fixlang) compiler.

For example, since the "math" project is registered in the [registry.toml](registry.toml) file,

```
[[projects]]
name = "math"
git = "https://github.com/tttmmmyyyy/fixlang-math.git"
```

you can add "math" project to your project by running `fix deps add math`.

## Add your Fix project

If you kindly add your Fix project to this registry, other people can easily use your project.
In this case, please create a Pull Request to change the registry.toml file.

Please note that Fix cannot use multiple modules with the same name in the same project.
Therefore, it is recommended to give an unique name for your module.