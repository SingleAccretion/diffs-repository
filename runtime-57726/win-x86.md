## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 187622
Total bytes of diff: 183359
Total bytes of delta: -4263 (-2.27% of base)
Total relative delta: -45.84
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          19 : 8633.dasm (1.10% of base)
           7 : 3069.dasm (0.22% of base)
           5 : 18881.dasm (0.58% of base)
           3 : 3354.dasm (0.35% of base)
           2 : 14591.dasm (0.35% of base)
           2 : 20306.dasm (0.34% of base)
           2 : 12822.dasm (0.44% of base)
           2 : 17453.dasm (2.78% of base)
           2 : 8646.dasm (0.15% of base)
           2 : 19482.dasm (2.60% of base)
           2 : 13789.dasm (1.21% of base)
           2 : 20854.dasm (0.50% of base)
           2 : 13844.dasm (2.78% of base)
           2 : 8376.dasm (0.30% of base)
           2 : 12058.dasm (0.35% of base)
           1 : 8374.dasm (0.13% of base)

Top file improvements (bytes):
        -620 : 2492.dasm (-11.37% of base)
        -119 : 16163.dasm (-17.76% of base)
        -113 : 16321.dasm (-3.62% of base)
         -62 : 18990.dasm (-2.92% of base)
         -54 : 14429.dasm (-10.38% of base)
         -52 : 9296.dasm (-7.04% of base)
         -52 : 9950.dasm (-7.84% of base)
         -50 : 8593.dasm (-5.46% of base)
         -50 : 6590.dasm (-1.59% of base)
         -45 : 18563.dasm (-5.33% of base)
         -43 : 2952.dasm (-2.79% of base)
         -42 : 18886.dasm (-1.01% of base)
         -38 : 23259.dasm (-4.22% of base)
         -38 : 9819.dasm (-3.77% of base)
         -36 : 5546.dasm (-1.17% of base)
         -36 : 21552.dasm (-5.70% of base)
         -34 : 13955.dasm (-6.39% of base)
         -33 : 18992.dasm (-1.99% of base)
         -32 : 9433.dasm (-3.80% of base)
         -31 : 16202.dasm (-11.23% of base)

364 total files with Code Size differences (348 improved, 16 regressed), 21 unchanged.

Top method regressions (bytes):
          19 ( 1.10% of base) : 8633.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:UnionAwareWriteMembers(bool,bool,System.Type,System.Collections.Generic.List`1[[System.Reflection.MemberInfo, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Sigil.Local,Sigil.Local,byref,WriteMemberDelegate[__Canon]):this
           7 ( 0.22% of base) : 3069.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)
           5 ( 0.58% of base) : 18881.dasm - System.Net.Http.SocketsHttpHandler:ValidateAndNormalizeRequest(System.Net.Http.HttpRequestMessage):System.Exception:this
           3 ( 0.35% of base) : 3354.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           2 ( 0.35% of base) : 14591.dasm - CscBench:CompileBench():bool
           2 ( 0.34% of base) : 20306.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberValueIndented(double):this
           2 ( 0.44% of base) : 12822.dasm - System.Text.Json.Utf8JsonWriter:WriteStringValueMinimized(System.Guid):this
           2 ( 2.78% of base) : 17453.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDouble(double):bool:this
           2 ( 0.15% of base) : 8646.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:WriteMember(System.Reflection.MemberInfo,Sigil.Local):this
           2 ( 2.60% of base) : 19482.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDateTimeOffsetNow(System.DateTimeOffset):bool:this
           2 ( 1.21% of base) : 13789.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:LoadRecursiveTypeDelegate(System.Type):this
           2 ( 0.50% of base) : 20854.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberValueMinimized(double):this
           2 ( 2.78% of base) : 13844.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDecimal(System.Decimal):bool:this
           2 ( 0.30% of base) : 8376.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:DynamicCallOutCheck(System.Reflection.MemberInfo,System.Type,Sigil.Local):bool:this
           2 ( 0.35% of base) : 12058.dasm - System.Text.Json.Utf8JsonWriter:WriteStringValueIndented(System.Guid):this
           1 ( 0.13% of base) : 8374.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:PreloadRecursiveTypes(System.Collections.Generic.HashSet`1[[System.Type, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Collections.Generic.Dictionary`2[[System.Type, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Sigil.Local, Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]]:this

Top method improvements (bytes):
        -620 (-11.37% of base) : 2492.dasm - Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder:BuildSerialize(System.Type,Utf8Json.Internal.Emit.MetaType,System.Reflection.Emit.ILGenerator,System.Action,System.Func`3[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Utf8Json.Internal.Emit.MetaMember, Utf8Json, Version=1.3.7.0, Culture=neutral, PublicKeyToken=8a73d3ba7e392e27],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,int)
        -119 (-17.76% of base) : 16163.dasm - BinopEasyOut:TypeToIndex(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):System.Nullable`1[Int32]
        -113 (-3.62% of base) : 16321.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -62 (-2.92% of base) : 18990.dasm - <ReadLineAsyncInternal>d__63:MoveNext():this
         -54 (-10.38% of base) : 14429.dasm - System.Drawing.Tests.Perf_Graphics_DrawBeziers:Setup():this
         -52 (-7.04% of base) : 9296.dasm - ImageTestData:CreateTestImage(System.Drawing.Imaging.ImageFormat):System.IO.Stream
         -52 (-7.84% of base) : 9950.dasm - EMFloat:Run():double:this
         -50 (-5.46% of base) : 8593.dasm - Jil.Common.Utils:_ReadFieldOperands(System.Reflection.Emit.OpCode,System.Byte[],int,int,byref,byref,byref,byref):System.Nullable`1[Int32]
         -50 (-1.59% of base) : 6590.dasm - MessagePack.Internal.DynamicObjectTypeBuilder:BuildDeserialize(System.Type,MessagePack.Internal.ObjectSerializationInfo,System.Reflection.Emit.ILGenerator,System.Func`3[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[MessagePack.Internal.ObjectSerializationInfo+EmittableMember, MessagePack, Version=1.9.0.0, Culture=neutral, PublicKeyToken=b4a0369545f0a1be],[System.Action, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int)
         -45 (-5.33% of base) : 18563.dasm - Microsoft.Extensions.Logging.EventSource.LoggingEventSource:ParseFilterSpec(System.String,int):Microsoft.Extensions.Logging.LoggerFilterRule[]
         -43 (-2.79% of base) : 2952.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:SetPropertySettingsFromAttributes(Newtonsoft.Json.Serialization.JsonProperty,System.Object,System.String,System.Type,int,byref):this
         -42 (-1.01% of base) : 18886.dasm - <SendAsync>d__4:MoveNext():this
         -38 (-4.22% of base) : 23259.dasm - System.Text.Json.Tests.Perf_Get:GetDecimal():System.Decimal:this
         -38 (-3.77% of base) : 9819.dasm - System.Text.Json.Tests.Perf_Reader:ReadReturnBytes():System.Byte[]:this
         -36 (-1.17% of base) : 5546.dasm - <ReadAsyncInternal>d__186`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
         -36 (-5.70% of base) : 21552.dasm - System.Text.Json.Tests.Perf_Get:GetInt64():long:this
         -34 (-6.39% of base) : 13955.dasm - System.IO.Pipelines.Pipe:PrepareFlush(byref,byref,System.Threading.CancellationToken):this
         -33 (-1.99% of base) : 18992.dasm - <ReadBufferAsync>d__71:MoveNext():this
         -32 (-3.80% of base) : 9433.dasm - System.IO.Strategies.AsyncWindowsFileStreamStrategy:ReadAsyncInternal(System.Memory`1[Byte],System.Threading.CancellationToken):System.Threading.Tasks.ValueTask`1[Int32]:this
         -31 (-11.23% of base) : 16202.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:ClassifyImplicitConstantExpressionConversion(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.Conversion

Top method regressions (percentages):
           2 ( 2.78% of base) : 17453.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDouble(double):bool:this
           2 ( 2.78% of base) : 13844.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDecimal(System.Decimal):bool:this
           2 ( 2.60% of base) : 19482.dasm - System.Buffers.Text.Tests.Utf8FormatterTests:FormatterDateTimeOffsetNow(System.DateTimeOffset):bool:this
           2 ( 1.21% of base) : 13789.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:LoadRecursiveTypeDelegate(System.Type):this
          19 ( 1.10% of base) : 8633.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:UnionAwareWriteMembers(bool,bool,System.Type,System.Collections.Generic.List`1[[System.Reflection.MemberInfo, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Sigil.Local,Sigil.Local,byref,WriteMemberDelegate[__Canon]):this
           5 ( 0.58% of base) : 18881.dasm - System.Net.Http.SocketsHttpHandler:ValidateAndNormalizeRequest(System.Net.Http.HttpRequestMessage):System.Exception:this
           2 ( 0.50% of base) : 20854.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberValueMinimized(double):this
           2 ( 0.44% of base) : 12822.dasm - System.Text.Json.Utf8JsonWriter:WriteStringValueMinimized(System.Guid):this
           2 ( 0.35% of base) : 14591.dasm - CscBench:CompileBench():bool
           3 ( 0.35% of base) : 3354.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           2 ( 0.35% of base) : 12058.dasm - System.Text.Json.Utf8JsonWriter:WriteStringValueIndented(System.Guid):this
           2 ( 0.34% of base) : 20306.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberValueIndented(double):this
           2 ( 0.30% of base) : 8376.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:DynamicCallOutCheck(System.Reflection.MemberInfo,System.Type,Sigil.Local):bool:this
           7 ( 0.22% of base) : 3069.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)
           2 ( 0.15% of base) : 8646.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:WriteMember(System.Reflection.MemberInfo,Sigil.Local):this
           1 ( 0.13% of base) : 8374.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:PreloadRecursiveTypes(System.Collections.Generic.HashSet`1[[System.Type, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Collections.Generic.Dictionary`2[[System.Type, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Sigil.Local, Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]]:this

Top method improvements (percentages):
         -10 (-28.57% of base) : 4509.dasm - System.Drawing.Color:get_DarkCyan():System.Drawing.Color
         -10 (-28.57% of base) : 4510.dasm - System.Drawing.Color:get_DarkGoldenrod():System.Drawing.Color
         -10 (-28.57% of base) : 4531.dasm - System.Drawing.Color:get_ForestGreen():System.Drawing.Color
         -10 (-28.57% of base) : 4532.dasm - System.Drawing.Color:get_Fuchsia():System.Drawing.Color
         -10 (-28.57% of base) : 4545.dasm - System.Drawing.Color:get_Khaki():System.Drawing.Color
         -10 (-28.57% of base) : 4546.dasm - System.Drawing.Color:get_Lavender():System.Drawing.Color
         -10 (-28.57% of base) : 4547.dasm - System.Drawing.Color:get_LavenderBlush():System.Drawing.Color
         -10 (-28.57% of base) : 4548.dasm - System.Drawing.Color:get_LawnGreen():System.Drawing.Color
         -10 (-28.57% of base) : 4565.dasm - System.Drawing.Color:get_Linen():System.Drawing.Color
         -10 (-28.57% of base) : 4566.dasm - System.Drawing.Color:get_Magenta():System.Drawing.Color
         -10 (-28.57% of base) : 4567.dasm - System.Drawing.Color:get_Maroon():System.Drawing.Color
         -10 (-28.57% of base) : 4568.dasm - System.Drawing.Color:get_MediumAquamarine():System.Drawing.Color
         -10 (-28.57% of base) : 4589.dasm - System.Drawing.Color:get_PaleGoldenrod():System.Drawing.Color
         -10 (-28.57% of base) : 4590.dasm - System.Drawing.Color:get_PaleGreen():System.Drawing.Color
         -10 (-28.57% of base) : 4591.dasm - System.Drawing.Color:get_PaleTurquoise():System.Drawing.Color
         -10 (-28.57% of base) : 4626.dasm - System.Drawing.Color:get_Yellow():System.Drawing.Color
         -10 (-28.57% of base) : 4627.dasm - System.Drawing.Color:get_YellowGreen():System.Drawing.Color
         -10 (-28.57% of base) : 4503.dasm - System.Drawing.Color:get_Coral():System.Drawing.Color
         -10 (-28.57% of base) : 4504.dasm - System.Drawing.Color:get_CornflowerBlue():System.Drawing.Color
         -10 (-28.57% of base) : 4515.dasm - System.Drawing.Color:get_DarkOliveGreen():System.Drawing.Color

364 total methods with Code Size differences (348 improved, 16 regressed), 21 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1334631
Total bytes of diff: 1331990
Total bytes of delta: -2641 (-0.20% of base)
Total relative delta: -17.55
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 212907.dasm (1.83% of base)
           8 : 167460.dasm (1.83% of base)
           8 : 245393.dasm (1.83% of base)
           6 : 168572.dasm (0.31% of base)
           6 : 168576.dasm (0.31% of base)
           6 : 168578.dasm (0.31% of base)
           6 : 168694.dasm (0.22% of base)
           6 : 168574.dasm (0.32% of base)
           6 : 168690.dasm (0.22% of base)
           6 : 168692.dasm (0.22% of base)
           5 : 223297.dasm (0.65% of base)
           5 : 223298.dasm (0.19% of base)
           5 : 170348.dasm (0.50% of base)
           5 : 223299.dasm (0.17% of base)
           5 : 81013.dasm (3.88% of base)
           5 : 168348.dasm (9.80% of base)
           5 : 171228.dasm (0.50% of base)
           4 : 168396.dasm (11.76% of base)
           4 : 168400.dasm (10.53% of base)
           4 : 168423.dasm (11.76% of base)

Top file improvements (bytes):
        -100 : 218830.dasm (-1.17% of base)
         -84 : 218535.dasm (-23.46% of base)
         -73 : 167327.dasm (-9.67% of base)
         -62 : 227165.dasm (-16.40% of base)
         -62 : 227589.dasm (-19.81% of base)
         -60 : 218748.dasm (-14.78% of base)
         -53 : 227195.dasm (-15.45% of base)
         -52 : 194789.dasm (-7.84% of base)
         -37 : 168691.dasm (-1.30% of base)
         -33 : 80611.dasm (-35.87% of base)
         -32 : 170880.dasm (-1.36% of base)
         -32 : 171249.dasm (-1.38% of base)
         -32 : 170747.dasm (-1.36% of base)
         -32 : 171256.dasm (-1.38% of base)
         -24 : 75.dasm (-1.01% of base)
         -24 : 168688.dasm (-0.48% of base)
         -22 : 223341.dasm (-2.01% of base)
         -20 : 168695.dasm (-0.71% of base)
         -20 : 168689.dasm (-0.71% of base)
         -20 : 168693.dasm (-0.70% of base)

471 total files with Code Size differences (446 improved, 25 regressed), 48 unchanged.

Top method regressions (bytes):
           8 ( 1.83% of base) : 212907.dasm - Xunit.XunitBase:RunTests():int:this
           8 ( 1.83% of base) : 167460.dasm - Xunit.XunitBase:RunTests():int:this
           8 ( 1.83% of base) : 245393.dasm - Xunit.XunitBase:RunTests():int:this
           6 ( 0.31% of base) : 168572.dasm - Managed:MarshalStructAsParam_AsExpByRef(int)
           6 ( 0.31% of base) : 168576.dasm - Managed:MarshalStructAsParam_AsExpByRefOut(int)
           6 ( 0.31% of base) : 168578.dasm - Managed:MarshalStructAsParam_AsExpByRefInOut(int)
           6 ( 0.22% of base) : 168694.dasm - Managed:MarshalStructAsParam_AsSeqByValInOut(int)
           6 ( 0.32% of base) : 168574.dasm - Managed:MarshalStructAsParam_AsExpByRefIn(int)
           6 ( 0.22% of base) : 168690.dasm - Managed:MarshalStructAsParam_AsSeqByValIn(int)
           6 ( 0.22% of base) : 168692.dasm - Managed:MarshalStructAsParam_AsSeqByValOut(int)
           5 ( 0.65% of base) : 223297.dasm - IlasmPortablePdbTests.IlasmPortablePdbTesterCommon:GetExpectedDocuments(System.String,System.String):System.Collections.Generic.List`1[[IlasmPortablePdbTests.DocumentStub, IlasmPortablePdbTests, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null]]
           5 ( 0.19% of base) : 223298.dasm - IlasmPortablePdbTests.IlasmPortablePdbTesterCommon:GetExpectedForTestMethodDebugInformation(System.String):System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[IlasmPortablePdbTests.MethodDebugInformationStub, IlasmPortablePdbTests, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null]]
           5 ( 0.50% of base) : 170348.dasm - NullableTest2:Run()
           5 ( 0.17% of base) : 223299.dasm - IlasmPortablePdbTests.IlasmPortablePdbTesterCommon:GetExpectedForTestLocalScopes(System.String):System.Collections.Generic.List`1[[IlasmPortablePdbTests.LocalScopeStub, IlasmPortablePdbTests, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null]]
           5 ( 3.88% of base) : 81013.dasm - Program:Main():int
           5 ( 9.80% of base) : 168348.dasm - <>c:<TestPoint3B>b__25_3():this
           5 ( 0.50% of base) : 171228.dasm - NullableTest2:Run()
           4 (11.76% of base) : 168396.dasm - <>c:<TestPoint2B>b__19_3():this
           4 (10.53% of base) : 168400.dasm - <>c:<TestPoint2C>b__20_3():this
           4 (11.76% of base) : 168423.dasm - <>c:<TestNullableB>b__7_2():this

Top method improvements (bytes):
        -100 (-1.17% of base) : 218830.dasm - structinreg.Program3:Main1():int
         -84 (-23.46% of base) : 218535.dasm - AA:reset()
         -73 (-9.67% of base) : 167327.dasm - Internal.IL.ILImporter:FindEnclosingExceptionRegions():this
         -62 (-16.40% of base) : 227165.dasm - AA:reset()
         -62 (-19.81% of base) : 227589.dasm - AA:reset()
         -60 (-14.78% of base) : 218748.dasm - AA:reset()
         -53 (-15.45% of base) : 227195.dasm - AA:reset()
         -52 (-7.84% of base) : 194789.dasm - EMFloat:Run():double:this
         -37 (-1.30% of base) : 168691.dasm - Managed:MarshalStructAsParam_AsSeqByRefIn(int)
         -33 (-35.87% of base) : 80611.dasm - b392262.Program:Main(System.String[]):int
         -32 (-1.36% of base) : 170880.dasm - NullableTest30:Run()
         -32 (-1.38% of base) : 171249.dasm - NullableTest23:Run()
         -32 (-1.36% of base) : 170747.dasm - NullableTest23:Run()
         -32 (-1.38% of base) : 171256.dasm - NullableTest30:Run()
         -24 (-1.01% of base) : 75.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:CalculateFC(int,System.Text.RegularExpressions.RegexNode,int):this
         -24 (-0.48% of base) : 168688.dasm - Managed:MarshalStructAsParam_AsSeqByVal(int)
         -22 (-2.01% of base) : 223341.dasm - SoDBench.Program:Main(System.String[])
         -20 (-0.71% of base) : 168695.dasm - Managed:MarshalStructAsParam_AsSeqByRefInOut(int)
         -20 (-0.71% of base) : 168689.dasm - Managed:MarshalStructAsParam_AsSeqByRef(int)
         -20 (-0.70% of base) : 168693.dasm - Managed:MarshalStructAsParam_AsSeqByRefOut(int)

Top method regressions (percentages):
           4 (11.76% of base) : 168396.dasm - <>c:<TestPoint2B>b__19_3():this
           4 (11.76% of base) : 168423.dasm - <>c:<TestNullableB>b__7_2():this
           4 (10.53% of base) : 168400.dasm - <>c:<TestPoint2C>b__20_3():this
           5 ( 9.80% of base) : 168348.dasm - <>c:<TestPoint3B>b__25_3():this
           2 ( 5.56% of base) : 168426.dasm - <>c:<TestNullableC>b__8_2():this
           5 ( 3.88% of base) : 81013.dasm - Program:Main():int
           1 ( 1.89% of base) : 168352.dasm - <>c:<TestPoint3C>b__26_3():this
           8 ( 1.83% of base) : 212907.dasm - Xunit.XunitBase:RunTests():int:this
           8 ( 1.83% of base) : 167460.dasm - Xunit.XunitBase:RunTests():int:this
           8 ( 1.83% of base) : 245393.dasm - Xunit.XunitBase:RunTests():int:this
           5 ( 0.65% of base) : 223297.dasm - IlasmPortablePdbTests.IlasmPortablePdbTesterCommon:GetExpectedDocuments(System.String,System.String):System.Collections.Generic.List`1[[IlasmPortablePdbTests.DocumentStub, IlasmPortablePdbTests, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null]]
           5 ( 0.50% of base) : 171228.dasm - NullableTest2:Run()
           5 ( 0.50% of base) : 170348.dasm - NullableTest2:Run()
           2 ( 0.46% of base) : 251026.dasm - GitHub_18238:Main():int
           2 ( 0.36% of base) : 239085.dasm - CscBench:CompileBench():bool
           3 ( 0.35% of base) : 41.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           6 ( 0.32% of base) : 168574.dasm - Managed:MarshalStructAsParam_AsExpByRefIn(int)
           6 ( 0.31% of base) : 168572.dasm - Managed:MarshalStructAsParam_AsExpByRef(int)
           6 ( 0.31% of base) : 168576.dasm - Managed:MarshalStructAsParam_AsExpByRefOut(int)
           6 ( 0.31% of base) : 168578.dasm - Managed:MarshalStructAsParam_AsExpByRefInOut(int)

Top method improvements (percentages):
         -33 (-35.87% of base) : 80611.dasm - b392262.Program:Main(System.String[]):int
         -12 (-35.29% of base) : 216020.dasm - TestStruct:Create():TestStruct
          -8 (-34.78% of base) : 215852.dasm - TestStruct:Create():TestStruct
         -10 (-28.57% of base) : 212633.dasm - ColorTesting:GetRed():System.Drawing.Color:this
          -4 (-26.67% of base) : 213244.dasm - ByteAndFloat:Get():ByteAndFloat
          -4 (-26.67% of base) : 213246.dasm - FloatAndByte:Get():FloatAndByte
          -4 (-26.67% of base) : 182840.dasm - TestStruct:Create():TestStruct
          -4 (-26.67% of base) : 182846.dasm - TestStruct:Create():TestStruct
         -84 (-23.46% of base) : 218535.dasm - AA:reset()
          -8 (-22.22% of base) : 242255.dasm - FastTailCallCandidates:CallerAmd64WindowsStructs5Bytes(int,int):int
          -5 (-20.00% of base) : 216022.dasm - TestStruct:Create():TestStruct
         -62 (-19.81% of base) : 227589.dasm - AA:reset()
          -4 (-19.05% of base) : 213254.dasm - PointerAndByte:Get():PointerAndByte
          -4 (-19.05% of base) : 213256.dasm - ByteAndPointer:Get():ByteAndPointer
          -3 (-18.75% of base) : 215854.dasm - TestStruct:Create():TestStruct
          -3 (-18.75% of base) : 182848.dasm - TestStruct:Create():TestStruct
          -3 (-18.75% of base) : 182842.dasm - TestStruct:Create():TestStruct
          -4 (-16.67% of base) : 213250.dasm - ByteAndDouble:Get():ByteAndDouble
          -4 (-16.67% of base) : 213252.dasm - DoubleAndByte:Get():DoubleAndByte
         -62 (-16.40% of base) : 227165.dasm - AA:reset()

471 total methods with Code Size differences (446 improved, 25 regressed), 48 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 274337
Total bytes of diff: 265964
Total bytes of delta: -8373 (-3.05% of base)
Total relative delta: -76.11
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          11 : 213706.dasm (1.34% of base)
           2 : 106273.dasm (2.25% of base)
           2 : 107722.dasm (7.69% of base)
           2 : 106287.dasm (1.77% of base)
           2 : 89192.dasm (0.46% of base)
           2 : 106288.dasm (7.14% of base)
           2 : 106215.dasm (0.46% of base)
           2 : 107723.dasm (7.69% of base)
           2 : 106275.dasm (1.36% of base)
           2 : 107724.dasm (7.69% of base)

Top file improvements (bytes):
       -1675 : 53882.dasm (-9.44% of base)
        -925 : 55143.dasm (-3.17% of base)
        -503 : 213704.dasm (-4.24% of base)
        -175 : 198900.dasm (-8.99% of base)
        -157 : 198896.dasm (-5.60% of base)
        -129 : 24500.dasm (-20.91% of base)
         -67 : 105942.dasm (-8.92% of base)
         -65 : 15771.dasm (-3.15% of base)
         -57 : 169264.dasm (-10.33% of base)
         -46 : 51475.dasm (-11.39% of base)
         -45 : 68928.dasm (-2.97% of base)
         -43 : 292.dasm (-0.98% of base)
         -42 : 54010.dasm (-1.55% of base)
         -37 : 15313.dasm (-1.03% of base)
         -34 : 152295.dasm (-12.88% of base)
         -34 : 86099.dasm (-1.84% of base)
         -33 : 15765.dasm (-2.00% of base)
         -32 : 1499.dasm (-31.07% of base)
         -32 : 170.dasm (-1.07% of base)
         -32 : 128.dasm (-1.07% of base)

657 total files with Code Size differences (647 improved, 10 regressed), 19 unchanged.

Top method regressions (bytes):
          11 ( 1.34% of base) : 213706.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           2 ( 2.25% of base) : 106273.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:GetSumByID():System.Collections.Generic.Dictionary`2[System.Int32, Microsoft.Diagnostics.Tracing.Stacks.CallTreeNodeBase]:this
           2 ( 7.69% of base) : 107722.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetFrameIndex(int):int:this
           2 ( 1.77% of base) : 106287.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:SortInclusiveMetricDecending():this
           2 ( 0.46% of base) : 89192.dasm - <>c__DisplayClass1_0:<ForEach>b__0(Microsoft.Diagnostics.Tracing.Stacks.StackSourceSample):this
           2 ( 7.14% of base) : 106288.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:Sort(System.Collections.Generic.IComparer`1[Microsoft.Diagnostics.Tracing.Stacks.CallTreeNode]):this
           2 ( 0.46% of base) : 106215.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallerCalleeNode:.ctor(System.String,Microsoft.Diagnostics.Tracing.Stacks.CallTree):this
           2 ( 7.69% of base) : 107723.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetNumberOfFoldedFrames(int):int:this
           2 ( 1.36% of base) : 106275.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:AddSample(Microsoft.Diagnostics.Tracing.Stacks.StackSourceSample):this
           2 ( 7.69% of base) : 107724.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetCallerIndex(int):int:this

Top method improvements (bytes):
       -1675 (-9.44% of base) : 53882.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
        -925 (-3.17% of base) : 55143.dasm - Microsoft.CodeAnalysis.DesktopAssemblyIdentityComparer:.cctor()
        -503 (-4.24% of base) : 213704.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -175 (-8.99% of base) : 198900.dasm - System.Drawing.ColorTranslator:FromOle(int):System.Drawing.Color
        -157 (-5.60% of base) : 198896.dasm - System.Drawing.ColorTranslator:InitializeHtmlSysColorTable()
        -129 (-20.91% of base) : 24500.dasm - System.Globalization.HebrewNumber:.cctor()
         -67 (-8.92% of base) : 105942.dasm - Microsoft.Diagnostics.Tracing.Parsers.DynamicManifestTraceEventData:.ctor(System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent],Microsoft.Diagnostics.Tracing.Parsers.ProviderManifest):this
         -65 (-3.15% of base) : 15771.dasm - <ReadLineAsyncInternal>d__63:MoveNext():this
         -57 (-10.33% of base) : 169264.dasm - System.Formats.Asn1.AsnWriter:SortContents(System.Byte[],int,int)
         -46 (-11.39% of base) : 51475.dasm - Microsoft.CodeAnalysis.CodeGen.ILBuilder:EmitSwitch(System.Object[]):this
         -45 (-2.97% of base) : 68928.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:CollectOverloadedCandidates(Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.OverloadResolution+CandidateAnalysisResult],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.OverloadResolution+Candidate],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundNode,bool,bool,bool,byref,byref)
         -43 (-0.98% of base) : 292.dasm - System.Data.Common.SqlConvert:ChangeTypeForXML(System.Object,System.Type):System.Object
         -42 (-1.55% of base) : 54010.dasm - Microsoft.CodeAnalysis.CommonReferenceManager`2:ResolveMetadataReferences(System.__Canon,System.Collections.Generic.Dictionary`2[System.String, System.Collections.Generic.List`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ReferencedAssemblyIdentity[System.__Canon, System.__Canon]]],byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ResolvedReference[System.__Canon, System.__Canon]]:this
         -37 (-1.03% of base) : 15313.dasm - <ReadAsyncSlowPath>d__39:MoveNext():this
         -34 (-12.88% of base) : 152295.dasm - FacetsCompiler:.cctor()
         -34 (-1.84% of base) : 86099.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindArrayBounds(Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize[],bool):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -33 (-2.00% of base) : 15765.dasm - <ReadBufferAsync>d__71:MoveNext():this
         -32 (-31.07% of base) : 1499.dasm - System.Data.SqlTypes.SqlByte:.cctor()
         -32 (-1.07% of base) : 170.dasm - System.Data.Common.SqlDoubleStorage:Aggregate(System.Int32[],int):System.Object:this
         -32 (-1.07% of base) : 128.dasm - System.Data.Common.SqlInt32Storage:Aggregate(System.Int32[],int):System.Object:this

Top method regressions (percentages):
           2 ( 7.69% of base) : 107722.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetFrameIndex(int):int:this
           2 ( 7.69% of base) : 107723.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetNumberOfFoldedFrames(int):int:this
           2 ( 7.69% of base) : 107724.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetCallerIndex(int):int:this
           2 ( 7.14% of base) : 106288.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:Sort(System.Collections.Generic.IComparer`1[Microsoft.Diagnostics.Tracing.Stacks.CallTreeNode]):this
           2 ( 2.25% of base) : 106273.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:GetSumByID():System.Collections.Generic.Dictionary`2[System.Int32, Microsoft.Diagnostics.Tracing.Stacks.CallTreeNodeBase]:this
           2 ( 1.77% of base) : 106287.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:SortInclusiveMetricDecending():this
           2 ( 1.36% of base) : 106275.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:AddSample(Microsoft.Diagnostics.Tracing.Stacks.StackSourceSample):this
          11 ( 1.34% of base) : 213706.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           2 ( 0.46% of base) : 106215.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallerCalleeNode:.ctor(System.String,Microsoft.Diagnostics.Tracing.Stacks.CallTree):this
           2 ( 0.46% of base) : 89192.dasm - <>c__DisplayClass1_0:<ForEach>b__0(Microsoft.Diagnostics.Tracing.Stacks.StackSourceSample):this

Top method improvements (percentages):
          -4 (-36.36% of base) : 138510.dasm - System.Reflection.Metadata.CustomAttributeHandle:op_Implicit(System.Reflection.Metadata.CustomAttributeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138540.dasm - System.Reflection.Metadata.ModuleReferenceHandle:op_Implicit(System.Reflection.Metadata.ModuleReferenceHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138703.dasm - System.Reflection.Metadata.MethodSpecificationHandle:op_Implicit(System.Reflection.Metadata.MethodSpecificationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138716.dasm - System.Reflection.Metadata.MethodImplementationHandle:op_Implicit(System.Reflection.Metadata.MethodImplementationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 33150.dasm - System.Nullable`1:op_Implicit(int):System.Nullable`1[System.Threading.LazyThreadSafetyMode]
          -4 (-36.36% of base) : 65081.dasm - DimensionSize:ConstantSize(int):Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize
          -4 (-36.36% of base) : 137703.dasm - System.Reflection.Metadata.MethodDebugInformationHandle:op_Implicit(System.Reflection.Metadata.MethodDebugInformationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 137716.dasm - System.Reflection.Metadata.DocumentHandle:op_Implicit(System.Reflection.Metadata.DocumentHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138591.dasm - System.Reflection.Metadata.StandaloneSignatureHandle:op_Implicit(System.Reflection.Metadata.StandaloneSignatureHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138602.dasm - System.Reflection.Metadata.PropertyDefinitionHandle:op_Implicit(System.Reflection.Metadata.PropertyDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138755.dasm - System.Reflection.Metadata.AssemblyDefinitionHandle:op_Implicit(System.Reflection.Metadata.AssemblyDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 2057.dasm - System.Data.SqlTypes.SqlInt32:op_Implicit(int):System.Data.SqlTypes.SqlInt32
          -4 (-36.36% of base) : 137638.dasm - System.Reflection.Metadata.CustomDebugInformationHandle:op_Implicit(System.Reflection.Metadata.CustomDebugInformationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 137651.dasm - System.Reflection.Metadata.ImportScopeHandle:op_Implicit(System.Reflection.Metadata.ImportScopeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138484.dasm - System.Reflection.Metadata.ConstantHandle:op_Implicit(System.Reflection.Metadata.ConstantHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138497.dasm - System.Reflection.Metadata.DeclarativeSecurityAttributeHandle:op_Implicit(System.Reflection.Metadata.DeclarativeSecurityAttributeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138651.dasm - System.Reflection.Metadata.TypeSpecificationHandle:op_Implicit(System.Reflection.Metadata.TypeSpecificationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138664.dasm - System.Reflection.Metadata.TypeReferenceHandle:op_Implicit(System.Reflection.Metadata.TypeReferenceHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138388.dasm - System.Reflection.Metadata.GuidHandle:op_Implicit(System.Reflection.Metadata.GuidHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 138448.dasm - System.Reflection.Metadata.UserStringHandle:op_Implicit(System.Reflection.Metadata.UserStringHandle):System.Reflection.Metadata.Handle

657 total methods with Code Size differences (647 improved, 10 regressed), 19 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 970358
Total bytes of diff: 948196
Total bytes of delta: -22162 (-2.28% of base)
Total relative delta: -169.83
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         118 : 116961.dasm (3.33% of base)
           8 : 229099.dasm (4.62% of base)
           7 : 126702.dasm (0.47% of base)
           7 : 105744.dasm (0.21% of base)
           7 : 105637.dasm (0.22% of base)
           5 : 127413.dasm (0.58% of base)
           5 : 202342.dasm (1.16% of base)
           5 : 230266.dasm (3.36% of base)
           5 : 230267.dasm (3.47% of base)
           4 : 126655.dasm (0.27% of base)
           4 : 202296.dasm (0.88% of base)
           4 : 205297.dasm (0.17% of base)
           3 : 41.dasm (0.35% of base)
           2 : 126667.dasm (0.11% of base)
           2 : 156432.dasm (0.25% of base)
           2 : 156456.dasm (0.33% of base)
           2 : 156457.dasm (0.35% of base)
           2 : 156458.dasm (0.25% of base)
           2 : 156459.dasm (0.26% of base)
           2 : 156460.dasm (0.17% of base)

Top file improvements (bytes):
        -184 : 116877.dasm (-5.16% of base)
        -175 : 190737.dasm (-8.97% of base)
        -157 : 190741.dasm (-4.38% of base)
        -155 : 80559.dasm (-7.47% of base)
        -132 : 218080.dasm (-11.16% of base)
        -124 : 54361.dasm (-9.88% of base)
        -119 : 44986.dasm (-17.68% of base)
        -112 : 214696.dasm (-8.53% of base)
        -108 : 169458.dasm (-22.59% of base)
        -107 : 183988.dasm (-5.64% of base)
         -99 : 169456.dasm (-9.58% of base)
         -95 : 80555.dasm (-4.85% of base)
         -87 : 217822.dasm (-6.93% of base)
         -87 : 216728.dasm (-6.85% of base)
         -87 : 215948.dasm (-6.85% of base)
         -81 : 44519.dasm (-2.06% of base)
         -80 : 216657.dasm (-2.40% of base)
         -80 : 42007.dasm (-2.04% of base)
         -80 : 215607.dasm (-2.40% of base)
         -78 : 193653.dasm (-4.30% of base)

2280 total files with Code Size differences (2182 improved, 98 regressed), 59 unchanged.

Top method regressions (bytes):
         118 ( 3.33% of base) : 116961.dasm - System.Data.Common.SqlMoneyStorage:Aggregate(System.Int32[],int):System.Object:this
           8 ( 4.62% of base) : 229099.dasm - Microsoft.Xunit.Performance.BenchmarkTestFrameworkExecutor:RunTestCases(System.Collections.Generic.IEnumerable`1[[Xunit.Sdk.IXunitTestCase, xunit.core, Version=2.4.1.0, Culture=neutral, PublicKeyToken=8d05b1bb7a6fdb6c]],Xunit.Abstractions.IMessageSink,Xunit.Abstractions.ITestFrameworkExecutionOptions):this
           7 ( 0.47% of base) : 126702.dasm - <ReadAsync>d__6:MoveNext():this
           7 ( 0.21% of base) : 105744.dasm - Newtonsoft.Json.JsonWriter:WriteValueAsync(Newtonsoft.Json.JsonWriter,int,System.Object,System.Threading.CancellationToken):System.Threading.Tasks.Task
           7 ( 0.22% of base) : 105637.dasm - Newtonsoft.Json.JsonWriter:WriteValue(Newtonsoft.Json.JsonWriter,int,System.Object)
           5 ( 0.58% of base) : 127413.dasm - System.Net.Http.SocketsHttpHandler:ValidateAndNormalizeRequest(System.Net.Http.HttpRequestMessage):System.Exception:this
           5 ( 1.16% of base) : 202342.dasm - System.Net.Http.WinHttpHandler:GetChunkedModeForSend(System.Net.Http.HttpRequestMessage):int
           5 ( 3.36% of base) : 230266.dasm - Xunit.Runners.AssemblyRunner:GetDiscoveryOptions(System.Nullable`1[Boolean],System.Nullable`1[TestMethodDisplay],System.Nullable`1[TestMethodDisplayOptions],System.Nullable`1[Boolean],System.Nullable`1[Boolean]):Xunit.Abstractions.ITestFrameworkDiscoveryOptions:this
           5 ( 3.47% of base) : 230267.dasm - Xunit.Runners.AssemblyRunner:GetExecutionOptions(System.Nullable`1[Boolean],System.Nullable`1[Boolean],System.Nullable`1[Int32],System.Nullable`1[Boolean]):Xunit.Abstractions.ITestFrameworkExecutionOptions:this
           4 ( 0.27% of base) : 126655.dasm - <ReadAsync>d__2:MoveNext():this
           4 ( 0.88% of base) : 202296.dasm - System.Net.Http.WinHttpHandler:OpenRequestHandle(System.Net.Http.WinHttpRequestState,SafeWinHttpHandle,System.String,byref,byref):this
           4 ( 0.17% of base) : 205297.dasm - <SendRequest>d__195:MoveNext():this
           3 ( 0.35% of base) : 41.dasm - System.Text.RegularExpressions.RegexCharClass:Canonicalize():this
           2 ( 0.11% of base) : 126667.dasm - <ReadAsync>d__3:MoveNext():this
           2 ( 0.25% of base) : 156432.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberIndented(System.ReadOnlySpan`1[Char],float):this
           2 ( 0.33% of base) : 156456.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberMinimized(System.ReadOnlySpan`1[Char],System.Decimal):this
           2 ( 0.35% of base) : 156457.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberMinimized(System.ReadOnlySpan`1[Byte],System.Decimal):this
           2 ( 0.25% of base) : 156458.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberIndented(System.ReadOnlySpan`1[Char],System.Decimal):this
           2 ( 0.26% of base) : 156459.dasm - System.Text.Json.Utf8JsonWriter:WriteNumberIndented(System.ReadOnlySpan`1[Byte],System.Decimal):this
           2 ( 0.17% of base) : 156460.dasm - System.Text.Json.Utf8JsonWriter:WritePropertyName(System.Decimal):this

Top method improvements (bytes):
        -184 (-5.16% of base) : 116877.dasm - System.Data.Common.SqlDecimalStorage:Aggregate(System.Int32[],int):System.Object:this
        -175 (-8.97% of base) : 190737.dasm - System.Drawing.ColorTranslator:FromOle(int):System.Drawing.Color
        -157 (-4.38% of base) : 190741.dasm - System.Drawing.ColorTranslator:InitializeHtmlSysColorTable()
        -155 (-7.47% of base) : 80559.dasm - Microsoft.CodeAnalysis.CodeGen.SwitchIntegralJumpTableEmitter:EmitSwitchBucketsLinearLeaf(System.Collections.Immutable.ImmutableArray`1[SwitchBucket],int,int):this
        -132 (-11.16% of base) : 218080.dasm - System.Security.Cryptography.Pkcs.CmsSignature:DsaDerToIeee(System.ReadOnlyMemory`1[Byte],System.Span`1[Byte]):bool
        -124 (-9.88% of base) : 54361.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitCaseBlocks(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundCaseBlock, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.GeneratedLabelSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Symbols.LabelSymbol):this
        -119 (-17.68% of base) : 44986.dasm - BinopEasyOut:TypeToIndex(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):System.Nullable`1[Int32]
        -112 (-8.53% of base) : 214696.dasm - Internal.Cryptography.AsymmetricAlgorithmHelpers:ConvertDerToIeee1363(System.ReadOnlySpan`1[Byte],int,System.Span`1[Byte]):int
        -108 (-22.59% of base) : 169458.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:WithGlob(System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation:this
        -107 (-5.64% of base) : 183988.dasm - System.Data.Odbc.OdbcMetaDataFactory:.ctor(System.IO.Stream,System.String,System.String,System.Data.Odbc.OdbcConnection):this
         -99 (-9.58% of base) : 169456.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:WithFileLineAndElement(System.String,System.Nullable`1[Int32],Microsoft.Build.Framework.IProjectElement):Microsoft.Build.Framework.Profiler.EvaluationLocation:this
         -95 (-4.85% of base) : 80555.dasm - Microsoft.CodeAnalysis.CodeGen.SwitchIntegralJumpTableEmitter:EmitJumpTable():this
         -87 (-6.93% of base) : 217822.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -87 (-6.85% of base) : 216728.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -87 (-6.85% of base) : 215948.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[Byte],int):System.Security.Cryptography.Asn1.PBES2Params
         -81 (-2.06% of base) : 44519.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitCondBranchCore(Microsoft.CodeAnalysis.CSharp.BoundExpression,byref,bool):this
         -80 (-2.40% of base) : 216657.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -80 (-2.04% of base) : 42007.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ConstantEvaluationHelpers:OrderGraph(System.Collections.Generic.Dictionary`2[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.CSharp.Symbols.ConstantEvaluationHelpers+Node`1[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[FieldInfo])
         -80 (-2.40% of base) : 215607.dasm - System.Security.Cryptography.EccKeyFormatHelper:GetSpecifiedECCurveCore(System.Security.Cryptography.Asn1.SpecifiedECDomain):System.Security.Cryptography.ECCurve
         -78 (-4.30% of base) : 193653.dasm - <CopyToAsync>d__38:MoveNext():this

Top method regressions (percentages):
           2 (11.11% of base) : 156636.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.String):System.Text.Json.Nodes.JsonNode
           2 (11.11% of base) : 156639.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(int):System.Text.Json.Nodes.JsonNode
           2 (11.11% of base) : 156628.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(int):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156669.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(bool):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156671.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(ubyte):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156673.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(ushort):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156637.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(ushort):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156626.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(short):System.Text.Json.Nodes.JsonNode
           2 ( 9.52% of base) : 156632.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(byte):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 156670.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[Boolean]):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 156672.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[Byte]):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 156674.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[Char]):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 83558.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetCallerIndex(int):int:this
           2 ( 8.00% of base) : 83559.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetNumberOfFoldedFrames(int):int:this
           2 ( 8.00% of base) : 83560.dasm - Diagnostics.Tracing.StackSources.FilterStackSource:GetFrameIndex(int):int:this
           2 ( 8.00% of base) : 156633.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[SByte]):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 156638.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[UInt16]):System.Text.Json.Nodes.JsonNode
           2 ( 8.00% of base) : 156627.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(System.Nullable`1[Int16]):System.Text.Json.Nodes.JsonNode
           2 ( 7.41% of base) : 85147.dasm - Microsoft.Diagnostics.Tracing.Stacks.CallTree:Sort(System.Collections.Generic.IComparer`1[[Microsoft.Diagnostics.Tracing.Stacks.CallTreeNode, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
           2 ( 7.14% of base) : 156641.dasm - System.Text.Json.Nodes.JsonNode:op_Implicit(long):System.Text.Json.Nodes.JsonNode

Top method improvements (percentages):
          -4 (-36.36% of base) : 149597.dasm - System.Reflection.Metadata.AssemblyDefinitionHandle:op_Implicit(System.Reflection.Metadata.AssemblyDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149610.dasm - System.Reflection.Metadata.InterfaceImplementationHandle:op_Implicit(System.Reflection.Metadata.InterfaceImplementationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149623.dasm - System.Reflection.Metadata.MethodDefinitionHandle:op_Implicit(System.Reflection.Metadata.MethodDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 71635.dasm - DimensionSize:ConstantSize(int):DimensionSize
          -4 (-36.36% of base) : 149637.dasm - System.Reflection.Metadata.MethodImplementationHandle:op_Implicit(System.Reflection.Metadata.MethodImplementationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149650.dasm - System.Reflection.Metadata.MethodSpecificationHandle:op_Implicit(System.Reflection.Metadata.MethodSpecificationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149663.dasm - System.Reflection.Metadata.TypeDefinitionHandle:op_Implicit(System.Reflection.Metadata.TypeDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149676.dasm - System.Reflection.Metadata.ExportedTypeHandle:op_Implicit(System.Reflection.Metadata.ExportedTypeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149689.dasm - System.Reflection.Metadata.TypeReferenceHandle:op_Implicit(System.Reflection.Metadata.TypeReferenceHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149702.dasm - System.Reflection.Metadata.TypeSpecificationHandle:op_Implicit(System.Reflection.Metadata.TypeSpecificationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149715.dasm - System.Reflection.Metadata.MemberReferenceHandle:op_Implicit(System.Reflection.Metadata.MemberReferenceHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149726.dasm - System.Reflection.Metadata.FieldDefinitionHandle:op_Implicit(System.Reflection.Metadata.FieldDefinitionHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150682.dasm - System.Reflection.Metadata.MethodDebugInformationHandle:op_Implicit(System.Reflection.Metadata.MethodDebugInformationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150696.dasm - System.Reflection.Metadata.LocalScopeHandle:op_Implicit(System.Reflection.Metadata.LocalScopeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150708.dasm - System.Reflection.Metadata.LocalVariableHandle:op_Implicit(System.Reflection.Metadata.LocalVariableHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150720.dasm - System.Reflection.Metadata.LocalConstantHandle:op_Implicit(System.Reflection.Metadata.LocalConstantHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150733.dasm - System.Reflection.Metadata.ImportScopeHandle:op_Implicit(System.Reflection.Metadata.ImportScopeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 150746.dasm - System.Reflection.Metadata.CustomDebugInformationHandle:op_Implicit(System.Reflection.Metadata.CustomDebugInformationHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149857.dasm - System.Reflection.Metadata.DeclarativeSecurityAttributeHandle:op_Implicit(System.Reflection.Metadata.DeclarativeSecurityAttributeHandle):System.Reflection.Metadata.Handle
          -4 (-36.36% of base) : 149870.dasm - System.Reflection.Metadata.ConstantHandle:op_Implicit(System.Reflection.Metadata.ConstantHandle):System.Reflection.Metadata.Handle

2280 total methods with Code Size differences (2182 improved, 98 regressed), 59 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4750661
Total bytes of diff: 4657982
Total bytes of delta: -92679 (-1.95% of base)
Total relative delta: -372.13
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         137 : 201525.dasm (2.67% of base)
          89 : 95534.dasm (3.29% of base)
          88 : 160579.dasm (3.79% of base)
          75 : 80170.dasm (2.08% of base)
          65 : 265684.dasm (15.33% of base)
          45 : 160570.dasm (6.54% of base)
          38 : 160572.dasm (4.90% of base)
          35 : 262974.dasm (3.85% of base)
          35 : 262976.dasm (3.85% of base)
          30 : 264769.dasm (15.38% of base)
          27 : 94743.dasm (1.33% of base)
          25 : 204630.dasm (4.97% of base)
          25 : 205774.dasm (4.97% of base)
          25 : 205775.dasm (4.97% of base)
          25 : 205777.dasm (4.97% of base)
          25 : 204714.dasm (4.97% of base)
          25 : 204715.dasm (4.97% of base)
          25 : 205060.dasm (4.97% of base)
          25 : 205062.dasm (4.97% of base)
          25 : 205244.dasm (4.96% of base)

Top file improvements (bytes):
        -578 : 94706.dasm (-26.39% of base)
        -431 : 94803.dasm (-14.39% of base)
        -384 : 169283.dasm (-7.59% of base)
        -360 : 169312.dasm (-6.36% of base)
        -322 : 169232.dasm (-7.08% of base)
        -299 : 51988.dasm (-5.84% of base)
        -289 : 164781.dasm (-15.06% of base)
        -278 : 52007.dasm (-6.32% of base)
        -270 : 201521.dasm (-5.98% of base)
        -262 : 169186.dasm (-2.89% of base)
        -243 : 160577.dasm (-14.91% of base)
        -240 : 144808.dasm (-4.26% of base)
        -238 : 182978.dasm (-7.14% of base)
        -238 : 182974.dasm (-8.10% of base)
        -232 : 183094.dasm (-7.29% of base)
        -232 : 183098.dasm (-6.58% of base)
        -232 : 335412.dasm (-2.32% of base)
        -228 : 166964.dasm (-9.92% of base)
        -226 : 201373.dasm (-8.15% of base)
        -220 : 335455.dasm (-2.43% of base)

6347 total files with Code Size differences (5631 improved, 716 regressed), 1996 unchanged.

Top method regressions (bytes):
         137 ( 2.67% of base) : 201525.dasm - System.Reflection.Metadata.Tests.HandleTests:IsNil():this
          89 ( 3.29% of base) : 95534.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:SkipIncomplete(System.String,int,ubyte)
          88 ( 3.79% of base) : 160579.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:ThanOrEqualOperators():this
          75 ( 2.08% of base) : 80170.dasm - <ExplicitConversion_FromSingle_TestData>d__33:MoveNext():bool:this
          65 (15.33% of base) : 265684.dasm - Microsoft.Extensions.Logging.Test.EventIdTest:Equality_operations():this
          45 ( 6.54% of base) : 160570.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:Greaters():this
          38 ( 4.90% of base) : 160572.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:NotEquals():this
          35 ( 3.85% of base) : 262974.dasm - Microsoft.Extensions.DependencyModel.Tests.DependencyContextJsonReaderTest:ReadsCompilationOptions():this
          35 ( 3.85% of base) : 262976.dasm - Microsoft.Extensions.DependencyModel.Tests.DependencyContextJsonReaderTest:IgnoresUnknownPropertiesInCompilationOptions():this
          30 (15.38% of base) : 264769.dasm - Microsoft.Extensions.Logging.Console.Test.ConsoleLoggerTest:IsEnabledReturnsCorrectValue()
          27 ( 1.33% of base) : 94743.dasm - System.Text.Json.Nodes.Tests.OperatorTests:ImplicitOperators_FromNullableValues()
          25 ( 4.97% of base) : 204630.dasm - System.Tests.ByteTests_GenericMath:TryCreateFromByteTest()
          25 ( 4.97% of base) : 205774.dasm - System.Tests.UIntPtrTests_GenericMath:TryCreateFromUInt16Test()
          25 ( 4.97% of base) : 205775.dasm - System.Tests.UIntPtrTests_GenericMath:TryCreateFromUInt32Test()
          25 ( 4.97% of base) : 205777.dasm - System.Tests.UIntPtrTests_GenericMath:TryCreateFromUIntPtrTest()
          25 ( 4.97% of base) : 204714.dasm - System.Tests.CharTests_GenericMath:TryCreateFromByteTest()
          25 ( 4.97% of base) : 204715.dasm - System.Tests.CharTests_GenericMath:TryCreateFromCharTest()
          25 ( 4.97% of base) : 205060.dasm - System.Tests.Int16Tests_GenericMath:TryCreateFromByteTest()
          25 ( 4.97% of base) : 205062.dasm - System.Tests.Int16Tests_GenericMath:TryCreateFromInt16Test()
          25 ( 4.96% of base) : 205244.dasm - System.Tests.Int64Tests_GenericMath:TryCreateFromSByteTest()

Top method improvements (bytes):
        -578 (-26.39% of base) : 94706.dasm - System.Text.Json.Nodes.Tests.JsonNodeTests:JsonTypes_Deserialize()
        -431 (-14.39% of base) : 94803.dasm - System.Text.Json.Nodes.Tests.ParseTests:Parse_TryGetValue()
        -384 (-7.59% of base) : 169283.dasm - System.Formats.Asn1.Tests.Reader.ReadEnumerated:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
        -360 (-6.36% of base) : 169312.dasm - System.Formats.Asn1.Tests.Reader.ReadIA5String:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
        -322 (-7.08% of base) : 169232.dasm - System.Formats.Asn1.Tests.Reader.ReadBitString:ExpectedTag_IgnoresConstructed(int,System.String,int,int)
        -299 (-5.84% of base) : 51988.dasm - <TestData>d__0:MoveNext():bool:this
        -289 (-15.06% of base) : 164781.dasm - System.Drawing.Drawing2D.Tests.GraphicsPathTests:AssertIsOutlineVisibleLine(System.Drawing.Graphics):this
        -278 (-6.32% of base) : 52007.dasm - <TestData>d__0:MoveNext():bool:this
        -270 (-5.98% of base) : 201521.dasm - System.Reflection.Metadata.Tests.HandleTests:Conversions_Handles():this
        -262 (-2.89% of base) : 169186.dasm - System.Formats.Asn1.Tests.Reader.ComprehensiveReadTests:ReadMicrosoftComCert()
        -243 (-14.91% of base) : 160577.dasm - System.Data.Tests.SqlTypes.SqlInt16Test:ArithmeticOperators():this
        -240 (-4.26% of base) : 144808.dasm - <SendAsync>d__2:MoveNext():this
        -238 (-7.14% of base) : 182978.dasm - <Max_NullableDouble_TestData>d__38:MoveNext():bool:this
        -238 (-8.10% of base) : 182974.dasm - <Max_NullableFloat_TestData>d__35:MoveNext():bool:this
        -232 (-7.29% of base) : 183094.dasm - <Min_NullableFloat_TestData>d__29:MoveNext():bool:this
        -232 (-6.58% of base) : 183098.dasm - <Min_NullableDouble_TestData>d__32:MoveNext():bool:this
        -232 (-2.32% of base) : 335412.dasm - TCWriteState:AddChildren():this
        -228 (-9.92% of base) : 166964.dasm - <Ctor_Point_TestData>d__0:MoveNext():bool:this
        -226 (-8.15% of base) : 201373.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataAggregatorTests:RowCounts():this
        -220 (-2.43% of base) : 335455.dasm - XObjectBuilderTest:AddChildren():this

Top method regressions (percentages):
           5 (23.81% of base) : 201698.dasm - System.Reflection.Metadata.Tests.AssertEx:Fail(System.String)
           5 (21.74% of base) : 184804.dasm - System.SpanTests.MemoryMarshalTests:ReadOnlySpanGetReferenceEmpty()
           5 (21.74% of base) : 184830.dasm - System.SpanTests.MemoryMarshalTests:SpanGetReferenceEmpty()
           5 (21.74% of base) : 184838.dasm - System.SpanTests.MemoryMarshalTests:SpanGetReferencePointerCreateSpan()
           5 (21.74% of base) : 184840.dasm - System.SpanTests.MemoryMarshalTests:ReadOnlySpanGetReferencePointerCreateReadOnlySpan()
           5 (21.74% of base) : 313848.dasm - System.Net.WebSockets.Tests.WebSocketTests:IsApplicationTargeting45_AlwaysTrue()
          25 (21.74% of base) : 322249.dasm - System.Runtime.CompilerServices.UnsafeTests:IsNullRef_Null()
           5 (21.74% of base) : 284177.dasm - <>c:<AddHandler_RemoveHandler_Roundtrips>b__0_1():this
           5 (21.74% of base) : 219048.dasm - DummyClass:.ctor():this
           5 (21.74% of base) : 266376.dasm - Microsoft.Extensions.Primitives.StringSegmentTest:StringSegment_CreateEmptySegment():this
           5 (21.74% of base) : 286263.dasm - System.Tests.ConsoleKeyInfoTests:ImplementsIEquatableInterface():this
           5 (21.74% of base) : 312320.dasm - System.Net.Security.Tests.ExtendedProtectionPolicyTest:ExtendedProtectionPolicy_OSSupportsExtendedProtection():this
          15 (21.13% of base) : 285204.dasm - MonoTests.System.Configuration.DefaultValidatorTest:CanValidate():this
          10 (20.41% of base) : 164355.dasm - System.Drawing.Printing.Tests.MarginsConverterTests:GetCreateInstanceSupported():this
          10 (20.41% of base) : 157309.dasm - System.ComponentModel.TypeConverterTests.ColorConverterTests:GetStandardValuesSupported():this
          10 (20.41% of base) : 72492.dasm - System.Runtime.CompilerServices.Tests.RuntimeFeatureTests:DynamicCode_Jit()
          10 (20.41% of base) : 72493.dasm - System.Runtime.CompilerServices.Tests.RuntimeFeatureTests:DynamicCode_Browser()
           5 (20.00% of base) : 155491.dasm - <>c:<Refresh_NoChanges_ShouldNotFireOnChanged>b__35_0(System.Object,System.ComponentModel.Composition.Hosting.ComposablePartCatalogChangeEventArgs):this
           5 (18.52% of base) : 153030.dasm - System.ComponentModel.Composition.CompositionResultOfTTest:Constructor1_ShouldSetSucceededPropertyToTrue():this
           5 (18.52% of base) : 153031.dasm - System.ComponentModel.Composition.CompositionResultOfTTest:Constructor2_ShouldSetSucceededPropertyToTrue():this

Top method improvements (percentages):
         -15 (-40.54% of base) : 14190.dasm - ParameterTypeInfoProvider:get_ComplexInfo():ParameterTypeInfo
         -15 (-36.59% of base) : 14199.dasm - ParameterTypeInfoProvider:GetFunctionPointerType(System.Reflection.Metadata.MethodSignature`1[ParameterTypeInfo]):ParameterTypeInfo:this
         -15 (-36.59% of base) : 14200.dasm - ParameterTypeInfoProvider:GetGenericMethodParameter(System.Object,int):ParameterTypeInfo:this
         -15 (-36.59% of base) : 14201.dasm - ParameterTypeInfoProvider:GetModifiedType(ParameterTypeInfo,ParameterTypeInfo,bool):ParameterTypeInfo:this
          -4 (-36.36% of base) : 107475.dasm - ImTools.Opt`1[Int32][System.Int32]:op_Implicit(int):ImTools.Opt`1[Int32]
          -4 (-36.36% of base) : 43084.dasm - System.Linq.Expressions.Tests.CallTests:ToDayOfWeekOpt1(int):System.Nullable`1[DayOfWeek]
          -9 (-32.14% of base) : 330638.dasm - ThrowsExceptionFromDispose:MoveNextAsync():System.Threading.Tasks.ValueTask`1[Boolean]:this
         -13 (-31.71% of base) : 10618.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithCodeActionEquivalenceKey(System.String):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
         -13 (-31.71% of base) : 10619.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithProject(Microsoft.CodeAnalysis.Project):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
          -9 (-31.03% of base) : 2403.dasm - Microsoft.CodeAnalysis.DocumentInfo:WithTextLoader(Microsoft.CodeAnalysis.TextLoader):Microsoft.CodeAnalysis.DocumentInfo:this
          -4 (-30.77% of base) : 75670.dasm - System.Tests.Types.GenericTypeParameter1Of1Tests:get_GenericParameterAttributes():System.Nullable`1[GenericParameterAttributes]:this
          -4 (-30.77% of base) : 75671.dasm - System.Tests.Types.GenericTypeParameter1Of1Tests:get_GenericParameterPosition():System.Nullable`1[Int32]:this
          -8 (-30.77% of base) : 928.dasm - Roslyn.Utilities.ValueTaskFactory:FromResult(int):System.Threading.Tasks.ValueTask`1[Int32]
         -22 (-30.56% of base) : 5450.dasm - Microsoft.CodeAnalysis.Shared.TestHooks.AsynchronousOperationListenerProvider:Enable(bool)
         -26 (-30.23% of base) : 113701.dasm - Nullable@619-3[Byte][System.Byte]:GetFreshEnumerator():System.Collections.Generic.IEnumerator`1[Nullable`1]:this
         -12 (-30.00% of base) : 10620.dasm - Microsoft.CodeAnalysis.CodeFixes.FixAllState:WithDocument(Microsoft.CodeAnalysis.Document):Microsoft.CodeAnalysis.CodeFixes.FixAllState:this
          -6 (-30.00% of base) : 260547.dasm - Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.PatternTestResult:Success(System.String):Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.PatternTestResult
          -4 (-28.57% of base) : 247713.dasm - FluentAssertions.Common.Configuration:set_ValueFormatterDetectionMode(int):this
          -4 (-28.57% of base) : 244401.dasm - Castle.Core.Logging.ConsoleFactory:.ctor(int):this
          -4 (-28.57% of base) : 244496.dasm - Castle.Core.Logging.TraceLoggerFactory:.ctor(int):this

6347 total methods with Code Size differences (5631 improved, 716 regressed), 1996 unchanged.

```

</details>

--------------------------------------------------------------------------------
