## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 201276
Total bytes of diff: 200316
Total bytes of delta: -960 (-0.48% of base)
Total relative delta: -1.56
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 2192.dasm (0.24% of base)

Top file improvements (bytes):
         -44 : 4837.dasm (-3.69% of base)
         -32 : 10080.dasm (-4.60% of base)
         -32 : 8854.dasm (-1.93% of base)
         -32 : 8203.dasm (-5.33% of base)
         -24 : 9525.dasm (-2.60% of base)
         -24 : 16632.dasm (-0.67% of base)
         -20 : 11346.dasm (-6.49% of base)
         -20 : 1657.dasm (-0.66% of base)
         -16 : 1718.dasm (-0.42% of base)
         -12 : 17312.dasm (-0.89% of base)
         -12 : 9639.dasm (-0.46% of base)
         -12 : 7933.dasm (-1.89% of base)
         -12 : 13447.dasm (-1.85% of base)
         -12 : 18883.dasm (-0.52% of base)
         -12 : 18934.dasm (-0.40% of base)
         -12 : 9680.dasm (-0.31% of base)
         -12 : 5414.dasm (-0.32% of base)
          -8 : 12797.dasm (-1.85% of base)
          -8 : 22152.dasm (-1.48% of base)
          -8 : 5437.dasm (-3.77% of base)

130 total files with Code Size differences (129 improved, 1 regressed), 203 unchanged.

Top method regressions (bytes):
           8 ( 0.24% of base) : 2192.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this

Top method improvements (bytes):
         -44 (-3.69% of base) : 4837.dasm - <GetOptions>d__5:MoveNext():bool:this
         -32 (-4.60% of base) : 10080.dasm - EMFloat:Run():double:this
         -32 (-1.93% of base) : 8854.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:SetPropertySettingsFromAttributes(Newtonsoft.Json.Serialization.JsonProperty,System.Object,System.String,System.Type,int,byref):this
         -32 (-5.33% of base) : 8203.dasm - System.Drawing.Tests.Perf_Graphics_DrawBeziers:Setup():this
         -24 (-2.60% of base) : 9525.dasm - ImageTestData:CreateTestImage(System.Drawing.Imaging.ImageFormat):System.IO.Stream
         -24 (-0.67% of base) : 16632.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -20 (-6.49% of base) : 11346.dasm - System.Numerics.BigNumber:TryParseBigInteger(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):bool
         -20 (-0.66% of base) : 1657.dasm - MessagePack.Internal.DynamicObjectTypeBuilder:BuildSerialize(System.Type,MessagePack.Internal.ObjectSerializationInfo,System.Reflection.Emit.ILGenerator,System.Action,System.Func`3[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[MessagePack.Internal.ObjectSerializationInfo+EmittableMember, MessagePack, Version=1.9.0.0, Culture=neutral, PublicKeyToken=b4a0369545f0a1be],[System.Action, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int)
         -16 (-0.42% of base) : 1718.dasm - MessagePack.Internal.DynamicObjectTypeBuilder:BuildDeserialize(System.Type,MessagePack.Internal.ObjectSerializationInfo,System.Reflection.Emit.ILGenerator,System.Func`3[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[MessagePack.Internal.ObjectSerializationInfo+EmittableMember, MessagePack, Version=1.9.0.0, Culture=neutral, PublicKeyToken=b4a0369545f0a1be],[System.Action, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int)
         -12 (-0.89% of base) : 17312.dasm - Microsoft.CodeAnalysis.CSharp.Emit.PEModuleBuilder:GetForwardedTypes(System.Collections.Generic.HashSet`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CommonAssemblyWellKnownAttributeData`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[ExportedType])
         -12 (-0.46% of base) : 9639.dasm - <CopyToAsyncCore>d__59:MoveNext():this
         -12 (-1.89% of base) : 7933.dasm - System.IO.Pipelines.Pipe:PrepareFlush(byref,byref,System.Threading.CancellationToken):this
         -12 (-1.85% of base) : 13447.dasm - BoundedChannelReader[__Canon][System.__Canon]:WaitToReadAsync(System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Boolean]:this
         -12 (-0.52% of base) : 18883.dasm - <DetermineVersionAndSendAsync>d__85:MoveNext():this
         -12 (-0.40% of base) : 18934.dasm - <ReadLineAsyncInternal>d__63:MoveNext():this
         -12 (-0.31% of base) : 9680.dasm - <ReadAsyncSlowPath>d__39:MoveNext():this
         -12 (-0.32% of base) : 5414.dasm - <ReceiveBlobAsync>d__174`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
          -8 (-1.85% of base) : 12797.dasm - System.Text.Json.Tests.Perf_Get:GetDateTimeOffset():System.DateTimeOffset:this
          -8 (-1.48% of base) : 22152.dasm - System.Text.Json.Tests.Perf_Get:GetSByte():byte:this
          -8 (-3.77% of base) : 5437.dasm - System.Runtime.CompilerServices.AsyncValueTaskMethodBuilder`1[__Canon][System.__Canon]:get_Task():System.Threading.Tasks.ValueTask`1[__Canon]:this

Top method regressions (percentages):
           8 ( 0.24% of base) : 2192.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this

Top method improvements (percentages):
          -4 (-8.33% of base) : 23168.dasm - System.Threading.Tasks.ValueTaskPerfTest:Setup_Copy_PassAsArgumentAndReturn_FromResult():this
         -20 (-6.49% of base) : 11346.dasm - System.Numerics.BigNumber:TryParseBigInteger(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):bool
         -32 (-5.33% of base) : 8203.dasm - System.Drawing.Tests.Perf_Graphics_DrawBeziers:Setup():this
         -32 (-4.60% of base) : 10080.dasm - EMFloat:Run():double:this
          -8 (-4.00% of base) : 10101.dasm - Interop.StructureToPtr:MarshalStructureToPtr():int:this
          -4 (-4.00% of base) : 23362.dasm - System.Threading.Tasks.ValueTaskPerfTest:Setup_Copy_PassAsArgumentAndReturn_FromTask():this
          -8 (-3.77% of base) : 5437.dasm - System.Runtime.CompilerServices.AsyncValueTaskMethodBuilder`1[__Canon][System.__Canon]:get_Task():System.Threading.Tasks.ValueTask`1[__Canon]:this
         -44 (-3.69% of base) : 4837.dasm - <GetOptions>d__5:MoveNext():bool:this
          -8 (-3.03% of base) : 6408.dasm - System.Text.Json.Tests.Perf_Reader:ReadMultiSpanSequenceEmptyLoop():this
          -8 (-3.03% of base) : 19649.dasm - System.Text.Json.Tests.Perf_Segment:ReadSingleSegmentSequence():this
          -8 (-3.03% of base) : 10024.dasm - System.Text.Json.Tests.Perf_Reader:ReadSingleSpanSequenceEmptyLoop():this
          -8 (-2.90% of base) : 18832.dasm - System.Net.Http.DiagnosticsHandler:SendAsync(System.Net.Http.HttpRequestMessage,bool,System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[[System.Net.Http.HttpResponseMessage, System.Net.Http, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
          -8 (-2.86% of base) : 11886.dasm - AwaitableSocketAsyncEventArgs:AcceptAsync(System.Net.Sockets.Socket,System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[[System.Net.Sockets.Socket, System.Net.Sockets, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
          -8 (-2.63% of base) : 6427.dasm - System.Text.Json.Tests.Perf_Reader:ReadSpanEmptyLoop():this
         -24 (-2.60% of base) : 9525.dasm - ImageTestData:CreateTestImage(System.Drawing.Imaging.ImageFormat):System.IO.Stream
          -4 (-2.44% of base) : 21068.dasm - System.Drawing.Color:FromArgb(int,System.Drawing.Color):System.Drawing.Color
          -4 (-2.38% of base) : 14435.dasm - System.Formats.Cbor.Tests.Perf_CborReader:SkipValue(CborEncoding):this
          -8 (-2.25% of base) : 6436.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequence(int):this
          -8 (-2.20% of base) : 11526.dasm - System.Text.Json.Tests.Perf_Get:GetString():System.String:this
          -8 (-2.13% of base) : 10017.dasm - System.Text.Json.Tests.Perf_Get:GetUInt64():long:this

130 total methods with Code Size differences (129 improved, 1 regressed), 203 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1577316
Total bytes of diff: 1576700
Total bytes of delta: -616 (-0.04% of base)
Total relative delta: -2.10
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 74.dasm (0.24% of base)

Top file improvements (bytes):
         -32 : 194804.dasm (-4.60% of base)
         -20 : 218587.dasm (-4.95% of base)
         -20 : 218800.dasm (-4.27% of base)
         -16 : 239913.dasm (-3.60% of base)
         -16 : 242301.dasm (-1.17% of base)
         -16 : 218872.dasm (-0.69% of base)
         -12 : 86362.dasm (-4.48% of base)
         -12 : 223397.dasm (-0.54% of base)
         -12 : 227248.dasm (-2.91% of base)
         -12 : 227642.dasm (-3.03% of base)
          -8 : 249132.dasm (-0.68% of base)
          -8 : 250621.dasm (-1.35% of base)
          -8 : 250622.dasm (-6.25% of base)
          -8 : 251132.dasm (-6.90% of base)
          -8 : 168608.dasm (-0.25% of base)
          -8 : 168609.dasm (-0.24% of base)
          -8 : 168610.dasm (-0.25% of base)
          -8 : 168611.dasm (-0.24% of base)
          -8 : 172403.dasm (-5.41% of base)
          -8 : 172405.dasm (-5.41% of base)

102 total files with Code Size differences (101 improved, 1 regressed), 615 unchanged.

Top method regressions (bytes):
           8 ( 0.24% of base) : 74.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this

Top method improvements (bytes):
         -32 (-4.60% of base) : 194804.dasm - EMFloat:Run():double:this
         -20 (-4.95% of base) : 218587.dasm - AA:reset()
         -20 (-4.27% of base) : 218800.dasm - AA:reset()
         -16 (-3.60% of base) : 239913.dasm - AllTypesNullable:.ctor(bool):this
         -16 (-1.17% of base) : 242301.dasm - Program:Main(System.String[]):int
         -16 (-0.69% of base) : 218872.dasm - structinreg.Program1:Main1():int
         -12 (-4.48% of base) : 86362.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,long,ushort,ubyte,short,int):short
         -12 (-0.54% of base) : 223397.dasm - SoDBench.Program:GetDeploymentSize():SoDBench.SizeReportingNode
         -12 (-2.91% of base) : 227248.dasm - AA:reset()
         -12 (-3.03% of base) : 227642.dasm - AA:reset()
          -8 (-0.68% of base) : 249132.dasm - <Main>d__0:MoveNext():this
          -8 (-1.35% of base) : 250621.dasm - BoxTest.Test:FibonacciImpl(System.Object):System.Object:this
          -8 (-6.25% of base) : 250622.dasm - BoxTest.Test:Main():int
          -8 (-6.90% of base) : 251132.dasm - Test4:Run():int
          -8 (-0.25% of base) : 168608.dasm - Managed:MarshalStructAsParam_AsSeqByRef(int)
          -8 (-0.24% of base) : 168609.dasm - Managed:MarshalStructAsParam_AsSeqByValIn(int)
          -8 (-0.25% of base) : 168610.dasm - Managed:MarshalStructAsParam_AsSeqByRefIn(int)
          -8 (-0.24% of base) : 168611.dasm - Managed:MarshalStructAsParam_AsSeqByValOut(int)
          -8 (-5.41% of base) : 172403.dasm - NullableTest4:Run()
          -8 (-5.41% of base) : 172405.dasm - NullableTest5:Run()

Top method regressions (percentages):
           8 ( 0.24% of base) : 74.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this

Top method improvements (percentages):
          -8 (-22.22% of base) : 81264.dasm - TestStruct:.ctor(int):this
          -4 (-12.50% of base) : 81197.dasm - S2:.ctor(S0):this
          -8 (-9.09% of base) : 79675.dasm - StaticValueField:Init()
          -8 (-6.90% of base) : 251132.dasm - Test4:Run():int
          -8 (-6.25% of base) : 250622.dasm - BoxTest.Test:Main():int
          -8 (-5.41% of base) : 172403.dasm - NullableTest4:Run()
          -8 (-5.41% of base) : 172405.dasm - NullableTest5:Run()
          -8 (-5.41% of base) : 172407.dasm - NullableTest6:Run()
          -8 (-5.41% of base) : 172397.dasm - NullableTest1:Run()
          -8 (-5.41% of base) : 172401.dasm - NullableTest3:Run()
          -8 (-5.41% of base) : 172431.dasm - NullableTest18:Run()
         -20 (-4.95% of base) : 218587.dasm - AA:reset()
         -32 (-4.60% of base) : 194804.dasm - EMFloat:Run():double:this
         -12 (-4.48% of base) : 86362.dasm - DevDiv_578217.Program:ILGEN_METHOD(ushort,float,long,ushort,ubyte,short,int):short
         -20 (-4.27% of base) : 218800.dasm - AA:reset()
          -4 (-3.70% of base) : 81072.dasm - GitHub_18522:Main():int
         -16 (-3.60% of base) : 239913.dasm - AllTypesNullable:.ctor(bool):this
          -4 (-3.57% of base) : 251107.dasm - Test.Setting:ForBool(System.String):Test.Setting`1[Nullable`1]
          -4 (-3.12% of base) : 81133.dasm - GitHub_19243:M7():byref
         -12 (-3.03% of base) : 227642.dasm - AA:reset()

102 total methods with Code Size differences (101 improved, 1 regressed), 615 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 256360
Total bytes of diff: 254720
Total bytes of delta: -1640 (-0.64% of base)
Total relative delta: -5.29
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -408 : 98391.dasm (-1.70% of base)
         -48 : 171137.dasm (-12.90% of base)
         -32 : 143932.dasm (-23.53% of base)
         -24 : 144495.dasm (-17.65% of base)
         -16 : 123201.dasm (-1.65% of base)
         -16 : 98899.dasm (-4.26% of base)
         -16 : 144298.dasm (-12.50% of base)
         -16 : 84773.dasm (-17.39% of base)
         -16 : 144363.dasm (-12.50% of base)
         -16 : 144429.dasm (-12.50% of base)
         -16 : 99055.dasm (-4.44% of base)
         -16 : 31197.dasm (-1.48% of base)
         -16 : 42921.dasm (-2.00% of base)
         -12 : 156177.dasm (-4.84% of base)
         -12 : 156209.dasm (-2.24% of base)
         -12 : 44860.dasm (-1.67% of base)
         -12 : 36931.dasm (-4.05% of base)
         -12 : 54733.dasm (-12.00% of base)
         -12 : 161790.dasm (-10.71% of base)
         -12 : 164736.dasm (-20.00% of base)

196 total files with Code Size differences (196 improved, 0 regressed), 254 unchanged.

Top method improvements (bytes):
        -408 (-1.70% of base) : 98391.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
         -48 (-12.90% of base) : 171137.dasm - System.Formats.Asn1.Asn1Tag:.cctor()
         -32 (-23.53% of base) : 143932.dasm - System.Data.SqlTypes.SqlByte:.cctor()
         -24 (-17.65% of base) : 144495.dasm - System.Data.SqlTypes.SqlInt16:.cctor()
         -16 (-1.65% of base) : 123201.dasm - System.Xml.Xsl.IlGen.XmlILVisitor:VisitNodeProperty(System.Xml.Xsl.Qil.QilUnary):System.Xml.Xsl.Qil.QilNode:this
         -16 (-4.26% of base) : 98899.dasm - Microsoft.CodeAnalysis.PEModule:GetTypeLayout(System.Reflection.Metadata.TypeDefinitionHandle):Microsoft.CodeAnalysis.TypeLayout:this
         -16 (-12.50% of base) : 144298.dasm - System.Data.SqlTypes.SqlMoney:.cctor()
         -16 (-17.39% of base) : 84773.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.LexicalSortKey:.cctor()
         -16 (-12.50% of base) : 144363.dasm - System.Data.SqlTypes.SqlInt64:.cctor()
         -16 (-12.50% of base) : 144429.dasm - System.Data.SqlTypes.SqlInt32:.cctor()
         -16 (-4.44% of base) : 99055.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:DecodeModifiersOrThrow(byref,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.ModifierInfo`1[System.__Canon]]:this
         -16 (-1.48% of base) : 31197.dasm - Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1:VisitSwitchHeader(Microsoft.CodeAnalysis.CSharp.BoundSwitchStatement):Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState:this
         -16 (-2.00% of base) : 42921.dasm - System.Threading.TimerQueueTimer:CloseAsync():System.Threading.Tasks.ValueTask:this
         -12 (-4.84% of base) : 156177.dasm - System.Security.Cryptography.ECDiffieHellmanCng:.ctor(int):this
         -12 (-2.24% of base) : 156209.dasm - System.Security.Cryptography.ECDiffieHellmanCng:.ctor(System.Security.Cryptography.CngKey):this
         -12 (-1.67% of base) : 44860.dasm - System.Globalization.HebrewNumber:.cctor()
         -12 (-4.05% of base) : 36931.dasm - System.IO.BinaryWriter:DisposeAsync():System.Threading.Tasks.ValueTask:this
         -12 (-12.00% of base) : 54733.dasm - ValueCollection:System.Collections.IEnumerable.GetEnumerator():System.Collections.IEnumerator:this
         -12 (-10.71% of base) : 161790.dasm - BigNumberBuffer:Create():System.Numerics.BigNumber+BigNumberBuffer
         -12 (-20.00% of base) : 164736.dasm - Microsoft.Extensions.FileSystemGlobbing.Internal.PatternTestResult:.cctor()

Top method improvements (percentages):
         -32 (-23.53% of base) : 143932.dasm - System.Data.SqlTypes.SqlByte:.cctor()
         -12 (-20.00% of base) : 164736.dasm - Microsoft.Extensions.FileSystemGlobbing.Internal.PatternTestResult:.cctor()
         -12 (-20.00% of base) : 99451.dasm - Microsoft.CodeAnalysis.PreprocessingSymbolInfo:.cctor()
         -12 (-18.75% of base) : 182453.dasm - System.Configuration.OverrideModeSetting:.cctor()
         -12 (-18.75% of base) : 49810.dasm - System.Half:.cctor()
         -24 (-17.65% of base) : 144495.dasm - System.Data.SqlTypes.SqlInt16:.cctor()
         -16 (-17.39% of base) : 84773.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.LexicalSortKey:.cctor()
         -12 (-15.79% of base) : 167451.dasm - System.Drawing.Printing.TriState:.cctor()
         -48 (-12.90% of base) : 171137.dasm - System.Formats.Asn1.Asn1Tag:.cctor()
         -16 (-12.50% of base) : 144298.dasm - System.Data.SqlTypes.SqlMoney:.cctor()
         -16 (-12.50% of base) : 144363.dasm - System.Data.SqlTypes.SqlInt64:.cctor()
         -16 (-12.50% of base) : 144429.dasm - System.Data.SqlTypes.SqlInt32:.cctor()
         -12 (-12.00% of base) : 54733.dasm - ValueCollection:System.Collections.IEnumerable.GetEnumerator():System.Collections.IEnumerator:this
          -8 (-11.76% of base) : 217293.dasm - System.IO.WaitForChangedResult:.cctor()
         -12 (-11.54% of base) : 53879.dasm - System.Collections.Generic.List`1:System.Collections.IEnumerable.GetEnumerator():System.Collections.IEnumerator:this
         -12 (-10.71% of base) : 161790.dasm - BigNumberBuffer:Create():System.Numerics.BigNumber+BigNumberBuffer
          -4 (-9.09% of base) : 190896.dasm - System.Drawing.Color:FromArgb(int):System.Drawing.Color
          -4 (-9.09% of base) : 190895.dasm - System.Drawing.Color:FromArgb(int):System.Drawing.Color
          -4 (-7.69% of base) : 197566.dasm - System.Linq.Parallel.ConcatKey`2:MakeRight(System.__Canon):System.Linq.Parallel.ConcatKey`2[System.__Canon, System.__Canon]
          -4 (-6.67% of base) : 54740.dasm - ValueCollection:GetEnumerator():System.Collections.Generic.Dictionary`2+ValueCollection+Enumerator[System.UInt64, System.Char]:this

196 total methods with Code Size differences (196 improved, 0 regressed), 254 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 995448
Total bytes of diff: 988980
Total bytes of delta: -6468 (-0.65% of base)
Total relative delta: -20.81
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 25985.dasm (5.48% of base)
          16 : 26569.dasm (8.33% of base)
          12 : 147627.dasm (2.22% of base)
           8 : 74.dasm (0.24% of base)
           8 : 85919.dasm (3.39% of base)
           4 : 105163.dasm (0.17% of base)
           4 : 228974.dasm (0.52% of base)
           4 : 222040.dasm (1.11% of base)
           4 : 222420.dasm (1.08% of base)
           4 : 85744.dasm (0.20% of base)

Top file improvements (bytes):
         -48 : 228976.dasm (-1.66% of base)
         -48 : 228977.dasm (-1.54% of base)
         -48 : 228979.dasm (-1.59% of base)
         -40 : 232175.dasm (-0.51% of base)
         -40 : 211483.dasm (-3.83% of base)
         -32 : 105436.dasm (-1.90% of base)
         -28 : 212740.dasm (-2.73% of base)
         -28 : 212762.dasm (-2.35% of base)
         -28 : 215151.dasm (-3.04% of base)
         -28 : 214626.dasm (-2.73% of base)
         -28 : 213520.dasm (-2.73% of base)
         -28 : 228999.dasm (-0.84% of base)
         -24 : 207722.dasm (-1.58% of base)
         -24 : 213449.dasm (-0.65% of base)
         -24 : 115001.dasm (-0.38% of base)
         -24 : 212394.dasm (-0.65% of base)
         -24 : 214722.dasm (-2.31% of base)
         -20 : 189339.dasm (-5.00% of base)
         -20 : 189342.dasm (-5.00% of base)
         -20 : 212722.dasm (-2.25% of base)

794 total files with Code Size differences (784 improved, 10 regressed), 1025 unchanged.

Top method regressions (bytes):
          16 ( 5.48% of base) : 25985.dasm - Microsoft.CodeAnalysis.CSharp.CSharpSemanticModel:GetConstantValueCore(Microsoft.CodeAnalysis.SyntaxNode,System.Threading.CancellationToken):Microsoft.CodeAnalysis.Optional`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]:this
          16 ( 8.33% of base) : 26569.dasm - Microsoft.CodeAnalysis.CSharp.CSharpExtensions:GetConstantValue(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,System.Threading.CancellationToken):Microsoft.CodeAnalysis.Optional`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
          12 ( 2.22% of base) : 147627.dasm - Microsoft.Extensions.Logging.Console.SimpleConsoleFormatter:GetLogLevelConsoleColors(int):ConsoleColors:this
           8 ( 0.24% of base) : 74.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           8 ( 3.39% of base) : 85919.dasm - Microsoft.Diagnostics.Tracing.StackSources.LinuxPerfScriptStackSource:CreateSampleFor(Microsoft.Diagnostics.Tracing.StackSources.LinuxEvent,Microsoft.Diagnostics.Tracing.StackSources.BlockedTimeAnalyzer):Microsoft.Diagnostics.Tracing.Stacks.LinuxPerfScriptStackSourceSample:this
           4 ( 0.17% of base) : 105163.dasm - Newtonsoft.Json.Utilities.EnumUtils:ParseEnum(System.Type,Newtonsoft.Json.Serialization.NamingStrategy,System.String,bool):System.Object
           4 ( 0.52% of base) : 228974.dasm - Internal.TypeSystem.Interop.ArrayMarshaller:EmitElementCount(Internal.IL.Stubs.ILCodeStream,int):this
           4 ( 1.11% of base) : 222040.dasm - System.Text.RegularExpressions.RegexCharClass:AddSet(System.ReadOnlySpan`1[Char]):this
           4 ( 1.08% of base) : 222420.dasm - System.Text.RegularExpressions.RegexFC:.ctor(ushort,bool,bool,bool):this
           4 ( 0.20% of base) : 85744.dasm - Microsoft.Diagnostics.Tracing.Session.TraceEventSession:CleanFilterDataForEtwSession():this

Top method improvements (bytes):
         -48 (-1.66% of base) : 228976.dasm - Internal.TypeSystem.Interop.ArrayMarshaller:TransformManagedToNative(Internal.IL.Stubs.ILCodeStream):this
         -48 (-1.54% of base) : 228977.dasm - Internal.TypeSystem.Interop.ArrayMarshaller:TransformNativeToManaged(Internal.IL.Stubs.ILCodeStream):this
         -48 (-1.59% of base) : 228979.dasm - Internal.TypeSystem.Interop.ArrayMarshaller:EmitCleanupManaged(Internal.IL.Stubs.ILCodeStream):this
         -40 (-0.51% of base) : 232175.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
         -40 (-3.83% of base) : 211483.dasm - Internal.Cryptography.AsymmetricAlgorithmHelpers:ConvertDerToIeee1363(System.ReadOnlySpan`1[Byte],int,System.Span`1[Byte]):int
         -32 (-1.90% of base) : 105436.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:SetPropertySettingsFromAttributes(Newtonsoft.Json.Serialization.JsonProperty,System.Object,System.String,System.Type,int,byref):this
         -28 (-2.73% of base) : 212740.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -28 (-2.35% of base) : 212762.dasm - System.Security.Cryptography.Asn1.RSAPublicKeyAsn:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.RSAPublicKeyAsn
         -28 (-3.04% of base) : 215151.dasm - System.Security.Cryptography.Pkcs.Asn1.KeyAgreeRecipientInfoAsn:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Pkcs.Asn1.KeyAgreeRecipientInfoAsn
         -28 (-2.73% of base) : 214626.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -28 (-2.73% of base) : 213520.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -28 (-0.84% of base) : 228999.dasm - Internal.TypeSystem.Interop.SafeHandleMarshaller:EmitMarshalArgumentManagedToNative():this
         -24 (-1.58% of base) : 207722.dasm - Enumerator:MoveNext():bool:this
         -24 (-0.65% of base) : 213449.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -24 (-0.38% of base) : 115001.dasm - <SendWithAuthAsync>d__17:MoveNext():this
         -24 (-0.65% of base) : 212394.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -24 (-2.31% of base) : 214722.dasm - System.Security.Cryptography.Asn1.Pkcs12.PfxAsn:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],byref)
         -20 (-5.00% of base) : 189339.dasm - System.Linq.Parallel.ContainsSearchOperator`1[__Canon][System.__Canon]:Aggregate():bool:this
         -20 (-5.00% of base) : 189342.dasm - System.Linq.Parallel.ContainsSearchOperator`1[Byte][System.Byte]:Aggregate():bool:this
         -20 (-2.25% of base) : 212722.dasm - System.Security.Cryptography.Asn1.ECDomainParameters:Decode(System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.ECDomainParameters

Top method regressions (percentages):
          16 ( 8.33% of base) : 26569.dasm - Microsoft.CodeAnalysis.CSharp.CSharpExtensions:GetConstantValue(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,System.Threading.CancellationToken):Microsoft.CodeAnalysis.Optional`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
          16 ( 5.48% of base) : 25985.dasm - Microsoft.CodeAnalysis.CSharp.CSharpSemanticModel:GetConstantValueCore(Microsoft.CodeAnalysis.SyntaxNode,System.Threading.CancellationToken):Microsoft.CodeAnalysis.Optional`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]:this
           8 ( 3.39% of base) : 85919.dasm - Microsoft.Diagnostics.Tracing.StackSources.LinuxPerfScriptStackSource:CreateSampleFor(Microsoft.Diagnostics.Tracing.StackSources.LinuxEvent,Microsoft.Diagnostics.Tracing.StackSources.BlockedTimeAnalyzer):Microsoft.Diagnostics.Tracing.Stacks.LinuxPerfScriptStackSourceSample:this
          12 ( 2.22% of base) : 147627.dasm - Microsoft.Extensions.Logging.Console.SimpleConsoleFormatter:GetLogLevelConsoleColors(int):ConsoleColors:this
           4 ( 1.11% of base) : 222040.dasm - System.Text.RegularExpressions.RegexCharClass:AddSet(System.ReadOnlySpan`1[Char]):this
           4 ( 1.08% of base) : 222420.dasm - System.Text.RegularExpressions.RegexFC:.ctor(ushort,bool,bool,bool):this
           4 ( 0.52% of base) : 228974.dasm - Internal.TypeSystem.Interop.ArrayMarshaller:EmitElementCount(Internal.IL.Stubs.ILCodeStream,int):this
           8 ( 0.24% of base) : 74.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
           4 ( 0.20% of base) : 85744.dasm - Microsoft.Diagnostics.Tracing.Session.TraceEventSession:CleanFilterDataForEtwSession():this
           4 ( 0.17% of base) : 105163.dasm - Newtonsoft.Json.Utilities.EnumUtils:ParseEnum(System.Type,Newtonsoft.Json.Serialization.NamingStrategy,System.String,bool):System.Object

Top method improvements (percentages):
         -12 (-14.29% of base) : 156629.dasm - Builder[Int64,Nullable`1][System.Int64,System.Nullable`1[System.Int32]]:GetValueOrDefault(long):System.Nullable`1[Int32]:this
         -12 (-14.29% of base) : 156602.dasm - Builder[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:GetValueOrDefault(int):System.Nullable`1[Int32]:this
         -12 (-13.64% of base) : 158239.dasm - Builder[Int64,Nullable`1][System.Int64,System.Nullable`1[System.Int32]]:GetValueOrDefault(long):System.Nullable`1[Int32]:this
         -12 (-13.64% of base) : 156611.dasm - Builder[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:GetValueOrDefault(double):System.Nullable`1[Int32]:this
         -12 (-13.64% of base) : 20732.dasm - KeyCollection[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:System.Collections.Generic.IEnumerable<TKey>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 234758.dasm - ChangeTrackingHashSet`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 158209.dasm - Builder[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:GetValueOrDefault(int):System.Nullable`1[Int32]:this
         -12 (-13.64% of base) : 158219.dasm - Builder[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:GetValueOrDefault(double):System.Nullable`1[Int32]:this
         -12 (-13.04% of base) : 20823.dasm - System.Collections.Generic.HashSet`1[Byte][System.Byte]:System.Collections.Generic.IEnumerable<T>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.04% of base) : 158165.dasm - Builder[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:GetValueOrDefault(ubyte):System.Nullable`1[Int32]:this
         -12 (-13.04% of base) : 158199.dasm - Builder[Int16,Nullable`1][System.Int16,System.Nullable`1[System.Int32]]:GetValueOrDefault(short):System.Nullable`1[Int32]:this
         -12 (-13.04% of base) : 20950.dasm - System.Collections.Generic.List`1[Int16][System.Int16]:System.Collections.Generic.IEnumerable<T>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Int16]:this
         -12 (-12.50% of base) : 160938.dasm - System.Collections.Generic.Stack`1[Byte][System.Byte]:System.Collections.Generic.IEnumerable<T>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-12.50% of base) : 221037.dasm - System.Text.Json.Nodes.JsonValue:Create(short,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -12 (-12.50% of base) : 221039.dasm - System.Text.Json.Nodes.JsonValue:Create(int,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -12 (-12.50% of base) : 221041.dasm - System.Text.Json.Nodes.JsonValue:Create(long,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -12 (-12.50% of base) : 221043.dasm - System.Text.Json.Nodes.JsonValue:Create(byte,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -16 (-12.50% of base) : 221047.dasm - System.Text.Json.Nodes.JsonValue:Create(System.String,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -12 (-12.50% of base) : 221048.dasm - System.Text.Json.Nodes.JsonValue:Create(ushort,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
         -12 (-12.50% of base) : 221050.dasm - System.Text.Json.Nodes.JsonValue:Create(int,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue

794 total methods with Code Size differences (784 improved, 10 regressed), 1025 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4192988
Total bytes of diff: 4158612
Total bytes of delta: -34376 (-0.82% of base)
Total relative delta: -97.92
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          80 : 258470.dasm (1.78% of base)
          20 : 5886.dasm (1.83% of base)
          20 : 62374.dasm (1.36% of base)
          16 : 176408.dasm (0.99% of base)
          16 : 176401.dasm (0.47% of base)
          16 : 176402.dasm (0.97% of base)
          16 : 176407.dasm (0.47% of base)
          16 : 33174.dasm (0.63% of base)
          12 : 13204.dasm (1.92% of base)
          12 : 13208.dasm (1.81% of base)
          12 : 201462.dasm (0.52% of base)
          12 : 179936.dasm (1.23% of base)
          12 : 179937.dasm (1.20% of base)
           8 : 8664.dasm (6.06% of base)
           8 : 13086.dasm (0.44% of base)
           8 : 32348.dasm (0.43% of base)
           8 : 13082.dasm (0.17% of base)
           8 : 160446.dasm (2.38% of base)
           8 : 160447.dasm (1.96% of base)
           8 : 160767.dasm (0.19% of base)

Top file improvements (bytes):
        -224 : 335555.dasm (-1.83% of base)
        -160 : 335340.dasm (-2.47% of base)
        -132 : 51895.dasm (-2.20% of base)
        -120 : 335291.dasm (-2.49% of base)
        -120 : 51914.dasm (-2.38% of base)
        -120 : 49231.dasm (-0.53% of base)
        -116 : 94740.dasm (-5.19% of base)
         -96 : 169361.dasm (-2.58% of base)
         -96 : 335299.dasm (-1.93% of base)
         -96 : 51385.dasm (-5.61% of base)
         -96 : 191099.dasm (-3.90% of base)
         -84 : 169264.dasm (-1.19% of base)
         -84 : 191080.dasm (-4.90% of base)
         -80 : 94822.dasm (-2.19% of base)
         -72 : 329903.dasm (-5.54% of base)
         -72 : 225601.dasm (-1.89% of base)
         -68 : 282382.dasm (-2.42% of base)
         -68 : 329906.dasm (-0.93% of base)
         -68 : 169310.dasm (-1.90% of base)
         -60 : 335398.dasm (-1.88% of base)

3329 total files with Code Size differences (3229 improved, 100 regressed), 2439 unchanged.

Top method regressions (bytes):
          80 ( 1.78% of base) : 258470.dasm - Microsoft.CSharp.RuntimeBinder.Tests.ImplicitConversionTests:NumericNullableToNullableConversions():this
          20 ( 1.83% of base) : 5886.dasm - Microsoft.CodeAnalysis.Shared.Extensions.SyntaxGeneratorExtensions:CreateIEquatableEqualsMethod(Microsoft.CodeAnalysis.Editing.SyntaxGenerator,Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.INamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=3.9.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.INamedTypeSymbol,Microsoft.CodeAnalysis.SyntaxAnnotation):Microsoft.CodeAnalysis.IMethodSymbol
          20 ( 1.36% of base) : 62374.dasm - <<EventSource_SendingRequestContent_LogsRequestContentStartStop>b__5_0>d:MoveNext():this
          16 ( 0.99% of base) : 176408.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Double_NaN()
          16 ( 0.47% of base) : 176401.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Float_Overflow()
          16 ( 0.97% of base) : 176402.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Float_NaN()
          16 ( 0.47% of base) : 176407.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Double_Overflow()
          16 ( 0.63% of base) : 33174.dasm - System.Dynamic.Runtime.Tests.Test:CalledFrom_CollectionInitializer()
          12 ( 1.92% of base) : 13204.dasm - <GetEnumerator>d__27[__Canon][System.__Canon]:MoveNext():bool:this
          12 ( 1.81% of base) : 13208.dasm - <GetEnumerator>d__27[Byte][System.Byte]:MoveNext():bool:this
          12 ( 0.52% of base) : 201462.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Add_BadValues():this
          12 ( 1.23% of base) : 179936.dasm - System.Linq.Tests.AppendPrependTests:SameResultsRepeatCallsIntQueryAppend():this
          12 ( 1.20% of base) : 179937.dasm - System.Linq.Tests.AppendPrependTests:SameResultsRepeatCallsIntQueryPrepend():this
           8 ( 6.06% of base) : 8664.dasm - Microsoft.CodeAnalysis.EmbeddedLanguages.Common.EmbeddedSyntaxToken`1[Byte][System.Byte]:WithDiagnostics(System.Collections.Immutable.ImmutableArray`1[EmbeddedDiagnostic]):Microsoft.CodeAnalysis.EmbeddedLanguages.Common.EmbeddedSyntaxToken`1[Byte]:this
           8 ( 0.44% of base) : 13086.dasm - <OverrideMethodAsync>d__18:MoveNext():this
           8 ( 0.43% of base) : 32348.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.indexer.regclass.regclass009.regclass009.Test:MainMethod():int
           8 ( 0.17% of base) : 13082.dasm - <OverridePropertyAsync>d__13:MoveNext():this
           8 ( 2.38% of base) : 160446.dasm - System.Data.Tests.SqlTypes.SqlByteTest:AdditionOperator():this
           8 ( 1.96% of base) : 160447.dasm - System.Data.Tests.SqlTypes.SqlByteTest:BitwiseAndOperator():this
           8 ( 0.19% of base) : 160767.dasm - System.Data.Tests.SqlTypes.SqlSingleTest:Conversions():this

Top method improvements (bytes):
        -224 (-1.83% of base) : 335555.dasm - TCWriteState:AddChildren():this
        -160 (-2.47% of base) : 335340.dasm - TCAttrNamespace:AddChildren():this
        -132 (-2.20% of base) : 51895.dasm - <TestData>d__0:MoveNext():bool:this
        -120 (-2.49% of base) : 335291.dasm - TCWriteNode_XmlReader:AddChildren():this
        -120 (-2.38% of base) : 51914.dasm - <TestData>d__0:MoveNext():bool:this
        -120 (-0.53% of base) : 49231.dasm - System.Linq.Expressions.Tests.Compiler_Tests:BinaryOperators(bool)
        -116 (-5.19% of base) : 94740.dasm - System.Text.Json.Nodes.Tests.JsonArrayTests:CreatingNestedJsonArray()
         -96 (-2.58% of base) : 169361.dasm - System.Formats.Asn1.Tests.Reader.ReadEnumerated:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
         -96 (-1.93% of base) : 335299.dasm - TCElemNamespace:AddChildren():this
         -96 (-5.61% of base) : 51385.dasm - <Bounds_TestData>d__2:MoveNext():bool:this
         -96 (-3.90% of base) : 191099.dasm - System.Net.Http.Tests.RangeItemHeaderValueTest:GetRangeItemLength_DifferentValidScenarios_AllReturnNonZero():this
         -84 (-1.19% of base) : 169264.dasm - System.Formats.Asn1.Tests.Reader.ComprehensiveReadTests:ReadMicrosoftComCert()
         -84 (-4.90% of base) : 191080.dasm - System.Net.Http.Tests.RangeHeaderValueTest:Equals_UseSameAndDifferentRanges_EqualOrNotEqualNoExceptions():this
         -80 (-2.19% of base) : 94822.dasm - System.Text.Json.Nodes.Tests.ParentPathRootTests:GetPathAndRoot()
         -72 (-5.54% of base) : 329903.dasm - System.Threading.Tasks.Tests.ValueTaskTests:NonGeneric_Equals_Object():this
         -72 (-1.89% of base) : 225601.dasm - <>c:<DroppedIncompleteStateMachine_RaisesIncompleteAsyncMethodEvent>b__33_0():this
         -68 (-2.42% of base) : 282382.dasm - <Section_Set_Data>d__2:MoveNext():bool:this
         -68 (-0.93% of base) : 329906.dasm - System.Threading.Tasks.Tests.ValueTaskTests:Generic_ToString_Success():this
         -68 (-1.90% of base) : 169310.dasm - System.Formats.Asn1.Tests.Reader.ReadBitString:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
         -60 (-1.88% of base) : 335398.dasm - TCEntityRef:AddChildren():this

Top method regressions (percentages):
           8 ( 6.06% of base) : 8664.dasm - Microsoft.CodeAnalysis.EmbeddedLanguages.Common.EmbeddedSyntaxToken`1[Byte][System.Byte]:WithDiagnostics(System.Collections.Immutable.ImmutableArray`1[EmbeddedDiagnostic]):Microsoft.CodeAnalysis.EmbeddedLanguages.Common.EmbeddedSyntaxToken`1[Byte]:this
           4 ( 5.00% of base) : 2648.dasm - Microsoft.CodeAnalysis.ProjectInfo:WithParseOptions(Microsoft.CodeAnalysis.ParseOptions):Microsoft.CodeAnalysis.ProjectInfo:this
           4 ( 4.00% of base) : 83098.dasm - System.Text.Json.SourceGeneration.Tests.SerializationContextTests:EnumAndNullable():this
           4 ( 4.00% of base) : 83227.dasm - System.Text.Json.SourceGeneration.Tests.RealWorldContextTests:EnumAndNullable():this
           4 ( 4.00% of base) : 224537.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus2()
           4 ( 3.85% of base) : 10627.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithScope(int):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
           4 ( 3.85% of base) : 224539.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus4()
           4 ( 3.85% of base) : 10630.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithDocument(Microsoft.CodeAnalysis.Document):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
           4 ( 3.85% of base) : 10629.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithProject(Microsoft.CodeAnalysis.Project):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
           4 ( 3.70% of base) : 224540.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus5()
           4 ( 3.12% of base) : 224548.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus13()
           4 ( 3.12% of base) : 224550.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus15()
           4 ( 2.94% of base) : 224538.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus3()
           4 ( 2.94% of base) : 224544.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus9()
           4 ( 2.94% of base) : 224545.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus10()
           4 ( 2.94% of base) : 224547.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus12()
           4 ( 2.94% of base) : 224549.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus14()
           4 ( 2.94% of base) : 224551.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus16()
           4 ( 2.94% of base) : 224552.dasm - System.Threading.Tasks.Tests.Status.TaskStatusTests:TaskStatus17()
           8 ( 2.38% of base) : 160446.dasm - System.Data.Tests.SqlTypes.SqlByteTest:AdditionOperator():this

Top method improvements (percentages):
         -16 (-23.53% of base) : 192450.dasm - <>c:<Ctor_FromValueNegative_Throw>b__1_0():this
         -16 (-23.53% of base) : 192452.dasm - <>c:<Ctor_ToValueNegative_Throw>b__3_0():this
         -12 (-18.75% of base) : 192449.dasm - <>c:<Ctor_BothValuesNull_Throw>b__0_0():this
         -12 (-18.75% of base) : 192451.dasm - <>c:<Ctor_FromGreaterThanToValue_Throw>b__2_0():this
         -20 (-16.67% of base) : 113741.dasm - Nullable@615[Byte][System.Byte]:Shrinker(System.Nullable`1[Byte]):System.Collections.Generic.IEnumerable`1[Nullable`1]:this
         -12 (-14.29% of base) : 100361.dasm - <>c:<WriteTo_Validation>b__2_0():this
         -16 (-14.29% of base) : 113738.dasm - Nullable@619-3[Byte][System.Byte]:GetFreshEnumerator():System.Collections.Generic.IEnumerator`1[Nullable`1]:this
         -12 (-14.29% of base) : 100391.dasm - <>c:<WriteTo_Validation>b__17_0():this
         -12 (-13.64% of base) : 324492.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 320092.dasm - MyList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 320093.dasm - MyList`1[Byte][System.Byte]:System.Collections.IEnumerable.GetEnumerator():System.Collections.IEnumerator:this
         -12 (-13.64% of base) : 245481.dasm - StringListWrapper`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 325364.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 231249.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 232235.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 68545.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 70831.dasm - SerializationTypes.MyGenericList`1[Byte][System.Byte]:GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.64% of base) : 12435.dasm - KeyCollection[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:System.Collections.Generic.IEnumerable<TKey>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Byte]:this
         -12 (-13.04% of base) : 100419.dasm - <>c:<CreateFromNode_Fail>b__1_1():System.Object:this
         -12 (-13.04% of base) : 100418.dasm - <>c:<CreateFromNode_Fail>b__1_0():System.Object:this

3329 total methods with Code Size differences (3229 improved, 100 regressed), 2439 unchanged.

```

</details>

--------------------------------------------------------------------------------
