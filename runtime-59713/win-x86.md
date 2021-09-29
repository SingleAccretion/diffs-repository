## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 17201
Total bytes of diff: 13395
Total bytes of delta: -3806 (-22.13% of base)
Total relative delta: -7.38
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         244 : 86340.dasm (70.72% of base)
         170 : 86783.dasm (71.73% of base)
          26 : 84751.dasm (2.58% of base)
           6 : 86137.dasm (2.64% of base)
           6 : 86524.dasm (12.77% of base)
           6 : 86565.dasm (75.00% of base)
           6 : 86283.dasm (75.00% of base)
           5 : 86399.dasm (45.45% of base)
           5 : 86539.dasm (2.00% of base)
           5 : 84715.dasm (1.99% of base)
           5 : 84782.dasm (2.04% of base)
           5 : 86160.dasm (13.89% of base)
           5 : 86343.dasm (11.11% of base)
           5 : 86486.dasm (13.89% of base)
           5 : 86566.dasm (13.89% of base)
           4 : 86491.dasm (10.81% of base)
           4 : 81059.dasm (4.21% of base)
           2 : 86490.dasm (16.67% of base)
           1 : 81061.dasm (0.82% of base)

Top file improvements (bytes):
        -641 : 232961.dasm (-43.87% of base)
        -508 : 84732.dasm (-67.37% of base)
        -484 : 84765.dasm (-28.22% of base)
        -349 : 232482.dasm (-33.24% of base)
        -329 : 84725.dasm (-76.51% of base)
        -296 : 86290.dasm (-76.49% of base)
        -289 : 86423.dasm (-53.52% of base)
        -250 : 86807.dasm (-58.55% of base)
        -153 : 86301.dasm (-83.15% of base)
        -129 : 86124.dasm (-53.53% of base)
        -119 : 84778.dasm (-22.12% of base)
        -116 : 86246.dasm (-89.23% of base)
        -102 : 86416.dasm (-23.34% of base)
         -82 : 86579.dasm (-43.16% of base)
         -81 : 86313.dasm (-66.39% of base)
         -61 : 86555.dasm (-41.22% of base)
         -58 : 86806.dasm (-24.89% of base)
         -54 : 86518.dasm (-70.13% of base)
         -41 : 84744.dasm (-5.86% of base)
         -34 : 86314.dasm (-34.00% of base)

52 total files with Code Size differences (33 improved, 19 regressed), 1 unchanged.

Top method regressions (bytes):
         244 (70.72% of base) : 86340.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
         170 (71.73% of base) : 86783.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
          26 ( 2.58% of base) : 84751.dasm - ILGEN_0x3c109d11:Method_0x52483fac(short,double,ubyte,byte,double):int
           6 ( 2.64% of base) : 86137.dasm - ILGEN_0x443f4d38:main():int
           6 (12.77% of base) : 86524.dasm - ILGEN_0x4cf11307:Method_0x3417140a():int
           6 (75.00% of base) : 86565.dasm - ILGEN_0x32b4c023:Method_0xbc5d3052(short,int):int
           6 (75.00% of base) : 86283.dasm - ILGEN_0x1915effd:Method_0x85e39eed():int
           5 (45.45% of base) : 86399.dasm - ILGEN_0x5fc83106:Method_0x959f4c04(ubyte,int,ushort,double,byte,long):int
           5 ( 2.00% of base) : 86539.dasm - ILGEN_0x42acd912:Method_0xc7da8033(int):int
           5 ( 1.99% of base) : 84715.dasm - ILGEN_0x1be1aaf4:Method_0xeae47998(short,short,ubyte,short,short,long,short):int
           5 ( 2.04% of base) : 84782.dasm - ILGEN_0x8259d717:Method_0xea14afe6():ushort
           5 (13.89% of base) : 86160.dasm - ILGEN_0xf0dc526d:Main():int
           5 (11.11% of base) : 86343.dasm - ILGEN_0x64f58bd0:Main():int
           5 (13.89% of base) : 86486.dasm - ILGEN_0x12b94a25:Main():int
           5 (13.89% of base) : 86566.dasm - ILGEN_0x32b4c023:Main():int
           4 (10.81% of base) : 86491.dasm - ILGEN_0x6d8b44b0:Main():int
           4 ( 4.21% of base) : 81059.dasm - add_ovf:u4():int
           2 (16.67% of base) : 86490.dasm - ILGEN_0x6d8b44b0:Method_0xcc3db83d(int,byte,int,ubyte):int
           1 ( 0.82% of base) : 81061.dasm - add_ovf:u8():int

Top method improvements (bytes):
        -641 (-43.87% of base) : 232961.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,int,int,ushort,int,int):double
        -508 (-67.37% of base) : 84732.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
        -484 (-28.22% of base) : 84765.dasm - ILGEN_0x1125a118:Method_0xa592ccf9(long,int,ushort,byte,int):int
        -349 (-33.24% of base) : 232482.dasm - ILGEN_0x1d013582:Method_0x7ef63454():long
        -329 (-76.51% of base) : 84725.dasm - ILGEN_0x2be45b24:Method_0xa3cb4747(float,long,float,double,double,long,float,byte):int
        -296 (-76.49% of base) : 86290.dasm - ILGEN_0x152f1077:Method_0x2763af56(long):int
        -289 (-53.52% of base) : 86423.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
        -250 (-58.55% of base) : 86807.dasm - DevDiv_590771:ILGEN_METHOD(long,ushort,int,int,ushort,int):byte
        -153 (-83.15% of base) : 86301.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
        -129 (-53.53% of base) : 86124.dasm - ILGEN_0x862954f4:main():int
        -119 (-22.12% of base) : 84778.dasm - ILGEN_0x65088b5c:Method_0x5ad2583a(long,ushort,int,ubyte,byte,short,ubyte):long
        -116 (-89.23% of base) : 86246.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
        -102 (-23.34% of base) : 86416.dasm - ILGEN_0x1ad7535f:Method_0x2ddbcfb4(short):int
         -82 (-43.16% of base) : 86579.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long
         -81 (-66.39% of base) : 86313.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
         -61 (-41.22% of base) : 86555.dasm - ILGEN_0x4a792db4:Method_0x2a166130(long,ushort,ubyte,double,ubyte,int,long):int
         -58 (-24.89% of base) : 86806.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,int,ushort,ubyte,short,int):short
         -54 (-70.13% of base) : 86518.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
         -41 (-5.86% of base) : 84744.dasm - ILGEN_0xa691ee4d:Method_0xf329b3e5(long):int
         -34 (-34.00% of base) : 86314.dasm - ILGEN_0x6322da7:Main():int

Top method regressions (percentages):
           6 (75.00% of base) : 86565.dasm - ILGEN_0x32b4c023:Method_0xbc5d3052(short,int):int
           6 (75.00% of base) : 86283.dasm - ILGEN_0x1915effd:Method_0x85e39eed():int
         170 (71.73% of base) : 86783.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
         244 (70.72% of base) : 86340.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
           5 (45.45% of base) : 86399.dasm - ILGEN_0x5fc83106:Method_0x959f4c04(ubyte,int,ushort,double,byte,long):int
           2 (16.67% of base) : 86490.dasm - ILGEN_0x6d8b44b0:Method_0xcc3db83d(int,byte,int,ubyte):int
           5 (13.89% of base) : 86160.dasm - ILGEN_0xf0dc526d:Main():int
           5 (13.89% of base) : 86486.dasm - ILGEN_0x12b94a25:Main():int
           5 (13.89% of base) : 86566.dasm - ILGEN_0x32b4c023:Main():int
           6 (12.77% of base) : 86524.dasm - ILGEN_0x4cf11307:Method_0x3417140a():int
           5 (11.11% of base) : 86343.dasm - ILGEN_0x64f58bd0:Main():int
           4 (10.81% of base) : 86491.dasm - ILGEN_0x6d8b44b0:Main():int
           4 ( 4.21% of base) : 81059.dasm - add_ovf:u4():int
           6 ( 2.64% of base) : 86137.dasm - ILGEN_0x443f4d38:main():int
          26 ( 2.58% of base) : 84751.dasm - ILGEN_0x3c109d11:Method_0x52483fac(short,double,ubyte,byte,double):int
           5 ( 2.04% of base) : 84782.dasm - ILGEN_0x8259d717:Method_0xea14afe6():ushort
           5 ( 2.00% of base) : 86539.dasm - ILGEN_0x42acd912:Method_0xc7da8033(int):int
           5 ( 1.99% of base) : 84715.dasm - ILGEN_0x1be1aaf4:Method_0xeae47998(short,short,ubyte,short,short,long,short):int
           1 ( 0.82% of base) : 81061.dasm - add_ovf:u8():int

Top method improvements (percentages):
        -116 (-89.23% of base) : 86246.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
        -153 (-83.15% of base) : 86301.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
        -329 (-76.51% of base) : 84725.dasm - ILGEN_0x2be45b24:Method_0xa3cb4747(float,long,float,double,double,long,float,byte):int
        -296 (-76.49% of base) : 86290.dasm - ILGEN_0x152f1077:Method_0x2763af56(long):int
         -54 (-70.13% of base) : 86518.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
        -508 (-67.37% of base) : 84732.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
         -81 (-66.39% of base) : 86313.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
        -250 (-58.55% of base) : 86807.dasm - DevDiv_590771:ILGEN_METHOD(long,ushort,int,int,ushort,int):byte
         -31 (-55.36% of base) : 84882.dasm - FullProof:Test():int
        -129 (-53.53% of base) : 86124.dasm - ILGEN_0x862954f4:main():int
        -289 (-53.52% of base) : 86423.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
         -33 (-47.83% of base) : 86525.dasm - ILGEN_0x8d1cfa06:Main():int
        -641 (-43.87% of base) : 232961.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,int,int,ushort,int,int):double
         -82 (-43.16% of base) : 86579.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long
         -61 (-41.22% of base) : 86555.dasm - ILGEN_0x4a792db4:Method_0x2a166130(long,ushort,ubyte,double,ubyte,int,long):int
         -34 (-34.00% of base) : 86314.dasm - ILGEN_0x6322da7:Main():int
        -349 (-33.24% of base) : 232482.dasm - ILGEN_0x1d013582:Method_0x7ef63454():long
        -484 (-28.22% of base) : 84765.dasm - ILGEN_0x1125a118:Method_0xa592ccf9(long,int,ushort,byte,int):int
         -58 (-24.89% of base) : 86806.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,int,ushort,ubyte,short,int):short
        -102 (-23.34% of base) : 86416.dasm - ILGEN_0x1ad7535f:Method_0x2ddbcfb4(short):int

52 total methods with Code Size differences (33 improved, 19 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

