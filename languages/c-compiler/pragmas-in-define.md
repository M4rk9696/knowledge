# Using pragma inside define

[Back](./c-compiler.md){: .button}

```c
/*
  This doesn't work
*/
#ifdef OPENACC
#pragma acc kernels
#endif

/* 
  This works
 */
#ifdef OPENMP
_Pragma("omp parallel for")
#endif
for (int i = 0; i < N; i++) {

}
```
