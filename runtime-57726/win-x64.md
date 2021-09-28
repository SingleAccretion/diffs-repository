## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 224392
Total bytes of diff: 221938
Total bytes of delta: -2454 (-1.09% of base)
Total relative delta: -34.77
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          18 : 856.dasm (2.55% of base)
           5 : 3090.dasm (0.11% of base)
           4 : 3386.dasm (0.15% of base)
           1 : 3376.dasm (0.11% of base)

Top file improvements (bytes):
         -79 : 10157.dasm (-7.37% of base)
         -52 : 24535.dasm (-8.52% of base)
         -41 : 4803.dasm (-3.71% of base)
         -38 : 20888.dasm (-3.45% of base)
         -35 : 18386.dasm (-0.88% of base)
         -35 : 15271.dasm (-3.37% of base)
         -32 : 9490.dasm (-3.46% of base)
         -31 : 14023.dasm (-3.06% of base)
         -29 : 15274.dasm (-4.54% of base)
         -26 : 2973.dasm (-1.55% of base)
         -24 : 10808.dasm (-3.67% of base)
         -23 : 21774.dasm (-2.79% of base)
         -22 : 18265.dasm (-2.20% of base)
         -20 : 11474.dasm (-3.12% of base)
         -19 : 16091.dasm (-2.59% of base)
         -18 : 16333.dasm (-2.88% of base)
         -18 : 14024.dasm (-3.11% of base)
         -17 : 11552.dasm (-5.80% of base)
         -16 : 9024.dasm (-2.14% of base)
         -16 : 2509.dasm (-0.27% of base)

345 total files with Code Size differences (341 improved, 4 regressed), 28 unchanged.

Top method regressions (bytes):
          18 ( 2.55% of base) : 856.dasm - System.Collections.Concurrent.ConcurrentQueueSegment`1[__Canon][System.__Canon]:.ctor(int):this
           5 ( 0.11% of base) : 3090.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)
           4 ( 0.15% of base) : 3386.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           1 ( 0.11% of base) : 3376.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this

Top method improvements (bytes):
         -79 (-7.37% of base) : 10157.dasm - ImageTestData:CreateTestImage(System.Drawing.Imaging.ImageFormat):System.IO.Stream
         -52 (-8.52% of base) : 24535.dasm - System.Drawing.Tests.Perf_Graphics_DrawBeziers:Setup():this
         -41 (-3.71% of base) : 4803.dasm - <GetOptions>d__5:MoveNext():bool:this
         -38 (-3.45% of base) : 20888.dasm - Microsoft.Extensions.Logging.EventSource.LoggingEventSource:ParseFilterSpec(System.String,int):Microsoft.Extensions.Logging.LoggerFilterRule[]
         -35 (-0.88% of base) : 18386.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -35 (-3.37% of base) : 15271.dasm - BoundedChannelWriter[__Canon][System.__Canon]:WriteAsync(System.__Canon,System.Threading.CancellationToken):System.Threading.Tasks.ValueTask:this
         -32 (-3.46% of base) : 9490.dasm - Jil.Common.Utils:_ReadFieldOperands(System.Reflection.Emit.OpCode,System.Byte[],int,int,byref,byref,byref,byref):System.Nullable`1[Int32]
         -31 (-3.06% of base) : 14023.dasm - BoundedChannelWriter[Int32][System.Int32]:WriteAsync(int,System.Threading.CancellationToken):System.Threading.Tasks.ValueTask:this
         -29 (-4.54% of base) : 15274.dasm - BoundedChannelReader[__Canon][System.__Canon]:WaitToReadAsync(System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Boolean]:this
         -26 (-1.55% of base) : 2973.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:SetPropertySettingsFromAttributes(Newtonsoft.Json.Serialization.JsonProperty,System.Object,System.String,System.Type,int,byref):this
         -24 (-3.67% of base) : 10808.dasm - EMFloat:Run():double:this
         -23 (-2.79% of base) : 21774.dasm - UnboundedChannelReader[Int32][System.Int32]:ReadAsync(System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -22 (-2.20% of base) : 18265.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:ClassifyImplicitBuiltInConversionFromExpression(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):Microsoft.CodeAnalysis.CSharp.Conversion:this
         -20 (-3.12% of base) : 11474.dasm - System.IO.Strategies.OSFileStreamStrategy:ReadAsync(System.Memory`1[Byte],System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -19 (-2.59% of base) : 16091.dasm - UnboundedChannelReader[Int32][System.Int32]:ReadAsync(System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -18 (-2.88% of base) : 16333.dasm - System.IO.Pipelines.Pipe:PrepareFlush(byref,byref,System.Threading.CancellationToken):this
         -18 (-3.11% of base) : 14024.dasm - BoundedChannelReader[Int32][System.Int32]:ReadAsync(System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -17 (-5.80% of base) : 11552.dasm - System.Numerics.BigNumber:TryParseBigInteger(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):bool
         -16 (-2.14% of base) : 9024.dasm - System.IO.MemoryStream:ReadAsync(System.Memory`1[Byte],System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -16 (-0.27% of base) : 2509.dasm - Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder:BuildSerialize(System.Type,Utf8Json.Internal.Emit.MetaType,System.Reflection.Emit.ILGenerator,System.Action,System.Func`3[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Utf8Json.Internal.Emit.MetaMember, Utf8Json, Version=1.3.7.0, Culture=neutral, PublicKeyToken=8a73d3ba7e392e27],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,int)

Top method regressions (percentages):
          18 ( 2.55% of base) : 856.dasm - System.Collections.Concurrent.ConcurrentQueueSegment`1[__Canon][System.__Canon]:.ctor(int):this
           4 ( 0.15% of base) : 3386.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           1 ( 0.11% of base) : 3376.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           5 ( 0.11% of base) : 3090.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)

Top method improvements (percentages):
          -4 (-26.67% of base) : 1351.dasm - MessagePack.KeyAttribute:.ctor(int):this
          -7 (-21.88% of base) : 4541.dasm - System.Drawing.Color:get_DarkOrange():System.Drawing.Color
          -7 (-21.88% of base) : 4542.dasm - System.Drawing.Color:get_DarkOrchid():System.Drawing.Color
          -7 (-21.88% of base) : 4555.dasm - System.Drawing.Color:get_FloralWhite():System.Drawing.Color
          -7 (-21.88% of base) : 4556.dasm - System.Drawing.Color:get_ForestGreen():System.Drawing.Color
          -7 (-21.88% of base) : 4575.dasm - System.Drawing.Color:get_LightBlue():System.Drawing.Color
          -7 (-21.88% of base) : 4576.dasm - System.Drawing.Color:get_LightCoral():System.Drawing.Color
          -7 (-21.88% of base) : 4593.dasm - System.Drawing.Color:get_MediumAquamarine():System.Drawing.Color
          -7 (-21.88% of base) : 4594.dasm - System.Drawing.Color:get_MediumBlue():System.Drawing.Color
          -7 (-21.88% of base) : 4595.dasm - System.Drawing.Color:get_MediumOrchid():System.Drawing.Color
          -7 (-21.88% of base) : 4596.dasm - System.Drawing.Color:get_MediumPurple():System.Drawing.Color
          -7 (-21.88% of base) : 4624.dasm - System.Drawing.Color:get_Purple():System.Drawing.Color
          -7 (-21.88% of base) : 4625.dasm - System.Drawing.Color:get_Red():System.Drawing.Color
          -7 (-21.88% of base) : 4626.dasm - System.Drawing.Color:get_RosyBrown():System.Drawing.Color
          -7 (-21.88% of base) : 4627.dasm - System.Drawing.Color:get_RoyalBlue():System.Drawing.Color
          -7 (-21.88% of base) : 4537.dasm - System.Drawing.Color:get_DarkGreen():System.Drawing.Color
          -7 (-21.88% of base) : 4538.dasm - System.Drawing.Color:get_DarkKhaki():System.Drawing.Color
          -7 (-21.88% of base) : 4569.dasm - System.Drawing.Color:get_Ivory():System.Drawing.Color
          -7 (-21.88% of base) : 4570.dasm - System.Drawing.Color:get_Khaki():System.Drawing.Color
          -7 (-21.88% of base) : 4597.dasm - System.Drawing.Color:get_MediumSeaGreen():System.Drawing.Color

345 total methods with Code Size differences (341 improved, 4 regressed), 28 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1531951
Total bytes of diff: 1529716
Total bytes of delta: -2235 (-0.15% of base)
Total relative delta: -12.95
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 169004.dasm (0.39% of base)
           8 : 169002.dasm (0.39% of base)
           8 : 169006.dasm (0.39% of base)
           6 : 169000.dasm (0.14% of base)
           4 : 70.dasm (0.15% of base)
           2 : 213599.dasm (0.50% of base)
           1 : 36.dasm (0.11% of base)
           1 : 247152.dasm (0.32% of base)

Top file improvements (bytes):
         -88 : 219212.dasm (-18.33% of base)
         -71 : 219425.dasm (-12.57% of base)
         -58 : 228256.dasm (-12.55% of base)
         -58 : 227832.dasm (-11.74% of base)
         -51 : 227862.dasm (-10.69% of base)
         -28 : 171307.dasm (-1.24% of base)
         -28 : 171174.dasm (-1.24% of base)
         -24 : 172593.dasm (-1.04% of base)
         -24 : 172600.dasm (-1.04% of base)
         -24 : 195072.dasm (-3.67% of base)
         -21 : 246709.dasm (-10.66% of base)
         -20 : 167741.dasm (-2.79% of base)
         -18 : 240675.dasm (-4.64% of base)
         -12 : 213147.dasm (-5.74% of base)
         -12 : 86754.dasm (-5.61% of base)
         -12 : 234585.dasm (-2.93% of base)
         -12 : 231083.dasm (-2.84% of base)
         -12 : 230797.dasm (-2.84% of base)
         -11 : 169097.dasm (-0.29% of base)
         -11 : 224113.dasm (-0.58% of base)

432 total files with Code Size differences (424 improved, 8 regressed), 59 unchanged.

Top method regressions (bytes):
           8 ( 0.39% of base) : 169004.dasm - Managed:MarshalStructAsParam_AsExpByValOut(int)
           8 ( 0.39% of base) : 169002.dasm - Managed:MarshalStructAsParam_AsExpByValIn(int)
           8 ( 0.39% of base) : 169006.dasm - Managed:MarshalStructAsParam_AsExpByValInOut(int)
           6 ( 0.14% of base) : 169000.dasm - Managed:MarshalStructAsParam_AsExpByVal(int)
           4 ( 0.15% of base) : 70.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           2 ( 0.50% of base) : 213599.dasm - StructABI:EchoSingleByteWrapper():bool
           1 ( 0.11% of base) : 36.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           1 ( 0.32% of base) : 247152.dasm - Test:Main():int

Top method improvements (bytes):
         -88 (-18.33% of base) : 219212.dasm - AA:reset()
         -71 (-12.57% of base) : 219425.dasm - AA:reset()
         -58 (-12.55% of base) : 228256.dasm - AA:reset()
         -58 (-11.74% of base) : 227832.dasm - AA:reset()
         -51 (-10.69% of base) : 227862.dasm - AA:reset()
         -28 (-1.24% of base) : 171307.dasm - NullableTest30:Run()
         -28 (-1.24% of base) : 171174.dasm - NullableTest23:Run()
         -24 (-1.04% of base) : 172593.dasm - NullableTest23:Run()
         -24 (-1.04% of base) : 172600.dasm - NullableTest30:Run()
         -24 (-3.67% of base) : 195072.dasm - EMFloat:Run():double:this
         -21 (-10.66% of base) : 246709.dasm - Program:Test():this
         -20 (-2.79% of base) : 167741.dasm - Internal.IL.ILImporter:FindEnclosingExceptionRegions():this
         -18 (-4.64% of base) : 240675.dasm - AllTypesNullable:.ctor(bool):this
         -12 (-5.74% of base) : 213147.dasm - NetClient.ColorTests:VerifyColorMarshalling():this
         -12 (-5.61% of base) : 86754.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,long,ushort,ubyte,short,int):short
         -12 (-2.93% of base) : 234585.dasm - Test:TestVariantBool()
         -12 (-2.84% of base) : 231083.dasm - NullableTest:Main():int
         -12 (-2.84% of base) : 230797.dasm - NullableTest:Main():int
         -11 (-0.29% of base) : 169097.dasm - Managed:MarshalStructAsParam_AsSeqByRefOut(int)
         -11 (-0.58% of base) : 224113.dasm - SoDBench.Program:Main(System.String[])

Top method regressions (percentages):
           2 ( 0.50% of base) : 213599.dasm - StructABI:EchoSingleByteWrapper():bool
           8 ( 0.39% of base) : 169004.dasm - Managed:MarshalStructAsParam_AsExpByValOut(int)
           8 ( 0.39% of base) : 169002.dasm - Managed:MarshalStructAsParam_AsExpByValIn(int)
           8 ( 0.39% of base) : 169006.dasm - Managed:MarshalStructAsParam_AsExpByValInOut(int)
           1 ( 0.32% of base) : 247152.dasm - Test:Main():int
           4 ( 0.15% of base) : 70.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           6 ( 0.14% of base) : 169000.dasm - Managed:MarshalStructAsParam_AsExpByVal(int)
           1 ( 0.11% of base) : 36.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this

Top method improvements (percentages):
          -4 (-25.00% of base) : 224105.dasm - SoDBench.SizeReportingNode:set_Size(long):this
          -8 (-24.24% of base) : 216521.dasm - TestStruct:Create():TestStruct
          -7 (-21.88% of base) : 212946.dasm - ColorTesting:GetRed():System.Drawing.Color:this
         -88 (-18.33% of base) : 219212.dasm - AA:reset()
          -4 (-16.00% of base) : 213504.dasm - ByteAndDouble:Get():ByteAndDouble
          -4 (-16.00% of base) : 213506.dasm - DoubleAndByte:Get():DoubleAndByte
          -4 (-12.90% of base) : 213508.dasm - PointerAndByte:Get():PointerAndByte
          -4 (-12.90% of base) : 213510.dasm - ByteAndPointer:Get():ByteAndPointer
         -71 (-12.57% of base) : 219425.dasm - AA:reset()
         -58 (-12.55% of base) : 228256.dasm - AA:reset()
         -58 (-11.74% of base) : 227832.dasm - AA:reset()
          -3 (-11.54% of base) : 216523.dasm - TestStruct:Create():TestStruct
          -7 (-11.29% of base) : 81934.dasm - Repro:ReturnsS():S
          -7 (-11.29% of base) : 252649.dasm - Repro:ReturnsS():S
         -10 (-10.75% of base) : 251800.dasm - Test.Setting:ForBool(System.String):Test.Setting`1[Nullable`1]
         -51 (-10.69% of base) : 227862.dasm - AA:reset()
          -8 (-10.67% of base) : 213542.dasm - Nested2:Get():Nested2
         -21 (-10.66% of base) : 246709.dasm - Program:Test():this
          -4 (-10.53% of base) : 213512.dasm - ByteFloatAndPointer:Get():ByteFloatAndPointer
          -4 (-10.53% of base) : 213514.dasm - PointerFloatAndByte:Get():PointerFloatAndByte

432 total methods with Code Size differences (424 improved, 8 regressed), 59 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 242296
Total bytes of diff: 237584
Total bytes of delta: -4712 (-1.94% of base)
Total relative delta: -49.05
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 2141.dasm (0.27% of base)
           2 : 2142.dasm (0.28% of base)
           1 : 2159.dasm (0.32% of base)
           1 : 183891.dasm (0.41% of base)

Top file improvements (bytes):
        -503 : 175110.dasm (-3.78% of base)
        -210 : 205806.dasm (-5.66% of base)
        -178 : 205810.dasm (-7.88% of base)
        -129 : 35141.dasm (-19.28% of base)
         -55 : 21803.dasm (-2.85% of base)
         -54 : 86247.dasm (-6.59% of base)
         -43 : 57265.dasm (-0.26% of base)
         -38 : 207056.dasm (-2.11% of base)
         -35 : 20965.dasm (-3.71% of base)
         -32 : 114258.dasm (-1.04% of base)
         -32 : 21112.dasm (-6.72% of base)
         -32 : 21119.dasm (-6.56% of base)
         -31 : 183113.dasm (-4.70% of base)
         -30 : 115553.dasm (-25.64% of base)
         -29 : 183297.dasm (-9.86% of base)
         -28 : 114174.dasm (-0.91% of base)
         -28 : 114103.dasm (-0.97% of base)
         -28 : 114230.dasm (-0.97% of base)
         -28 : 114202.dasm (-0.86% of base)
         -28 : 114216.dasm (-0.97% of base)

540 total files with Code Size differences (536 improved, 4 regressed), 27 unchanged.

Top method regressions (bytes):
           2 ( 0.27% of base) : 2141.dasm - BinderFactoryVisitor:VisitEnumDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           2 ( 0.28% of base) : 2142.dasm - BinderFactoryVisitor:VisitDelegateDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.DelegateDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           1 ( 0.32% of base) : 2159.dasm - BinderFactoryVisitor:VisitDestructorDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.DestructorDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           1 ( 0.41% of base) : 183891.dasm - <<CopyToAsync>g__Awaited|15_1>d:MoveNext():this

Top method improvements (bytes):
        -503 (-3.78% of base) : 175110.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -210 (-5.66% of base) : 205806.dasm - System.Drawing.ColorTranslator:InitializeHtmlSysColorTable()
        -178 (-7.88% of base) : 205810.dasm - System.Drawing.ColorTranslator:FromOle(int):System.Drawing.Color
        -129 (-19.28% of base) : 35141.dasm - System.Globalization.HebrewNumber:.cctor()
         -55 (-2.85% of base) : 21803.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckViability(Microsoft.CodeAnalysis.CSharp.Symbol,int,int,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,bool,byref,Roslyn.Utilities.ConsList`1[Microsoft.CodeAnalysis.CSharp.Symbol]):Microsoft.CodeAnalysis.CSharp.SingleLookupResult:this
         -54 (-6.59% of base) : 86247.dasm - Microsoft.Diagnostics.Tracing.Parsers.DynamicManifestTraceEventData:.ctor(System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent],Microsoft.Diagnostics.Tracing.Parsers.ProviderManifest):this
         -43 (-0.26% of base) : 57265.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
         -38 (-2.11% of base) : 207056.dasm - System.Data.Odbc.OdbcMetaDataFactory:.ctor(System.IO.Stream,System.String,System.String,System.Data.Odbc.OdbcConnection):this
         -35 (-3.71% of base) : 20965.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:AnalyzeArguments(Microsoft.CodeAnalysis.CSharp.Symbol,Microsoft.CodeAnalysis.CSharp.AnalyzedArguments,bool,bool):Microsoft.CodeAnalysis.CSharp.ArgumentAnalysisResult
         -32 (-1.04% of base) : 114258.dasm - System.Data.Common.SqlDoubleStorage:Aggregate(System.Int32[],int):System.Object:this
         -32 (-6.72% of base) : 21112.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:AnalyzeImplicitUserDefinedConversions(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):Microsoft.CodeAnalysis.CSharp.UserDefinedConversionResult:this
         -32 (-6.56% of base) : 21119.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:AnalyzeExplicitUserDefinedConversions(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):Microsoft.CodeAnalysis.CSharp.UserDefinedConversionResult:this
         -31 (-4.70% of base) : 183113.dasm - System.Formats.Asn1.AsnWriter:SortContents(System.Byte[],int,int)
         -30 (-25.64% of base) : 115553.dasm - System.Data.SqlTypes.SqlByte:.cctor()
         -29 (-9.86% of base) : 183297.dasm - System.Formats.Asn1.Asn1Tag:.cctor()
         -28 (-0.91% of base) : 114174.dasm - System.Data.Common.SqlSingleStorage:Aggregate(System.Int32[],int):System.Object:this
         -28 (-0.97% of base) : 114103.dasm - System.Data.Common.SqlByteStorage:Aggregate(System.Int32[],int):System.Object:this
         -28 (-0.97% of base) : 114230.dasm - System.Data.Common.SqlInt16Storage:Aggregate(System.Int32[],int):System.Object:this
         -28 (-0.86% of base) : 114202.dasm - System.Data.Common.SqlInt64Storage:Aggregate(System.Int32[],int):System.Object:this
         -28 (-0.97% of base) : 114216.dasm - System.Data.Common.SqlInt32Storage:Aggregate(System.Int32[],int):System.Object:this

Top method regressions (percentages):
           1 ( 0.41% of base) : 183891.dasm - <<CopyToAsync>g__Awaited|15_1>d:MoveNext():this
           1 ( 0.32% of base) : 2159.dasm - BinderFactoryVisitor:VisitDestructorDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.DestructorDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           2 ( 0.28% of base) : 2142.dasm - BinderFactoryVisitor:VisitDelegateDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.DelegateDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           2 ( 0.27% of base) : 2141.dasm - BinderFactoryVisitor:VisitEnumDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this

Top method improvements (percentages):
          -4 (-26.67% of base) : 116045.dasm - System.Data.SqlTypes.SqlInt64:op_Implicit(long):System.Data.SqlTypes.SqlInt64
         -30 (-25.64% of base) : 115553.dasm - System.Data.SqlTypes.SqlByte:.cctor()
          -7 (-24.14% of base) : 206435.dasm - Microsoft.Extensions.FileSystemGlobbing.Internal.PatternTestResult:Success(System.String):Microsoft.Extensions.FileSystemGlobbing.Internal.PatternTestResult
          -6 (-24.00% of base) : 20873.dasm - Microsoft.CodeAnalysis.CSharp.ArgumentAnalysisResult:RequiredParameterMissing(int):Microsoft.CodeAnalysis.CSharp.ArgumentAnalysisResult
         -28 (-22.76% of base) : 116116.dasm - System.Data.SqlTypes.SqlInt16:.cctor()
          -7 (-21.88% of base) : 205861.dasm - System.Drawing.Color:get_White():System.Drawing.Color
          -7 (-21.88% of base) : 205862.dasm - System.Drawing.Color:get_Wheat():System.Drawing.Color
          -7 (-21.88% of base) : 205871.dasm - System.Drawing.Color:get_Snow():System.Drawing.Color
          -7 (-21.88% of base) : 205872.dasm - System.Drawing.Color:get_SlateGray():System.Drawing.Color
          -7 (-21.88% of base) : 205883.dasm - System.Drawing.Color:get_RosyBrown():System.Drawing.Color
          -7 (-21.88% of base) : 205884.dasm - System.Drawing.Color:get_Red():System.Drawing.Color
          -7 (-21.88% of base) : 205885.dasm - System.Drawing.Color:get_RebeccaPurple():System.Drawing.Color
          -7 (-21.88% of base) : 205886.dasm - System.Drawing.Color:get_Purple():System.Drawing.Color
          -7 (-21.88% of base) : 205913.dasm - System.Drawing.Color:get_MediumSeaGreen():System.Drawing.Color
          -7 (-21.88% of base) : 205914.dasm - System.Drawing.Color:get_MediumPurple():System.Drawing.Color
          -7 (-21.88% of base) : 205915.dasm - System.Drawing.Color:get_MediumOrchid():System.Drawing.Color
          -7 (-21.88% of base) : 205916.dasm - System.Drawing.Color:get_MediumBlue():System.Drawing.Color
          -7 (-21.88% of base) : 205941.dasm - System.Drawing.Color:get_Ivory():System.Drawing.Color
          -7 (-21.88% of base) : 205942.dasm - System.Drawing.Color:get_Indigo():System.Drawing.Color
          -7 (-21.88% of base) : 205943.dasm - System.Drawing.Color:get_IndianRed():System.Drawing.Color

540 total methods with Code Size differences (536 improved, 4 regressed), 27 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1040993
Total bytes of diff: 1025809
Total bytes of delta: -15184 (-1.46% of base)
Total relative delta: -105.50
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          18 : 220765.dasm (1.61% of base)
          17 : 106940.dasm (0.78% of base)
          11 : 45270.dasm (0.63% of base)
          10 : 85823.dasm (4.72% of base)
           9 : 8578.dasm (1.24% of base)
           9 : 8579.dasm (1.24% of base)
           6 : 221320.dasm (0.44% of base)
           5 : 106318.dasm (0.10% of base)
           5 : 106400.dasm (0.10% of base)
           5 : 218804.dasm (0.38% of base)
           5 : 218806.dasm (0.38% of base)
           4 : 70.dasm (0.15% of base)
           2 : 224952.dasm (0.70% of base)
           2 : 195301.dasm (0.29% of base)
           1 : 50315.dasm (0.29% of base)
           1 : 77097.dasm (0.12% of base)
           1 : 224567.dasm (0.39% of base)
           1 : 40660.dasm (0.14% of base)
           1 : 45604.dasm (0.11% of base)
           1 : 158920.dasm (0.18% of base)

Top file improvements (bytes):
        -187 : 192634.dasm (-3.72% of base)
        -175 : 192630.dasm (-7.72% of base)
        -140 : 115560.dasm (-3.95% of base)
        -138 : 115546.dasm (-4.15% of base)
        -113 : 115532.dasm (-3.89% of base)
         -95 : 216972.dasm (-6.51% of base)
         -70 : 232435.dasm (-3.22% of base)
         -63 : 230579.dasm (-0.79% of base)
         -58 : 220162.dasm (-2.27% of base)
         -58 : 219024.dasm (-2.27% of base)
         -58 : 218242.dasm (-2.27% of base)
         -58 : 86212.dasm (-7.35% of base)
         -56 : 42687.dasm (-1.02% of base)
         -53 : 211976.dasm (-3.54% of base)
         -51 : 107845.dasm (-2.32% of base)
         -48 : 23420.dasm (-2.13% of base)
         -48 : 107815.dasm (-0.92% of base)
         -44 : 220639.dasm (-1.98% of base)
         -43 : 167477.dasm (-9.13% of base)
         -41 : 162056.dasm (-1.57% of base)

1894 total files with Code Size differences (1873 improved, 21 regressed), 107 unchanged.

Top method regressions (bytes):
          18 ( 1.61% of base) : 220765.dasm - System.Security.Cryptography.Pkcs.Asn1.PolicyInformation:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
          17 ( 0.78% of base) : 106940.dasm - Newtonsoft.Json.Utilities.EnumUtils:ParseEnum(System.Type,Newtonsoft.Json.Serialization.NamingStrategy,System.String,bool):System.Object
          11 ( 0.63% of base) : 45270.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitArrayCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundArrayCreation,bool):this
          10 ( 4.72% of base) : 85823.dasm - Microsoft.Diagnostics.Tracing.StackSources.LinuxPerfScriptStackSource:CreateSampleFor(Microsoft.Diagnostics.Tracing.StackSources.LinuxEvent,Microsoft.Diagnostics.Tracing.StackSources.BlockedTimeAnalyzer):Microsoft.Diagnostics.Tracing.Stacks.LinuxPerfScriptStackSourceSample:this
           9 ( 1.24% of base) : 8578.dasm - Microsoft.FSharp.Collections.ArrayModule:Choose(Microsoft.FSharp.Core.FSharpFunc`2[__Canon,__Canon],System.__Canon[]):System.Nullable`1[System.Int32][]
           9 ( 1.24% of base) : 8579.dasm - Microsoft.FSharp.Collections.ArrayModule:Choose(Microsoft.FSharp.Core.FSharpFunc`2[[System.Byte, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpOption`1[[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], FSharp.Core, Version=5.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Byte[]):System.Nullable`1[System.Int32][]
           6 ( 0.44% of base) : 221320.dasm - Internal.Cryptography.Helpers:ValidateDer(System.ReadOnlyMemory`1[Byte])
           5 ( 0.10% of base) : 106318.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)
           5 ( 0.10% of base) : 106400.dasm - Newtonsoft.Json.JsonWriter:WriteValueAsync(Newtonsoft.Json.JsonWriter,int,System.Object,System.Threading.CancellationToken):System.Threading.Tasks.Task
           5 ( 0.38% of base) : 218804.dasm - System.Security.Cryptography.ECDiffieHellmanCng:DeriveKeyMaterial(System.Security.Cryptography.ECDiffieHellmanPublicKey):System.Byte[]:this
           5 ( 0.38% of base) : 218806.dasm - System.Security.Cryptography.ECDiffieHellmanCng:DeriveSecretAgreementHandle(System.Security.Cryptography.ECDiffieHellmanPublicKey):Microsoft.Win32.SafeHandles.SafeNCryptSecretHandle:this
           4 ( 0.15% of base) : 70.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           2 ( 0.70% of base) : 224952.dasm - System.Text.RegularExpressions.RegexFC:.ctor(ushort,bool,bool,bool):this
           2 ( 0.29% of base) : 195301.dasm - <<CopyToAsync>g__Awaited|15_1>d:MoveNext():this
           1 ( 0.29% of base) : 50315.dasm - Microsoft.CodeAnalysis.VisualBasic.BinderFactory:GetContainingNamedTypeBinderForMemberNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Binder):Microsoft.CodeAnalysis.VisualBasic.NamedTypeBinder:this
           1 ( 0.12% of base) : 77097.dasm - Microsoft.CodeAnalysis.AssemblyPortabilityPolicy:LoadFromXml(System.IO.Stream):Microsoft.CodeAnalysis.AssemblyPortabilityPolicy
           1 ( 0.39% of base) : 224567.dasm - System.Text.RegularExpressions.RegexCharClass:AddSet(System.ReadOnlySpan`1[Char]):this
           1 ( 0.14% of base) : 40660.dasm - Microsoft.CodeAnalysis.CSharp.Emit.PEDeltaAssemblyBuilder:TryGetAnonymousTypeKey(System.Reflection.Metadata.MetadataReader,System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.ArrayBuilder`1[AnonymousTypeKeyField]):bool
           1 ( 0.11% of base) : 45604.dasm - BinderFactoryVisitor:VisitEnumDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           1 ( 0.18% of base) : 158920.dasm - ILCompiler.Reflection.ReadyToRun.x86.GcTransitionCall:.ctor(int,bool,int,int):this

Top method improvements (bytes):
        -187 (-3.72% of base) : 192634.dasm - System.Drawing.ColorTranslator:InitializeHtmlSysColorTable()
        -175 (-7.72% of base) : 192630.dasm - System.Drawing.ColorTranslator:FromOle(int):System.Drawing.Color
        -140 (-3.95% of base) : 115560.dasm - System.Data.Common.SqlMoneyStorage:Aggregate(System.Int32[],int):System.Object:this
        -138 (-4.15% of base) : 115546.dasm - System.Data.Common.SqlInt64Storage:Aggregate(System.Int32[],int):System.Object:this
        -113 (-3.89% of base) : 115532.dasm - System.Data.Common.SqlInt32Storage:Aggregate(System.Int32[],int):System.Object:this
         -95 (-6.51% of base) : 216972.dasm - Internal.Cryptography.AsymmetricAlgorithmHelpers:ConvertDerToIeee1363(System.ReadOnlySpan`1[Byte],int,System.Span`1[Byte]):int
         -70 (-3.22% of base) : 232435.dasm - Xunit.ConfigReader_Json:Load(System.IO.Stream):Xunit.TestAssemblyConfiguration
         -63 (-0.79% of base) : 230579.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
         -58 (-2.27% of base) : 220162.dasm - System.Security.Cryptography.Asn1.PrivateKeyInfoAsn:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
         -58 (-2.27% of base) : 219024.dasm - System.Security.Cryptography.Asn1.PrivateKeyInfoAsn:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
         -58 (-2.27% of base) : 218242.dasm - System.Security.Cryptography.Asn1.PrivateKeyInfoAsn:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
         -58 (-7.35% of base) : 86212.dasm - Microsoft.Diagnostics.Tracing.Parsers.DynamicManifestTraceEventData:.ctor(System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],Microsoft.Diagnostics.Tracing.Parsers.ProviderManifest):this
         -56 (-1.02% of base) : 42687.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ConstantEvaluationHelpers:OrderGraph(System.Collections.Generic.Dictionary`2[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.CSharp.Symbols.ConstantEvaluationHelpers+Node`1[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[FieldInfo])
         -53 (-3.54% of base) : 211976.dasm - <SaveAsync>d__35:MoveNext():this
         -51 (-2.32% of base) : 107845.dasm - Newtonsoft.Json.Schema.JsonSchemaGenerator:GenerateInternal(System.Type,int,bool):Newtonsoft.Json.Schema.JsonSchema:this
         -48 (-2.13% of base) : 23420.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckViability(Microsoft.CodeAnalysis.CSharp.Symbol,int,int,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,bool,byref,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.SingleLookupResult:this
         -48 (-0.92% of base) : 107815.dasm - Newtonsoft.Json.Schema.JsonSchemaBuilder:ProcessSchemaProperties(Newtonsoft.Json.Linq.JObject):this
         -44 (-1.98% of base) : 220639.dasm - System.Security.Cryptography.Pkcs.Asn1.EnvelopedDataAsn:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
         -43 (-9.13% of base) : 167477.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:WithFileLineAndElement(System.String,System.Nullable`1[Int32],Microsoft.Build.Framework.IProjectElement):Microsoft.Build.Framework.Profiler.EvaluationLocation:this
         -41 (-1.57% of base) : 162056.dasm - Microsoft.Extensions.Configuration.Xml.XmlStreamConfigurationProvider:Read(System.IO.Stream,Microsoft.Extensions.Configuration.Xml.XmlDocumentDecryptor):System.Collections.Generic.IDictionary`2[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]

Top method regressions (percentages):
          10 ( 4.72% of base) : 85823.dasm - Microsoft.Diagnostics.Tracing.StackSources.LinuxPerfScriptStackSource:CreateSampleFor(Microsoft.Diagnostics.Tracing.StackSources.LinuxEvent,Microsoft.Diagnostics.Tracing.StackSources.BlockedTimeAnalyzer):Microsoft.Diagnostics.Tracing.Stacks.LinuxPerfScriptStackSourceSample:this
          18 ( 1.61% of base) : 220765.dasm - System.Security.Cryptography.Pkcs.Asn1.PolicyInformation:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
           9 ( 1.24% of base) : 8578.dasm - Microsoft.FSharp.Collections.ArrayModule:Choose(Microsoft.FSharp.Core.FSharpFunc`2[__Canon,__Canon],System.__Canon[]):System.Nullable`1[System.Int32][]
           9 ( 1.24% of base) : 8579.dasm - Microsoft.FSharp.Collections.ArrayModule:Choose(Microsoft.FSharp.Core.FSharpFunc`2[[System.Byte, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpOption`1[[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], FSharp.Core, Version=5.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Byte[]):System.Nullable`1[System.Int32][]
          17 ( 0.78% of base) : 106940.dasm - Newtonsoft.Json.Utilities.EnumUtils:ParseEnum(System.Type,Newtonsoft.Json.Serialization.NamingStrategy,System.String,bool):System.Object
           2 ( 0.70% of base) : 224952.dasm - System.Text.RegularExpressions.RegexFC:.ctor(ushort,bool,bool,bool):this
          11 ( 0.63% of base) : 45270.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitArrayCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundArrayCreation,bool):this
           6 ( 0.44% of base) : 221320.dasm - Internal.Cryptography.Helpers:ValidateDer(System.ReadOnlyMemory`1[Byte])
           1 ( 0.39% of base) : 224567.dasm - System.Text.RegularExpressions.RegexCharClass:AddSet(System.ReadOnlySpan`1[Char]):this
           5 ( 0.38% of base) : 218804.dasm - System.Security.Cryptography.ECDiffieHellmanCng:DeriveKeyMaterial(System.Security.Cryptography.ECDiffieHellmanPublicKey):System.Byte[]:this
           5 ( 0.38% of base) : 218806.dasm - System.Security.Cryptography.ECDiffieHellmanCng:DeriveSecretAgreementHandle(System.Security.Cryptography.ECDiffieHellmanPublicKey):Microsoft.Win32.SafeHandles.SafeNCryptSecretHandle:this
           2 ( 0.29% of base) : 195301.dasm - <<CopyToAsync>g__Awaited|15_1>d:MoveNext():this
           1 ( 0.29% of base) : 50315.dasm - Microsoft.CodeAnalysis.VisualBasic.BinderFactory:GetContainingNamedTypeBinderForMemberNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Binder):Microsoft.CodeAnalysis.VisualBasic.NamedTypeBinder:this
           1 ( 0.18% of base) : 158920.dasm - ILCompiler.Reflection.ReadyToRun.x86.GcTransitionCall:.ctor(int,bool,int,int):this
           4 ( 0.15% of base) : 70.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           1 ( 0.14% of base) : 40660.dasm - Microsoft.CodeAnalysis.CSharp.Emit.PEDeltaAssemblyBuilder:TryGetAnonymousTypeKey(System.Reflection.Metadata.MetadataReader,System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.ArrayBuilder`1[AnonymousTypeKeyField]):bool
           1 ( 0.12% of base) : 77097.dasm - Microsoft.CodeAnalysis.AssemblyPortabilityPolicy:LoadFromXml(System.IO.Stream):Microsoft.CodeAnalysis.AssemblyPortabilityPolicy
           1 ( 0.11% of base) : 36.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           1 ( 0.11% of base) : 45604.dasm - BinderFactoryVisitor:VisitEnumDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax):Microsoft.CodeAnalysis.CSharp.Binder:this
           5 ( 0.10% of base) : 106318.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)

Top method improvements (percentages):
          -4 (-26.67% of base) : 105678.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_ObjectCreationHandling(int):this
          -4 (-26.67% of base) : 105521.dasm - Newtonsoft.Json.JsonContainerAttribute:set_ItemReferenceLoopHandling(int):this
          -4 (-26.67% of base) : 105897.dasm - Newtonsoft.Json.JsonSerializerSettings:set_DateFormatHandling(int):this
          -4 (-26.67% of base) : 105655.dasm - Newtonsoft.Json.JsonObjectAttribute:set_ItemRequired(int):this
          -4 (-26.67% of base) : 105680.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_TypeNameHandling(int):this
          -4 (-26.67% of base) : 105690.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_ItemReferenceLoopHandling(int):this
          -4 (-26.67% of base) : 105895.dasm - Newtonsoft.Json.JsonSerializerSettings:set_Formatting(int):this
          -4 (-26.67% of base) : 105901.dasm - Newtonsoft.Json.JsonSerializerSettings:set_DateParseHandling(int):this
          -4 (-26.67% of base) : 113713.dasm - System.Data.SqlTypes.SqlInt64:op_Implicit(long):System.Data.SqlTypes.SqlInt64
          -4 (-26.67% of base) : 15717.dasm - System.Nullable`1[Int64][System.Int64]:op_Implicit(long):System.Nullable`1[Int64]
          -4 (-26.67% of base) : 78339.dasm - Microsoft.CodeAnalysis.Optional`1[Int64][System.Int64]:op_Implicit(long):Microsoft.CodeAnalysis.Optional`1[Int64]
          -4 (-26.67% of base) : 105674.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_DefaultValueHandling(int):this
          -4 (-26.67% of base) : 105899.dasm - Newtonsoft.Json.JsonSerializerSettings:set_DateTimeZoneHandling(int):this
          -4 (-26.67% of base) : 105523.dasm - Newtonsoft.Json.JsonContainerAttribute:set_ItemTypeNameHandling(int):this
          -4 (-26.67% of base) : 105653.dasm - Newtonsoft.Json.JsonObjectAttribute:set_ItemNullValueHandling(int):this
          -4 (-26.67% of base) : 105903.dasm - Newtonsoft.Json.JsonSerializerSettings:set_FloatFormatHandling(int):this
          -4 (-26.67% of base) : 105672.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_NullValueHandling(int):this
          -4 (-26.67% of base) : 105684.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_Order(int):this
          -4 (-26.67% of base) : 105676.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_ReferenceLoopHandling(int):this
          -4 (-26.67% of base) : 105686.dasm - Newtonsoft.Json.JsonPropertyAttribute:set_Required(int):this

1894 total methods with Code Size differences (1873 improved, 21 regressed), 107 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4243384
Total bytes of diff: 4166258
Total bytes of delta: -77126 (-1.82% of base)
Total relative delta: -285.11
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          20 : 257555.dasm (2.78% of base)
          20 : 224470.dasm (2.78% of base)
          18 : 202314.dasm (0.79% of base)
          14 : 161529.dasm (0.59% of base)
          12 : 202310.dasm (0.17% of base)
          12 : 42044.dasm (2.55% of base)
          12 : 324474.dasm (1.62% of base)
          11 : 16239.dasm (0.54% of base)
          11 : 32614.dasm (0.82% of base)
          10 : 16240.dasm (0.50% of base)
           8 : 161305.dasm (0.93% of base)
           7 : 161474.dasm (0.33% of base)
           7 : 202324.dasm (1.07% of base)
           5 : 145185.dasm (0.41% of base)
           5 : 161476.dasm (0.82% of base)
           5 : 161269.dasm (1.09% of base)
           5 : 161271.dasm (0.94% of base)
           5 : 161273.dasm (1.07% of base)
           5 : 161276.dasm (1.22% of base)
           5 : 161469.dasm (1.25% of base)

Top file improvements (bytes):
        -335 : 52356.dasm (-5.65% of base)
        -309 : 52375.dasm (-6.16% of base)
        -302 : 170185.dasm (-6.21% of base)
        -232 : 336855.dasm (-1.65% of base)
        -220 : 336894.dasm (-1.73% of base)
        -215 : 289603.dasm (-1.45% of base)
        -213 : 184015.dasm (-5.62% of base)
        -207 : 183895.dasm (-5.75% of base)
        -207 : 183899.dasm (-5.18% of base)
        -204 : 51846.dasm (-12.21% of base)
        -203 : 184019.dasm (-4.90% of base)
        -190 : 170306.dasm (-7.71% of base)
        -188 : 336091.dasm (-1.06% of base)
        -175 : 293589.dasm (-3.52% of base)
        -175 : 168401.dasm (-3.52% of base)
        -169 : 86953.dasm (-7.02% of base)
        -169 : 99381.dasm (-7.02% of base)
        -168 : 336640.dasm (-2.15% of base)
        -160 : 170214.dasm (-3.09% of base)
        -158 : 183422.dasm (-13.05% of base)

5031 total files with Code Size differences (4922 improved, 109 regressed), 783 unchanged.

Top method regressions (bytes):
          20 ( 2.78% of base) : 257555.dasm - System.Runtime.CompilerServices.Tests.ConfiguredAsyncDisposableTests:DisposeAsync_InvokesUnderlyingDisposeAsync(bool):this
          20 ( 2.78% of base) : 224470.dasm - System.Runtime.CompilerServices.Tests.ConfiguredAsyncDisposableTests:DisposeAsync_InvokesUnderlyingDisposeAsync(bool):this
          18 ( 0.79% of base) : 202314.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Add_BadValues():this
          14 ( 0.59% of base) : 161529.dasm - System.Data.Tests.SqlTypes.SqlInt64Test:ArithmeticOperators():this
          12 ( 0.17% of base) : 202310.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Add():this
          12 ( 2.55% of base) : 42044.dasm - System.Linq.Expressions.Tests.ArrayBoundsTests:NewArrayBounds(System.Type,System.Object,System.Type,System.Object,bool)
          12 ( 1.62% of base) : 324474.dasm - System.Numerics.Tests.modpowTest:ModPowValidSmallNumbers()
          11 ( 0.54% of base) : 16239.dasm - System.Collections.Generic.Tests.ComparerTests:NullableComparisons(ubyte,bool,ubyte,bool,int):this
          11 ( 0.82% of base) : 32614.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.indexer.regclass.regclass047.regclass047.Test:MainMethod():int
          10 ( 0.50% of base) : 16240.dasm - System.Collections.Generic.Tests.ComparerTests:NullableComparisons(short,bool,short,bool,int):this
           8 ( 0.93% of base) : 161305.dasm - System.Data.Tests.SqlTypes.SqlByteTest:Mod():this
           7 ( 0.33% of base) : 161474.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:BitwiseOperators():this
           7 ( 1.07% of base) : 202324.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:ValidateClassLayoutTable():this
           5 ( 0.41% of base) : 145185.dasm - NuGet.Protocol.Plugins.PluginFactory:WriteCommonLogMessages(NuGet.Protocol.Plugins.IPluginLogger)
           5 ( 0.82% of base) : 161476.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:OnesComplementOperator():this
           5 ( 1.09% of base) : 161269.dasm - System.Data.Tests.SqlTypes.SqlByteTest:BitwiseAndOperator():this
           5 ( 0.94% of base) : 161271.dasm - System.Data.Tests.SqlTypes.SqlByteTest:DivisionOperator():this
           5 ( 1.07% of base) : 161273.dasm - System.Data.Tests.SqlTypes.SqlByteTest:ExclusiveOrOperator():this
           5 ( 1.22% of base) : 161276.dasm - System.Data.Tests.SqlTypes.SqlByteTest:OnesComplementOperator():this
           5 ( 1.25% of base) : 161469.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:OnesComplement():this

Top method improvements (bytes):
        -335 (-5.65% of base) : 52356.dasm - <TestData>d__0:MoveNext():bool:this
        -309 (-6.16% of base) : 52375.dasm - <TestData>d__0:MoveNext():bool:this
        -302 (-6.21% of base) : 170185.dasm - System.Formats.Asn1.Tests.Reader.ReadEnumerated:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
        -232 (-1.65% of base) : 336855.dasm - TCWriteState:AddChildren():this
        -220 (-1.73% of base) : 336894.dasm - XObjectBuilderTest:AddChildren():this
        -215 (-1.45% of base) : 289603.dasm - System.Diagnostics.Metrics.Tests.MetricsTests:<ObservableInstrumentMeasurementTest>b__7_0():this
        -213 (-5.62% of base) : 184015.dasm - <Min_NullableFloat_TestData>d__29:MoveNext():bool:this
        -207 (-5.75% of base) : 183895.dasm - <Max_NullableFloat_TestData>d__35:MoveNext():bool:this
        -207 (-5.18% of base) : 183899.dasm - <Max_NullableDouble_TestData>d__38:MoveNext():bool:this
        -204 (-12.21% of base) : 51846.dasm - <Bounds_TestData>d__2:MoveNext():bool:this
        -203 (-4.90% of base) : 184019.dasm - <Min_NullableDouble_TestData>d__32:MoveNext():bool:this
        -190 (-7.71% of base) : 170306.dasm - System.Formats.Asn1.Tests.Reader.ReadSetOf:ReadSetOf_DataSorting(int,System.String,bool,int)
        -188 (-1.06% of base) : 336091.dasm - XLinqTests.SimpleObjectsCreation:AddChildren():this
        -175 (-3.52% of base) : 293589.dasm - <SystemColors_TestData>d__0:MoveNext():bool:this
        -175 (-3.52% of base) : 168401.dasm - <SystemColors_TestData>d__0:MoveNext():bool:this
        -169 (-7.02% of base) : 86953.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithNullables:Initialize():this
        -169 (-7.02% of base) : 99381.dasm - System.Text.Json.Serialization.Tests.SimpleTestClassWithNullables:Initialize():this
        -168 (-2.15% of base) : 336640.dasm - TCAttrNamespace:AddChildren():this
        -160 (-3.09% of base) : 170214.dasm - System.Formats.Asn1.Tests.Reader.ReadIA5String:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
        -158 (-13.05% of base) : 183422.dasm - <NullableInt_TestData>d__6:MoveNext():bool:this

Top method regressions (percentages):
          20 ( 2.78% of base) : 257555.dasm - System.Runtime.CompilerServices.Tests.ConfiguredAsyncDisposableTests:DisposeAsync_InvokesUnderlyingDisposeAsync(bool):this
          20 ( 2.78% of base) : 224470.dasm - System.Runtime.CompilerServices.Tests.ConfiguredAsyncDisposableTests:DisposeAsync_InvokesUnderlyingDisposeAsync(bool):this
          12 ( 2.55% of base) : 42044.dasm - System.Linq.Expressions.Tests.ArrayBoundsTests:NewArrayBounds(System.Type,System.Object,System.Type,System.Object,bool)
          12 ( 1.62% of base) : 324474.dasm - System.Numerics.Tests.modpowTest:ModPowValidSmallNumbers()
           2 ( 1.41% of base) : 203176.dasm - <>c__DisplayClass3_0:<Add_ArgumentErrors>b__5():System.Object:this
           5 ( 1.25% of base) : 161469.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:OnesComplement():this
           5 ( 1.22% of base) : 161276.dasm - System.Data.Tests.SqlTypes.SqlByteTest:OnesComplementOperator():this
           5 ( 1.22% of base) : 161308.dasm - System.Data.Tests.SqlTypes.SqlByteTest:OnesComplement():this
           5 ( 1.20% of base) : 161525.dasm - System.Data.Tests.SqlTypes.SqlInt64Test:OnesComplement():this
           5 ( 1.09% of base) : 161269.dasm - System.Data.Tests.SqlTypes.SqlByteTest:BitwiseAndOperator():this
           7 ( 1.07% of base) : 202324.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:ValidateClassLayoutTable():this
           5 ( 1.07% of base) : 161273.dasm - System.Data.Tests.SqlTypes.SqlByteTest:ExclusiveOrOperator():this
           2 ( 1.02% of base) : 15212.dasm - <>c__DisplayClass3_0:<GetSolutionFixesAsync>b__2(Microsoft.CodeAnalysis.Project):Microsoft.CodeAnalysis.CodeFixes.FixAllContext:this
           2 ( 0.96% of base) : 10632.dasm - Microsoft.CodeAnalysis.CodeFixes.DefaultFixAllProviderHelpers:GetProjectFixesAsync(Microsoft.CodeAnalysis.CodeFixes.FixAllContext,System.Func`3[[Microsoft.CodeAnalysis.CodeFixes.FixAllContext, Microsoft.CodeAnalysis.Workspaces, Version=3.9.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CodeFixes.FixAllContext, Microsoft.CodeAnalysis.Workspaces, Version=3.9.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[System.Threading.Tasks.Task`1[[Microsoft.CodeAnalysis.Solution, Microsoft.CodeAnalysis.Workspaces, Version=3.9.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Threading.Tasks.Task`1[[Microsoft.CodeAnalysis.Solution, Microsoft.CodeAnalysis.Workspaces, Version=3.9.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           5 ( 0.94% of base) : 161271.dasm - System.Data.Tests.SqlTypes.SqlByteTest:DivisionOperator():this
           8 ( 0.93% of base) : 161305.dasm - System.Data.Tests.SqlTypes.SqlByteTest:Mod():this
          11 ( 0.82% of base) : 32614.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.indexer.regclass.regclass047.regclass047.Test:MainMethod():int
           5 ( 0.82% of base) : 161476.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:OnesComplementOperator():this
           1 ( 0.80% of base) : 10713.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithDocument(Microsoft.CodeAnalysis.Document):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
          18 ( 0.79% of base) : 202314.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Add_BadValues():this

Top method improvements (percentages):
          -4 (-26.67% of base) : 101551.dasm - <>c:<.cctor>b__92_7(long):System.Nullable`1[UInt64]:this
          -4 (-26.67% of base) : 248757.dasm - FluentAssertions.Common.Configuration:set_ValueFormatterDetectionMode(int):this
          -4 (-26.67% of base) : 114465.dasm - Nullable@616-2[Int64][System.Int64]:Invoke(long):System.Nullable`1[Int64]:this
          -4 (-26.67% of base) : 55373.dasm - <>c__1`1[Int64][System.Int64]:<NullableSequence>b__1_0(long):System.Nullable`1[Int64]:this
          -4 (-26.67% of base) : 343906.dasm - Microsoft.Test.ModuleCore.TestAttribute:set_Priority(int):this
          -4 (-26.67% of base) : 108108.dasm - ImTools.Opt`1[Int64][System.Int64]:op_Implicit(long):ImTools.Opt`1[Int64]
          -4 (-26.67% of base) : 245427.dasm - Castle.Core.Logging.ConsoleFactory:.ctor(int):this
          -4 (-26.67% of base) : 245522.dasm - Castle.Core.Logging.TraceLoggerFactory:.ctor(int):this
          -4 (-26.67% of base) : 101548.dasm - <>c:<.cctor>b__92_4(long):System.Nullable`1[Int64]:this
          -8 (-25.81% of base) : 332080.dasm - ThrowsExceptionFromDispose:MoveNextAsync():System.Threading.Tasks.ValueTask`1[Boolean]:this
          -7 (-25.00% of base) : 261754.dasm - Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.PatternTestResult:Success(System.String):Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.PatternTestResult
         -37 (-24.50% of base) : 50458.dasm - System.Linq.Expressions.Tests.UnaryArithmeticNegateCheckedNullableTests:CheckUnaryArithmeticNegateCheckedNullableSByteTest()
          -7 (-24.14% of base) : 932.dasm - Roslyn.Utilities.ValueTaskFactory:FromResult(int):System.Threading.Tasks.ValueTask`1[Int32]
         -77 (-23.69% of base) : 33547.dasm - System.Dynamic.Runtime.Tests.Test:IsEqual(System.Nullable`1[System.Byte][])
         -77 (-23.69% of base) : 33548.dasm - System.Dynamic.Runtime.Tests.Test:IsEqual(System.Nullable`1[System.Byte][])
          -4 (-23.53% of base) : 144390.dasm - NuGet.Protocol.LocalPackageSearchMetadata:get_DownloadCount():System.Nullable`1[Int64]:this
         -47 (-23.50% of base) : 48885.dasm - System.Linq.Expressions.Tests.LiftedComparisonNotEqualNullableTests:CheckLiftedComparisonNotEqualNullableSByteTest(bool)
         -47 (-23.50% of base) : 48916.dasm - System.Linq.Expressions.Tests.LiftedDivideNullableTests:CheckLiftedDivideNullableSByteTest(bool)
         -47 (-23.50% of base) : 43002.dasm - System.Linq.Expressions.Tests.BinaryNullableAndTests:CheckNullableSByteAndTest(bool)
         -47 (-23.50% of base) : 43018.dasm - System.Linq.Expressions.Tests.BinaryNullableExclusiveOrTests:CheckNullableSByteExclusiveOrTest(bool)

5031 total methods with Code Size differences (4922 improved, 109 regressed), 783 unchanged.

```

</details>

--------------------------------------------------------------------------------

