# SELMA Use Case 0 (UC0) Open Source version

<B>Online demo</B> version of SELMA UC0 is available at: https://selma.ailab.lv

<B>How to use</B> video is available at: https://youtu.be/r4nsumsnR5M

<B>The project</B> page is available at: https://selma-project.eu/

## Install your own private copy of UC0

<B>Download All Parts</B> of the split archive to the same directory from the Release https://github.com/SELMA-project/UC0-OpenSource/releases/tag/v1.0.0.0.

<B>Reassemble the Archive</B> using the cat command:

```
cat UC0run.tgz.part* > UC0run.tgz
```

<B>Decompress the Reassembled Archive</B> with tar:
```
tar -xzvf UC0run.tgz
```

<B>Run</B> the UC0 server by executing one of:

`./uc0-darwin` on Apple MacOS (arm M1, M2, M3 or Intel x86 CPU) 

or

`./uc0-linux-x86_64` on Linux


<B>Open</B> in browser `http://localhost:9090`

