 ## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 312708
Total bytes of diff: 310136
Total bytes of delta: -2572 (-0.82% of base)
Total relative delta: -3.38
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -128 : 5849.dasm (-11.72% of base)
         -80 : 12529.dasm (-0.78% of base)
         -80 : 18414.dasm (-0.79% of base)
         -80 : 22190.dasm (-1.13% of base)
         -80 : 7626.dasm (-1.09% of base)
         -56 : 5795.dasm (-3.66% of base)
         -48 : 12516.dasm (-0.25% of base)
         -40 : 11339.dasm (-2.99% of base)
         -36 : 12010.dasm (-1.84% of base)
         -32 : 12042.dasm (-2.20% of base)
         -28 : 18022.dasm (-1.27% of base)
         -24 : 7431.dasm (-0.10% of base)
         -24 : 22588.dasm (-1.14% of base)
         -24 : 6529.dasm (-1.74% of base)
         -20 : 16787.dasm (-0.95% of base)
         -20 : 5133.dasm (-1.43% of base)
         -20 : 5369.dasm (-1.54% of base)
         -20 : 15878.dasm (-1.62% of base)
         -20 : 667.dasm (-1.46% of base)
         -20 : 156.dasm (-1.46% of base)

256 total files with Code Size differences (256 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -128 (-11.72% of base) : 5849.dasm - DecCalc:VarDecMul(byref,byref)
         -80 (-0.78% of base) : 12529.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffsetThunkReader(byref,System.Char[]):System.DateTimeOffset
         -80 (-0.79% of base) : 18414.dasm - Jil.Deserialize.Methods:_ReadISO8601DateThunkReader(byref,System.Char[]):System.DateTime
         -80 (-1.13% of base) : 22190.dasm - Jil.Deserialize.Methods:_ReadISO8601Date(System.IO.TextReader,System.Char[]):System.DateTime
         -80 (-1.09% of base) : 7626.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffset(System.IO.TextReader,System.Char[]):System.DateTimeOffset
         -56 (-3.66% of base) : 5795.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
         -48 (-0.25% of base) : 12516.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)
         -40 (-2.99% of base) : 11339.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)
         -36 (-1.84% of base) : 12010.dasm - DecCalc:DecAddSub(byref,byref,bool)
         -32 (-2.20% of base) : 12042.dasm - BenchmarksGame.FannkuchRedux_9:Run(int,int)
         -28 (-1.27% of base) : 18022.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:IsPossibleLocalDeclarationStatement(bool):bool:this
         -24 (-0.10% of base) : 7431.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.MyEventsListerItem,int)
         -24 (-1.14% of base) : 22588.dasm - DecCalc:VarDecDiv(byref,byref)
         -24 (-1.74% of base) : 6529.dasm - System.Collections.Generic.Dictionary`2[ValueTuple`2,__Canon][System.ValueTuple`2[System.Int32,System.Int32],System.__Canon]:TryInsert(System.ValueTuple`2[Int32,Int32],System.__Canon,ubyte):bool:this
         -20 (-0.95% of base) : 16787.dasm - Microsoft.CodeAnalysis.CSharp.ImportChain:TranslateImports(Microsoft.CodeAnalysis.CSharp.Emit.PEModuleBuilder,Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[UsedNamespaceOrType]:this
         -20 (-1.43% of base) : 5133.dasm - System.Collections.Generic.HashSet`1[Char][System.Char]:AddIfNotPresent(ushort,byref):bool:this
         -20 (-1.54% of base) : 5369.dasm - System.Globalization.IdnMapping:IcuGetAsciiCore(System.String,long,int):System.String:this
         -20 (-1.62% of base) : 15878.dasm - System.Collections.Generic.Dictionary`2[TypeDefinitionHandle,ImmutableArray`1][System.Reflection.Metadata.TypeDefinitionHandle,System.Collections.Immutable.ImmutableArray`1[System.Reflection.Metadata.TypeDefinitionHandle]]:TryInsert(System.Reflection.Metadata.TypeDefinitionHandle,System.Collections.Immutable.ImmutableArray`1[TypeDefinitionHandle],ubyte):bool:this
         -20 (-1.46% of base) : 667.dasm - System.Collections.Generic.Dictionary`2[__Canon,IntPtr][System.__Canon,System.IntPtr]:TryInsert(System.__Canon,long,ubyte):bool:this
         -20 (-1.46% of base) : 156.dasm - System.Collections.Generic.Dictionary`2[__Canon,HostSignal][System.__Canon,BenchmarkDotNet.Engines.HostSignal]:TryInsert(System.__Canon,int,ubyte):bool:this

Top method improvements (percentages):
        -128 (-11.72% of base) : 5849.dasm - DecCalc:VarDecMul(byref,byref)
          -8 (-5.00% of base) : 723.dasm - System.Object:MemberwiseClone():System.Object:this
         -12 (-5.00% of base) : 1150.dasm - System.TimeSpan:.ctor(int,int,int,int,int):this
          -4 (-4.35% of base) : 13390.dasm - System.DateTimeOffset:get_Offset():System.TimeSpan:this
          -8 (-4.00% of base) : 10077.dasm - Benchstone.BenchI.TreeInsert:BenchInner(int):this
          -4 (-4.00% of base) : 15868.dasm - Microsoft.CodeAnalysis.WellKnownMembers:GetDescriptor(int):Microsoft.CodeAnalysis.RuntimeMembers.MemberDescriptor
          -8 (-3.70% of base) : 7812.dasm - System.Xml.XmlWellFormedWriter:StartElementContent():this
         -56 (-3.66% of base) : 5795.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
          -4 (-3.57% of base) : 7874.dasm - System.Xml.XmlNamespaceManager:LookupNamespace(System.String):System.String:this
          -4 (-3.33% of base) : 8029.dasm - System.DateTimeOffset:ToString():System.String:this
          -4 (-3.23% of base) : 21508.dasm - System.Drawing.Tests.Perf_Color:GetHue():float:this
          -4 (-3.23% of base) : 19602.dasm - System.Tests.Perf_DateTimeOffset:ToString(System.DateTimeOffset):System.String:this
          -4 (-3.23% of base) : 21282.dasm - System.Drawing.Tests.Perf_Color:GetBrightness():float:this
          -4 (-3.23% of base) : 4689.dasm - System.Drawing.Tests.Perf_Color:GetSaturation():float:this
          -8 (-3.17% of base) : 20402.dasm - System.DateTimeOffset:System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(System.Object):this
          -4 (-3.12% of base) : 13711.dasm - System.Tests.Perf_DateTimeOffset:ToString(System.String):System.String:this
          -8 (-3.08% of base) : 9381.dasm - System.Collections.Queue:Enqueue(System.Object):this
         -40 (-2.99% of base) : 11339.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)
          -4 (-2.78% of base) : 2487.dasm - System.Runtime.Serialization.DateTimeOffsetAdapter:GetDateTimeOffsetAdapter(System.DateTimeOffset):System.Runtime.Serialization.DateTimeOffsetAdapter
          -4 (-2.70% of base) : 1945.dasm - System.DateTimeOffset:get_ClockDateTime():System.DateTime:this

256 total methods with Code Size differences (256 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 530184
Total bytes of diff: 521740
Total bytes of delta: -8444 (-1.59% of base)
Total relative delta: -53.44
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         472 : 224771.dasm (2.70% of base)

Top file improvements (bytes):
        -192 : 225172.dasm (-2.94% of base)
        -192 : 225201.dasm (-2.94% of base)
        -192 : 225202.dasm (-2.94% of base)
        -168 : 225473.dasm (-3.15% of base)
        -168 : 225476.dasm (-3.15% of base)
        -144 : 225553.dasm (-3.07% of base)
        -144 : 225058.dasm (-2.82% of base)
        -132 : 227941.dasm (-1.34% of base)
        -120 : 227886.dasm (-1.21% of base)
        -120 : 228077.dasm (-1.25% of base)
        -112 : 227988.dasm (-1.10% of base)
        -108 : 228034.dasm (-1.09% of base)
        -108 : 227761.dasm (-1.11% of base)
        -100 : 227830.dasm (-0.98% of base)
         -80 : 216447.dasm (-2.55% of base)
         -80 : 194765.dasm (-3.47% of base)
         -80 : 224761.dasm (-0.43% of base)
         -64 : 234494.dasm (-0.23% of base)
         -60 : 167230.dasm (-0.46% of base)
         -56 : 216442.dasm (-7.29% of base)

853 total files with Code Size differences (852 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
         472 ( 2.70% of base) : 224771.dasm - lclfldmul:Main():int

Top method improvements (bytes):
        -192 (-2.94% of base) : 225172.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -192 (-2.94% of base) : 225201.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -192 (-2.94% of base) : 225202.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -168 (-3.15% of base) : 225473.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -168 (-3.15% of base) : 225476.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -144 (-3.07% of base) : 225553.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -144 (-2.82% of base) : 225058.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
        -132 (-1.34% of base) : 227941.dasm - TestApp:Main():int
        -120 (-1.21% of base) : 227886.dasm - TestApp:Main():int
        -120 (-1.25% of base) : 228077.dasm - TestApp:Main():int
        -112 (-1.10% of base) : 227988.dasm - TestApp:Main():int
        -108 (-1.09% of base) : 228034.dasm - TestApp:Main():int
        -108 (-1.11% of base) : 227761.dasm - TestApp:Main():int
        -100 (-0.98% of base) : 227830.dasm - TestApp:Main():int
         -80 (-2.55% of base) : 216447.dasm - IntelHardwareIntrinsicTest:Main():int
         -80 (-3.47% of base) : 194765.dasm - Huffman:DoHuffIteration(System.Byte[],System.Byte[],System.Byte[],int,int,huff_node[]):long
         -80 (-0.43% of base) : 224761.dasm - lclfldmul:Main():int
         -64 (-0.23% of base) : 234494.dasm - StrAccess2:Main():int
         -60 (-0.46% of base) : 167230.dasm - Internal.IL.ILImporter:ImportBasicBlock(BasicBlock):this
         -56 (-7.29% of base) : 216442.dasm - IntelHardwareIntrinsicTest:Vector128Int16ReturnTest():int

Top method regressions (percentages):
         472 ( 2.70% of base) : 224771.dasm - lclfldmul:Main():int

Top method improvements (percentages):
         -20 (-41.67% of base) : 194671.dasm - LongMulOn32BitTest:LongMul_60(int,int):long
         -20 (-41.67% of base) : 194688.dasm - LongMulOn32BitTest:LongMul_14(int,int):long
         -16 (-33.33% of base) : 194667.dasm - LongMulOn32BitTest:LongMul_56(int):long
         -16 (-33.33% of base) : 194668.dasm - LongMulOn32BitTest:LongMul_57(int):long
         -16 (-33.33% of base) : 194652.dasm - LongMulOn32BitTest:LongMul_41(int):long
         -16 (-33.33% of base) : 194653.dasm - LongMulOn32BitTest:LongMul_42(int):long
         -16 (-33.33% of base) : 194676.dasm - LongMulOn32BitTest:LongMul_2(int):long
         -16 (-33.33% of base) : 194679.dasm - LongMulOn32BitTest:LongMul_5(int):long
         -16 (-33.33% of base) : 194685.dasm - LongMulOn32BitTest:LongMul_11(int):long
         -16 (-33.33% of base) : 194700.dasm - LongMulOn32BitTest:LongMul_26(int):long
          -8 (-28.57% of base) : 194669.dasm - LongMulOn32BitTest:LongMul_58(int,int):long
          -8 (-28.57% of base) : 194687.dasm - LongMulOn32BitTest:LongMul_13(int,int):long
          -8 (-28.57% of base) : 6661.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWidening(int,int):long
          -8 (-28.57% of base) : 6730.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWidening(int,int):long
          -8 (-25.00% of base) : 108917.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(long,int,int):long
          -8 (-25.00% of base) : 108967.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long
          -8 (-25.00% of base) : 116332.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(long,int,int):long
          -8 (-25.00% of base) : 120510.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long
          -8 (-25.00% of base) : 176300.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(long,int,int):long
          -8 (-25.00% of base) : 176301.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long

853 total methods with Code Size differences (852 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 617252
Total bytes of diff: 610896
Total bytes of delta: -6356 (-1.03% of base)
Total relative delta: -15.31
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -304 : 145350.dasm (-3.47% of base)
        -176 : 145345.dasm (-3.41% of base)
        -128 : 52804.dasm (-11.51% of base)
        -124 : 145346.dasm (-2.17% of base)
         -56 : 161964.dasm (-3.10% of base)
         -44 : 145351.dasm (-3.30% of base)
         -44 : 145352.dasm (-3.30% of base)
         -40 : 161967.dasm (-2.72% of base)
         -36 : 101941.dasm (-3.41% of base)
         -36 : 217002.dasm (-1.82% of base)
         -36 : 52808.dasm (-1.79% of base)
         -32 : 34783.dasm (-1.23% of base)
         -32 : 34785.dasm (-1.92% of base)
         -32 : 52803.dasm (-2.90% of base)
         -28 : 217001.dasm (-2.28% of base)
         -28 : 142663.dasm (-0.69% of base)
         -24 : 145336.dasm (-4.08% of base)
         -24 : 131079.dasm (-2.65% of base)
         -20 : 145334.dasm (-3.11% of base)
         -20 : 145337.dasm (-4.17% of base)

825 total files with Code Size differences (825 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -304 (-3.47% of base) : 145350.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
        -176 (-3.41% of base) : 145345.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
        -128 (-11.51% of base) : 52804.dasm - DecCalc:VarDecMul(byref,byref)
        -124 (-2.17% of base) : 145346.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -56 (-3.10% of base) : 161964.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
         -44 (-3.30% of base) : 145351.dasm - System.Data.RBTree`1:RightRotate(int,int,int):int:this
         -44 (-3.30% of base) : 145352.dasm - System.Data.RBTree`1:LeftRotate(int,int,int):int:this
         -40 (-2.72% of base) : 161967.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)
         -36 (-3.41% of base) : 101941.dasm - PastEventInfo:LogEvent(Microsoft.Diagnostics.Tracing.TraceEvent,int,Microsoft.Diagnostics.Tracing.Etlx.TraceEventCounts):this
         -36 (-1.82% of base) : 217002.dasm - Microsoft.VisualBasic.CompilerServices.LikeOperator:BuildPatternGroups(System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],byref,byref,System.Globalization.CompareInfo,int,byref)
         -36 (-1.79% of base) : 52808.dasm - DecCalc:DecAddSub(byref,byref,bool)
         -32 (-1.23% of base) : 34783.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
         -32 (-1.92% of base) : 34785.dasm - System.Diagnostics.Tracing.EventSource:WriteMultiMergeInner(System.String,byref,System.Diagnostics.Tracing.TraceLoggingEventTypes,long,long,System.Object[]):this
         -32 (-2.90% of base) : 52803.dasm - DecCalc:VarDecFromR4(float,byref)
         -28 (-2.28% of base) : 217001.dasm - Microsoft.VisualBasic.CompilerServices.LikeOperator:MatchAsterisk(System.String,int,int,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],System.String,int,int,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],byref,byref,System.Globalization.CompareInfo,int)
         -28 (-0.69% of base) : 142663.dasm - System.Data.Common.SqlDecimalStorage:Aggregate(System.Int32[],int):System.Object:this
         -24 (-4.08% of base) : 145336.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
         -24 (-2.65% of base) : 131079.dasm - System.Xml.XmlTextWriter:WriteEndStartTag(bool):this
         -20 (-3.11% of base) : 145334.dasm - System.Data.RBTree`1:ComputeNodeByIndex(int,byref):int:this
         -20 (-4.17% of base) : 145337.dasm - System.Data.RBTree`1:ComputeIndexByNode(int):int:this

Top method improvements (percentages):
          -8 (-28.57% of base) : 52822.dasm - DecCalc:UInt32x32To64(int,int):long
          -8 (-28.57% of base) : 52547.dasm - System.Math:BigMul(int,int):long
         -16 (-25.00% of base) : 153070.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -8 (-20.00% of base) : 126451.dasm - System.Xml.Xsl.XPathConvert:MulU(int,int,byref):int
          -8 (-18.18% of base) : 39766.dasm - System.Runtime.InteropServices.SafeBuffer:Initialize(int,int):this
         -20 (-12.20% of base) : 216740.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyInt32(int,int):System.Object
         -20 (-12.20% of base) : 216893.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:MulInt32(int,int):System.Object
        -128 (-11.51% of base) : 52804.dasm - DecCalc:VarDecMul(byref,byref)
          -8 (-11.11% of base) : 39661.dasm - System.Runtime.CompilerServices.RuntimeHelpers:GetRawObjectDataSize(System.Object):long
          -8 (-10.53% of base) : 151175.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161Accuracy:get_TotalMicros():long:this
          -4 (-10.00% of base) : 144360.dasm - System.Data.SqlTypes.SqlMoney:.ctor(int):this
          -4 (-10.00% of base) : 39690.dasm - System.Runtime.CompilerServices.CastHelpers:Element(byref,int):byref
         -16 (-9.76% of base) : 196553.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
         -16 (-8.70% of base) : 216174.dasm - Microsoft.VisualBasic.DateAndTime:TimeSerial(int,int,int):System.DateTime
         -16 (-6.90% of base) : 215692.dasm - Microsoft.VisualBasic.VBMath:Rnd(float):float
          -8 (-6.45% of base) : 47149.dasm - System.TimeSpan:TimeToTicks(int,int,int):long
          -8 (-6.25% of base) : 153986.dasm - System.Data.OleDb.Bindings:GuidKindName(System.Guid,int,long):this
          -8 (-6.25% of base) : 47184.dasm - System.TimeSpan:.ctor(int,int,int):this
         -20 (-6.10% of base) : 216739.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyUInt32(int,int):System.Object
         -16 (-5.97% of base) : 217249.dasm - FixedList:MoveToFront(int):this

825 total methods with Code Size differences (825 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1269724
Total bytes of diff: 1258324
Total bytes of delta: -11400 (-0.90% of base)
Total relative delta: -22.30
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -304 : 110802.dasm (-3.51% of base)
        -236 : 85747.dasm (-6.09% of base)
        -176 : 110807.dasm (-3.51% of base)
        -136 : 110806.dasm (-2.47% of base)
         -92 : 29694.dasm (-1.23% of base)
         -72 : 24487.dasm (-1.50% of base)
         -68 : 68738.dasm (-1.65% of base)
         -64 : 227578.dasm (-0.99% of base)
         -56 : 31759.dasm (-1.04% of base)
         -56 : 63929.dasm (-1.03% of base)
         -56 : 209800.dasm (-3.66% of base)
         -56 : 72289.dasm (-0.91% of base)
         -56 : 79007.dasm (-2.24% of base)
         -52 : 31265.dasm (-0.78% of base)
         -52 : 24488.dasm (-1.61% of base)
         -52 : 52621.dasm (-0.82% of base)
         -44 : 110800.dasm (-3.36% of base)
         -44 : 110801.dasm (-3.36% of base)
         -40 : 68734.dasm (-1.48% of base)
         -40 : 209797.dasm (-2.96% of base)

1438 total files with Code Size differences (1438 improved, 0 regressed), 3 unchanged.

Top method improvements (bytes):
        -304 (-3.51% of base) : 110802.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBInsert(int,int,int,int,bool):int:this
        -236 (-6.09% of base) : 85747.dasm - Microsoft.Diagnostics.Tracing.Session.TraceEventSession:SetStackTraceIds(int,long,int):int
        -176 (-3.51% of base) : 110807.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
        -136 (-2.47% of base) : 110806.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -92 (-1.23% of base) : 29694.dasm - Microsoft.CodeAnalysis.CSharp.SymbolDisplayVisitor:VisitMethod(Microsoft.CodeAnalysis.IMethodSymbol):this
         -72 (-1.50% of base) : 24487.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:GetEnumOperation(int,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[BinaryOperatorSignature]):this
         -68 (-1.65% of base) : 68738.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:AddMethodKind(Microsoft.CodeAnalysis.IMethodSymbol):this
         -64 (-0.99% of base) : 227578.dasm - ILCompiler.DependencyAnalysis.NodeFactory:AttachToDependencyGraph(ILCompiler.DependencyAnalysisFramework.DependencyAnalyzerBase`1[[ILCompiler.DependencyAnalysis.NodeFactory, ILCompiler.ReadyToRun, Version=6.0.0.0, Culture=neutral, PublicKeyToken=null]]):this
         -56 (-1.04% of base) : 31759.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:RewriteTrivia(Microsoft.CodeAnalysis.SyntaxTriviaList,int,bool,bool,bool,int):Microsoft.CodeAnalysis.SyntaxTriviaList:this
         -56 (-1.03% of base) : 63929.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:RewriteTrivia(Microsoft.CodeAnalysis.SyntaxTriviaList,int,bool,bool,bool,int,int):Microsoft.CodeAnalysis.SyntaxTriviaList:this
         -56 (-3.66% of base) : 209800.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
         -56 (-0.91% of base) : 72289.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicDeclarationComputer:ComputeDeclarationsCore(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,System.Collections.Generic.List`1[DeclarationInfo],System.Nullable`1[Int32],System.Threading.CancellationToken)
         -56 (-2.24% of base) : 79007.dasm - Microsoft.CodeAnalysis.SyntaxDiffer:GetNextAction():DiffAction:this
         -52 (-0.78% of base) : 31265.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:ComputeDeclarations(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,System.Collections.Generic.List`1[DeclarationInfo],System.Nullable`1[Int32],System.Threading.CancellationToken)
         -52 (-1.61% of base) : 24488.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:GetPointerArithmeticOperators(int,Microsoft.CodeAnalysis.CSharp.Symbols.PointerTypeSymbol,Microsoft.CodeAnalysis.ArrayBuilder`1[BinaryOperatorSignature]):this
         -52 (-0.82% of base) : 52621.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ConstraintsHelper:RemoveDirectConstraintConflicts(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol,System.Collections.Immutable.ImmutableArray`1[TypeParameterConstraint],Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterDiagnosticInfo]):System.Collections.Immutable.ImmutableArray`1[TypeParameterConstraint]
         -44 (-3.36% of base) : 110800.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:LeftRotate(int,int,int):int:this
         -44 (-3.36% of base) : 110801.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RightRotate(int,int,int):int:this
         -40 (-1.48% of base) : 68734.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:VisitProperty(Microsoft.CodeAnalysis.IPropertySymbol):this
         -40 (-2.96% of base) : 209797.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)

Top method improvements (percentages):
         -16 (-30.77% of base) : 168603.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -8 (-20.00% of base) : 131329.dasm - System.Xml.Xsl.XPathConvert:MulU(int,int,byref):int
          -8 (-15.38% of base) : 19680.dasm - System.Runtime.InteropServices.SafeBuffer:Initialize(int):this
         -20 (-13.16% of base) : 148790.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:MulInt32(int,int):System.Object
         -20 (-13.16% of base) : 148874.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyInt32(int,int):System.Object
         -16 (-12.50% of base) : 168515.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
          -4 (-11.11% of base) : 175573.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_PingWaitTimeout():System.TimeSpan:this
          -8 (-10.53% of base) : 215284.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161Accuracy:get_TotalMicros():long:this
          -4 (-10.00% of base) : 111993.dasm - System.Data.SqlTypes.SqlMoney:.ctor(int):this
          -4 (-10.00% of base) : 175528.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_SendTimeout():System.TimeSpan:this
          -4 (-10.00% of base) : 175569.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_PingKeepAliveTimeout():System.TimeSpan:this
         -16 (-9.30% of base) : 149520.dasm - Microsoft.VisualBasic.DateAndTime:TimeSerial(int,int,int):System.DateTime
          -8 (-6.90% of base) : 169992.dasm - System.Data.OleDb.Bindings:GuidKindName(System.Guid,int,long):this
          -8 (-6.67% of base) : 215124.dasm - System.Security.Cryptography.Pkcs.Rfc3161TimestampTokenInfo:get_AccuracyInMicroseconds():System.Nullable`1[Int64]:this
         -16 (-6.56% of base) : 150012.dasm - Microsoft.VisualBasic.VBMath:Rnd(float):float
          -8 (-6.45% of base) : 113653.dasm - System.Data.Common.SqlDateTimeStorage:Compare(int,int):int:this
          -8 (-6.45% of base) : 113656.dasm - System.Data.Common.SqlDateTimeStorage:Copy(int,int):this
          -8 (-6.45% of base) : 113667.dasm - System.Data.Common.SqlDecimalStorage:Compare(int,int):int:this
          -4 (-6.25% of base) : 186071.dasm - DebugView:<GetInstructionViews>b__4_0(int):int:this
         -16 (-6.25% of base) : 148406.dasm - FixedList:MoveToFront(int):this

1438 total methods with Code Size differences (1438 improved, 0 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1875064
Total bytes of diff: 1862956
Total bytes of delta: -12108 (-0.65% of base)
Total relative delta: -14.59
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -156 : 159959.dasm (-1.64% of base)
        -152 : 159791.dasm (-1.40% of base)
        -144 : 159832.dasm (-1.07% of base)
        -132 : 159790.dasm (-1.26% of base)
        -104 : 336882.dasm (-2.91% of base)
         -88 : 129011.dasm (-1.98% of base)
         -88 : 159792.dasm (-1.16% of base)
         -84 : 159169.dasm (-1.28% of base)
         -72 : 159876.dasm (-1.18% of base)
         -68 : 159889.dasm (-1.30% of base)
         -64 : 159347.dasm (-1.40% of base)
         -60 : 159407.dasm (-1.70% of base)
         -60 : 159877.dasm (-1.11% of base)
         -60 : 160102.dasm (-0.65% of base)
         -60 : 159887.dasm (-1.32% of base)
         -56 : 201475.dasm (-1.97% of base)
         -56 : 159174.dasm (-1.07% of base)
         -56 : 159175.dasm (-1.06% of base)
         -56 : 159883.dasm (-1.31% of base)
         -56 : 159436.dasm (-0.57% of base)

1407 total files with Code Size differences (1407 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -156 (-1.64% of base) : 159959.dasm - System.Data.Tests.DataTableTest:ImportRowTest():this
        -152 (-1.40% of base) : 159791.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestOverwriteChanges():this
        -144 (-1.07% of base) : 159832.dasm - System.Data.Tests.DataTableReaderTest:TestSchemaTable():this
        -132 (-1.26% of base) : 159790.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestUpsert():this
        -104 (-2.91% of base) : 336882.dasm - System.Xml.Tests.ToTypeTests:ToType57():int:this
         -88 (-1.98% of base) : 129011.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:AsModifierList(int,Microsoft.CodeAnalysis.Editing.DeclarationModifiers):Microsoft.CodeAnalysis.SyntaxTokenList
         -88 (-1.16% of base) : 159792.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestPreserveChanges():this
         -84 (-1.28% of base) : 159169.dasm - System.Data.Tests.DataColumnTest:ExpressionOperator():this
         -72 (-1.18% of base) : 159876.dasm - System.Data.Tests.DataTableTest:Load_MissingColsDefault():this
         -68 (-1.30% of base) : 159889.dasm - System.Data.Tests.DataTableTest:Load_RowStateUpsertDuplicateKey1():this
         -64 (-1.40% of base) : 159347.dasm - System.Data.Tests.DataRowTest:ParentRowTest():this
         -60 (-1.70% of base) : 159407.dasm - System.Data.Tests.DataRowTest2:TestRowErrors():this
         -60 (-1.11% of base) : 159877.dasm - System.Data.Tests.DataTableTest:Load_MissingColsNullable():this
         -60 (-0.65% of base) : 160102.dasm - System.Data.Tests.DataTableTest4:XmlTest9():this
         -60 (-1.32% of base) : 159887.dasm - System.Data.Tests.DataTableTest:Load_RowStateOverwriteChanges():this
         -56 (-1.97% of base) : 201475.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:ValidateGenericParamTable():this
         -56 (-1.07% of base) : 159174.dasm - System.Data.Tests.DataColumnTest:Aggregation_CheckIfChangesDynamically():this
         -56 (-1.06% of base) : 159175.dasm - System.Data.Tests.DataColumnTest:Aggregation_CheckIfChangesDynamically_ChildTable():this
         -56 (-1.31% of base) : 159883.dasm - System.Data.Tests.DataTableTest:Load_RowStateChangesDefault():this
         -56 (-0.57% of base) : 159436.dasm - System.Data.Tests.DataRowTest2:Indexer1_Value_Null():this

Top method improvements (percentages):
         -16 (-30.77% of base) : 234828.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -4 (-14.29% of base) : 236902.dasm - System.Data.SqlClient.TdsParserStateObject:SetTimeoutSeconds(int):this
          -4 (-14.29% of base) : 241178.dasm - System.Data.SqlClient.TdsParserStateObject:SetTimeoutSeconds(int):this
          -8 (-12.50% of base) : 82262.dasm - System.Text.Encodings.Web.Tests.EncoderCommon:GetCapacityOfOutputStringBuilder(int,int):int
         -16 (-9.30% of base) : 238989.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
         -16 (-9.30% of base) : 234691.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
          -8 (-9.09% of base) : 141672.dasm - NuGet.Packaging.Signing.Accuracy:GetTotalMicroseconds():System.Nullable`1[Int64]:this
         -16 (-7.84% of base) : 236945.dasm - System.Data.SqlClient.TdsParserStaticMethods:GetRemainingTimeout(int,long):int
         -16 (-7.84% of base) : 241221.dasm - System.Data.SqlClient.TdsParserStaticMethods:GetRemainingTimeout(int,long):int
          -4 (-7.14% of base) : 135525.dasm - Microsoft.Diagnostics.Runtime.Utilities.MINIDUMP_MODULE:get_Timestamp():System.DateTime:this
          -4 (-5.88% of base) : 342172.dasm - Unity.Storage.MiniHashSet`1[Byte][System.Byte]:get_Item(int):ubyte:this
          -4 (-5.88% of base) : 342184.dasm - Unity.Storage.MiniHashSet`1[Int16][System.Int16]:get_Item(int):short:this
          -4 (-5.88% of base) : 342189.dasm - Unity.Storage.MiniHashSet`1[Int32][System.Int32]:get_Item(int):int:this
          -4 (-5.88% of base) : 342194.dasm - Unity.Storage.MiniHashSet`1[Double][System.Double]:get_Item(int):double:this
          -4 (-5.88% of base) : 342204.dasm - Unity.Storage.MiniHashSet`1[Int64][System.Int64]:get_Item(int):long:this
          -4 (-4.76% of base) : 187101.dasm - <>c:<CastReadOnlySpanOverflow>b__19_0(System.ReadOnlySpan`1[TestStructExplicit]):this
          -4 (-4.76% of base) : 187105.dasm - <>c:<CastSpanOverflow>b__26_0(System.Span`1[TestStructExplicit]):this
          -4 (-4.55% of base) : 187102.dasm - <>c:<CastReadOnlySpanOverflow>b__19_1(System.ReadOnlySpan`1[TestStructExplicit]):this
          -4 (-4.55% of base) : 187106.dasm - <>c:<CastSpanOverflow>b__26_1(System.Span`1[TestStructExplicit]):this
         -16 (-4.12% of base) : 257515.dasm - Microsoft.Build.Shared.NativeMethodsShared:GetFullPath(System.String):System.String

1407 total methods with Code Size differences (1407 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------
