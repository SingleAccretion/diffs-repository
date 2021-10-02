## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1412684
Total bytes of diff: 1408970
Total bytes of delta: -3714 (-0.26% of base)
Total relative delta: -6.70
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          13 : 30335.dasm (1.10% of base)
           5 : 15347.dasm (0.20% of base)
           1 : 15483.dasm (0.02% of base)

Top file improvements (bytes):
         -82 : 41586.dasm (-2.98% of base)
         -66 : 40133.dasm (-4.61% of base)
         -57 : 27589.dasm (-7.43% of base)
         -47 : 34751.dasm (-6.08% of base)
         -39 : 27590.dasm (-11.05% of base)
         -29 : 15714.dasm (-4.10% of base)
         -28 : 5314.dasm (-3.78% of base)
         -28 : 10923.dasm (-3.78% of base)
         -27 : 34735.dasm (-13.17% of base)
         -27 : 41099.dasm (-13.17% of base)
         -26 : 31256.dasm (-3.96% of base)
         -26 : 40492.dasm (-5.79% of base)
         -23 : 14722.dasm (-5.05% of base)
         -22 : 36703.dasm (-0.89% of base)
         -21 : 27317.dasm (-3.66% of base)
         -20 : 29196.dasm (-1.75% of base)
         -19 : 31361.dasm (-9.45% of base)
         -19 : 26575.dasm (-4.32% of base)
         -19 : 27441.dasm (-9.45% of base)
         -19 : 40012.dasm (-1.68% of base)

876 total files with Code Size differences (873 improved, 3 regressed), 215 unchanged.

Top method regressions (bytes):
          13 ( 1.10% of base) : 30335.dasm - ResourceManager:GetFirstResourceSet(CultureInfo):ResourceSet:this
           5 ( 0.20% of base) : 15347.dasm - HttpTransformer:TransformRequestAsync(HttpContext,HttpRequestMessage,String):ValueTask:this
           1 ( 0.02% of base) : 15483.dasm - Uri:ParseRemaining():this

Top method improvements (bytes):
         -82 (-2.98% of base) : 41586.dasm - NpgsqlSchema:GetSchema(NpgsqlConnection,String,ref,bool,CancellationToken):Task`1
         -66 (-4.61% of base) : 40133.dasm - PostgresBaseType:TranslateInternalName(String):String
         -57 (-7.43% of base) : 27589.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -47 (-6.08% of base) : 34751.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -39 (-11.05% of base) : 27590.dasm - Socket:SetToConnected():this
         -29 (-4.10% of base) : 15714.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -28 (-3.78% of base) : 5314.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -28 (-3.78% of base) : 10923.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -27 (-13.17% of base) : 34735.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -27 (-13.17% of base) : 41099.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -26 (-3.96% of base) : 31256.dasm - RuntimeConstructorInfo:<get_InvocationFlags>g__LazyCreateInvocationFlags|13_0():int:this
         -26 (-5.79% of base) : 40492.dasm - CerHashtable`2:get_Item(__Canon):__Canon:this
         -23 (-5.05% of base) : 14722.dasm - HttpHeaders:TryGetHeaderDescriptor(String,byref):bool:this
         -22 (-0.89% of base) : 36703.dasm - SharedTableConvention:TryUniquifyForeignKeyNames(IConventionEntityType,Dictionary`2,byref,int):this
         -21 (-3.66% of base) : 27317.dasm - TypeUtils:ValidateType(Type,String,int):bool
         -20 (-1.75% of base) : 29196.dasm - NpgsqlConnector:ReadParameterStatus(ReadOnlySpan`1,ReadOnlySpan`1):this
         -19 (-9.45% of base) : 31361.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -19 (-4.32% of base) : 26575.dasm - CerHashtable`2:get_Item(__Canon):__Canon:this
         -19 (-9.45% of base) : 27441.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -19 (-1.68% of base) : 40012.dasm - NpgsqlConnector:ReadParameterStatus(ReadOnlySpan`1,ReadOnlySpan`1):this

Top method regressions (percentages):
          13 ( 1.10% of base) : 30335.dasm - ResourceManager:GetFirstResourceSet(CultureInfo):ResourceSet:this
           5 ( 0.20% of base) : 15347.dasm - HttpTransformer:TransformRequestAsync(HttpContext,HttpRequestMessage,String):ValueTask:this
           1 ( 0.02% of base) : 15483.dasm - Uri:ParseRemaining():this

Top method improvements (percentages):
         -27 (-13.17% of base) : 34735.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -27 (-13.17% of base) : 41099.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -39 (-11.05% of base) : 27590.dasm - Socket:SetToConnected():this
          -3 (-10.34% of base) : 39185.dasm - <>c:<Main>b__3_2(WebHostBuilderContext,ServiceProviderOptions):this
         -19 (-9.45% of base) : 31361.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -19 (-9.45% of base) : 27441.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -57 (-7.43% of base) : 27589.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -14 (-7.22% of base) : 27591.dasm - Socket:UpdateLocalEndPointOnConnect():this
         -12 (-7.06% of base) : 15702.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -12 (-6.15% of base) : 5289.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -12 (-6.15% of base) : 10907.dasm - Socket:IsWildcardEndPoint(EndPoint):bool:this
         -47 (-6.08% of base) : 34751.dasm - Socket:UpdateAcceptSocket(Socket,EndPoint):Socket:this
         -11 (-6.04% of base) : 15711.dasm - Socket:UpdateLocalEndPointOnConnect():this
         -26 (-5.79% of base) : 40492.dasm - CerHashtable`2:get_Item(__Canon):__Canon:this
          -3 (-5.45% of base) : 38609.dasm - SafeDeleteContext:get_IsInvalid():bool:this
          -8 (-5.19% of base) : 14721.dasm - KnownHeaders:TryGetKnownHeader(String):KnownHeader
         -23 (-5.05% of base) : 14722.dasm - HttpHeaders:TryGetHeaderDescriptor(String,byref):bool:this
          -6 (-4.92% of base) : 41451.dasm - CoreSingletonOptions:Initialize(IDbContextOptions):this
         -66 (-4.61% of base) : 40133.dasm - PostgresBaseType:TranslateInternalName(String):String
          -9 (-4.48% of base) : 5316.dasm - Socket:UpdateLocalEndPointOnConnect():this

876 total methods with Code Size differences (873 improved, 3 regressed), 215 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 811818
Total bytes of diff: 808159
Total bytes of delta: -3659 (-0.45% of base)
Total relative delta: -6.73
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 20705.dasm (0.37% of base)
           4 : 10345.dasm (0.84% of base)
           4 : 23453.dasm (0.73% of base)
           1 : 5590.dasm (0.09% of base)

Top file improvements (bytes):
        -198 : 16843.dasm (-2.03% of base)
        -122 : 16901.dasm (-2.70% of base)
         -84 : 17743.dasm (-2.03% of base)
         -78 : 19357.dasm (-1.83% of base)
         -73 : 3539.dasm (-1.20% of base)
         -60 : 10704.dasm (-3.83% of base)
         -55 : 13968.dasm (-4.58% of base)
         -55 : 6967.dasm (-4.85% of base)
         -50 : 1853.dasm (-1.01% of base)
         -39 : 13589.dasm (-0.39% of base)
         -34 : 3698.dasm (-0.66% of base)
         -33 : 7940.dasm (-1.07% of base)
         -33 : 3620.dasm (-1.54% of base)
         -33 : 8579.dasm (-1.25% of base)
         -32 : 8432.dasm (-1.57% of base)
         -30 : 6900.dasm (-1.90% of base)
         -24 : 16909.dasm (-0.67% of base)
         -24 : 2116.dasm (-0.65% of base)
         -24 : 6403.dasm (-0.74% of base)
         -24 : 11796.dasm (-1.56% of base)

594 total files with Code Size differences (590 improved, 4 regressed), 151 unchanged.

Top method regressions (bytes):
          10 ( 0.37% of base) : 20705.dasm - System.Numerics.BigNumber:FormatBigInteger(bool,System.Numerics.BigInteger,System.String,System.ReadOnlySpan`1[Char],System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
           4 ( 0.84% of base) : 10345.dasm - System.Globalization.CultureData:get_CalendarIds():System.Globalization.CalendarId[]:this
           4 ( 0.73% of base) : 23453.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           1 ( 0.09% of base) : 5590.dasm - System.Uri:CheckCanonical(long,byref,int,ushort):int:this

Top method improvements (bytes):
        -198 (-2.03% of base) : 16843.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -122 (-2.70% of base) : 16901.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
         -84 (-2.03% of base) : 17743.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
         -78 (-1.83% of base) : 19357.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
         -73 (-1.20% of base) : 3539.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WritePrimitive(System.Xml.Serialization.TypeMapping,System.String):this
         -60 (-3.83% of base) : 10704.dasm - System.Text.Json.Serialization.JsonConverter`1[LargeStructWithProperties][MicroBenchmarks.Serializers.LargeStructWithProperties]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):MicroBenchmarks.Serializers.LargeStructWithProperties:this
         -55 (-4.58% of base) : 13968.dasm - System.Text.Json.Serialization.JsonConverter`1[Int32][System.Int32]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):int:this
         -55 (-4.85% of base) : 6967.dasm - System.Text.Json.Serialization.JsonConverter`1[__Canon][System.__Canon]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):System.__Canon:this
         -50 (-1.01% of base) : 1853.dasm - System.Globalization.DateTimeFormatInfo:CreateTokenHashTable():System.Globalization.DateTimeFormatInfo+TokenHashValue[]:this
         -39 (-0.39% of base) : 13589.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
         -34 (-0.66% of base) : 3698.dasm - System.Xml.XmlTextReaderImpl:ParseXmlDeclaration(bool):bool:this
         -33 (-1.07% of base) : 7940.dasm - System.Runtime.Serialization.Json.XmlJsonWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -33 (-1.54% of base) : 3620.dasm - System.Xml.XmlWellFormedWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -33 (-1.25% of base) : 8579.dasm - System.Xml.XmlBaseWriter:StartAttribute(byref,System.String,System.String,System.Xml.XmlDictionaryString):this
         -32 (-1.57% of base) : 8432.dasm - NamespaceManager:AddNamespace(System.String,System.String,System.Xml.XmlDictionaryString):this
         -30 (-1.90% of base) : 6900.dasm - System.Text.Json.Reflection.ReflectionExtensions:IsImmutableEnumerableType(System.Type,bool):bool
         -24 (-0.67% of base) : 16909.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Lexer:ScanNumericLiteral(byref):bool:this
         -24 (-0.65% of base) : 2116.dasm - System.Text.RegularExpressions.RegexNode:CanBeMadeAtomic(System.Text.RegularExpressions.RegexNode,System.Text.RegularExpressions.RegexNode,int):bool
         -24 (-0.74% of base) : 6403.dasm - System.Reflection.Metadata.MetadataReader:InitializeStreamReaders(byref,System.Reflection.Metadata.Ecma335.StreamHeader[],byref,byref,byref):this
         -24 (-1.56% of base) : 11796.dasm - System.Xml.Linq.XAttribute:ValidateAttribute(System.Xml.Linq.XName,System.String)

Top method regressions (percentages):
           4 ( 0.84% of base) : 10345.dasm - System.Globalization.CultureData:get_CalendarIds():System.Globalization.CalendarId[]:this
           4 ( 0.73% of base) : 23453.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
          10 ( 0.37% of base) : 20705.dasm - System.Numerics.BigNumber:FormatBigInteger(bool,System.Numerics.BigInteger,System.String,System.ReadOnlySpan`1[Char],System.Globalization.NumberFormatInfo,System.Span`1[Char],byref,byref):System.String
           1 ( 0.09% of base) : 5590.dasm - System.Uri:CheckCanonical(long,byref,int,ushort):int:this

Top method improvements (percentages):
         -19 (-9.74% of base) : 11739.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[__Canon][System.__Canon]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -19 (-9.74% of base) : 11735.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[LargeStructWithProperties][MicroBenchmarks.Serializers.LargeStructWithProperties]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
          -3 (-9.09% of base) : 19242.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol:Microsoft.Cci.ISignature.get_ReturnValueIsByRef():bool:this
         -14 (-8.86% of base) : 17476.dasm - Microsoft.CodeAnalysis.MetadataHelpers:GetAssemblyOrModuleNameErrorArgumentResourceName(System.String):System.String
          -7 (-8.33% of base) : 17766.dasm - Microsoft.CodeAnalysis.RuntimeMembers.SignatureComparer`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:ReadTypeId(System.Collections.Immutable.ImmutableArray`1[Byte],byref):short
          -6 (-5.41% of base) : 9916.dasm - System.Xml.ValidateNames:ParseNmtoken(System.String,int):int
         -11 (-5.39% of base) : 1525.dasm - <>c:<.cctor>b__1_0(System.Reflection.MethodInfo):bool:this
          -3 (-5.36% of base) : 25535.dasm - System.Tests.Perf_Char:Char_ToLowerInvariant(System.String):int:this
          -3 (-5.36% of base) : 25180.dasm - System.Tests.Perf_Char:Char_ToUpperInvariant(System.String):int:this
          -3 (-5.26% of base) : 6310.dasm - System.Reflection.Internal.ReadOnlyUnmanagedMemoryStream:Read(System.Byte[],int,int):int:this
         -11 (-5.24% of base) : 2852.dasm - Newtonsoft.Json.Converters.RegexConverter:CanConvert(System.Type):bool:this
         -18 (-5.19% of base) : 9552.dasm - Sigil.Impl.TypeOnStack:op_Equality(Sigil.Impl.TypeOnStack,Sigil.Impl.TypeOnStack):bool
          -6 (-4.92% of base) : 3613.dasm - System.Xml.XmlWellFormedWriter:CheckNCName(System.String):this
         -55 (-4.85% of base) : 6967.dasm - System.Text.Json.Serialization.JsonConverter`1[__Canon][System.__Canon]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):System.__Canon:this
          -2 (-4.65% of base) : 23149.dasm - System.Tests.Perf_Guid:EqualsSame():bool:this
         -55 (-4.58% of base) : 13968.dasm - System.Text.Json.Serialization.JsonConverter`1[Int32][System.Int32]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):int:this
          -3 (-4.35% of base) : 18901.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ContainsExtensionMethods():bool:this
          -4 (-4.30% of base) : 17801.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:get_PrimitiveTypeCode():int:this
          -5 (-4.27% of base) : 12767.dasm - CredentialEnumerator:MoveNext():bool:this
          -2 (-4.17% of base) : 2842.dasm - Newtonsoft.Json.Converters.EntityKeyMemberConverter:CanConvert(System.Type):bool:this

594 total methods with Code Size differences (590 improved, 4 regressed), 151 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1901131
Total bytes of diff: 1888692
Total bytes of delta: -12439 (-0.65% of base)
Total relative delta: -46.10
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 190.dasm (0.73% of base)
           3 : 196824.dasm (0.01% of base)
           3 : 207044.dasm (0.01% of base)
           2 : 231400.dasm (0.08% of base)

Top file improvements (bytes):
        -113 : 184052.dasm (-2.03% of base)
        -102 : 164986.dasm (-0.49% of base)
         -99 : 220457.dasm (-1.80% of base)
         -87 : 209791.dasm (-0.64% of base)
         -83 : 225062.dasm (-3.44% of base)
         -77 : 215002.dasm (-1.03% of base)
         -77 : 207069.dasm (-1.03% of base)
         -77 : 207072.dasm (-1.04% of base)
         -77 : 207081.dasm (-1.05% of base)
         -77 : 207085.dasm (-1.04% of base)
         -77 : 207132.dasm (-1.05% of base)
         -71 : 202838.dasm (-1.46% of base)
         -64 : 207777.dasm (-0.19% of base)
         -64 : 207783.dasm (-0.19% of base)
         -50 : 217898.dasm (-3.50% of base)
         -50 : 218004.dasm (-1.19% of base)
         -50 : 218016.dasm (-1.06% of base)
         -50 : 218021.dasm (-1.19% of base)
         -50 : 218234.dasm (-2.70% of base)
         -50 : 218236.dasm (-2.47% of base)

2337 total files with Code Size differences (2333 improved, 4 regressed), 233 unchanged.

Top method regressions (bytes):
           4 ( 0.73% of base) : 190.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           3 ( 0.01% of base) : 196824.dasm - lclfldrem:Main():int
           3 ( 0.01% of base) : 207044.dasm - lclfldrem:Main():int
           2 ( 0.08% of base) : 231400.dasm - ILGEN_0x977f9ed2:Method_0xf6b7353b():float

Top method improvements (bytes):
        -113 (-2.03% of base) : 184052.dasm - TailcallVerify.Program:Run(System.String):int
        -102 (-0.49% of base) : 164986.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
         -99 (-1.80% of base) : 220457.dasm - Test:bar(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String):int
         -87 (-0.64% of base) : 209791.dasm - ILGEN_0x372a9ae6:Method_0xdc6ff1a4(byte,byte,int,long,ushort,double,long,long):int
         -83 (-3.44% of base) : 225062.dasm - TestClass:LoadTypeInternal(System.String):System.Type
         -77 (-1.03% of base) : 215002.dasm - Test:Main():int
         -77 (-1.03% of base) : 207069.dasm - Test:Main():int
         -77 (-1.04% of base) : 207072.dasm - Test:Main():int
         -77 (-1.05% of base) : 207081.dasm - Test:Main():int
         -77 (-1.04% of base) : 207085.dasm - Test:Main():int
         -77 (-1.05% of base) : 207132.dasm - Test:Main():int
         -71 (-1.46% of base) : 202838.dasm - BenchmarkConsoleApplication.BenchmarkSystem:ProcessCommandLine(System.String[]):this
         -64 (-0.19% of base) : 207777.dasm - doubleMDArrTest:Main():int
         -64 (-0.19% of base) : 207783.dasm - floatMDArrTest:Main():int
         -50 (-3.50% of base) : 217898.dasm - Test:Main():int
         -50 (-1.19% of base) : 218004.dasm - Test:Main():int
         -50 (-1.06% of base) : 218016.dasm - Test:Main():int
         -50 (-1.19% of base) : 218021.dasm - Test:Main():int
         -50 (-2.70% of base) : 218234.dasm - Test:Main():int
         -50 (-2.47% of base) : 218236.dasm - Test:Main():int

Top method regressions (percentages):
           4 ( 0.73% of base) : 190.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           2 ( 0.08% of base) : 231400.dasm - ILGEN_0x977f9ed2:Method_0xf6b7353b():float
           3 ( 0.01% of base) : 196824.dasm - lclfldrem:Main():int
           3 ( 0.01% of base) : 207044.dasm - lclfldrem:Main():int

Top method improvements (percentages):
          -3 (-33.33% of base) : 87439.dasm - Program:Test_ldind_u1_conv_u2(byref,byref)
          -3 (-33.33% of base) : 87441.dasm - Program:Test_ldind_u1_conv_ovf_u2(byref,byref)
          -3 (-33.33% of base) : 87444.dasm - Program:Test_ldind_u1_conv_ovf_u2_un(byref,byref)
         -11 (-25.00% of base) : 86008.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
          -2 (-22.22% of base) : 87409.dasm - Program:Test_ldind_u1_conv_ovf_u8(byref,byref)
          -2 (-22.22% of base) : 87271.dasm - Program:Test_ldind_u2_conv_i8(byref,byref)
          -2 (-22.22% of base) : 87273.dasm - Program:Test_ldind_u2_conv_ovf_i8(byref,byref)
          -2 (-22.22% of base) : 87281.dasm - Program:Test_ldind_u2_conv_ovf_u8(byref,byref)
          -2 (-22.22% of base) : 87399.dasm - Program:Test_ldind_u1_conv_i8(byref,byref)
          -2 (-22.22% of base) : 87401.dasm - Program:Test_ldind_u1_conv_ovf_i8(byref,byref)
          -2 (-20.00% of base) : 209300.dasm - TestApp:test_309(ubyte,long):long
          -2 (-20.00% of base) : 209318.dasm - TestApp:test_36(ubyte,long):long
          -2 (-20.00% of base) : 209385.dasm - TestApp:test_114(ubyte,long):long
          -2 (-20.00% of base) : 209444.dasm - TestApp:test_192(ubyte,long):long
          -2 (-20.00% of base) : 209571.dasm - TestApp:test_153(ubyte,long):long
          -5 (-17.86% of base) : 86029.dasm - DevDiv_524309.ILGEN_CLASS:ILGEN_METHOD(long,short):bool
          -2 (-16.67% of base) : 209453.dasm - TestApp:test_270(ubyte,long):long
          -2 (-16.67% of base) : 209510.dasm - TestApp:test_348(ubyte,long):long
         -20 (-16.67% of base) : 85488.dasm - ILGEN_0x37ae0554:Method_0xb77ea7c1(short,short):int
          -1 (-14.29% of base) : 87431.dasm - Program:Test_ldind_u1_conv_i2(byref,byref)

2337 total methods with Code Size differences (2333 improved, 4 regressed), 233 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 16039933
Total bytes of diff: 15983100
Total bytes of delta: -56833 (-0.35% of base)
Total relative delta: -443.39
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          45 : 196712.dasm (28.85% of base)
          38 : 133132.dasm (1.58% of base)
          35 : 87779.dasm (17.24% of base)
          33 : 168184.dasm (16.34% of base)
          33 : 196552.dasm (18.54% of base)
          33 : 196647.dasm (18.23% of base)
          30 : 186704.dasm (16.67% of base)
          18 : 102912.dasm (3.54% of base)
          15 : 133133.dasm (0.85% of base)
          15 : 111603.dasm (1.22% of base)
           7 : 119722.dasm (0.60% of base)
           6 : 12202.dasm (1.76% of base)
           6 : 121476.dasm (1.24% of base)
           6 : 47753.dasm (0.31% of base)
           5 : 70470.dasm (0.83% of base)
           5 : 162324.dasm (2.98% of base)
           5 : 17803.dasm (0.51% of base)
           5 : 144595.dasm (0.46% of base)
           5 : 94569.dasm (2.84% of base)
           5 : 90899.dasm (0.28% of base)

Top file improvements (bytes):
       -1333 : 137351.dasm (-10.61% of base)
        -287 : 80715.dasm (-9.52% of base)
        -252 : 87675.dasm (-7.77% of base)
        -250 : 10983.dasm (-9.06% of base)
        -100 : 87875.dasm (-2.87% of base)
         -95 : 86551.dasm (-2.24% of base)
         -86 : 86444.dasm (-3.27% of base)
         -82 : 214491.dasm (-3.55% of base)
         -82 : 214558.dasm (-3.48% of base)
         -81 : 147203.dasm (-2.07% of base)
         -78 : 114415.dasm (-3.04% of base)
         -73 : 86447.dasm (-1.66% of base)
         -64 : 86563.dasm (-7.13% of base)
         -63 : 111639.dasm (-2.35% of base)
         -63 : 94178.dasm (-1.34% of base)
         -62 : 63062.dasm (-6.29% of base)
         -61 : 137601.dasm (-7.38% of base)
         -61 : 114419.dasm (-3.64% of base)
         -58 : 141955.dasm (-1.14% of base)
         -58 : 14047.dasm (-4.77% of base)

15246 total files with Code Size differences (14777 improved, 469 regressed), 24253 unchanged.

Top method regressions (bytes):
          45 (28.85% of base) : 196712.dasm - ElementAtQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          38 ( 1.58% of base) : 133132.dasm - System.Text.UnicodeEncoding:GetBytes(long,int,long,int,System.Text.EncoderNLS):int:this
          35 (17.24% of base) : 87779.dasm - Microsoft.CodeAnalysis.VisualBasic.LambdaRewriter:LowestCommonAncestor(Microsoft.CodeAnalysis.VisualBasic.BoundNode,Microsoft.CodeAnalysis.VisualBasic.BoundNode):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          33 (16.34% of base) : 168184.dasm - System.IO.Compression.BrotliStream:Read(System.Span`1[System.Byte]):int:this
          33 (18.54% of base) : 196552.dasm - WhereQueryOperatorEnumerator`1:MoveNext(byref,byref):bool:this
          33 (18.23% of base) : 196647.dasm - IndexedWhereQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          30 (16.67% of base) : 186704.dasm - System.Threading.Tasks.Dataflow.Internal.ReorderingBuffer`1:OutputNextItem(System.__Canon,bool):this
          18 ( 3.54% of base) : 102912.dasm - <GetKeywordKinds>d__17:MoveNext():bool:this
          15 ( 0.85% of base) : 133133.dasm - System.Text.UnicodeEncoding:GetByteCount(long,int,System.Text.EncoderNLS):int:this
          15 ( 1.22% of base) : 111603.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Lexer:ScanXmlEntity(byref):this
           7 ( 0.60% of base) : 119722.dasm - Microsoft.CodeAnalysis.CSharp.ClsComplianceChecker:CheckForAttributeWithArrayArgumentInternal(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbols.CSharpAttributeData]):this
           6 ( 1.76% of base) : 12202.dasm - System.Text.Json.Nodes.JsonValue:VerifyJsonElementIsNotArrayOrObject(byref)
           6 ( 1.24% of base) : 121476.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:MoreSpecificType(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):int
           6 ( 0.31% of base) : 47753.dasm - System.Drawing.ColorConverter:ConvertTo(System.ComponentModel.ITypeDescriptorContext,System.Globalization.CultureInfo,System.Object,System.Type):System.Object:this
           5 ( 0.83% of base) : 70470.dasm - WellKnownTagsSupport:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbol):this
           5 ( 2.98% of base) : 162324.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:EnqueueTypeToken(System.Collections.Generic.Queue`1[System.Reflection.Metadata.TypeDefinitionHandle],System.Collections.Generic.Queue`1[System.__Canon],System.Reflection.Metadata.EntityHandle):this
           5 ( 0.51% of base) : 17803.dasm - System.Data.Common.DataAdapter:Fill(System.Data.DataTable[],System.Data.IDataReader,int,int):int:this
           5 ( 0.46% of base) : 144595.dasm - System.Enum:TryParse(System.Type,System.ReadOnlySpan`1[System.Char],bool,bool,byref):bool
           5 ( 2.84% of base) : 94569.dasm - Microsoft.CodeAnalysis.VisualBasic.IteratorAndAsyncCaptureWalker:MarkLocalsUnassigned():this
           5 ( 0.28% of base) : 90899.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberContainerTypeSymbol:MakeExplicitInterfaceImplementationMap(Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Generic.Dictionary`2[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic.Symbol]:this

Top method improvements (bytes):
       -1333 (-10.61% of base) : 137351.dasm - System.Globalization.CultureData:get_RegionNames():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -287 (-9.52% of base) : 80715.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
        -252 (-7.77% of base) : 87675.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:TransformRewrittenBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
        -250 (-9.06% of base) : 10983.dasm - System.Text.GB18030Encoding:GetChars(long,int,long,int,System.Text.DecoderNLS):int:this
        -100 (-2.87% of base) : 87875.dasm - Microsoft.CodeAnalysis.VisualBasic.ExpressionLambdaRewriter:CreateBuiltInConversion(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,bool,bool,int,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -95 (-2.24% of base) : 86551.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
         -86 (-3.27% of base) : 86444.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanDateLiteral(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode]):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
         -82 (-3.55% of base) : 214491.dasm - System.Net.HttpKnownHeaderNames:TryGetHeaderName(System.__Canon,int,int,System.Func`3[System.__Canon, System.Int32, System.Char],System.Func`5[System.String, System.__Canon, System.Int32, System.Int32, System.Boolean],byref):bool
         -82 (-3.48% of base) : 214558.dasm - System.Net.HttpKnownHeaderNames:TryGetHeaderName(long,int,int,System.Func`3[System.IntPtr, System.Int32, System.Char],System.Func`5[System.String, System.IntPtr, System.Int32, System.Int32, System.Boolean],byref):bool
         -81 (-2.07% of base) : 147203.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[System.Int32],System.Collections.Immutable.ImmutableArray`1[System.Int32],System.Collections.Immutable.ImmutableArray`1[System.Int32],int,bool):this
         -78 (-3.04% of base) : 114415.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
         -73 (-1.66% of base) : 86447.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanNumericLiteral(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode]):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
         -64 (-7.13% of base) : 86563.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:EvaluateTernaryIfExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TernaryConditionalExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst:this
         -63 (-2.35% of base) : 111639.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Lexer:ScanSyntaxToken(byref):this
         -63 (-1.34% of base) : 94178.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,ushort,int,bool,Microsoft.CodeAnalysis.DiagnosticBag,bool,byref):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -62 (-6.29% of base) : 63062.dasm - System.Xml.Schema.SchemaCollectionCompiler:IsValidRestriction(System.Xml.Schema.XmlSchemaParticle,System.Xml.Schema.XmlSchemaParticle):bool:this
         -61 (-7.38% of base) : 137601.dasm - System.Globalization.CalendarData:IcuLoadCalendarDataFromSystem(System.String,ushort):bool:this
         -61 (-3.64% of base) : 114419.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:LineBreaksAfter(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):int:this
         -58 (-1.14% of base) : 141955.dasm - System.DateTimeParse:ParseByFormat(byref,byref,byref,System.Globalization.DateTimeFormatInfo,byref):bool
         -58 (-4.77% of base) : 14047.dasm - System.Text.Json.Serialization.JsonConverter`1:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):long:this

Top method regressions (percentages):
          45 (28.85% of base) : 196712.dasm - ElementAtQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          33 (18.54% of base) : 196552.dasm - WhereQueryOperatorEnumerator`1:MoveNext(byref,byref):bool:this
          33 (18.23% of base) : 196647.dasm - IndexedWhereQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          35 (17.24% of base) : 87779.dasm - Microsoft.CodeAnalysis.VisualBasic.LambdaRewriter:LowestCommonAncestor(Microsoft.CodeAnalysis.VisualBasic.BoundNode,Microsoft.CodeAnalysis.VisualBasic.BoundNode):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          30 (16.67% of base) : 186704.dasm - System.Threading.Tasks.Dataflow.Internal.ReorderingBuffer`1:OutputNextItem(System.__Canon,bool):this
          33 (16.34% of base) : 168184.dasm - System.IO.Compression.BrotliStream:Read(System.Span`1[System.Byte]):int:this
           1 ( 4.35% of base) : 206414.dasm - Microsoft.Extensions.DependencyModel.Utf8JsonReaderExtensions:IsTokenTypeProperty(byref):bool
          18 ( 3.54% of base) : 102912.dasm - <GetKeywordKinds>d__17:MoveNext():bool:this
           3 ( 3.41% of base) : 92945.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:get_IsReferenceType():bool:this
           1 ( 3.12% of base) : 104693.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbolExtensions:IsDelegateType(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):bool
           1 ( 3.12% of base) : 90977.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberContainerTypeSymbol:get_IsInterface():bool:this
           1 ( 3.12% of base) : 106646.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsUsing():bool:this
           1 ( 3.12% of base) : 106647.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsConst():bool:this
           1 ( 3.12% of base) : 106648.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsCatch():bool:this
           1 ( 3.12% of base) : 106643.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsForEach():bool:this
           1 ( 3.12% of base) : 106644.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsFor():bool:this
           1 ( 3.12% of base) : 106645.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol:get_IsFixed():bool:this
           1 ( 3.12% of base) : 104944.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SynthesizedContainer:get_IsInterface():bool:this
           1 ( 3.12% of base) : 107154.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:get_IsSubmissionClass():bool:this
           1 ( 3.12% of base) : 77402.dasm - Microsoft.CodeAnalysis.VisualBasic.Conversions:IsArrayType(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool

Top method improvements (percentages):
          -8 (-17.02% of base) : 1035.dasm - OperatorIntrinsics:current@5245-8(Microsoft.FSharp.Core.Operators+OperatorIntrinsics+VariableStepIntegralRangeState`1[System.SByte],Microsoft.FSharp.Core.Unit):byte
          -3 (-15.79% of base) : 144788.dasm - System.Decimal:op_Explicit(System.Decimal):byte
          -3 (-15.79% of base) : 9050.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToSByte(System.Object):byte:this
          -3 (-15.79% of base) : 7911.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToSByte(System.IFormatProvider):byte:this
          -3 (-15.00% of base) : 135978.dasm - System.Buffers.Text.FormattingHelpers:GetSymbolOrDefault(byref,ushort):ushort
          -7 (-14.89% of base) : 90865.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberMethodSymbol:get_IsExtensionMethod():bool:this
          -5 (-14.71% of base) : 23738.dasm - Microsoft.VisualBasic.CompilerServices.StringType:StrLike(System.String,System.String,int):bool
          -3 (-14.29% of base) : 141538.dasm - System.Int32:System.IConvertible.ToSByte(System.IFormatProvider):byte:this
          -8 (-14.04% of base) : 807.dasm - RangeSByte@5428-3:System.Collections.Generic.IEnumerator<System.SByte>.get_Current():byte:this
         -15 (-13.89% of base) : 140767.dasm - System.PasteArguments:ContainsNoWhitespaceOrQuotes(System.String):bool
          -5 (-13.89% of base) : 90585.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNamedTypeSymbol:MyGroupCollectionCandidateHasPublicParameterlessConstructor(Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNamedTypeSymbol):bool
          -5 (-13.89% of base) : 77736.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:MakeHalfWidth(ushort):ushort
          -5 (-13.89% of base) : 77737.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:MakeFullWidth(ushort):ushort
         -13 (-13.83% of base) : 140772.dasm - System.ParseNumbers:EatWhiteSpace(System.ReadOnlySpan`1[System.Char],byref)
         -18 (-13.74% of base) : 13209.dasm - System.Text.Json.Utf8JsonReader:Read():bool:this
          -6 (-13.64% of base) : 1039.dasm - OperatorIntrinsics:current@5245-7(Microsoft.FSharp.Core.Operators+OperatorIntrinsics+VariableStepIntegralRangeState`1[System.UInt16],Microsoft.FSharp.Core.Unit):ushort
          -6 (-13.64% of base) : 1031.dasm - OperatorIntrinsics:current@5245-9(Microsoft.FSharp.Core.Operators+OperatorIntrinsics+VariableStepIntegralRangeState`1[System.Byte],Microsoft.FSharp.Core.Unit):ubyte
          -3 (-13.64% of base) : 25253.dasm - Microsoft.CSharp.RuntimeBinder.Semantics.ConstVal:get_SByteVal():byte:this
          -3 (-13.64% of base) : 141461.dasm - System.Int64:System.IConvertible.ToSByte(System.IFormatProvider):byte:this
          -3 (-13.64% of base) : 11369.dasm - System.Text.Json.Serialization.Converters.SByteConverter:ReadAsPropertyNameCore(byref,System.Type,System.Text.Json.JsonSerializerOptions):byte:this

15246 total methods with Code Size differences (14777 improved, 469 regressed), 24253 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 5295032
Total bytes of diff: 5269530
Total bytes of delta: -25502 (-0.48% of base)
Total relative delta: -47.77
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          42 : 183915.dasm (2.48% of base)
          11 : 214794.dasm (0.67% of base)
           8 : 183916.dasm (0.36% of base)
           4 : 195.dasm (0.73% of base)
           3 : 153328.dasm (0.22% of base)
           2 : 137076.dasm (0.19% of base)
           2 : 29053.dasm (0.20% of base)
           2 : 155312.dasm (0.33% of base)
           2 : 155359.dasm (0.45% of base)
           2 : 155183.dasm (0.33% of base)
           1 : 142243.dasm (0.39% of base)
           1 : 142275.dasm (0.39% of base)
           1 : 155342.dasm (0.33% of base)
           1 : 155343.dasm (0.27% of base)
           1 : 155344.dasm (0.19% of base)
           1 : 155351.dasm (0.19% of base)
           1 : 154449.dasm (0.05% of base)
           1 : 155241.dasm (0.09% of base)
           1 : 209949.dasm (0.09% of base)

Top file improvements (bytes):
        -193 : 118289.dasm (-13.58% of base)
        -168 : 29399.dasm (-1.81% of base)
        -147 : 29405.dasm (-3.11% of base)
        -126 : 178112.dasm (-2.28% of base)
        -126 : 29400.dasm (-3.30% of base)
        -125 : 153279.dasm (-3.92% of base)
        -111 : 152219.dasm (-1.76% of base)
        -111 : 29401.dasm (-3.46% of base)
        -110 : 143532.dasm (-1.69% of base)
        -109 : 107817.dasm (-2.10% of base)
        -109 : 221354.dasm (-2.73% of base)
        -106 : 155693.dasm (-7.16% of base)
        -105 : 114750.dasm (-2.82% of base)
        -105 : 222063.dasm (-2.09% of base)
         -92 : 230286.dasm (-1.16% of base)
         -92 : 145879.dasm (-2.42% of base)
         -87 : 143023.dasm (-2.21% of base)
         -86 : 2787.dasm (-1.54% of base)
         -84 : 44919.dasm (-1.89% of base)
         -82 : 86232.dasm (-2.35% of base)

4501 total files with Code Size differences (4482 improved, 19 regressed), 1299 unchanged.

Top method regressions (bytes):
          42 ( 2.48% of base) : 183915.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfo(bool,QualifiedTableName,bool):int:this
          11 ( 0.67% of base) : 214794.dasm - System.Security.AccessControl.GenericAce:CreateFromBinaryForm(System.Byte[],int):System.Security.AccessControl.GenericAce
           8 ( 0.36% of base) : 183916.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfoFromStatistics(QualifiedTableName,bool):int:this
           4 ( 0.73% of base) : 195.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           3 ( 0.22% of base) : 153328.dasm - System.Text.SBCSCodePageEncoding:GetBytes(long,int,long,int,System.Text.EncoderNLS):int:this
           2 ( 0.19% of base) : 137076.dasm - AttributeValueCache:Trim():this
           2 ( 0.20% of base) : 29053.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MergeArgumentsAndSideEffects(Microsoft.CodeAnalysis.CSharp.BoundExpression[],Microsoft.CodeAnalysis.ArrayBuilder`1[RefKind],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundAssignmentOperator, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):int
           2 ( 0.33% of base) : 155312.dasm - System.Text.Json.Nodes.JsonObject:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonObject
           2 ( 0.45% of base) : 155359.dasm - System.Text.Json.Nodes.JsonValue:VerifyJsonElementIsNotArrayOrObject(byref)
           2 ( 0.33% of base) : 155183.dasm - System.Text.Json.Nodes.JsonArray:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonArray
           1 ( 0.39% of base) : 142243.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.39% of base) : 142275.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.33% of base) : 155342.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.27% of base) : 155343.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Nullable`1[JsonElement],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.19% of base) : 155344.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.19% of base) : 155351.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Text.Json.Serialization.Metadata.JsonTypeInfo`1[__Canon],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.05% of base) : 154449.dasm - System.Text.Json.JsonSerializer:TryGetReferenceFromJsonElement(byref,System.Text.Json.JsonElement,byref):bool
           1 ( 0.09% of base) : 155241.dasm - System.Text.Json.Nodes.JsonNode:ToString():System.String:this
           1 ( 0.09% of base) : 209949.dasm - System.Uri:CheckCanonical(long,byref,int,ushort):int:this

Top method improvements (bytes):
        -193 (-13.58% of base) : 118289.dasm - System.Drawing.SystemFonts:GetFontByName(System.String):System.Drawing.Font
        -168 (-1.81% of base) : 29399.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -147 (-3.11% of base) : 29405.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
        -126 (-2.28% of base) : 178112.dasm - System.ComponentModel.CategoryAttribute:GetLocalizedString(System.String):System.String:this
        -126 (-3.30% of base) : 29400.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetOperatorKind(System.String):ushort
        -125 (-3.92% of base) : 153279.dasm - System.Text.GB18030Encoding:GetChars(long,int,long,int,System.Text.DecoderNLS):int:this
        -111 (-1.76% of base) : 152219.dasm - System.Speech.Internal.SrgsParser.XmlParser:ParseGrammar(System.Xml.XmlReader,System.Speech.Internal.SrgsParser.IGrammar):this
        -111 (-3.46% of base) : 29401.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetPreprocessorKeywordKind(System.String):ushort
        -110 (-1.69% of base) : 143532.dasm - System.Xml.Xsl.Runtime.XmlCollation:Create(System.String,bool):System.Xml.Xsl.Runtime.XmlCollation
        -109 (-2.10% of base) : 107817.dasm - Newtonsoft.Json.Schema.JsonSchemaBuilder:ProcessSchemaProperties(Newtonsoft.Json.Linq.JObject):this
        -109 (-2.73% of base) : 221354.dasm - System.Security.Cryptography.Xml.CryptoHelpers:CreateFromKnownName(System.String):System.Object
        -106 (-7.16% of base) : 155693.dasm - System.Text.Json.Serialization.JsonConverter`1[Vector`1][System.Numerics.Vector`1[System.Single]]:ReadCore(byref,System.Text.Json.JsonSerializerOptions,byref):System.Numerics.Vector`1[Single]:this
        -105 (-2.82% of base) : 114750.dasm - System.Data.Common.DbColumn:get_Item(System.String):System.Object:this
        -105 (-2.09% of base) : 222063.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
         -92 (-1.16% of base) : 230286.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
         -92 (-2.42% of base) : 145879.dasm - System.Xml.Serialization.ReflectionXmlSerializationWriter:ConvertPrimitiveToString(System.Object,System.Xml.Serialization.TypeDesc):System.String:this
         -87 (-2.21% of base) : 143023.dasm - System.Xml.Xsl.XsltOld.XsltCompileContext:FunctionAvailable(System.String):bool:this
         -86 (-1.54% of base) : 2787.dasm - Microsoft.FSharp.Linq.QueryModule:TransNestedOuter(int,Microsoft.FSharp.Quotations.FSharpExpr):Microsoft.FSharp.Quotations.FSharpExpr
         -84 (-1.89% of base) : 44919.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
         -82 (-2.35% of base) : 86232.dasm - Microsoft.Diagnostics.Tracing.Parsers.ProviderManifest:GetTypeForManifestTypeName(System.String):System.Type

Top method regressions (percentages):
          42 ( 2.48% of base) : 183915.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfo(bool,QualifiedTableName,bool):int:this
           4 ( 0.73% of base) : 195.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
          11 ( 0.67% of base) : 214794.dasm - System.Security.AccessControl.GenericAce:CreateFromBinaryForm(System.Byte[],int):System.Security.AccessControl.GenericAce
           2 ( 0.45% of base) : 155359.dasm - System.Text.Json.Nodes.JsonValue:VerifyJsonElementIsNotArrayOrObject(byref)
           1 ( 0.39% of base) : 142243.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.39% of base) : 142275.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           8 ( 0.36% of base) : 183916.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfoFromStatistics(QualifiedTableName,bool):int:this
           2 ( 0.33% of base) : 155312.dasm - System.Text.Json.Nodes.JsonObject:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonObject
           2 ( 0.33% of base) : 155183.dasm - System.Text.Json.Nodes.JsonArray:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonArray
           1 ( 0.33% of base) : 155342.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.27% of base) : 155343.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Nullable`1[JsonElement],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           3 ( 0.22% of base) : 153328.dasm - System.Text.SBCSCodePageEncoding:GetBytes(long,int,long,int,System.Text.EncoderNLS):int:this
           2 ( 0.20% of base) : 29053.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MergeArgumentsAndSideEffects(Microsoft.CodeAnalysis.CSharp.BoundExpression[],Microsoft.CodeAnalysis.ArrayBuilder`1[RefKind],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundAssignmentOperator, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):int
           1 ( 0.19% of base) : 155344.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           2 ( 0.19% of base) : 137076.dasm - AttributeValueCache:Trim():this
           1 ( 0.19% of base) : 155351.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Text.Json.Serialization.Metadata.JsonTypeInfo`1[__Canon],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.09% of base) : 155241.dasm - System.Text.Json.Nodes.JsonNode:ToString():System.String:this
           1 ( 0.09% of base) : 209949.dasm - System.Uri:CheckCanonical(long,byref,int,ushort):int:this
           1 ( 0.05% of base) : 154449.dasm - System.Text.Json.JsonSerializer:TryGetReferenceFromJsonElement(byref,System.Text.Json.JsonElement,byref):bool

Top method improvements (percentages):
         -10 (-20.00% of base) : 103222.dasm - <>c:<ParseSymbolFile>b__23_0(ubyte):bool:this
        -193 (-13.58% of base) : 118289.dasm - System.Drawing.SystemFonts:GetFontByName(System.String):System.Drawing.Font
          -5 (-13.16% of base) : 183592.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
          -5 (-13.16% of base) : 185548.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
          -2 (-11.76% of base) : 219665.dasm - System.Security.Cryptography.HashAlgorithmName:op_Equality(System.Security.Cryptography.HashAlgorithmName,System.Security.Cryptography.HashAlgorithmName):bool
          -2 (-11.76% of base) : 186096.dasm - System.Diagnostics.ActivityTraceId:op_Equality(System.Diagnostics.ActivityTraceId,System.Diagnostics.ActivityTraceId):bool
          -2 (-11.76% of base) : 186114.dasm - System.Diagnostics.ActivitySpanId:op_Equality(System.Diagnostics.ActivitySpanId,System.Diagnostics.ActivitySpanId):bool
          -2 (-10.00% of base) : 219663.dasm - System.Security.Cryptography.HashAlgorithmName:Equals(System.Security.Cryptography.HashAlgorithmName):bool:this
          -2 (-10.00% of base) : 76794.dasm - Microsoft.CodeAnalysis.CommandLineAnalyzerReference:Equals(Microsoft.CodeAnalysis.CommandLineAnalyzerReference):bool:this
          -2 (-10.00% of base) : 134754.dasm - System.Xml.XmlCharType:GetCharProperties(ushort):int
          -2 (-10.00% of base) : 186098.dasm - System.Diagnostics.ActivityTraceId:Equals(System.Diagnostics.ActivityTraceId):bool:this
          -2 (-10.00% of base) : 186116.dasm - System.Diagnostics.ActivitySpanId:Equals(System.Diagnostics.ActivitySpanId):bool:this
          -2 (-10.00% of base) : 186680.dasm - System.Diagnostics.Metrics.StringSequence1:Equals(System.Diagnostics.Metrics.StringSequence1):bool:this
         -19 (-9.74% of base) : 156307.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[__Canon][System.__Canon]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -19 (-9.74% of base) : 156313.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[Byte][System.Byte]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -10 (-8.93% of base) : 183543.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
         -10 (-8.93% of base) : 185571.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
         -10 (-8.93% of base) : 114906.dasm - System.Data.Common.DbConnectionOptions:IsKeyNameValid(System.String):bool
          -3 (-8.82% of base) : 156358.dasm - System.Text.Json.Serialization.Converters.ByteConverter:WriteNumberWithCustomHandling(System.Text.Json.Utf8JsonWriter,ubyte,int):this
          -2 (-8.70% of base) : 213689.dasm - System.Runtime.InteropServices.OSPlatform:op_Equality(System.Runtime.InteropServices.OSPlatform,System.Runtime.InteropServices.OSPlatform):bool

4501 total methods with Code Size differences (4482 improved, 19 regressed), 1299 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 12194814
Total bytes of diff: 12124767
Total bytes of delta: -70047 (-0.57% of base)
Total relative delta: -160.80
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          19 : 184908.dasm (0.62% of base)
          19 : 305152.dasm (0.62% of base)
          19 : 64473.dasm (0.62% of base)
          18 : 146491.dasm (2.58% of base)
           9 : 313518.dasm (1.44% of base)
           9 : 313520.dasm (1.10% of base)
           9 : 313521.dasm (0.84% of base)
           4 : 195.dasm (0.73% of base)
           4 : 124328.dasm (0.33% of base)
           1 : 15506.dasm (0.05% of base)
           1 : 39994.dasm (0.31% of base)
           1 : 245711.dasm (0.14% of base)
           1 : 93629.dasm (0.06% of base)
           1 : 41752.dasm (0.31% of base)

Top file improvements (bytes):
        -240 : 310455.dasm (-2.08% of base)
        -171 : 152882.dasm (-5.19% of base)
        -160 : 75195.dasm (-1.61% of base)
        -144 : 151988.dasm (-1.71% of base)
        -140 : 125397.dasm (-12.05% of base)
        -138 : 68978.dasm (-2.16% of base)
        -126 : 10330.dasm (-3.25% of base)
        -125 : 345926.dasm (-2.70% of base)
        -125 : 341653.dasm (-2.62% of base)
        -123 : 257241.dasm (-1.75% of base)
        -122 : 6815.dasm (-3.19% of base)
        -119 : 130652.dasm (-1.18% of base)
        -118 : 177410.dasm (-1.22% of base)
        -117 : 12107.dasm (-2.90% of base)
        -114 : 340339.dasm (-2.60% of base)
        -114 : 340340.dasm (-2.60% of base)
        -108 : 151317.dasm (-4.85% of base)
        -102 : 156073.dasm (-4.28% of base)
         -93 : 130223.dasm (-2.77% of base)
         -92 : 125385.dasm (-12.35% of base)

13540 total files with Code Size differences (13526 improved, 14 regressed), 1347 unchanged.

Top method regressions (bytes):
          19 ( 0.62% of base) : 184908.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
          19 ( 0.62% of base) : 305152.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
          19 ( 0.62% of base) : 64473.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
          18 ( 2.58% of base) : 146491.dasm - TypeLoadNotifyingCatalog:CreateWrapped(System.ComponentModel.Composition.Primitives.ContractBasedImportDefinition,System.Type):System.ComponentModel.Composition.Primitives.ImportDefinition:this
           9 ( 1.44% of base) : 313518.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Receives_Correct_Arguments()
           9 ( 1.10% of base) : 313520.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Receives_Correct_Arguments()
           9 ( 0.84% of base) : 313521.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Via_Params_Receives_Correct_Arguments()
           4 ( 0.73% of base) : 195.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           4 ( 0.33% of base) : 124328.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpDeclarationComparer:GetAccessibilityPrecedence(Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxNode):int
           1 ( 0.05% of base) : 15506.dasm - AllLowerCamelCaseMatcher:TryMatch(int,int,System.Nullable`1[Boolean],byref):System.Nullable`1[CamelCaseResult]:this
           1 ( 0.31% of base) : 39994.dasm - System.Globalization.Tests.CultureInfoAll:GetTimeFormats(System.Globalization.CultureInfo,int):System.String[]:this
           1 ( 0.14% of base) : 245711.dasm - <RunSubmissionsAsync>d__21[Byte][System.Byte]:MoveNext():this
           1 ( 0.06% of base) : 93629.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestingGetBase64InvalidUTF8(System.Byte[])
           1 ( 0.31% of base) : 41752.dasm - System.Globalization.Tests.CultureInfoAll:GetTimeFormats(System.Globalization.CultureInfo,int):System.String[]:this

Top method improvements (bytes):
        -240 (-2.08% of base) : 310455.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4EqualsNanTest():this
        -171 (-5.19% of base) : 152882.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:Remove():this
        -160 (-1.61% of base) : 75195.dasm - <ToString_MatchesExpected_MemberData>d__105:MoveNext():bool:this
        -144 (-1.71% of base) : 151988.dasm - System.Data.Tests.DataTableTest4:XmlTest10():this
        -140 (-12.05% of base) : 125397.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -138 (-2.16% of base) : 68978.dasm - System.Tests.AttributeGetCustomAttributes:RunPosTests()
        -126 (-3.25% of base) : 10330.dasm - Microsoft.CodeAnalysis.Editing.SyntaxGenerator:GetOperatorKind(Microsoft.CodeAnalysis.IMethodSymbol):int
        -125 (-2.70% of base) : 345926.dasm - TCWriteState:InvokeMethod(System.Xml.XmlWriter,System.String):this
        -125 (-2.62% of base) : 341653.dasm - TCWriteState:InvokeMethod(System.Xml.XmlWriter,System.String):this
        -123 (-1.75% of base) : 257241.dasm - NuGet.Frameworks.NuGetFramework:TryParseCommonFramework(System.String,byref):bool
        -122 (-3.19% of base) : 6815.dasm - Microsoft.CodeAnalysis.Shared.Extensions.IMethodSymbolExtensions:GetPredefinedOperator(Microsoft.CodeAnalysis.IMethodSymbol):int
        -119 (-1.18% of base) : 130652.dasm - Microsoft.Diagnostics.Runtime.Desktop.LockInspection:SetThreadWaiters():this
        -118 (-1.22% of base) : 177410.dasm - System.Buffers.Text.Tests.FormatterTests:TryFormatUtf8(System.Object,System.Span`1[Byte],byref,System.Buffers.StandardFormat):bool
        -117 (-2.90% of base) : 12107.dasm - Microsoft.CodeAnalysis.Classification.Classifier:GetClassificationKind(System.String):System.Nullable`1[SymbolDisplayPartKind]
        -114 (-2.60% of base) : 340339.dasm - PropertiesTests:Explicit(System.Type,System.Xml.Linq.XAttribute):System.Object
        -114 (-2.60% of base) : 340340.dasm - PropertiesTests:Explicit(System.Type,System.Xml.Linq.XElement):System.Object
        -108 (-4.85% of base) : 151317.dasm - System.Data.Tests.DataRowTest2:HasVersion_ByDataRowVersion():this
        -102 (-4.28% of base) : 156073.dasm - System.ComponentModel.TypeConverterTests.IconConverterTest:TestCanConvertTo():this
         -93 (-2.77% of base) : 130223.dasm - Microsoft.Diagnostics.Runtime.Desktop.DesktopGCHeap:InitBasicTypes():this
         -92 (-12.35% of base) : 125385.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this

Top method regressions (percentages):
          18 ( 2.58% of base) : 146491.dasm - TypeLoadNotifyingCatalog:CreateWrapped(System.ComponentModel.Composition.Primitives.ContractBasedImportDefinition,System.Type):System.ComponentModel.Composition.Primitives.ImportDefinition:this
           9 ( 1.44% of base) : 313518.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Receives_Correct_Arguments()
           9 ( 1.10% of base) : 313520.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Receives_Correct_Arguments()
           9 ( 0.84% of base) : 313521.dasm - DispatchProxyTests.DispatchProxyTests:Invoke_Multiple_Parameters_Via_Params_Receives_Correct_Arguments()
           4 ( 0.73% of base) : 195.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
          19 ( 0.62% of base) : 184908.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
          19 ( 0.62% of base) : 305152.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
          19 ( 0.62% of base) : 64473.dasm - <AcceptHttpsClientAsync>d__13:MoveNext():this
           4 ( 0.33% of base) : 124328.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpDeclarationComparer:GetAccessibilityPrecedence(Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxNode):int
           1 ( 0.31% of base) : 39994.dasm - System.Globalization.Tests.CultureInfoAll:GetTimeFormats(System.Globalization.CultureInfo,int):System.String[]:this
           1 ( 0.31% of base) : 41752.dasm - System.Globalization.Tests.CultureInfoAll:GetTimeFormats(System.Globalization.CultureInfo,int):System.String[]:this
           1 ( 0.14% of base) : 245711.dasm - <RunSubmissionsAsync>d__21[Byte][System.Byte]:MoveNext():this
           1 ( 0.06% of base) : 93629.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestingGetBase64InvalidUTF8(System.Byte[])
           1 ( 0.05% of base) : 15506.dasm - AllLowerCamelCaseMatcher:TryMatch(int,int,System.Nullable`1[Boolean],byref):System.Nullable`1[CamelCaseResult]:this

Top method improvements (percentages):
         -11 (-15.28% of base) : 127209.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.VisualBasicTriviaFormatter:IsWhitespace(ushort):bool:this
          -5 (-13.16% of base) : 216945.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
          -5 (-13.16% of base) : 221305.dasm - System.Data.Common.MultipartIdentifier:IsWhitespace(ushort):bool
         -31 (-12.65% of base) : 114581.dasm - Microsoft.Build.Shared.LanguageParser.VisualBasicTokenCharReader:SinkSeparatorCharacter():bool:this
         -92 (-12.35% of base) : 125385.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -140 (-12.05% of base) : 125397.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -2 (-11.76% of base) : 241969.dasm - Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection:op_Equality(Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection,Microsoft.AspNetCore.Http.Internal.HeaderSegmentCollection):bool
          -3 (-11.54% of base) : 331580.dasm - <>c:<WideToAsciiStr>b__9_0(ushort):ubyte:this
         -12 (-10.62% of base) : 114586.dasm - Microsoft.Build.Shared.LanguageParser.VisualBasicTokenCharReader:SinkWhiteSpace():bool:this
         -24 (-10.48% of base) : 114570.dasm - Microsoft.Build.Shared.LanguageParser.CSharpTokenCharReader:SinkLongIntegerSuffix():bool:this
         -14 (-10.45% of base) : 125418.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -2 (-10.00% of base) : 278187.dasm - System.Diagnostics.Metrics.StringSequence1:Equals(System.Diagnostics.Metrics.StringSequence1):bool:this
          -2 (-10.00% of base) : 2311.dasm - Microsoft.CodeAnalysis.SymbolKey:Equals(Microsoft.CodeAnalysis.SymbolKey):bool:this
          -2 (-10.00% of base) : 2443.dasm - Microsoft.CodeAnalysis.CompilationOutputInfo:Equals(Microsoft.CodeAnalysis.CompilationOutputInfo):bool:this
         -26 (-9.67% of base) : 125373.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -6 (-9.52% of base) : 2304.dasm - Microsoft.CodeAnalysis.SymbolKey:Equals(Microsoft.CodeAnalysis.Compilation,System.String,System.String):bool
          -8 (-9.20% of base) : 125379.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -8 (-9.20% of base) : 125391.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -8 (-9.20% of base) : 125412.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
          -3 (-9.09% of base) : 125292.dasm - <>c:<.cctor>b__161_0(System.String):Microsoft.CodeAnalysis.Optional`1[Boolean]:this

13540 total methods with Code Size differences (13526 improved, 14 regressed), 1347 unchanged.

```

</details>

--------------------------------------------------------------------------------

