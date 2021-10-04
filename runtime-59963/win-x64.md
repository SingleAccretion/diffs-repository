## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 397
Total bytes of diff: 420
Total bytes of delta: 23 (5.79% of base)
Total relative delta: 0.06
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          23 : 5388.dasm (5.79% of base)

1 total files with Code Size differences (0 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          23 ( 5.79% of base) : 5388.dasm - <>c:<GenerateId>b__3_0(Span`1,long):this

Top method regressions (percentages):
          23 ( 5.79% of base) : 5388.dasm - <>c:<GenerateId>b__3_0(Span`1,long):this

1 total methods with Code Size differences (0 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 31695
Total bytes of diff: 31679
Total bytes of delta: -16 (-0.05% of base)
Total relative delta: 0.05
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          19 : 9265.dasm (1.40% of base)
           6 : 23671.dasm (6.98% of base)

Top file improvements (bytes):
         -18 : 6544.dasm (-1.42% of base)
         -13 : 9263.dasm (-0.99% of base)
          -7 : 11208.dasm (-0.69% of base)
          -2 : 20707.dasm (-0.14% of base)
          -1 : 25917.dasm (-0.32% of base)

7 total files with Code Size differences (5 improved, 2 regressed), 19 unchanged.

Top method regressions (bytes):
          19 ( 1.40% of base) : 9265.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])
           6 ( 6.98% of base) : 23671.dasm - MessagePack.Decoders.Str16String:Read(System.Byte[],int,byref):System.String:this

Top method improvements (bytes):
         -18 (-1.42% of base) : 6544.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
         -13 (-0.99% of base) : 9263.dasm - Benchstone.BenchF.MatInv4:MinV1(System.Single[],byref,byref,System.Single[],System.Single[])
          -7 (-0.69% of base) : 11208.dasm - Jil.Serialize.Methods:_CustomWriteIntUnrolledSigned(System.IO.TextWriter,int,System.Char[])
          -2 (-0.14% of base) : 20707.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
          -1 (-0.32% of base) : 25917.dasm - DecCalc:SearchScale(byref,int):int

Top method regressions (percentages):
           6 ( 6.98% of base) : 23671.dasm - MessagePack.Decoders.Str16String:Read(System.Byte[],int,byref):System.String:this
          19 ( 1.40% of base) : 9265.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])

Top method improvements (percentages):
         -18 (-1.42% of base) : 6544.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
         -13 (-0.99% of base) : 9263.dasm - Benchstone.BenchF.MatInv4:MinV1(System.Single[],byref,byref,System.Single[],System.Single[])
          -7 (-0.69% of base) : 11208.dasm - Jil.Serialize.Methods:_CustomWriteIntUnrolledSigned(System.IO.TextWriter,int,System.Char[])
          -1 (-0.32% of base) : 25917.dasm - DecCalc:SearchScale(byref,int):int
          -2 (-0.14% of base) : 20707.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String

7 total methods with Code Size differences (5 improved, 2 regressed), 19 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 154074
Total bytes of diff: 147873
Total bytes of delta: -6201 (-4.02% of base)
Total relative delta: -10.10
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          19 : 221864.dasm (1.40% of base)
           4 : 231668.dasm (4.26% of base)
           3 : 220066.dasm (0.57% of base)

Top file improvements (bytes):
         -76 : 100414.dasm (-12.24% of base)
         -76 : 100828.dasm (-12.28% of base)
         -76 : 95517.dasm (-11.00% of base)
         -76 : 95518.dasm (-10.98% of base)
         -76 : 97171.dasm (-11.06% of base)
         -76 : 97172.dasm (-11.05% of base)
         -76 : 100715.dasm (-12.34% of base)
         -76 : 91749.dasm (-10.63% of base)
         -76 : 91750.dasm (-10.64% of base)
         -76 : 93404.dasm (-10.69% of base)
         -76 : 93405.dasm (-10.70% of base)
         -76 : 96646.dasm (-10.86% of base)
         -76 : 96757.dasm (-11.00% of base)
         -76 : 100302.dasm (-12.40% of base)
         -76 : 100827.dasm (-12.77% of base)
         -76 : 95404.dasm (-10.84% of base)
         -76 : 95405.dasm (-10.86% of base)
         -76 : 97059.dasm (-10.90% of base)
         -76 : 97060.dasm (-10.92% of base)
         -76 : 99588.dasm (-12.77% of base)

156 total files with Code Size differences (153 improved, 3 regressed), 239 unchanged.

Top method regressions (bytes):
          19 ( 1.40% of base) : 221864.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])
           4 ( 4.26% of base) : 231668.dasm - Repro:WriteInt(System.Byte[],int,int)
           3 ( 0.57% of base) : 220066.dasm - double1:ProcessJagged3DArray(System.Double[][])

Top method improvements (bytes):
         -76 (-12.24% of base) : 100414.dasm - testout1:Sub_Funclet_187():int
         -76 (-12.28% of base) : 100828.dasm - testout1:Sub_Funclet_187():int
         -76 (-11.00% of base) : 95517.dasm - testout1:Sub_Funclet_186():float
         -76 (-10.98% of base) : 95518.dasm - testout1:Sub_Funclet_187():float
         -76 (-11.06% of base) : 97171.dasm - testout1:Sub_Funclet_186():float
         -76 (-11.05% of base) : 97172.dasm - testout1:Sub_Funclet_187():float
         -76 (-12.34% of base) : 100715.dasm - testout1:Sub_Funclet_263():int
         -76 (-10.63% of base) : 91749.dasm - testout1:Sub_Funclet_263():double
         -76 (-10.64% of base) : 91750.dasm - testout1:Sub_Funclet_264():double
         -76 (-10.69% of base) : 93404.dasm - testout1:Sub_Funclet_263():double
         -76 (-10.70% of base) : 93405.dasm - testout1:Sub_Funclet_264():double
         -76 (-10.86% of base) : 96646.dasm - testout1:Sub_Funclet_264():float
         -76 (-11.00% of base) : 96757.dasm - testout1:Sub_Funclet_186():float
         -76 (-12.40% of base) : 100302.dasm - testout1:Sub_Funclet_264():int
         -76 (-12.77% of base) : 100827.dasm - testout1:Sub_Funclet_186():int
         -76 (-10.84% of base) : 95404.dasm - testout1:Sub_Funclet_263():float
         -76 (-10.86% of base) : 95405.dasm - testout1:Sub_Funclet_264():float
         -76 (-10.90% of base) : 97059.dasm - testout1:Sub_Funclet_263():float
         -76 (-10.92% of base) : 97060.dasm - testout1:Sub_Funclet_264():float
         -76 (-12.77% of base) : 99588.dasm - testout1:Sub_Funclet_186():int

Top method regressions (percentages):
           4 ( 4.26% of base) : 231668.dasm - Repro:WriteInt(System.Byte[],int,int)
          19 ( 1.40% of base) : 221864.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])
           3 ( 0.57% of base) : 220066.dasm - double1:ProcessJagged3DArray(System.Double[][])

Top method improvements (percentages):
         -16 (-20.51% of base) : 81534.dasm - N.C:Exn():int
         -17 (-14.53% of base) : 195947.dasm - TestHFAandHVA:TestReturnViaThrowing()
         -12 (-13.19% of base) : 81848.dasm - AutoGen.Program:Test()
         -76 (-12.77% of base) : 100827.dasm - testout1:Sub_Funclet_186():int
         -76 (-12.77% of base) : 99588.dasm - testout1:Sub_Funclet_186():int
         -76 (-12.73% of base) : 99172.dasm - testout1:Sub_Funclet_186():int
         -76 (-12.73% of base) : 100413.dasm - testout1:Sub_Funclet_186():int
         -76 (-12.40% of base) : 100302.dasm - testout1:Sub_Funclet_264():int
         -76 (-12.40% of base) : 99060.dasm - testout1:Sub_Funclet_264():int
         -76 (-12.36% of base) : 100716.dasm - testout1:Sub_Funclet_264():int
         -76 (-12.36% of base) : 99476.dasm - testout1:Sub_Funclet_264():int
         -76 (-12.34% of base) : 100715.dasm - testout1:Sub_Funclet_263():int
         -76 (-12.34% of base) : 99475.dasm - testout1:Sub_Funclet_263():int
         -76 (-12.30% of base) : 100301.dasm - testout1:Sub_Funclet_263():int
         -76 (-12.30% of base) : 99059.dasm - testout1:Sub_Funclet_263():int
         -76 (-12.28% of base) : 100828.dasm - testout1:Sub_Funclet_187():int
         -76 (-12.28% of base) : 99589.dasm - testout1:Sub_Funclet_187():int
         -76 (-12.24% of base) : 100414.dasm - testout1:Sub_Funclet_187():int
         -76 (-12.24% of base) : 99173.dasm - testout1:Sub_Funclet_187():int
         -76 (-11.06% of base) : 97171.dasm - testout1:Sub_Funclet_186():float

156 total methods with Code Size differences (153 improved, 3 regressed), 239 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 89305
Total bytes of diff: 89224
Total bytes of delta: -81 (-0.09% of base)
Total relative delta: 0.05
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          22 : 22547.dasm (8.56% of base)
           6 : 10996.dasm (1.00% of base)
           4 : 174074.dasm (3.15% of base)
           4 : 195656.dasm (0.63% of base)
           3 : 175606.dasm (0.71% of base)
           2 : 19547.dasm (0.98% of base)
           1 : 68522.dasm (0.07% of base)
           1 : 174132.dasm (0.79% of base)

Top file improvements (bytes):
         -30 : 22558.dasm (-0.59% of base)
         -21 : 19552.dasm (-0.40% of base)
         -15 : 175542.dasm (-3.50% of base)
         -14 : 19551.dasm (-0.32% of base)
         -13 : 22580.dasm (-0.30% of base)
          -8 : 22562.dasm (-0.74% of base)
          -8 : 22563.dasm (-0.74% of base)
          -4 : 19540.dasm (-0.80% of base)
          -4 : 22566.dasm (-0.81% of base)
          -3 : 174166.dasm (-0.38% of base)
          -2 : 10968.dasm (-1.83% of base)
          -1 : 144683.dasm (-0.34% of base)
          -1 : 19545.dasm (-0.49% of base)

21 total files with Code Size differences (13 improved, 8 regressed), 117 unchanged.

Top method regressions (bytes):
          22 ( 8.56% of base) : 22547.dasm - System.Data.RBTree`1:UpdateNodeKey(int,int):this
           6 ( 1.00% of base) : 10996.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[System.Int32, System.String]):System.String
           4 ( 3.15% of base) : 174074.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           4 ( 0.63% of base) : 195656.dasm - System.Net.HttpWebResponse:get_CharacterSet():System.String:this
           3 ( 0.71% of base) : 175606.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this
           2 ( 0.98% of base) : 19547.dasm - System.Data.RBTree`1:GetNodeByKey(System.__Canon):System.Data.RBTree`1+NodePath[System.__Canon]:this
           1 ( 0.07% of base) : 68522.dasm - System.Xml.XmlSqlBinaryReader:ValueAsString(int):System.String:this
           1 ( 0.79% of base) : 174132.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this

Top method improvements (bytes):
         -30 (-0.59% of base) : 22558.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -21 (-0.40% of base) : 19552.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -15 (-3.50% of base) : 175542.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this
         -14 (-0.32% of base) : 19551.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -13 (-0.30% of base) : 22580.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
          -8 (-0.74% of base) : 22562.dasm - System.Data.RBTree`1:RightRotate(int,int,int):int:this
          -8 (-0.74% of base) : 22563.dasm - System.Data.RBTree`1:LeftRotate(int,int,int):int:this
          -4 (-0.80% of base) : 19540.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -4 (-0.81% of base) : 22566.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -3 (-0.38% of base) : 174166.dasm - System.Diagnostics.EventLog:UnsafeTryFormatMessage(Microsoft.Win32.SafeHandles.SafeLibraryHandle,int,System.String[]):System.String
          -2 (-1.83% of base) : 10968.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -1 (-0.34% of base) : 144683.dasm - DecCalc:SearchScale(byref,int):int
          -1 (-0.49% of base) : 19545.dasm - System.Data.RBTree`1:GetIndexByNode(int):int:this

Top method regressions (percentages):
          22 ( 8.56% of base) : 22547.dasm - System.Data.RBTree`1:UpdateNodeKey(int,int):this
           4 ( 3.15% of base) : 174074.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           6 ( 1.00% of base) : 10996.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[System.Int32, System.String]):System.String
           2 ( 0.98% of base) : 19547.dasm - System.Data.RBTree`1:GetNodeByKey(System.__Canon):System.Data.RBTree`1+NodePath[System.__Canon]:this
           1 ( 0.79% of base) : 174132.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           3 ( 0.71% of base) : 175606.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this
           4 ( 0.63% of base) : 195656.dasm - System.Net.HttpWebResponse:get_CharacterSet():System.String:this
           1 ( 0.07% of base) : 68522.dasm - System.Xml.XmlSqlBinaryReader:ValueAsString(int):System.String:this

Top method improvements (percentages):
         -15 (-3.50% of base) : 175542.dasm - System.Collections.Generic.SegmentedList`1:RemoveRoomForElement(int):this
          -2 (-1.83% of base) : 10968.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -4 (-0.81% of base) : 22566.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -4 (-0.80% of base) : 19540.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -8 (-0.74% of base) : 22562.dasm - System.Data.RBTree`1:RightRotate(int,int,int):int:this
          -8 (-0.74% of base) : 22563.dasm - System.Data.RBTree`1:LeftRotate(int,int,int):int:this
         -30 (-0.59% of base) : 22558.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
          -1 (-0.49% of base) : 19545.dasm - System.Data.RBTree`1:GetIndexByNode(int):int:this
         -21 (-0.40% of base) : 19552.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
          -3 (-0.38% of base) : 174166.dasm - System.Diagnostics.EventLog:UnsafeTryFormatMessage(Microsoft.Win32.SafeHandles.SafeLibraryHandle,int,System.String[]):System.String
          -1 (-0.34% of base) : 144683.dasm - DecCalc:SearchScale(byref,int):int
         -14 (-0.32% of base) : 19551.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -13 (-0.30% of base) : 22580.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this

21 total methods with Code Size differences (13 improved, 8 regressed), 117 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 120732
Total bytes of diff: 120771
Total bytes of delta: 39 (0.03% of base)
Total relative delta: 0.44
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          22 : 112711.dasm (8.63% of base)
          22 : 112697.dasm (8.43% of base)
          21 : 112846.dasm (1.32% of base)
          21 : 112673.dasm (8.08% of base)
          21 : 112752.dasm (8.17% of base)
          18 : 112725.dasm (6.32% of base)
          18 : 112738.dasm (6.50% of base)
           8 : 131234.dasm (1.63% of base)
           8 : 128895.dasm (1.63% of base)
           6 : 153265.dasm (0.89% of base)
           4 : 186912.dasm (3.17% of base)
           3 : 112863.dasm (0.26% of base)
           3 : 160927.dasm (0.72% of base)
           2 : 186864.dasm (0.68% of base)
           2 : 112620.dasm (1.02% of base)
           2 : 186873.dasm (0.59% of base)
           1 : 111674.dasm (0.26% of base)
           1 : 186880.dasm (0.79% of base)

Top file improvements (bytes):
         -32 : 112676.dasm (-0.64% of base)
         -20 : 112615.dasm (-0.39% of base)
         -15 : 160893.dasm (-3.56% of base)
         -14 : 112616.dasm (-0.32% of base)
         -13 : 112677.dasm (-0.30% of base)
          -8 : 112671.dasm (-0.74% of base)
          -8 : 112670.dasm (-0.74% of base)
          -8 : 207212.dasm (-0.59% of base)
          -6 : 214008.dasm (-0.44% of base)
          -4 : 112627.dasm (-0.81% of base)
          -4 : 112688.dasm (-0.81% of base)
          -3 : 186823.dasm (-0.40% of base)
          -3 : 114614.dasm (-2.11% of base)
          -2 : 214020.dasm (-0.13% of base)
          -2 : 153295.dasm (-1.82% of base)
          -1 : 186872.dasm (-0.46% of base)
          -1 : 112622.dasm (-0.52% of base)

35 total files with Code Size differences (17 improved, 18 regressed), 147 unchanged.

Top method regressions (bytes):
          22 ( 8.63% of base) : 112711.dasm - System.Data.RBTree`1[Int32][System.Int32]:UpdateNodeKey(int,int):this
          22 ( 8.43% of base) : 112697.dasm - System.Data.RBTree`1[Int16][System.Int16]:UpdateNodeKey(short,short):this
          21 ( 1.32% of base) : 112846.dasm - System.Data.Index:RecordStateChanged(int,int,int,int,int,int):this
          21 ( 8.08% of base) : 112673.dasm - System.Data.RBTree`1[Byte][System.Byte]:UpdateNodeKey(ubyte,ubyte):this
          21 ( 8.17% of base) : 112752.dasm - System.Data.RBTree`1[Int64][System.Int64]:UpdateNodeKey(long,long):this
          18 ( 6.32% of base) : 112725.dasm - System.Data.RBTree`1[Double][System.Double]:UpdateNodeKey(double,double):this
          18 ( 6.50% of base) : 112738.dasm - System.Data.RBTree`1[Vector`1][System.Numerics.Vector`1[System.Single]]:UpdateNodeKey(System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single]):this
           8 ( 1.63% of base) : 131234.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:CleanupCharBreak():this
           8 ( 1.63% of base) : 128895.dasm - System.Xml.EncodingStreamWrapper:CleanupCharBreak():this
           6 ( 0.89% of base) : 153265.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.String
           4 ( 3.17% of base) : 186912.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           3 ( 0.26% of base) : 112863.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
           3 ( 0.72% of base) : 160927.dasm - System.Collections.Generic.SegmentedList`1[Byte][System.Byte]:RemoveRoomForElement(int):this
           2 ( 0.68% of base) : 186864.dasm - System.Diagnostics.EventLogEntry:get_MachineName():System.String:this
           2 ( 1.02% of base) : 112620.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:GetNodeByKey(System.__Canon):NodePath[__Canon]:this
           2 ( 0.59% of base) : 186873.dasm - System.Diagnostics.EventLogEntry:get_ReplacementStrings():System.String[]:this
           1 ( 0.26% of base) : 111674.dasm - System.Data.DataSet:MarkModifiedRows(System.Data.DataSet+TableChanges[],int):this
           1 ( 0.79% of base) : 186880.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this

Top method improvements (bytes):
         -32 (-0.64% of base) : 112676.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteX(int,int,int):int:this
         -20 (-0.39% of base) : 112615.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -15 (-3.56% of base) : 160893.dasm - System.Collections.Generic.SegmentedList`1[__Canon][System.__Canon]:RemoveRoomForElement(int):this
         -14 (-0.32% of base) : 112616.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
         -13 (-0.30% of base) : 112677.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this
          -8 (-0.74% of base) : 112671.dasm - System.Data.RBTree`1[Byte][System.Byte]:RightRotate(int,int,int):int:this
          -8 (-0.74% of base) : 112670.dasm - System.Data.RBTree`1[Byte][System.Byte]:LeftRotate(int,int,int):int:this
          -8 (-0.59% of base) : 207212.dasm - System.Net.Security.NegotiateStreamPal:Encrypt(System.Net.Security.SafeDeleteContext,System.ReadOnlySpan`1[Byte],bool,bool,byref,int):int
          -6 (-0.44% of base) : 214008.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
          -4 (-0.81% of base) : 112627.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeNodeByIndex(int,byref):int:this
          -4 (-0.81% of base) : 112688.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeNodeByIndex(int,byref):int:this
          -3 (-0.40% of base) : 186823.dasm - System.Diagnostics.EventLog:UnsafeTryFormatMessage(Microsoft.Win32.SafeHandles.SafeLibraryHandle,int,System.String[]):System.String
          -3 (-2.11% of base) : 114614.dasm - System.Data.Common.DataStorage:CopyBits(int,int):this
          -2 (-0.13% of base) : 214020.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
          -2 (-1.82% of base) : 153295.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -1 (-0.46% of base) : 186872.dasm - System.Diagnostics.EventLogEntry:get_Source():System.String:this
          -1 (-0.52% of base) : 112622.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:GetIndexByNode(int):int:this

Top method regressions (percentages):
          22 ( 8.63% of base) : 112711.dasm - System.Data.RBTree`1[Int32][System.Int32]:UpdateNodeKey(int,int):this
          22 ( 8.43% of base) : 112697.dasm - System.Data.RBTree`1[Int16][System.Int16]:UpdateNodeKey(short,short):this
          21 ( 8.17% of base) : 112752.dasm - System.Data.RBTree`1[Int64][System.Int64]:UpdateNodeKey(long,long):this
          21 ( 8.08% of base) : 112673.dasm - System.Data.RBTree`1[Byte][System.Byte]:UpdateNodeKey(ubyte,ubyte):this
          18 ( 6.50% of base) : 112738.dasm - System.Data.RBTree`1[Vector`1][System.Numerics.Vector`1[System.Single]]:UpdateNodeKey(System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single]):this
          18 ( 6.32% of base) : 112725.dasm - System.Data.RBTree`1[Double][System.Double]:UpdateNodeKey(double,double):this
           4 ( 3.17% of base) : 186912.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           8 ( 1.63% of base) : 131234.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:CleanupCharBreak():this
           8 ( 1.63% of base) : 128895.dasm - System.Xml.EncodingStreamWrapper:CleanupCharBreak():this
          21 ( 1.32% of base) : 112846.dasm - System.Data.Index:RecordStateChanged(int,int,int,int,int,int):this
           2 ( 1.02% of base) : 112620.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:GetNodeByKey(System.__Canon):NodePath[__Canon]:this
           6 ( 0.89% of base) : 153265.dasm - System.Text.EncodingTable:GetNameFromCodePage(int,System.String,System.Int32[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.String
           1 ( 0.79% of base) : 186880.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           3 ( 0.72% of base) : 160927.dasm - System.Collections.Generic.SegmentedList`1[Byte][System.Byte]:RemoveRoomForElement(int):this
           2 ( 0.68% of base) : 186864.dasm - System.Diagnostics.EventLogEntry:get_MachineName():System.String:this
           2 ( 0.59% of base) : 186873.dasm - System.Diagnostics.EventLogEntry:get_ReplacementStrings():System.String[]:this
           1 ( 0.26% of base) : 111674.dasm - System.Data.DataSet:MarkModifiedRows(System.Data.DataSet+TableChanges[],int):this
           3 ( 0.26% of base) : 112863.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this

Top method improvements (percentages):
         -15 (-3.56% of base) : 160893.dasm - System.Collections.Generic.SegmentedList`1[__Canon][System.__Canon]:RemoveRoomForElement(int):this
          -3 (-2.11% of base) : 114614.dasm - System.Data.Common.DataStorage:CopyBits(int,int):this
          -2 (-1.82% of base) : 153295.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -4 (-0.81% of base) : 112688.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeNodeByIndex(int,byref):int:this
          -4 (-0.81% of base) : 112627.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeNodeByIndex(int,byref):int:this
          -8 (-0.74% of base) : 112671.dasm - System.Data.RBTree`1[Byte][System.Byte]:RightRotate(int,int,int):int:this
          -8 (-0.74% of base) : 112670.dasm - System.Data.RBTree`1[Byte][System.Byte]:LeftRotate(int,int,int):int:this
         -32 (-0.64% of base) : 112676.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteX(int,int,int):int:this
          -8 (-0.59% of base) : 207212.dasm - System.Net.Security.NegotiateStreamPal:Encrypt(System.Net.Security.SafeDeleteContext,System.ReadOnlySpan`1[Byte],bool,bool,byref,int):int
          -1 (-0.52% of base) : 112622.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:GetIndexByNode(int):int:this
          -1 (-0.46% of base) : 186872.dasm - System.Diagnostics.EventLogEntry:get_Source():System.String:this
          -6 (-0.44% of base) : 214008.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
          -3 (-0.40% of base) : 186823.dasm - System.Diagnostics.EventLog:UnsafeTryFormatMessage(Microsoft.Win32.SafeHandles.SafeLibraryHandle,int,System.String[]):System.String
         -20 (-0.39% of base) : 112615.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -14 (-0.32% of base) : 112616.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
         -13 (-0.30% of base) : 112677.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this
          -2 (-0.13% of base) : 214020.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String

35 total methods with Code Size differences (17 improved, 18 regressed), 147 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 291625
Total bytes of diff: 291514
Total bytes of delta: -111 (-0.04% of base)
Total relative delta: -2.55
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           6 : 129655.dasm (3.02% of base)
           3 : 218811.dasm (1.21% of base)
           3 : 218812.dasm (1.21% of base)
           3 : 223145.dasm (1.21% of base)
           3 : 223146.dasm (1.21% of base)
           2 : 129662.dasm (0.56% of base)
           2 : 176244.dasm (0.35% of base)
           2 : 176252.dasm (0.28% of base)
           2 : 176848.dasm (0.28% of base)
           2 : 129656.dasm (1.03% of base)
           2 : 176840.dasm (0.35% of base)
           2 : 129663.dasm (0.54% of base)
           1 : 215238.dasm (0.91% of base)
           1 : 176302.dasm (0.19% of base)
           1 : 176898.dasm (0.19% of base)

Top file improvements (bytes):
         -24 : 310684.dasm (-85.71% of base)
         -16 : 73072.dasm (-26.23% of base)
         -16 : 193628.dasm (-26.23% of base)
         -16 : 73075.dasm (-23.88% of base)
         -16 : 193631.dasm (-23.88% of base)
         -12 : 73073.dasm (-21.05% of base)
         -12 : 73076.dasm (-19.35% of base)
         -12 : 193629.dasm (-21.05% of base)
         -12 : 193632.dasm (-19.35% of base)
         -10 : 19767.dasm (-0.39% of base)

25 total files with Code Size differences (10 improved, 15 regressed), 31 unchanged.

Top method regressions (bytes):
           6 ( 3.02% of base) : 129655.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Add(long):bool:this
           3 ( 1.21% of base) : 218811.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadChar(byref):bool:this
           3 ( 1.21% of base) : 218812.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadInt16(byref):bool:this
           3 ( 1.21% of base) : 223145.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadChar(byref):bool:this
           3 ( 1.21% of base) : 223146.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadInt16(byref):bool:this
           2 ( 0.56% of base) : 129662.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Add(long):bool:this
           2 ( 0.35% of base) : 176244.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_ThreeByte()
           2 ( 0.28% of base) : 176252.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_ManyByte()
           2 ( 0.28% of base) : 176848.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_ManyByte()
           2 ( 1.03% of base) : 129656.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Remove(long):bool:this
           2 ( 0.35% of base) : 176840.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_ThreeByte()
           2 ( 0.54% of base) : 129663.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Remove(long):bool:this
           1 ( 0.91% of base) : 215238.dasm - XmlCoreTest.Common.UnicodeCharHelper:IsW3C_IsValidXmlSurrogateChar(ushort,ushort):bool
           1 ( 0.19% of base) : 176302.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_TwoByte()
           1 ( 0.19% of base) : 176898.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_TwoByte()

Top method improvements (bytes):
         -24 (-85.71% of base) : 310684.dasm - <>c__DisplayClass159_0`1[Byte][System.Byte]:<TestIndexerOutOfRange>b__0():this
         -16 (-26.23% of base) : 73072.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_1():System.Object:this
         -16 (-26.23% of base) : 193628.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_1():System.Object:this
         -16 (-23.88% of base) : 73075.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_4():System.Object:this
         -16 (-23.88% of base) : 193631.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_4():System.Object:this
         -12 (-21.05% of base) : 73073.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_2():System.Object:this
         -12 (-19.35% of base) : 73076.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_5():System.Object:this
         -12 (-21.05% of base) : 193629.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_2():System.Object:this
         -12 (-19.35% of base) : 193632.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_5():System.Object:this
         -10 (-0.39% of base) : 19767.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[Byte][System.Byte]:AddBefore_LLNode_LLNode():this

Top method regressions (percentages):
           6 ( 3.02% of base) : 129655.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Add(long):bool:this
           3 ( 1.21% of base) : 218811.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadChar(byref):bool:this
           3 ( 1.21% of base) : 218812.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadInt16(byref):bool:this
           3 ( 1.21% of base) : 223145.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadChar(byref):bool:this
           3 ( 1.21% of base) : 223146.dasm - System.Data.SqlClient.TdsParserStateObject:TryReadInt16(byref):bool:this
           2 ( 1.03% of base) : 129656.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Remove(long):bool:this
           1 ( 0.91% of base) : 215238.dasm - XmlCoreTest.Common.UnicodeCharHelper:IsW3C_IsValidXmlSurrogateChar(ushort,ushort):bool
           2 ( 0.56% of base) : 129662.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Add(long):bool:this
           2 ( 0.54% of base) : 129663.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Remove(long):bool:this
           2 ( 0.35% of base) : 176244.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_ThreeByte()
           2 ( 0.35% of base) : 176840.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_ThreeByte()
           2 ( 0.28% of base) : 176252.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_ManyByte()
           2 ( 0.28% of base) : 176848.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_ManyByte()
           1 ( 0.19% of base) : 176302.dasm - System.SpanTests.ReadOnlySpanTests:TestMultipleMatchLastIndexOfAny_String_TwoByte()
           1 ( 0.19% of base) : 176898.dasm - System.SpanTests.SpanTests:TestMultipleMatchLastIndexOfAny_String_TwoByte()

Top method improvements (percentages):
         -24 (-85.71% of base) : 310684.dasm - <>c__DisplayClass159_0`1[Byte][System.Byte]:<TestIndexerOutOfRange>b__0():this
         -16 (-26.23% of base) : 73072.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_1():System.Object:this
         -16 (-26.23% of base) : 193628.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_1():System.Object:this
         -16 (-23.88% of base) : 73075.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_4():System.Object:this
         -16 (-23.88% of base) : 193631.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_4():System.Object:this
         -12 (-21.05% of base) : 73073.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_2():System.Object:this
         -12 (-21.05% of base) : 193629.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_2():System.Object:this
         -12 (-19.35% of base) : 73076.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__14_5():System.Object:this
         -12 (-19.35% of base) : 193632.dasm - <>c:<Item_Get_InvalidIndex_ThrowsIndexOutOfRangeException>b__114_5():System.Object:this
         -10 (-0.39% of base) : 19767.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[Byte][System.Byte]:AddBefore_LLNode_LLNode():this

25 total methods with Code Size differences (10 improved, 15 regressed), 31 unchanged.

```

</details>

--------------------------------------------------------------------------------

