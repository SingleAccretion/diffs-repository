## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4932392
Total bytes of diff: 4926172
Total bytes of delta: -6220 (-0.13% of base)
Total relative delta: -5.72
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          24 : 205888.dasm (11.54% of base)
          22 : 204535.dasm (8.21% of base)
          20 : 205889.dasm (9.52% of base)
          20 : 207352.dasm (1.46% of base)
          16 : 205890.dasm (7.48% of base)
          12 : 204537.dasm (4.44% of base)
          12 : 204540.dasm (7.69% of base)
          12 : 204542.dasm (7.69% of base)
          12 : 205876.dasm (7.69% of base)
          12 : 205878.dasm (7.59% of base)
          12 : 211943.dasm (7.69% of base)
          12 : 216085.dasm (7.50% of base)
          12 : 216491.dasm (7.69% of base)
          10 : 204536.dasm (3.70% of base)
          10 : 204538.dasm (3.70% of base)
          10 : 204541.dasm (6.33% of base)
          10 : 210719.dasm (6.25% of base)
          10 : 205877.dasm (6.33% of base)
          10 : 205879.dasm (6.33% of base)
          10 : 205884.dasm (4.17% of base)

Top file improvements (bytes):
         -76 : 129756.dasm (-7.50% of base)
         -76 : 129757.dasm (-7.68% of base)
         -76 : 129843.dasm (-7.58% of base)
         -76 : 129844.dasm (-7.97% of base)
         -76 : 102016.dasm (-7.65% of base)
         -76 : 102106.dasm (-7.55% of base)
         -76 : 102107.dasm (-7.93% of base)
         -76 : 107826.dasm (-7.47% of base)
         -76 : 107827.dasm (-7.65% of base)
         -76 : 107913.dasm (-7.55% of base)
         -76 : 107914.dasm (-7.93% of base)
         -76 : 162427.dasm (-9.29% of base)
         -76 : 162428.dasm (-9.48% of base)
         -76 : 162514.dasm (-9.34% of base)
         -76 : 162515.dasm (-9.62% of base)
         -76 : 164811.dasm (-13.57% of base)
         -76 : 164812.dasm (-14.13% of base)
         -76 : 164898.dasm (-13.52% of base)
         -76 : 164899.dasm (-13.43% of base)
         -76 : 90680.dasm (-7.50% of base)

582 total files with Code Size differences (403 improved, 179 regressed), 12176 unchanged.

Top method regressions (bytes):
          24 (11.54% of base) : 205888.dasm - <>c:<Main>b__2_15(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
          22 ( 8.21% of base) : 204535.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          20 ( 9.52% of base) : 205889.dasm - <>c:<Main>b__2_16(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
          20 ( 1.46% of base) : 207352.dasm - JIT.HardwareIntrinsics.X86.SimpleBinaryOpTest__CompareGreaterThanInt64:ValidateResult(System.Int64[],System.Int64[],System.Int64[],System.String):this
          16 ( 7.48% of base) : 205890.dasm - <>c:<Main>b__2_17(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
          12 ( 4.44% of base) : 204537.dasm - <>c:<Main>b__2_2(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 204540.dasm - <>c:<Main>b__2_6(System.Double[],System.Double[],System.Double[]):bool:this
          12 ( 7.69% of base) : 204542.dasm - <>c:<Main>b__2_8(System.Double[],System.Double[],System.Double[]):bool:this
          12 ( 7.69% of base) : 205876.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.59% of base) : 205878.dasm - <>c:<Main>b__2_2(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 211943.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.50% of base) : 216085.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 216491.dasm - <>c:<Main>b__2_3(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 3.70% of base) : 204536.dasm - <>c:<Main>b__2_1(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 3.70% of base) : 204538.dasm - <>c:<Main>b__2_3(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 6.33% of base) : 204541.dasm - <>c:<Main>b__2_7(System.Double[],System.Double[],System.Double[]):bool:this
          10 ( 6.25% of base) : 210719.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 6.33% of base) : 205877.dasm - <>c:<Main>b__2_1(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 6.33% of base) : 205879.dasm - <>c:<Main>b__2_3(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 4.17% of base) : 205884.dasm - <>c:<Main>b__2_10(System.Int16[],System.Int16[],System.Int16[]):bool:this

Top method improvements (bytes):
         -76 (-7.50% of base) : 129756.dasm - testout1:Sub_Funclet_263():double
         -76 (-7.68% of base) : 129757.dasm - testout1:Sub_Funclet_264():double
         -76 (-7.58% of base) : 129843.dasm - testout1:Sub_Funclet_186():double
         -76 (-7.97% of base) : 129844.dasm - testout1:Sub_Funclet_187():double
         -76 (-7.65% of base) : 102016.dasm - testout1:Sub_Funclet_264():double
         -76 (-7.55% of base) : 102106.dasm - testout1:Sub_Funclet_186():double
         -76 (-7.93% of base) : 102107.dasm - testout1:Sub_Funclet_187():double
         -76 (-7.47% of base) : 107826.dasm - testout1:Sub_Funclet_263():double
         -76 (-7.65% of base) : 107827.dasm - testout1:Sub_Funclet_264():double
         -76 (-7.55% of base) : 107913.dasm - testout1:Sub_Funclet_186():double
         -76 (-7.93% of base) : 107914.dasm - testout1:Sub_Funclet_187():double
         -76 (-9.29% of base) : 162427.dasm - testout1:Sub_Funclet_263():float
         -76 (-9.48% of base) : 162428.dasm - testout1:Sub_Funclet_264():float
         -76 (-9.34% of base) : 162514.dasm - testout1:Sub_Funclet_186():float
         -76 (-9.62% of base) : 162515.dasm - testout1:Sub_Funclet_187():float
         -76 (-13.57% of base) : 164811.dasm - testout1:Sub_Funclet_263():int
         -76 (-14.13% of base) : 164812.dasm - testout1:Sub_Funclet_264():int
         -76 (-13.52% of base) : 164898.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.43% of base) : 164899.dasm - testout1:Sub_Funclet_187():int
         -76 (-7.50% of base) : 90680.dasm - testout1:Sub_Funclet_263():double

Top method regressions (percentages):
          24 (11.54% of base) : 205888.dasm - <>c:<Main>b__2_15(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
          20 ( 9.52% of base) : 205889.dasm - <>c:<Main>b__2_16(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
          22 ( 8.21% of base) : 204535.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 204540.dasm - <>c:<Main>b__2_6(System.Double[],System.Double[],System.Double[]):bool:this
          12 ( 7.69% of base) : 204542.dasm - <>c:<Main>b__2_8(System.Double[],System.Double[],System.Double[]):bool:this
          12 ( 7.69% of base) : 205876.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 211943.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.69% of base) : 216491.dasm - <>c:<Main>b__2_3(System.Single[],System.Single[],System.Single[]):bool:this
          12 ( 7.59% of base) : 205878.dasm - <>c:<Main>b__2_2(System.Single[],System.Single[],System.Single[]):bool:this
           6 ( 7.50% of base) : 231824.dasm - Repro:WriteInt(System.Byte[],int,int)
          12 ( 7.50% of base) : 216085.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this
          16 ( 7.48% of base) : 205890.dasm - <>c:<Main>b__2_17(System.UInt16[],System.UInt16[],System.UInt16[]):bool:this
           2 ( 6.67% of base) : 214591.dasm - Test:test11(System.SByte[],byte)
           2 ( 6.67% of base) : 214592.dasm - Test:test12(System.SByte[],byte)
           2 ( 6.67% of base) : 214593.dasm - Test:test13(System.SByte[],byte)
           6 ( 6.67% of base) : 231825.dasm - Repro:WriteFloat(System.Byte[],int,float)
          10 ( 6.33% of base) : 204541.dasm - <>c:<Main>b__2_7(System.Double[],System.Double[],System.Double[]):bool:this
          10 ( 6.33% of base) : 205877.dasm - <>c:<Main>b__2_1(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 6.33% of base) : 205879.dasm - <>c:<Main>b__2_3(System.Single[],System.Single[],System.Single[]):bool:this
          10 ( 6.25% of base) : 210719.dasm - <>c:<Main>b__2_0(System.Single[],System.Single[],System.Single[]):bool:this

Top method improvements (percentages):
         -76 (-14.18% of base) : 149158.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.18% of base) : 145402.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.13% of base) : 164812.dasm - testout1:Sub_Funclet_264():int
         -76 (-14.13% of base) : 136745.dasm - testout1:Sub_Funclet_264():int
         -76 (-13.62% of base) : 149157.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.62% of base) : 145401.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.57% of base) : 164811.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.57% of base) : 149244.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.57% of base) : 145485.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.57% of base) : 136744.dasm - testout1:Sub_Funclet_263():int
         -76 (-13.52% of base) : 164898.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.52% of base) : 136828.dasm - testout1:Sub_Funclet_186():int
         -76 (-13.48% of base) : 149245.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.48% of base) : 145486.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.43% of base) : 164899.dasm - testout1:Sub_Funclet_187():int
         -76 (-13.43% of base) : 136829.dasm - testout1:Sub_Funclet_187():int
         -48 (-13.41% of base) : 164897.dasm - testout1:Sub_Funclet_185():int
         -44 (-12.09% of base) : 164810.dasm - testout1:Sub_Funclet_262():int
         -44 (-12.02% of base) : 149156.dasm - testout1:Sub_Funclet_262():int
         -60 (-10.75% of base) : 149246.dasm - testout1:Sub_Funclet_188():int

582 total methods with Code Size differences (403 improved, 179 regressed), 12176 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2119740
Total bytes of diff: 2118946
Total bytes of delta: -794 (-0.04% of base)
Total relative delta: 1.07
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          26 : 145523.dasm (18.06% of base)
          22 : 167935.dasm (7.97% of base)
          22 : 165000.dasm (7.97% of base)
          22 : 167960.dasm (11.83% of base)
          20 : 167934.dasm (5.75% of base)
          20 : 164999.dasm (5.75% of base)
          18 : 152390.dasm (10.98% of base)
          18 : 152392.dasm (10.98% of base)
          18 : 194899.dasm (15.52% of base)
          16 : 164863.dasm (7.21% of base)
          12 : 152391.dasm (8.11% of base)
          10 : 170039.dasm (0.86% of base)
          10 : 194767.dasm (1.08% of base)
           8 : 170028.dasm (4.71% of base)
           8 : 167994.dasm (3.15% of base)
           8 : 164978.dasm (3.15% of base)
           6 : 165012.dasm (2.78% of base)
           6 : 170015.dasm (2.78% of base)
           6 : 83085.dasm (0.13% of base)
           6 : 152393.dasm (4.55% of base)

Top file improvements (bytes):
        -352 : 165008.dasm (-8.68% of base)
        -352 : 167992.dasm (-8.68% of base)
         -28 : 42382.dasm (-5.17% of base)
         -28 : 11031.dasm (-1.18% of base)
         -26 : 165009.dasm (-0.58% of base)
         -24 : 167972.dasm (-0.55% of base)
         -20 : 165013.dasm (-0.36% of base)
         -14 : 164997.dasm (-3.23% of base)
         -14 : 167957.dasm (-0.26% of base)
         -14 : 167980.dasm (-3.23% of base)
         -10 : 131659.dasm (-1.51% of base)
          -8 : 104935.dasm (-6.78% of base)
          -8 : 147131.dasm (-0.44% of base)
          -8 : 95215.dasm (-2.11% of base)
          -8 : 194923.dasm (-1.00% of base)
          -8 : 167025.dasm (-0.67% of base)
          -6 : 12668.dasm (-0.48% of base)
          -6 : 7305.dasm (-0.28% of base)
          -4 : 126736.dasm (-0.68% of base)
          -4 : 127016.dasm (-0.69% of base)

237 total files with Code Size differences (152 improved, 85 regressed), 2498 unchanged.

Top method regressions (bytes):
          26 (18.06% of base) : 145523.dasm - SslCredKey:GetHashCode():int:this
          22 ( 7.97% of base) : 167935.dasm - System.Data.RBTree`1:ComputeIndexByNode(int):int:this
          22 ( 7.97% of base) : 165000.dasm - System.Data.RBTree`1:ComputeIndexByNode(int):int:this
          22 (11.83% of base) : 167960.dasm - System.Data.RBTree`1:UpdateNodeKey(int,int):this
          20 ( 5.75% of base) : 167934.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
          20 ( 5.75% of base) : 164999.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
          18 (10.98% of base) : 152390.dasm - System.Xml.XmlBufferReader:GetApostropheCharEntity(int,int):int:this
          18 (10.98% of base) : 152392.dasm - System.Xml.XmlBufferReader:GetQuoteCharEntity(int,int):int:this
          18 (15.52% of base) : 194899.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool
          16 ( 7.21% of base) : 164863.dasm - System.Data.Index:GetRangeFromNode(int):System.Data.Range:this
          12 ( 8.11% of base) : 152391.dasm - System.Xml.XmlBufferReader:GetAmpersandCharEntity(int,int):int:this
          10 ( 0.86% of base) : 170039.dasm - Number:FormatFixed(byref,byref,int,int,System.Globalization.NumberFormatInfo,System.Int32[],System.String,System.String)
          10 ( 1.08% of base) : 194767.dasm - System.Text.RegularExpressions.RegexNode:<ReduceAlternation>g__ReduceSingleLetterAndNestedAlternations|81_0():this
           8 ( 4.71% of base) : 170028.dasm - System.Numerics.BigIntegerCalculator:Add(System.UInt32[],int):System.UInt32[]
           8 ( 3.15% of base) : 167994.dasm - System.Data.RBTree`1:RecomputeSize(int):this
           8 ( 3.15% of base) : 164978.dasm - System.Data.RBTree`1:RecomputeSize(int):this
           6 ( 2.78% of base) : 165012.dasm - System.Data.RBTree`1:UpdateNodeKey(System.__Canon,System.__Canon):this
           6 ( 2.78% of base) : 170015.dasm - System.Numerics.BigIntegerCalculator:Divide(System.UInt32[],System.UInt32[],byref):System.UInt32[]
           6 ( 0.13% of base) : 83085.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteUnstructuredExceptionHandlingStatementIntoBlock(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
           6 ( 4.55% of base) : 152393.dasm - System.Xml.XmlBufferReader:GetGreaterThanCharEntity(int,int):int:this

Top method improvements (bytes):
        -352 (-8.68% of base) : 165008.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
        -352 (-8.68% of base) : 167992.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
         -28 (-5.17% of base) : 42382.dasm - System.Drawing.Imaging.ColorMatrix:SetMatrix(System.Single[][]):this
         -28 (-1.18% of base) : 11031.dasm - System.Xml.XmlDocument:.ctor(System.Xml.XmlImplementation):this
         -26 (-0.58% of base) : 165009.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -24 (-0.55% of base) : 167972.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -20 (-0.36% of base) : 165013.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
         -14 (-3.23% of base) : 164997.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
         -14 (-0.26% of base) : 167957.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
         -14 (-3.23% of base) : 167980.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
         -10 (-1.51% of base) : 131659.dasm - System.Sha1ForNonSecretPurposes:Drain():this
          -8 (-6.78% of base) : 104935.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -8 (-0.44% of base) : 147131.dasm - Microsoft.VisualBasic.CompilerServices.StringType:StrLikeText(System.String,System.String):bool
          -8 (-2.11% of base) : 95215.dasm - AssemblyDataForAssemblyBeingBuilt:BindAssemblyReferences(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+AssemblyData[System.__Canon, System.__Canon]],Microsoft.CodeAnalysis.AssemblyIdentityComparer):Microsoft.CodeAnalysis.CommonReferenceManager`2+AssemblyReferenceBinding[System.__Canon, System.__Canon][]:this
          -8 (-1.00% of base) : 194923.dasm - System.Text.RegularExpressions.RegexBoyerMoore:Scan(System.String,int,int,int):int:this
          -8 (-0.67% of base) : 167025.dasm - System.Data.XmlTreeGen:SetupAutoGenerated(System.Data.DataTable):this
          -6 (-0.48% of base) : 12668.dasm - System.Xml.XmlTextReaderImpl:ParseNumericCharRefInline(int,bool,System.Text.StringBuilder,byref,byref):int:this
          -6 (-0.28% of base) : 7305.dasm - BigNumber:DblToRgbPrecise(double,System.Byte[],byref,byref)
          -4 (-0.68% of base) : 126736.dasm - System.Text.UTF8Encoding:GetChars(System.Byte[],int,int,System.Char[],int):int:this
          -4 (-0.69% of base) : 127016.dasm - System.Text.Latin1Encoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this

Top method regressions (percentages):
          26 (18.06% of base) : 145523.dasm - SslCredKey:GetHashCode():int:this
          18 (15.52% of base) : 194899.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool
          22 (11.83% of base) : 167960.dasm - System.Data.RBTree`1:UpdateNodeKey(int,int):this
          18 (10.98% of base) : 152390.dasm - System.Xml.XmlBufferReader:GetApostropheCharEntity(int,int):int:this
          18 (10.98% of base) : 152392.dasm - System.Xml.XmlBufferReader:GetQuoteCharEntity(int,int):int:this
           4 ( 8.70% of base) : 7111.dasm - System.Xml.Xsl.Xslt.OutputScopeManager:Reset():this
          12 ( 8.11% of base) : 152391.dasm - System.Xml.XmlBufferReader:GetAmpersandCharEntity(int,int):int:this
          22 ( 7.97% of base) : 167935.dasm - System.Data.RBTree`1:ComputeIndexByNode(int):int:this
          22 ( 7.97% of base) : 165000.dasm - System.Data.RBTree`1:ComputeIndexByNode(int):int:this
          16 ( 7.21% of base) : 164863.dasm - System.Data.Index:GetRangeFromNode(int):System.Data.Range:this
           4 ( 6.67% of base) : 164980.dasm - System.Data.RBTree`1:SetSubTreeSize(int,int):this
           4 ( 6.67% of base) : 164981.dasm - System.Data.RBTree`1:SetNext(int,int):this
           4 ( 6.67% of base) : 164983.dasm - System.Data.RBTree`1:SetColor(int,int):this
           4 ( 6.67% of base) : 164984.dasm - System.Data.RBTree`1:SetParent(int,int):this
           4 ( 6.67% of base) : 164985.dasm - System.Data.RBTree`1:SetLeft(int,int):this
           4 ( 6.67% of base) : 164986.dasm - System.Data.RBTree`1:SetRight(int,int):this
          20 ( 5.75% of base) : 167934.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
          20 ( 5.75% of base) : 164999.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
           4 ( 5.26% of base) : 164982.dasm - System.Data.RBTree`1:SetKey(int,System.__Canon):this
           8 ( 4.71% of base) : 170028.dasm - System.Numerics.BigIntegerCalculator:Add(System.UInt32[],int):System.UInt32[]

Top method improvements (percentages):
        -352 (-8.68% of base) : 165008.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
        -352 (-8.68% of base) : 167992.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
          -8 (-6.78% of base) : 104935.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
         -28 (-5.17% of base) : 42382.dasm - System.Drawing.Imaging.ColorMatrix:SetMatrix(System.Single[][]):this
          -4 (-4.35% of base) : 163728.dasm - System.Data.SqlTypes.SqlBinary:GetHashCode():int:this
         -14 (-3.23% of base) : 164997.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -2 (-3.23% of base) : 1322.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetIndexBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
         -14 (-3.23% of base) : 167980.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
          -2 (-2.70% of base) : 1373.dasm - Microsoft.CSharp.RuntimeBinder.CSharpGetMemberBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
          -2 (-2.70% of base) : 1313.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetMemberBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
          -2 (-2.27% of base) : 1303.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
          -8 (-2.11% of base) : 95215.dasm - AssemblyDataForAssemblyBeingBuilt:BindAssemblyReferences(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+AssemblyData[System.__Canon, System.__Canon]],Microsoft.CodeAnalysis.AssemblyIdentityComparer):Microsoft.CodeAnalysis.CommonReferenceManager`2+AssemblyReferenceBinding[System.__Canon, System.__Canon][]:this
          -2 (-2.00% of base) : 1374.dasm - Microsoft.CSharp.RuntimeBinder.CSharpGetMemberBinder:DispatchPayload(Microsoft.CSharp.RuntimeBinder.RuntimeBinder,Microsoft.CSharp.RuntimeBinder.ArgumentObject[],Microsoft.CSharp.RuntimeBinder.Semantics.LocalVariableSymbol[]):Microsoft.CSharp.RuntimeBinder.Semantics.Expr:this
          -2 (-2.00% of base) : 166190.dasm - System.Data.DataKey:GetSortIndex():System.Data.Index:this
          -2 (-1.96% of base) : 166189.dasm - System.Data.DataKey:GetSortIndex(int):System.Data.Index:this
          -2 (-1.96% of base) : 185814.dasm - System.IO.Compression.Inflater:Inflate(System.Byte[],int,int):int:this
          -4 (-1.90% of base) : 167963.dasm - System.Data.RBTree`1:InitTree():this
          -4 (-1.85% of base) : 165029.dasm - System.Data.RBTree`1:InitTree():this
          -2 (-1.75% of base) : 170667.dasm - System.Net.Sockets.SocketPal:Bind(System.Net.Sockets.SafeSocketHandle,int,System.Byte[],int):int
          -2 (-1.67% of base) : 177581.dasm - FastSerialization.PinnedStreamReader:.ctor(System.IO.Stream,int):this

237 total methods with Code Size differences (152 improved, 85 regressed), 2498 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2712338
Total bytes of diff: 2712676
Total bytes of delta: 338 (0.01% of base)
Total relative delta: NaN
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          42 : 159388.dasm (2.02% of base)
          38 : 151460.dasm (18.45% of base)
          26 : 159283.dasm (12.26% of base)
          26 : 183235.dasm (18.57% of base)
          26 : 159405.dasm (1.75% of base)
          26 : 159426.dasm (2.54% of base)
          26 : 159311.dasm (12.04% of base)
          22 : 159126.dasm (8.09% of base)
          22 : 159235.dasm (12.64% of base)
          22 : 159187.dasm (8.09% of base)
          22 : 159269.dasm (12.64% of base)
          22 : 158811.dasm (2.56% of base)
          22 : 158812.dasm (2.58% of base)
          22 : 159255.dasm (12.64% of base)
          22 : 159389.dasm (1.91% of base)
          20 : 159127.dasm (5.81% of base)
          20 : 159188.dasm (5.81% of base)
          18 : 150830.dasm (12.00% of base)
          18 : 150832.dasm (12.00% of base)
          18 : 175383.dasm (16.07% of base)

Top file improvements (bytes):
         -40 : 159239.dasm (-1.01% of base)
         -40 : 159178.dasm (-1.01% of base)
         -28 : 147414.dasm (-5.20% of base)
         -28 : 159177.dasm (-0.67% of base)
         -26 : 159238.dasm (-0.63% of base)
         -20 : 185932.dasm (-12.50% of base)
         -16 : 159129.dasm (-3.76% of base)
         -16 : 159190.dasm (-3.76% of base)
         -14 : 150835.dasm (-1.90% of base)
         -14 : 113173.dasm (-0.30% of base)
         -14 : 159173.dasm (-0.27% of base)
         -12 : 75231.dasm (-0.62% of base)
         -12 : 159234.dasm (-0.23% of base)
         -10 : 218369.dasm (-0.27% of base)
         -10 : 194188.dasm (-0.79% of base)
         -10 : 175345.dasm (-1.38% of base)
          -8 : 194033.dasm (-1.39% of base)
          -8 : 161161.dasm (-4.49% of base)
          -8 : 144134.dasm (-7.02% of base)
          -8 : 157001.dasm (-0.76% of base)

342 total files with Code Size differences (151 improved, 191 regressed), 3110 unchanged.

Top method regressions (bytes):
          42 ( 2.02% of base) : 159388.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
          38 (18.45% of base) : 151460.dasm - System.Xml.XmlSigningNodeWriter:WriteBoolText(bool):this
          26 (12.26% of base) : 159283.dasm - System.Data.RBTree`1[Double][System.Double]:UpdateNodeKey(double,double):this
          26 (18.57% of base) : 183235.dasm - SslCredKey:GetHashCode():int:this
          26 ( 1.75% of base) : 159405.dasm - System.Data.Index:RecordStateChanged(int,int,int,int,int,int):this
          26 ( 2.54% of base) : 159426.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
          26 (12.04% of base) : 159311.dasm - System.Data.RBTree`1[Int64][System.Int64]:UpdateNodeKey(long,long):this
          22 ( 8.09% of base) : 159126.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeIndexByNode(int):int:this
          22 (12.64% of base) : 159235.dasm - System.Data.RBTree`1[Byte][System.Byte]:UpdateNodeKey(ubyte,ubyte):this
          22 ( 8.09% of base) : 159187.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeIndexByNode(int):int:this
          22 (12.64% of base) : 159269.dasm - System.Data.RBTree`1[Int32][System.Int32]:UpdateNodeKey(int,int):this
          22 ( 2.56% of base) : 158811.dasm - System.Data.DataView:CopyTo(System.Array,int):this
          22 ( 2.58% of base) : 158812.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
          22 (12.64% of base) : 159255.dasm - System.Data.RBTree`1[Int16][System.Int16]:UpdateNodeKey(short,short):this
          22 ( 1.91% of base) : 159389.dasm - System.Data.Select:GetLinearFilteredRows(System.Data.Range):System.Data.DataRow[]:this
          20 ( 5.81% of base) : 159127.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeIndexWithSatelliteByNode(int):int:this
          20 ( 5.81% of base) : 159188.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeIndexWithSatelliteByNode(int):int:this
          18 (12.00% of base) : 150830.dasm - System.Xml.XmlBufferReader:GetQuoteCharEntity(int,int):int:this
          18 (12.00% of base) : 150832.dasm - System.Xml.XmlBufferReader:GetApostropheCharEntity(int,int):int:this
          18 (16.07% of base) : 175383.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool

Top method improvements (bytes):
         -40 (-1.01% of base) : 159239.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteFixup(int,int,int,int):int:this
         -40 (-1.01% of base) : 159178.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
         -28 (-5.20% of base) : 147414.dasm - System.Drawing.Imaging.ColorMatrix:SetMatrix(System.Single[][]):this
         -28 (-0.67% of base) : 159177.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -26 (-0.63% of base) : 159238.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBDeleteX(int,int,int):int:this
         -20 (-12.50% of base) : 185932.dasm - Internal.TypeSystem.GCPointerMap:get_NumSeries():int:this
         -16 (-3.76% of base) : 159129.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeNodeByIndex(int,byref):int:this
         -16 (-3.76% of base) : 159190.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeNodeByIndex(int,byref):int:this
         -14 (-1.90% of base) : 150835.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this
         -14 (-0.30% of base) : 113173.dasm - Microsoft.Cci.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,int,int,int,bool,bool,bool):this
         -14 (-0.27% of base) : 159173.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBInsert(int,int,int,int,bool):int:this
         -12 (-0.62% of base) : 75231.dasm - BigNumber:DblToRgbPrecise(double,System.Byte[],byref,byref)
         -12 (-0.23% of base) : 159234.dasm - System.Data.RBTree`1[Byte][System.Byte]:RBInsert(int,int,int,int,bool):int:this
         -10 (-0.27% of base) : 218369.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -10 (-0.79% of base) : 194188.dasm - System.Numerics.BigInteger:.ctor(System.ReadOnlySpan`1[Byte],bool,bool):this
         -10 (-1.38% of base) : 175345.dasm - System.Text.RegularExpressions.RegexBoyerMoore:Scan(System.String,int,int,int):int:this
          -8 (-1.39% of base) : 194033.dasm - System.Numerics.BigIntegerCalculator:ExtractDigits(byref,byref,byref,byref)
          -8 (-4.49% of base) : 161161.dasm - System.Data.Common.DataStorage:CompareBits(int,int):int:this
          -8 (-7.02% of base) : 144134.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
          -8 (-0.76% of base) : 157001.dasm - System.Data.XmlTreeGen:SetupAutoGenerated(System.Data.DataTable):this

Top method regressions (percentages):
          26 (18.57% of base) : 183235.dasm - SslCredKey:GetHashCode():int:this
          38 (18.45% of base) : 151460.dasm - System.Xml.XmlSigningNodeWriter:WriteBoolText(bool):this
          18 (16.07% of base) : 175383.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool
          22 (12.64% of base) : 159235.dasm - System.Data.RBTree`1[Byte][System.Byte]:UpdateNodeKey(ubyte,ubyte):this
          22 (12.64% of base) : 159269.dasm - System.Data.RBTree`1[Int32][System.Int32]:UpdateNodeKey(int,int):this
          22 (12.64% of base) : 159255.dasm - System.Data.RBTree`1[Int16][System.Int16]:UpdateNodeKey(short,short):this
          26 (12.26% of base) : 159283.dasm - System.Data.RBTree`1[Double][System.Double]:UpdateNodeKey(double,double):this
          26 (12.04% of base) : 159311.dasm - System.Data.RBTree`1[Int64][System.Int64]:UpdateNodeKey(long,long):this
          18 (12.00% of base) : 150830.dasm - System.Xml.XmlBufferReader:GetQuoteCharEntity(int,int):int:this
          18 (12.00% of base) : 150832.dasm - System.Xml.XmlBufferReader:GetApostropheCharEntity(int,int):int:this
           4 ( 9.52% of base) : 75475.dasm - System.Xml.Xsl.Xslt.OutputScopeManager:Reset():this
          12 ( 8.96% of base) : 150831.dasm - System.Xml.XmlBufferReader:GetAmpersandCharEntity(int,int):int:this
          22 ( 8.09% of base) : 159126.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeIndexByNode(int):int:this
          22 ( 8.09% of base) : 159187.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeIndexByNode(int):int:this
          16 ( 7.77% of base) : 159418.dasm - System.Data.Index:GetRangeFromNode(int):System.Data.Range:this
          10 ( 7.35% of base) : 38322.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:IsBlankLine(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxListBuilder):bool
           4 ( 7.14% of base) : 159140.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:SetRight(int,int):this
           4 ( 7.14% of base) : 159141.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:SetLeft(int,int):this
           4 ( 7.14% of base) : 159142.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:SetParent(int,int):this
           4 ( 7.14% of base) : 159143.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:SetColor(int,int):this

Top method improvements (percentages):
         -20 (-12.50% of base) : 185932.dasm - Internal.TypeSystem.GCPointerMap:get_NumSeries():int:this
          -8 (-7.02% of base) : 144134.dasm - System.Text.ISO2022Encoding:DecrementEscapeBytes(byref,byref):ubyte:this
         -28 (-5.20% of base) : 147414.dasm - System.Drawing.Imaging.ColorMatrix:SetMatrix(System.Single[][]):this
          -4 (-4.88% of base) : 160564.dasm - System.Data.SqlTypes.SqlBinary:GetHashCode():int:this
          -8 (-4.49% of base) : 161161.dasm - System.Data.Common.DataStorage:CompareBits(int,int):int:this
          -2 (-4.00% of base) : 24812.dasm - Microsoft.CSharp.RuntimeBinder.CSharpGetIndexBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
         -16 (-3.76% of base) : 159129.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:ComputeNodeByIndex(int,byref):int:this
         -16 (-3.76% of base) : 159190.dasm - System.Data.RBTree`1[Byte][System.Byte]:ComputeNodeByIndex(int,byref):int:this
          -2 (-3.12% of base) : 24885.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:PopulateSymbolTableWithName(System.Type,Microsoft.CSharp.RuntimeBinder.ArgumentObject[]):this
          -2 (-2.78% of base) : 157816.dasm - System.Data.DataKey:GetSortIndex():System.Data.Index:this
          -2 (-2.70% of base) : 157817.dasm - System.Data.DataKey:GetSortIndex(int):System.Data.Index:this
          -2 (-2.22% of base) : 24818.dasm - Microsoft.CSharp.RuntimeBinder.CSharpGetMemberBinder:DispatchPayload(Microsoft.CSharp.RuntimeBinder.RuntimeBinder,Microsoft.CSharp.RuntimeBinder.ArgumentObject[],Microsoft.CSharp.RuntimeBinder.Semantics.LocalVariableSymbol[]):Microsoft.CSharp.RuntimeBinder.Semantics.Expr:this
          -2 (-2.17% of base) : 214886.dasm - System.IO.Compression.Inflater:Inflate(System.Byte[],int,int):int:this
          -2 (-2.13% of base) : 196743.dasm - System.Net.Sockets.SocketPal:Bind(System.Net.Sockets.SafeSocketHandle,int,System.Byte[],int):int
          -4 (-2.02% of base) : 159157.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:InitTree():this
          -4 (-2.00% of base) : 159218.dasm - System.Data.RBTree`1[Byte][System.Byte]:InitTree():this
         -14 (-1.90% of base) : 150835.dasm - System.Xml.XmlBufferReader:GetCharEntity(int,int):int:this
          -2 (-1.79% of base) : 159539.dasm - System.Data.UniqueConstraint:ConstraintIndexInitialize():this
          -2 (-1.79% of base) : 69943.dasm - System.Xml.XmlTextReaderImpl:ParseCharRefInline(int,byref,byref):int:this
          -4 (-1.74% of base) : 146948.dasm - System.Drawing.Drawing2D.GraphicsPathIterator:Enumerate(byref,byref):int:this

342 total methods with Code Size differences (151 improved, 191 regressed), 3111 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7274890
Total bytes of diff: 7273676
Total bytes of delta: -1214 (-0.02% of base)
Total relative delta: -1.20
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          18 : 282085.dasm (16.07% of base)
          14 : 170149.dasm (0.48% of base)
          12 : 200079.dasm (2.33% of base)
          10 : 37098.dasm (2.59% of base)
           8 : 122498.dasm (2.12% of base)
           8 : 234011.dasm (1.53% of base)
           8 : 89424.dasm (6.45% of base)
           8 : 176307.dasm (6.45% of base)
           8 : 239294.dasm (1.53% of base)
           6 : 79596.dasm (1.06% of base)
           6 : 79598.dasm (1.09% of base)
           6 : 305627.dasm (2.14% of base)
           6 : 79511.dasm (1.28% of base)
           6 : 37010.dasm (1.52% of base)
           6 : 145944.dasm (1.79% of base)
           4 : 10090.dasm (0.41% of base)
           4 : 122497.dasm (2.06% of base)
           4 : 146163.dasm (0.64% of base)
           4 : 164135.dasm (1.61% of base)
           4 : 175199.dasm (0.45% of base)

Top file improvements (bytes):
         -32 : 258434.dasm (-0.50% of base)
         -22 : 204676.dasm (-1.70% of base)
         -18 : 206053.dasm (-0.87% of base)
         -16 : 199633.dasm (-0.54% of base)
         -16 : 78724.dasm (-0.76% of base)
         -16 : 78743.dasm (-0.73% of base)
         -16 : 200090.dasm (-0.27% of base)
         -12 : 170177.dasm (-0.23% of base)
         -12 : 199691.dasm (-0.32% of base)
         -12 : 172610.dasm (-0.51% of base)
         -12 : 49509.dasm (-0.58% of base)
         -12 : 199713.dasm (-0.47% of base)
         -12 : 199714.dasm (-0.34% of base)
         -12 : 204548.dasm (-0.42% of base)
         -10 : 170176.dasm (-0.31% of base)
         -10 : 170190.dasm (-0.77% of base)
         -10 : 81639.dasm (-0.68% of base)
         -10 : 170687.dasm (-0.54% of base)
         -10 : 171153.dasm (-1.33% of base)
         -10 : 171157.dasm (-1.38% of base)

567 total files with Code Size differences (404 improved, 163 regressed), 5766 unchanged.

Top method regressions (bytes):
          18 (16.07% of base) : 282085.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool
          14 ( 0.48% of base) : 170149.dasm - Microsoft.CodeAnalysis.CSharp.ReplaceDiscardDeclarationsWithAssignments.CSharpReplaceDiscardDeclarationsWithAssignmentsService:ReplaceAsync(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.Workspace,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          12 ( 2.33% of base) : 200079.dasm - System.Data.Tests.DataTableTest2:GetErrors():this
          10 ( 2.59% of base) : 37098.dasm - System.Collections.Tests.List_Generic_Tests`1[Byte][System.Byte]:Sort_intintIComparer_WithDuplicates(int):this
           8 ( 2.12% of base) : 122498.dasm - Microsoft.Build.Tasks.Deployment.ManifestUtilities.Util:GetClrVersion(System.String):System.String
           8 ( 1.53% of base) : 234011.dasm - System.Data.SqlClient.TdsParserStateObject:WritePacket(ubyte,bool):System.Threading.Tasks.Task:this
           8 ( 6.45% of base) : 89424.dasm - System.Net.Test.Common.HPackEncoder:EncodeInteger(int,ubyte,ubyte,System.Span`1[Byte]):int
           8 ( 6.45% of base) : 176307.dasm - System.Net.Test.Common.HPackEncoder:EncodeInteger(int,ubyte,ubyte,System.Span`1[Byte]):int
           8 ( 1.53% of base) : 239294.dasm - System.Data.SqlClient.TdsParserStateObject:WritePacket(ubyte,bool):System.Threading.Tasks.Task:this
           6 ( 1.06% of base) : 79596.dasm - System.Text.Json.Serialization.Tests.ReferenceHandlerTests:ArrayPreserveDuplicateObjects()
           6 ( 1.09% of base) : 79598.dasm - System.Text.Json.Serialization.Tests.ReferenceHandlerTests:ArrayPreserveDuplicateDictionaries()
           6 ( 2.14% of base) : 305627.dasm - System.Text.Tests.UTF8EncodingEncode:FixedEncodingHelper(System.Char[],int,System.Byte[],int)
           6 ( 1.28% of base) : 79511.dasm - System.Text.Json.Serialization.Tests.ReferenceHandlerTests:ArrayWithDuplicates()
           6 ( 1.52% of base) : 37010.dasm - System.Collections.Tests.List_Generic_Tests`1[__Canon][System.__Canon]:Sort_intintIComparer_WithDuplicates(int):this
           6 ( 1.79% of base) : 145944.dasm - System.Formats.Asn1.Tests.Writer.WriteNamedBitList:VerifyWriteNamedBitList_BitArray_7992Bits(int)
           4 ( 0.41% of base) : 10090.dasm - System.Linq.Expressions.Tests.LambdaTests:HighArityDelegate(bool):this
           4 ( 2.06% of base) : 122497.dasm - Microsoft.Build.Tasks.Deployment.ManifestUtilities.Util:GetClrVersion():System.String
           4 ( 0.64% of base) : 146163.dasm - System.Formats.Asn1.Tests.Reader.ReadNamedBitList:ReadNamedBitList_BitArray_7992Bits(int)
           4 ( 1.61% of base) : 164135.dasm - System.SpanTests.SpanTests:MakeSureNoEndsWithChecksGoOutOfRange_Byte()
           4 ( 0.45% of base) : 175199.dasm - System.Net.Http.Tests.HttpResponseHeadersTest:Location_RequiresEncoding_Encoded():this

Top method improvements (bytes):
         -32 (-0.50% of base) : 258434.dasm - System.Diagnostics.Tests.DiagnosticSourceTest:MultiSubscriber():this
         -22 (-1.70% of base) : 204676.dasm - Microsoft.CodeAnalysis.VisualBasic.Utilities.NameSyntaxComparer:Compare(Microsoft.CodeAnalysis.VisualBasic.Syntax.NameSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.NameSyntax):int:this
         -18 (-0.87% of base) : 206053.dasm - AddMissingTokensRewriter:SetOmittedToken(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.SyntaxNode
         -16 (-0.54% of base) : 199633.dasm - System.Data.Tests.DataSetTest:CloneCopy_TestForeignKeyConstraints():this
         -16 (-0.76% of base) : 78724.dasm - System.Text.Json.Serialization.Tests.ArrayTests:<ClassWithNonNullEnumerableGettersIsParsed>g__TestRoundTrip|52_0(ClassWithNonNullEnumerableGetters)
         -16 (-0.73% of base) : 78743.dasm - System.Text.Json.Serialization.Tests.ArrayTests:ClassWithNonNullEnumerableGettersIsParsed()
         -16 (-0.27% of base) : 200090.dasm - System.Data.Tests.DataTableTest3:VerifyParentTableSchema(System.Data.DataTable,System.String,System.Data.DataSet):this
         -12 (-0.23% of base) : 170177.dasm - Microsoft.CodeAnalysis.CSharp.Utilities.FormattingRangeHelper:FindAppropriateRangeForCloseBrace(Microsoft.CodeAnalysis.SyntaxToken):System.Nullable`1[ValueTuple`2]
         -12 (-0.32% of base) : 199691.dasm - System.Data.Tests.DataSetTest2:InferXmlSchema_inferringRelationships1():this
         -12 (-0.51% of base) : 172610.dasm - Expander:VisitSimpleLambdaExpression(Microsoft.CodeAnalysis.CSharp.Syntax.SimpleLambdaExpressionSyntax):Microsoft.CodeAnalysis.SyntaxNode:this
         -12 (-0.58% of base) : 49509.dasm - Microsoft.CodeAnalysis.Shared.Extensions.SyntaxGeneratorExtensions:Negate(Microsoft.CodeAnalysis.Editing.SyntaxGenerator,Microsoft.CodeAnalysis.Editing.SyntaxGeneratorInternal,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.SemanticModel,bool,System.Threading.CancellationToken):Microsoft.CodeAnalysis.SyntaxNode
         -12 (-0.47% of base) : 199713.dasm - System.Data.Tests.DataSetTest2:CompareResults_1(System.String,System.Data.DataSet,System.Data.DataSet):this
         -12 (-0.34% of base) : 199714.dasm - System.Data.Tests.DataSetTest2:CompareResults_2(System.String,System.Data.DataSet,System.Data.DataSet):this
         -12 (-0.42% of base) : 204548.dasm - Microsoft.CodeAnalysis.VisualBasic.Simplification.VisualBasicVariableDeclaratorReducer:TryReduceVariableDeclaratorWithoutType(Microsoft.CodeAnalysis.VisualBasic.Syntax.VariableDeclaratorSyntax,Microsoft.CodeAnalysis.SemanticModel,byref,byref):bool
         -10 (-0.31% of base) : 170176.dasm - Microsoft.CodeAnalysis.CSharp.Utilities.FormattingRangeHelper:FindAppropriateRangeForSemicolon(Microsoft.CodeAnalysis.SyntaxToken):System.Nullable`1[ValueTuple`2]
         -10 (-0.77% of base) : 170190.dasm - Microsoft.CodeAnalysis.CSharp.Utilities.NameSyntaxComparer:Compare(Microsoft.CodeAnalysis.CSharp.Syntax.NameSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.NameSyntax):int:this
         -10 (-0.68% of base) : 81639.dasm - <ReadListOfArray>d__138:MoveNext():this
         -10 (-0.54% of base) : 170687.dasm - Microsoft.CodeAnalysis.CSharp.Simplification.CSharpMiscellaneousReducer:SimplifyBlock(Microsoft.CodeAnalysis.CSharp.Syntax.BlockSyntax,Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.Options.OptionSet,System.Threading.CancellationToken):Microsoft.CodeAnalysis.SyntaxNode
         -10 (-1.33% of base) : 171153.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.IndentBlockFormattingRule:AddTypeParameterConstraintClauseOperation(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode)
         -10 (-1.38% of base) : 171157.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.IndentBlockFormattingRule:SetAlignmentBlockOperation(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.SyntaxNode)

Top method regressions (percentages):
          18 (16.07% of base) : 282085.dasm - System.Text.RegularExpressions.RegexCharClass:TryGetSingleRange(System.String,byref,byref):bool
           8 ( 6.45% of base) : 89424.dasm - System.Net.Test.Common.HPackEncoder:EncodeInteger(int,ubyte,ubyte,System.Span`1[Byte]):int
           8 ( 6.45% of base) : 176307.dasm - System.Net.Test.Common.HPackEncoder:EncodeInteger(int,ubyte,ubyte,System.Span`1[Byte]):int
           2 ( 4.76% of base) : 199770.dasm - System.Data.Tests.DataTableCollectionTest:<AddException1>b__5_0():this
           2 ( 4.76% of base) : 317397.dasm - <>c__DisplayClass0_0:<MakeGenericType_NullTypeArguments_ThrowsInvalidOperationException>b__0():System.Object:this
           2 ( 4.76% of base) : 317402.dasm - <>c__DisplayClass4_0:<SetCustomAttribute_CustomAttributeBuilder_NullAttributeBuilder_ThrowsArgumentNullException>b__0():this
           2 ( 4.55% of base) : 57102.dasm - SignatureTypeSymbolEquivalenceComparer:GetHashCode(Microsoft.CodeAnalysis.ITypeSymbol):int:this
           2 ( 4.35% of base) : 57100.dasm - SignatureTypeSymbolEquivalenceComparer:Equals(Microsoft.CodeAnalysis.ITypeSymbol,Microsoft.CodeAnalysis.ITypeSymbol):bool:this
           2 ( 4.00% of base) : 290350.dasm - Moq.EmptyDefaultValueProvider:CreateEnumerableOf(System.Type,Moq.Mock):System.Object
           4 ( 3.45% of base) : 337979.dasm - Microsoft.CodeAnalysis.FusionAssemblyIdentity:SetProperty(IAssemblyName,int,System.Byte[])
           2 ( 3.12% of base) : 251728.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToInstanceTest:Execute():this
           4 ( 2.86% of base) : 139141.dasm - AesLegalSizesBreaker:.ctor():this
           4 ( 2.86% of base) : 139815.dasm - RijndaelLegalSizesBreaker:.ctor():this
           4 ( 2.86% of base) : 139829.dasm - RC2LegalSizesBreaker:.ctor():this
           4 ( 2.86% of base) : 139862.dasm - DESLegalSizesBreaker:.ctor():this
           4 ( 2.86% of base) : 139921.dasm - TripleDESLegalSizesBreaker:.ctor():this
           2 ( 2.78% of base) : 234064.dasm - System.Data.SqlClient.TdsParserStateObject:IsNullCompressionBitSet(int):bool:this
           2 ( 2.78% of base) : 239884.dasm - NullBitmap:IsGuaranteedNull(int):bool:this
           2 ( 2.78% of base) : 234702.dasm - NullBitmap:IsGuaranteedNull(int):bool:this
           2 ( 2.78% of base) : 305789.dasm - <>c__DisplayClass4_0:<EncoderExceptionFallbackBufferTest>b__1():System.Object:this

Top method improvements (percentages):
          -8 (-7.69% of base) : 234141.dasm - System.Data.SqlClient.SNINativeMethodWrapper:SNISecGenClientContext(System.Data.SqlClient.SNIHandle,System.Byte[],int,System.Byte[],byref,System.Byte[]):int
          -4 (-6.67% of base) : 23618.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithImmutableArray:Verify():this
          -4 (-6.67% of base) : 77957.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithImmutableArray:Verify():this
          -4 (-5.88% of base) : 226982.dasm - System.Reflection.Metadata.Tests.StandalonePortablePdbStreamTests:ReadHeader(byref,byref,System.Byte[])
          -4 (-3.85% of base) : 23623.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithObjectImmutableArray:Verify():this
          -4 (-3.85% of base) : 77962.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithObjectImmutableArray:Verify():this
          -4 (-3.51% of base) : 234174.dasm - System.Data.SqlClient.TdsParserStateObjectNative:GenerateSspiClientContext(System.Byte[],int,byref,byref,System.Byte[]):int:this
          -2 (-3.03% of base) : 105306.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.method.regmethod.regclass.regclassregmeth.regclassregmeth.MemberClass:Method_ReturnUlong(byref,byref,byref):long:this
          -2 (-2.78% of base) : 137645.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacMD5Tests:HmacMD5_Rfc2202_4():this
          -2 (-2.78% of base) : 137646.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacMD5Tests:HmacMD5_Rfc2202_5():this
          -2 (-2.78% of base) : 137647.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacMD5Tests:HmacMD5_Rfc2202_6():this
          -2 (-2.78% of base) : 137648.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacMD5Tests:HmacMD5_Rfc2202_7():this
          -2 (-2.78% of base) : 137715.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha512Tests:HmacSha512_Rfc4231_3():this
          -2 (-2.78% of base) : 137716.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha512Tests:HmacSha512_Rfc4231_4():this
          -2 (-2.78% of base) : 137717.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha512Tests:HmacSha512_Rfc4231_5():this
          -2 (-2.78% of base) : 137718.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha512Tests:HmacSha512_Rfc4231_6():this
          -2 (-2.78% of base) : 137719.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha512Tests:HmacSha512_Rfc4231_7():this
          -2 (-2.78% of base) : 137697.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha384Tests:HmacSha384_Rfc4231_2():this
          -2 (-2.78% of base) : 137698.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha384Tests:HmacSha384_Rfc4231_3():this
          -2 (-2.78% of base) : 137699.dasm - System.Security.Cryptography.Hashing.Algorithms.Tests.HmacSha384Tests:HmacSha384_Rfc4231_4():this

567 total methods with Code Size differences (404 improved, 163 regressed), 5766 unchanged.

```

</details>

--------------------------------------------------------------------------------

