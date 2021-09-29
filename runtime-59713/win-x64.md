## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7308
Total bytes of diff: 5473
Total bytes of delta: -1835 (-25.11% of base)
Total relative delta: 0.65
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         151 : 86799.dasm (109.42% of base)
          86 : 86878.dasm (477.78% of base)
          27 : 86354.dasm (7.32% of base)
           7 : 86593.dasm (3.32% of base)
           6 : 86777.dasm (50.00% of base)
           5 : 86346.dasm (27.78% of base)

Top file improvements (bytes):
        -697 : 233381.dasm (-46.10% of base)
        -435 : 84743.dasm (-61.61% of base)
        -221 : 84757.dasm (-42.02% of base)
        -182 : 86437.dasm (-49.86% of base)
        -115 : 86315.dasm (-75.16% of base)
         -83 : 86255.dasm (-62.41% of base)
         -69 : 86532.dasm (-68.32% of base)
         -64 : 84755.dasm (-8.64% of base)
         -62 : 86822.dasm (-30.69% of base)
         -56 : 86327.dasm (-51.85% of base)
         -45 : 86569.dasm (-31.03% of base)
         -36 : 84893.dasm (-52.17% of base)
         -28 : 86328.dasm (-20.74% of base)
         -12 : 84762.dasm (-1.53% of base)
          -5 : 86591.dasm (-2.15% of base)
          -3 : 86487.dasm (-1.99% of base)
          -2 : 86425.dasm (-1.92% of base)
          -2 : 86248.dasm (-2.06% of base)

24 total files with Code Size differences (18 improved, 6 regressed), 2 unchanged.

Top method regressions (bytes):
         151 (109.42% of base) : 86799.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
          86 (477.78% of base) : 86878.dasm - GitHub_18291:ILGEN_METHOD(long,byte,long):ushort
          27 ( 7.32% of base) : 86354.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
           7 ( 3.32% of base) : 86593.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long
           6 (50.00% of base) : 86777.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
           5 (27.78% of base) : 86346.dasm - ILGEN_0x498e48f6:Method_0x1eae(long):int

Top method improvements (bytes):
        -697 (-46.10% of base) : 233381.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,long,long,ushort,long,int):double
        -435 (-61.61% of base) : 84743.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
        -221 (-42.02% of base) : 84757.dasm - ILGEN_0x13e5362e:Method_0x6ddf86e(ushort,float,int,ubyte,int,int,ubyte,long,long):int
        -182 (-49.86% of base) : 86437.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
        -115 (-75.16% of base) : 86315.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
         -83 (-62.41% of base) : 86255.dasm - ILGEN_0x44f8f663:Method_0x2e75f3b4(byte,long,short):int
         -69 (-68.32% of base) : 86532.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
         -64 (-8.64% of base) : 84755.dasm - ILGEN_0xa691ee4d:Method_0xf329b3e5(long):int
         -62 (-30.69% of base) : 86822.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,long,ushort,ubyte,short,int):short
         -56 (-51.85% of base) : 86327.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
         -45 (-31.03% of base) : 86569.dasm - ILGEN_0x4a792db4:Method_0x2a166130(long,ushort,ubyte,double,ubyte,int,long):int
         -36 (-52.17% of base) : 84893.dasm - FullProof:Test():int
         -28 (-20.74% of base) : 86328.dasm - ILGEN_0x6322da7:Main():int
         -12 (-1.53% of base) : 84762.dasm - ILGEN_0x3c109d11:Method_0x52483fac(short,double,ubyte,byte,double):int
          -5 (-2.15% of base) : 86591.dasm - ILGEN_0xb45a7d8a:Method_0xd47d5ddc():int
          -3 (-1.99% of base) : 86487.dasm - ILGEN_0xe71156b4:Method_0x5b58faef(long,float,ushort,byte):int
          -2 (-1.92% of base) : 86425.dasm - ILGEN_0xab09d49:Main():int
          -2 (-2.06% of base) : 86248.dasm - ILGEN_0xcb543741:Main():int

Top method regressions (percentages):
          86 (477.78% of base) : 86878.dasm - GitHub_18291:ILGEN_METHOD(long,byte,long):ushort
         151 (109.42% of base) : 86799.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
           6 (50.00% of base) : 86777.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
           5 (27.78% of base) : 86346.dasm - ILGEN_0x498e48f6:Method_0x1eae(long):int
          27 ( 7.32% of base) : 86354.dasm - ILGEN_0x59749830:Method_0x386e(double,ushort):int
           7 ( 3.32% of base) : 86593.dasm - ILGEN_0xf9a34ac1:Method_0x2d60f019(byte,int):long

Top method improvements (percentages):
        -115 (-75.16% of base) : 86315.dasm - ILGEN_0x11c02e62:Method_0x7f2e741b(ubyte,ubyte,float,float,int):int
         -69 (-68.32% of base) : 86532.dasm - ILGEN_0x6af2431f:Method_0x4ce0d6c6():ushort
         -83 (-62.41% of base) : 86255.dasm - ILGEN_0x44f8f663:Method_0x2e75f3b4(byte,long,short):int
        -435 (-61.61% of base) : 84743.dasm - ILGEN_0xc2d6ebd8:Method_0x6228(ushort,short,int,long,short,long,int):int
         -36 (-52.17% of base) : 84893.dasm - FullProof:Test():int
         -56 (-51.85% of base) : 86327.dasm - ILGEN_0x6322da7:Method_0xc5c40454(short,byte,short,ushort,double,float,int,double):int
        -182 (-49.86% of base) : 86437.dasm - ILGEN_0x14dd78f4:Method_0xb96ba46d(long,short):int
        -697 (-46.10% of base) : 233381.dasm - ILGEN_0xdea951c0:Method_0x5a7bd7a1(long,short,byte,ubyte,long,long,ushort,long,int):double
        -221 (-42.02% of base) : 84757.dasm - ILGEN_0x13e5362e:Method_0x6ddf86e(ushort,float,int,ubyte,int,int,ubyte,long,long):int
         -45 (-31.03% of base) : 86569.dasm - ILGEN_0x4a792db4:Method_0x2a166130(long,ushort,ubyte,double,ubyte,int,long):int
         -62 (-30.69% of base) : 86822.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,long,ushort,ubyte,short,int):short
         -28 (-20.74% of base) : 86328.dasm - ILGEN_0x6322da7:Main():int
         -64 (-8.64% of base) : 84755.dasm - ILGEN_0xa691ee4d:Method_0xf329b3e5(long):int
          -5 (-2.15% of base) : 86591.dasm - ILGEN_0xb45a7d8a:Method_0xd47d5ddc():int
          -2 (-2.06% of base) : 86248.dasm - ILGEN_0xcb543741:Main():int
          -3 (-1.99% of base) : 86487.dasm - ILGEN_0xe71156b4:Method_0x5b58faef(long,float,ushort,byte):int
          -2 (-1.92% of base) : 86425.dasm - ILGEN_0xab09d49:Main():int
         -12 (-1.53% of base) : 84762.dasm - ILGEN_0x3c109d11:Method_0x52483fac(short,double,ubyte,byte,double):int

24 total methods with Code Size differences (18 improved, 6 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51
Total bytes of diff: 61
Total bytes of delta: 10 (19.61% of base)
Total relative delta: 0.20
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 72205.dasm (19.61% of base)

1 total files with Code Size differences (0 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          10 (19.61% of base) : 72205.dasm - TestClass:get_PropertyTypedAsRefToRefStruct():byref

Top method regressions (percentages):
          10 (19.61% of base) : 72205.dasm - TestClass:get_PropertyTypedAsRefToRefStruct():byref

1 total methods with Code Size differences (0 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

