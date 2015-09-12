# arc3.1

A mirror of [arc3.1.tar](https://github.com/laarc/arc3.1/releases/download/1/arc3.1.tar), the latest release of Arc as of 11 Sep 2015

See also:

* [arc0](https://github.com/laarc/arc0)
* arc0 vs arc3.1 ([html](https://rawgit.com/laarc/notebook/master/arc0-3.1.html) | [txt](https://rawgit.com/laarc/notebook/master/arc0-3.1.txt))

```
$ wget https://github.com/laarc/arc3.1/releases/download/1/arc3.1.tar
$ cat arc3.1.tar | shasum -a 256
18fa4d1e5bff333d66e6ec01d8485f3b1f2a9d59959b119d7118ea305177c014  -
$ tar xvf arc3.1.tar
$ cd arc3.1
$ ls -1 | grep '\.scm$' | xargs cat | wc -l
    1553
$ ls -1 | grep '\.arc$' | xargs cat | wc -l
    6564
```

