# The default registry of Fix programming language

## Overview

The registry.toml file in this repository is the default registry file that the [fixlang](https://github.com/tttmmmyyyy/fixlang) compiler refers to by default.

For example, the "math" project is registered in the registry.toml:

```
[[projects]]
name = "math"
git = "https://github.com/tttmmmyyyy/fixlang-math.git"
```

When you use it in your Fix project, run "fix deps add math".

## Add your Fix project

If you kindly add your Fix project to this registry, other people can easily use your project.
In this case, please create a Pull Request to change the registry.toml file.

Please note that Fix cannot use projects with the same name in the same project.
Therefore, it is recommended to use a unique name for the module.