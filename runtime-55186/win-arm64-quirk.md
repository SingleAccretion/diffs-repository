## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 57508
Total bytes of diff: 57320
Total bytes of delta: -188 (-0.33% of base)
Total relative delta: -0.24
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -16 : 7671.dasm (-0.12% of base)
         -12 : 21932.dasm (-0.72% of base)
         -12 : 16693.dasm (-7.50% of base)
         -12 : 21934.dasm (-0.45% of base)
         -12 : 11632.dasm (-0.63% of base)
          -8 : 16632.dasm (-0.22% of base)
          -8 : 2377.dasm (-0.60% of base)
          -8 : 2445.dasm (-0.36% of base)
          -8 : 10188.dasm (-0.19% of base)
          -8 : 21937.dasm (-0.64% of base)
          -8 : 5635.dasm (-0.37% of base)
          -4 : 14277.dasm (-0.41% of base)
          -4 : 16835.dasm (-1.37% of base)
          -4 : 21933.dasm (-0.47% of base)
          -4 : 2206.dasm (-0.55% of base)
          -4 : 3409.dasm (-0.59% of base)
          -4 : 5678.dasm (-1.19% of base)
          -4 : 8046.dasm (-0.28% of base)
          -4 : 15585.dasm (-0.45% of base)
          -4 : 21935.dasm (-0.47% of base)

30 total files with Code Size differences (30 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
         -16 (-0.12% of base) : 7671.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.72% of base) : 21932.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-7.50% of base) : 16693.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -12 (-0.45% of base) : 21934.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.63% of base) : 11632.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.22% of base) : 16632.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -8 (-0.60% of base) : 2377.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.36% of base) : 2445.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.19% of base) : 10188.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
          -8 (-0.64% of base) : 21937.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.37% of base) : 5635.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -4 (-0.41% of base) : 14277.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this
          -4 (-1.37% of base) : 16835.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-0.47% of base) : 21933.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -4 (-0.55% of base) : 2206.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -4 (-0.59% of base) : 3409.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
          -4 (-1.19% of base) : 5678.dasm - System.Net.Sockets.SafeSocketHandle:CloseHandle(bool,bool):bool:this
          -4 (-0.28% of base) : 8046.dasm - System.Threading.Barrier:SignalAndWait(int,System.Threading.CancellationToken):bool:this
          -4 (-0.45% of base) : 15585.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
          -4 (-0.47% of base) : 21935.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)

Top method improvements (percentages):
         -12 (-7.50% of base) : 16693.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-3.23% of base) : 16967.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -4 (-1.37% of base) : 16835.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-1.19% of base) : 5678.dasm - System.Net.Sockets.SafeSocketHandle:CloseHandle(bool,bool):bool:this
          -4 (-0.92% of base) : 8851.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:CreateProperty(System.Reflection.MemberInfo,int):Newtonsoft.Json.Serialization.JsonProperty:this
         -12 (-0.72% of base) : 21932.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.64% of base) : 21937.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.63% of base) : 11632.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.60% of base) : 2377.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.59% of base) : 3409.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportElement(System.Xml.Serialization.TypeModel,System.Xml.Serialization.XmlRootAttribute,System.String,System.Xml.Serialization.RecursionLimiter):System.Xml.Serialization.ElementAccessor:this
          -4 (-0.58% of base) : 4147.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -4 (-0.57% of base) : 1581.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
          -4 (-0.55% of base) : 2206.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -4 (-0.47% of base) : 21933.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -4 (-0.47% of base) : 21935.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -4 (-0.47% of base) : 2433.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
         -12 (-0.45% of base) : 21934.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.45% of base) : 15585.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this
          -4 (-0.41% of base) : 14277.dasm - System.Xml.Serialization.XmlReflectionImporter:CreateArrayElementsFromAttributes(System.Xml.Serialization.ArrayMapping,System.Xml.Serialization.XmlArrayItemAttributes,System.Type,System.String,System.Xml.Serialization.RecursionLimiter):this
          -8 (-0.37% of base) : 5635.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this

30 total methods with Code Size differences (30 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 50256
Total bytes of diff: 49588
Total bytes of delta: -668 (-1.33% of base)
Total relative delta: -1.55
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -344 : 79908.dasm (-7.96% of base)
         -44 : 86304.dasm (-24.44% of base)
         -12 : 136204.dasm (-0.34% of base)
         -12 : 82871.dasm (-0.35% of base)
         -12 : 83472.dasm (-0.34% of base)
         -12 : 82870.dasm (-0.34% of base)
         -12 : 133761.dasm (-0.34% of base)
         -12 : 223788.dasm (-3.45% of base)
          -8 : 86369.dasm (-1.77% of base)
          -8 : 136202.dasm (-0.40% of base)
          -8 : 133758.dasm (-0.40% of base)
          -4 : 170347.dasm (-2.44% of base)
          -4 : 173434.dasm (-1.89% of base)
          -4 : 173441.dasm (-2.44% of base)
          -4 : 223342.dasm (-0.10% of base)
          -4 : 231237.dasm (-3.70% of base)
          -4 : 170361.dasm (-2.13% of base)
          -4 : 173438.dasm (-2.50% of base)
          -4 : 214525.dasm (-2.38% of base)
          -4 : 229543.dasm (-3.70% of base)

57 total files with Code Size differences (57 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
        -344 (-7.96% of base) : 79908.dasm - JitTest.Test:Main():int
         -44 (-24.44% of base) : 86304.dasm - ILGEN_CLASS:ILGEN_METHOD(bool,ushort,short,int):ushort
         -12 (-0.34% of base) : 136204.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -12 (-0.35% of base) : 82871.dasm - JitTest.Test:Main():int
         -12 (-0.34% of base) : 83472.dasm - JitTest.Test:Main():int
         -12 (-0.34% of base) : 82870.dasm - JitTest.Test:Main():int
         -12 (-0.34% of base) : 133761.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -12 (-3.45% of base) : 223788.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -8 (-1.77% of base) : 86369.dasm - DevDiv_605447:ILGEN_METHOD(int,int,int,ushort,float):ushort
          -8 (-0.40% of base) : 136202.dasm - testout1:Func_0_5_2_1_6():System.Decimal
          -8 (-0.40% of base) : 133758.dasm - testout1:Func_0_5_2_1_6():System.Decimal
          -4 (-2.44% of base) : 170347.dasm - NullableTest2:BoxUnboxToNQGen(System.__Canon):bool
          -4 (-1.89% of base) : 173434.dasm - NullableTest2:BoxUnboxToNQ(System.Object):bool
          -4 (-2.44% of base) : 173441.dasm - NullableTest2:BoxUnboxToNQGen(System.Numerics.Vector`1[Single]):bool
          -4 (-0.10% of base) : 223342.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbMethodDebugInformation2():this
          -4 (-3.70% of base) : 231237.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-2.13% of base) : 170361.dasm - NullableTest2:BoxUnboxToNQGenC(System.Nullable`1[Byte]):bool
          -4 (-2.50% of base) : 173438.dasm - NullableTest2:BoxUnboxToNQGen(short):bool
          -4 (-2.38% of base) : 214525.dasm - NullableTest7:BoxUnboxToNQ(System.IComparable):bool
          -4 (-3.70% of base) : 229543.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool

Top method improvements (percentages):
         -44 (-24.44% of base) : 86304.dasm - ILGEN_CLASS:ILGEN_METHOD(bool,ushort,short,int):ushort
        -344 (-7.96% of base) : 79908.dasm - JitTest.Test:Main():int
          -4 (-3.70% of base) : 231237.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-3.70% of base) : 229543.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -4 (-3.70% of base) : 229801.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -4 (-3.70% of base) : 229806.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -4 (-3.70% of base) : 231241.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -4 (-3.70% of base) : 229800.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool
          -4 (-3.70% of base) : 230475.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -4 (-3.70% of base) : 231238.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -4 (-3.70% of base) : 229803.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -4 (-3.70% of base) : 231236.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -4 (-3.70% of base) : 229802.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -4 (-3.57% of base) : 229804.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-3.57% of base) : 231240.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -4 (-3.57% of base) : 231239.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -4 (-3.57% of base) : 229805.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
         -12 (-3.45% of base) : 223788.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -4 (-3.12% of base) : 231489.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -4 (-2.70% of base) : 231235.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool

57 total methods with Code Size differences (57 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 473840
Total bytes of diff: 471952
Total bytes of delta: -1888 (-0.40% of base)
Total relative delta: -3.78
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -44 : 176073.dasm (-1.96% of base)
         -20 : 207534.dasm (-0.81% of base)
         -20 : 66000.dasm (-1.35% of base)
         -20 : 80647.dasm (-0.59% of base)
         -20 : 25126.dasm (-0.42% of base)
         -16 : 80635.dasm (-0.49% of base)
         -16 : 80596.dasm (-0.32% of base)
         -16 : 192555.dasm (-0.67% of base)
         -16 : 87103.dasm (-0.51% of base)
         -12 : 121771.dasm (-0.06% of base)
         -12 : 216780.dasm (-0.27% of base)
         -12 : 216790.dasm (-0.37% of base)
         -12 : 216800.dasm (-0.34% of base)
         -12 : 83385.dasm (-0.18% of base)
         -12 : 66274.dasm (-0.31% of base)
         -12 : 86402.dasm (-0.15% of base)
         -12 : 63939.dasm (-0.83% of base)
         -12 : 83478.dasm (-0.88% of base)
         -12 : 96987.dasm (-5.88% of base)
         -12 : 27940.dasm (-0.22% of base)

357 total files with Code Size differences (357 improved, 0 regressed), 96 unchanged.

Top method improvements (bytes):
         -44 (-1.96% of base) : 176073.dasm - <SendAsyncCore>d__44:MoveNext():this
         -20 (-0.81% of base) : 207534.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -20 (-1.35% of base) : 66000.dasm - RetargetingSymbolTranslator:FindPropertyInRetargetedType(Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol:this
         -20 (-0.59% of base) : 80647.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
         -20 (-0.42% of base) : 25126.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -16 (-0.49% of base) : 80635.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -16 (-0.32% of base) : 80596.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -16 (-0.67% of base) : 192555.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
         -16 (-0.51% of base) : 87103.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -12 (-0.06% of base) : 121771.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.27% of base) : 216780.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
         -12 (-0.37% of base) : 216790.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
         -12 (-0.34% of base) : 216800.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AndObject(System.Object,System.Object):System.Object
         -12 (-0.18% of base) : 83385.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedEventAccessorSymbol:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock
         -12 (-0.31% of base) : 66274.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
         -12 (-0.15% of base) : 86402.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedPropertyAccessorBase`1:GetBoundMethodBody(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.FieldSymbol,byref):Microsoft.CodeAnalysis.VisualBasic.BoundBlock
         -12 (-0.83% of base) : 63939.dasm - RetargetedTypeMethodFinder:FindWorker(Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingModuleSymbol+RetargetingSymbolTranslator,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
         -12 (-0.88% of base) : 83478.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
         -12 (-5.88% of base) : 96987.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
         -12 (-0.22% of base) : 27940.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.CSharp.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.CSharp.CSharpCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock

Top method improvements (percentages):
          -8 (-6.90% of base) : 88203.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-6.67% of base) : 49196.dasm - TryWriteInterpolatedStringHandler:.ctor(int,int,System.Span`1[System.Char],byref):this
          -4 (-6.25% of base) : 88807.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -4 (-5.88% of base) : 11885.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
         -12 (-5.88% of base) : 96987.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -4 (-4.55% of base) : 11185.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-4.35% of base) : 98636.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:WithAliases(System.Collections.Immutable.ImmutableArray`1[System.String]):Microsoft.CodeAnalysis.MetadataReferenceProperties:this
          -4 (-4.35% of base) : 88244.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-4.35% of base) : 88245.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-4.26% of base) : 187772.dasm - CredentialEnumerator:MoveNext():bool:this
          -4 (-4.00% of base) : 99452.dasm - Microsoft.CodeAnalysis.PreprocessingSymbolInfo:GetHashCode():int:this
          -4 (-3.85% of base) : 28981.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-3.85% of base) : 88237.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-3.57% of base) : 215012.dasm - CommandLine.NamedError:GetHashCode():int:this
          -4 (-3.57% of base) : 215017.dasm - CommandLine.TokenError:GetHashCode():int:this
          -8 (-3.39% of base) : 60002.dasm - System.Runtime.Serialization.Json.DataContractJsonSerializerImpl:.ctor(System.Type,System.Runtime.Serialization.Json.DataContractJsonSerializerSettings):this
          -4 (-3.33% of base) : 25543.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-3.23% of base) : 25530.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-3.12% of base) : 172118.dasm - ShellExecuteHelper:ShellExecuteFunction():this
          -4 (-3.12% of base) : 99163.dasm - Microsoft.CodeAnalysis.FileLinePositionSpan:GetHashCode():int:this

357 total methods with Code Size differences (357 improved, 0 regressed), 96 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 319212
Total bytes of diff: 316936
Total bytes of delta: -2276 (-0.71% of base)
Total relative delta: -7.38
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 57110.dasm (4.35% of base)

Top file improvements (bytes):
         -20 : 175276.dasm (-0.79% of base)
         -20 : 227096.dasm (-1.85% of base)
         -16 : 50174.dasm (-0.48% of base)
         -16 : 49104.dasm (-12.50% of base)
         -16 : 166245.dasm (-0.25% of base)
         -16 : 57008.dasm (-1.90% of base)
         -16 : 136252.dasm (-0.12% of base)
         -16 : 57462.dasm (-8.33% of base)
         -12 : 80064.dasm (-7.14% of base)
         -12 : 132068.dasm (-0.52% of base)
         -12 : 25312.dasm (-9.38% of base)
         -12 : 49123.dasm (-9.38% of base)
         -12 : 40183.dasm (-2.88% of base)
         -12 : 40184.dasm (-2.88% of base)
         -12 : 40209.dasm (-2.88% of base)
         -12 : 40210.dasm (-2.88% of base)
         -12 : 49883.dasm (-0.33% of base)
          -8 : 120752.dasm (-2.33% of base)
          -8 : 132072.dasm (-0.41% of base)
          -8 : 28727.dasm (-0.78% of base)

494 total files with Code Size differences (493 improved, 1 regressed), 19 unchanged.

Top method regressions (bytes):
           4 ( 4.35% of base) : 57110.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitArrayCreation(Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method improvements (bytes):
         -20 (-0.79% of base) : 175276.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -20 (-1.85% of base) : 227096.dasm - ILCompiler.ReadyToRunCodegenCompilation:Compile(System.String):this
         -16 (-0.48% of base) : 50174.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -16 (-12.50% of base) : 49104.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -16 (-0.25% of base) : 166245.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -16 (-1.90% of base) : 57008.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -16 (-0.12% of base) : 136252.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -16 (-8.33% of base) : 57462.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-7.14% of base) : 80064.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
         -12 (-0.52% of base) : 132068.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadDecimalFormat(System.Xml.Xsl.Xslt.NsDecl):this
         -12 (-9.38% of base) : 25312.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -12 (-9.38% of base) : 49123.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-2.88% of base) : 40183.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
         -12 (-2.88% of base) : 40184.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
         -12 (-2.88% of base) : 40209.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
         -12 (-2.88% of base) : 40210.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
         -12 (-0.33% of base) : 49883.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          -8 (-2.33% of base) : 120752.dasm - System.Runtime.Serialization.Json.DataContractJsonSerializerImpl:.ctor(System.Type,System.Runtime.Serialization.Json.DataContractJsonSerializerSettings):this
          -8 (-0.41% of base) : 132072.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadTemplate(System.Xml.Xsl.Xslt.NsDecl):this
          -8 (-0.78% of base) : 28727.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckCompoundAssignmentOperator(Microsoft.CodeAnalysis.CSharp.BoundCompoundAssignmentOperator):this

Top method regressions (percentages):
           4 ( 4.35% of base) : 57110.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitArrayCreation(Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method improvements (percentages):
         -16 (-12.50% of base) : 49104.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-9.38% of base) : 25312.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -12 (-9.38% of base) : 49123.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -16 (-8.33% of base) : 57462.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -4 (-7.69% of base) : 48577.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
         -12 (-7.14% of base) : 80064.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -4 (-6.67% of base) : 48351.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:this
          -4 (-5.56% of base) : 49183.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-5.56% of base) : 49184.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-5.26% of base) : 78329.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:WithAliases(System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.MetadataReferenceProperties:this
          -4 (-4.76% of base) : 28676.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -8 (-4.76% of base) : 49217.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-4.76% of base) : 57452.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceFieldAccess(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Result
          -4 (-4.55% of base) : 28689.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-4.17% of base) : 140682.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[[CommandLine.Core.OptionSpecification, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[[System.Collections.Generic.IEnumerable`1[[CommandLine.Core.Token, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[CommandLine.Error, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]]
          -4 (-4.00% of base) : 140635.dasm - CommandLine.NamedError:GetHashCode():int:this
          -4 (-4.00% of base) : 140629.dasm - CommandLine.TokenError:GetHashCode():int:this
          -4 (-3.85% of base) : 189304.dasm - System.Linq.Parallel.UnaryQueryOperator`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(System.Linq.Parallel.QueryOperator`1[__Canon]):this
          -4 (-3.85% of base) : 189312.dasm - System.Linq.Parallel.UnaryQueryOperator`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(System.Linq.Parallel.QueryOperator`1[Byte]):this
          -8 (-3.64% of base) : 73925.dasm - AsyncMethodToClassRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

494 total methods with Code Size differences (493 improved, 1 regressed), 19 unchanged.

```

</details>

--------------------------------------------------------------------------------
