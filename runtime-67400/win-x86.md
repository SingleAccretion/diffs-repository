## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9009069 (overridden on cmd)
Total bytes of diff: 8999456 (overridden on cmd)
Total bytes of delta: -9613 (-0.11 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          45 : 6683.dasm (2.35% of base)
          38 : 11178.dasm (0.80% of base)
          27 : 9216.dasm (0.48% of base)
          23 : 9413.dasm (1.10% of base)
           7 : 24913.dasm (0.28% of base)
           4 : 1854.dasm (0.06% of base)
           1 : 12065.dasm (0.33% of base)
           1 : 9018.dasm (0.15% of base)

Top file improvements (bytes):
       -1189 : 28492.dasm (-4.98% of base)
        -388 : 25126.dasm (-2.04% of base)
        -374 : 7196.dasm (-1.91% of base)
        -362 : 25467.dasm (-4.89% of base)
        -227 : 25304.dasm (-4.83% of base)
        -165 : 7459.dasm (-2.36% of base)
        -122 : 5550.dasm (-0.86% of base)
        -107 : 8285.dasm (-0.90% of base)
        -106 : 29021.dasm (-4.76% of base)
         -76 : 7318.dasm (-1.29% of base)
         -75 : 1973.dasm (-1.28% of base)
         -67 : 903.dasm (-4.73% of base)
         -63 : 8182.dasm (-2.34% of base)
         -58 : 8194.dasm (-1.88% of base)
         -55 : 12507.dasm (-0.88% of base)
         -52 : 659.dasm (-3.83% of base)
         -48 : 2563.dasm (-1.20% of base)
         -44 : 7613.dasm (-0.41% of base)
         -44 : 10829.dasm (-4.76% of base)
         -43 : 23915.dasm (-48.86% of base)

2347 total files with Code Size differences (2339 improved, 8 regressed), 299 unchanged.

Top method regressions (bytes):
          45 ( 2.35% of base) : 6683.dasm - System.Number:TryParseNumber(byref,int,int,byref,System.Globalization.NumberFormatInfo):bool
          38 ( 0.80% of base) : 11178.dasm - System.Diagnostics.Tracing.EventSource:CreateManifestAndDescriptors(System.Type,System.String,System.Diagnostics.Tracing.EventSource,int):System.Byte[]
          27 ( 0.48% of base) : 9216.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Serialize(byref,int,MicroBenchmarks.Serializers.Location,MessagePack.IFormatterResolver):int:this
          23 ( 1.10% of base) : 9413.dasm - System.Xml.Serialization.XmlSerializationWriterILGen:WriteArrayItems(System.Xml.Serialization.ElementAccessor[],System.Xml.Serialization.TextAccessor,System.Xml.Serialization.ChoiceIdentifierAccessor,System.Xml.Serialization.TypeDesc,System.String,System.String):this
           7 ( 0.28% of base) : 24913.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxAndDeclarationManager:AddSyntaxTrees(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxTree, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.SyntaxAndDeclarationManager:this
           4 ( 0.06% of base) : 1854.dasm - System.DateTimeFormat:FormatCustomized(System.DateTime,System.ReadOnlySpan`1[Char],System.Globalization.DateTimeFormatInfo,System.TimeSpan,System.Text.StringBuilder):System.Text.StringBuilder
           1 ( 0.33% of base) : 12065.dasm - ConstructorMatcher:Match(System.Object[]):int:this
           1 ( 0.15% of base) : 9018.dasm - System.Number:<FormatInt32>g__FormatInt32Slow|38_0(int,int,System.String,System.IFormatProvider):System.String

Top method improvements (bytes):
       -1189 (-4.98% of base) : 28492.dasm - System.Linq.Tests.PersonData:.cctor()
        -388 (-2.04% of base) : 25126.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
        -374 (-1.91% of base) : 7196.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -362 (-4.89% of base) : 25467.dasm - Microsoft.CodeAnalysis.WellKnownMembers:.cctor()
        -227 (-4.83% of base) : 25304.dasm - Microsoft.CodeAnalysis.WellKnownTypes:.cctor()
        -165 (-2.36% of base) : 7459.dasm - MessagePack.MessagePackBinary:.cctor()
        -122 (-0.86% of base) : 5550.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
        -107 (-0.90% of base) : 8285.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
        -106 (-4.76% of base) : 29021.dasm - System.Xml.Serialization.XmlCustomFormatter:.cctor()
         -76 (-1.29% of base) : 7318.dasm - MessagePack.Internal.BuiltinResolverGetFormatterHelper:.cctor()
         -75 (-1.28% of base) : 1973.dasm - BuiltinResolverGetFormatterHelper:.cctor()
         -67 (-4.73% of base) : 903.dasm - JetStream.CardDeck:.cctor()
         -63 (-2.34% of base) : 8182.dasm - System.Xml.Serialization.TypeScope:.cctor()
         -58 (-1.88% of base) : 8194.dasm - System.Xml.Serialization.TypeScope:AddSoapEncodedTypes(System.String)
         -55 (-0.88% of base) : 12507.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Serialize(byref,int,MicroBenchmarks.Serializers.ActiveOrUpcomingEvent,MessagePack.IFormatterResolver):int:this
         -52 (-3.83% of base) : 659.dasm - System.Number:.cctor()
         -48 (-1.20% of base) : 2563.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:.cctor()
         -44 (-0.41% of base) : 7613.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Serialize(byref,int,MicroBenchmarks.Serializers.MyEventsListerItem,MessagePack.IFormatterResolver):int:this
         -44 (-4.76% of base) : 10829.dasm - System.MulticastDelegate:CombineImpl(System.Delegate):System.Delegate:this
         -43 (-2.08% of base) : 25425.dasm - Microsoft.CodeAnalysis.SpecialTypes:.cctor()

Top method regressions (percentages):
          45 ( 2.35% of base) : 6683.dasm - System.Number:TryParseNumber(byref,int,int,byref,System.Globalization.NumberFormatInfo):bool
          23 ( 1.10% of base) : 9413.dasm - System.Xml.Serialization.XmlSerializationWriterILGen:WriteArrayItems(System.Xml.Serialization.ElementAccessor[],System.Xml.Serialization.TextAccessor,System.Xml.Serialization.ChoiceIdentifierAccessor,System.Xml.Serialization.TypeDesc,System.String,System.String):this
          38 ( 0.80% of base) : 11178.dasm - System.Diagnostics.Tracing.EventSource:CreateManifestAndDescriptors(System.Type,System.String,System.Diagnostics.Tracing.EventSource,int):System.Byte[]
          27 ( 0.48% of base) : 9216.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Serialize(byref,int,MicroBenchmarks.Serializers.Location,MessagePack.IFormatterResolver):int:this
           1 ( 0.33% of base) : 12065.dasm - ConstructorMatcher:Match(System.Object[]):int:this
           7 ( 0.28% of base) : 24913.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxAndDeclarationManager:AddSyntaxTrees(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxTree, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.SyntaxAndDeclarationManager:this
           1 ( 0.15% of base) : 9018.dasm - System.Number:<FormatInt32>g__FormatInt32Slow|38_0(int,int,System.String,System.IFormatProvider):System.String
           4 ( 0.06% of base) : 1854.dasm - System.DateTimeFormat:FormatCustomized(System.DateTime,System.ReadOnlySpan`1[Char],System.Globalization.DateTimeFormatInfo,System.TimeSpan,System.Text.StringBuilder):System.Text.StringBuilder

Top method improvements (percentages):
         -43 (-48.86% of base) : 23915.dasm - System.Numerics.Tests.Perf_Vector4:GetHashCodeBenchmark():int:this
         -33 (-46.48% of base) : 31709.dasm - System.Numerics.Tests.Perf_Vector3:GetHashCodeBenchmark():int:this
         -23 (-39.66% of base) : 27369.dasm - System.Numerics.Tests.Perf_Vector2:GetHashCodeBenchmark():int:this
          -2 (-18.18% of base) : 28313.dasm - System.Tests.Perf_Type:GetTypeFromHandle():System.Type:this
          -5 (-17.86% of base) : 6528.dasm - <>c__DisplayClass21_0:<ConnectAsync>b__0():this
          -5 (-12.50% of base) : 27324.dasm - SciMark2.kernel:benchSparseMult():this
          -5 (-12.20% of base) : 13300.dasm - System.Collections.Generic.SortedList`2[Int32,Int32][System.Int32,System.Int32]:IndexOfKey(int):int:this
         -11 (-11.70% of base) : 33036.dasm - System.Collections.ContainsFalse`1[__Canon][System.__Canon]:ImmutableArray():bool:this
         -11 (-11.70% of base) : 24398.dasm - System.Collections.ContainsTrue`1[__Canon][System.__Canon]:ImmutableArray():bool:this
          -4 (-10.81% of base) : 15512.dasm - <>c__DisplayClass7_1:<IsMatch_Multithreading>b__0():bool:this
          -3 (-10.34% of base) : 15058.dasm - Replica`1[RangeWorker][System.Threading.Tasks.RangeWorker]:ExecuteAction(byref):this
          -7 (-10.29% of base) : 11271.dasm - ActivityScope:Dispose():this
          -3 (-10.00% of base) : 4676.dasm - KeyValuePairComparer[__Canon,__Canon][System.__Canon,System.__Canon]:Compare(System.Collections.Generic.KeyValuePair`2[__Canon,__Canon],System.Collections.Generic.KeyValuePair`2[__Canon,__Canon]):int:this
          -1 (-9.09% of base) : 4162.dasm - Microsoft.Extensions.DependencyInjection.ServiceProvider:GetService(System.Type):System.Object:this
          -2 (-8.70% of base) : 8875.dasm - System.Collections.Generic.List`1[__Canon][System.__Canon]:IndexOf(System.__Canon):int:this
          -4 (-8.33% of base) : 32073.dasm - System.Threading.Tests.Perf_CancellationToken:CreateLinkedTokenSource2():this
          -2 (-7.69% of base) : 11356.dasm - System.Collections.Sort`1[__Canon][System.__Canon]:SetupArrayIteration():this
          -2 (-7.69% of base) : 13879.dasm - System.Collections.Sort`1[__Canon][System.__Canon]:SetupListIteration():this
          -2 (-7.41% of base) : 6272.dasm - <>c__DisplayClass27_0:<AcquireCredentialsHandle>b__0():System.Net.Security.SafeFreeCredentials:this
          -6 (-7.32% of base) : 25845.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.OverriddenOrHiddenMembersResult:.cctor()

2347 total methods with Code Size differences (2339 improved, 8 regressed), 299 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 115733908 (overridden on cmd)
Total bytes of diff: 115483131 (overridden on cmd)
Total bytes of delta: -250777 (-0.22 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          71 : 245948.dasm (1.68% of base)
          11 : 245940.dasm (0.96% of base)
          10 : 36467.dasm (1.47% of base)
           4 : 56190.dasm (0.52% of base)
           2 : 26139.dasm (1.10% of base)
           1 : 246488.dasm (0.08% of base)

Top file improvements (bytes):
      -20450 : 254712.dasm (-6.63% of base)
      -12816 : 5474.dasm (-8.29% of base)
      -10080 : 254711.dasm (-4.14% of base)
       -6764 : 5464.dasm (-4.42% of base)
       -3984 : 12456.dasm (-10.42% of base)
       -2380 : 12469.dasm (-8.31% of base)
       -2360 : 12464.dasm (-7.82% of base)
       -2300 : 262496.dasm (-1.79% of base)
       -2296 : 262506.dasm (-1.43% of base)
       -2296 : 262553.dasm (-1.64% of base)
       -2296 : 262573.dasm (-1.43% of base)
       -2264 : 258613.dasm (-1.36% of base)
       -2264 : 258633.dasm (-1.36% of base)
       -1997 : 262394.dasm (-1.59% of base)
       -1997 : 262517.dasm (-1.59% of base)
       -1424 : 12549.dasm (-3.69% of base)
       -1171 : 18597.dasm (-2.19% of base)
       -1012 : 258623.dasm (-0.56% of base)
       -1012 : 258643.dasm (-0.56% of base)
        -932 : 262420.dasm (-0.70% of base)

34849 total files with Code Size differences (34843 improved, 6 regressed), 1046 unchanged.

Top method regressions (bytes):
          71 ( 1.68% of base) : 245948.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeAutoFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          11 ( 0.96% of base) : 245940.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeStaticFieldLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedStaticFieldLayout:this
          10 ( 1.47% of base) : 36467.dasm - Driver`2[__Canon,__Canon][System.__Canon,System.__Canon]:AddRemoveKeyValPair(System.__Canon[],System.__Canon[],int,int):this
           4 ( 0.52% of base) : 56190.dasm - ILStubClass:IL_STUB_PInvoke(int,int,System.Text.StringBuilder,int,int):int
           2 ( 1.10% of base) : 26139.dasm - MonoAPI.Tests.MonoAPISupport:SetupSymbols(System.String):bool
           1 ( 0.08% of base) : 246488.dasm - Internal.TypeSystem.Ecma.MetadataExtensions:GetCustomAttributeHandle(System.Reflection.Metadata.MetadataReader,System.Reflection.Metadata.CustomAttributeHandleCollection,System.String,System.String):System.Reflection.Metadata.CustomAttributeHandle

Top method improvements (bytes):
      -20450 (-6.63% of base) : 254712.dasm - CodeSize0:Main():int
      -12816 (-8.29% of base) : 5474.dasm - r4rem:Main():int
      -10080 (-4.14% of base) : 254711.dasm - CodeSize1:Main():int
       -6764 (-4.42% of base) : 5464.dasm - r4rem:Main():int
       -3984 (-10.42% of base) : 12456.dasm - r4NaNrem:Main():int
       -2380 (-8.31% of base) : 12469.dasm - r4NaNrem:Main():int
       -2360 (-7.82% of base) : 12464.dasm - r4NaNrem:Main():int
       -2300 (-1.79% of base) : 262496.dasm - i4rem:Main():int
       -2296 (-1.43% of base) : 262506.dasm - i8rem:Main():int
       -2296 (-1.64% of base) : 262553.dasm - u4rem:Main():int
       -2296 (-1.43% of base) : 262573.dasm - u8rem:Main():int
       -2264 (-1.36% of base) : 258613.dasm - decimaldiv:Main():int
       -2264 (-1.36% of base) : 258633.dasm - decimalrem:Main():int
       -1997 (-1.59% of base) : 262394.dasm - overlddiv:Main():int
       -1997 (-1.59% of base) : 262517.dasm - overldrem:Main():int
       -1424 (-3.69% of base) : 12549.dasm - r8NaNrem:Main():int
       -1171 (-2.19% of base) : 18597.dasm - lclfldrem:Main():int
       -1012 (-0.56% of base) : 258623.dasm - decimaldiv:Main():int
       -1012 (-0.56% of base) : 258643.dasm - decimalrem:Main():int
        -932 (-0.70% of base) : 262420.dasm - overlddiv:Main():int

Top method regressions (percentages):
          71 ( 1.68% of base) : 245948.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeAutoFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          10 ( 1.47% of base) : 36467.dasm - Driver`2[__Canon,__Canon][System.__Canon,System.__Canon]:AddRemoveKeyValPair(System.__Canon[],System.__Canon[],int,int):this
           2 ( 1.10% of base) : 26139.dasm - MonoAPI.Tests.MonoAPISupport:SetupSymbols(System.String):bool
          11 ( 0.96% of base) : 245940.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeStaticFieldLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedStaticFieldLayout:this
           4 ( 0.52% of base) : 56190.dasm - ILStubClass:IL_STUB_PInvoke(int,int,System.Text.StringBuilder,int,int):int
           1 ( 0.08% of base) : 246488.dasm - Internal.TypeSystem.Ecma.MetadataExtensions:GetCustomAttributeHandle(System.Reflection.Metadata.MetadataReader,System.Reflection.Metadata.CustomAttributeHandleCollection,System.String,System.String):System.Reflection.Metadata.CustomAttributeHandle

Top method improvements (percentages):
         -63 (-57.80% of base) : 57480.dasm - BoundingBoxTest:GetHashCode():int:this
        -515 (-45.82% of base) : 247946.dasm - NativeVarargTest.VarArg:TestPassingManyFloatsManaged(System.Single[]):bool
         -80 (-44.20% of base) : 29353.dasm - MathFusedMultiplyAddTest.Program:Check1(float,float,float)
         -20 (-37.74% of base) : 12467.dasm - numHolder:op_Modulus(numHolder,numHolder):float
         -13 (-34.21% of base) : 194483.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.DuplicateUnaryOpTest__DuplicateToVector64_Single):this
         -63 (-32.14% of base) : 247934.dasm - NativeVarargTest.VarArg:TestPassingFloatsManaged(System.Single[]):bool
         -60 (-30.61% of base) : 52565.dasm - BringUpTest_FPCall2:FPCall2(float,float,float,float):float
         -60 (-30.46% of base) : 29354.dasm - MathFusedMultiplyAddTest.Program:Check2(float,float,float)
         -60 (-30.46% of base) : 29357.dasm - MathFusedMultiplyAddTest.Program:Check5(float,float,float)
         -60 (-30.46% of base) : 29360.dasm - MathFusedMultiplyAddTest.Program:Check8(float,float,float)
         -60 (-29.70% of base) : 29368.dasm - MathFusedMultiplyAddTest.Program:TestExplicitFmaUsage6(byref,float)
         -30 (-29.41% of base) : 146032.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 200886.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 227403.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 163891.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 215987.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 92830.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 135969.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 138537.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float
         -30 (-29.41% of base) : 218791.dasm - JIT.HardwareIntrinsics.Arm.Helpers:FusedMultiplyAdd(float,float,float):float

34849 total methods with Code Size differences (34843 improved, 6 regressed), 1046 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 27648889 (overridden on cmd)
Total bytes of diff: 27523519 (overridden on cmd)
Total bytes of delta: -125370 (-0.45 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         843 : 198690.dasm (6.22% of base)
         525 : 171852.dasm (14.79% of base)
          67 : 45932.dasm (2.16% of base)
          56 : 16240.dasm (2.83% of base)
          46 : 46252.dasm (2.63% of base)
          26 : 71326.dasm (2.55% of base)
          25 : 42924.dasm (1.75% of base)
          25 : 60985.dasm (0.89% of base)
          24 : 22529.dasm (1.68% of base)
          22 : 194183.dasm (0.97% of base)
          15 : 23539.dasm (0.92% of base)
          15 : 46147.dasm (0.37% of base)
          13 : 137407.dasm (0.62% of base)
          11 : 173494.dasm (3.20% of base)
          11 : 52484.dasm (1.77% of base)
          11 : 216567.dasm (1.01% of base)
          11 : 66207.dasm (1.74% of base)
           9 : 128055.dasm (0.60% of base)
           9 : 41233.dasm (2.11% of base)
           8 : 52468.dasm (0.63% of base)

Top file improvements (bytes):
       -2763 : 107498.dasm (-3.87% of base)
       -1130 : 105352.dasm (-3.92% of base)
        -798 : 107229.dasm (-4.01% of base)
        -702 : 106927.dasm (-3.75% of base)
        -424 : 110093.dasm (-1.20% of base)
        -274 : 201199.dasm (-3.98% of base)
        -256 : 12671.dasm (-2.12% of base)
        -205 : 171735.dasm (-10.43% of base)
        -160 : 13223.dasm (-7.66% of base)
        -160 : 13224.dasm (-41.45% of base)
        -134 : 129536.dasm (-0.83% of base)
        -123 : 160721.dasm (-4.19% of base)
        -122 : 85276.dasm (-3.25% of base)
        -119 : 197238.dasm (-1.47% of base)
        -114 : 197442.dasm (-1.45% of base)
        -111 : 91987.dasm (-7.12% of base)
        -108 : 71695.dasm (-7.05% of base)
        -107 : 198880.dasm (-5.05% of base)
         -99 : 137335.dasm (-2.70% of base)
         -93 : 19227.dasm (-2.24% of base)

35510 total files with Code Size differences (35417 improved, 93 regressed), 1942 unchanged.

Top method regressions (bytes):
         843 ( 6.22% of base) : 198690.dasm - System.Management.ManagementClassGenerator:GenerateMethods():this
         525 (14.79% of base) : 171852.dasm - System.Data.OleDb.OleDbDataReader:DumpToSchemaTable(System.Data.Common.UnsafeNativeMethods+IRowset):this
          67 ( 2.16% of base) : 45932.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol],Microsoft.CodeAnalysis.VisualBasic.Binder+CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
          56 ( 2.83% of base) : 16240.dasm - System.Number:TryParseNumber(byref,int,int,byref,System.Globalization.NumberFormatInfo):bool
          46 ( 2.63% of base) : 46252.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindArrayBounds(Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize[],bool):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
          26 ( 2.55% of base) : 71326.dasm - Microsoft.CodeAnalysis.CSharp.Binder:ReduceOrderBy(Microsoft.CodeAnalysis.CSharp.Syntax.OrderByClauseSyntax,Microsoft.CodeAnalysis.CSharp.Binder+QueryTranslationState,Microsoft.CodeAnalysis.DiagnosticBag):this
          25 ( 0.89% of base) : 60985.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseNamespaceBody(byref,byref,byref,ushort):this
          25 ( 1.75% of base) : 42924.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceFile:BindOptions(Microsoft.CodeAnalysis.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.OptionStatementSyntax],Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,byref,byref,byref,byref,System.Nullable`1[Microsoft.CodeAnalysis.Text.TextSpan])
          24 ( 1.68% of base) : 22529.dasm - InferenceGraph:Infer(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundNode,byref,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.BitVector):bool
          22 ( 0.97% of base) : 194183.dasm - CommandLine.UnParserExtensions:FormatCommandLine(CommandLine.Parser,System.__Canon,System.Action`1[CommandLine.UnParserSettings]):System.String
          15 ( 0.92% of base) : 23539.dasm - IteratorMethodToClassRewriter:GenerateMoveNextAndDispose(Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedMethod,Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedMethod):this
          15 ( 0.37% of base) : 46147.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,ushort,int,bool,Microsoft.CodeAnalysis.DiagnosticBag,bool,byref):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          13 ( 0.62% of base) : 137407.dasm - System.Data.XMLDiffLoader:ReadOldRowData(System.Data.DataSet,byref,byref,System.Xml.XmlReader):int:this
          11 ( 1.77% of base) : 52484.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitStringSwitchJumpTable(Microsoft.CodeAnalysis.CSharp.BoundSwitchStatement,System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.ConstantValue, System.Object][],Microsoft.CodeAnalysis.CSharp.Symbols.LabelSymbol,Microsoft.CodeAnalysis.CodeGen.LocalOrParameter,Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode):this
          11 ( 1.74% of base) : 66207.dasm - Microsoft.CodeAnalysis.CSharp.InitializerRewriter:RewriteScriptInitializer(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundInitializer],Microsoft.CodeAnalysis.CSharp.Symbols.SynthesizedInteractiveInitializerMethod,byref):Microsoft.CodeAnalysis.CSharp.BoundTypeOrInstanceInitializers
          11 ( 3.20% of base) : 173494.dasm - System.Composition.Convention.PartConventionBuilder:ConfigureConstructorAttributes(System.Reflection.ConstructorInfo,byref,System.Action`2[System.Reflection.ParameterInfo, System.Composition.Convention.ImportConventionBuilder])
          11 ( 1.01% of base) : 216567.dasm - System.Diagnostics.SharedPerformanceCounter:CreateInstance(int,int,System.String,int):int:this
           9 ( 0.60% of base) : 128055.dasm - Microsoft.CodeAnalysis.Emit.DeltaMetadataWriter:GetDelta(Microsoft.CodeAnalysis.Emit.EmitBaseline,Microsoft.CodeAnalysis.Compilation,System.Guid,Microsoft.Cci.MetadataSizes):Microsoft.CodeAnalysis.Emit.EmitBaseline:this
           9 ( 2.11% of base) : 41233.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitComplexConditionalAccessReceiver(Microsoft.CodeAnalysis.VisualBasic.BoundComplexConditionalAccessReceiver,bool):this
           8 ( 0.63% of base) : 52468.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.Optimizer:RemoveIntersectingLocals(System.Collections.Generic.Dictionary`2[Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol, Microsoft.CodeAnalysis.CSharp.CodeGen.LocalDefUseInfo],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.CSharp.CodeGen.LocalDefUseInfo])

Top method improvements (bytes):
       -2763 (-3.87% of base) : 107498.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServerTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
       -1130 (-3.92% of base) : 105352.dasm - Microsoft.Diagnostics.Tracing.Parsers.KernelTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -798 (-4.01% of base) : 107229.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrPrivateTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -702 (-3.75% of base) : 106927.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -424 (-1.20% of base) : 110093.dasm - Microsoft.Diagnostics.Tracing.CtfTraceEventSource:InitEventMap():System.Collections.Generic.Dictionary`2[System.String, Microsoft.Diagnostics.Tracing.ETWMapping]
        -274 (-3.98% of base) : 201199.dasm - CultureInfoMapper:CreateMap():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -256 (-2.12% of base) : 12671.dasm - System.Globalization.CultureData:get_RegionNames():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -205 (-10.43% of base) : 171735.dasm - System.Data.OleDb.OleDbSchemaGuid:GetTextFromValue(System.Guid):System.String
        -160 (-41.45% of base) : 13224.dasm - System.Numerics.Matrix4x4:GetHashCode():int:this
        -160 (-7.66% of base) : 13223.dasm - System.Numerics.Matrix4x4:ToString():System.String:this
        -134 (-0.83% of base) : 129536.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
        -123 (-4.19% of base) : 160721.dasm - System.Xml.Schema.SchemaNames:CreateTokenToQNameTable():this
        -122 (-3.25% of base) : 85276.dasm - System.Net.Http.HPack.H2StaticTable:.cctor()
        -119 (-1.47% of base) : 197238.dasm - System.DirectoryServices.AccountManagement.ADAMStoreCtx:.cctor()
        -114 (-1.45% of base) : 197442.dasm - System.DirectoryServices.AccountManagement.ADStoreCtx:.cctor()
        -111 (-7.12% of base) : 91987.dasm - <>c__DisplayClass0_0:<.ctor>b__1(Microsoft.Diagnostics.Tracing.TraceEvent):this
        -108 (-7.05% of base) : 71695.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckConstantBounds(byte,System.Decimal):bool
        -107 (-5.05% of base) : 198880.dasm - System.Management.WmiNetUtilsHelper:.cctor()
         -99 (-2.70% of base) : 137335.dasm - System.Data.XmlDataTreeWriter:XmlDataRowWriter(System.Data.DataRow,System.String):this
         -93 (-2.24% of base) : 19227.dasm - System.RuntimeType:InvokeMember(System.String,int,System.Reflection.Binder,System.Object,System.Object[],System.Reflection.ParameterModifier[],System.Globalization.CultureInfo,System.String[]):System.Object:this

Top method regressions (percentages):
         525 (14.79% of base) : 171852.dasm - System.Data.OleDb.OleDbDataReader:DumpToSchemaTable(System.Data.Common.UnsafeNativeMethods+IRowset):this
           3 ( 6.38% of base) : 50561.dasm - <>c__DisplayClass48_0:<ForceComplete>b__0(int):this
         843 ( 6.22% of base) : 198690.dasm - System.Management.ManagementClassGenerator:GenerateMethods():this
           5 ( 5.49% of base) : 112939.dasm - Microsoft.FSharp.Collections.ArrayModule:loop@388-34(System.__Canon[],System.__Canon[],Microsoft.FSharp.Core.OptimizedClosures+FSharpFunc`3[System.__Canon, System.__Canon, System.Boolean],int,int):bool
          11 ( 3.20% of base) : 173494.dasm - System.Composition.Convention.PartConventionBuilder:ConfigureConstructorAttributes(System.Reflection.ConstructorInfo,byref,System.Action`2[System.Reflection.ParameterInfo, System.Composition.Convention.ImportConventionBuilder])
          56 ( 2.83% of base) : 16240.dasm - System.Number:TryParseNumber(byref,int,int,byref,System.Globalization.NumberFormatInfo):bool
          46 ( 2.63% of base) : 46252.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindArrayBounds(Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize[],bool):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
          26 ( 2.55% of base) : 71326.dasm - Microsoft.CodeAnalysis.CSharp.Binder:ReduceOrderBy(Microsoft.CodeAnalysis.CSharp.Syntax.OrderByClauseSyntax,Microsoft.CodeAnalysis.CSharp.Binder+QueryTranslationState,Microsoft.CodeAnalysis.DiagnosticBag):this
           3 ( 2.48% of base) : 185792.dasm - ILCompiler.Reflection.ReadyToRun.NativeHashtable:EnumerateAllEntries():ILCompiler.Reflection.ReadyToRun.NativeHashtable+AllEntriesEnumerator:this
           5 ( 2.16% of base) : 129877.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:KeysEqual(Microsoft.CodeAnalysis.AssemblyIdentity,Microsoft.CodeAnalysis.AssemblyIdentity):bool
          67 ( 2.16% of base) : 45932.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol],Microsoft.CodeAnalysis.VisualBasic.Binder+CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
           2 ( 2.13% of base) : 49304.dasm - System.Reflection.TypeLoading.Ecma.EcmaHelpers:AsReadOnlySpan(System.Reflection.Metadata.StringHandle,System.Reflection.Metadata.MetadataReader):System.ReadOnlySpan`1[System.Byte]
           9 ( 2.11% of base) : 41233.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitComplexConditionalAccessReceiver(Microsoft.CodeAnalysis.VisualBasic.BoundComplexConditionalAccessReceiver,bool):this
          11 ( 1.77% of base) : 52484.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitStringSwitchJumpTable(Microsoft.CodeAnalysis.CSharp.BoundSwitchStatement,System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.ConstantValue, System.Object][],Microsoft.CodeAnalysis.CSharp.Symbols.LabelSymbol,Microsoft.CodeAnalysis.CodeGen.LocalOrParameter,Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode):this
          25 ( 1.75% of base) : 42924.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceFile:BindOptions(Microsoft.CodeAnalysis.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.OptionStatementSyntax],Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,byref,byref,byref,byref,System.Nullable`1[Microsoft.CodeAnalysis.Text.TextSpan])
          11 ( 1.74% of base) : 66207.dasm - Microsoft.CodeAnalysis.CSharp.InitializerRewriter:RewriteScriptInitializer(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundInitializer],Microsoft.CodeAnalysis.CSharp.Symbols.SynthesizedInteractiveInitializerMethod,byref):Microsoft.CodeAnalysis.CSharp.BoundTypeOrInstanceInitializers
           2 ( 1.69% of base) : 183886.dasm - Internal.IL.EcmaMethodIL:Create(Internal.TypeSystem.Ecma.EcmaMethod):Internal.IL.EcmaMethodIL
          24 ( 1.68% of base) : 22529.dasm - InferenceGraph:Infer(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundNode,byref,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.BitVector):bool
           2 ( 1.60% of base) : 182736.dasm - Internal.TypeSystem.Ecma.EcmaFieldExtensions:GetFieldRvaValue(Internal.TypeSystem.Ecma.EcmaField):int
           3 ( 1.50% of base) : 203168.dasm - System.Net.Mail.AuthCommand:PrepareCommand(System.Net.Mail.SmtpConnection,System.String,System.String)

Top method improvements (percentages):
         -60 (-68.18% of base) : 13276.dasm - System.Numerics.Matrix3x2:GetHashCode():int:this
         -30 (-66.67% of base) : 13068.dasm - System.Numerics.Vector3:GetHashCode():int:this
         -40 (-64.52% of base) : 13009.dasm - System.Numerics.Vector4:GetHashCode():int:this
         -30 (-62.50% of base) : 111558.dasm - RangeSingle@5487:System.Collections.IEnumerable.GetEnumerator():System.Collections.IEnumerator:this
         -20 (-62.50% of base) : 13124.dasm - System.Numerics.Vector2:GetHashCode():int:this
         -20 (-54.05% of base) : 169649.dasm - System.Drawing.RectangleF:Contains(System.Drawing.PointF):bool:this
         -20 (-54.05% of base) : 169645.dasm - System.Drawing.RectangleF:Inflate(System.Drawing.SizeF):this
         -60 (-44.44% of base) : 121960.dasm - System.Drawing.Drawing2D.Matrix:CreateNativeHandle(System.Numerics.Matrix3x2):int
        -160 (-41.45% of base) : 13224.dasm - System.Numerics.Matrix4x4:GetHashCode():int:this
         -30 (-38.96% of base) : 13215.dasm - System.Numerics.Plane:GetHashCode():int:this
         -61 (-36.53% of base) : 121951.dasm - System.Drawing.Drawing2D.Matrix:set_MatrixElements(System.Numerics.Matrix3x2):this
         -60 (-33.33% of base) : 121962.dasm - System.Drawing.Drawing2D.Matrix:.ctor(System.Numerics.Matrix3x2):this
         -10 (-31.25% of base) : 169586.dasm - System.Drawing.SizeF:GetHashCode():int:this
         -10 (-22.73% of base) : 114274.dasm - u_constSpec@1659-15:Invoke(Microsoft.FSharp.Collections.FSharpList`1[System.Type]):Microsoft.FSharp.Quotations.ExprConstInfo:this
         -10 (-21.74% of base) : 74745.dasm - Newtonsoft.Json.JsonWriter:WriteValue(System.Nullable`1[System.Single]):this
         -11 (-21.15% of base) : 117760.dasm - Microsoft.FSharp.Core.FSharpOption`1:ToString():System.String:this
         -10 (-20.83% of base) : 132799.dasm - System.Data.Common.SingleStorage:ConvertObjectToXml(System.Object):System.String:this
         -20 (-19.80% of base) : 16987.dasm - System.Half:SinCos(System.Half):System.ValueTuple`2[System.Half, System.Half]
         -60 (-19.74% of base) : 122793.dasm - System.Drawing.Graphics:GetContextInfo():System.Object:this
         -10 (-19.61% of base) : 19549.dasm - System.MathF:Truncate(float):float

35510 total methods with Code Size differences (35417 improved, 93 regressed), 1942 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 39502366 (overridden on cmd)
Total bytes of diff: 39447117 (overridden on cmd)
Total bytes of delta: -55249 (-0.14 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         138 : 120154.dasm (4.10% of base)
         132 : 120224.dasm (3.57% of base)
          53 : 217146.dasm (2.18% of base)
          53 : 28798.dasm (1.76% of base)
          43 : 41101.dasm (3.25% of base)
          35 : 38612.dasm (1.35% of base)
          35 : 38613.dasm (1.33% of base)
          31 : 38657.dasm (0.75% of base)
          29 : 181218.dasm (0.67% of base)
          27 : 217144.dasm (2.64% of base)
          25 : 42389.dasm (8.65% of base)
          23 : 150698.dasm (1.10% of base)
          21 : 150667.dasm (1.55% of base)
          21 : 41768.dasm (6.44% of base)
          21 : 41769.dasm (7.34% of base)
          21 : 41770.dasm (7.34% of base)
          17 : 33341.dasm (0.34% of base)
          17 : 108286.dasm (1.90% of base)
          16 : 58379.dasm (1.33% of base)
          15 : 194728.dasm (2.58% of base)

Top file improvements (bytes):
        -574 : 77012.dasm (-2.42% of base)
        -558 : 86320.dasm (-0.77% of base)
        -407 : 144521.dasm (-1.96% of base)
        -374 : 233091.dasm (-1.91% of base)
        -359 : 78307.dasm (-2.02% of base)
        -294 : 79220.dasm (-4.87% of base)
        -281 : 88999.dasm (-0.96% of base)
        -273 : 195669.dasm (-3.00% of base)
        -234 : 51953.dasm (-14.62% of base)
        -222 : 206189.dasm (-1.98% of base)
        -208 : 206291.dasm (-2.00% of base)
        -206 : 79226.dasm (-4.81% of base)
        -192 : 142578.dasm (-2.05% of base)
        -175 : 207133.dasm (-4.94% of base)
        -173 : 185141.dasm (-4.61% of base)
        -171 : 87260.dasm (-0.84% of base)
        -163 : 172652.dasm (-1.63% of base)
        -160 : 87533.dasm (-0.87% of base)
        -159 : 206364.dasm (-1.48% of base)
        -144 : 144918.dasm (-2.93% of base)

23636 total files with Code Size differences (23568 improved, 68 regressed), 1770 unchanged.

Top method regressions (bytes):
         138 ( 4.10% of base) : 120154.dasm - System.Data.Common.SqlDoubleStorage:Aggregate(System.Int32[],int):System.Object:this
         132 ( 3.57% of base) : 120224.dasm - System.Data.Common.SqlMoneyStorage:Aggregate(System.Int32[],int):System.Object:this
          53 ( 1.76% of base) : 28798.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitDelegateCreation(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression,bool,Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,bool):this
          53 ( 2.18% of base) : 217146.dasm - System.Management.ManagementClassGenerator:GenerateSystemPropertiesClass():System.CodeDom.CodeTypeDeclaration:this
          43 ( 3.25% of base) : 41101.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseRedimStatement():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.StatementSyntax:this
          35 ( 1.35% of base) : 38612.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitFieldInfoExpression(Microsoft.CodeAnalysis.VisualBasic.BoundFieldInfo,bool):this
          35 ( 1.33% of base) : 38613.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitMethodInfoExpression(Microsoft.CodeAnalysis.VisualBasic.BoundMethodInfo,bool):this
          31 ( 0.75% of base) : 38657.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess,bool):this
          29 ( 0.67% of base) : 181218.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeAutoFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          27 ( 2.64% of base) : 217144.dasm - System.Management.ManagementClassGenerator:GeneratePublicProperty(System.String,System.String,System.CodeDom.CodeExpression,bool,System.String,bool):this
          25 ( 8.65% of base) : 42389.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.FloatingLiteralTokenSyntax`1[__Canon][System.__Canon]:WithTrailingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this
          23 ( 1.10% of base) : 150698.dasm - System.Xml.Serialization.XmlSerializationWriterILGen:WriteArrayItems(System.Xml.Serialization.ElementAccessor[],System.Xml.Serialization.TextAccessor,System.Xml.Serialization.ChoiceIdentifierAccessor,System.Xml.Serialization.TypeDesc,System.String,System.String):this
          21 ( 7.34% of base) : 41770.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          21 ( 7.34% of base) : 41769.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          21 ( 6.44% of base) : 41768.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:WithTrailingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this
          21 ( 1.55% of base) : 150667.dasm - System.Xml.Serialization.XmlSerializationWriterCodeGen:FindChoiceEnumValue(System.Xml.Serialization.ElementAccessor,System.Xml.Serialization.EnumMapping,bool):System.String
          17 ( 1.90% of base) : 108286.dasm - Microsoft.Build.Construction.SolutionProjectGenerator:EvaluateAndAddProjects(System.Collections.Generic.List`1[[Microsoft.Build.Construction.ProjectInSolution, Microsoft.Build, Version=15.1.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Collections.Generic.List`1[[Microsoft.Build.Execution.ProjectInstance, Microsoft.Build, Version=15.1.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],Microsoft.Build.Execution.ProjectInstance,System.String):this
          17 ( 0.34% of base) : 33341.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,ushort,int,bool,Microsoft.CodeAnalysis.DiagnosticBag,bool,byref):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          16 ( 1.33% of base) : 58379.dasm - InferenceGraph:Infer(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[Int32],Microsoft.CodeAnalysis.ArrayBuilder`1[Int32],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundNode,byref,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.BitVector):bool
          15 ( 4.49% of base) : 41767.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:WithLeadingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this

Top method improvements (bytes):
        -574 (-2.42% of base) : 77012.dasm - Microsoft.CodeAnalysis.DesktopAssemblyIdentityComparer:.cctor()
        -558 (-0.77% of base) : 86320.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServerTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -407 (-1.96% of base) : 144521.dasm - System.Xml.Schema.XsdBuilder:.cctor()
        -374 (-1.91% of base) : 233091.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -359 (-2.02% of base) : 78307.dasm - Microsoft.CodeAnalysis.AttributeDescription:.cctor()
        -294 (-4.87% of base) : 79220.dasm - Microsoft.CodeAnalysis.WellKnownMembers:.cctor()
        -281 (-0.96% of base) : 88999.dasm - Microsoft.Diagnostics.Tracing.Parsers.KernelTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -273 (-3.00% of base) : 195669.dasm - CultureInfoMapper:CreateMap():System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
        -234 (-14.62% of base) : 51953.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:ResolveUserDefinedBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,int,Microsoft.CodeAnalysis.VisualBasic.Binder,byref,bool):OverloadResolutionResult
        -222 (-1.98% of base) : 206189.dasm - System.DirectoryServices.AccountManagement.ADStoreCtx:.cctor()
        -208 (-2.00% of base) : 206291.dasm - System.DirectoryServices.AccountManagement.ADAMStoreCtx:.cctor()
        -206 (-4.81% of base) : 79226.dasm - Microsoft.CodeAnalysis.WellKnownTypes:.cctor()
        -192 (-2.05% of base) : 142578.dasm - System.Xml.Schema.DatatypeImplementation:.cctor()
        -175 (-4.94% of base) : 207133.dasm - System.Drawing.KnownColorNames:.cctor()
        -173 (-4.61% of base) : 185141.dasm - Microsoft.VisualBasic.VBCodeGenerator:.cctor()
        -171 (-0.84% of base) : 87260.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrPrivateTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -163 (-1.63% of base) : 172652.dasm - Microsoft.CSharp.RuntimeBinder.Semantics.PredefinedMembers:.cctor()
        -160 (-0.87% of base) : 87533.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -159 (-1.48% of base) : 206364.dasm - System.DirectoryServices.AccountManagement.SAMStoreCtx:.cctor()
        -144 (-2.93% of base) : 144918.dasm - System.Xml.Xsl.XmlQueryCardinality:.cctor()

Top method regressions (percentages):
          25 ( 8.65% of base) : 42389.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.FloatingLiteralTokenSyntax`1[__Canon][System.__Canon]:WithTrailingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this
          14 ( 7.91% of base) : 76306.dasm - Microsoft.CodeAnalysis.MergedAliases:AddNonIncluded(Microsoft.CodeAnalysis.ArrayBuilder`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
          21 ( 7.34% of base) : 41770.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          21 ( 7.34% of base) : 41769.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          21 ( 6.44% of base) : 41768.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:WithTrailingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this
          12 ( 6.32% of base) : 25707.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MemberSignatureComparer:HaveSameConstraints(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.Symbols.TypeMap,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.Symbols.TypeMap):bool
          15 ( 4.49% of base) : 41767.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ComplexIdentifierSyntax:WithLeadingTrivia(Microsoft.CodeAnalysis.GreenNode):Microsoft.CodeAnalysis.GreenNode:this
         138 ( 4.10% of base) : 120154.dasm - System.Data.Common.SqlDoubleStorage:Aggregate(System.Int32[],int):System.Object:this
          13 ( 3.98% of base) : 37890.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SubstitutedNamedType:MakeAcyclicInterfaces(Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          13 ( 3.87% of base) : 37888.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SubstitutedNamedType:MakeDeclaredInterfaces(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         132 ( 3.57% of base) : 120224.dasm - System.Data.Common.SqlMoneyStorage:Aggregate(System.Int32[],int):System.Object:this
          43 ( 3.25% of base) : 41101.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseRedimStatement():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.StatementSyntax:this
           7 ( 2.82% of base) : 226946.dasm - System.Xml.Linq.ElementWriter:PushElement(System.Xml.Linq.XElement):this
          27 ( 2.64% of base) : 217144.dasm - System.Management.ManagementClassGenerator:GeneratePublicProperty(System.String,System.String,System.CodeDom.CodeExpression,bool,System.String,bool):this
          15 ( 2.58% of base) : 194728.dasm - System.Drawing.RectangleConverter:ConvertFrom(System.ComponentModel.ITypeDescriptorContext,System.Globalization.CultureInfo,System.Object):System.Object:this
           3 ( 2.46% of base) : 170643.dasm - ILCompiler.Reflection.ReadyToRun.NativeHashtable:EnumerateAllEntries():AllEntriesEnumerator:this
          53 ( 2.18% of base) : 217146.dasm - System.Management.ManagementClassGenerator:GenerateSystemPropertiesClass():System.CodeDom.CodeTypeDeclaration:this
          12 ( 2.09% of base) : 122121.dasm - System.Drawing.Printing.MarginsConverter:ConvertFrom(System.ComponentModel.ITypeDescriptorContext,System.Globalization.CultureInfo,System.Object):System.Object:this
           9 ( 2.02% of base) : 161077.dasm - System.Speech.Internal.SrgsParser.XmlParser:ParseText(System.Speech.Internal.SrgsParser.IElement,System.String,System.String,System.String,float,System.Speech.Internal.SrgsParser.CreateTokenCallback)
          17 ( 1.90% of base) : 108286.dasm - Microsoft.Build.Construction.SolutionProjectGenerator:EvaluateAndAddProjects(System.Collections.Generic.List`1[[Microsoft.Build.Construction.ProjectInSolution, Microsoft.Build, Version=15.1.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Collections.Generic.List`1[[Microsoft.Build.Execution.ProjectInstance, Microsoft.Build, Version=15.1.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],Microsoft.Build.Execution.ProjectInstance,System.String):this

Top method improvements (percentages):
         -83 (-69.17% of base) : 120946.dasm - System.Drawing.Graphics:DrawBezier(System.Drawing.Pen,System.Drawing.PointF,System.Drawing.PointF,System.Drawing.PointF,System.Drawing.PointF):this
         -33 (-64.71% of base) : 73111.dasm - RangeSingle@5487:System.Collections.Generic.IEnumerable<System.Single>.GetEnumerator():System.Collections.Generic.IEnumerator`1[Single]:this
         -43 (-63.24% of base) : 120898.dasm - System.Drawing.Graphics:DrawEllipse(System.Drawing.Pen,System.Drawing.RectangleF):this
         -43 (-63.24% of base) : 120850.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.RectangleF):this
         -43 (-63.24% of base) : 120827.dasm - System.Drawing.Graphics:DrawLine(System.Drawing.Pen,System.Drawing.PointF,System.Drawing.PointF):this
         -43 (-63.24% of base) : 120948.dasm - System.Drawing.Graphics:DrawRectangle(System.Drawing.Pen,System.Drawing.RectangleF):this
         -43 (-63.24% of base) : 120875.dasm - System.Drawing.Graphics:FillEllipse(System.Drawing.Brush,System.Drawing.RectangleF):this
         -43 (-63.24% of base) : 120921.dasm - System.Drawing.Graphics:FillRectangle(System.Drawing.Brush,System.Drawing.RectangleF):this
         -23 (-57.50% of base) : 120848.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.PointF):this
         -23 (-57.50% of base) : 207219.dasm - System.Drawing.RectangleF:Contains(System.Drawing.PointF):bool:this
         -63 (-45.65% of base) : 121853.dasm - System.Drawing.Drawing2D.Matrix:set_MatrixElements(System.Numerics.Matrix3x2):this
         -40 (-42.55% of base) : 120942.dasm - System.Drawing.Graphics:DrawArc(System.Drawing.Pen,System.Drawing.RectangleF,float,float):this
         -40 (-42.55% of base) : 120902.dasm - System.Drawing.Graphics:DrawPie(System.Drawing.Pen,System.Drawing.RectangleF,float,float):this
         -40 (-42.55% of base) : 120880.dasm - System.Drawing.Graphics:FillPie(System.Drawing.Brush,System.Drawing.RectangleF,float,float):this
         -43 (-38.39% of base) : 121992.dasm - System.Drawing.Drawing2D.GraphicsPath:AddRectangle(System.Drawing.RectangleF):this
         -43 (-37.72% of base) : 120968.dasm - System.Drawing.Graphics:SetClip(System.Drawing.RectangleF,int):this
         -43 (-36.75% of base) : 120973.dasm - System.Drawing.Graphics:IntersectClip(System.Drawing.RectangleF):this
         -43 (-33.59% of base) : 120931.dasm - System.Drawing.Graphics:IsVisible(System.Drawing.RectangleF):bool:this
         -10 (-28.57% of base) : 207306.dasm - System.Drawing.SizeF:GetHashCode():int:this
         -13 (-28.26% of base) : 66629.dasm - u_constSpec@1659-15:Invoke(Microsoft.FSharp.Collections.FSharpList`1[[System.Type, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.FSharp.Quotations.ExprConstInfo:this

23636 total methods with Code Size differences (23568 improved, 68 regressed), 1770 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 96295370 (overridden on cmd)
Total bytes of diff: 96152994 (overridden on cmd)
Total bytes of delta: -142376 (-0.15 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         461 : 161519.dasm (5.87% of base)
         461 : 161563.dasm (5.87% of base)
         275 : 162553.dasm (8.68% of base)
         232 : 37315.dasm (3.99% of base)
         133 : 354557.dasm (6.78% of base)
          88 : 278128.dasm (1.10% of base)
          83 : 293069.dasm (1.92% of base)
          68 : 161529.dasm (3.79% of base)
          68 : 161574.dasm (3.79% of base)
          62 : 261831.dasm (4.77% of base)
          61 : 203534.dasm (1.41% of base)
          55 : 96131.dasm (3.71% of base)
          52 : 219811.dasm (7.14% of base)
          48 : 329259.dasm (2.30% of base)
          34 : 212203.dasm (0.68% of base)
          34 : 207919.dasm (0.68% of base)
          32 : 161502.dasm (1.34% of base)
          32 : 314184.dasm (1.29% of base)
          32 : 314186.dasm (1.29% of base)
          32 : 161543.dasm (1.34% of base)

Top file improvements (bytes):
      -13294 : 306171.dasm (-2.35% of base)
       -4931 : 157369.dasm (-1.49% of base)
       -4111 : 203764.dasm (-2.26% of base)
       -2010 : 203661.dasm (-2.40% of base)
       -1314 : 136927.dasm (-4.99% of base)
       -1169 : 118513.dasm (-0.65% of base)
       -1107 : 203951.dasm (-2.10% of base)
        -852 : 331719.dasm (-2.19% of base)
        -645 : 338995.dasm (-3.40% of base)
        -483 : 237855.dasm (-1.57% of base)
        -399 : 339042.dasm (-3.67% of base)
        -376 : 346790.dasm (-1.85% of base)
        -374 : 292744.dasm (-1.91% of base)
        -343 : 272847.dasm (-53.10% of base)
        -320 : 254784.dasm (-2.38% of base)
        -314 : 351706.dasm (-4.92% of base)
        -309 : 281521.dasm (-2.57% of base)
        -233 : 280960.dasm (-1.59% of base)
        -229 : 319465.dasm (-1.73% of base)
        -214 : 162887.dasm (-0.31% of base)

46926 total files with Code Size differences (46829 improved, 97 regressed), 2323 unchanged.

Top method regressions (bytes):
         461 ( 5.87% of base) : 161563.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:MetadataAttributes():this
         461 ( 5.87% of base) : 161519.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:MetadataAttributes():this
         275 ( 8.68% of base) : 162553.dasm - <>c__DisplayClass164_0:<OutputAttributeDeclarations_NonEmptyAttributes_Success>b__0(System.IO.StringWriter):this
         232 ( 3.99% of base) : 37315.dasm - System.Text.Json.Tests.JsonDocumentTests:GetPropertyFindsLast_WithEscaping(System.String)
         133 ( 6.78% of base) : 354557.dasm - Microsoft.Test.ModuleCore.KeywordParser:ParseKeywords(System.String,Tokens):System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
          88 ( 1.10% of base) : 278128.dasm - System.Reflection.Metadata.Decoding.Tests.SignatureDecoderTests:SimpleSignatureProviderCoverage():this
          83 ( 1.92% of base) : 293069.dasm - <>c__DisplayClass16_0:<EmitTryMatchAtCurrentPosition>g__EmitSingleCharAtomicLoop|30(System.Text.RegularExpressions.RegexNode,bool):this
          68 ( 3.79% of base) : 161574.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:Params():this
          68 ( 3.79% of base) : 161529.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:Params():this
          62 ( 4.77% of base) : 261831.dasm - System.IO.Ports.Tests.ReadChar:Read_Timeout():this
          61 ( 1.41% of base) : 203534.dasm - System.Text.RegularExpressions.Tests.RegexExperiment:PasswordSearchDual():this
          55 ( 3.71% of base) : 96131.dasm - System.Runtime.CompilerServices.Tests.DefaultInterpolatedStringHandlerTests:AppendFormatted_ReferenceTypes_ICustomFormatter():this
          52 ( 7.14% of base) : 219811.dasm - DryIoc.Container:CombineRegisteredWithDynamicFactories(ubyte,ubyte,ImTools.KV`2[System.Object,DryIoc.Factory][],bool,int,System.Type,System.Object):ImTools.KV`2[System.Object,DryIoc.Factory][]:this
          48 ( 2.30% of base) : 329259.dasm - System.Diagnostics.Tests.ProviderMetadataTests:ProviderNameTests(bool):this
          34 ( 0.68% of base) : 212203.dasm - System.Data.SqlClient.TdsParser:TdsLogin(System.Data.SqlClient.SqlLogin,int,System.Data.SqlClient.SessionData,System.Nullable`1[FederatedAuthenticationFeatureExtensionData]):this
          34 ( 0.68% of base) : 207919.dasm - System.Data.SqlClient.TdsParser:TdsLogin(System.Data.SqlClient.SqlLogin,int,System.Data.SqlClient.SessionData,System.Nullable`1[FederatedAuthenticationFeatureExtensionData]):this
          32 ( 1.29% of base) : 314184.dasm - <DisposeAsync_DisposesAppConfigurationProviders>d__43:MoveNext():this
          32 ( 1.29% of base) : 314186.dasm - <DisposeAsync_DisposesHostConfigurationProviders>d__44:MoveNext():this
          32 ( 1.34% of base) : 161543.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:GenericTypesAndConstraints():this
          32 ( 1.34% of base) : 161502.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:GenericTypesAndConstraints():this

Top method improvements (bytes):
      -13294 (-2.35% of base) : 306171.dasm - CoreXml.Test.XLinq.InputSpace:Hamlet(byref,byref)
       -4931 (-1.49% of base) : 157369.dasm - <Compare_Primitives_TestData>d__139:MoveNext():bool:this
       -4111 (-2.26% of base) : 203764.dasm - <Groups_Basic_TestData>d__0:MoveNext():bool:this
       -2010 (-2.40% of base) : 203661.dasm - <<ValidateRegex_MemberData>g__Cases|1_0>d:MoveNext():bool:this
       -1314 (-4.99% of base) : 136927.dasm - <StartupCode$FsCheck>.$Data:.cctor()
       -1169 (-0.65% of base) : 118513.dasm - <SerializableObjects>d__3:MoveNext():bool:this
       -1107 (-2.10% of base) : 203951.dasm - <<Match_MemberData>g__Cases|0_0>d:MoveNext():bool:this
        -852 (-2.19% of base) : 331719.dasm - System.Drawing.Primitives.Tests.ColorTests:.cctor()
        -645 (-3.40% of base) : 338995.dasm - System.Net.Primitives.Functional.Tests.IPAddressParsing:.cctor()
        -483 (-1.57% of base) : 237855.dasm - NuGet.Packaging.Licenses.NuGetLicenseData:.cctor()
        -399 (-3.67% of base) : 339042.dasm - System.Net.Primitives.Functional.Tests.IPEndPointParsing:.cctor()
        -376 (-1.85% of base) : 346790.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -374 (-1.91% of base) : 292744.dasm - System.Text.RegularExpressions.RegexCharClass:.cctor()
        -343 (-53.10% of base) : 272847.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Matrix4x4,System.Numerics.Matrix4x4):bool
        -320 (-2.38% of base) : 254784.dasm - System.Formats.Asn1.Tests.Asn1TagTests:.cctor()
        -314 (-4.92% of base) : 351706.dasm - System.Xml.Tests.XmlBaseCharConvertTests:.cctor()
        -309 (-2.57% of base) : 281521.dasm - System.IO.Tests.PathTests_Join:.cctor()
        -233 (-1.59% of base) : 280960.dasm - <Invoke_TestData>d__17:MoveNext():bool:this
        -229 (-1.73% of base) : 319465.dasm - Microsoft.Win32.RegistryTests.TestData:.cctor()
        -214 (-0.31% of base) : 162887.dasm - <GenerateCodeFromType_TestData>d__25:MoveNext():bool:this

Top method regressions (percentages):
         275 ( 8.68% of base) : 162553.dasm - <>c__DisplayClass164_0:<OutputAttributeDeclarations_NonEmptyAttributes_Success>b__0(System.IO.StringWriter):this
          52 ( 7.14% of base) : 219811.dasm - DryIoc.Container:CombineRegisteredWithDynamicFactories(ubyte,ubyte,ImTools.KV`2[System.Object,DryIoc.Factory][],bool,int,System.Type,System.Object):ImTools.KV`2[System.Object,DryIoc.Factory][]:this
         133 ( 6.78% of base) : 354557.dasm - Microsoft.Test.ModuleCore.KeywordParser:ParseKeywords(System.String,Tokens):System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
         461 ( 5.87% of base) : 161563.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:MetadataAttributes():this
         461 ( 5.87% of base) : 161519.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:MetadataAttributes():this
          62 ( 4.77% of base) : 261831.dasm - System.IO.Ports.Tests.ReadChar:Read_Timeout():this
         232 ( 3.99% of base) : 37315.dasm - System.Text.Json.Tests.JsonDocumentTests:GetPropertyFindsLast_WithEscaping(System.String)
          68 ( 3.79% of base) : 161574.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:Params():this
          68 ( 3.79% of base) : 161529.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:Params():this
          55 ( 3.71% of base) : 96131.dasm - System.Runtime.CompilerServices.Tests.DefaultInterpolatedStringHandlerTests:AppendFormatted_ReferenceTypes_ICustomFormatter():this
          16 ( 2.66% of base) : 81074.dasm - System.Linq.Expressions.Tests.TernaryNullableTests:CheckTernaryNullableUIntTest(bool)
          18 ( 2.64% of base) : 76863.dasm - System.Linq.Expressions.Tests.ConvertCheckedTests:ConvertCheckedDecimalToDoubleTest(bool)
          18 ( 2.64% of base) : 78449.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertDecimalToDoubleTest(bool)
          16 ( 2.55% of base) : 81062.dasm - System.Linq.Expressions.Tests.TernaryNullableTests:CheckTernaryNullableEnumTest(bool)
          16 ( 2.55% of base) : 81065.dasm - System.Linq.Expressions.Tests.TernaryNullableTests:CheckTernaryNullableIntTest(bool)
          28 ( 2.36% of base) : 278468.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:ValidateInterfaceImplTable():this
          48 ( 2.30% of base) : 329259.dasm - System.Diagnostics.Tests.ProviderMetadataTests:ProviderNameTests(bool):this
          15 ( 2.23% of base) : 76865.dasm - System.Linq.Expressions.Tests.ConvertCheckedTests:ConvertCheckedDecimalToFloatTest(bool)
          15 ( 2.23% of base) : 78451.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertDecimalToFloatTest(bool)
          23 ( 2.19% of base) : 251349.dasm - MonoTests.System.Configuration.ConfigurationManagerTest:TestContext2():this

Top method improvements (percentages):
        -131 (-55.51% of base) : 272848.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Matrix3x2,System.Numerics.Matrix3x2):bool
         -83 (-53.21% of base) : 272850.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Quaternion,System.Numerics.Quaternion):bool
         -83 (-53.21% of base) : 272846.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Vector4,System.Numerics.Vector4):bool
        -343 (-53.10% of base) : 272847.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Matrix4x4,System.Numerics.Matrix4x4):bool
         -63 (-52.50% of base) : 272845.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Vector3,System.Numerics.Vector3):bool
         -43 (-51.19% of base) : 272844.dasm - System.Numerics.MathHelper:Equal(System.Numerics.Vector2,System.Numerics.Vector2):bool
        -120 (-39.09% of base) : 273829.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2GetHashCodeTest():this
         -13 (-35.14% of base) : 106853.dasm - <>c__DisplayClass79_0:<TestFormatterSingle_Invalid>b__0():System.Object:this
         -13 (-35.14% of base) : 184245.dasm - <>c__DisplayClass79_0:<TestFormatterSingle_Invalid>b__0():System.Object:this
        -128 (-33.86% of base) : 273808.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2IdentityTest():this
        -128 (-29.29% of base) : 273812.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2InvertIdentityTest():this
         -13 (-26.53% of base) : 151168.dasm - Microsoft.IdentityModel.Json.JsonWriter:WriteValue(System.Nullable`1[Single]):this
        -128 (-25.55% of base) : 273814.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2InvertRotationTest():this
        -196 (-23.93% of base) : 273811.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2InvertTest():this
          -4 (-23.53% of base) : 15894.dasm - <>c__DisplayClass17_0:<GetOptionPersisters>b__2():System.Threading.Tasks.Task`1[[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Options.IOptionPersister, Microsoft.CodeAnalysis.Workspaces, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
        -132 (-23.40% of base) : 273815.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2InvertScaleTest():this
        -132 (-23.40% of base) : 273813.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2InvertTranslationTest():this
          -6 (-22.22% of base) : 159914.dasm - <>c__DisplayClass2_0:<SearchAsync>b__2(NuGet.Protocol.LocalPackageInfo):NuGet.Protocol.Core.Types.IPackageSearchMetadata:this
          -5 (-21.74% of base) : 159767.dasm - <>c__DisplayClass10_0:<GetCachedCapabilitiesAsync>b__0(System.String):System.Threading.Tasks.Task`1[[NuGet.Protocol.LegacyFeedCapabilityResourceV2Feed+Capabilities, NuGet.Protocol, Version=5.8.0.6930, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -5 (-21.74% of base) : 16302.dasm - <>c__DisplayClass17_0:<FindSourceDeclarationsWithPatternInCurrentProcessAsync>b__0(Microsoft.CodeAnalysis.FindSymbols.SearchQuery):System.Threading.Tasks.Task`1[[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this

46926 total methods with Code Size differences (46829 improved, 97 regressed), 2323 unchanged.

```

</details>

--------------------------------------------------------------------------------

