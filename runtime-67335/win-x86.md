## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9009069 (overridden on cmd)
Total bytes of diff: 9001229 (overridden on cmd)
Total bytes of delta: -7840 (-0.09 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          28 : 25679.dasm (0.23% of base)
           7 : 7884.dasm (2.24% of base)

Top file improvements (bytes):
        -320 : 2446.dasm (-1.67% of base)
        -156 : 25126.dasm (-0.82% of base)
         -95 : 5550.dasm (-0.67% of base)
         -80 : 7681.dasm (-1.18% of base)
         -62 : 3096.dasm (-2.21% of base)
         -45 : 2878.dasm (-1.60% of base)
         -44 : 1051.dasm (-0.62% of base)
         -43 : 10643.dasm (-2.86% of base)
         -27 : 7953.dasm (-0.85% of base)
         -24 : 5566.dasm (-1.17% of base)
         -23 : 7296.dasm (-0.99% of base)
         -21 : 7459.dasm (-0.30% of base)
         -21 : 7405.dasm (-0.57% of base)
         -20 : 12234.dasm (-1.08% of base)
         -20 : 11824.dasm (-4.31% of base)
         -20 : 3325.dasm (-2.36% of base)
         -19 : 3044.dasm (-1.13% of base)
         -19 : 11275.dasm (-9.13% of base)
         -18 : 5617.dasm (-3.85% of base)
         -17 : 25775.dasm (-1.71% of base)

6006 total files with Code Size differences (6004 improved, 2 regressed), 165 unchanged.

Top method regressions (bytes):
          28 ( 0.23% of base) : 25679.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):this
           7 ( 2.24% of base) : 7884.dasm - Newtonsoft.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Newtonsoft.Json.JsonSerializer):System.String

Top method improvements (bytes):
        -320 (-1.67% of base) : 2446.dasm - Jil.Options:.cctor()
        -156 (-0.82% of base) : 25126.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
         -95 (-0.67% of base) : 5550.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
         -80 (-1.18% of base) : 7681.dasm - Jil.Deserialize.Methods:.cctor()
         -62 (-2.21% of base) : 3096.dasm - System.Runtime.Serialization.DictionaryGlobals:.cctor()
         -45 (-1.60% of base) : 2878.dasm - Jil.Serialize.Methods:.cctor()
         -44 (-0.62% of base) : 1051.dasm - System.Text.RegularExpressions.RegexCompiler:.cctor()
         -43 (-2.86% of base) : 10643.dasm - System.Runtime.Serialization.Formatters.Binary.Converter:.cctor()
         -27 (-0.85% of base) : 7953.dasm - <>c:<get_IntrinsicTypeConverters>b__24_0():System.Collections.Generic.Dictionary`2[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.ComponentModel.ReflectTypeDescriptionProvider+IntrinsicTypeConverterData, System.ComponentModel.TypeConverter, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
         -24 (-1.17% of base) : 5566.dasm - System.Net.Http.Headers.GenericHeaderParser:.cctor()
         -23 (-0.99% of base) : 7296.dasm - MessagePack.Resolvers.DynamicUnionResolver:.cctor()
         -21 (-0.30% of base) : 7459.dasm - MessagePack.MessagePackBinary:.cctor()
         -21 (-0.57% of base) : 7405.dasm - MessagePackBinaryTypeInfo:.cctor()
         -20 (-2.36% of base) : 3325.dasm - PerfLabTests.GetMember:.cctor()
         -20 (-1.08% of base) : 12234.dasm - System.Diagnostics.Tracing.PropertyValue:GetFactory(System.Type):System.Func`2[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Diagnostics.Tracing.PropertyValue, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
         -20 (-4.31% of base) : 11824.dasm - System.Runtime.Serialization.Json.JsonGlobals:.cctor()
         -19 (-9.13% of base) : 11275.dasm - System.Diagnostics.Tracing.EventListener:Dispose():this
         -19 (-1.13% of base) : 3044.dasm - System.UriParser:.cctor()
         -18 (-3.85% of base) : 5617.dasm - System.Uri:.cctor()
         -17 (-1.71% of base) : 25775.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MemberSignatureComparer:.cctor()

Top method regressions (percentages):
           7 ( 2.24% of base) : 7884.dasm - Newtonsoft.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Newtonsoft.Json.JsonSerializer):System.String
          28 ( 0.23% of base) : 25679.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):this

Top method improvements (percentages):
          -7 (-13.21% of base) : 683.dasm - System.Marvin:.cctor()
         -12 (-9.92% of base) : 818.dasm - System.Diagnostics.Stopwatch:.cctor()
         -12 (-9.84% of base) : 29528.dasm - System.MathBenchmarks.MathTests:.cctor()
         -19 (-9.13% of base) : 11275.dasm - System.Diagnostics.Tracing.EventListener:Dispose():this
          -1 (-7.14% of base) : 6234.dasm - System.Net.SSPISecureChannelType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -7 (-5.98% of base) : 6841.dasm - Newtonsoft.Json.JsonConvert:.cctor()
          -1 (-5.88% of base) : 28068.dasm - PerfLabTests.CastingPerf:SetupFooObjIsDescendant():this
          -1 (-5.88% of base) : 23856.dasm - PerfLabTests.CastingPerf:SetupFooObjIsFoo2():this
          -1 (-5.88% of base) : 29482.dasm - PerfLabTests.CastingPerf:SetupIFooObjIsIFooInterAlia():this
          -1 (-5.88% of base) : 30485.dasm - PerfLabTests.CastingPerf:SetupIntObj():this
          -1 (-5.88% of base) : 14622.dasm - PerfLabTests.CastingPerf:SetupObjObjIsFoo():this
          -1 (-5.88% of base) : 8617.dasm - PerfLabTests.CastingPerf:SetupObjrefValueTypeObj():this
          -1 (-5.88% of base) : 31071.dasm - PerfLabTests.CastingPerf:SetupScalarValueTypeObj():this
          -1 (-5.56% of base) : 24576.dasm - CscBench:SetMscorlib():this
          -2 (-5.41% of base) : 2184.dasm - System.Reflection.ConstructorInfo:.cctor()
          -2 (-5.13% of base) : 9923.dasm - System.Security.Cryptography.X509Certificates.Tests.X509ChainTests:.cctor()
          -1 (-4.76% of base) : 25226.dasm - Microsoft.CodeAnalysis.WellKnownAttributeData:.cctor()
          -1 (-4.76% of base) : 32447.dasm - Microsoft.Extensions.Configuration.ConfigurationPath:.cctor()
          -1 (-4.76% of base) : 4215.dasm - Microsoft.Extensions.Options.Options:.cctor()
          -1 (-4.76% of base) : 14527.dasm - NeuralData:.cctor()

6006 total methods with Code Size differences (6004 improved, 2 regressed), 165 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 115733908 (overridden on cmd)
Total bytes of diff: 115702963 (overridden on cmd)
Total bytes of delta: -30945 (-0.03 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
        1329 : 5402.dasm (0.88% of base)
        1329 : 262486.dasm (0.88% of base)
        1203 : 5454.dasm (0.76% of base)
        1203 : 262583.dasm (0.76% of base)
          29 : 5509.dasm (0.04% of base)
          28 : 5503.dasm (0.04% of base)
          20 : 174753.dasm (1.75% of base)
          18 : 30376.dasm (1.09% of base)
          17 : 174146.dasm (1.46% of base)
          13 : 174050.dasm (1.13% of base)
           8 : 174779.dasm (0.35% of base)
           7 : 174424.dasm (1.27% of base)
           6 : 4812.dasm (0.39% of base)
           6 : 4826.dasm (0.40% of base)
           3 : 173953.dasm (0.56% of base)
           2 : 174766.dasm (0.04% of base)

Top file improvements (bytes):
        -868 : 241792.dasm (-0.81% of base)
        -820 : 177712.dasm (-1.33% of base)
        -798 : 175010.dasm (-1.24% of base)
        -304 : 262383.dasm (-0.20% of base)
        -304 : 262476.dasm (-0.20% of base)
        -304 : 262506.dasm (-0.19% of base)
        -304 : 262573.dasm (-0.19% of base)
        -242 : 18634.dasm (-0.53% of base)
        -227 : 18523.dasm (-0.46% of base)
        -227 : 18560.dasm (-0.47% of base)
        -227 : 18597.dasm (-0.43% of base)
        -218 : 18468.dasm (-0.49% of base)
        -110 : 18652.dasm (-0.43% of base)
        -110 : 18662.dasm (-0.43% of base)
        -109 : 18495.dasm (-0.45% of base)
        -109 : 18514.dasm (-0.46% of base)
        -108 : 18541.dasm (-0.39% of base)
        -108 : 18551.dasm (-0.39% of base)
        -108 : 18578.dasm (-0.40% of base)
        -108 : 18588.dasm (-0.40% of base)

22478 total files with Code Size differences (22462 improved, 16 regressed), 1808 unchanged.

Top method regressions (bytes):
        1329 ( 0.88% of base) : 5402.dasm - i8div:Main():int
        1329 ( 0.88% of base) : 262486.dasm - u8div:Main():int
        1203 ( 0.76% of base) : 5454.dasm - i8rem:Main():int
        1203 ( 0.76% of base) : 262583.dasm - u8rem:Main():int
          29 ( 0.04% of base) : 5509.dasm - testout1:Func_0():int
          28 ( 0.04% of base) : 5503.dasm - testout1:Func_0():int
          20 ( 1.75% of base) : 174753.dasm - testout1:Func_0_5_4_5_1():double
          18 ( 1.09% of base) : 30376.dasm - JitTest.Test:testNumbers(long,long)
          17 ( 1.46% of base) : 174146.dasm - testout1:Func_0_2_3_5_2():System.Decimal
          13 ( 1.13% of base) : 174050.dasm - testout1:Func_0_1_6_1_4():ushort
           8 ( 0.35% of base) : 174779.dasm - testout1:Func_0_5_5_4_1():int
           7 ( 1.27% of base) : 174424.dasm - testout1:Func_0_4_2_1_2():long
           6 ( 0.40% of base) : 4826.dasm - testout1:Func_0_1_1_1():long
           6 ( 0.39% of base) : 4812.dasm - testout1:Func_0_1_4_3():double
           3 ( 0.56% of base) : 173953.dasm - testout1:Func_0_1_3_4_1():long
           2 ( 0.04% of base) : 174766.dasm - testout1:Func_0_5_5_6_3():double

Top method improvements (bytes):
        -868 (-0.81% of base) : 241792.dasm - Program:Main(System.String[]):int
        -820 (-1.33% of base) : 177712.dasm - testout1:.cctor()
        -798 (-1.24% of base) : 175010.dasm - testout1:.cctor()
        -304 (-0.20% of base) : 262383.dasm - i8div:Main():int
        -304 (-0.19% of base) : 262506.dasm - i8rem:Main():int
        -304 (-0.20% of base) : 262476.dasm - u8div:Main():int
        -304 (-0.19% of base) : 262573.dasm - u8rem:Main():int
        -242 (-0.53% of base) : 18634.dasm - lclfldsub:Main():int
        -227 (-0.46% of base) : 18523.dasm - lclflddiv:Main():int
        -227 (-0.47% of base) : 18560.dasm - lclfldmul:Main():int
        -227 (-0.43% of base) : 18597.dasm - lclfldrem:Main():int
        -218 (-0.49% of base) : 18468.dasm - lclfldadd:Main():int
        -110 (-0.43% of base) : 18652.dasm - lclfldsub:Main():int
        -110 (-0.43% of base) : 18662.dasm - lclfldsub:Main():int
        -109 (-0.45% of base) : 18495.dasm - lclfldadd:Main():int
        -109 (-0.46% of base) : 18514.dasm - lclfldadd:Main():int
        -108 (-0.39% of base) : 18541.dasm - lclflddiv:Main():int
        -108 (-0.39% of base) : 18551.dasm - lclflddiv:Main():int
        -108 (-0.40% of base) : 18578.dasm - lclfldmul:Main():int
        -108 (-0.40% of base) : 18588.dasm - lclfldmul:Main():int

Top method regressions (percentages):
          20 ( 1.75% of base) : 174753.dasm - testout1:Func_0_5_4_5_1():double
          17 ( 1.46% of base) : 174146.dasm - testout1:Func_0_2_3_5_2():System.Decimal
           7 ( 1.27% of base) : 174424.dasm - testout1:Func_0_4_2_1_2():long
          13 ( 1.13% of base) : 174050.dasm - testout1:Func_0_1_6_1_4():ushort
          18 ( 1.09% of base) : 30376.dasm - JitTest.Test:testNumbers(long,long)
        1329 ( 0.88% of base) : 5402.dasm - i8div:Main():int
        1329 ( 0.88% of base) : 262486.dasm - u8div:Main():int
        1203 ( 0.76% of base) : 5454.dasm - i8rem:Main():int
        1203 ( 0.76% of base) : 262583.dasm - u8rem:Main():int
           3 ( 0.56% of base) : 173953.dasm - testout1:Func_0_1_3_4_1():long
           6 ( 0.40% of base) : 4826.dasm - testout1:Func_0_1_1_1():long
           6 ( 0.39% of base) : 4812.dasm - testout1:Func_0_1_4_3():double
           8 ( 0.35% of base) : 174779.dasm - testout1:Func_0_5_5_4_1():int
           2 ( 0.04% of base) : 174766.dasm - testout1:Func_0_5_5_6_3():double
          29 ( 0.04% of base) : 5509.dasm - testout1:Func_0():int
          28 ( 0.04% of base) : 5503.dasm - testout1:Func_0():int

Top method improvements (percentages):
         -12 (-29.27% of base) : 75943.dasm - ILGEN_622380794:main():int
          -7 (-17.95% of base) : 32386.dasm - Test.LongValues:.cctor()
          -7 (-17.07% of base) : 38372.dasm - ShiftTest.longTest:.cctor()
          -7 (-16.28% of base) : 58567.dasm - ldsshrstsfld:f1()
          -7 (-14.58% of base) : 5204.dasm - JIT.HardwareIntrinsics.X86.ScalarBinaryOpTest__BitFieldExtractUInt64:.cctor()
          -7 (-13.73% of base) : 222690.dasm - JIT.HardwareIntrinsics.Arm.ScalarBinaryOpTest__ComputeCrc32_UInt64:.cctor()
          -7 (-13.73% of base) : 222692.dasm - JIT.HardwareIntrinsics.Arm.ScalarBinaryOpTest__ComputeCrc32C_UInt64:.cctor()
          -7 (-13.21% of base) : 5192.dasm - JIT.HardwareIntrinsics.X86.ScalarTernOpTest__BitFieldExtractUInt64:.cctor()
         -34 (-12.98% of base) : 27558.dasm - IntrinsicTest:.cctor()
          -7 (-12.73% of base) : 58992.dasm - JitTest.TestStruct:.cctor()
          -7 (-12.28% of base) : 57855.dasm - Runtime_61077:.cctor()
          -7 (-12.28% of base) : 38367.dasm - ShiftTest.longTest:.cctor()
          -7 (-12.28% of base) : 38410.dasm - ShiftTest.ulong32Test:.cctor()
          -7 (-12.28% of base) : 57011.dasm - Test.BB:.cctor()
          -7 (-12.28% of base) : 46029.dasm - TestSetValue:.cctor()
         -12 (-11.76% of base) : 38166.dasm - IntrinsicTest:.cctor()
         -12 (-11.76% of base) : 11181.dasm - JIT.HardwareIntrinsics.X86.ScalarBinaryOpTest__MultiplyNoFlagsUInt64:.cctor()
         -12 (-11.76% of base) : 11179.dasm - JIT.HardwareIntrinsics.X86.ScalarBinaryOpTest__ZeroHighBitsUInt64:.cctor()
         -17 (-11.72% of base) : 38168.dasm - IntrinsicTest:.cctor()
         -17 (-11.72% of base) : 11183.dasm - JIT.HardwareIntrinsics.X86.ScalarTernOpBinResTest__MultiplyNoFlagsUInt64:.cctor()

22478 total methods with Code Size differences (22462 improved, 16 regressed), 1808 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 39502366 (overridden on cmd)
Total bytes of diff: 39490121 (overridden on cmd)
Total bytes of delta: -12245 (-0.03 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          23 : 182584.dasm (1.21% of base)
           8 : 78844.dasm (3.76% of base)
           7 : 103531.dasm (2.24% of base)
           4 : 119947.dasm (0.58% of base)
           4 : 159639.dasm (0.75% of base)
           4 : 197690.dasm (0.62% of base)
           4 : 150111.dasm (0.85% of base)
           4 : 18397.dasm (1.13% of base)
           4 : 42451.dasm (1.75% of base)
           4 : 18361.dasm (0.34% of base)
           2 : 204848.dasm (0.46% of base)
           1 : 225220.dasm (0.03% of base)
           1 : 104237.dasm (0.06% of base)

Top file improvements (bytes):
        -235 : 148054.dasm (-1.09% of base)
        -167 : 63035.dasm (-1.82% of base)
        -146 : 78307.dasm (-0.82% of base)
        -141 : 120735.dasm (-2.30% of base)
        -141 : 121298.dasm (-2.30% of base)
        -120 : 63784.dasm (-0.99% of base)
         -95 : 129959.dasm (-0.67% of base)
         -79 : 142578.dasm (-0.84% of base)
         -62 : 133030.dasm (-2.21% of base)
         -61 : 144521.dasm (-0.29% of base)
         -58 : 144960.dasm (-2.55% of base)
         -55 : 196026.dasm (-1.45% of base)
         -51 : 216916.dasm (-2.71% of base)
         -44 : 233425.dasm (-0.62% of base)
         -43 : 119772.dasm (-6.20% of base)
         -43 : 229330.dasm (-2.86% of base)
         -42 : 74876.dasm (-2.66% of base)
         -41 : 201214.dasm (-1.01% of base)
         -39 : 242151.dasm (-1.20% of base)
         -37 : 147562.dasm (-1.45% of base)

7018 total files with Code Size differences (7005 improved, 13 regressed), 341 unchanged.

Top method regressions (bytes):
          23 ( 1.21% of base) : 182584.dasm - R2RDump.TextDumper:DumpAllMethods():this
           8 ( 3.76% of base) : 78844.dasm - Microsoft.CodeAnalysis.SyntaxNode:GetText(System.Text.Encoding,int):Microsoft.CodeAnalysis.Text.SourceText:this
           7 ( 2.24% of base) : 103531.dasm - Newtonsoft.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Newtonsoft.Json.JsonSerializer):System.String
           4 ( 0.34% of base) : 18361.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveParser:ParseErrorOrWarningDirective(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,bool):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveTriviaSyntax:this
           4 ( 1.13% of base) : 18397.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveStack:GetDebuggerDisplay():System.String:this
           4 ( 1.75% of base) : 42451.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:ToString():System.String:this
           4 ( 0.62% of base) : 197690.dasm - System.Configuration.ConfigurationSection:SerializeSection(System.Configuration.ConfigurationElement,System.String,int):System.String:this
           4 ( 0.58% of base) : 119947.dasm - System.Data.Common.ObjectStorage:ConvertObjectToXml(System.Object):System.String:this
           4 ( 0.75% of base) : 159639.dasm - System.Speech.Synthesis.PromptBuilder:AppendSsmlInternal(System.Xml.XmlReader):this
           4 ( 0.85% of base) : 150111.dasm - System.Xml.Serialization.XmlSchemas:Dump(System.Xml.Schema.XmlSchemaObject):System.String
           2 ( 0.46% of base) : 204848.dasm - System.Diagnostics.XmlWriterTraceListener:WriteData(System.Object):this
           1 ( 0.03% of base) : 225220.dasm - <ConnectAsync>d__13:MoveNext():this
           1 ( 0.06% of base) : 104237.dasm - Newtonsoft.Json.JsonValidatingReader:WriteToken(System.Collections.Generic.IList`1[[Newtonsoft.Json.Schema.JsonSchemaModel, Newtonsoft.Json, Version=12.0.0.0, Culture=neutral, PublicKeyToken=30ad4fe6b2a6aeed]]):this

Top method improvements (bytes):
        -235 (-1.09% of base) : 148054.dasm - System.Xml.Xsl.IlGen.XmlILMethods:.cctor()
        -167 (-1.82% of base) : 63035.dasm - <StartupCode$FSharp-Core>.$Query:.cctor()
        -146 (-0.82% of base) : 78307.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
        -141 (-2.30% of base) : 120735.dasm - System.Drawing.Brushes:.cctor()
        -141 (-2.30% of base) : 121298.dasm - System.Drawing.Pens:.cctor()
        -120 (-0.99% of base) : 63784.dasm - <StartupCode$FSharp-Core>.$Linq:.cctor()
         -95 (-0.67% of base) : 129959.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
         -79 (-0.84% of base) : 142578.dasm - System.Xml.Schema.DatatypeImplementation:.cctor()
         -62 (-2.21% of base) : 133030.dasm - System.Runtime.Serialization.DictionaryGlobals:.cctor()
         -61 (-0.29% of base) : 144521.dasm - System.Xml.Schema.XsdBuilder:.cctor()
         -58 (-2.55% of base) : 144960.dasm - System.Xml.Xsl.XmlQueryTypeFactory:.cctor()
         -55 (-1.45% of base) : 196026.dasm - System.ComponentModel.Design.StandardCommands:.cctor()
         -51 (-2.71% of base) : 216916.dasm - System.Management.WmiNetUtilsHelper:LoadPlatformNotSupportedDelegates(System.String)
         -44 (-0.62% of base) : 233425.dasm - System.Text.RegularExpressions.RegexCompiler:.cctor()
         -43 (-6.20% of base) : 119772.dasm - System.Data.Common.DbMetaDataColumnNames:.cctor()
         -43 (-2.86% of base) : 229330.dasm - System.Runtime.Serialization.Formatters.Binary.Converter:.cctor()
         -42 (-2.66% of base) : 74876.dasm - <StartupCode$FSharp-Core>.$Prim-types:.cctor()
         -41 (-1.01% of base) : 201214.dasm - System.Data.OleDb.NativeDBType:.cctor()
         -39 (-1.20% of base) : 242151.dasm - Xunit.TestMessageVisitor:OnMessage(Xunit.Abstractions.IMessageSinkMessage):bool:this
         -37 (-1.45% of base) : 147562.dasm - System.Xml.Xsl.Runtime.XsltMethods:.cctor()

Top method regressions (percentages):
           8 ( 3.76% of base) : 78844.dasm - Microsoft.CodeAnalysis.SyntaxNode:GetText(System.Text.Encoding,int):Microsoft.CodeAnalysis.Text.SourceText:this
           7 ( 2.24% of base) : 103531.dasm - Newtonsoft.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Newtonsoft.Json.JsonSerializer):System.String
           4 ( 1.75% of base) : 42451.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:ToString():System.String:this
          23 ( 1.21% of base) : 182584.dasm - R2RDump.TextDumper:DumpAllMethods():this
           4 ( 1.13% of base) : 18397.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveStack:GetDebuggerDisplay():System.String:this
           4 ( 0.85% of base) : 150111.dasm - System.Xml.Serialization.XmlSchemas:Dump(System.Xml.Schema.XmlSchemaObject):System.String
           4 ( 0.75% of base) : 159639.dasm - System.Speech.Synthesis.PromptBuilder:AppendSsmlInternal(System.Xml.XmlReader):this
           4 ( 0.62% of base) : 197690.dasm - System.Configuration.ConfigurationSection:SerializeSection(System.Configuration.ConfigurationElement,System.String,int):System.String:this
           4 ( 0.58% of base) : 119947.dasm - System.Data.Common.ObjectStorage:ConvertObjectToXml(System.Object):System.String:this
           2 ( 0.46% of base) : 204848.dasm - System.Diagnostics.XmlWriterTraceListener:WriteData(System.Object):this
           4 ( 0.34% of base) : 18361.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveParser:ParseErrorOrWarningDirective(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,bool):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DirectiveTriviaSyntax:this
           1 ( 0.06% of base) : 104237.dasm - Newtonsoft.Json.JsonValidatingReader:WriteToken(System.Collections.Generic.IList`1[[Newtonsoft.Json.Schema.JsonSchemaModel, Newtonsoft.Json, Version=12.0.0.0, Culture=neutral, PublicKeyToken=30ad4fe6b2a6aeed]]):this
           1 ( 0.03% of base) : 225220.dasm - <ConnectAsync>d__13:MoveNext():this

Top method improvements (percentages):
         -12 (-11.76% of base) : 228329.dasm - System.Runtime.Caching.CacheMemoryMonitor:.cctor()
         -12 (-10.53% of base) : 183931.dasm - Microsoft.Build.Framework.Profiler.EvaluationIdProvider:.cctor()
          -1 (-8.33% of base) : 165766.dasm - ILLink.Shared.SharedStrings:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 239096.dasm - Internal.CommandLine.Strings:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 108227.dasm - Microsoft.Build.Evaluation.Context.EvaluationContext:set_TestOnlyHookOnCreate(System.Action`1[[Microsoft.Build.Evaluation.Context.EvaluationContext, Microsoft.Build, Version=15.1.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]])
          -1 (-8.33% of base) : 183763.dasm - Microsoft.Build.Shared.Debugging.CommonWriter:set_Writer(System.Action`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
          -1 (-8.33% of base) : 76419.dasm - Microsoft.CodeAnalysis.CodeAnalysisResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 11410.dasm - Microsoft.CodeAnalysis.CSharp.CSharpResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 77690.dasm - Microsoft.CodeAnalysis.FatalError:OverwriteHandler(System.Action`1[[System.Exception, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
          -1 (-8.33% of base) : 55396.dasm - Microsoft.CodeAnalysis.VisualBasic.VBResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 182922.dasm - System.CommandLine.Properties.Resources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 238762.dasm - System.SR:set_Culture(System.Globalization.CultureInfo)
          -7 (-7.69% of base) : 129305.dasm - RttEstimator:.cctor()
          -1 (-7.14% of base) : 218506.dasm - System.Net.SSPIAuthType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 223133.dasm - System.Net.SSPIAuthType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 128083.dasm - System.Net.SSPIAuthType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 219845.dasm - System.Net.SSPIAuthType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 218495.dasm - System.Net.SSPISecureChannelType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 223154.dasm - System.Net.SSPISecureChannelType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this
          -1 (-7.14% of base) : 128074.dasm - System.Net.SSPISecureChannelType:set_SecurityPackages(System.Net.SecurityPackageInfoClass[]):this

7018 total methods with Code Size differences (7005 improved, 13 regressed), 341 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 96295370 (overridden on cmd)
Total bytes of diff: 96221533 (overridden on cmd)
Total bytes of delta: -73837 (-0.08 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          22 : 168137.dasm (0.98% of base)
          17 : 38084.dasm (6.83% of base)
          17 : 38085.dasm (6.49% of base)
          15 : 293055.dasm (2.34% of base)
          15 : 38086.dasm (5.70% of base)
          15 : 38087.dasm (5.73% of base)
          12 : 263727.dasm (1.60% of base)
          12 : 263730.dasm (1.60% of base)
          11 : 38026.dasm (3.91% of base)
          11 : 38027.dasm (3.87% of base)
          11 : 38028.dasm (3.90% of base)
           7 : 150436.dasm (2.24% of base)
           7 : 305203.dasm (1.98% of base)
           6 : 293057.dasm (0.11% of base)
           3 : 263711.dasm (0.30% of base)
           3 : 263712.dasm (0.64% of base)
           3 : 62099.dasm (0.17% of base)
           2 : 304994.dasm (0.14% of base)
           1 : 151092.dasm (0.06% of base)
           1 : 207654.dasm (0.12% of base)

Top file improvements (bytes):
        -262 : 52933.dasm (-0.58% of base)
        -262 : 52948.dasm (-0.59% of base)
        -174 : 26585.dasm (-0.42% of base)
        -174 : 28428.dasm (-0.42% of base)
        -174 : 26384.dasm (-0.42% of base)
        -174 : 26903.dasm (-0.42% of base)
        -174 : 27283.dasm (-0.42% of base)
        -174 : 27291.dasm (-0.42% of base)
        -174 : 28335.dasm (-0.42% of base)
        -174 : 26853.dasm (-0.42% of base)
        -174 : 25717.dasm (-0.42% of base)
        -174 : 24552.dasm (-0.42% of base)
        -174 : 25304.dasm (-0.42% of base)
        -174 : 26103.dasm (-0.42% of base)
        -141 : 115786.dasm (-0.73% of base)
        -141 : 116771.dasm (-0.73% of base)
        -138 : 54039.dasm (-0.62% of base)
        -132 : 323614.dasm (-1.64% of base)
        -109 : 131524.dasm (-1.45% of base)
        -105 : 59786.dasm (-0.58% of base)

32116 total files with Code Size differences (32093 improved, 23 regressed), 916 unchanged.

Top method regressions (bytes):
          22 ( 0.98% of base) : 168137.dasm - System.Data.Tests.DataSetTest2:WriteXml_Stream():this
          17 ( 6.83% of base) : 38084.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,System.__Canon):System.String
          17 ( 6.49% of base) : 38085.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,ubyte):System.String
          15 ( 2.34% of base) : 293055.dasm - <>c:<Initialize>b__4_1(System.Object,System.Threading.CancellationToken):System.Object:this
          15 ( 5.73% of base) : 38087.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,int):System.String
          15 ( 5.70% of base) : 38086.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,short):System.String
          12 ( 1.60% of base) : 263727.dasm - System.CodeDom.Tests.IndentedTextWriterTests:Write_IsIndented_AfterWriteLine(System.Action`1[[System.CodeDom.Compiler.IndentedTextWriter, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):this
          12 ( 1.60% of base) : 263730.dasm - System.CodeDom.Tests.IndentedTextWriterTests:WriteLine_IsIndented_AfterWriteLine(System.Action`1[[System.CodeDom.Compiler.IndentedTextWriter, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):this
          11 ( 3.91% of base) : 38026.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,double):System.String
          11 ( 3.90% of base) : 38028.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,long):System.String
          11 ( 3.87% of base) : 38027.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,System.Numerics.Vector`1[Single]):System.String
           7 ( 2.24% of base) : 150436.dasm - Microsoft.IdentityModel.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Microsoft.IdentityModel.Json.JsonSerializer):System.String
           7 ( 1.98% of base) : 305203.dasm - System.Xml.Tests.SameInstanceXslTransformReader:Transform(System.Object):int:this
           6 ( 0.11% of base) : 293057.dasm - <>c:<Initialize>b__4_3(Microsoft.CodeAnalysis.SourceProductionContext,System.ValueTuple`2[[System.Collections.Immutable.ImmutableArray`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[System.ValueTuple`2[[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):this
           3 ( 0.17% of base) : 62099.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.operate.genclass.genclass007.genclass007.Test:MainMethod():int
           3 ( 0.30% of base) : 263711.dasm - System.CodeDom.Tests.IndentedTextWriterTests:Indent_RoundtripsAndAffectsOutput(int)
           3 ( 0.64% of base) : 263712.dasm - System.CodeDom.Tests.IndentedTextWriterTests:TabString_UsesProvidedString(System.String)
           2 ( 0.14% of base) : 304994.dasm - System.Xml.Tests.Errata4:TestXslTransform(System.Object,System.Object):this
           1 ( 0.06% of base) : 293646.dasm - <TestPrecanceledToken>d__12:MoveNext():this
           1 ( 0.07% of base) : 60664.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.basic.lambda008.lambda008.Test:MainMethod():int

Top method improvements (bytes):
        -262 (-0.59% of base) : 52948.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.freach.freach001.freach001.Test:MainMethod():int
        -262 (-0.58% of base) : 52933.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.freach.freach007.freach007.Test:MainMethod():int
        -174 (-0.42% of base) : 25304.dasm - CollectionTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 24552.dasm - CollectionTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 26103.dasm - ConstructorTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 25717.dasm - ConstructorTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 26585.dasm - ExtensionDataTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 26384.dasm - ExtensionDataTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 28428.dasm - PropertyNameTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 28335.dasm - PropertyNameTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 27283.dasm - ReferenceHandlerTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 27291.dasm - ReferenceHandlerTestsContext_Default:SimpleTestClassWithFieldsPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 26903.dasm - ReferenceHandlerTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -174 (-0.42% of base) : 26853.dasm - ReferenceHandlerTestsContext_Metadata:SimpleTestClassWithFieldsPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
        -141 (-0.73% of base) : 115786.dasm - <Brushes_TestData>d__0:MoveNext():bool:this
        -141 (-0.73% of base) : 116771.dasm - <Pens_TestData>d__0:MoveNext():bool:this
        -138 (-0.62% of base) : 54039.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Methods.Oneclass2methods.literals01.literals01.A:MainMethod():int
        -132 (-1.64% of base) : 323614.dasm - NativeMethods:Setup(SQLitePCL.IGetFunctionPointer)
        -109 (-1.45% of base) : 131524.dasm - XmlCoreTest.Common.FilePathUtil:.cctor()
        -105 (-0.58% of base) : 59786.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001.cnst001.Test:MainMethod():int

Top method regressions (percentages):
          17 ( 6.83% of base) : 38084.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,System.__Canon):System.String
          17 ( 6.49% of base) : 38085.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,ubyte):System.String
          15 ( 5.73% of base) : 38087.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,int):System.String
          15 ( 5.70% of base) : 38086.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetPropertyExpectedString(bool,short):System.String
          11 ( 3.91% of base) : 38026.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,double):System.String
          11 ( 3.90% of base) : 38028.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,long):System.String
          11 ( 3.87% of base) : 38027.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:GetNumbersExpectedString(bool,int,System.Numerics.Vector`1[Single]):System.String
          15 ( 2.34% of base) : 293055.dasm - <>c:<Initialize>b__4_1(System.Object,System.Threading.CancellationToken):System.Object:this
           7 ( 2.24% of base) : 150436.dasm - Microsoft.IdentityModel.Json.JsonConvert:SerializeObjectInternal(System.Object,System.Type,Microsoft.IdentityModel.Json.JsonSerializer):System.String
           7 ( 1.98% of base) : 305203.dasm - System.Xml.Tests.SameInstanceXslTransformReader:Transform(System.Object):int:this
          12 ( 1.60% of base) : 263727.dasm - System.CodeDom.Tests.IndentedTextWriterTests:Write_IsIndented_AfterWriteLine(System.Action`1[[System.CodeDom.Compiler.IndentedTextWriter, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):this
          12 ( 1.60% of base) : 263730.dasm - System.CodeDom.Tests.IndentedTextWriterTests:WriteLine_IsIndented_AfterWriteLine(System.Action`1[[System.CodeDom.Compiler.IndentedTextWriter, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):this
          22 ( 0.98% of base) : 168137.dasm - System.Data.Tests.DataSetTest2:WriteXml_Stream():this
           3 ( 0.64% of base) : 263712.dasm - System.CodeDom.Tests.IndentedTextWriterTests:TabString_UsesProvidedString(System.String)
           3 ( 0.30% of base) : 263711.dasm - System.CodeDom.Tests.IndentedTextWriterTests:Indent_RoundtripsAndAffectsOutput(int)
           3 ( 0.17% of base) : 62099.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.operate.genclass.genclass007.genclass007.Test:MainMethod():int
           2 ( 0.14% of base) : 304994.dasm - System.Xml.Tests.Errata4:TestXslTransform(System.Object,System.Object):this
           1 ( 0.12% of base) : 207654.dasm - System.Data.SqlClient.SqlStreamingXml:GetChars(long,System.Char[],int,int):long:this
           1 ( 0.12% of base) : 211937.dasm - System.Data.SqlClient.SqlStreamingXml:GetChars(long,System.Char[],int,int):long:this
           6 ( 0.11% of base) : 293057.dasm - <>c:<Initialize>b__4_3(Microsoft.CodeAnalysis.SourceProductionContext,System.ValueTuple`2[[System.Collections.Immutable.ImmutableArray`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[System.ValueTuple`2[[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):this

Top method improvements (percentages):
          -7 (-11.11% of base) : 280467.dasm - System.Reflection.Tests.TI_GenericTypeWithAllMembers`1[Int64][System.Int64]:get_PrivateStaticProperty():long
          -7 (-11.11% of base) : 280471.dasm - System.Reflection.Tests.TI_GenericTypeWithAllMembers`1[Int64][System.Int64]:get_PublicStaticProperty():long
         -12 (-10.53% of base) : 311366.dasm - Microsoft.Build.Framework.Profiler.EvaluationIdProvider:.cctor()
          -7 (-10.45% of base) : 18614.dasm - <Module>:.cctor()
          -7 (-9.72% of base) : 280468.dasm - System.Reflection.Tests.TI_GenericTypeWithAllMembers`1[Int64][System.Int64]:set_PrivateStaticProperty(long)
          -7 (-9.72% of base) : 280472.dasm - System.Reflection.Tests.TI_GenericTypeWithAllMembers`1[Int64][System.Int64]:set_PublicStaticProperty(long)
          -1 (-8.33% of base) : 214677.dasm - Autofac.Builder.RegistrationBuilderResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 213225.dasm - Autofac.ContainerBuilderResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214544.dasm - Autofac.Core.Activators.InstanceActivatorResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214565.dasm - Autofac.Core.Activators.Reflection.BoundConstructorResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214587.dasm - Autofac.Core.Activators.Reflection.MatchingSignatureConstructorSelectorResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214593.dasm - Autofac.Core.Activators.Reflection.MostParametersConstructorSelectorResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214602.dasm - Autofac.Core.Activators.Reflection.NoConstructorsFoundExceptionResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214613.dasm - Autofac.Core.Activators.Reflection.ReflectionActivatorResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214139.dasm - Autofac.Core.ContainerResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214151.dasm - Autofac.Core.DisposerResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214524.dasm - Autofac.Core.Lifetime.LifetimeScopeResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214532.dasm - Autofac.Core.Lifetime.MatchingScopeLifetimeResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214347.dasm - Autofac.Core.Registration.ComponentNotRegisteredExceptionResources:set_Culture(System.Globalization.CultureInfo)
          -1 (-8.33% of base) : 214384.dasm - Autofac.Core.Registration.ComponentRegistrationResources:set_Culture(System.Globalization.CultureInfo)

32116 total methods with Code Size differences (32093 improved, 23 regressed), 916 unchanged.

```

</details>

--------------------------------------------------------------------------------

