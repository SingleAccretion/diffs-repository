## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 25255
Total bytes of diff: 25161
Total bytes of delta: -94 (-0.37% of base)
Total relative delta: -0.08
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 9008.dasm (0.63% of base)
           9 : 6455.dasm (0.79% of base)

Top file improvements (bytes):
         -46 : 22988.dasm (-0.58% of base)
         -28 : 10821.dasm (-3.16% of base)
         -16 : 22244.dasm (-2.59% of base)
         -15 : 21412.dasm (-2.08% of base)
          -6 : 9006.dasm (-0.40% of base)
          -2 : 18942.dasm (-0.18% of base)

8 total files with Code Size differences (6 improved, 2 regressed), 10 unchanged.

Top method regressions (bytes):
          10 ( 0.63% of base) : 9008.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])
           9 ( 0.79% of base) : 6455.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this

Top method improvements (bytes):
         -46 (-0.58% of base) : 22988.dasm - Benchstone.BenchF.LLoops:Main1(int):this
         -28 (-3.16% of base) : 10821.dasm - Jil.Serialize.Methods:_CustomWriteIntUnrolledSigned(System.IO.TextWriter,int,System.Char[])
         -16 (-2.59% of base) : 22244.dasm - Benchstone.BenchF.FFT:FastFourierT(System.Double[],System.Double[],int)
         -15 (-2.08% of base) : 21412.dasm - SciMark2.SOR:execute(double,System.Double[][],int)
          -6 (-0.40% of base) : 9006.dasm - Benchstone.BenchF.MatInv4:MinV1(System.Single[],byref,byref,System.Single[],System.Single[])
          -2 (-0.18% of base) : 18942.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String

Top method regressions (percentages):
           9 ( 0.79% of base) : 6455.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
          10 ( 0.63% of base) : 9008.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])

Top method improvements (percentages):
         -28 (-3.16% of base) : 10821.dasm - Jil.Serialize.Methods:_CustomWriteIntUnrolledSigned(System.IO.TextWriter,int,System.Char[])
         -16 (-2.59% of base) : 22244.dasm - Benchstone.BenchF.FFT:FastFourierT(System.Double[],System.Double[],int)
         -15 (-2.08% of base) : 21412.dasm - SciMark2.SOR:execute(double,System.Double[][],int)
         -46 (-0.58% of base) : 22988.dasm - Benchstone.BenchF.LLoops:Main1(int):this
          -6 (-0.40% of base) : 9006.dasm - Benchstone.BenchF.MatInv4:MinV1(System.Single[],byref,byref,System.Single[],System.Single[])
          -2 (-0.18% of base) : 18942.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String

8 total methods with Code Size differences (6 improved, 2 regressed), 10 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 138545
Total bytes of diff: 132308
Total bytes of delta: -6237 (-4.50% of base)
Total relative delta: -10.23
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 221492.dasm (0.63% of base)
           5 : 215397.dasm (1.22% of base)

Top file improvements (bytes):
         -76 : 100387.dasm (-13.87% of base)
         -76 : 100709.dasm (-13.74% of base)
         -76 : 100800.dasm (-14.02% of base)
         -76 : 92985.dasm (-10.90% of base)
         -76 : 93075.dasm (-11.05% of base)
         -76 : 93076.dasm (-11.03% of base)
         -76 : 99053.dasm (-13.69% of base)
         -76 : 99054.dasm (-14.02% of base)
         -76 : 99143.dasm (-14.10% of base)
         -76 : 99144.dasm (-13.87% of base)
         -76 : 100296.dasm (-14.02% of base)
         -76 : 93398.dasm (-10.89% of base)
         -76 : 93399.dasm (-10.90% of base)
         -76 : 96639.dasm (-11.14% of base)
         -76 : 92158.dasm (-10.89% of base)
         -76 : 92159.dasm (-10.90% of base)
         -76 : 95488.dasm (-11.31% of base)
         -76 : 95489.dasm (-11.29% of base)
         -76 : 97144.dasm (-11.31% of base)
         -76 : 97145.dasm (-11.29% of base)

152 total files with Code Size differences (150 improved, 2 regressed), 255 unchanged.

Top method regressions (bytes):
          10 ( 0.63% of base) : 221492.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])
           5 ( 1.22% of base) : 215397.dasm - DefaultNamespace.DoubLinkBig:.ctor(int):this

Top method improvements (bytes):
         -76 (-13.87% of base) : 100387.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.74% of base) : 100709.dasm - testout1:Sub_Funclet_263():int
         -76 (-14.02% of base) : 100800.dasm - testout1:Sub_Funclet_186():int
         -76 (-10.90% of base) : 92985.dasm - testout1:Sub_Funclet_264():double
         -76 (-11.05% of base) : 93075.dasm - testout1:Sub_Funclet_186():double
         -76 (-11.03% of base) : 93076.dasm - testout1:Sub_Funclet_187():double
         -76 (-13.69% of base) : 99053.dasm - testout1:Sub_Funclet_263():int
         -76 (-14.02% of base) : 99054.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.10% of base) : 99143.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.87% of base) : 99144.dasm - testout1:Sub_Funclet_187():int
         -76 (-14.02% of base) : 100296.dasm - testout1:Sub_Funclet_264():int
         -76 (-10.89% of base) : 93398.dasm - testout1:Sub_Funclet_263():double
         -76 (-10.90% of base) : 93399.dasm - testout1:Sub_Funclet_264():double
         -76 (-11.14% of base) : 96639.dasm - testout1:Sub_Funclet_263():float
         -76 (-10.89% of base) : 92158.dasm - testout1:Sub_Funclet_263():double
         -76 (-10.90% of base) : 92159.dasm - testout1:Sub_Funclet_264():double
         -76 (-11.31% of base) : 95488.dasm - testout1:Sub_Funclet_186():float
         -76 (-11.29% of base) : 95489.dasm - testout1:Sub_Funclet_187():float
         -76 (-11.31% of base) : 97144.dasm - testout1:Sub_Funclet_186():float
         -76 (-11.29% of base) : 97145.dasm - testout1:Sub_Funclet_187():float

Top method regressions (percentages):
           5 ( 1.22% of base) : 215397.dasm - DefaultNamespace.DoubLinkBig:.ctor(int):this
          10 ( 0.63% of base) : 221492.dasm - Benchstone.BenchF.MatInv4:MinV2(System.Single[],byref,byref,System.Single[],System.Single[])

Top method improvements (percentages):
         -76 (-14.10% of base) : 99143.dasm - testout1:Sub_Funclet_186():int
         -76 (-14.10% of base) : 100386.dasm - testout1:Sub_Funclet_186():int
         -76 (-14.02% of base) : 100800.dasm - testout1:Sub_Funclet_186():int
         -76 (-14.02% of base) : 99054.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.02% of base) : 100296.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.02% of base) : 99559.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.97% of base) : 99470.dasm - testout1:Sub_Funclet_264():int
         -76 (-13.97% of base) : 100710.dasm - testout1:Sub_Funclet_264():int
         -76 (-13.87% of base) : 100387.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.87% of base) : 99144.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.87% of base) : 99560.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.87% of base) : 100801.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.74% of base) : 100709.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.74% of base) : 99469.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.69% of base) : 99053.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.69% of base) : 100295.dasm - testout1:Sub_Funclet_263():int
         -64 (-13.09% of base) : 89751.dasm - testout1:Sub_Funclet_263():int
         -64 (-13.09% of base) : 89341.dasm - testout1:Sub_Funclet_263():int
         -44 (-12.15% of base) : 99468.dasm - testout1:Sub_Funclet_262():int
         -44 (-12.09% of base) : 99052.dasm - testout1:Sub_Funclet_262():int

152 total methods with Code Size differences (150 improved, 2 regressed), 255 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 68560
Total bytes of diff: 68308
Total bytes of delta: -252 (-0.37% of base)
Total relative delta: -0.12
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 208041.dasm (8.00% of base)
           8 : 208099.dasm (7.55% of base)
           7 : 37858.dasm (1.35% of base)
           7 : 37859.dasm (1.35% of base)
           4 : 123895.dasm (1.26% of base)
           2 : 208095.dasm (3.51% of base)

Top file improvements (bytes):
         -34 : 165231.dasm (-0.81% of base)
         -34 : 168210.dasm (-0.81% of base)
         -30 : 165232.dasm (-0.62% of base)
         -30 : 168190.dasm (-0.62% of base)
         -18 : 165236.dasm (-0.27% of base)
         -18 : 168175.dasm (-0.28% of base)
         -15 : 174556.dasm (-1.66% of base)
         -14 : 43344.dasm (-8.05% of base)
         -13 : 31209.dasm (-3.13% of base)
         -12 : 175318.dasm (-2.45% of base)
         -10 : 185317.dasm (-0.38% of base)
          -8 : 174339.dasm (-2.04% of base)
          -7 : 197097.dasm (-3.87% of base)
          -7 : 126590.dasm (-2.71% of base)
          -6 : 124019.dasm (-0.22% of base)
          -6 : 126075.dasm (-1.43% of base)
          -6 : 165235.dasm (-2.99% of base)
          -6 : 174696.dasm (-0.52% of base)
          -6 : 123884.dasm (-1.43% of base)
          -2 : 168194.dasm (-0.18% of base)

31 total files with Code Size differences (25 improved, 6 regressed), 37 unchanged.

Top method regressions (bytes):
           8 ( 8.00% of base) : 208041.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           8 ( 7.55% of base) : 208099.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           7 ( 1.35% of base) : 37858.dasm - System.Xml.Ucs4Decoder3412:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
           7 ( 1.35% of base) : 37859.dasm - System.Xml.Ucs4Decoder2143:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
           4 ( 1.26% of base) : 123895.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:ProcessBuffer(System.Byte[],int,int,System.Text.Encoding):System.ArraySegment`1[System.Byte]
           2 ( 3.51% of base) : 208095.dasm - System.Diagnostics.EventLogEntry:ShortFrom(System.Byte[],int):short:this

Top method improvements (bytes):
         -34 (-0.81% of base) : 165231.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -34 (-0.81% of base) : 168210.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -30 (-0.62% of base) : 165232.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -30 (-0.62% of base) : 168190.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -18 (-0.27% of base) : 165236.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
         -18 (-0.28% of base) : 168175.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
         -15 (-1.66% of base) : 174556.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[System.Char],byref,byref):System.String
         -14 (-8.05% of base) : 43344.dasm - System.Speech.Internal.Synthesis.AudioFormatConverter:ConvertLinear2LinearShortByte(System.Int16[],int):System.Byte[]
         -13 (-3.13% of base) : 31209.dasm - BigInteger:DivRem(System.Xml.Xsl.XPathConvert+BigInteger):int:this
         -12 (-2.45% of base) : 175318.dasm - System.Net.HttpWebResponse:get_CharacterSet():System.String:this
         -10 (-0.38% of base) : 185317.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
          -8 (-2.04% of base) : 174339.dasm - Internal.IL.Stubs.ILCodeStream:PatchLabels():this
          -7 (-3.87% of base) : 197097.dasm - System.Text.RegularExpressions.CaptureCollection:ForceInitialized():this
          -7 (-2.71% of base) : 126590.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this
          -6 (-0.22% of base) : 124019.dasm - System.Runtime.Serialization.Json.XmlJsonReader:Read():bool:this
          -6 (-1.43% of base) : 126075.dasm - System.Xml.EncodingStreamWrapper:CleanupCharBreak():this
          -6 (-2.99% of base) : 165235.dasm - System.Data.RBTree`1:UpdateNodeKey(System.__Canon,System.__Canon):this
          -6 (-0.52% of base) : 174696.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[System.Byte],bool,bool):this
          -6 (-1.43% of base) : 123884.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:CleanupCharBreak():this
          -2 (-0.18% of base) : 168194.dasm - System.Data.RBTree`1:RightRotate(int,int,int):int:this

Top method regressions (percentages):
           8 ( 8.00% of base) : 208041.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           8 ( 7.55% of base) : 208099.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           2 ( 3.51% of base) : 208095.dasm - System.Diagnostics.EventLogEntry:ShortFrom(System.Byte[],int):short:this
           7 ( 1.35% of base) : 37858.dasm - System.Xml.Ucs4Decoder3412:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
           7 ( 1.35% of base) : 37859.dasm - System.Xml.Ucs4Decoder2143:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
           4 ( 1.26% of base) : 123895.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:ProcessBuffer(System.Byte[],int,int,System.Text.Encoding):System.ArraySegment`1[System.Byte]

Top method improvements (percentages):
         -14 (-8.05% of base) : 43344.dasm - System.Speech.Internal.Synthesis.AudioFormatConverter:ConvertLinear2LinearShortByte(System.Int16[],int):System.Byte[]
          -7 (-3.87% of base) : 197097.dasm - System.Text.RegularExpressions.CaptureCollection:ForceInitialized():this
         -13 (-3.13% of base) : 31209.dasm - BigInteger:DivRem(System.Xml.Xsl.XPathConvert+BigInteger):int:this
          -6 (-2.99% of base) : 165235.dasm - System.Data.RBTree`1:UpdateNodeKey(System.__Canon,System.__Canon):this
          -7 (-2.71% of base) : 126590.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this
         -12 (-2.45% of base) : 175318.dasm - System.Net.HttpWebResponse:get_CharacterSet():System.String:this
          -8 (-2.04% of base) : 174339.dasm - Internal.IL.Stubs.ILCodeStream:PatchLabels():this
         -15 (-1.66% of base) : 174556.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[System.Char],byref,byref):System.String
          -6 (-1.43% of base) : 126075.dasm - System.Xml.EncodingStreamWrapper:CleanupCharBreak():this
          -6 (-1.43% of base) : 123884.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:CleanupCharBreak():this
         -34 (-0.81% of base) : 165231.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -34 (-0.81% of base) : 168210.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -30 (-0.62% of base) : 168190.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -30 (-0.62% of base) : 165232.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
          -6 (-0.52% of base) : 174696.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[System.Byte],bool,bool):this
         -10 (-0.38% of base) : 185317.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -18 (-0.28% of base) : 168175.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
         -18 (-0.27% of base) : 165236.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
          -6 (-0.22% of base) : 124019.dasm - System.Runtime.Serialization.Json.XmlJsonReader:Read():bool:this
          -1 (-0.19% of base) : 165220.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this

31 total methods with Code Size differences (25 improved, 6 regressed), 37 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 98210
Total bytes of diff: 97836
Total bytes of delta: -374 (-0.38% of base)
Total relative delta: -0.75
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          11 : 186980.dasm (3.31% of base)
           8 : 186987.dasm (7.62% of base)
           8 : 187030.dasm (8.08% of base)
           5 : 213351.dasm (0.42% of base)
           4 : 132554.dasm (1.34% of base)
           2 : 186991.dasm (3.57% of base)
           2 : 129653.dasm (0.27% of base)

Top file improvements (bytes):
         -34 : 114060.dasm (-0.82% of base)
         -34 : 113999.dasm (-0.82% of base)
         -18 : 114059.dasm (-0.30% of base)
         -17 : 113998.dasm (-0.28% of base)
         -16 : 162287.dasm (-8.79% of base)
         -14 : 136263.dasm (-3.06% of base)
         -14 : 136264.dasm (-3.06% of base)
         -13 : 142811.dasm (-3.16% of base)
         -12 : 114055.dasm (-0.18% of base)
         -12 : 216804.dasm (-0.37% of base)
         -12 : 113994.dasm (-0.18% of base)
         -12 : 114231.dasm (-0.87% of base)
         -12 : 215752.dasm (-0.37% of base)
         -10 : 228870.dasm (-0.38% of base)
         -10 : 9589.dasm (-4.83% of base)
          -9 : 113446.dasm (-3.27% of base)
          -8 : 153268.dasm (-4.49% of base)
          -8 : 206596.dasm (-0.69% of base)
          -7 : 222455.dasm (-3.78% of base)
          -6 : 115794.dasm (-3.03% of base)

53 total files with Code Size differences (46 improved, 7 regressed), 61 unchanged.

Top method regressions (bytes):
          11 ( 3.31% of base) : 186980.dasm - System.Diagnostics.EventLogEntry:get_ReplacementStrings():System.String[]:this
           8 ( 7.62% of base) : 186987.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           8 ( 8.08% of base) : 187030.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           5 ( 0.42% of base) : 213351.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
           4 ( 1.34% of base) : 132554.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:ProcessBuffer(System.Byte[],int,int,System.Text.Encoding):System.ArraySegment`1[Byte]
           2 ( 3.57% of base) : 186991.dasm - System.Diagnostics.EventLogEntry:ShortFrom(System.Byte[],int):short:this
           2 ( 0.27% of base) : 129653.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this

Top method improvements (bytes):
         -34 (-0.82% of base) : 114060.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this
         -34 (-0.82% of base) : 113999.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
         -18 (-0.30% of base) : 114059.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteX(int,int,int):int:this
         -17 (-0.28% of base) : 113998.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -16 (-8.79% of base) : 162287.dasm - Internal.TypeSystem.GCPointerMap:get_NumSeries():int:this
         -14 (-3.06% of base) : 136263.dasm - System.Xml.Ucs4Decoder2143:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
         -14 (-3.06% of base) : 136264.dasm - System.Xml.Ucs4Decoder3412:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
         -13 (-3.16% of base) : 142811.dasm - BigInteger:DivRem(BigInteger):int:this
         -12 (-0.18% of base) : 114055.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBInsert(int,int,int,int,bool):int:this
         -12 (-0.37% of base) : 216804.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -12 (-0.18% of base) : 113994.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBInsert(int,int,int,int,bool):int:this
         -12 (-0.87% of base) : 114231.dasm - System.Data.Index:RecordStateChanged(int,int,int,int,int,int):this
         -12 (-0.37% of base) : 215752.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -10 (-0.38% of base) : 228870.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -10 (-4.83% of base) : 9589.dasm - ScanBack@904[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Invoke(Microsoft.FSharp.Core.Unit):System.Collections.Generic.IEnumerable`1[Byte]:this
          -9 (-3.27% of base) : 113446.dasm - System.Data.DataTable:ConvertToRowState(System.Collections.BitArray,int):int:this
          -8 (-4.49% of base) : 153268.dasm - System.Speech.Internal.Synthesis.AudioFormatConverter:ConvertLinear2LinearShortByte(System.Int16[],int):System.Byte[]
          -8 (-0.69% of base) : 206596.dasm - System.Net.Security.NegotiateStreamPal:Encrypt(System.Net.Security.SafeDeleteContext,System.ReadOnlySpan`1[Byte],bool,bool,byref,int):int
          -7 (-3.78% of base) : 222455.dasm - System.Text.RegularExpressions.CaptureCollection:ForceInitialized():this
          -6 (-3.03% of base) : 115794.dasm - System.Data.Common.BooleanStorage:Copy(int,int):this

Top method regressions (percentages):
           8 ( 8.08% of base) : 187030.dasm - System.Diagnostics.EventLogInternal:IntFrom(System.Byte[],int):int
           8 ( 7.62% of base) : 186987.dasm - System.Diagnostics.EventLogEntry:IntFrom(System.Byte[],int):int:this
           2 ( 3.57% of base) : 186991.dasm - System.Diagnostics.EventLogEntry:ShortFrom(System.Byte[],int):short:this
          11 ( 3.31% of base) : 186980.dasm - System.Diagnostics.EventLogEntry:get_ReplacementStrings():System.String[]:this
           4 ( 1.34% of base) : 132554.dasm - System.Runtime.Serialization.Json.JsonEncodingStreamWrapper:ProcessBuffer(System.Byte[],int,int,System.Text.Encoding):System.ArraySegment`1[Byte]
           5 ( 0.42% of base) : 213351.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
           2 ( 0.27% of base) : 129653.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this

Top method improvements (percentages):
         -16 (-8.79% of base) : 162287.dasm - Internal.TypeSystem.GCPointerMap:get_NumSeries():int:this
         -10 (-4.83% of base) : 9589.dasm - ScanBack@904[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Invoke(Microsoft.FSharp.Core.Unit):System.Collections.Generic.IEnumerable`1[Byte]:this
          -8 (-4.49% of base) : 153268.dasm - System.Speech.Internal.Synthesis.AudioFormatConverter:ConvertLinear2LinearShortByte(System.Int16[],int):System.Byte[]
          -7 (-3.78% of base) : 222455.dasm - System.Text.RegularExpressions.CaptureCollection:ForceInitialized():this
          -9 (-3.27% of base) : 113446.dasm - System.Data.DataTable:ConvertToRowState(System.Collections.BitArray,int):int:this
          -6 (-3.19% of base) : 116750.dasm - System.Data.Common.SqlUdtStorage:Copy(int,int):this
          -6 (-3.17% of base) : 114056.dasm - System.Data.RBTree`1[Byte][System.Byte]:UpdateNodeKey(ubyte,ubyte):this
         -13 (-3.16% of base) : 142811.dasm - BigInteger:DivRem(BigInteger):int:this
          -6 (-3.11% of base) : 116615.dasm - System.Data.Common.Int32Storage:Copy(int,int):this
          -6 (-3.11% of base) : 116813.dasm - System.Data.Common.UInt32Storage:Copy(int,int):this
         -14 (-3.06% of base) : 136263.dasm - System.Xml.Ucs4Decoder2143:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
         -14 (-3.06% of base) : 136264.dasm - System.Xml.Ucs4Decoder3412:GetFullChars(System.Byte[],int,int,System.Char[],int):int:this
          -6 (-3.03% of base) : 115794.dasm - System.Data.Common.BooleanStorage:Copy(int,int):this
          -6 (-3.03% of base) : 116700.dasm - System.Data.Common.SByteStorage:Copy(int,int):this
          -6 (-3.03% of base) : 115808.dasm - System.Data.Common.ByteStorage:Copy(int,int):this
          -6 (-3.02% of base) : 115822.dasm - System.Data.Common.CharStorage:Copy(int,int):this
          -6 (-3.02% of base) : 116601.dasm - System.Data.Common.Int16Storage:Copy(int,int):this
          -6 (-3.02% of base) : 116799.dasm - System.Data.Common.UInt16Storage:Copy(int,int):this
          -6 (-2.94% of base) : 116587.dasm - System.Data.Common.DoubleStorage:Copy(int,int):this
          -6 (-2.94% of base) : 116716.dasm - System.Data.Common.SingleStorage:Copy(int,int):this

53 total methods with Code Size differences (46 improved, 7 regressed), 61 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 215482
Total bytes of diff: 215472
Total bytes of delta: -10 (-0.00% of base)
Total relative delta: -0.03
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 175572.dasm (0.20% of base)
           2 : 128880.dasm (0.54% of base)

Top file improvements (bytes):
          -6 : 19519.dasm (-1.55% of base)
          -6 : 19520.dasm (-1.55% of base)
          -2 : 128881.dasm (-0.54% of base)

5 total files with Code Size differences (3 improved, 2 regressed), 33 unchanged.

Top method regressions (bytes):
           2 ( 0.20% of base) : 175572.dasm - System.SpanTests.ReadOnlySpanTests:TestMatchMany_Char()
           2 ( 0.54% of base) : 128880.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Add(long):bool:this

Top method improvements (bytes):
          -6 (-1.55% of base) : 19519.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[__Canon][System.__Canon]:VerifyFindLastDuplicates(System.Collections.Generic.LinkedList`1[__Canon],System.__Canon[]):this
          -6 (-1.55% of base) : 19520.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[__Canon][System.__Canon]:VerifyFindDuplicates(System.Collections.Generic.LinkedList`1[__Canon],System.__Canon[]):this
          -2 (-0.54% of base) : 128881.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Remove(long):bool:this

Top method regressions (percentages):
           2 ( 0.54% of base) : 128880.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Add(long):bool:this
           2 ( 0.20% of base) : 175572.dasm - System.SpanTests.ReadOnlySpanTests:TestMatchMany_Char()

Top method improvements (percentages):
          -6 (-1.55% of base) : 19519.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[__Canon][System.__Canon]:VerifyFindLastDuplicates(System.Collections.Generic.LinkedList`1[__Canon],System.__Canon[]):this
          -6 (-1.55% of base) : 19520.dasm - System.Collections.Tests.LinkedList_Generic_Tests`1[__Canon][System.__Canon]:VerifyFindDuplicates(System.Collections.Generic.LinkedList`1[__Canon],System.__Canon[]):this
          -2 (-0.54% of base) : 128881.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Remove(long):bool:this

5 total methods with Code Size differences (3 improved, 2 regressed), 33 unchanged.

```

</details>

--------------------------------------------------------------------------------

