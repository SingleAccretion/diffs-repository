## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 686725
Total bytes of diff: 683106
Total bytes of delta: -3619 (-0.53% of base)
Total relative delta: -11.52
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         122 : 7822.dasm (7.70% of base)
          27 : 5553.dasm (5.66% of base)
          24 : 9984.dasm (3.12% of base)
          21 : 57.dasm (4.28% of base)
           3 : 1011.dasm (1.50% of base)

Top file improvements (bytes):
        -198 : 15266.dasm (-2.38% of base)
        -102 : 15324.dasm (-2.68% of base)
         -88 : 16168.dasm (-2.50% of base)
         -78 : 17781.dasm (-1.88% of base)
         -73 : 3516.dasm (-1.48% of base)
         -41 : 5675.dasm (-14.09% of base)
         -40 : 1838.dasm (-1.09% of base)
         -36 : 12727.dasm (-0.33% of base)
         -34 : 15332.dasm (-1.17% of base)
         -34 : 6782.dasm (-2.61% of base)
         -33 : 8429.dasm (-1.41% of base)
         -33 : 3597.dasm (-1.71% of base)
         -33 : 7794.dasm (-1.27% of base)
         -33 : 5109.dasm (-13.20% of base)
         -29 : 569.dasm (-8.24% of base)
         -28 : 11298.dasm (-2.29% of base)
         -25 : 4835.dasm (-46.30% of base)
         -24 : 2097.dasm (-0.71% of base)
         -24 : 6318.dasm (-0.88% of base)
         -24 : 8283.dasm (-1.39% of base)

643 total files with Code Size differences (638 improved, 5 regressed), 145 unchanged.

Top method regressions (bytes):
         122 ( 7.70% of base) : 7822.dasm - CriticalHelper:WriteMembers(System.Runtime.Serialization.ClassDataContract,System.Reflection.Emit.LocalBuilder,System.Runtime.Serialization.ClassDataContract):int:this
          27 ( 5.66% of base) : 5553.dasm - System.Text.ASCIIEncoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          24 ( 3.12% of base) : 9984.dasm - System.Drawing.Imaging.ImageCodecInfo:ConvertFromMemory(int,int):System.Drawing.Imaging.ImageCodecInfo[]
          21 ( 4.28% of base) : 57.dasm - System.Text.UTF8Encoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
           3 ( 1.50% of base) : 1011.dasm - System.Resources.ResourceReader:.ctor(System.IO.Stream,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Resources.ResourceLocator, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool):this

Top method improvements (bytes):
        -198 (-2.38% of base) : 15266.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -102 (-2.68% of base) : 15324.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
         -88 (-2.50% of base) : 16168.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
         -78 (-1.88% of base) : 17781.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
         -73 (-1.48% of base) : 3516.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WritePrimitive(System.Xml.Serialization.TypeMapping,System.String):this
         -41 (-14.09% of base) : 5675.dasm - System.Net.Sockets.SocketAsyncEventArgs:FreePinHandles():this
         -40 (-1.09% of base) : 1838.dasm - System.Globalization.DateTimeFormatInfo:CreateTokenHashTable():System.Globalization.DateTimeFormatInfo+TokenHashValue[]:this
         -36 (-0.33% of base) : 12727.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
         -34 (-1.17% of base) : 15332.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Lexer:ScanNumericLiteral(byref):bool:this
         -34 (-2.61% of base) : 6782.dasm - System.Text.Json.Reflection.ReflectionExtensions:IsImmutableEnumerableType(System.Type,bool):bool
         -33 (-1.41% of base) : 8429.dasm - System.Xml.XmlBaseWriter:StartAttribute(byref,System.String,System.String,System.Xml.XmlDictionaryString):this
         -33 (-1.71% of base) : 3597.dasm - System.Xml.XmlWellFormedWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -33 (-1.27% of base) : 7794.dasm - System.Runtime.Serialization.Json.XmlJsonWriter:WriteStartAttribute(System.String,System.String,System.String):this
         -33 (-13.20% of base) : 5109.dasm - System.IO.RandomAccess:CleanupScatterGatherBuffers(System.Buffers.MemoryHandle[],int)
         -29 (-8.24% of base) : 569.dasm - System.String:Concat(System.String[]):System.String
         -28 (-2.29% of base) : 11298.dasm - System.Xml.Linq.XAttribute:ValidateAttribute(System.Xml.Linq.XName,System.String)
         -25 (-46.30% of base) : 4835.dasm - System.Runtime.InteropServices.GCHandle:Free():this
         -24 (-0.71% of base) : 2097.dasm - System.Text.RegularExpressions.RegexNode:CanBeMadeAtomic(System.Text.RegularExpressions.RegexNode,System.Text.RegularExpressions.RegexNode,int):bool
         -24 (-0.88% of base) : 6318.dasm - System.Reflection.Metadata.MetadataReader:InitializeStreamReaders(byref,System.Reflection.Metadata.Ecma335.StreamHeader[],byref,byref,byref):this
         -24 (-1.39% of base) : 8283.dasm - NamespaceManager:AddNamespace(System.String,System.String,System.Xml.XmlDictionaryString):this

Top method regressions (percentages):
         122 ( 7.70% of base) : 7822.dasm - CriticalHelper:WriteMembers(System.Runtime.Serialization.ClassDataContract,System.Reflection.Emit.LocalBuilder,System.Runtime.Serialization.ClassDataContract):int:this
          27 ( 5.66% of base) : 5553.dasm - System.Text.ASCIIEncoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          21 ( 4.28% of base) : 57.dasm - System.Text.UTF8Encoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          24 ( 3.12% of base) : 9984.dasm - System.Drawing.Imaging.ImageCodecInfo:ConvertFromMemory(int,int):System.Drawing.Imaging.ImageCodecInfo[]
           3 ( 1.50% of base) : 1011.dasm - System.Resources.ResourceReader:.ctor(System.IO.Stream,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Resources.ResourceLocator, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool):this

Top method improvements (percentages):
         -25 (-46.30% of base) : 4835.dasm - System.Runtime.InteropServices.GCHandle:Free():this
          -3 (-33.33% of base) : 2949.dasm - System.Reflection.PropertyInfo:Equals(System.Object):bool:this
          -3 (-33.33% of base) : 2848.dasm - System.Reflection.ConstructorInfo:Equals(System.Object):bool:this
          -3 (-25.00% of base) : 661.dasm - <>c:<FillAllCharacteristicsCore>b__13_1(BenchmarkDotNet.Characteristics.Characteristic):bool:this
          -3 (-17.65% of base) : 15977.dasm - Roslyn.Utilities.StringOrdinalComparer:System.Collections.Generic.IEqualityComparer<System.String>.Equals(System.String,System.String):bool:this
          -3 (-15.79% of base) : 11403.dasm - <>c__DisplayClass25_0:<TryBuildImmutableForDictionaryContract>b__0(ImmutableCollectionTypeInfo):bool:this
          -3 (-15.79% of base) : 11412.dasm - <>c__DisplayClass24_0:<TryBuildImmutableForArrayContract>b__0(ImmutableCollectionTypeInfo):bool:this
         -41 (-14.09% of base) : 5675.dasm - System.Net.Sockets.SocketAsyncEventArgs:FreePinHandles():this
         -33 (-13.20% of base) : 5109.dasm - System.IO.RandomAccess:CleanupScatterGatherBuffers(System.Buffers.MemoryHandle[],int)
          -3 (-12.50% of base) : 17666.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol:Microsoft.Cci.ISignature.get_ReturnValueIsByRef():bool:this
         -19 (-10.67% of base) : 11252.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[LargeStructWithProperties][MicroBenchmarks.Serializers.LargeStructWithProperties]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -19 (-10.67% of base) : 11255.dasm - System.Text.Json.Serialization.Converters.ObjectDefaultConverter`1[__Canon][System.__Canon]:ReadAheadPropertyValue(byref,byref,System.Text.Json.Serialization.Metadata.JsonPropertyInfo):bool
         -12 (-10.26% of base) : 15901.dasm - Microsoft.CodeAnalysis.MetadataHelpers:GetAssemblyOrModuleNameErrorArgumentResourceName(System.String):System.String
          -3 (-9.68% of base) : 19472.dasm - System.Security.Cryptography.HMACSHA256:TryHashFinal(System.Span`1[Byte],byref):bool:this
          -3 (-9.68% of base) : 9306.dasm - <>c__DisplayClass83_0[__Canon][System.__Canon]:<CastClass>b__1(Sigil.Impl.TypeOnStack):bool:this
         -21 (-9.42% of base) : 1834.dasm - System.__DTString:SkipWhiteSpaceCurrent():bool:this
          -3 (-9.38% of base) : 9143.dasm - <>c__DisplayClass2_0:<GetMethod>b__0(System.Reflection.MethodInfo):bool:this
          -3 (-8.33% of base) : 2821.dasm - Newtonsoft.Json.Converters.EntityKeyMemberConverter:CanConvert(System.Type):bool:this
          -3 (-8.33% of base) : 20768.dasm - System.Tests.Perf_Guid:EqualsSame():bool:this
         -29 (-8.24% of base) : 569.dasm - System.String:Concat(System.String[]):System.String

643 total methods with Code Size differences (638 improved, 5 regressed), 145 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1689696
Total bytes of diff: 1673678
Total bytes of delta: -16018 (-0.95% of base)
Total relative delta: -56.66
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           1 : 86026.dasm (0.16% of base)

Top file improvements (bytes):
       -1397 : 215296.dasm (-43.22% of base)
        -397 : 215294.dasm (-19.98% of base)
        -126 : 209580.dasm (-0.60% of base)
        -112 : 164966.dasm (-0.64% of base)
        -105 : 183964.dasm (-2.36% of base)
         -99 : 220084.dasm (-2.57% of base)
         -93 : 205891.dasm (-22.04% of base)
         -93 : 205916.dasm (-22.04% of base)
         -89 : 226594.dasm (-3.30% of base)
         -77 : 214636.dasm (-1.21% of base)
         -77 : 206858.dasm (-1.21% of base)
         -77 : 206861.dasm (-1.28% of base)
         -77 : 206870.dasm (-1.28% of base)
         -77 : 206874.dasm (-1.28% of base)
         -77 : 206921.dasm (-1.28% of base)
         -63 : 202639.dasm (-1.63% of base)
         -61 : 205892.dasm (-10.55% of base)
         -61 : 205917.dasm (-10.55% of base)
         -61 : 226597.dasm (-8.24% of base)
         -58 : 231887.dasm (-6.17% of base)

2414 total files with Code Size differences (2413 improved, 1 regressed), 199 unchanged.

Top method regressions (bytes):
           1 ( 0.16% of base) : 86026.dasm - DevDiv_544985:Test(int,int,int,short,short,short):int

Top method improvements (bytes):
       -1397 (-43.22% of base) : 215296.dasm - GCHandleTest:GetTargetTest():this
        -397 (-19.98% of base) : 215294.dasm - GCHandleTest:FreeTest():this
        -126 (-0.60% of base) : 209580.dasm - ILGEN_0x372a9ae6:Method_0xdc6ff1a4(byte,byte,int,int,ushort,double,long,long):int
        -112 (-0.64% of base) : 164966.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
        -105 (-2.36% of base) : 183964.dasm - TailcallVerify.Program:Run(System.String):int
         -99 (-2.57% of base) : 220084.dasm - Test:bar(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String):int
         -93 (-22.04% of base) : 205891.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
         -93 (-22.04% of base) : 205916.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
         -89 (-3.30% of base) : 226594.dasm - LOHPin.LOHPin:Main(System.String[]):int
         -77 (-1.21% of base) : 214636.dasm - Test:Main():int
         -77 (-1.21% of base) : 206858.dasm - Test:Main():int
         -77 (-1.28% of base) : 206861.dasm - Test:Main():int
         -77 (-1.28% of base) : 206870.dasm - Test:Main():int
         -77 (-1.28% of base) : 206874.dasm - Test:Main():int
         -77 (-1.28% of base) : 206921.dasm - Test:Main():int
         -63 (-1.63% of base) : 202639.dasm - BenchmarkConsoleApplication.BenchmarkSystem:ProcessCommandLine(System.String[]):this
         -61 (-10.55% of base) : 205892.dasm - PartialCompactionTest.PartialCompactionTest:RemoveObjects(System.Collections.Generic.List`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
         -61 (-10.55% of base) : 205917.dasm - PartialCompactionTest.PartialCompactionTest:RemoveObjects(System.Collections.Generic.List`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
         -61 (-8.24% of base) : 226597.dasm - request:Main(System.String[]):int
         -58 (-6.17% of base) : 231887.dasm - DefaultNamespace.RootMem:Main(System.String[]):int

Top method regressions (percentages):
           1 ( 0.16% of base) : 86026.dasm - DevDiv_544985:Test(int,int,int,short,short,short):int

Top method improvements (percentages):
         -25 (-52.08% of base) : 231825.dasm - GCUtil:GetTarget(System.Runtime.InteropServices.GCHandle):System.Object
       -1397 (-43.22% of base) : 215296.dasm - GCHandleTest:GetTargetTest():this
          -3 (-23.08% of base) : 87385.dasm - Program:Test_ldind_u1_conv_u2(byref,byref)
          -3 (-23.08% of base) : 87387.dasm - Program:Test_ldind_u1_conv_ovf_u2(byref,byref)
          -3 (-23.08% of base) : 87390.dasm - Program:Test_ldind_u1_conv_ovf_u2_un(byref,byref)
         -10 (-22.73% of base) : 85992.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
         -93 (-22.04% of base) : 205891.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
         -93 (-22.04% of base) : 205916.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
          -9 (-21.43% of base) : 223579.dasm - Tests:CompareAgainstLong(System.Int32[])
         -25 (-20.33% of base) : 226762.dasm - DefaultNamespace.NDPinFinal:Finalize():this
        -397 (-19.98% of base) : 215294.dasm - GCHandleTest:FreeTest():this
         -56 (-19.93% of base) : 205895.dasm - PartialCompactionTest.PartialCompactionTest:CleanupWeakReferenceArr()
         -56 (-19.93% of base) : 205920.dasm - PartialCompactionTest.PartialCompactionTest:CleanupWeakReferenceArr()
         -27 (-19.71% of base) : 228206.dasm - MyProgram:TestStruct3():int
          -3 (-18.75% of base) : 148552.dasm - testout1:Func_0_1_4_1_4():ushort
          -3 (-18.75% of base) : 151190.dasm - testout1:Func_0_1_4_1_4():ushort
         -53 (-18.21% of base) : 205922.dasm - PartialCompactionTest.PartialCompactionTest:AddRefFrom(System.Object)
         -53 (-18.21% of base) : 205923.dasm - PartialCompactionTest.PartialCompactionTest:AddRefTo(System.Object)
         -53 (-18.21% of base) : 205900.dasm - PartialCompactionTest.PartialCompactionTest:AddRefFrom(System.Object)
         -53 (-18.21% of base) : 205901.dasm - PartialCompactionTest.PartialCompactionTest:AddRefTo(System.Object)

2414 total methods with Code Size differences (2413 improved, 1 regressed), 199 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 12747949
Total bytes of diff: 12686142
Total bytes of delta: -61807 (-0.48% of base)
Total relative delta: -847.91
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         122 : 123248.dasm (7.56% of base)
          32 : 169516.dasm (4.16% of base)
          31 : 117327.dasm (6.62% of base)
          29 : 118586.dasm (5.95% of base)
          28 : 111343.dasm (6.64% of base)
          28 : 117318.dasm (6.64% of base)
          28 : 186348.dasm (17.72% of base)
          28 : 186443.dasm (17.39% of base)
          28 : 186508.dasm (20.14% of base)
          27 : 58657.dasm (5.36% of base)
          27 : 58659.dasm (5.09% of base)
          27 : 59014.dasm (5.09% of base)
          27 : 59015.dasm (5.36% of base)
          27 : 45089.dasm (2.06% of base)
          26 : 117123.dasm (5.91% of base)
          24 : 44771.dasm (3.27% of base)
          22 : 116792.dasm (6.59% of base)
          22 : 117194.dasm (6.38% of base)
          21 : 58383.dasm (3.86% of base)
          21 : 58384.dasm (4.05% of base)

Top file improvements (bytes):
       -1064 : 62728.dasm (-10.38% of base)
        -244 : 143306.dasm (-10.09% of base)
        -189 : 150042.dasm (-7.62% of base)
        -112 : 12725.dasm (-3.93% of base)
         -95 : 573.dasm (-17.18% of base)
         -93 : 148919.dasm (-1.82% of base)
         -81 : 75314.dasm (-2.20% of base)
         -78 : 150240.dasm (-2.40% of base)
         -78 : 61612.dasm (-2.91% of base)
         -76 : 140090.dasm (-18.05% of base)
         -75 : 110719.dasm (-3.55% of base)
         -69 : 148815.dasm (-1.53% of base)
         -69 : 107943.dasm (-2.83% of base)
         -67 : 148812.dasm (-3.42% of base)
         -62 : 61613.dasm (-2.25% of base)
         -60 : 211039.dasm (-3.01% of base)
         -60 : 211107.dasm (-3.01% of base)
         -58 : 67323.dasm (-1.26% of base)
         -56 : 204667.dasm (-2.02% of base)
         -54 : 156459.dasm (-1.30% of base)

15414 total files with Code Size differences (14894 improved, 520 regressed), 24073 unchanged.

Top method regressions (bytes):
         122 ( 7.56% of base) : 123248.dasm - CriticalHelper:WriteMembers(System.Runtime.Serialization.ClassDataContract,System.Reflection.Emit.LocalBuilder,System.Runtime.Serialization.ClassDataContract):int:this
          32 ( 4.16% of base) : 169516.dasm - ILCompiler.Reflection.ReadyToRun.ReadyToRunReader:EnsureHeader():this
          31 ( 6.62% of base) : 117327.dasm - Microsoft.CodeAnalysis.CSharp.BoundIndexerAccess:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.PropertySymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],bool,System.Collections.Immutable.ImmutableArray`1[System.Int32],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundIndexerAccess:this
          29 ( 5.95% of base) : 118586.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindSimpleBinaryOperator(Microsoft.CodeAnalysis.CSharp.Syntax.BinaryExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          28 ( 6.64% of base) : 111343.dasm - Microsoft.CodeAnalysis.CSharp.BoundDynamicInvocation:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundDynamicInvocation:this
          28 ( 6.64% of base) : 117318.dasm - Microsoft.CodeAnalysis.CSharp.BoundDynamicIndexerAccess:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbols.PropertySymbol],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundDynamicIndexerAccess:this
          28 (17.72% of base) : 186348.dasm - WhereQueryOperatorEnumerator`1:MoveNext(byref,byref):bool:this
          28 (17.39% of base) : 186443.dasm - IndexedWhereQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          28 (20.14% of base) : 186508.dasm - ElementAtQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          27 ( 5.36% of base) : 58657.dasm - System.Text.Latin1Encoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          27 ( 5.09% of base) : 58659.dasm - System.Text.Latin1Encoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this
          27 ( 5.09% of base) : 59014.dasm - System.Text.ASCIIEncoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this
          27 ( 5.36% of base) : 59015.dasm - System.Text.ASCIIEncoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          27 ( 2.06% of base) : 45089.dasm - System.Drawing.Printing.PrinterSettings:Get_PaperSizes():System.Drawing.Printing.PaperSize[]:this
          26 ( 5.91% of base) : 117123.dasm - Microsoft.CodeAnalysis.CSharp.BoundObjectInitializerMember:Update(Microsoft.CodeAnalysis.CSharp.Symbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],bool,System.Collections.Immutable.ImmutableArray`1[System.Int32],ubyte,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundObjectInitializerMember:this
          24 ( 3.27% of base) : 44771.dasm - System.Drawing.Imaging.ImageCodecInfo:ConvertFromMemory(int,int):System.Drawing.Imaging.ImageCodecInfo[]
          22 ( 6.59% of base) : 116792.dasm - Microsoft.CodeAnalysis.CSharp.BoundBadExpression:Update(ubyte,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbol],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundNode],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundBadExpression:this
          22 ( 6.38% of base) : 117194.dasm - Microsoft.CodeAnalysis.CSharp.BoundAnonymousObjectCreationExpression:Update(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundAnonymousPropertyDeclaration],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundAnonymousObjectCreationExpression:this
          21 ( 3.86% of base) : 58383.dasm - System.Text.UTF8Encoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this
          21 ( 4.05% of base) : 58384.dasm - System.Text.UTF8Encoding:GetBytes(System.String,int,int,System.Byte[],int):int:this

Top method improvements (bytes):
       -1064 (-10.38% of base) : 62728.dasm - System.Globalization.CultureData:get_RegionNames():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -244 (-10.09% of base) : 143306.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
        -189 (-7.62% of base) : 150042.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:TransformRewrittenBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
        -112 (-3.93% of base) : 12725.dasm - System.Text.GB18030Encoding:GetChars(int,int,int,int,System.Text.DecoderNLS):int:this
         -95 (-17.18% of base) : 573.dasm - System.Net.Http.Headers.HeaderUtilities:Encode5987(System.String):System.String
         -93 (-1.82% of base) : 148919.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
         -81 (-2.20% of base) : 75314.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[System.Int32],System.Collections.Immutable.ImmutableArray`1[System.Int32],System.Collections.Immutable.ImmutableArray`1[System.Int32],int,bool):this
         -78 (-2.40% of base) : 150240.dasm - Microsoft.CodeAnalysis.VisualBasic.ExpressionLambdaRewriter:CreateBuiltInConversion(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,bool,bool,int,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -78 (-2.91% of base) : 61612.dasm - System.Globalization.TimeSpanParse:ProcessTerminal_HM_S_D(byref,ubyte,byref):bool
         -76 (-18.05% of base) : 140090.dasm - Microsoft.CodeAnalysis.VisualBasic.CompileTimeCalculations:GetConstantValueAsInt64(byref):long
         -75 (-3.55% of base) : 110719.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
         -69 (-1.53% of base) : 148815.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanNumericLiteral(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode]):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
         -69 (-2.83% of base) : 107943.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Lexer:ScanSyntaxToken(byref):this
         -67 (-3.42% of base) : 148812.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanDateLiteral(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode]):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
         -62 (-2.25% of base) : 61613.dasm - System.Globalization.TimeSpanParse:ProcessTerminal_HMS_F_D(byref,ubyte,byref):bool
         -60 (-3.01% of base) : 211039.dasm - System.Net.HttpKnownHeaderNames:TryGetHeaderName(System.__Canon,int,int,System.Func`3[System.__Canon, System.Int32, System.Char],System.Func`5[System.String, System.__Canon, System.Int32, System.Int32, System.Boolean],byref):bool
         -60 (-3.01% of base) : 211107.dasm - System.Net.HttpKnownHeaderNames:TryGetHeaderName(int,int,int,System.Func`3[System.IntPtr, System.Int32, System.Char],System.Func`5[System.String, System.IntPtr, System.Int32, System.Int32, System.Boolean],byref):bool
         -58 (-1.26% of base) : 67323.dasm - System.DateTimeParse:ParseByFormat(byref,byref,byref,System.Globalization.DateTimeFormatInfo,byref):bool
         -56 (-2.02% of base) : 204667.dasm - <UploadBitsAsync>d__152:MoveNext():this
         -54 (-1.30% of base) : 156459.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,ushort,int,bool,Microsoft.CodeAnalysis.DiagnosticBag,bool,byref):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method regressions (percentages):
          28 (20.14% of base) : 186508.dasm - ElementAtQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
          28 (17.72% of base) : 186348.dasm - WhereQueryOperatorEnumerator`1:MoveNext(byref,byref):bool:this
          28 (17.39% of base) : 186443.dasm - IndexedWhereQueryOperatorEnumerator:MoveNext(byref,byref):bool:this
         122 ( 7.56% of base) : 123248.dasm - CriticalHelper:WriteMembers(System.Runtime.Serialization.ClassDataContract,System.Reflection.Emit.LocalBuilder,System.Runtime.Serialization.ClassDataContract):int:this
          19 ( 6.79% of base) : 111508.dasm - Microsoft.CodeAnalysis.CSharp.BoundArrayAccess:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundArrayAccess:this
           1 ( 6.67% of base) : 205504.dasm - Microsoft.Extensions.DependencyModel.Utf8JsonReaderExtensions:IsTokenTypeProperty(byref):bool
          28 ( 6.64% of base) : 111343.dasm - Microsoft.CodeAnalysis.CSharp.BoundDynamicInvocation:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundDynamicInvocation:this
          28 ( 6.64% of base) : 117318.dasm - Microsoft.CodeAnalysis.CSharp.BoundDynamicIndexerAccess:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbols.PropertySymbol],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundDynamicIndexerAccess:this
          31 ( 6.62% of base) : 117327.dasm - Microsoft.CodeAnalysis.CSharp.BoundIndexerAccess:Update(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.PropertySymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],bool,System.Collections.Immutable.ImmutableArray`1[System.Int32],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundIndexerAccess:this
          22 ( 6.59% of base) : 116792.dasm - Microsoft.CodeAnalysis.CSharp.BoundBadExpression:Update(ubyte,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.Symbol],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundNode],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundBadExpression:this
          22 ( 6.38% of base) : 117194.dasm - Microsoft.CodeAnalysis.CSharp.BoundAnonymousObjectCreationExpression:Update(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundAnonymousPropertyDeclaration],Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundAnonymousObjectCreationExpression:this
          29 ( 5.95% of base) : 118586.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindSimpleBinaryOperator(Microsoft.CodeAnalysis.CSharp.Syntax.BinaryExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          26 ( 5.91% of base) : 117123.dasm - Microsoft.CodeAnalysis.CSharp.BoundObjectInitializerMember:Update(Microsoft.CodeAnalysis.CSharp.Symbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.RefKind],bool,System.Collections.Immutable.ImmutableArray`1[System.Int32],ubyte,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundObjectInitializerMember:this
          20 ( 5.39% of base) : 117109.dasm - Microsoft.CodeAnalysis.CSharp.BoundCollectionElementInitializer:Update(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],bool,System.Collections.Immutable.ImmutableArray`1[System.Int32],bool,ubyte,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundCollectionElementInitializer:this
           3 ( 5.36% of base) : 155234.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:get_IsReferenceType():bool:this
          27 ( 5.36% of base) : 58657.dasm - System.Text.Latin1Encoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          27 ( 5.36% of base) : 59015.dasm - System.Text.ASCIIEncoding:GetBytes(System.String,int,int,System.Byte[],int):int:this
          27 ( 5.09% of base) : 58659.dasm - System.Text.Latin1Encoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this
          27 ( 5.09% of base) : 59014.dasm - System.Text.ASCIIEncoding:GetBytes(System.Char[],int,int,System.Byte[],int):int:this
          20 ( 4.84% of base) : 117167.dasm - Microsoft.CodeAnalysis.CSharp.BoundAttribute:Update(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],ubyte,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundAttribute:this

Top method improvements (percentages):
         -27 (-81.82% of base) : 57506.dasm - System.Runtime.InteropServices.GCHandle:GetHandleValue(int):int
         -26 (-49.06% of base) : 57518.dasm - System.Runtime.InteropServices.GCHandle:get_Target():System.Object:this
         -26 (-45.61% of base) : 57519.dasm - System.Runtime.InteropServices.GCHandle:Free():this
         -26 (-34.67% of base) : 57810.dasm - System.Runtime.Loader.AssemblyLoadContext:Resolve(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -26 (-34.67% of base) : 57867.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUsingResolvingEvent(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -26 (-34.67% of base) : 57870.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveSatelliteAssembly(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -26 (-33.77% of base) : 57869.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUnmanagedDll(System.String,int):int
         -26 (-30.59% of base) : 57868.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUnmanagedDllUsingEvent(System.String,System.Reflection.Assembly,int):int
          -3 (-30.00% of base) : 103286.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:get_IsManagedType():bool:this
          -3 (-30.00% of base) : 176389.dasm - System.Collections.Concurrent.ConcurrentStack`1:System.Collections.Concurrent.IProducerConsumerCollection<T>.TryTake(byref):bool:this
          -3 (-30.00% of base) : 19187.dasm - Blobs:MoveNext():bool:this
          -3 (-30.00% of base) : 191992.dasm - System.Security.AccessControl.SemaphoreSecurity:RemoveAuditRule(System.Security.AccessControl.SemaphoreAuditRule):bool:this
          -3 (-30.00% of base) : 191997.dasm - System.Security.AccessControl.SemaphoreSecurity:RemoveAccessRule(System.Security.AccessControl.SemaphoreAccessRule):bool:this
          -3 (-30.00% of base) : 20142.dasm - Microsoft.CodeAnalysis.Diagnostics.AsyncQueue`1:TryComplete():bool:this
          -3 (-30.00% of base) : 20147.dasm - Microsoft.CodeAnalysis.Diagnostics.AsyncQueue`1:TryEnqueue(System.__Canon):bool:this
          -3 (-30.00% of base) : 201535.dasm - System.Security.Principal.SecurityIdentifier:IsEqualDomainSid(System.Security.Principal.SecurityIdentifier):bool:this
          -3 (-30.00% of base) : 201537.dasm - System.Security.Principal.SecurityIdentifier:IsWellKnown(int):bool:this
          -3 (-30.00% of base) : 201550.dasm - System.Security.Principal.SecurityIdentifier:Equals(System.Security.Principal.SecurityIdentifier):bool:this
          -3 (-30.00% of base) : 20621.dasm - Microsoft.CodeAnalysis.Collections.SmallConcurrentSetOfInts:Add(int):bool:this
          -3 (-30.00% of base) : 20623.dasm - Microsoft.CodeAnalysis.Collections.SmallConcurrentSetOfInts:Contains(int):bool:this

15414 total methods with Code Size differences (14894 improved, 520 regressed), 24073 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4298575
Total bytes of diff: 4271545
Total bytes of delta: -27030 (-0.63% of base)
Total relative delta: -89.95
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         198 : 184048.dasm (10.69% of base)
          28 : 184047.dasm (2.03% of base)
          24 : 120910.dasm (3.12% of base)
          21 : 28118.dasm (1.07% of base)
           9 : 185381.dasm (0.46% of base)
           5 : 183691.dasm (1.25% of base)
           3 : 140268.dasm (0.25% of base)
           3 : 56242.dasm (0.66% of base)
           2 : 120548.dasm (0.20% of base)
           2 : 156642.dasm (0.41% of base)
           2 : 156693.dasm (0.55% of base)
           2 : 54679.dasm (0.33% of base)
           2 : 156513.dasm (0.41% of base)
           1 : 143566.dasm (0.44% of base)
           1 : 143567.dasm (0.44% of base)
           1 : 156676.dasm (0.41% of base)
           1 : 156677.dasm (0.32% of base)
           1 : 156678.dasm (0.25% of base)
           1 : 156685.dasm (0.23% of base)
           1 : 155813.dasm (0.05% of base)

Top file improvements (bytes):
        -168 : 28736.dasm (-2.15% of base)
        -126 : 180292.dasm (-2.65% of base)
        -105 : 221364.dasm (-2.60% of base)
        -105 : 107100.dasm (-2.48% of base)
        -102 : 144849.dasm (-1.86% of base)
        -102 : 154620.dasm (-2.78% of base)
        -100 : 227977.dasm (-1.49% of base)
         -99 : 28742.dasm (-2.53% of base)
         -96 : 170944.dasm (-2.99% of base)
         -91 : 54758.dasm (-4.30% of base)
         -91 : 153564.dasm (-1.80% of base)
         -88 : 44208.dasm (-2.36% of base)
         -86 : 144343.dasm (-2.77% of base)
         -84 : 2680.dasm (-1.41% of base)
         -82 : 20914.dasm (-2.57% of base)
         -78 : 28737.dasm (-2.50% of base)
         -78 : 151402.dasm (-1.88% of base)
         -78 : 133020.dasm (-2.18% of base)
         -73 : 116127.dasm (-2.45% of base)
         -72 : 165007.dasm (-2.61% of base)

4889 total files with Code Size differences (4868 improved, 21 regressed), 1194 unchanged.

Top method regressions (bytes):
         198 (10.69% of base) : 184048.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfoFromStatistics(QualifiedTableName,bool):int:this
          28 ( 2.03% of base) : 184047.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfo(bool,QualifiedTableName,bool):int:this
          24 ( 3.12% of base) : 120910.dasm - System.Drawing.Imaging.ImageCodecInfo:ConvertFromMemory(int,int):System.Drawing.Imaging.ImageCodecInfo[]
          21 ( 1.07% of base) : 28118.dasm - Microsoft.CodeAnalysis.CSharp.LambdaRewriter:IntroduceFrame(Microsoft.CodeAnalysis.CSharp.BoundNode,Microsoft.CodeAnalysis.CSharp.LambdaFrame,System.Func`3[[Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Numerics.Vector`1[[System.Single, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Numerics.Vector`1[Single]:this
           9 ( 0.46% of base) : 185381.dasm - System.Data.OleDb.OleDbDataReader:AppendSchemaUniqueIndexAsKey(System.Collections.Hashtable,System.Object[]):this
           5 ( 1.25% of base) : 183691.dasm - System.Data.Common.DBConnectionString:RemoveDuplicates(System.String[]):System.String[]
           3 ( 0.25% of base) : 140268.dasm - System.Xml.Schema.ParticleContentValidator:Finish(bool):System.Xml.Schema.ContentValidator:this
           3 ( 0.66% of base) : 56242.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteDecimalBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator,int):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           2 ( 0.20% of base) : 120548.dasm - System.Drawing.Printing.PrinterSettings:Get_PaperSizes():System.Drawing.Printing.PaperSize[]:this
           2 ( 0.41% of base) : 156642.dasm - System.Text.Json.Nodes.JsonObject:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonObject
           2 ( 0.55% of base) : 156693.dasm - System.Text.Json.Nodes.JsonValue:VerifyJsonElementIsNotArrayOrObject(byref)
           2 ( 0.33% of base) : 54679.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
           2 ( 0.41% of base) : 156513.dasm - System.Text.Json.Nodes.JsonArray:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonArray
           1 ( 0.44% of base) : 143566.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.44% of base) : 143567.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.41% of base) : 156676.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.32% of base) : 156677.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Nullable`1[JsonElement],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.25% of base) : 156678.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.23% of base) : 156685.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Text.Json.Serialization.Metadata.JsonTypeInfo`1[__Canon],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.05% of base) : 155813.dasm - System.Text.Json.JsonSerializer:TryGetReferenceFromJsonElement(byref,System.Text.Json.JsonElement,byref):bool

Top method improvements (bytes):
        -168 (-2.15% of base) : 28736.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -126 (-2.65% of base) : 180292.dasm - System.ComponentModel.CategoryAttribute:GetLocalizedString(System.String):System.String:this
        -105 (-2.60% of base) : 221364.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
        -105 (-2.48% of base) : 107100.dasm - Newtonsoft.Json.Schema.JsonSchemaBuilder:ProcessSchemaProperties(Newtonsoft.Json.Linq.JObject):this
        -102 (-1.86% of base) : 144849.dasm - System.Xml.Xsl.Runtime.XmlCollation:Create(System.String,bool):System.Xml.Xsl.Runtime.XmlCollation
        -102 (-2.78% of base) : 154620.dasm - System.Text.GB18030Encoding:GetChars(int,int,int,int,System.Text.DecoderNLS):int:this
        -100 (-1.49% of base) : 227977.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
         -99 (-2.53% of base) : 28742.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
         -96 (-2.99% of base) : 170944.dasm - Microsoft.CSharp.CSharpCodeGenerator:GetBaseTypeOutput(System.CodeDom.CodeTypeReference,bool):System.String:this
         -91 (-4.30% of base) : 54758.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation:ReportUnusedImports(Microsoft.CodeAnalysis.SyntaxTree,Microsoft.CodeAnalysis.DiagnosticBag,System.Threading.CancellationToken):this
         -91 (-1.80% of base) : 153564.dasm - System.Speech.Internal.SrgsParser.XmlParser:ParseGrammar(System.Xml.XmlReader,System.Speech.Internal.SrgsParser.IGrammar):this
         -88 (-2.36% of base) : 44208.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
         -86 (-2.77% of base) : 144343.dasm - System.Xml.Xsl.XsltOld.XsltCompileContext:FunctionAvailable(System.String):bool:this
         -84 (-1.41% of base) : 2680.dasm - Microsoft.FSharp.Linq.QueryModule:EvalNonNestedOuter(int,Microsoft.FSharp.Quotations.FSharpExpr):System.Object
         -82 (-2.57% of base) : 20914.dasm - Microsoft.CSharp.RuntimeBinder.SymbolTable:IsOperator(System.Reflection.MethodInfo):bool
         -78 (-2.50% of base) : 28737.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetOperatorKind(System.String):ushort
         -78 (-1.88% of base) : 151402.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
         -78 (-2.18% of base) : 133020.dasm - DataContractCriticalHelper:GetBuiltInDataContract(System.String):System.Runtime.Serialization.DataContract
         -73 (-2.45% of base) : 116127.dasm - System.Data.Common.DbColumn:get_Item(System.String):System.Object:this
         -72 (-2.61% of base) : 165007.dasm - Microsoft.Extensions.DependencyModel.DependencyContextJsonReader:ReadCompilationOptions(byref):Microsoft.Extensions.DependencyModel.CompilationOptions

Top method regressions (percentages):
         198 (10.69% of base) : 184048.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfoFromStatistics(QualifiedTableName,bool):int:this
          24 ( 3.12% of base) : 120910.dasm - System.Drawing.Imaging.ImageCodecInfo:ConvertFromMemory(int,int):System.Drawing.Imaging.ImageCodecInfo[]
          28 ( 2.03% of base) : 184047.dasm - System.Data.Odbc.OdbcDataReader:RetrieveKeyInfo(bool,QualifiedTableName,bool):int:this
           5 ( 1.25% of base) : 183691.dasm - System.Data.Common.DBConnectionString:RemoveDuplicates(System.String[]):System.String[]
          21 ( 1.07% of base) : 28118.dasm - Microsoft.CodeAnalysis.CSharp.LambdaRewriter:IntroduceFrame(Microsoft.CodeAnalysis.CSharp.BoundNode,Microsoft.CodeAnalysis.CSharp.LambdaFrame,System.Func`3[[Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Numerics.Vector`1[[System.Single, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Numerics.Vector`1[Single]:this
           3 ( 0.66% of base) : 56242.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteDecimalBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator,int):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           2 ( 0.55% of base) : 156693.dasm - System.Text.Json.Nodes.JsonValue:VerifyJsonElementIsNotArrayOrObject(byref)
           9 ( 0.46% of base) : 185381.dasm - System.Data.OleDb.OleDbDataReader:AppendSchemaUniqueIndexAsKey(System.Collections.Hashtable,System.Object[]):this
           1 ( 0.44% of base) : 143566.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.44% of base) : 143567.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           1 ( 0.41% of base) : 156676.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           2 ( 0.41% of base) : 156642.dasm - System.Text.Json.Nodes.JsonObject:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonObject
           2 ( 0.41% of base) : 156513.dasm - System.Text.Json.Nodes.JsonArray:Create(System.Text.Json.JsonElement,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonArray
           2 ( 0.33% of base) : 54679.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
           1 ( 0.32% of base) : 156677.dasm - System.Text.Json.Nodes.JsonValue:Create(System.Nullable`1[JsonElement],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           3 ( 0.25% of base) : 140268.dasm - System.Xml.Schema.ParticleContentValidator:Finish(bool):System.Xml.Schema.ContentValidator:this
           1 ( 0.25% of base) : 156678.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           1 ( 0.23% of base) : 156685.dasm - System.Text.Json.Nodes.JsonValue:Create(System.__Canon,System.Text.Json.Serialization.Metadata.JsonTypeInfo`1[__Canon],System.Nullable`1[JsonNodeOptions]):System.Text.Json.Nodes.JsonValue
           2 ( 0.20% of base) : 120548.dasm - System.Drawing.Printing.PrinterSettings:Get_PaperSizes():System.Drawing.Printing.PaperSize[]:this
           1 ( 0.12% of base) : 156551.dasm - System.Text.Json.Nodes.JsonNode:ToString():System.String:this

Top method improvements (percentages):
         -25 (-35.21% of base) : 202501.dasm - System.Net.Http.WinHttpRequestState:FromIntPtr(int):System.Net.Http.WinHttpRequestState
          -3 (-33.33% of base) : 220723.dasm - System.Security.NamedPermissionSet:Equals(System.Object):bool:this
          -3 (-33.33% of base) : 220753.dasm - System.Security.Policy.FileCodeGroup:Equals(System.Object):bool:this
          -3 (-33.33% of base) : 220787.dasm - System.Security.Permissions.FileIOPermission:Equals(System.Object):bool:this
         -25 (-28.09% of base) : 204991.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:NativeCallbackHandler(int,int,byref):int
          -3 (-27.27% of base) : 104854.dasm - Newtonsoft.Json.JsonConvert:DeserializeAnonymousType(System.String,ubyte):ubyte
         -25 (-26.32% of base) : 203885.dasm - GetAddrInfoExState:FromHandleAndFree(int):GetAddrInfoExState
          -3 (-25.00% of base) : 79493.dasm - Microsoft.CodeAnalysis.Collections.ImmutableMemoryStream:get_Length():long:this
          -3 (-25.00% of base) : 186072.dasm - <>c__DisplayClass2_0:<.ctor>b__1(System.String):bool:this
         -12 (-23.08% of base) : 211445.dasm - System.Reflection.TypeLoading.TypeContext:GetGenericTypeArgumentOrNull(int):System.Reflection.TypeLoading.RoType:this
          -3 (-23.08% of base) : 179637.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValue():ubyte:this
          -3 (-23.08% of base) : 179651.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValueOrDefault():ubyte:this
         -12 (-22.64% of base) : 211446.dasm - System.Reflection.TypeLoading.TypeContext:GetGenericMethodArgumentOrNull(int):System.Reflection.TypeLoading.RoType:this
         -25 (-21.74% of base) : 202497.dasm - System.Net.Http.WinHttpRequestState:PinReceiveBuffer(System.Byte[]):this
          -3 (-21.43% of base) : 152011.dasm - System.Reflection.Internal.ImmutableMemoryStream:get_Length():long:this
          -3 (-21.43% of base) : 22195.dasm - Microsoft.CSharp.RuntimeBinder.Semantics.AggregateType:get_IsNonNullableValueType():bool:this
          -3 (-21.43% of base) : 43724.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Retargeting.RetargetingAssemblySymbol:GetGuidString(byref):bool:this
          -3 (-21.43% of base) : 203117.dasm - System.Net.Mail.MailAddress:TryCreate(System.String,byref):bool
          -3 (-21.43% of base) : 129094.dasm - System.Xml.PrefixHandle:op_Equality(System.Xml.PrefixHandle,System.Xml.XmlDictionaryString):bool
          -3 (-21.43% of base) : 51427.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingAssemblySymbol:GetGuidString(byref):bool:this

4889 total methods with Code Size differences (4868 improved, 21 regressed), 1194 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9870250
Total bytes of diff: 9788687
Total bytes of delta: -81563 (-0.83% of base)
Total relative delta: -284.81
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          27 : 205007.dasm (1.27% of base)
          26 : 244913.dasm (1.18% of base)
          21 : 284323.dasm (0.94% of base)
          21 : 284502.dasm (0.94% of base)
          18 : 227718.dasm (2.80% of base)
          17 : 267406.dasm (0.69% of base)
          15 : 227719.dasm (2.34% of base)
           8 : 139573.dasm (0.60% of base)
           4 : 139784.dasm (0.28% of base)
           3 : 141414.dasm (0.52% of base)
           2 : 169925.dasm (0.30% of base)

Top file improvements (bytes):
        -240 : 309017.dasm (-1.80% of base)
        -171 : 152063.dasm (-6.32% of base)
        -153 : 68396.dasm (-3.12% of base)
        -144 : 151169.dasm (-2.12% of base)
        -140 : 124618.dasm (-15.37% of base)
        -123 : 255875.dasm (-2.15% of base)
        -120 : 74505.dasm (-0.92% of base)
        -118 : 180043.dasm (-3.96% of base)
        -111 : 129869.dasm (-1.19% of base)
        -108 : 150498.dasm (-5.78% of base)
        -102 : 155251.dasm (-5.81% of base)
         -92 : 176565.dasm (-1.02% of base)
         -92 : 124606.dasm (-15.75% of base)
         -88 : 340405.dasm (-1.49% of base)
         -84 : 135203.dasm (-2.30% of base)
         -84 : 249513.dasm (-5.72% of base)
         -81 : 11929.dasm (-2.46% of base)
         -81 : 152031.dasm (-2.83% of base)
         -81 : 152065.dasm (-5.18% of base)
         -79 : 344443.dasm (-2.26% of base)

14931 total files with Code Size differences (14920 improved, 11 regressed), 1270 unchanged.

Top method regressions (bytes):
          27 ( 1.27% of base) : 205007.dasm - System.ServiceModel.Syndication.Tests.XmlDiffDocument:ReadChildNodes(System.ServiceModel.Syndication.Tests.XmlDiffNode,System.Xml.XmlReader,System.ServiceModel.Syndication.Tests.PositionInfo):this
          26 ( 1.18% of base) : 244913.dasm - Microsoft.DotNet.ProjectModel.ProjectReader:ReadProject(System.IO.Stream,System.String,System.String,Microsoft.DotNet.ProjectModel.ProjectReaderSettings):Microsoft.DotNet.ProjectModel.Project:this
          21 ( 0.94% of base) : 284323.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
          21 ( 0.94% of base) : 284502.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
          18 ( 2.80% of base) : 227718.dasm - ImTools.ArrayTools:Match(System.__Canon[],System.Func`2[__Canon,Boolean],System.Func`2[__Canon,Nullable`1]):System.Nullable`1[System.Int32][]
          17 ( 0.69% of base) : 267406.dasm - System.Collections.Immutable.Tests.ImmutableListTest:IndexOfAndContainsTest():this
          15 ( 2.34% of base) : 227719.dasm - ImTools.ArrayTools:Match(System.Byte[],System.Func`2[Byte,Boolean],System.Func`2[Byte,Nullable`1]):System.Nullable`1[System.Int32][]
           8 ( 0.60% of base) : 139573.dasm - <ListAsync>d__7:MoveNext():this
           4 ( 0.28% of base) : 139784.dasm - <CopyNupkgFileToAsync>d__20:MoveNext():this
           3 ( 0.52% of base) : 141414.dasm - System.CodeDom.Tests.CodeCollectionTestBase`2[__Canon,__Canon][System.__Canon,System.__Canon]:VerifyCollection(System.__Canon,System.__Canon[]):this
           2 ( 0.30% of base) : 169925.dasm - <>c__DisplayClass4_0:<Validate>b__0(System.Collections.Generic.KeyValuePair`2[Int32,Int32]):this

Top method improvements (bytes):
        -240 (-1.80% of base) : 309017.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4EqualsNanTest():this
        -171 (-6.32% of base) : 152063.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:Remove():this
        -153 (-3.12% of base) : 68396.dasm - System.Tests.AttributeGetCustomAttributes:RunPosTests()
        -144 (-2.12% of base) : 151169.dasm - System.Data.Tests.DataTableTest4:XmlTest10():this
        -140 (-15.37% of base) : 124618.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
        -123 (-2.15% of base) : 255875.dasm - NuGet.Frameworks.NuGetFramework:TryParseCommonFramework(System.String,byref):bool
        -120 (-0.92% of base) : 74505.dasm - <ToString_MatchesExpected_MemberData>d__105:MoveNext():bool:this
        -118 (-3.96% of base) : 180043.dasm - System.Net.Http.Tests.MediaTypeHeaderParserTest:TryParse_SetOfValidValueStringsForMediaTypeWithQuality_ParsedCorrectly():this
        -111 (-1.19% of base) : 129869.dasm - Microsoft.Diagnostics.Runtime.Desktop.LockInspection:SetThreadWaiters():this
        -108 (-5.78% of base) : 150498.dasm - System.Data.Tests.DataRowTest2:HasVersion_ByDataRowVersion():this
        -102 (-5.81% of base) : 155251.dasm - System.ComponentModel.TypeConverterTests.IconConverterTest:TestCanConvertTo():this
         -92 (-1.02% of base) : 176565.dasm - System.Buffers.Text.Tests.FormatterTests:TryFormatUtf8(System.Object,System.Span`1[Byte],byref,System.Buffers.StandardFormat):bool
         -92 (-15.75% of base) : 124606.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
         -88 (-1.49% of base) : 340405.dasm - TCNamespace:TestNamespace6():this
         -84 (-2.30% of base) : 135203.dasm - NuGet.Packaging.ManifestReader:ReadMetadataValue(NuGet.Packaging.ManifestMetadata,System.Xml.Linq.XElement,System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
         -84 (-5.72% of base) : 249513.dasm - Microsoft.Extensions.Logging.Test.EventSourceLoggerTest:FilterSpecs_UseAppFilters_IncreaseLoggingLevelForOneCategory_GuaranteesAllRulesRemainAvailable():this
         -81 (-2.46% of base) : 11929.dasm - Microsoft.CodeAnalysis.Classification.Classifier:GetClassificationKind(System.String):System.Nullable`1[SymbolDisplayPartKind]
         -81 (-2.83% of base) : 152031.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:TryGetValueTest():this
         -81 (-5.18% of base) : 152065.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:ContainsKey():this
         -79 (-2.26% of base) : 344443.dasm - TCWriteState:InvokeMethod(System.Xml.XmlWriter,System.String):this

Top method regressions (percentages):
          18 ( 2.80% of base) : 227718.dasm - ImTools.ArrayTools:Match(System.__Canon[],System.Func`2[__Canon,Boolean],System.Func`2[__Canon,Nullable`1]):System.Nullable`1[System.Int32][]
          15 ( 2.34% of base) : 227719.dasm - ImTools.ArrayTools:Match(System.Byte[],System.Func`2[Byte,Boolean],System.Func`2[Byte,Nullable`1]):System.Nullable`1[System.Int32][]
          27 ( 1.27% of base) : 205007.dasm - System.ServiceModel.Syndication.Tests.XmlDiffDocument:ReadChildNodes(System.ServiceModel.Syndication.Tests.XmlDiffNode,System.Xml.XmlReader,System.ServiceModel.Syndication.Tests.PositionInfo):this
          26 ( 1.18% of base) : 244913.dasm - Microsoft.DotNet.ProjectModel.ProjectReader:ReadProject(System.IO.Stream,System.String,System.String,Microsoft.DotNet.ProjectModel.ProjectReaderSettings):Microsoft.DotNet.ProjectModel.Project:this
          21 ( 0.94% of base) : 284323.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
          21 ( 0.94% of base) : 284502.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
          17 ( 0.69% of base) : 267406.dasm - System.Collections.Immutable.Tests.ImmutableListTest:IndexOfAndContainsTest():this
           8 ( 0.60% of base) : 139573.dasm - <ListAsync>d__7:MoveNext():this
           3 ( 0.52% of base) : 141414.dasm - System.CodeDom.Tests.CodeCollectionTestBase`2[__Canon,__Canon][System.__Canon,System.__Canon]:VerifyCollection(System.__Canon,System.__Canon[]):this
           2 ( 0.30% of base) : 169925.dasm - <>c__DisplayClass4_0:<Validate>b__0(System.Collections.Generic.KeyValuePair`2[Int32,Int32]):this
           4 ( 0.28% of base) : 139784.dasm - <CopyNupkgFileToAsync>d__20:MoveNext():this

Top method improvements (percentages):
         -25 (-47.17% of base) : 321828.dasm - <>c__DisplayClass0_0:<Ctor_Default>b__0():System.Object:this
         -25 (-41.67% of base) : 257807.dasm - SQLitePCL.log_hook_info:from_ptr(int):SQLitePCL.log_hook_info
         -25 (-41.67% of base) : 257811.dasm - SQLitePCL.commit_hook_info:from_ptr(int):SQLitePCL.commit_hook_info
         -25 (-41.67% of base) : 257813.dasm - SQLitePCL.rollback_hook_info:from_ptr(int):SQLitePCL.rollback_hook_info
         -25 (-41.67% of base) : 257816.dasm - SQLitePCL.trace_hook_info:from_ptr(int):SQLitePCL.trace_hook_info
         -25 (-41.67% of base) : 257819.dasm - SQLitePCL.profile_hook_info:from_ptr(int):SQLitePCL.profile_hook_info
         -25 (-41.67% of base) : 257822.dasm - SQLitePCL.progress_hook_info:from_ptr(int):SQLitePCL.progress_hook_info
         -25 (-41.67% of base) : 257825.dasm - SQLitePCL.update_hook_info:from_ptr(int):SQLitePCL.update_hook_info
         -25 (-41.67% of base) : 257828.dasm - SQLitePCL.collation_hook_info:from_ptr(int):SQLitePCL.collation_hook_info
         -25 (-41.67% of base) : 257831.dasm - SQLitePCL.exec_hook_info:from_ptr(int):SQLitePCL.exec_hook_info
         -25 (-41.67% of base) : 257834.dasm - SQLitePCL.function_hook_info:from_ptr(int):SQLitePCL.function_hook_info
         -25 (-41.67% of base) : 257841.dasm - SQLitePCL.authorizer_hook_info:from_ptr(int):SQLitePCL.authorizer_hook_info
         -25 (-40.98% of base) : 251769.dasm - StringWeakHandle:get_IsUsed():bool:this
         -25 (-35.21% of base) : 296964.dasm - System.Net.Http.WinHttpRequestState:FromIntPtr(int):System.Net.Http.WinHttpRequestState
          -3 (-27.27% of base) : 253463.dasm - Moq.CastleProxyFactory:IsTypeVisible(System.Type):bool:this
         -25 (-25.00% of base) : 322720.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToTypeTest:CheckTypeNotUnloaded():this
         -25 (-25.00% of base) : 322724.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToInstanceTest:CheckInstanceNotUnloaded():this
          -3 (-25.00% of base) : 341280.dasm - System.Xml.Tests.OneByteStream:get_Length():long:this
         -25 (-25.00% of base) : 299393.dasm - GetAddrInfoExState:FromHandleAndFree(int):GetAddrInfoExState
          -3 (-25.00% of base) : 122258.dasm - Microsoft.CodeAnalysis.CSharp.LanguageServices.CSharpSyntaxFacts:IsIdentifierStartCharacter(ushort):bool:this

14931 total methods with Code Size differences (14920 improved, 11 regressed), 1270 unchanged.

```

</details>

--------------------------------------------------------------------------------

