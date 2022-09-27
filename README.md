# Practice Sed

Practice `sed` (Command File).

```bash
# Sed File
$ cat ./example.sed
s/aaa/bbb/

# `-f` : GNU And BSD Sed
$ echo 'aaa' | sed -f ./example.sed
bbb
$ echo 'AAA' | sed -f ./example.sed
AAA

# `--file` : GNU Sed Only
$ echo 'aaa' | sed --file ./example.sed
$ echo 'aaa' | sed --file='./example.sed'
```


## Links

- [Neo's World](https://neos21.net/)
