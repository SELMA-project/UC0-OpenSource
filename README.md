# SELMA Use Case 0 (UC0) Open Source version

<B>Download All Parts</B> of the split archive to the same directory from the Release https://github.com/SELMA-project/UC0-OpenSource/releases/tag/v1.0.0.0.

<B>Reassemble the Archive</B> using the cat command:

```
cat myfolder.tar.gz.part* > myfolder.tar.gz
```

<B>Decompress the Reassembled Archive</B> with tar:
```
tar -xzvf myfolder.tar.gz
```

<B>Run</B> the UC0 server by executing one of:

```
./uc0-darwin
```
or
```
./uc0-linux-x86_64
```

<B>Open</B> in browser `http://localhost:9090`
