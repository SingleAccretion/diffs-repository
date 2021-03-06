## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 203796
Total bytes of diff: 203796
Total bytes of delta: 0 (0.00% of base)
```
<details>

<summary>Detail diffs</summary>

```


0 total files with Code Size differences (0 improved, 0 regressed), 103 unchanged.

0 total methods with Code Size differences (0 improved, 0 regressed), 103 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 229364
Total bytes of diff: 229424
Total bytes of delta: 60 (0.03% of base)
Total relative delta: 0.05
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          36 : 222256.dasm (3.42% of base)
           8 : 216624.dasm (0.46% of base)
           8 : 227158.dasm (0.46% of base)
           4 : 226785.dasm (0.35% of base)
           4 : 226907.dasm (0.35% of base)
           4 : 79587.dasm (0.35% of base)

Top file improvements (bytes):
          -4 : 215227.dasm (-0.20% of base)

7 total files with Code Size differences (1 improved, 6 regressed), 492 unchanged.

Top method regressions (bytes):
          36 ( 3.42% of base) : 222256.dasm - BB:Method1(byref,byref,byref,AA`6[SByte,Byte,UInt32,UInt32,Int64,Boolean],byref,int):this
           8 ( 0.46% of base) : 216624.dasm - StrAccess1:Main(System.String[]):int
           8 ( 0.46% of base) : 227158.dasm - StrAccess1:Main(System.String[]):int
           4 ( 0.35% of base) : 226785.dasm - GCVariant.DoubLink:.ctor(int,bool):this
           4 ( 0.35% of base) : 226907.dasm - GCVariant.DoubLink:.ctor(int,bool):this
           4 ( 0.35% of base) : 79587.dasm - GCVariant.DoubLink:.ctor(int,bool):this

Top method improvements (bytes):
          -4 (-0.20% of base) : 215227.dasm - Test:Main():int

Top method regressions (percentages):
          36 ( 3.42% of base) : 222256.dasm - BB:Method1(byref,byref,byref,AA`6[SByte,Byte,UInt32,UInt32,Int64,Boolean],byref,int):this
           8 ( 0.46% of base) : 216624.dasm - StrAccess1:Main(System.String[]):int
           8 ( 0.46% of base) : 227158.dasm - StrAccess1:Main(System.String[]):int
           4 ( 0.35% of base) : 226785.dasm - GCVariant.DoubLink:.ctor(int,bool):this
           4 ( 0.35% of base) : 226907.dasm - GCVariant.DoubLink:.ctor(int,bool):this
           4 ( 0.35% of base) : 79587.dasm - GCVariant.DoubLink:.ctor(int,bool):this

Top method improvements (percentages):
          -4 (-0.20% of base) : 215227.dasm - Test:Main():int

7 total methods with Code Size differences (1 improved, 6 regressed), 492 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 390236
Total bytes of diff: 390160
Total bytes of delta: -76 (-0.02% of base)
Total relative delta: -0.04
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 69201.dasm (0.31% of base)
           4 : 111978.dasm (0.50% of base)
           4 : 193918.dasm (0.69% of base)

Top file improvements (bytes):
         -40 : 57138.dasm (-2.13% of base)
         -40 : 63301.dasm (-2.14% of base)
          -8 : 193854.dasm (-1.29% of base)

6 total files with Code Size differences (3 improved, 3 regressed), 424 unchanged.

Top method regressions (bytes):
           4 ( 0.31% of base) : 69201.dasm - Microsoft.Diagnostics.Tracing.Ctf.CtfMetadataLegacyParser:GetPropertyBag(System.String,int,int):Microsoft.Diagnostics.Tracing.Ctf.CtfPropertyBag:this
           4 ( 0.50% of base) : 111978.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[System.Int32, System.String]):System.String
           4 ( 0.69% of base) : 193918.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this

Top method improvements (bytes):
         -40 (-2.13% of base) : 57138.dasm - System.Buffers.Text.Utf8Formatter:TryFormatDateTimeO(System.DateTime,System.TimeSpan,System.Span`1[System.Byte],byref):bool
         -40 (-2.14% of base) : 63301.dasm - System.DateTimeFormat:TryFormatO(System.DateTime,System.TimeSpan,System.Span`1[System.Char],byref):bool
          -8 (-1.29% of base) : 193854.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this

Top method regressions (percentages):
           4 ( 0.69% of base) : 193918.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this
           4 ( 0.50% of base) : 111978.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[System.Int32, System.String]):System.String
           4 ( 0.31% of base) : 69201.dasm - Microsoft.Diagnostics.Tracing.Ctf.CtfMetadataLegacyParser:GetPropertyBag(System.String,int,int):Microsoft.Diagnostics.Tracing.Ctf.CtfPropertyBag:this

Top method improvements (percentages):
         -40 (-2.14% of base) : 63301.dasm - System.DateTimeFormat:TryFormatO(System.DateTime,System.TimeSpan,System.Span`1[System.Char],byref):bool
         -40 (-2.13% of base) : 57138.dasm - System.Buffers.Text.Utf8Formatter:TryFormatDateTimeO(System.DateTime,System.TimeSpan,System.Span`1[System.Byte],byref):bool
          -8 (-1.29% of base) : 193854.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this

6 total methods with Code Size differences (3 improved, 3 regressed), 424 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 633188
Total bytes of diff: 633184
Total bytes of delta: -4 (-0.00% of base)
Total relative delta: 0.00
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 137831.dasm (0.50% of base)
           4 : 147490.dasm (0.77% of base)
           4 : 82407.dasm (0.80% of base)

Top file improvements (bytes):
          -8 : 147456.dasm (-1.52% of base)
          -4 : 108896.dasm (-0.08% of base)
          -4 : 108957.dasm (-0.09% of base)

6 total files with Code Size differences (3 improved, 3 regressed), 779 unchanged.

Top method regressions (bytes):
           4 ( 0.50% of base) : 137831.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.String
           4 ( 0.77% of base) : 147490.dasm - System.Collections.Generic.SegmentedList`1[Byte][System.Byte]:RemoveRoomForElement(int):this
           4 ( 0.80% of base) : 82407.dasm - Microsoft.Diagnostics.Utilities.DirectoryUtilities:DeleteOldest(System.String,int):bool

Top method improvements (bytes):
          -8 (-1.52% of base) : 147456.dasm - System.Collections.Generic.SegmentedList`1[__Canon][System.__Canon]:RemoveRoomForElement(int):this
          -4 (-0.08% of base) : 108896.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
          -4 (-0.09% of base) : 108957.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this

Top method regressions (percentages):
           4 ( 0.80% of base) : 82407.dasm - Microsoft.Diagnostics.Utilities.DirectoryUtilities:DeleteOldest(System.String,int):bool
           4 ( 0.77% of base) : 147490.dasm - System.Collections.Generic.SegmentedList`1[Byte][System.Byte]:RemoveRoomForElement(int):this
           4 ( 0.50% of base) : 137831.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.String

Top method improvements (percentages):
          -8 (-1.52% of base) : 147456.dasm - System.Collections.Generic.SegmentedList`1[__Canon][System.__Canon]:RemoveRoomForElement(int):this
          -4 (-0.09% of base) : 108957.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this
          -4 (-0.08% of base) : 108896.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this

6 total methods with Code Size differences (3 improved, 3 regressed), 779 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1386956
Total bytes of diff: 1386948
Total bytes of delta: -8 (-0.00% of base)
Total relative delta: -0.00
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 19552.dasm (-0.30% of base)

1 total files with Code Size differences (1 improved, 0 regressed), 851 unchanged.

Top method improvements (bytes):
          -8 (-0.30% of base) : 19552.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[Byte][System.Byte]:AddBefore_LLNode_LLNode():this

Top method improvements (percentages):
          -8 (-0.30% of base) : 19552.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[Byte][System.Byte]:AddBefore_LLNode_LLNode():this

1 total methods with Code Size differences (1 improved, 0 regressed), 851 unchanged.

```

</details>

--------------------------------------------------------------------------------

