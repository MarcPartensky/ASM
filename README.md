# Trying out assembly on osx
(Replace * by the name of the file)

## Install asm on osx
```zsh
brew install nasm
```

## Compile into *.o
```zsh
nasm -f macho64 *.asm
```

## Compile *.o inti binary
```zsh
ld -macosx_version_min 10.7.0 -o * *.o
```

## Run
```zsh
./*
```

## Reference
<cite><a>https://medium.com/@thisura1998/hello-world-assembly-program-on-macos-mojave-d5d65f0ce7c6</a></cite>
<cite><a>https://cs.lmu.edu/~ray/notes/asmtoexe/</a></cite>
