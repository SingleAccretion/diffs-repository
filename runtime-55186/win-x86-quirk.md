## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 64518
Total bytes of diff: 64568
Total bytes of delta: 50 (0.08% of base)
Total relative delta: -0.18
    diff is a regression.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         176 : 1338.dasm (4.45% of base)
          12 : 12567.dasm (0.06% of base)
           6 : 2339.dasm (0.94% of base)

Top file improvements (bytes):
         -19 : 3231.dasm (-0.16% of base)
         -14 : 1420.dasm (-0.53% of base)
          -9 : 8850.dasm (-0.44% of base)
          -9 : 16382.dasm (-7.09% of base)
          -9 : 8848.dasm (-0.86% of base)
          -9 : 8856.dasm (-1.02% of base)
          -9 : 11706.dasm (-0.74% of base)
          -6 : 16321.dasm (-0.19% of base)
          -6 : 5433.dasm (-0.37% of base)
          -6 : 7166.dasm (-0.39% of base)
          -6 : 7101.dasm (-0.69% of base)
          -5 : 3383.dasm (-0.88% of base)
          -3 : 16173.dasm (-0.19% of base)
          -3 : 17881.dasm (-0.13% of base)
          -3 : 15275.dasm (-0.27% of base)
          -3 : 3209.dasm (-0.56% of base)
          -3 : 4216.dasm (-0.61% of base)
          -3 : 7157.dasm (-0.53% of base)
          -3 : 8849.dasm (-0.53% of base)
          -3 : 17357.dasm (-0.40% of base)

28 total files with Code Size differences (25 improved, 3 regressed), 1 unchanged.

Top method regressions (bytes):
         176 ( 4.45% of base) : 1338.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
          12 ( 0.06% of base) : 12567.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)
           6 ( 0.94% of base) : 2339.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this

Top method improvements (bytes):
         -19 (-0.16% of base) : 3231.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -14 (-0.53% of base) : 1420.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
          -9 (-0.44% of base) : 8850.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-7.09% of base) : 16382.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -9 (-0.86% of base) : 8848.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-1.02% of base) : 8856.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.74% of base) : 11706.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.19% of base) : 16321.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -6 (-0.37% of base) : 5433.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -6 (-0.39% of base) : 7166.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.69% of base) : 7101.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -5 (-0.88% of base) : 3383.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -3 (-0.19% of base) : 16173.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CreateConversion(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -3 (-0.13% of base) : 17881.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindDeclarationStatementParts(Microsoft.CodeAnalysis.CSharp.Syntax.LocalDeclarationStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
          -3 (-0.27% of base) : 15275.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
          -3 (-0.56% of base) : 3209.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
          -3 (-0.61% of base) : 4216.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -3 (-0.53% of base) : 7157.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -3 (-0.53% of base) : 8849.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -3 (-0.40% of base) : 17357.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this

Top method regressions (percentages):
         176 ( 4.45% of base) : 1338.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
           6 ( 0.94% of base) : 2339.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
          12 ( 0.06% of base) : 12567.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)

Top method improvements (percentages):
          -9 (-7.09% of base) : 16382.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.76% of base) : 16655.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -9 (-1.02% of base) : 8856.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.95% of base) : 2949.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:CreateProperty(System.Reflection.MemberInfo,int):Newtonsoft.Json.Serialization.JsonProperty:this
          -5 (-0.88% of base) : 3383.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -9 (-0.86% of base) : 8848.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.74% of base) : 11706.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.69% of base) : 7101.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.61% of base) : 4216.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -3 (-0.56% of base) : 3209.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
         -14 (-0.53% of base) : 1420.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
          -3 (-0.53% of base) : 7157.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -3 (-0.53% of base) : 8849.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -3 (-0.53% of base) : 8851.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -9 (-0.44% of base) : 8850.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.40% of base) : 17357.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this
          -6 (-0.39% of base) : 7166.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.37% of base) : 5433.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -3 (-0.27% of base) : 15275.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
          -3 (-0.20% of base) : 8473.dasm - Sigil.Impl.VerifiableTracker:GetLegalTransitions(Sigil.Impl.LinqList`1[[Sigil.Impl.StackTransition, Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]],Sigil.Impl.LinqStack`1[[Sigil.Impl.LinqList`1[[Sigil.Impl.TypeOnStack, Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]], Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]]):Sigil.Impl.LinqList`1[[Sigil.Impl.StackTransition, Sigil, Version=5.0.0.0, Culture=neutral, PublicKeyToken=2d06c3494341c8ab]]:this

28 total methods with Code Size differences (25 improved, 3 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 173116
Total bytes of diff: 173209
Total bytes of delta: 93 (0.05% of base)
Total relative delta: -1.45
    diff is a regression.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         136 : 218800.dasm (0.17% of base)
         136 : 218794.dasm (0.17% of base)
           2 : 91.dasm (0.31% of base)

Top file improvements (bytes):
         -21 : 86080.dasm (-3.66% of base)
         -11 : 223705.dasm (-0.30% of base)
          -9 : 223706.dasm (-4.25% of base)
          -8 : 86352.dasm (-1.23% of base)
          -3 : 167467.dasm (-0.49% of base)
          -3 : 170337.dasm (-2.65% of base)
          -3 : 170332.dasm (-2.91% of base)
          -3 : 172579.dasm (-2.91% of base)
          -3 : 214474.dasm (-2.91% of base)
          -3 : 231365.dasm (-4.62% of base)
          -3 : 231370.dasm (-3.85% of base)
          -3 : 167470.dasm (-0.49% of base)
          -3 : 170338.dasm (-2.70% of base)
          -3 : 172581.dasm (-2.73% of base)
          -3 : 223290.dasm (-0.08% of base)
          -3 : 231366.dasm (-4.41% of base)
          -3 : 170333.dasm (-3.00% of base)
          -3 : 172575.dasm (-2.33% of base)
          -3 : 172582.dasm (-2.65% of base)
          -3 : 223684.dasm (-1.42% of base)

51 total files with Code Size differences (48 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
         136 ( 0.17% of base) : 218800.dasm - testout1:Func_0():int
         136 ( 0.17% of base) : 218794.dasm - testout1:Func_0():int
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this

Top method improvements (bytes):
         -21 (-3.66% of base) : 86080.dasm - ILGEN_0xace3f910:Method_0xf9cc7d6a(long,long,float,int,ushort,int,long,long,long):float
         -11 (-0.30% of base) : 223705.dasm - GCSimulator.ClientSimulator:RunTest()
          -9 (-4.25% of base) : 223706.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -8 (-1.23% of base) : 86352.dasm - DevDiv_605447:ILGEN_METHOD(int,int,int,ushort,float):ushort
          -3 (-0.49% of base) : 167467.dasm - ILVerification.Tests.ILMethodTester:TestMethodsWithInvalidIL(ILVerification.Tests.InvalidILTestCase):this
          -3 (-2.65% of base) : 170337.dasm - NullableTest2:BoxUnboxToNQGen(System.Numerics.Vector`1[Single]):bool
          -3 (-2.91% of base) : 170332.dasm - NullableTest2:BoxUnboxToNQGen(System.__Canon):bool
          -3 (-2.91% of base) : 172579.dasm - NullableTest2:BoxUnboxToNQGen(short):bool
          -3 (-2.91% of base) : 214474.dasm - NullableTest7:BoxUnboxToNQ(System.IComparable):bool
          -3 (-4.62% of base) : 231365.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -3 (-3.85% of base) : 231370.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -3 (-0.49% of base) : 167470.dasm - ILVerification.Tests.ILTypeVerificationTester:TestInvalidTypes(ILVerification.Tests.InvalidTypeTestCase):this
          -3 (-2.70% of base) : 170338.dasm - NullableTest2:BoxUnboxToNQGen(long):bool
          -3 (-2.73% of base) : 172581.dasm - NullableTest2:BoxUnboxToNQGen(double):bool
          -3 (-0.08% of base) : 223290.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbMethodDebugInformation2():this
          -3 (-4.41% of base) : 231366.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -3 (-3.00% of base) : 170333.dasm - NullableTest2:BoxUnboxToNQGen(ubyte):bool
          -3 (-2.33% of base) : 172575.dasm - NullableTest2:BoxUnboxToNQ(System.Object):bool
          -3 (-2.65% of base) : 172582.dasm - NullableTest2:BoxUnboxToNQGen(System.Numerics.Vector`1[Single]):bool
          -3 (-1.42% of base) : 223684.dasm - GCSimulator.ClientSimulator:objectDied(LifeTimeFX.LifeTime,int)

Top method regressions (percentages):
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
         136 ( 0.17% of base) : 218800.dasm - testout1:Func_0():int
         136 ( 0.17% of base) : 218794.dasm - testout1:Func_0():int

Top method improvements (percentages):
          -3 (-5.17% of base) : 229539.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -3 (-5.17% of base) : 230012.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool
          -3 (-5.17% of base) : 230429.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -3 (-4.62% of base) : 231365.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -3 (-4.62% of base) : 230013.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -3 (-4.48% of base) : 230015.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -3 (-4.48% of base) : 231367.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -3 (-4.41% of base) : 231366.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -3 (-4.41% of base) : 230014.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -3 (-4.29% of base) : 231428.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -9 (-4.25% of base) : 223706.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -3 (-3.95% of base) : 231368.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -3 (-3.95% of base) : 230016.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -3 (-3.85% of base) : 231370.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -3 (-3.85% of base) : 230018.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -3 (-3.80% of base) : 230017.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -3 (-3.80% of base) : 231369.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
         -21 (-3.66% of base) : 86080.dasm - ILGEN_0xace3f910:Method_0xf9cc7d6a(long,long,float,int,ushort,int,long,long,long):float
          -3 (-3.26% of base) : 230780.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -3 (-3.26% of base) : 231364.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool

51 total methods with Code Size differences (48 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 285275
Total bytes of diff: 283532
Total bytes of delta: -1743 (-0.61% of base)
Total relative delta: -7.22
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           6 : 209266.dasm (1.37% of base)
           3 : 180290.dasm (0.88% of base)
           2 : 190184.dasm (1.50% of base)
           2 : 190185.dasm (1.50% of base)

Top file improvements (bytes):
         -15 : 130334.dasm (-0.38% of base)
         -15 : 207607.dasm (-0.84% of base)
         -15 : 79435.dasm (-0.61% of base)
         -12 : 190274.dasm (-3.17% of base)
         -12 : 85901.dasm (-0.55% of base)
         -12 : 79423.dasm (-0.55% of base)
         -12 : 79384.dasm (-0.34% of base)
         -12 : 79455.dasm (-2.89% of base)
         -12 : 86183.dasm (-0.68% of base)
         -11 : 82264.dasm (-1.44% of base)
         -10 : 152662.dasm (-0.98% of base)
         -10 : 170096.dasm (-4.95% of base)
          -9 : 133146.dasm (-0.25% of base)
          -9 : 149594.dasm (-0.48% of base)
          -9 : 160746.dasm (-0.42% of base)
          -9 : 160756.dasm (-0.41% of base)
          -9 : 133127.dasm (-0.25% of base)
          -9 : 79271.dasm (-0.61% of base)
          -9 : 62370.dasm (-1.19% of base)
          -9 : 79448.dasm (-0.61% of base)

450 total files with Code Size differences (446 improved, 4 regressed), 0 unchanged.

Top method regressions (bytes):
           6 ( 1.37% of base) : 209266.dasm - System.Linq.Parallel.TakeOrSkipWhileQueryOperator`1:WrapHelper(System.Linq.Parallel.PartitionedStream`2[System.__Canon, System.__Canon],System.Linq.Parallel.IPartitionedStreamRecipient`1[System.__Canon],System.Linq.Parallel.QuerySettings):this
           3 ( 0.88% of base) : 180290.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           2 ( 1.50% of base) : 190184.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           2 ( 1.50% of base) : 190185.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this

Top method improvements (bytes):
         -15 (-0.38% of base) : 130334.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -15 (-0.84% of base) : 207607.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -15 (-0.61% of base) : 79435.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
         -12 (-3.17% of base) : 190274.dasm - System.Security.AccessControl.ObjectSecurity:UpdateWithNewSecurityDescriptor(System.Security.AccessControl.RawSecurityDescriptor,int):this
         -12 (-0.55% of base) : 85901.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -12 (-0.55% of base) : 79423.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-0.34% of base) : 79384.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-2.89% of base) : 79455.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.68% of base) : 86183.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -11 (-1.44% of base) : 82264.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
         -10 (-0.98% of base) : 152662.dasm - System.Xml.Schema.ParticleContentValidator:Finish(bool):System.Xml.Schema.ContentValidator:this
         -10 (-4.95% of base) : 170096.dasm - CommandLine.Text.HelpText:AddOptionName(int,CommandLine.Core.OptionSpecification):System.String:this
          -9 (-0.25% of base) : 133146.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:CompileMethod(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,int,byref,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.TypeCompilationState):this
          -9 (-0.48% of base) : 149594.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadDecimalFormat(System.Xml.Xsl.Xslt.NsDecl):this
          -9 (-0.42% of base) : 160746.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
          -9 (-0.41% of base) : 160756.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AndObject(System.Object,System.Object):System.Object
          -9 (-0.25% of base) : 133127.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.CSharp.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.CSharp.CSharpCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock
          -9 (-0.61% of base) : 79271.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitUsingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUsingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-1.19% of base) : 62370.dasm - RetargetedTypeMethodFinder:FindWorker(Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingModuleSymbol+RetargetingSymbolTranslator,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
          -9 (-0.61% of base) : 79448.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitBottomConditionLoop(Microsoft.CodeAnalysis.VisualBasic.BoundDoLoopStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method regressions (percentages):
           2 ( 1.50% of base) : 190184.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           2 ( 1.50% of base) : 190185.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this
           6 ( 1.37% of base) : 209266.dasm - System.Linq.Parallel.TakeOrSkipWhileQueryOperator`1:WrapHelper(System.Linq.Parallel.PartitionedStream`2[System.__Canon, System.__Canon],System.Linq.Parallel.IPartitionedStreamRecipient`1[System.__Canon],System.Linq.Parallel.QuerySettings):this
           3 ( 0.88% of base) : 180290.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this

Top method improvements (percentages):
          -3 (-13.64% of base) : 117728.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
          -6 (-9.52% of base) : 86996.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-7.89% of base) : 87571.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -3 (-7.14% of base) : 117033.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-6.82% of base) : 87038.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.67% of base) : 87037.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.52% of base) : 63490.dasm - LocalVariableSubstituter:VisitLocal(Microsoft.CodeAnalysis.VisualBasic.BoundLocal):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.00% of base) : 134141.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-6.00% of base) : 87030.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -6 (-6.00% of base) : 110934.dasm - leftJustify@875-4:Invoke(System.String,int,System.Object):System.String:this
          -3 (-5.88% of base) : 170313.dasm - CommandLine.NamedError:GetHashCode():int:this
          -3 (-5.88% of base) : 170318.dasm - CommandLine.TokenError:GetHashCode():int:this
          -3 (-5.77% of base) : 54960.dasm - Microsoft.CodeAnalysis.PreprocessingSymbolInfo:GetHashCode():int:this
          -5 (-5.75% of base) : 216009.dasm - CredentialEnumerator:MoveNext():bool:this
          -3 (-5.17% of base) : 28792.dasm - TryWriteInterpolatedStringHandler:.ctor(int,int,System.Span`1[System.Char],byref):this
          -3 (-5.08% of base) : 170272.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[System.String],System.Collections.Generic.IEnumerable`1[CommandLine.Core.OptionSpecification],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[System.Collections.Generic.IEnumerable`1[CommandLine.Core.Token], CommandLine.Error]
         -10 (-4.95% of base) : 170096.dasm - CommandLine.Text.HelpText:AddOptionName(int,CommandLine.Core.OptionSpecification):System.String:this
          -6 (-4.65% of base) : 121813.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -6 (-4.65% of base) : 121814.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -3 (-4.62% of base) : 133665.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:FilterAndAppendAndFreeDiagnostics(Microsoft.CodeAnalysis.DiagnosticBag,byref):bool:this

450 total methods with Code Size differences (446 improved, 4 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 256043
Total bytes of diff: 254293
Total bytes of delta: -1750 (-0.68% of base)
Total relative delta: -7.96
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          14 : 72007.dasm (0.44% of base)
           3 : 214336.dasm (2.13% of base)
           3 : 214337.dasm (2.13% of base)
           3 : 207649.dasm (1.09% of base)
           2 : 91.dasm (0.31% of base)
           1 : 143569.dasm (0.57% of base)

Top file improvements (bytes):
         -20 : 206204.dasm (-1.20% of base)
         -19 : 147712.dasm (-0.16% of base)
         -12 : 109133.dasm (-0.23% of base)
         -12 : 49358.dasm (-0.42% of base)
         -12 : 214181.dasm (-2.05% of base)
         -12 : 56654.dasm (-8.96% of base)
         -12 : 56183.dasm (-1.74% of base)
         -12 : 189938.dasm (-0.46% of base)
         -11 : 49083.dasm (-0.29% of base)
          -9 : 192080.dasm (-0.36% of base)
          -9 : 192081.dasm (-0.70% of base)
          -9 : 143566.dasm (-0.48% of base)
          -9 : 39385.dasm (-3.18% of base)
          -9 : 39386.dasm (-3.18% of base)
          -9 : 135348.dasm (-2.38% of base)
          -9 : 39411.dasm (-3.18% of base)
          -9 : 39412.dasm (-3.18% of base)
          -8 : 27334.dasm (-0.73% of base)
          -7 : 153346.dasm (-1.90% of base)
          -7 : 194714.dasm (-2.79% of base)

507 total files with Code Size differences (501 improved, 6 regressed), 1 unchanged.

Top method regressions (bytes):
          14 ( 0.44% of base) : 72007.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
           3 ( 2.13% of base) : 214336.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this
           3 ( 2.13% of base) : 214337.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           3 ( 1.09% of base) : 207649.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
           1 ( 0.57% of base) : 143569.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadGlobalVariableOrParameter(System.Xml.Xsl.Xslt.NsDecl,int):this

Top method improvements (bytes):
         -20 (-1.20% of base) : 206204.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
         -19 (-0.16% of base) : 147712.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.23% of base) : 109133.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -12 (-0.42% of base) : 49358.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-2.05% of base) : 214181.dasm - System.Security.AccessControl.ObjectSecurity:UpdateWithNewSecurityDescriptor(System.Security.AccessControl.RawSecurityDescriptor,int):this
         -12 (-8.96% of base) : 56654.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-1.74% of base) : 56183.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.46% of base) : 189938.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -11 (-0.29% of base) : 49083.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          -9 (-0.36% of base) : 192080.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAccess(int,System.Security.AccessControl.ObjectAccessRule,byref):bool:this
          -9 (-0.70% of base) : 192081.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAudit(int,System.Security.AccessControl.ObjectAuditRule,byref):bool:this
          -9 (-0.48% of base) : 143566.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadDecimalFormat(System.Xml.Xsl.Xslt.NsDecl):this
          -9 (-3.18% of base) : 39385.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -9 (-3.18% of base) : 39386.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -9 (-2.38% of base) : 135348.dasm - System.Xml.BinXmlDateTime:BreakDownXsdDate(long,byref,byref,byref,byref,byref,byref)
          -9 (-3.18% of base) : 39411.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -9 (-3.18% of base) : 39412.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -8 (-0.73% of base) : 27334.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CreateScriptRootDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.CompilationUnitSyntax):Microsoft.CodeAnalysis.CSharp.RootSingleNamespaceDeclaration:this
          -7 (-1.90% of base) : 153346.dasm - System.Speech.Internal.Synthesis.SsmlParser:NextChar(System.Char[],int,ushort,bool,byref):int
          -7 (-2.79% of base) : 194714.dasm - System.Linq.ParallelEnumerable:Select(System.Linq.ParallelQuery`1[Byte],System.Func`3[Byte,Int32,Nullable`1]):System.Linq.ParallelQuery`1[Nullable`1]

Top method regressions (percentages):
           3 ( 2.13% of base) : 214336.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this
           3 ( 2.13% of base) : 214337.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           3 ( 1.09% of base) : 207649.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
           1 ( 0.57% of base) : 143569.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadGlobalVariableOrParameter(System.Xml.Xsl.Xslt.NsDecl,int):this
          14 ( 0.44% of base) : 72007.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this

Top method improvements (percentages):
          -7 (-12.28% of base) : 56311.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitArrayCreation(Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-8.96% of base) : 56654.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-8.11% of base) : 47773.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -3 (-6.67% of base) : 73224.dasm - LocalVariableSubstituter:VisitLocal(Microsoft.CodeAnalysis.VisualBasic.BoundLocal):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.52% of base) : 48339.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.38% of base) : 48340.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.12% of base) : 47547.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:this
          -6 (-5.77% of base) : 56195.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-5.56% of base) : 159505.dasm - CommandLine.NamedError:GetHashCode():int:this
          -3 (-5.56% of base) : 159499.dasm - CommandLine.TokenError:GetHashCode():int:this
          -6 (-5.45% of base) : 48365.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-5.26% of base) : 159552.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[[CommandLine.Core.OptionSpecification, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[[System.Collections.Generic.IEnumerable`1[[CommandLine.Core.Token, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[CommandLine.Error, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]]
          -4 (-5.19% of base) : 48320.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-4.76% of base) : 48347.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-4.76% of base) : 27885.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.76% of base) : 24541.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.48% of base) : 27898.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -6 (-4.41% of base) : 73121.dasm - AsyncMethodToClassRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -6 (-3.90% of base) : 190109.dasm - System.DirectoryServices.Protocols.LdapConnection:InternalInitConnectionHandle(System.String):this
          -3 (-3.90% of base) : 74480.dasm - AssemblyDataForFile:CreateAssemblySymbol():Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol:this

507 total methods with Code Size differences (501 improved, 6 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------
