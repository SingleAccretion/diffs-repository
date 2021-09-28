## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 49559
Total bytes of diff: 49392
Total bytes of delta: -167 (-0.34% of base)
Total relative delta: -0.23
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -14 : 1348.dasm (-0.26% of base)
         -13 : 3253.dasm (-0.10% of base)
         -12 : 9101.dasm (-0.82% of base)
         -12 : 12398.dasm (-0.71% of base)
         -12 : 1430.dasm (-0.38% of base)
         -10 : 17839.dasm (-5.88% of base)
         -10 : 7229.dasm (-0.82% of base)
          -9 : 9103.dasm (-0.40% of base)
          -8 : 5509.dasm (-0.41% of base)
          -7 : 17981.dasm (-2.41% of base)
          -7 : 9329.dasm (-0.55% of base)
          -5 : 7285.dasm (-0.72% of base)
          -5 : 9102.dasm (-0.72% of base)
          -5 : 9104.dasm (-0.72% of base)
          -4 : 4254.dasm (-0.60% of base)
          -4 : 7294.dasm (-0.22% of base)
          -4 : 9109.dasm (-0.34% of base)
          -3 : 16732.dasm (-0.29% of base)
          -3 : 3231.dasm (-0.45% of base)
          -3 : 18828.dasm (-0.30% of base)

27 total files with Code Size differences (27 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -14 (-0.26% of base) : 1348.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
         -13 (-0.10% of base) : 3253.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.82% of base) : 9101.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.71% of base) : 12398.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.38% of base) : 1430.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
         -10 (-5.88% of base) : 17839.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -10 (-0.82% of base) : 7229.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.40% of base) : 9103.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.41% of base) : 5509.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -7 (-2.41% of base) : 17981.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -7 (-0.55% of base) : 9329.dasm - System.Threading.Barrier:SignalAndWait(int,System.Threading.CancellationToken):bool:this
          -5 (-0.72% of base) : 7285.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 9102.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 9104.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -4 (-0.60% of base) : 4254.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -4 (-0.22% of base) : 7294.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.34% of base) : 9109.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.29% of base) : 16732.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
          -3 (-0.45% of base) : 3231.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
          -3 (-0.30% of base) : 18828.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this

Top method improvements (percentages):
         -10 (-5.88% of base) : 17839.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-3.95% of base) : 18113.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -7 (-2.41% of base) : 17981.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -10 (-0.82% of base) : 7229.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.82% of base) : 9101.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.79% of base) : 2971.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:CreateProperty(System.Reflection.MemberInfo,int):Newtonsoft.Json.Serialization.JsonProperty:this
          -5 (-0.72% of base) : 7285.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 9102.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 9104.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
         -12 (-0.71% of base) : 12398.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.60% of base) : 4254.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -7 (-0.55% of base) : 9329.dasm - System.Threading.Barrier:SignalAndWait(int,System.Threading.CancellationToken):bool:this
          -3 (-0.45% of base) : 3231.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
          -8 (-0.41% of base) : 5509.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -9 (-0.40% of base) : 9103.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.38% of base) : 1430.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
          -4 (-0.34% of base) : 9109.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.30% of base) : 18828.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this
          -3 (-0.29% of base) : 16732.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
         -14 (-0.26% of base) : 1348.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute

27 total methods with Code Size differences (27 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 61327
Total bytes of diff: 60277
Total bytes of delta: -1050 (-1.71% of base)
Total relative delta: -1.51
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -760 : 79908.dasm (-10.92% of base)
         -41 : 133760.dasm (-0.87% of base)
         -41 : 136203.dasm (-0.87% of base)
         -11 : 223929.dasm (-3.93% of base)
          -9 : 86368.dasm (-1.90% of base)
          -7 : 86303.dasm (-4.61% of base)
          -4 : 133757.dasm (-0.15% of base)
          -4 : 171284.dasm (-2.25% of base)
          -4 : 172603.dasm (-2.38% of base)
          -4 : 230644.dasm (-4.71% of base)
          -4 : 231266.dasm (-3.81% of base)
          -4 : 136201.dasm (-0.15% of base)
          -4 : 171276.dasm (-2.65% of base)
          -4 : 172612.dasm (-1.91% of base)
          -4 : 230291.dasm (-4.30% of base)
          -4 : 230293.dasm (-3.81% of base)
          -4 : 231262.dasm (-3.54% of base)
          -4 : 231267.dasm (-3.81% of base)
          -4 : 171272.dasm (-2.67% of base)
          -4 : 172602.dasm (-2.48% of base)

54 total files with Code Size differences (54 improved, 0 regressed), 4 unchanged.

Top method improvements (bytes):
        -760 (-10.92% of base) : 79908.dasm - JitTest.Test:Main():int
         -41 (-0.87% of base) : 133760.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -41 (-0.87% of base) : 136203.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -11 (-3.93% of base) : 223929.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -9 (-1.90% of base) : 86368.dasm - DevDiv_605447:ILGEN_METHOD(int,int,int,ushort,float):ushort
          -7 (-4.61% of base) : 86303.dasm - ILGEN_CLASS:ILGEN_METHOD(bool,ushort,short,int):ushort
          -4 (-0.15% of base) : 133757.dasm - testout1:Func_0_5_2_1_6():System.Decimal
          -4 (-2.25% of base) : 171284.dasm - NullableTest2:BoxUnboxToNQGenC(System.Nullable`1[Byte]):bool
          -4 (-2.38% of base) : 172603.dasm - NullableTest2:BoxUnboxToNQGen(System.Numerics.Vector`1[Single]):bool
          -4 (-4.71% of base) : 230644.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -4 (-3.81% of base) : 231266.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-0.15% of base) : 136201.dasm - testout1:Func_0_5_2_1_6():System.Decimal
          -4 (-2.65% of base) : 171276.dasm - NullableTest2:BoxUnboxToNQGen(long):bool
          -4 (-1.91% of base) : 172612.dasm - NullableTest2:BoxUnboxToNQGenC(System.Nullable`1[Byte]):bool
          -4 (-4.30% of base) : 230291.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-3.81% of base) : 230293.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-3.54% of base) : 231262.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool
          -4 (-3.81% of base) : 231267.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -4 (-2.67% of base) : 171272.dasm - NullableTest2:BoxUnboxToNQGen(short):bool
          -4 (-2.48% of base) : 172602.dasm - NullableTest2:BoxUnboxToNQGen(double):bool

Top method improvements (percentages):
        -760 (-10.92% of base) : 79908.dasm - JitTest.Test:Main():int
          -4 (-4.71% of base) : 230644.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -4 (-4.71% of base) : 229814.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -4 (-4.71% of base) : 230289.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool
          -7 (-4.61% of base) : 86303.dasm - ILGEN_CLASS:ILGEN_METHOD(bool,ushort,short,int):ushort
          -4 (-4.35% of base) : 231265.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -4 (-4.35% of base) : 230292.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -4 (-4.30% of base) : 230291.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-4.30% of base) : 230290.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -4 (-4.30% of base) : 231264.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-4.30% of base) : 231263.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -4 (-4.26% of base) : 230295.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -4 (-4.26% of base) : 231268.dasm - NullableTest:BoxUnboxToNQ(long):bool
         -11 (-3.93% of base) : 223929.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -4 (-3.88% of base) : 231660.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -4 (-3.81% of base) : 231266.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-3.81% of base) : 230293.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-3.81% of base) : 231267.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -4 (-3.81% of base) : 230294.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -4 (-3.54% of base) : 231262.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool

54 total methods with Code Size differences (54 improved, 0 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 355767
Total bytes of diff: 353923
Total bytes of delta: -1844 (-0.52% of base)
Total relative delta: -6.04
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 183436.dasm (1.67% of base)

Top file improvements (bytes):
         -31 : 137440.dasm (-3.43% of base)
         -20 : 212815.dasm (-1.13% of base)
         -19 : 4989.dasm (-1.60% of base)
         -15 : 103534.dasm (-0.38% of base)
         -15 : 20061.dasm (-0.50% of base)
         -14 : 26951.dasm (-0.70% of base)
         -13 : 20081.dasm (-2.28% of base)
         -12 : 20049.dasm (-0.51% of base)
         -12 : 20010.dasm (-0.26% of base)
         -12 : 26669.dasm (-0.45% of base)
         -11 : 135405.dasm (-5.56% of base)
         -10 : 175768.dasm (-2.49% of base)
         -10 : 22942.dasm (-1.01% of base)
          -9 : 5272.dasm (-0.28% of base)
          -9 : 19932.dasm (-0.37% of base)
          -9 : 22847.dasm (-0.16% of base)
          -9 : 106351.dasm (-0.21% of base)
          -9 : 25966.dasm (-0.13% of base)
          -9 : 20074.dasm (-0.53% of base)
          -9 : 4155.dasm (-3.12% of base)

451 total files with Code Size differences (450 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          16 ( 1.67% of base) : 183436.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.Int64[]:this

Top method improvements (bytes):
         -31 (-3.43% of base) : 137440.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:FindMethodSymbolInSuperType(System.Reflection.Metadata.TypeDefinitionHandle,System.Reflection.Metadata.MethodDefinitionHandle):System.__Canon:this
         -20 (-1.13% of base) : 212815.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -19 (-1.60% of base) : 4989.dasm - RetargetingSymbolTranslator:FindPropertyInRetargetedType(Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol:this
         -15 (-0.38% of base) : 103534.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -15 (-0.50% of base) : 20061.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
         -14 (-0.70% of base) : 26951.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -13 (-2.28% of base) : 20081.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.51% of base) : 20049.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-0.26% of base) : 20010.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-0.45% of base) : 26669.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -11 (-5.56% of base) : 135405.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
         -10 (-2.49% of base) : 175768.dasm - System.Net.Mail.SmtpClient:SendMailCallback(System.IAsyncResult):this
         -10 (-1.01% of base) : 22942.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
          -9 (-0.28% of base) : 5272.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
          -9 (-0.37% of base) : 19932.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitSyncLockStatement(Microsoft.CodeAnalysis.VisualBasic.BoundSyncLockStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-0.16% of base) : 22847.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedEventAccessorSymbol:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock
          -9 (-0.21% of base) : 106351.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:CompileMethod(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,int,byref,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.TypeCompilationState):this
          -9 (-0.13% of base) : 25966.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedPropertyAccessorBase`1:GetBoundMethodBody(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.FieldSymbol,byref):Microsoft.CodeAnalysis.VisualBasic.BoundBlock
          -9 (-0.53% of base) : 20074.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitBottomConditionLoop(Microsoft.CodeAnalysis.VisualBasic.BoundDoLoopStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-3.12% of base) : 4155.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method regressions (percentages):
          16 ( 1.67% of base) : 183436.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.Int64[]:this

Top method improvements (percentages):
          -3 (-9.38% of base) : 90773.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
          -6 (-8.33% of base) : 207501.dasm - CommandLine.NamedError:GetHashCode():int:this
          -6 (-8.33% of base) : 207506.dasm - CommandLine.TokenError:GetHashCode():int:this
          -7 (-8.24% of base) : 27769.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-7.84% of base) : 28390.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -4 (-7.14% of base) : 90086.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-6.15% of base) : 27811.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-6.06% of base) : 27810.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-5.88% of base) : 107358.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-5.88% of base) : 27803.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -6 (-5.66% of base) : 108030.dasm - Microsoft.CodeAnalysis.CSharp.MethodTypeInferrer:InferTypeArgs(Microsoft.CodeAnalysis.CSharp.Binder,byref):Microsoft.CodeAnalysis.CSharp.MethodTypeInferenceResult:this
         -11 (-5.56% of base) : 135405.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -3 (-5.08% of base) : 137867.dasm - Microsoft.CodeAnalysis.PreprocessingSymbolInfo:GetHashCode():int:this
          -4 (-4.94% of base) : 103949.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -5 (-4.59% of base) : 190392.dasm - CredentialEnumerator:MoveNext():bool:this
          -4 (-4.44% of base) : 103936.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.29% of base) : 207462.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[System.String],System.Collections.Generic.IEnumerable`1[CommandLine.Core.OptionSpecification],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[System.Collections.Generic.IEnumerable`1[CommandLine.Core.Token], CommandLine.Error]
          -7 (-4.14% of base) : 94854.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -7 (-4.14% of base) : 94855.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -3 (-4.11% of base) : 65502.dasm - TryWriteInterpolatedStringHandler:.ctor(int,int,System.Span`1[System.Char],byref):this

451 total methods with Code Size differences (450 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 305560
Total bytes of diff: 303516
Total bytes of delta: -2044 (-0.67% of base)
Total relative delta: -6.80
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          39 : 195803.dasm (3.65% of base)
          37 : 195784.dasm (3.51% of base)
          11 : 208321.dasm (2.58% of base)
           4 : 208368.dasm (0.89% of base)
           2 : 208371.dasm (0.83% of base)
           2 : 208373.dasm (0.90% of base)

Top file improvements (bytes):
         -50 : 29023.dasm (-2.37% of base)
         -18 : 188328.dasm (-0.67% of base)
         -16 : 56893.dasm (-2.02% of base)
         -15 : 50055.dasm (-0.47% of base)
         -14 : 180885.dasm (-0.22% of base)
         -14 : 57347.dasm (-7.45% of base)
         -13 : 146378.dasm (-0.10% of base)
         -12 : 23558.dasm (-0.62% of base)
         -12 : 29280.dasm (-0.80% of base)
         -12 : 28985.dasm (-1.27% of base)
         -12 : 23762.dasm (-1.67% of base)
         -12 : 29281.dasm (-1.32% of base)
         -11 : 28883.dasm (-0.72% of base)
         -11 : 29034.dasm (-0.49% of base)
         -11 : 152049.dasm (-2.58% of base)
         -11 : 29035.dasm (-0.79% of base)
         -11 : 79969.dasm (-5.64% of base)
         -10 : 40064.dasm (-3.04% of base)
         -10 : 40065.dasm (-3.04% of base)
         -10 : 40090.dasm (-3.04% of base)

500 total files with Code Size differences (494 improved, 6 regressed), 7 unchanged.

Top method regressions (bytes):
          39 ( 3.65% of base) : 195803.dasm - System.Linq.Parallel.QueryOperator`1[Byte][System.Byte]:ExecuteAndGetResultsAsArray():System.Byte[]:this
          37 ( 3.51% of base) : 195784.dasm - System.Linq.Parallel.QueryOperator`1[__Canon][System.__Canon]:ExecuteAndGetResultsAsArray():System.__Canon[]:this
          11 ( 2.58% of base) : 208321.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
           4 ( 0.89% of base) : 208368.dasm - System.Net.WebClient:DownloadStringAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.83% of base) : 208371.dasm - System.Net.WebClient:DownloadDataAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.90% of base) : 208373.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this

Top method improvements (bytes):
         -50 (-2.37% of base) : 29023.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteLiftedConversionInExpressionTree(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ubyte,bool,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -18 (-0.67% of base) : 188328.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -16 (-2.02% of base) : 56893.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -15 (-0.47% of base) : 50055.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -14 (-0.22% of base) : 180885.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -14 (-7.45% of base) : 57347.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -13 (-0.10% of base) : 146378.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.62% of base) : 23558.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindFieldAccess(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.FieldSymbol,Microsoft.CodeAnalysis.DiagnosticBag,ubyte,bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -12 (-0.80% of base) : 29280.dasm - Microsoft.CodeAnalysis.CSharp.SyntheticBoundNodeFactory:Convert(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.BoundExpression):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -12 (-1.27% of base) : 28985.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeFieldAccess(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.FieldSymbol,Microsoft.CodeAnalysis.ConstantValue,ubyte,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.BoundFieldAccess):Microsoft.CodeAnalysis.CSharp.BoundExpression
         -12 (-1.67% of base) : 23762.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CreateAnonymousFunctionConversion(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression
         -12 (-1.32% of base) : 29281.dasm - Microsoft.CodeAnalysis.CSharp.SyntheticBoundNodeFactory:Convert(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -11 (-0.72% of base) : 28883.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitStackAllocArrayCreation(Microsoft.CodeAnalysis.CSharp.BoundStackAllocArrayCreation):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -11 (-0.49% of base) : 29034.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeSizeOfMultiplication(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.PointerTypeSymbol,bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -11 (-2.58% of base) : 152049.dasm - System.Speech.Internal.Synthesis.SsmlParser:NextChar(System.Char[],int,ushort,bool,byref):int
         -11 (-0.79% of base) : 29035.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewritePointerSubtraction(int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -11 (-5.64% of base) : 79969.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
         -10 (-3.04% of base) : 40064.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
         -10 (-3.04% of base) : 40065.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
         -10 (-3.04% of base) : 40090.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this

Top method regressions (percentages):
          39 ( 3.65% of base) : 195803.dasm - System.Linq.Parallel.QueryOperator`1[Byte][System.Byte]:ExecuteAndGetResultsAsArray():System.Byte[]:this
          37 ( 3.51% of base) : 195784.dasm - System.Linq.Parallel.QueryOperator`1[__Canon][System.__Canon]:ExecuteAndGetResultsAsArray():System.__Canon[]:this
          11 ( 2.58% of base) : 208321.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
           2 ( 0.90% of base) : 208373.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this
           4 ( 0.89% of base) : 208368.dasm - System.Net.WebClient:DownloadStringAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.83% of base) : 208371.dasm - System.Net.WebClient:DownloadDataAsyncCallback(System.Byte[],System.Exception,System.Object):this

Top method improvements (percentages):
          -4 (-8.00% of base) : 48458.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
         -14 (-7.45% of base) : 57347.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-7.32% of base) : 157066.dasm - CommandLine.TokenError:GetHashCode():int:this
          -6 (-7.32% of base) : 157072.dasm - CommandLine.NamedError:GetHashCode():int:this
          -4 (-6.45% of base) : 49064.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-6.35% of base) : 49065.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-5.88% of base) : 48232.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:this
         -11 (-5.64% of base) : 79969.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -4 (-5.13% of base) : 28555.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -7 (-5.04% of base) : 56905.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-4.88% of base) : 25191.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -7 (-4.83% of base) : 49098.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -5 (-4.72% of base) : 48985.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-4.71% of base) : 49004.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-4.60% of base) : 28568.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.29% of base) : 157118.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[[CommandLine.Core.OptionSpecification, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[[System.Collections.Generic.IEnumerable`1[[CommandLine.Core.Token, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[CommandLine.Error, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]]
          -7 (-4.07% of base) : 73811.dasm - AsyncMethodToClassRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-3.96% of base) : 78217.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:WithAliases(System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.MetadataReferenceProperties:this
          -4 (-3.74% of base) : 28552.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -2 (-3.57% of base) : 73918.dasm - LocalVariableSubstituter:VisitLocal(Microsoft.CodeAnalysis.VisualBasic.BoundLocal):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

500 total methods with Code Size differences (494 improved, 6 regressed), 7 unchanged.

```

</details>

--------------------------------------------------------------------------------
