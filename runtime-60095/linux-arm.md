## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 869052
Total bytes of diff: 867850
Total bytes of delta: -1202 (-0.14% of base)
Total relative delta: -0.30
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 185481.dasm (0.01% of base)
          16 : 166543.dasm (0.01% of base)

Top file improvements (bytes):
        -840 : 99187.dasm (-10.51% of base)
        -296 : 99188.dasm (-12.38% of base)
         -74 : 99123.dasm (-5.45% of base)
         -24 : 203803.dasm (-1.29% of base)

6 total files with Code Size differences (4 improved, 2 regressed), 6 unchanged.

Top method regressions (bytes):
          16 ( 0.01% of base) : 185481.dasm - overlddiv:Main():int
          16 ( 0.01% of base) : 166543.dasm - overldrem:Main():int

Top method improvements (bytes):
        -840 (-10.51% of base) : 99187.dasm - testout1:Func_0_2_3_1_5():System.Decimal
        -296 (-12.38% of base) : 99188.dasm - testout1:Func_0_2_3_1_4():System.Decimal
         -74 (-5.45% of base) : 99123.dasm - testout1:Func_0_2_1_5_5():double
         -24 (-1.29% of base) : 203803.dasm - HVATests`1[Byte][System.Byte]:doTests():this

Top method regressions (percentages):
          16 ( 0.01% of base) : 185481.dasm - overlddiv:Main():int
          16 ( 0.01% of base) : 166543.dasm - overldrem:Main():int

Top method improvements (percentages):
        -296 (-12.38% of base) : 99188.dasm - testout1:Func_0_2_3_1_4():System.Decimal
        -840 (-10.51% of base) : 99187.dasm - testout1:Func_0_2_3_1_5():System.Decimal
         -74 (-5.45% of base) : 99123.dasm - testout1:Func_0_2_1_5_5():double
         -24 (-1.29% of base) : 203803.dasm - HVATests`1[Byte][System.Byte]:doTests():this

6 total methods with Code Size differences (4 improved, 2 regressed), 6 unchanged.

```

</details>

--------------------------------------------------------------------------------

