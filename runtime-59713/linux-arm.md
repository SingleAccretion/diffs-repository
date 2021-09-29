## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 22458
Total bytes of diff: 17346
Total bytes of delta: -5112 (-22.76% of base)
Total relative delta: -6.76
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         214 : 86090.dasm (43.15% of base)
         182 : 86957.dasm (69.47% of base)
          12 : 84744.dasm (75.00% of base)
          12 : 84868.dasm (23.08% of base)
          12 : 84307.dasm (6.74% of base)
          12 : 87710.dasm (16.67% of base)
          12 : 84401.dasm (75.00% of base)
          10 : 84867.dasm (55.56% of base)
          10 : 84454.dasm (2.59% of base)
          10 : 84745.dasm (18.52% of base)
          10 : 85636.dasm (50.00% of base)
          10 : 85547.dasm (2.73% of base)
          10 : 86651.dasm (18.52% of base)
          10 : 84202.dasm (2.65% of base)
          10 : 85791.dasm (18.52% of base)
           8 : 81594.dasm (5.71% of base)
           8 : 81596.dasm (5.26% of base)
           6 : 87293.dasm (6.67% of base)
           6 : 87606.dasm (1.79% of base)

Top file improvements (bytes):
        -906 : 84602.dasm (-48.09% of base)
        -688 : 234122.dasm (-41.95% of base)
        -502 : 84049.dasm (-60.05% of base)
        -400 : 84023.dasm (-72.46% of base)
        -376 : 234593.dasm (-29.94% of base)
        -344 : 83782.dasm (-72.57% of base)
        -318 : 83716.dasm (-18.36% of base)
        -304 : 84715.dasm (-51.53% of base)
        -258 : 87043.dasm (-66.49% of base)
        -252 : 86906.dasm (-60.58% of base)
        -168 : 84925.dasm (-77.06% of base)
        -154 : 85031.dasm (-47.83% of base)
        -146 : 84606.dasm (-47.71% of base)
        -132 : 86081.dasm (-82.50% of base)
        -126 : 85605.dasm (-21.43% of base)
         -94 : 86138.dasm (-12.74% of base)
         -82 : 84452.dasm (-57.75% of base)
         -78 : 84865.dasm (-68.42% of base)
         -66 : 85218.dasm (-36.67% of base)
         -64 : 85217.dasm (-33.33% of base)

53 total files with Code Size differences (34 improved, 19 regressed), 0 unchanged.

Top method regressions (bytes):
         214 (43.15% of base) : 86090.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
         182 (69.47% of base) : 86957.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
          12 (75.00% of base) : 84744.dasm - ILGEN_0x32b4c023:Method_0xbc5d3052(short,int):int
          12 (23.08% of base) : 84868.dasm - ILGEN_0x6d8b44b0:Main():int
          12 ( 6.74% of base) : 84307.dasm - ILGEN_0xe71156b4:Method_0x5b58faef(long,float,ushort,byte):int
          12 (16.67% of base) : 87710.dasm - ILGEN_0x4cf11307:Method_0x3417140a():int
          12 (75.00% of base) : 84401.dasm - ILGEN_0x1915effd:Method_0x85e39eed():int
          10 (55.56% of base) : 84867.dasm - ILGEN_0x6d8b44b0:Method_0xcc3db83d(int,byte,int,ubyte):int
          10 ( 2.59% of base) : 84454.dasm - ILGEN_0x42acd912:Method_0xc7da8033(int):int
          10 (18.52% of base) : 84745.dasm - ILGEN_0x32b4c023:Main():int
          10 (50.00% of base) : 85636.dasm - ILGEN_0x5fc83106:Method_0x959f4c04(ubyte,int,ushort,double,byte,long):int
          10 ( 2.73% of base) : 85547.dasm - ILGEN_0x8259d717:Method_0xea14afe6():ushort
          10 (18.52% of base) : 86651.dasm - ILGEN_0x12b94a25:Main():int
          10 ( 2.65% of base) : 84202.dasm - ILGEN_0x1be1aaf4:Method_0xeae47998(short,short,ubyte,short,short,long,short):int
          10 (18.52% of base) : 85791.dasm - ILGEN_0xf0dc526d:Main():int
           8 ( 5.71% of base) : 81594.dasm - add_ovf:u4():int
           8 ( 5.26% of base) : 81596.dasm - add_ovf:u8():int
           6 ( 6.67% of base) : 87293.dasm - Class_test:Main():int
           6 ( 1.79% of base) : 87606.dasm - ILGEN_0x443f4d38:main():int

Top method improvements (bytes):
        -906 (-48.09% of base) : 84602.dasm - ILGEN_0x38e69edd:main():int
        -688 (-41.95% of base) : 234122.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,int,int,ushort,int,int):double
        -502 (-60.05% of base) : 84049.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
        -400 (-72.46% of base) : 84023.dasm - ILGEN_0x2be45b24:Method_0xa3cb4747(float,long,float,double,double,long,float,byte):int
        -376 (-29.94% of base) : 234593.dasm - ILGEN_0x1d013582:Method_0x7ef63454():long
        -344 (-72.57% of base) : 83782.dasm - ILGEN_0x152f1077:Method_0x2763af56(long):int
        -318 (-18.36% of base) : 83716.dasm - ILGEN_0x1125a118:Method_0xa592ccf9(long,int,ushort,byte,int):int
        -304 (-51.53% of base) : 84715.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
        -258 (-66.49% of base) : 87043.dasm - ILGEN_CLASS:ILGEN_METHOD(long,short,int):long
        -252 (-60.58% of base) : 86906.dasm - DevDiv_590771:ILGEN_METHOD(long,ushort,int,int,ushort,int):byte
        -168 (-77.06% of base) : 84925.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
        -154 (-47.83% of base) : 85031.dasm - ILGEN_0x862954f4:main():int
        -146 (-47.71% of base) : 84606.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long
        -132 (-82.50% of base) : 86081.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
        -126 (-21.43% of base) : 85605.dasm - ILGEN_0x1ad7535f:Method_0x2ddbcfb4(short):int
         -94 (-12.74% of base) : 86138.dasm - ILGEN_0x65088b5c:Method_0x5ad2583a(long,ushort,int,ubyte,byte,short,ubyte):long
         -82 (-57.75% of base) : 84452.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
         -78 (-68.42% of base) : 84865.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
         -66 (-36.67% of base) : 85218.dasm - ILGEN_0x64f58bd0:Main():int
         -64 (-33.33% of base) : 85217.dasm - ILGEN_0x64f58bd0:Method_0x1bb0(int,long,float,int,int):int

Top method regressions (percentages):
          12 (75.00% of base) : 84744.dasm - ILGEN_0x32b4c023:Method_0xbc5d3052(short,int):int
          12 (75.00% of base) : 84401.dasm - ILGEN_0x1915effd:Method_0x85e39eed():int
         182 (69.47% of base) : 86957.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
          10 (55.56% of base) : 84867.dasm - ILGEN_0x6d8b44b0:Method_0xcc3db83d(int,byte,int,ubyte):int
          10 (50.00% of base) : 85636.dasm - ILGEN_0x5fc83106:Method_0x959f4c04(ubyte,int,ushort,double,byte,long):int
         214 (43.15% of base) : 86090.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
          12 (23.08% of base) : 84868.dasm - ILGEN_0x6d8b44b0:Main():int
          10 (18.52% of base) : 84745.dasm - ILGEN_0x32b4c023:Main():int
          10 (18.52% of base) : 86651.dasm - ILGEN_0x12b94a25:Main():int
          10 (18.52% of base) : 85791.dasm - ILGEN_0xf0dc526d:Main():int
          12 (16.67% of base) : 87710.dasm - ILGEN_0x4cf11307:Method_0x3417140a():int
          12 ( 6.74% of base) : 84307.dasm - ILGEN_0xe71156b4:Method_0x5b58faef(long,float,ushort,byte):int
           6 ( 6.67% of base) : 87293.dasm - Class_test:Main():int
           8 ( 5.71% of base) : 81594.dasm - add_ovf:u4():int
           8 ( 5.26% of base) : 81596.dasm - add_ovf:u8():int
          10 ( 2.73% of base) : 85547.dasm - ILGEN_0x8259d717:Method_0xea14afe6():ushort
          10 ( 2.65% of base) : 84202.dasm - ILGEN_0x1be1aaf4:Method_0xeae47998(short,short,ubyte,short,short,long,short):int
          10 ( 2.59% of base) : 84454.dasm - ILGEN_0x42acd912:Method_0xc7da8033(int):int
           6 ( 1.79% of base) : 87606.dasm - ILGEN_0x443f4d38:main():int

Top method improvements (percentages):
        -132 (-82.50% of base) : 86081.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
        -168 (-77.06% of base) : 84925.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
        -344 (-72.57% of base) : 83782.dasm - ILGEN_0x152f1077:Method_0x2763af56(long):int
        -400 (-72.46% of base) : 84023.dasm - ILGEN_0x2be45b24:Method_0xa3cb4747(float,long,float,double,double,long,float,byte):int
         -78 (-68.42% of base) : 84865.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
        -258 (-66.49% of base) : 87043.dasm - ILGEN_CLASS:ILGEN_METHOD(long,short,int):long
        -252 (-60.58% of base) : 86906.dasm - DevDiv_590771:ILGEN_METHOD(long,ushort,int,int,ushort,int):byte
        -502 (-60.05% of base) : 84049.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
         -82 (-57.75% of base) : 84452.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
        -304 (-51.53% of base) : 84715.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
         -40 (-51.28% of base) : 85952.dasm - FullProof:Test():int
        -906 (-48.09% of base) : 84602.dasm - ILGEN_0x38e69edd:main():int
        -154 (-47.83% of base) : 85031.dasm - ILGEN_0x862954f4:main():int
        -146 (-47.71% of base) : 84606.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long
        -688 (-41.95% of base) : 234122.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,int,int,ushort,int,int):double
         -66 (-36.67% of base) : 85218.dasm - ILGEN_0x64f58bd0:Main():int
         -64 (-33.33% of base) : 85217.dasm - ILGEN_0x64f58bd0:Method_0x1bb0(int,long,float,int,int):int
        -376 (-29.94% of base) : 234593.dasm - ILGEN_0x1d013582:Method_0x7ef63454():long
         -36 (-27.69% of base) : 84453.dasm - ILGEN_0x6322da7:Main():int
        -126 (-21.43% of base) : 85605.dasm - ILGEN_0x1ad7535f:Method_0x2ddbcfb4(short):int

53 total methods with Code Size differences (34 improved, 19 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

