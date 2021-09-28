## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 94324
Total bytes of diff: 94100
Total bytes of delta: -224 (-0.24% of base)
Total relative delta: -0.66
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 14143.dasm (1.87% of base)
           7 : 10506.dasm (0.66% of base)
           5 : 10509.dasm (2.89% of base)
           4 : 6097.dasm (2.48% of base)
           4 : 3954.dasm (3.85% of base)
           3 : 15020.dasm (0.18% of base)
           3 : 9223.dasm (0.14% of base)

Top file improvements (bytes):
         -18 : 10479.dasm (-2.80% of base)
         -18 : 2751.dasm (-1.19% of base)
         -14 : 1348.dasm (-0.26% of base)
         -13 : 3253.dasm (-0.10% of base)
         -12 : 1430.dasm (-0.38% of base)
         -12 : 9101.dasm (-0.82% of base)
         -12 : 12398.dasm (-0.71% of base)
         -10 : 17839.dasm (-5.88% of base)
         -10 : 7229.dasm (-0.82% of base)
          -9 : 9103.dasm (-0.40% of base)
          -8 : 23039.dasm (-2.42% of base)
          -8 : 5509.dasm (-0.41% of base)
          -7 : 9329.dasm (-0.55% of base)
          -7 : 17981.dasm (-2.41% of base)
          -5 : 14126.dasm (-2.66% of base)
          -5 : 9102.dasm (-0.72% of base)
          -5 : 7285.dasm (-0.72% of base)
          -5 : 9104.dasm (-0.72% of base)
          -4 : 9109.dasm (-0.34% of base)
          -4 : 4254.dasm (-0.60% of base)

53 total files with Code Size differences (46 improved, 7 regressed), 29 unchanged.

Top method regressions (bytes):
          10 ( 1.87% of base) : 14143.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           7 ( 0.66% of base) : 10506.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           5 ( 2.89% of base) : 10509.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           4 ( 2.48% of base) : 6097.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
           4 ( 3.85% of base) : 3954.dasm - Microsoft.Extensions.Logging.MessageLogger:IsEnabled(int):bool:this
           3 ( 0.18% of base) : 15020.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadField(System.Reflection.FieldInfo,System.Nullable`1[Boolean],System.Nullable`1[Int32]):Sigil.Emit`1[__Canon]:this
           3 ( 0.14% of base) : 9223.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:SetEntry(Microsoft.Extensions.Caching.Memory.CacheEntry):this

Top method improvements (bytes):
         -18 (-2.80% of base) : 10479.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
         -18 (-1.19% of base) : 2751.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this
         -14 (-0.26% of base) : 1348.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
         -13 (-0.10% of base) : 3253.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -12 (-0.38% of base) : 1430.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
         -12 (-0.82% of base) : 9101.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.71% of base) : 12398.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -10 (-5.88% of base) : 17839.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
         -10 (-0.82% of base) : 7229.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.40% of base) : 9103.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-2.42% of base) : 23039.dasm - System.Formats.Cbor.CborWriter:WriteInitialByte(System.Formats.Cbor.CborInitialByte):this
          -8 (-0.41% of base) : 5509.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -7 (-0.55% of base) : 9329.dasm - System.Threading.Barrier:SignalAndWait(int,System.Threading.CancellationToken):bool:this
          -7 (-2.41% of base) : 17981.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -5 (-2.66% of base) : 14126.dasm - System.Formats.Cbor.Tests.ECDsaCosePublicKeyHelper:<ReadECParametersAsCosePublicKey>g__TryReadCoseKeyLabel|1_3(int,byref):bool
          -5 (-0.72% of base) : 9102.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 7285.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 9104.dasm - DynamicClass:WriteArrayOfMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -4 (-0.34% of base) : 9109.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.60% of base) : 4254.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this

Top method regressions (percentages):
           4 ( 3.85% of base) : 3954.dasm - Microsoft.Extensions.Logging.MessageLogger:IsEnabled(int):bool:this
           5 ( 2.89% of base) : 10509.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           4 ( 2.48% of base) : 6097.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
          10 ( 1.87% of base) : 14143.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           7 ( 0.66% of base) : 10506.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           3 ( 0.18% of base) : 15020.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadField(System.Reflection.FieldInfo,System.Nullable`1[Boolean],System.Nullable`1[Int32]):Sigil.Emit`1[__Canon]:this
           3 ( 0.14% of base) : 9223.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:SetEntry(Microsoft.Extensions.Caching.Memory.CacheEntry):this

Top method improvements (percentages):
          -3 (-27.27% of base) : 8722.dasm - <>c:<CollapseAndVerify>b__27_0(Sigil.Impl.StackTransition):bool:this
         -10 (-5.88% of base) : 17839.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.17% of base) : 23042.dasm - System.Formats.Cbor.CborWriter:AdvanceDataItemCounters():this
          -3 (-3.95% of base) : 18113.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -3 (-3.70% of base) : 14129.dasm - System.Formats.Cbor.CborReader:AdvanceDataItemCounters():this
         -18 (-2.80% of base) : 10479.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
          -5 (-2.66% of base) : 14126.dasm - System.Formats.Cbor.Tests.ECDsaCosePublicKeyHelper:<ReadECParametersAsCosePublicKey>g__TryReadCoseKeyLabel|1_3(int,byref):bool
          -8 (-2.42% of base) : 23039.dasm - System.Formats.Cbor.CborWriter:WriteInitialByte(System.Formats.Cbor.CborInitialByte):this
          -7 (-2.41% of base) : 17981.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -4 (-2.27% of base) : 9224.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:UpdateCacheSizeExceedsCapacity(Microsoft.Extensions.Caching.Memory.CacheEntry):bool:this
          -3 (-2.13% of base) : 6073.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineNumberHandlingForTypeInfo(System.Nullable`1[JsonNumberHandling]):this
          -3 (-2.05% of base) : 6098.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineNumberHandlingForProperty(System.Nullable`1[JsonNumberHandling],System.Nullable`1[JsonNumberHandling]):this
          -3 (-1.47% of base) : 5926.dasm - Newtonsoft.Json.JsonReader:Pop():int:this
         -18 (-1.19% of base) : 2751.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this
          -3 (-1.05% of base) : 23051.dasm - System.Formats.Cbor.CborWriter:WriteByteString(System.ReadOnlySpan`1[Byte]):this
         -10 (-0.82% of base) : 7229.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.82% of base) : 9101.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.79% of base) : 2971.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:CreateProperty(System.Reflection.MemberInfo,int):Newtonsoft.Json.Serialization.JsonProperty:this
          -5 (-0.72% of base) : 9102.dasm - DynamicClass:WriteArrayOfMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)
          -5 (-0.72% of base) : 7285.dasm - DynamicClass:WriteArrayOfActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.CollectionDataContract)

53 total methods with Code Size differences (46 improved, 7 regressed), 29 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 89251
Total bytes of diff: 87508
Total bytes of delta: -1743 (-1.95% of base)
Total relative delta: -6.04
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          17 : 171304.dasm (26.56% of base)

Top file improvements (bytes):
        -760 : 79908.dasm (-10.92% of base)
         -52 : 167303.dasm (-4.13% of base)
         -41 : 133760.dasm (-0.87% of base)
         -41 : 136203.dasm (-0.87% of base)
         -14 : 167304.dasm (-1.08% of base)
         -11 : 223929.dasm (-3.93% of base)
         -10 : 102384.dasm (-1.47% of base)
         -10 : 229751.dasm (-1.47% of base)
         -10 : 230683.dasm (-1.47% of base)
         -10 : 173399.dasm (-1.47% of base)
         -10 : 229641.dasm (-1.47% of base)
         -10 : 229993.dasm (-1.47% of base)
         -10 : 101640.dasm (-1.47% of base)
         -10 : 172361.dasm (-1.47% of base)
         -10 : 229949.dasm (-1.47% of base)
         -10 : 225056.dasm (-1.47% of base)
         -10 : 229585.dasm (-1.47% of base)
         -10 : 229892.dasm (-1.47% of base)
         -10 : 174339.dasm (-1.47% of base)
         -10 : 230281.dasm (-1.47% of base)

151 total files with Code Size differences (150 improved, 1 regressed), 18 unchanged.

Top method regressions (bytes):
          17 (26.56% of base) : 171304.dasm - NullableTest3:BoxUnboxToQGenC(System.Nullable`1[Byte]):bool

Top method improvements (bytes):
        -760 (-10.92% of base) : 79908.dasm - JitTest.Test:Main():int
         -52 (-4.13% of base) : 167303.dasm - Internal.IL.ILImporter:CheckIsValidLeaveTarget(BasicBlock,BasicBlock):this
         -41 (-0.87% of base) : 133760.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -41 (-0.87% of base) : 136203.dasm - testout1:Func_0_5_2_1_3():System.Decimal
         -14 (-1.08% of base) : 167304.dasm - Internal.IL.ILImporter:IsValidBranchTarget(BasicBlock,BasicBlock,bool,bool):bool:this
         -11 (-3.93% of base) : 223929.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
         -10 (-1.47% of base) : 102384.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229751.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 230683.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 173399.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229641.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229993.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 101640.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 172361.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229949.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 225056.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229585.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 229892.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 174339.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -10 (-1.47% of base) : 230281.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool

Top method regressions (percentages):
          17 (26.56% of base) : 171304.dasm - NullableTest3:BoxUnboxToQGenC(System.Nullable`1[Byte]):bool

Top method improvements (percentages):
        -760 (-10.92% of base) : 79908.dasm - JitTest.Test:Main():int
          -6 (-6.90% of base) : 101889.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 102366.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 172343.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 173391.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 214917.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 229573.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 230748.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 101895.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 102118.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 214912.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 229567.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 229734.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-6.90% of base) : 102124.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 174514.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 230750.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 229739.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 101627.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 172349.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-6.90% of base) : 173394.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool

151 total methods with Code Size differences (150 improved, 1 regressed), 18 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 381252
Total bytes of diff: 379250
Total bytes of delta: -2002 (-0.53% of base)
Total relative delta: -7.74
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 183436.dasm (1.67% of base)
           2 : 70063.dasm (2.60% of base)
           2 : 70064.dasm (2.70% of base)

Top file improvements (bytes):
         -31 : 137440.dasm (-3.43% of base)
         -20 : 212815.dasm (-1.13% of base)
         -19 : 4989.dasm (-1.60% of base)
         -15 : 20061.dasm (-0.50% of base)
         -15 : 103534.dasm (-0.38% of base)
         -14 : 26951.dasm (-0.70% of base)
         -13 : 55885.dasm (-3.54% of base)
         -13 : 55886.dasm (-3.45% of base)
         -13 : 20081.dasm (-2.28% of base)
         -12 : 20010.dasm (-0.26% of base)
         -12 : 26669.dasm (-0.45% of base)
         -12 : 20049.dasm (-0.51% of base)
         -11 : 135405.dasm (-5.56% of base)
         -10 : 175768.dasm (-2.49% of base)
         -10 : 22942.dasm (-1.01% of base)
          -9 : 19897.dasm (-0.45% of base)
          -9 : 20062.dasm (-0.60% of base)
          -9 : 34442.dasm (-0.46% of base)
          -9 : 4155.dasm (-3.12% of base)
          -9 : 106332.dasm (-0.20% of base)

492 total files with Code Size differences (489 improved, 3 regressed), 16 unchanged.

Top method regressions (bytes):
          16 ( 1.67% of base) : 183436.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.Int64[]:this
           2 ( 2.60% of base) : 70063.dasm - ConfiguredNoThrowAwaiter`1:OnCompleted(System.Action):this
           2 ( 2.70% of base) : 70064.dasm - ConfiguredNoThrowAwaiter`1:UnsafeOnCompleted(System.Action):this

Top method improvements (bytes):
         -31 (-3.43% of base) : 137440.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:FindMethodSymbolInSuperType(System.Reflection.Metadata.TypeDefinitionHandle,System.Reflection.Metadata.MethodDefinitionHandle):System.__Canon:this
         -20 (-1.13% of base) : 212815.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -19 (-1.60% of base) : 4989.dasm - RetargetingSymbolTranslator:FindPropertyInRetargetedType(Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol:this
         -15 (-0.50% of base) : 20061.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
         -15 (-0.38% of base) : 103534.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -14 (-0.70% of base) : 26951.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -13 (-3.54% of base) : 55885.dasm - ConfiguredValueTaskAwaiter:UnsafeOnCompleted(System.Action):this
         -13 (-3.45% of base) : 55886.dasm - ConfiguredValueTaskAwaiter:OnCompleted(System.Action):this
         -13 (-2.28% of base) : 20081.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.26% of base) : 20010.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-0.45% of base) : 26669.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -12 (-0.51% of base) : 20049.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -11 (-5.56% of base) : 135405.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
         -10 (-2.49% of base) : 175768.dasm - System.Net.Mail.SmtpClient:SendMailCallback(System.IAsyncResult):this
         -10 (-1.01% of base) : 22942.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
          -9 (-0.45% of base) : 19897.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitUsingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUsingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-0.60% of base) : 20062.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:CreateLoweredWhileStatements(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundLocal,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool):Microsoft.CodeAnalysis.VisualBasic.BoundStatementList:this
          -9 (-0.46% of base) : 34442.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadDecimalFormat(System.Xml.Xsl.Xslt.NsDecl):this
          -9 (-3.12% of base) : 4155.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -9 (-0.20% of base) : 106332.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.CSharp.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.CSharp.CSharpCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock

Top method regressions (percentages):
           2 ( 2.70% of base) : 70064.dasm - ConfiguredNoThrowAwaiter`1:UnsafeOnCompleted(System.Action):this
           2 ( 2.60% of base) : 70063.dasm - ConfiguredNoThrowAwaiter`1:OnCompleted(System.Action):this
          16 ( 1.67% of base) : 183436.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.Int64[]:this

Top method improvements (percentages):
          -3 (-30.00% of base) : 130488.dasm - Microsoft.CSharp.RuntimeBinder.RuntimeBinder:get_IsChecked():bool:this
          -6 (-16.67% of base) : 104384.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:IntersectWith(byref,byref):bool:this
          -3 (-12.50% of base) : 130545.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:get_IsChecked():bool:this
          -3 (-12.50% of base) : 130627.dasm - Microsoft.CSharp.RuntimeBinder.CSharpConvertBinder:get_IsChecked():bool:this
          -3 (-12.50% of base) : 130563.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetIndexBinder:get_IsChecked():bool:this
          -3 (-12.50% of base) : 130554.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetMemberBinder:get_IsChecked():bool:this
          -3 (-12.50% of base) : 130634.dasm - Microsoft.CSharp.RuntimeBinder.CSharpBinaryOperationBinder:get_IsChecked():bool:this
          -3 (-9.38% of base) : 90773.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
          -8 (-8.89% of base) : 135350.dasm - Microsoft.CodeAnalysis.Emit.AnonymousTypeKey:Equals(System.Object):bool:this
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

492 total methods with Code Size differences (489 improved, 3 regressed), 16 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 519183
Total bytes of diff: 516438
Total bytes of delta: -2745 (-0.53% of base)
Total relative delta: -9.25
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          69 : 162536.dasm (5.34% of base)
          39 : 195803.dasm (3.65% of base)
          37 : 195784.dasm (3.51% of base)
          25 : 74987.dasm (80.65% of base)
          25 : 46188.dasm (80.65% of base)
          17 : 74986.dasm (13.71% of base)
          17 : 164000.dasm (6.49% of base)
          17 : 46187.dasm (13.71% of base)
          11 : 208321.dasm (2.58% of base)
          10 : 191123.dasm (1.87% of base)
           7 : 107522.dasm (0.65% of base)
           6 : 23629.dasm (0.33% of base)
           5 : 202395.dasm (0.10% of base)
           5 : 107525.dasm (2.89% of base)
           4 : 155917.dasm (2.48% of base)
           4 : 164349.dasm (3.85% of base)
           4 : 208368.dasm (0.89% of base)
           3 : 161403.dasm (0.14% of base)
           2 : 208371.dasm (0.83% of base)
           2 : 208373.dasm (0.90% of base)

Top file improvements (bytes):
         -50 : 29023.dasm (-2.37% of base)
         -43 : 167154.dasm (-12.36% of base)
         -43 : 167156.dasm (-12.36% of base)
         -39 : 107862.dasm (-28.68% of base)
         -34 : 126354.dasm (-6.23% of base)
         -29 : 78258.dasm (-7.23% of base)
         -29 : 78201.dasm (-7.21% of base)
         -25 : 126442.dasm (-10.59% of base)
         -22 : 85649.dasm (-1.00% of base)
         -18 : 105817.dasm (-2.80% of base)
         -18 : 105824.dasm (-1.19% of base)
         -18 : 188328.dasm (-0.67% of base)
         -16 : 56893.dasm (-2.02% of base)
         -15 : 109404.dasm (-0.88% of base)
         -15 : 219027.dasm (-1.00% of base)
         -15 : 50055.dasm (-0.47% of base)
         -14 : 57347.dasm (-7.45% of base)
         -14 : 78188.dasm (-8.48% of base)
         -14 : 180885.dasm (-0.22% of base)
         -13 : 146378.dasm (-0.10% of base)

650 total files with Code Size differences (629 improved, 21 regressed), 381 unchanged.

Top method regressions (bytes):
          69 ( 5.34% of base) : 162536.dasm - Microsoft.Extensions.DependencyModel.DependencyContextWriter:WriteCompilationOptions(Microsoft.Extensions.DependencyModel.CompilationOptions,System.Text.Json.Utf8JsonWriter):this
          39 ( 3.65% of base) : 195803.dasm - System.Linq.Parallel.QueryOperator`1[Byte][System.Byte]:ExecuteAndGetResultsAsArray():System.Byte[]:this
          37 ( 3.51% of base) : 195784.dasm - System.Linq.Parallel.QueryOperator`1[__Canon][System.__Canon]:ExecuteAndGetResultsAsArray():System.__Canon[]:this
          25 (80.65% of base) : 74987.dasm - _Closure$__:_Lambda$__2-0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          25 (80.65% of base) : 46188.dasm - <>c:<ComputeDeclarationsInNode>b__1_0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          17 (13.71% of base) : 74986.dasm - _Closure$__1-0:_Lambda$__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          17 ( 6.49% of base) : 164000.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:WriteToConsole(System.String,int,int,System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):this
          17 (13.71% of base) : 46187.dasm - <>c__DisplayClass0_0:<ComputeDeclarationsInSpan>b__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 ( 2.58% of base) : 208321.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
          10 ( 1.87% of base) : 191123.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           7 ( 0.65% of base) : 107522.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           6 ( 0.33% of base) : 23629.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindArrayCreationWithInitializer(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InitializerExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Symbols.ArrayTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.BoundArrayCreation:this
           5 ( 0.10% of base) : 202395.dasm - <Process>d__19:MoveNext():this
           5 ( 2.89% of base) : 107525.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           4 ( 2.48% of base) : 155917.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
           4 ( 3.85% of base) : 164349.dasm - Microsoft.Extensions.Logging.MessageLogger:IsEnabled(int):bool:this
           4 ( 0.89% of base) : 208368.dasm - System.Net.WebClient:DownloadStringAsyncCallback(System.Byte[],System.Exception,System.Object):this
           3 ( 0.14% of base) : 161403.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:SetEntry(Microsoft.Extensions.Caching.Memory.CacheEntry):this
           2 ( 0.83% of base) : 208371.dasm - System.Net.WebClient:DownloadDataAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.90% of base) : 208373.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this

Top method improvements (bytes):
         -50 (-2.37% of base) : 29023.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteLiftedConversionInExpressionTree(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ubyte,bool,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -43 (-12.36% of base) : 167154.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForCondition(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
         -43 (-12.36% of base) : 167156.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForGlob(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
         -39 (-28.68% of base) : 107862.dasm - Newtonsoft.Json.Schema.JsonSchemaGenerator:HasFlag(System.Nullable`1[JsonSchemaType],int):bool
         -34 (-6.23% of base) : 126354.dasm - System.Net.Http.Headers.CacheControlHeaderValue:Equals(System.Object):bool:this
         -29 (-7.23% of base) : 78258.dasm - Microsoft.CodeAnalysis.PortableExecutableReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.PortableExecutableReference:this
         -29 (-7.21% of base) : 78201.dasm - Microsoft.CodeAnalysis.MetadataReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.MetadataReference:this
         -25 (-10.59% of base) : 126442.dasm - System.Net.Http.Headers.ContentRangeHeaderValue:Equals(System.Object):bool:this
         -22 (-1.00% of base) : 85649.dasm - Microsoft.Diagnostics.Tracing.Session.TraceEventSession:CleanFilterDataForEtwSession():this
         -18 (-2.80% of base) : 105817.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
         -18 (-1.19% of base) : 105824.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this
         -18 (-0.67% of base) : 188328.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -16 (-2.02% of base) : 56893.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -15 (-0.88% of base) : 109404.dasm - <ExecuteFilter>d__12:MoveNext():bool:this
         -15 (-1.00% of base) : 219027.dasm - System.Security.Cryptography.Pkcs.Rfc3161TimestampTokenInfo:TryDecode(System.ReadOnlyMemory`1[Byte],bool,byref,byref,byref):bool
         -15 (-0.47% of base) : 50055.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -14 (-7.45% of base) : 57347.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -14 (-8.48% of base) : 78188.dasm - Microsoft.CodeAnalysis.CompilationReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.CompilationReference:this
         -14 (-0.22% of base) : 180885.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -13 (-0.10% of base) : 146378.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this

Top method regressions (percentages):
          25 (80.65% of base) : 74987.dasm - _Closure$__:_Lambda$__2-0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          25 (80.65% of base) : 46188.dasm - <>c:<ComputeDeclarationsInNode>b__1_0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          17 (13.71% of base) : 74986.dasm - _Closure$__1-0:_Lambda$__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          17 (13.71% of base) : 46187.dasm - <>c__DisplayClass0_0:<ComputeDeclarationsInSpan>b__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          17 ( 6.49% of base) : 164000.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:WriteToConsole(System.String,int,int,System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):this
          69 ( 5.34% of base) : 162536.dasm - Microsoft.Extensions.DependencyModel.DependencyContextWriter:WriteCompilationOptions(Microsoft.Extensions.DependencyModel.CompilationOptions,System.Text.Json.Utf8JsonWriter):this
           4 ( 3.85% of base) : 164349.dasm - Microsoft.Extensions.Logging.MessageLogger:IsEnabled(int):bool:this
          39 ( 3.65% of base) : 195803.dasm - System.Linq.Parallel.QueryOperator`1[Byte][System.Byte]:ExecuteAndGetResultsAsArray():System.Byte[]:this
          37 ( 3.51% of base) : 195784.dasm - System.Linq.Parallel.QueryOperator`1[__Canon][System.__Canon]:ExecuteAndGetResultsAsArray():System.__Canon[]:this
           5 ( 2.89% of base) : 107525.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
          11 ( 2.58% of base) : 208321.dasm - System.Net.WebClient:<UploadStringAsync>b__178_0(System.Byte[],System.Exception,System.ComponentModel.AsyncOperation):this
           4 ( 2.48% of base) : 155917.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
          10 ( 1.87% of base) : 191123.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           2 ( 0.90% of base) : 208373.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this
           4 ( 0.89% of base) : 208368.dasm - System.Net.WebClient:DownloadStringAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.83% of base) : 208371.dasm - System.Net.WebClient:DownloadDataAsyncCallback(System.Byte[],System.Exception,System.Object):this
           7 ( 0.65% of base) : 107522.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           6 ( 0.33% of base) : 23629.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindArrayCreationWithInitializer(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InitializerExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Symbols.ArrayTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.BoundArrayCreation:this
           2 ( 0.22% of base) : 55239.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCommandLineArguments:ResolveMetadataReferences(Microsoft.CodeAnalysis.MetadataReferenceResolver,System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.DiagnosticInfo, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CommonMessageProvider,System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.MetadataReference, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):bool:this
           3 ( 0.14% of base) : 161403.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:SetEntry(Microsoft.Extensions.Caching.Memory.CacheEntry):this

Top method improvements (percentages):
          -3 (-30.00% of base) : 21521.dasm - Microsoft.CSharp.RuntimeBinder.RuntimeBinder:get_IsChecked():bool:this
         -39 (-28.68% of base) : 107862.dasm - Newtonsoft.Json.Schema.JsonSchemaGenerator:HasFlag(System.Nullable`1[JsonSchemaType],int):bool
          -3 (-21.43% of base) : 21415.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetMemberBinder:get_IsChecked():bool:this
          -3 (-21.43% of base) : 21424.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:get_IsChecked():bool:this
          -3 (-21.43% of base) : 21332.dasm - Microsoft.CSharp.RuntimeBinder.CSharpBinaryOperationBinder:get_IsChecked():bool:this
          -3 (-21.43% of base) : 21341.dasm - Microsoft.CSharp.RuntimeBinder.CSharpConvertBinder:get_IsChecked():bool:this
          -3 (-21.43% of base) : 21407.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetIndexBinder:get_IsChecked():bool:this
         -11 (-18.33% of base) : 31144.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:DecrementLevel(System.Nullable`1[Int32]):System.Nullable`1[Int32]
          -6 (-16.67% of base) : 28260.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:IntersectWith(byref,byref):bool:this
         -43 (-12.36% of base) : 167154.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForCondition(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
         -43 (-12.36% of base) : 167156.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForGlob(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
         -25 (-10.59% of base) : 126442.dasm - System.Net.Http.Headers.ContentRangeHeaderValue:Equals(System.Object):bool:this
         -14 (-8.48% of base) : 78188.dasm - Microsoft.CodeAnalysis.CompilationReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.CompilationReference:this
          -8 (-8.42% of base) : 80005.dasm - Microsoft.CodeAnalysis.Emit.AnonymousTypeKey:Equals(System.Object):bool:this
          -4 (-8.00% of base) : 48458.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
         -14 (-7.45% of base) : 57347.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-7.32% of base) : 157072.dasm - CommandLine.NamedError:GetHashCode():int:this
          -6 (-7.32% of base) : 157066.dasm - CommandLine.TokenError:GetHashCode():int:this
         -29 (-7.23% of base) : 78258.dasm - Microsoft.CodeAnalysis.PortableExecutableReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.PortableExecutableReference:this
         -29 (-7.21% of base) : 78201.dasm - Microsoft.CodeAnalysis.MetadataReference:WithEmbedInteropTypes(bool):Microsoft.CodeAnalysis.MetadataReference:this

650 total methods with Code Size differences (629 improved, 21 regressed), 381 unchanged.

```

</details>

--------------------------------------------------------------------------------

