## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 962572
Total bytes of diff: 957492
Total bytes of delta: -5080 (-0.53% of base)
Total relative delta: -7.88
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 17647.dasm (0.46% of base)

Top file improvements (bytes):
        -324 : 15279.dasm (-3.34% of base)
        -156 : 12592.dasm (-1.55% of base)
        -136 : 15337.dasm (-3.19% of base)
        -116 : 16182.dasm (-2.97% of base)
        -104 : 17802.dasm (-2.40% of base)
         -96 : 8017.dasm (-6.25% of base)
         -88 : 7119.dasm (-7.28% of base)
         -84 : 8603.dasm (-1.53% of base)
         -48 : 13525.dasm (-1.04% of base)
         -44 : 2285.dasm (-1.43% of base)
         -44 : 3647.dasm (-1.66% of base)
         -44 : 8653.dasm (-2.07% of base)
         -44 : 6369.dasm (-0.37% of base)
         -40 : 10209.dasm (-2.97% of base)
         -40 : 7148.dasm (-2.77% of base)
         -40 : 1181.dasm (-1.06% of base)
         -36 : 13613.dasm (-13.24% of base)
         -36 : 8660.dasm (-2.17% of base)
         -36 : 10500.dasm (-13.24% of base)
         -32 : 18273.dasm (-1.58% of base)

567 total files with Code Size differences (566 improved, 1 regressed), 318 unchanged.

Top method regressions (bytes):
           4 ( 0.46% of base) : 17647.dasm - Microsoft.Cci.MetadataWriter:PopulateFileTableRows():this

Top method improvements (bytes):
        -324 (-3.34% of base) : 15279.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -156 (-1.55% of base) : 12592.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
        -136 (-3.19% of base) : 15337.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
        -116 (-2.97% of base) : 16182.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
        -104 (-2.40% of base) : 17802.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
         -96 (-6.25% of base) : 8017.dasm - Sigil.Impl.ExtensionMethods:IsAssignableFrom(Sigil.Impl.TypeOnStack,Sigil.Impl.TypeOnStack):bool
         -88 (-7.28% of base) : 7119.dasm - System.Text.Json.Serialization.JsonConverter`1[__Canon][System.__Canon]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):System.__Canon:this
         -84 (-1.53% of base) : 8603.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WritePrimitive(System.Xml.Serialization.TypeMapping,System.String):this
         -48 (-1.04% of base) : 13525.dasm - System.Globalization.DateTimeFormatInfo:CreateTokenHashTable():System.Globalization.DateTimeFormatInfo+TokenHashValue[]:this
         -44 (-1.43% of base) : 2285.dasm - System.Runtime.Serialization.Json.XmlJsonWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -44 (-1.66% of base) : 3647.dasm - System.Xml.XmlBaseWriter:StartAttribute(byref,System.String,System.String,System.Xml.XmlDictionaryString):this
         -44 (-2.07% of base) : 8653.dasm - System.Xml.XmlWellFormedWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -44 (-0.37% of base) : 6369.dasm - System.Reflection.Metadata.MetadataReader:InitializeTableReaders(System.Reflection.Internal.MemoryBlock,ubyte,System.Int32[],System.Int32[]):this
         -40 (-2.97% of base) : 10209.dasm - System.Drawing.Imaging.ImageFormat:ToString():System.String:this
         -40 (-2.77% of base) : 7148.dasm - System.Text.Json.Reflection.ReflectionExtensions:IsImmutableEnumerableType(System.Type,bool):bool
         -40 (-1.06% of base) : 1181.dasm - System.Text.RegularExpressions.RegexNode:CanBeMadeAtomic(System.Text.RegularExpressions.RegexNode,System.Text.RegularExpressions.RegexNode,int):bool
         -36 (-13.24% of base) : 13613.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[LargeStructWithProperties][MicroBenchmarks.Serializers.LargeStructWithProperties]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -36 (-2.17% of base) : 8660.dasm - System.Xml.XmlWellFormedWriter:PushNamespaceExplicit(System.String,System.String):bool:this
         -36 (-13.24% of base) : 10500.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[__Canon][System.__Canon]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -32 (-1.58% of base) : 18273.dasm - System.Text.Json.Document.Tests.Perf_DocumentParse:ReadJson400B(System.Text.Json.JsonElement)

Top method regressions (percentages):
           4 ( 0.46% of base) : 17647.dasm - Microsoft.Cci.MetadataWriter:PopulateFileTableRows():this

Top method improvements (percentages):
         -36 (-13.24% of base) : 13613.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[LargeStructWithProperties][MicroBenchmarks.Serializers.LargeStructWithProperties]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -36 (-13.24% of base) : 10500.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[__Canon][System.__Canon]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
          -4 (-11.11% of base) : 20903.dasm - System.Security.Cryptography.HMACSHA256:TryHashFinal(System.Span`1[Byte],byref):bool:this
          -4 (-9.09% of base) : 17687.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol:Microsoft.Cci.ISignature.get_ReturnValueIsByRef():bool:this
         -12 (-8.57% of base) : 10098.dasm - System.Diagnostics.ActivityContext:Equals(System.Diagnostics.ActivityContext):bool:this
          -4 (-8.33% of base) : 669.dasm - <>c:<GetThisTypeCharacteristicsCore>b__8_4(BenchmarkDotNet.Characteristics.Characteristic):int:this
          -4 (-8.33% of base) : 6618.dasm - System.Tests.Perf_Guid:EqualsOperator():bool:this
          -4 (-8.33% of base) : 642.dasm - System.RuntimeType:IsPrimitiveImpl():bool:this
         -88 (-7.28% of base) : 7119.dasm - System.Text.Json.Serialization.JsonConverter`1[__Canon][System.__Canon]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):System.__Canon:this
          -4 (-7.14% of base) : 9386.dasm - Newtonsoft.Json.Converters.EntityKeyMemberConverter:CanConvert(System.Type):bool:this
          -4 (-6.67% of base) : 1976.dasm - MessagePack.Decoders.FixInt16:Read(System.Byte[],int,byref):short:this
         -96 (-6.25% of base) : 8017.dasm - Sigil.Impl.ExtensionMethods:IsAssignableFrom(Sigil.Impl.TypeOnStack,Sigil.Impl.TypeOnStack):bool
         -12 (-6.12% of base) : 15915.dasm - Microsoft.CodeAnalysis.MetadataHelpers:GetAssemblyOrModuleNameErrorArgumentResourceName(System.String):System.String
          -8 (-5.26% of base) : 8004.dasm - Sigil.Impl.TypeOnStack:GetHashCode():int:this
          -8 (-5.26% of base) : 11847.dasm - CredentialEnumerator:MoveNext():bool:this
          -4 (-5.26% of base) : 12851.dasm - System.Tests.Perf_UInt32:TryFormat(int):bool:this
         -12 (-5.26% of base) : 4742.dasm - System.Formats.Cbor.Tests.ECDsaCosePublicKeyHelper:<WriteECParametersAsCosePublicKey>g__MapHashAlgorithmNameToCoseKeyAlg|0_1(System.Security.Cryptography.HashAlgorithmName):int
          -4 (-5.26% of base) : 6647.dasm - System.Tests.Perf_UInt64:TryFormat(long):bool:this
          -4 (-5.00% of base) : 17343.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ContainsExtensionMethods():bool:this
          -4 (-4.76% of base) : 4051.dasm - System.Threading.PortableThreadPool:get_MinThreadsGoal():short:this

567 total methods with Code Size differences (566 improved, 1 regressed), 318 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1950920
Total bytes of diff: 1924756
Total bytes of delta: -26164 (-1.34% of base)
Total relative delta: -59.87
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 231083.dasm (0.48% of base)
           4 : 170640.dasm (0.88% of base)

Top file improvements (bytes):
        -420 : 164980.dasm (-2.17% of base)
        -308 : 206913.dasm (-4.95% of base)
        -308 : 206916.dasm (-5.06% of base)
        -308 : 206925.dasm (-5.23% of base)
        -308 : 206929.dasm (-5.06% of base)
        -308 : 206976.dasm (-5.23% of base)
        -308 : 214692.dasm (-4.95% of base)
        -272 : 184017.dasm (-4.67% of base)
        -216 : 176627.dasm (-0.48% of base)
        -200 : 224457.dasm (-5.03% of base)
        -200 : 224478.dasm (-4.37% of base)
        -200 : 224525.dasm (-5.03% of base)
        -200 : 224561.dasm (-5.17% of base)
        -200 : 217563.dasm (-12.56% of base)
        -200 : 217566.dasm (-14.97% of base)
        -200 : 217568.dasm (-11.06% of base)
        -200 : 217569.dasm (-14.71% of base)
        -200 : 217573.dasm (-12.56% of base)
        -200 : 217578.dasm (-14.97% of base)
        -200 : 217583.dasm (-11.06% of base)

2339 total files with Code Size differences (2337 improved, 2 regressed), 370 unchanged.

Top method regressions (bytes):
          16 ( 0.48% of base) : 231083.dasm - ILGEN_0x977f9ed2:Method_0xf6b7353b():float
           4 ( 0.88% of base) : 170640.dasm - testout1:Func_0_2_2_1():long

Top method improvements (bytes):
        -420 (-2.17% of base) : 164980.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
        -308 (-4.95% of base) : 206913.dasm - Test:Main():int
        -308 (-5.06% of base) : 206916.dasm - Test:Main():int
        -308 (-5.23% of base) : 206925.dasm - Test:Main():int
        -308 (-5.06% of base) : 206929.dasm - Test:Main():int
        -308 (-5.23% of base) : 206976.dasm - Test:Main():int
        -308 (-4.95% of base) : 214692.dasm - Test:Main():int
        -272 (-4.67% of base) : 184017.dasm - TailcallVerify.Program:Run(System.String):int
        -216 (-0.48% of base) : 176627.dasm - testout1:Func_0():int
        -200 (-5.03% of base) : 224457.dasm - Test:Main():int
        -200 (-4.37% of base) : 224478.dasm - Test:Main():int
        -200 (-5.03% of base) : 224525.dasm - Test:Main():int
        -200 (-5.17% of base) : 224561.dasm - Test:Main():int
        -200 (-12.56% of base) : 217563.dasm - Test:Main():int
        -200 (-14.97% of base) : 217566.dasm - Test:Main():int
        -200 (-11.06% of base) : 217568.dasm - Test:Main():int
        -200 (-14.71% of base) : 217569.dasm - Test:Main():int
        -200 (-12.56% of base) : 217573.dasm - Test:Main():int
        -200 (-14.97% of base) : 217578.dasm - Test:Main():int
        -200 (-11.06% of base) : 217583.dasm - Test:Main():int

Top method regressions (percentages):
           4 ( 0.88% of base) : 170640.dasm - testout1:Func_0_2_2_1():long
          16 ( 0.48% of base) : 231083.dasm - ILGEN_0x977f9ed2:Method_0xf6b7353b():float

Top method improvements (percentages):
         -16 (-30.77% of base) : 86009.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
         -24 (-20.69% of base) : 85489.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
          -8 (-18.18% of base) : 86030.dasm - DevDiv_524309.ILGEN_CLASS:ILGEN_METHOD(long,short):bool
        -200 (-14.97% of base) : 217566.dasm - Test:Main():int
        -200 (-14.97% of base) : 217578.dasm - Test:Main():int
        -200 (-14.71% of base) : 217569.dasm - Test:Main():int
        -200 (-14.71% of base) : 217585.dasm - Test:Main():int
          -4 (-14.29% of base) : 151178.dasm - testout1:Func_0_1_4_1_4():ushort
          -4 (-14.29% of base) : 87426.dasm - Program:Test_ldind_u1_conv_i2(byref,byref)
          -4 (-14.29% of base) : 87428.dasm - Program:Test_ldind_u1_conv_ovf_i2(byref,byref)
          -4 (-14.29% of base) : 87431.dasm - Program:Test_ldind_u1_conv_ovf_i2_un(byref,byref)
          -4 (-14.29% of base) : 87434.dasm - Program:Test_ldind_u1_conv_u2(byref,byref)
          -4 (-14.29% of base) : 148529.dasm - testout1:Func_0_1_4_1_4():ushort
          -4 (-14.29% of base) : 87436.dasm - Program:Test_ldind_u1_conv_ovf_u2(byref,byref)
          -4 (-14.29% of base) : 87439.dasm - Program:Test_ldind_u1_conv_ovf_u2_un(byref,byref)
          -4 (-14.29% of base) : 87490.dasm - Program:Test_ldind_i1_conv_i2(byref,byref)
          -4 (-14.29% of base) : 87492.dasm - Program:Test_ldind_i1_conv_ovf_i2(byref,byref)
        -200 (-12.56% of base) : 217563.dasm - Test:Main():int
        -200 (-12.56% of base) : 217573.dasm - Test:Main():int
        -200 (-12.50% of base) : 217920.dasm - Test:Main():int

2339 total methods with Code Size differences (2337 improved, 2 regressed), 370 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 22973008
Total bytes of diff: 22631980
Total bytes of delta: -341028 (-1.48% of base)
Total relative delta: -1029.75
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          48 : 198893.dasm (17.14% of base)
          44 : 176280.dasm (7.64% of base)
          40 : 161594.dasm (11.49% of base)
          32 : 178452.dasm (3.51% of base)
          32 : 178458.dasm (3.51% of base)
          32 : 178464.dasm (3.51% of base)
          32 : 112077.dasm (6.06% of base)
          32 : 112078.dasm (5.59% of base)
          32 : 16421.dasm (4.32% of base)
          32 : 114721.dasm (3.05% of base)
          32 : 114732.dasm (3.05% of base)
          32 : 114745.dasm (3.05% of base)
          32 : 16441.dasm (4.32% of base)
          32 : 176511.dasm (4.32% of base)
          32 : 16459.dasm (4.32% of base)
          28 : 87574.dasm (1.62% of base)
          28 : 16298.dasm (1.53% of base)
          28 : 65875.dasm (2.00% of base)
          28 : 209428.dasm (0.68% of base)
          24 : 129351.dasm (8.22% of base)

Top file improvements (bytes):
        -920 : 58532.dasm (-4.65% of base)
        -684 : 35598.dasm (-2.60% of base)
        -324 : 31577.dasm (-5.53% of base)
        -300 : 122508.dasm (-8.17% of base)
        -256 : 129247.dasm (-6.11% of base)
        -248 : 63214.dasm (-3.58% of base)
        -232 : 2427.dasm (-1.07% of base)
        -224 : 130773.dasm (-0.69% of base)
        -224 : 144761.dasm (-3.17% of base)
        -216 : 96724.dasm (-3.52% of base)
        -204 : 204762.dasm (-5.60% of base)
        -200 : 202806.dasm (-1.80% of base)
        -200 : 96728.dasm (-3.22% of base)
        -188 : 14688.dasm (-1.20% of base)
        -188 : 63538.dasm (-1.39% of base)
        -180 : 96736.dasm (-3.42% of base)
        -176 : 45855.dasm (-6.46% of base)
        -176 : 155701.dasm (-6.31% of base)
        -172 : 128124.dasm (-3.19% of base)
        -172 : 29536.dasm (-5.32% of base)

37403 total files with Code Size differences (37337 improved, 66 regressed), 2520 unchanged.

Top method regressions (bytes):
          48 (17.14% of base) : 198893.dasm - System.Threading.Tasks.Dataflow.Internal.ReorderingBuffer`1:OutputNextItem(System.__Canon,bool):this
          44 ( 7.64% of base) : 176280.dasm - System.Net.Http.WinHttpCookieContainerAdapter:AddResponseCookiesToContainer(System.Net.Http.WinHttpRequestState)
          40 (11.49% of base) : 161594.dasm - System.IO.Compression.BrotliStream:Read(System.Span`1[System.Byte]):int:this
          32 ( 3.51% of base) : 178452.dasm - <SpecializeProperties>d__4:MoveNext():bool:this
          32 ( 3.51% of base) : 178458.dasm - <SpecializeFields>d__3:MoveNext():bool:this
          32 ( 3.51% of base) : 178464.dasm - <SpecializeEvents>d__2:MoveNext():bool:this
          32 ( 6.06% of base) : 112077.dasm - System.Text.DecoderFallbackBufferHelper:InternalFallback(System.Byte[],long):int:this
          32 ( 5.59% of base) : 112078.dasm - System.Text.DecoderFallbackBufferHelper:InternalFallback(System.Byte[],long,byref):bool:this
          32 ( 4.32% of base) : 16421.dasm - <Microsoft-Cci-ITypeDefinition-GetProperties>d__71:MoveNext():bool:this
          32 ( 3.05% of base) : 114721.dasm - VB$StateMachine_78_ITypeDefinitionGetProperties:MoveNext():bool:this
          32 ( 3.05% of base) : 114732.dasm - VB$StateMachine_75_ITypeDefinitionGetMethods:MoveNext():bool:this
          32 ( 3.05% of base) : 114745.dasm - VB$StateMachine_35_ITypeDefinitionGetFields:MoveNext():bool:this
          32 ( 4.32% of base) : 16441.dasm - <Microsoft-Cci-ITypeDefinition-GetMethods>d__68:MoveNext():bool:this
          32 ( 4.32% of base) : 176511.dasm - <GetVirtualMethods>d__44:MoveNext():bool:this
          32 ( 4.32% of base) : 16459.dasm - <Microsoft-Cci-ITypeDefinition-GetFields>d__32:MoveNext():bool:this
          28 ( 1.62% of base) : 87574.dasm - <ExecuteFilter>d__4:MoveNext():bool:this
          28 ( 1.53% of base) : 16298.dasm - <GetSecurityAttributes>d__110:MoveNext():bool:this
          28 ( 2.00% of base) : 65875.dasm - System.Enum:TryParse(System.Type,System.ReadOnlySpan`1[System.Char],bool,bool,byref):bool
          28 ( 0.68% of base) : 209428.dasm - <BuildCommandLineArguments>d__15:MoveNext():bool:this
          24 ( 8.22% of base) : 129351.dasm - Microsoft.CodeAnalysis.VisualBasic.LambdaRewriter:LowestCommonAncestor(Microsoft.CodeAnalysis.VisualBasic.BoundNode,Microsoft.CodeAnalysis.VisualBasic.BoundNode):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method improvements (bytes):
        -920 (-4.65% of base) : 58532.dasm - System.Globalization.CultureData:get_RegionNames():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -684 (-2.60% of base) : 35598.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[System.String],System.String,System.String,System.String):Microsoft.CodeAnalysis.CSharp.CSharpCommandLineArguments:this
        -324 (-5.53% of base) : 31577.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -300 (-8.17% of base) : 122508.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
        -256 (-6.11% of base) : 129247.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:TransformRewrittenBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
        -248 (-3.58% of base) : 63214.dasm - System.DateTimeParse:ParseByFormat(byref,byref,byref,System.Globalization.DateTimeFormatInfo,byref):bool
        -232 (-1.07% of base) : 2427.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
        -224 (-0.69% of base) : 130773.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[System.String],System.String,System.String,System.String):Microsoft.CodeAnalysis.VisualBasic.VisualBasicCommandLineArguments:this
        -224 (-3.17% of base) : 144761.dasm - DataContractCriticalHelper:TryCreateBuiltInDataContract(System.String,System.String,byref):bool
        -216 (-3.52% of base) : 96724.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitDocOrderDistinct(System.Xml.Xsl.Qil.QilUnary):System.Xml.Xsl.Qil.QilNode:this
        -204 (-5.60% of base) : 204762.dasm - System.Management.WmiNetUtilsHelper:.cctor()
        -200 (-1.80% of base) : 202806.dasm - System.Configuration.ConfigurationElement:DeserializeElement(System.Xml.XmlReader,bool):this
        -200 (-3.22% of base) : 96728.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitLoop(System.Xml.Xsl.Qil.QilLoop):System.Xml.Xsl.Qil.QilNode:this
        -188 (-1.20% of base) : 14688.dasm - <SendAsyncCore>d__60:MoveNext():this
        -188 (-1.39% of base) : 63538.dasm - System.DefaultBinder:BindToMethod(int,System.Reflection.MethodBase[],byref,System.Reflection.ParameterModifier[],System.Globalization.CultureInfo,System.String[],byref):System.Reflection.MethodBase:this
        -180 (-3.42% of base) : 96736.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitEq(System.Xml.Xsl.Qil.QilBinary):System.Xml.Xsl.Qil.QilNode:this
        -176 (-6.46% of base) : 45855.dasm - Microsoft.Cci.MetadataWriter:SerializeMetadataTables(Microsoft.Cci.BlobBuilder,Microsoft.Cci.MetadataSizes,int,int):this
        -176 (-6.31% of base) : 155701.dasm - System.Reflection.Metadata.Ecma335.MetadataBuilder:SerializeMetadataTables(System.Reflection.Metadata.BlobBuilder,System.Reflection.Metadata.Ecma335.MetadataSizes,System.Collections.Immutable.ImmutableArray`1[System.Int32],int,int):this
        -172 (-3.19% of base) : 128124.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
        -172 (-5.32% of base) : 29536.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this

Top method regressions (percentages):
          48 (17.14% of base) : 198893.dasm - System.Threading.Tasks.Dataflow.Internal.ReorderingBuffer`1:OutputNextItem(System.__Canon,bool):this
          40 (11.49% of base) : 161594.dasm - System.IO.Compression.BrotliStream:Read(System.Span`1[System.Byte]):int:this
          24 ( 8.22% of base) : 129351.dasm - Microsoft.CodeAnalysis.VisualBasic.LambdaRewriter:LowestCommonAncestor(Microsoft.CodeAnalysis.VisualBasic.BoundNode,Microsoft.CodeAnalysis.VisualBasic.BoundNode):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          44 ( 7.64% of base) : 176280.dasm - System.Net.Http.WinHttpCookieContainerAdapter:AddResponseCookiesToContainer(System.Net.Http.WinHttpRequestState)
          24 ( 6.38% of base) : 201416.dasm - Enumerator:System.Collections.IEnumerator.MoveNext():bool:this
          32 ( 6.06% of base) : 112077.dasm - System.Text.DecoderFallbackBufferHelper:InternalFallback(System.Byte[],long):int:this
          20 ( 5.75% of base) : 114766.dasm - VB$StateMachine_10_GetSizes:MoveNext():bool:this
          20 ( 5.68% of base) : 16502.dasm - <GetSizes>d__10:MoveNext():bool:this
          32 ( 5.59% of base) : 112078.dasm - System.Text.DecoderFallbackBufferHelper:InternalFallback(System.Byte[],long,byref):bool:this
          20 ( 4.35% of base) : 40024.dasm - <ResolveAnalyzerReferences>d__161:MoveNext():bool:this
          32 ( 4.32% of base) : 16421.dasm - <Microsoft-Cci-ITypeDefinition-GetProperties>d__71:MoveNext():bool:this
          32 ( 4.32% of base) : 16441.dasm - <Microsoft-Cci-ITypeDefinition-GetMethods>d__68:MoveNext():bool:this
          32 ( 4.32% of base) : 176511.dasm - <GetVirtualMethods>d__44:MoveNext():bool:this
          32 ( 4.32% of base) : 16459.dasm - <Microsoft-Cci-ITypeDefinition-GetFields>d__32:MoveNext():bool:this
          20 ( 4.20% of base) : 176499.dasm - <GetNestedTypes>d__51:MoveNext():bool:this
          32 ( 3.51% of base) : 178452.dasm - <SpecializeProperties>d__4:MoveNext():bool:this
          32 ( 3.51% of base) : 178458.dasm - <SpecializeFields>d__3:MoveNext():bool:this
          32 ( 3.51% of base) : 178464.dasm - <SpecializeEvents>d__2:MoveNext():bool:this
          16 ( 3.42% of base) : 214599.dasm - <Wrap>d__0`1:MoveNext():bool:this
          20 ( 3.38% of base) : 176504.dasm - <GetFields>d__49:MoveNext():bool:this

Top method improvements (percentages):
          -8 (-14.29% of base) : 131164.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:AllowsCompileTimeOperations(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-14.29% of base) : 131165.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:AllowsCompileTimeConversions(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-14.29% of base) : 34768.dasm - Microsoft.CodeAnalysis.CSharp.CSharpExtensions:IsReservedKeyword(Microsoft.CodeAnalysis.SyntaxToken):bool
          -8 (-14.29% of base) : 34769.dasm - Microsoft.CodeAnalysis.CSharp.CSharpExtensions:IsContextualKeyword(Microsoft.CodeAnalysis.SyntaxToken):bool
          -8 (-14.29% of base) : 115542.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicExtensions:IsPreprocessorKeyword(Microsoft.CodeAnalysis.SyntaxToken):bool
          -8 (-14.29% of base) : 115544.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicExtensions:IsReservedKeyword(Microsoft.CodeAnalysis.SyntaxToken):bool
          -8 (-14.29% of base) : 115545.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicExtensions:IsKeyword(Microsoft.CodeAnalysis.SyntaxToken):bool
         -24 (-13.64% of base) : 60424.dasm - System.OrdinalComparer:Equals(System.String,System.String):bool:this
          -8 (-13.33% of base) : 44308.dasm - Microsoft.CodeAnalysis.ConstantValue:get_IsUnsigned():bool:this
          -8 (-13.33% of base) : 44312.dasm - Microsoft.CodeAnalysis.ConstantValue:get_IsIntegral():bool:this
          -8 (-13.33% of base) : 131122.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsPrimitiveType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131169.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsIntrinsicValueType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131173.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsRestrictedType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131177.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsStrictSupertypeOfConcreteDelegate(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131184.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsFloatingType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131185.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsSignedIntegralType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131186.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsUnsignedIntegralType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131187.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsIntegralType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 131188.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:IsNumericType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -8 (-13.33% of base) : 19255.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbolExtensions:IsPrimitiveRecursiveStruct(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):bool

37403 total methods with Code Size differences (37337 improved, 66 regressed), 2520 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 6058476
Total bytes of diff: 6021020
Total bytes of delta: -37456 (-0.62% of base)
Total relative delta: -71.39
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 151923.dasm (0.25% of base)
           4 : 121934.dasm (0.56% of base)
           4 : 130100.dasm (1.18% of base)
           4 : 130132.dasm (1.18% of base)
           4 : 170137.dasm (0.12% of base)

Top file improvements (bytes):
        -440 : 23633.dasm (-2.02% of base)
        -324 : 27471.dasm (-3.53% of base)
        -224 : 119529.dasm (-4.11% of base)
        -168 : 166380.dasm (-3.12% of base)
        -164 : 181378.dasm (-12.09% of base)
        -140 : 104120.dasm (-2.77% of base)
        -140 : 221165.dasm (-2.99% of base)
        -136 : 131387.dasm (-2.22% of base)
        -136 : 173716.dasm (-6.20% of base)
        -132 : 27477.dasm (-2.93% of base)
        -116 : 136777.dasm (-1.90% of base)
        -116 : 42996.dasm (-2.83% of base)
        -112 : 130880.dasm (-3.03% of base)
        -112 : 232431.dasm (-1.43% of base)
        -104 : 119527.dasm (-2.93% of base)
        -104 : 211476.dasm (-2.40% of base)
        -104 : 27472.dasm (-2.86% of base)
        -104 : 145846.dasm (-2.85% of base)
         -96 : 66578.dasm (-6.20% of base)
         -92 : 111029.dasm (-2.60% of base)

4543 total files with Code Size differences (4538 improved, 5 regressed), 2075 unchanged.

Top method regressions (bytes):
           8 ( 0.25% of base) : 151923.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
           4 ( 0.56% of base) : 121934.dasm - System.Xml.Base64Decoder:Decode(System.ReadOnlySpan`1[Char],System.Span`1[Byte],byref,byref):this
           4 ( 1.18% of base) : 130100.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           4 ( 1.18% of base) : 130132.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           4 ( 0.12% of base) : 170137.dasm - System.Configuration.MgmtConfigurationRecord:GetConfigDefinitionUpdates(bool,int,bool,byref,byref):this

Top method improvements (bytes):
        -440 (-2.02% of base) : 23633.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String,System.String,System.String):Microsoft.CodeAnalysis.CSharp.CSharpCommandLineArguments:this
        -324 (-3.53% of base) : 27471.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -224 (-4.11% of base) : 119529.dasm - DataContractCriticalHelper:TryCreateBuiltInDataContract(System.String,System.String,byref):bool
        -168 (-3.12% of base) : 166380.dasm - System.ComponentModel.CategoryAttribute:GetLocalizedString(System.String):System.String:this
        -164 (-12.09% of base) : 181378.dasm - System.Drawing.SystemFonts:GetFontByName(System.String):System.Drawing.Font
        -140 (-2.77% of base) : 104120.dasm - Newtonsoft.Json.Schema.JsonSchemaBuilder:ProcessSchemaProperties(Newtonsoft.Json.Linq.JObject):this
        -140 (-2.99% of base) : 221165.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
        -136 (-2.22% of base) : 131387.dasm - System.Xml.Xsl.Runtime.XmlCollation:Create(System.String,bool):System.Xml.Xsl.Runtime.XmlCollation
        -136 (-6.20% of base) : 173716.dasm - System.Data.OleDb.OleDbSchemaGuid:GetTextFromValue(System.Guid):System.String
        -132 (-2.93% of base) : 27477.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
        -116 (-1.90% of base) : 136777.dasm - System.Speech.Internal.SrgsParser.XmlParser:ParseGrammar(System.Xml.XmlReader,System.Speech.Internal.SrgsParser.IGrammar):this
        -116 (-2.83% of base) : 42996.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
        -112 (-3.03% of base) : 130880.dasm - System.Xml.Xsl.XsltOld.XsltCompileContext:FunctionAvailable(System.String):bool:this
        -112 (-1.43% of base) : 232431.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
        -104 (-2.93% of base) : 119527.dasm - DataContractCriticalHelper:GetBuiltInDataContract(System.String):System.Runtime.Serialization.DataContract
        -104 (-2.40% of base) : 211476.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
        -104 (-2.86% of base) : 27472.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetOperatorKind(System.String):ushort
        -104 (-2.85% of base) : 145846.dasm - Microsoft.CSharp.RuntimeBinder.SymbolTable:IsOperator(System.Reflection.MethodInfo):bool
         -96 (-6.20% of base) : 66578.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:FoldIntegralCharOrDateTimeBinaryOperator(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,byref,byref):Microsoft.CodeAnalysis.ConstantValue
         -92 (-2.60% of base) : 111029.dasm - System.Data.Common.DbColumn:get_Item(System.String):System.Object:this

Top method regressions (percentages):
           4 ( 1.18% of base) : 130100.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           4 ( 1.18% of base) : 130132.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           4 ( 0.56% of base) : 121934.dasm - System.Xml.Base64Decoder:Decode(System.ReadOnlySpan`1[Char],System.Span`1[Byte],byref,byref):this
           8 ( 0.25% of base) : 151923.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
           4 ( 0.12% of base) : 170137.dasm - System.Configuration.MgmtConfigurationRecord:GetConfigDefinitionUpdates(bool,int,bool,byref,byref):this

Top method improvements (percentages):
         -16 (-25.00% of base) : 101321.dasm - <>c:<ParseSymbolFile>b__23_0(ubyte):bool:this
          -4 (-16.67% of base) : 174394.dasm - System.Diagnostics.ActivityTraceId:op_Equality(System.Diagnostics.ActivityTraceId,System.Diagnostics.ActivityTraceId):bool
          -4 (-16.67% of base) : 174412.dasm - System.Diagnostics.ActivitySpanId:op_Equality(System.Diagnostics.ActivitySpanId,System.Diagnostics.ActivitySpanId):bool
          -8 (-16.67% of base) : 173841.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
          -4 (-16.67% of base) : 218768.dasm - System.Security.Cryptography.HashAlgorithmName:op_Equality(System.Security.Cryptography.HashAlgorithmName,System.Security.Cryptography.HashAlgorithmName):bool
          -4 (-16.67% of base) : 52960.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:AllowsCompileTimeConversions(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -4 (-16.67% of base) : 52961.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:AllowsCompileTimeOperations(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -4 (-16.67% of base) : 75895.dasm - Microsoft.CodeAnalysis.DocumentationCommentIncludeCache:KeyValueEquality(System.String,System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Xml.Linq.XDocument, System.Private.Xml.Linq, Version=7.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51]]):bool
          -8 (-16.67% of base) : 171875.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
         -24 (-15.00% of base) : 173864.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
         -24 (-15.00% of base) : 111188.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
         -24 (-15.00% of base) : 171826.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
          -4 (-14.29% of base) : 43933.dasm - <>c:<GetPreprocessingSymbolInfo>b__165_0(Microsoft.CodeAnalysis.SyntaxNode):bool:this
          -4 (-14.29% of base) : 233719.dasm - Microsoft.Xunit.Performance.Api.Common:get_IsWindowsPlatform():bool
          -4 (-14.29% of base) : 174396.dasm - System.Diagnostics.ActivityTraceId:Equals(System.Diagnostics.ActivityTraceId):bool:this
          -4 (-14.29% of base) : 174414.dasm - System.Diagnostics.ActivitySpanId:Equals(System.Diagnostics.ActivitySpanId):bool:this
          -4 (-14.29% of base) : 74893.dasm - Microsoft.CodeAnalysis.CommandLineAnalyzerReference:Equals(Microsoft.CodeAnalysis.CommandLineAnalyzerReference):bool:this
          -4 (-14.29% of base) : 212800.dasm - System.Runtime.InteropServices.OSPlatform:op_Equality(System.Runtime.InteropServices.OSPlatform,System.Runtime.InteropServices.OSPlatform):bool
          -4 (-14.29% of base) : 218766.dasm - System.Security.Cryptography.HashAlgorithmName:Equals(System.Security.Cryptography.HashAlgorithmName):bool:this
          -4 (-14.29% of base) : 165648.dasm - System.ComponentModel.Composition.Hosting.DirectoryCatalog:get_IsWindows():bool

4543 total methods with Code Size differences (4538 improved, 5 regressed), 2075 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 13883328
Total bytes of diff: 13793168
Total bytes of delta: -90160 (-0.65% of base)
Total relative delta: -201.75
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          36 : 64867.dasm (1.97% of base)
          12 : 189071.dasm (0.79% of base)
           8 : 312175.dasm (1.20% of base)
           8 : 312177.dasm (0.93% of base)
           8 : 312178.dasm (0.74% of base)
           4 : 64865.dasm (0.21% of base)
           4 : 123526.dasm (0.31% of base)

Top file improvements (bytes):
        -340 : 123403.dasm (-2.31% of base)
        -320 : 309118.dasm (-2.51% of base)
        -228 : 152125.dasm (-6.19% of base)
        -192 : 151231.dasm (-2.40% of base)
        -184 : 68412.dasm (-3.16% of base)
        -184 : 124675.dasm (-16.43% of base)
        -164 : 255982.dasm (-2.41% of base)
        -160 : 74521.dasm (-1.67% of base)
        -148 : 129928.dasm (-1.54% of base)
        -144 : 340492.dasm (-1.87% of base)
        -144 : 150560.dasm (-6.61% of base)
        -136 : 155314.dasm (-5.87% of base)
        -120 : 124663.dasm (-16.39% of base)
        -112 : 135265.dasm (-2.59% of base)
        -112 : 249595.dasm (-5.61% of base)
        -112 : 176628.dasm (-1.07% of base)
        -108 : 123126.dasm (-3.26% of base)
        -108 : 152127.dasm (-4.84% of base)
        -108 : 152143.dasm (-2.96% of base)
        -108 : 11939.dasm (-2.76% of base)

12130 total files with Code Size differences (12123 improved, 7 regressed), 4589 unchanged.

Top method regressions (bytes):
          36 ( 1.97% of base) : 64867.dasm - <Send_RequestContentNotDisposed>d__3:MoveNext():this
          12 ( 0.79% of base) : 189071.dasm - System.Tests.ConvertTests:TryFromBase64String(System.String,System.Byte[])
           8 ( 1.20% of base) : 312175.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Receives_Correct_Arguments()
           8 ( 0.93% of base) : 312177.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Receives_Correct_Arguments()
           8 ( 0.74% of base) : 312178.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Via_Params_Receives_Correct_Arguments()
           4 ( 0.21% of base) : 64865.dasm - <Send_DuplicateRequest_ThrowsException>d__2:MoveNext():this
           4 ( 0.31% of base) : 123526.dasm - Microsoft.CodeAnalysis.CSharp.CodeStyle.TypeStyle.TypeStyleHelper:IsTypeApparentInAssignmentExpression(int,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.ITypeSymbol,System.Threading.CancellationToken):bool

Top method improvements (bytes):
        -340 (-2.31% of base) : 123403.dasm - Microsoft.CodeAnalysis.CSharp.Extensions.ContextQuery.SyntaxTreeExtensions:IsExpressionContext(Microsoft.CodeAnalysis.SyntaxTree,int,Microsoft.CodeAnalysis.SyntaxToken,bool,System.Threading.CancellationToken,Microsoft.CodeAnalysis.SemanticModel):bool
        -320 (-2.51% of base) : 309118.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4EqualsNanTest():this
        -228 (-6.19% of base) : 152125.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:Remove():this
        -192 (-2.40% of base) : 151231.dasm - System.Data.Tests.DataTableTest4:XmlTest10():this
        -184 (-3.16% of base) : 68412.dasm - System.Tests.AttributeGetCustomAttributes:RunPosTests()
        -184 (-16.43% of base) : 124675.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -164 (-2.41% of base) : 255982.dasm - NuGet.Frameworks.NuGetFramework:TryParseCommonFramework(System.String,byref):bool
        -160 (-1.67% of base) : 74521.dasm - <ToString_MatchesExpected_MemberData>d__105:MoveNext():bool:this
        -148 (-1.54% of base) : 129928.dasm - Microsoft.Diagnostics.Runtime.Desktop.LockInspection:SetThreadWaiters():this
        -144 (-1.87% of base) : 340492.dasm - TCNamespace:TestNamespace6():this
        -144 (-6.61% of base) : 150560.dasm - System.Data.Tests.DataRowTest2:HasVersion_ByDataRowVersion():this
        -136 (-5.87% of base) : 155314.dasm - System.ComponentModel.TypeConverterTests.IconConverterTest:TestCanConvertTo():this
        -120 (-16.39% of base) : 124663.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -112 (-2.59% of base) : 135265.dasm - NuGet.Packaging.ManifestReader:ReadMetadataValue(NuGet.Packaging.ManifestMetadata,System.Xml.Linq.XElement,System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
        -112 (-5.61% of base) : 249595.dasm - Microsoft.Extensions.Logging.Test.EventSourceLoggerTest:FilterSpecs_UseAppFilters_IncreaseLoggingLevelForOneCategory_GuaranteesAllRulesRemainAvailable():this
        -112 (-1.07% of base) : 176628.dasm - System.Buffers.Text.Tests.FormatterTests:TryFormatUtf8(System.Object,System.Span`1[Byte],byref,System.Buffers.StandardFormat):bool
        -108 (-3.26% of base) : 123126.dasm - Microsoft.CodeAnalysis.CSharp.Extensions.ParenthesizedExpressionSyntaxExtensions:CanRemoveParentheses(Microsoft.CodeAnalysis.CSharp.Syntax.ParenthesizedExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,System.Threading.CancellationToken):bool
        -108 (-4.84% of base) : 152127.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:ContainsKey():this
        -108 (-2.96% of base) : 152143.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:TryGetValueTest():this
        -108 (-2.76% of base) : 11939.dasm - Microsoft.CodeAnalysis.Classification.Classifier:GetClassificationKind(System.String):System.Nullable`1[SymbolDisplayPartKind]

Top method regressions (percentages):
          36 ( 1.97% of base) : 64867.dasm - <Send_RequestContentNotDisposed>d__3:MoveNext():this
           8 ( 1.20% of base) : 312175.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Receives_Correct_Arguments()
           8 ( 0.93% of base) : 312177.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Receives_Correct_Arguments()
          12 ( 0.79% of base) : 189071.dasm - System.Tests.ConvertTests:TryFromBase64String(System.String,System.Byte[])
           8 ( 0.74% of base) : 312178.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Via_Params_Receives_Correct_Arguments()
           4 ( 0.31% of base) : 123526.dasm - Microsoft.CodeAnalysis.CSharp.CodeStyle.TypeStyle.TypeStyleHelper:IsTypeApparentInAssignmentExpression(int,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.ITypeSymbol,System.Threading.CancellationToken):bool
           4 ( 0.21% of base) : 64865.dasm - <Send_DuplicateRequest_ThrowsException>d__2:MoveNext():this

Top method improvements (percentages):
          -8 (-16.67% of base) : 216126.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
          -4 (-16.67% of base) : 240857.dasm - Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection:op_Equality(Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection,Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection):bool
          -8 (-16.67% of base) : 220482.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
        -184 (-16.43% of base) : 124675.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -120 (-16.39% of base) : 124663.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
         -20 (-15.62% of base) : 349395.dasm - System.PlatformDetection:get_IsSizeOptimized():bool
         -20 (-15.62% of base) : 349434.dasm - System.PlatformDetection:get_IsMobile():bool
         -24 (-15.00% of base) : 216101.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
         -24 (-15.00% of base) : 220459.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
          -4 (-14.29% of base) : 122256.dasm - Microsoft.CodeAnalysis.CSharp.LanguageServices.CSharpSyntaxFacts:IsTypeDeclaration(Microsoft.CodeAnalysis.SyntaxNode):bool:this
          -4 (-14.29% of base) : 349310.dasm - System.PlatformDetection:get_IsWindows():bool
         -16 (-14.29% of base) : 349347.dasm - System.PlatformDetection:get_IsOSXLike():bool
          -4 (-14.29% of base) : 349348.dasm - System.PlatformDetection:get_IsOSX():bool
          -4 (-14.29% of base) : 349391.dasm - System.PlatformDetection:get_IsLinux():bool
         -16 (-14.29% of base) : 349417.dasm - System.PlatformDetection:get_IsOpenSslSupported():bool
         -16 (-14.29% of base) : 349418.dasm - System.PlatformDetection:get_UsesAppleCrypto():bool
          -4 (-14.29% of base) : 185912.dasm - System.Net.Sockets.Tests.SocketHelperEap:get_SupportsAcceptReceive():bool:this
          -4 (-14.29% of base) : 2278.dasm - Microsoft.CodeAnalysis.SymbolKey:Equals(Microsoft.CodeAnalysis.SymbolKey):bool:this
          -4 (-14.29% of base) : 317865.dasm - System.Drawing.Helpers:get_IsNotUnix():bool
          -4 (-14.29% of base) : 2410.dasm - Microsoft.CodeAnalysis.CompilationOutputInfo:Equals(Microsoft.CodeAnalysis.CompilationOutputInfo):bool:this

12130 total methods with Code Size differences (12123 improved, 7 regressed), 4589 unchanged.

```

</details>

--------------------------------------------------------------------------------

