# SELMA Use Case 0 (UC0) Open Source version

<B>Online demo</B> version of SELMA UC0 is available at: https://selma.ailab.lv

<B>How to use</B> video is available at: https://youtu.be/r4nsumsnR5M

<B>The project</B> page is available at: https://selma-project.eu/

<B>Please use the following text to cite this item:</B> Goško, Didzis and Bārzdiņš, Guntis, 2024, 
  SELMA Open Source Platform (UC0), CLARIN-LV digital library at IMCS, University of Latvia, 
  http://hdl.handle.net/20.500.12574/97.

<B>Source Code</B> of all components necessary to re-build the percompiled UC0 Release below is available from separate repository https://github.com/SELMA-project/UC0-Build

## Install your own private copy of UC0 (precompiled)

<B>Download All Parts</B> of the split archive to the same directory from the Release https://github.com/SELMA-project/UC0-OpenSource/releases/tag/v1.0.0.0.

<B>Reassemble and decompress the Archive</B> using the `cat` and `tar` command:

```
cat `ls -1 UC0run.tgz.part-* | sort` | tar xvz
```

<B>Run</B> the UC0 server by executing one of:

`./uc0-darwin` on Apple MacOS (arm M1, M2, M3 or Intel x86 CPU) 

or

`./uc0-linux-x86_64` on Linux


<B>Open</B> in browser `http://localhost:9090`

## Examles of Videos voiced with SELMA UC0 

Deep Learning Course videos at: https://github.com/guntisx/DeepLearningCourse

