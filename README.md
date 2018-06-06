# ARMIPS Assembler Language Support in Atom

Add syntax highlighting for use with the [ARMIPS toolchain](https://github.com/Kingcom/armips) to Atom.

This package depends on the already existing excellent [language-mips](https://github.com/Jakehp/language-mips) and [language-arm](https://github.com/dan-c-underwood/language-arm) packages, which adds language support for ARM and MIPS assembly languages. These two packages are required by this one since it only extends those packages with commands and instructions specific to ARMIPS.

The package should check for dependencies automatically. Else, install the packages mentioned above by running

```
apm install language-mips language-arm
```

or by using the package installer in Atom's settings window.

This is work in progress. Please use Github's issue function to report bugs or improvement ideas. Contributions are greatly appreciated!

## Known bugs
While MIPS support works, ARM syntax highlight is still faulty. There seems to be some conflicts with my existing code. I hope to fix this in the next update.
