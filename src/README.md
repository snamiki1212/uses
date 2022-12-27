## Getting Started

```zsh
$ yarn

$ pwd
/.../src

$ diff -u ../2022.md ../2023.md > ./diff/2022-2023.diff
$ cat ./diff/2022-2023.diff | yarn diff2html --style side --input stdin --file .bin/2022-2023.html
$ open .bin/2022-2023.html
```