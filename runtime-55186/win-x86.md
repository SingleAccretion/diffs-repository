## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 100143
Total bytes of diff: 100270
Total bytes of delta: 127 (0.13% of base)
Total relative delta: -0.66
    diff is a regression.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         176 : 1338.dasm (4.45% of base)
         116 : 6557.dasm (1.35% of base)
          12 : 12567.dasm (0.06% of base)
           8 : 13071.dasm (1.86% of base)
           8 : 7803.dasm (1.02% of base)
           6 : 2339.dasm (0.94% of base)
           5 : 5995.dasm (3.47% of base)
           5 : 10148.dasm (3.03% of base)
           3 : 10145.dasm (0.39% of base)
           3 : 13780.dasm (0.21% of base)

Top file improvements (bytes):
         -19 : 3231.dasm (-0.16% of base)
         -15 : 10118.dasm (-2.66% of base)
         -14 : 1420.dasm (-0.53% of base)
         -10 : 2730.dasm (-0.93% of base)
          -9 : 16382.dasm (-7.09% of base)
          -9 : 11706.dasm (-0.74% of base)
          -9 : 8848.dasm (-0.86% of base)
          -9 : 8850.dasm (-0.44% of base)
          -9 : 8856.dasm (-1.02% of base)
          -6 : 7166.dasm (-0.39% of base)
          -6 : 16321.dasm (-0.19% of base)
          -6 : 5433.dasm (-0.37% of base)
          -6 : 7101.dasm (-0.69% of base)
          -5 : 3383.dasm (-0.88% of base)
          -3 : 20727.dasm (-1.11% of base)
          -3 : 4216.dasm (-0.61% of base)
          -3 : 16655.dasm (-4.76% of base)
          -3 : 20730.dasm (-4.69% of base)
          -3 : 13054.dasm (-2.00% of base)
          -3 : 15275.dasm (-0.27% of base)

53 total files with Code Size differences (43 improved, 10 regressed), 27 unchanged.

Top method regressions (bytes):
         176 ( 4.45% of base) : 1338.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
         116 ( 1.35% of base) : 6557.dasm - MessagePack.Internal.ObjectSerializationInfo:CreateOrNull(System.Type,bool,bool,bool):MessagePack.Internal.ObjectSerializationInfo
          12 ( 0.06% of base) : 12567.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)
           8 ( 1.86% of base) : 13071.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           8 ( 1.02% of base) : 7803.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Int32,Int32][System.Int32,System.Int32]:TryAddInternal(int,System.Nullable`1[Int32],int,bool,bool,byref):bool:this
           6 ( 0.94% of base) : 2339.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
           5 ( 3.47% of base) : 5995.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
           5 ( 3.03% of base) : 10148.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           3 ( 0.39% of base) : 10145.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           3 ( 0.21% of base) : 13780.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadField(System.Reflection.FieldInfo,System.Nullable`1[Boolean],System.Nullable`1[Int32]):Sigil.Emit`1[__Canon]:this

Top method improvements (bytes):
         -19 (-0.16% of base) : 3231.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -15 (-2.66% of base) : 10118.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
         -14 (-0.53% of base) : 1420.dasm - ProtoBuf.Meta.MetaType:BuildSerializer():ProtoBuf.Internal.Serializers.IProtoTypeSerializer:this
         -10 (-0.93% of base) : 2730.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this
          -9 (-7.09% of base) : 16382.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -9 (-0.74% of base) : 11706.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.86% of base) : 8848.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.44% of base) : 8850.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-1.02% of base) : 8856.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.39% of base) : 7166.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -6 (-0.19% of base) : 16321.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -6 (-0.37% of base) : 5433.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
          -6 (-0.69% of base) : 7101.dasm - DynamicClass:WriteIndexViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -5 (-0.88% of base) : 3383.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -3 (-1.11% of base) : 20727.dasm - System.Formats.Cbor.CborWriter:WriteInitialByte(System.Formats.Cbor.CborInitialByte):this
          -3 (-0.61% of base) : 4216.dasm - System.Threading.ThreadLocal`1[__Canon][System.__Canon]:SetValueSlow(System.__Canon,System.Threading.ThreadLocal`1+LinkedSlotVolatile[System.__Canon][]):this
          -3 (-4.76% of base) : 16655.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -3 (-4.69% of base) : 20730.dasm - System.Formats.Cbor.CborWriter:AdvanceDataItemCounters():this
          -3 (-2.00% of base) : 13054.dasm - System.Formats.Cbor.Tests.ECDsaCosePublicKeyHelper:<ReadECParametersAsCosePublicKey>g__TryReadCoseKeyLabel|1_3(int,byref):bool
          -3 (-0.27% of base) : 15275.dasm - Microsoft.CodeAnalysis.Compilation:ConstructModuleSerializationProperties(Microsoft.CodeAnalysis.Emit.EmitOptions,System.String,System.Guid):Microsoft.Cci.ModulePropertiesForSerialization:this

Top method regressions (percentages):
         176 ( 4.45% of base) : 1338.dasm - ProtoBuf.Meta.MetaType:NormalizeProtoMember(System.Reflection.MemberInfo,int,bool,bool,System.Collections.Generic.List`1[[ProtoBuf.Meta.AttributeMap, protobuf-net, Version=3.0.0.0, Culture=neutral, PublicKeyToken=257b51d87d2e4d67]],int,bool,byref,System.Reflection.MemberInfo):ProtoBuf.ProtoMemberAttribute
           5 ( 3.47% of base) : 5995.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
           5 ( 3.03% of base) : 10148.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           8 ( 1.86% of base) : 13071.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
         116 ( 1.35% of base) : 6557.dasm - MessagePack.Internal.ObjectSerializationInfo:CreateOrNull(System.Type,bool,bool,bool):MessagePack.Internal.ObjectSerializationInfo
           8 ( 1.02% of base) : 7803.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Int32,Int32][System.Int32,System.Int32]:TryAddInternal(int,System.Nullable`1[Int32],int,bool,bool,byref):bool:this
           6 ( 0.94% of base) : 2339.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
           3 ( 0.39% of base) : 10145.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CalculatePropertyDetails(Newtonsoft.Json.Serialization.JsonProperty,byref,Newtonsoft.Json.Serialization.JsonContainerContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.JsonReader,System.Object,byref,byref,byref,byref,byref):bool:this
           3 ( 0.21% of base) : 13780.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadField(System.Reflection.FieldInfo,System.Nullable`1[Boolean],System.Nullable`1[Int32]):Sigil.Emit`1[__Canon]:this
          12 ( 0.06% of base) : 12567.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)

Top method improvements (percentages):
          -3 (-30.00% of base) : 8472.dasm - <>c:<CollapseAndVerify>b__27_0(Sigil.Impl.StackTransition):bool:this
          -9 (-7.09% of base) : 16382.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitConversion(Microsoft.CodeAnalysis.CSharp.BoundConversion):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-4.76% of base) : 16655.dasm - Microsoft.CodeAnalysis.AssemblyIdentity:GetHashCodeIgnoringNameAndVersion():int:this
          -3 (-4.69% of base) : 20730.dasm - System.Formats.Cbor.CborWriter:AdvanceDataItemCounters():this
          -3 (-4.11% of base) : 13057.dasm - System.Formats.Cbor.CborReader:AdvanceDataItemCounters():this
          -3 (-3.70% of base) : 3930.dasm - Microsoft.Extensions.Logging.MessageLogger:IsEnabled(int):bool:this
         -15 (-2.66% of base) : 10118.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
          -3 (-2.54% of base) : 5971.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineNumberHandlingForTypeInfo(System.Nullable`1[JsonNumberHandling]):this
          -3 (-2.46% of base) : 5996.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineNumberHandlingForProperty(System.Nullable`1[JsonNumberHandling],System.Nullable`1[JsonNumberHandling]):this
          -3 (-2.00% of base) : 13054.dasm - System.Formats.Cbor.Tests.ECDsaCosePublicKeyHelper:<ReadECParametersAsCosePublicKey>g__TryReadCoseKeyLabel|1_3(int,byref):bool
          -3 (-1.69% of base) : 5824.dasm - Newtonsoft.Json.JsonReader:Pop():int:this
          -3 (-1.12% of base) : 20739.dasm - System.Formats.Cbor.CborWriter:WriteByteString(System.ReadOnlySpan`1[Byte]):this
          -3 (-1.11% of base) : 20727.dasm - System.Formats.Cbor.CborWriter:WriteInitialByte(System.Formats.Cbor.CborInitialByte):this
          -3 (-1.09% of base) : 8969.dasm - Microsoft.Extensions.Caching.Memory.MemoryCache:UpdateCacheSizeExceedsCapacity(Microsoft.Extensions.Caching.Memory.CacheEntry):bool:this
          -9 (-1.02% of base) : 8856.dasm - DynamicClass:WriteMyEventsListerItemTaskToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -3 (-0.95% of base) : 2949.dasm - Newtonsoft.Json.Serialization.DefaultContractResolver:CreateProperty(System.Reflection.MemberInfo,int):Newtonsoft.Json.Serialization.JsonProperty:this
         -10 (-0.93% of base) : 2730.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this
          -5 (-0.88% of base) : 3383.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,int,int,int,bool,System.TimeSpan):System.Text.RegularExpressions.Match:this
          -9 (-0.86% of base) : 8848.dasm - DynamicClass:WriteMyEventsListerViewModelToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -9 (-0.74% of base) : 11706.dasm - DynamicClass:WriteCollectionsOfPrimitivesToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])

53 total methods with Code Size differences (43 improved, 10 regressed), 27 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 198556
Total bytes of diff: 197850
Total bytes of delta: -706 (-0.36% of base)
Total relative delta: -7.20
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         136 : 218794.dasm (0.17% of base)
         136 : 218800.dasm (0.17% of base)
          11 : 170366.dasm (22.00% of base)
           2 : 91.dasm (0.31% of base)

Top file improvements (bytes):
         -62 : 167295.dasm (-4.61% of base)
         -60 : 167294.dasm (-3.65% of base)
         -21 : 86080.dasm (-3.66% of base)
         -12 : 229636.dasm (-1.93% of base)
         -12 : 214785.dasm (-1.93% of base)
         -12 : 230088.dasm (-1.93% of base)
         -12 : 102333.dasm (-1.93% of base)
         -12 : 172493.dasm (-1.93% of base)
         -12 : 173355.dasm (-1.93% of base)
         -12 : 174477.dasm (-1.93% of base)
         -12 : 230459.dasm (-1.93% of base)
         -12 : 101856.dasm (-1.93% of base)
         -12 : 229347.dasm (-1.93% of base)
         -12 : 229524.dasm (-1.93% of base)
         -12 : 230241.dasm (-1.93% of base)
         -12 : 171154.dasm (-1.93% of base)
         -12 : 174286.dasm (-1.93% of base)
         -12 : 101585.dasm (-1.93% of base)
         -12 : 102085.dasm (-1.93% of base)
         -12 : 214534.dasm (-1.93% of base)

148 total files with Code Size differences (144 improved, 4 regressed), 15 unchanged.

Top method regressions (bytes):
         136 ( 0.17% of base) : 218794.dasm - testout1:Func_0():int
         136 ( 0.17% of base) : 218800.dasm - testout1:Func_0():int
          11 (22.00% of base) : 170366.dasm - NullableTest3:BoxUnboxToQGenC(System.Nullable`1[Byte]):bool
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this

Top method improvements (bytes):
         -62 (-4.61% of base) : 167295.dasm - Internal.IL.ILImporter:IsValidBranchTarget(BasicBlock,BasicBlock,bool,bool):bool:this
         -60 (-3.65% of base) : 167294.dasm - Internal.IL.ILImporter:CheckIsValidLeaveTarget(BasicBlock,BasicBlock):this
         -21 (-3.66% of base) : 86080.dasm - ILGEN_0xace3f910:Method_0xf9cc7d6a(long,long,float,int,ushort,int,long,long,long):float
         -12 (-1.93% of base) : 229636.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 214785.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 230088.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 102333.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 172493.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 173355.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 174477.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 230459.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 101856.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 229347.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 229524.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 230241.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 171154.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 174286.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 101585.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 102085.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool
         -12 (-1.93% of base) : 214534.dasm - Helper:Compare(MixedAllStruct,MixedAllStruct):bool

Top method regressions (percentages):
          11 (22.00% of base) : 170366.dasm - NullableTest3:BoxUnboxToQGenC(System.Nullable`1[Byte]):bool
           2 ( 0.31% of base) : 91.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
         136 ( 0.17% of base) : 218800.dasm - testout1:Func_0():int
         136 ( 0.17% of base) : 218794.dasm - testout1:Func_0():int

Top method improvements (percentages):
          -6 (-9.38% of base) : 101628.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 102116.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 102370.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 172524.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 173380.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 229489.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 229665.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 101893.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 171191.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 214814.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 229494.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 230573.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 174503.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 229384.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 229670.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 174316.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 214819.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 229378.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool
          -6 (-9.38% of base) : 102122.dasm - Helper:Compare(NotEmptyStructConstrainedGenQ`1[Int32],NotEmptyStructConstrainedGenQ`1[Int32]):bool
          -6 (-9.38% of base) : 102364.dasm - Helper:Compare(NotEmptyStructQ,NotEmptyStructQ):bool

148 total methods with Code Size differences (144 improved, 4 regressed), 15 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 306522
Total bytes of diff: 304604
Total bytes of delta: -1918 (-0.63% of base)
Total relative delta: -9.27
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
         -15 : 207607.dasm (-0.84% of base)
         -15 : 130334.dasm (-0.38% of base)
         -15 : 79435.dasm (-0.61% of base)
         -12 : 79384.dasm (-0.34% of base)
         -12 : 79423.dasm (-0.55% of base)
         -12 : 79455.dasm (-2.89% of base)
         -12 : 86183.dasm (-0.68% of base)
         -12 : 190274.dasm (-3.17% of base)
         -12 : 85901.dasm (-0.55% of base)
         -11 : 82264.dasm (-1.44% of base)
         -10 : 170096.dasm (-4.95% of base)
         -10 : 152662.dasm (-0.98% of base)
          -9 : 79306.dasm (-0.44% of base)
          -9 : 133146.dasm (-0.25% of base)
          -9 : 64717.dasm (-0.35% of base)
          -9 : 160736.dasm (-0.32% of base)
          -9 : 160746.dasm (-0.42% of base)
          -9 : 79436.dasm (-0.82% of base)
          -9 : 133127.dasm (-0.25% of base)
          -9 : 160756.dasm (-0.41% of base)

491 total files with Code Size differences (487 improved, 4 regressed), 16 unchanged.

Top method regressions (bytes):
           6 ( 1.37% of base) : 209266.dasm - System.Linq.Parallel.TakeOrSkipWhileQueryOperator`1:WrapHelper(System.Linq.Parallel.PartitionedStream`2[System.__Canon, System.__Canon],System.Linq.Parallel.IPartitionedStreamRecipient`1[System.__Canon],System.Linq.Parallel.QuerySettings):this
           3 ( 0.88% of base) : 180290.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this
           2 ( 1.50% of base) : 190184.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           2 ( 1.50% of base) : 190185.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this

Top method improvements (bytes):
         -15 (-0.84% of base) : 207607.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -15 (-0.38% of base) : 130334.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -15 (-0.61% of base) : 79435.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
         -12 (-0.34% of base) : 79384.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-0.55% of base) : 79423.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
         -12 (-2.89% of base) : 79455.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.68% of base) : 86183.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-3.17% of base) : 190274.dasm - System.Security.AccessControl.ObjectSecurity:UpdateWithNewSecurityDescriptor(System.Security.AccessControl.RawSecurityDescriptor,int):this
         -12 (-0.55% of base) : 85901.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -11 (-1.44% of base) : 82264.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
         -10 (-4.95% of base) : 170096.dasm - CommandLine.Text.HelpText:AddOptionName(int,CommandLine.Core.OptionSpecification):System.String:this
         -10 (-0.98% of base) : 152662.dasm - System.Xml.Schema.ParticleContentValidator:Finish(bool):System.Xml.Schema.ContentValidator:this
          -9 (-0.44% of base) : 79306.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitSyncLockStatement(Microsoft.CodeAnalysis.VisualBasic.BoundSyncLockStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-0.25% of base) : 133146.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:CompileMethod(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,int,byref,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.TypeCompilationState):this
          -9 (-0.35% of base) : 64717.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
          -9 (-0.32% of base) : 160736.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
          -9 (-0.42% of base) : 160746.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
          -9 (-0.82% of base) : 79436.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:CreateLoweredWhileStatements(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundLocal,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool):Microsoft.CodeAnalysis.VisualBasic.BoundStatementList:this
          -9 (-0.25% of base) : 133127.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:ConstructFieldLikeEventAccessorBody_Regular(Microsoft.CodeAnalysis.CSharp.Symbols.SourceEventSymbol,bool,Microsoft.CodeAnalysis.CSharp.CSharpCompilation,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock
          -9 (-0.41% of base) : 160756.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AndObject(System.Object,System.Object):System.Object

Top method regressions (percentages):
           2 ( 1.50% of base) : 190184.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
           2 ( 1.50% of base) : 190185.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this
           6 ( 1.37% of base) : 209266.dasm - System.Linq.Parallel.TakeOrSkipWhileQueryOperator`1:WrapHelper(System.Linq.Parallel.PartitionedStream`2[System.__Canon, System.__Canon],System.Linq.Parallel.IPartitionedStreamRecipient`1[System.__Canon],System.Linq.Parallel.QuerySettings):this
           3 ( 0.88% of base) : 180290.dasm - System.Diagnostics.Process:WaitForExitCore(int):bool:this

Top method improvements (percentages):
          -3 (-30.00% of base) : 40967.dasm - Microsoft.CSharp.RuntimeBinder.RuntimeBinder:get_IsChecked():bool:this
          -6 (-14.29% of base) : 131181.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:IntersectWith(byref,byref):bool:this
          -3 (-13.64% of base) : 41111.dasm - Microsoft.CSharp.RuntimeBinder.CSharpBinaryOperationBinder:get_IsChecked():bool:this
          -3 (-13.64% of base) : 41024.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:get_IsChecked():bool:this
          -3 (-13.64% of base) : 41033.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetMemberBinder:get_IsChecked():bool:this
          -3 (-13.64% of base) : 41042.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetIndexBinder:get_IsChecked():bool:this
          -3 (-13.64% of base) : 117728.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
          -3 (-13.64% of base) : 41105.dasm - Microsoft.CSharp.RuntimeBinder.CSharpConvertBinder:get_IsChecked():bool:this
          -6 (-9.52% of base) : 86996.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-7.89% of base) : 87571.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -3 (-7.14% of base) : 117033.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -6 (-7.14% of base) : 52412.dasm - Microsoft.CodeAnalysis.Emit.AnonymousTypeKey:Equals(System.Object):bool:this
          -3 (-6.82% of base) : 87038.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.67% of base) : 87037.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.52% of base) : 63490.dasm - LocalVariableSubstituter:VisitLocal(Microsoft.CodeAnalysis.VisualBasic.BoundLocal):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-6.45% of base) : 54163.dasm - Microsoft.CodeAnalysis.CompilationReference:WithAliases(System.Collections.Immutable.ImmutableArray`1[System.String]):Microsoft.CodeAnalysis.CompilationReference:this
          -6 (-6.38% of base) : 55177.dasm - Microsoft.CodeAnalysis.AssemblyPortabilityPolicy:Equals(System.Object):bool:this
          -6 (-6.00% of base) : 110934.dasm - leftJustify@875-4:Invoke(System.String,int,System.Object):System.String:this
          -3 (-6.00% of base) : 134141.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -3 (-6.00% of base) : 87030.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

491 total methods with Code Size differences (487 improved, 4 regressed), 16 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 430201
Total bytes of diff: 428162
Total bytes of delta: -2039 (-0.47% of base)
Total relative delta: -10.60
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          63 : 164923.dasm (6.35% of base)
          32 : 106808.dasm (0.95% of base)
          26 : 22956.dasm (1.93% of base)
          15 : 166307.dasm (22.06% of base)
          14 : 189422.dasm (0.76% of base)
          11 : 45502.dasm (9.48% of base)
          11 : 45503.dasm (36.67% of base)
          11 : 74292.dasm (9.48% of base)
          11 : 74293.dasm (36.67% of base)
          11 : 166311.dasm (5.26% of base)
          10 : 189465.dasm (1.25% of base)
           9 : 171596.dasm (1.36% of base)
           9 : 176725.dasm (4.29% of base)
           8 : 171532.dasm (1.10% of base)
           8 : 171564.dasm (1.14% of base)
           8 : 171344.dasm (1.28% of base)
           8 : 171419.dasm (1.20% of base)
           8 : 176684.dasm (2.23% of base)
           8 : 191167.dasm (1.86% of base)
           8 : 171500.dasm (1.23% of base)

Top file improvements (bytes):
         -40 : 107175.dasm (-27.97% of base)
         -20 : 206204.dasm (-1.20% of base)
         -19 : 147712.dasm (-0.16% of base)
         -18 : 127825.dasm (-5.92% of base)
         -17 : 30468.dasm (-26.98% of base)
         -15 : 218328.dasm (-1.26% of base)
         -15 : 169454.dasm (-2.56% of base)
         -15 : 105139.dasm (-2.66% of base)
         -12 : 189938.dasm (-0.46% of base)
         -12 : 56654.dasm (-8.96% of base)
         -12 : 128343.dasm (-5.80% of base)
         -12 : 191667.dasm (-1.00% of base)
         -12 : 214181.dasm (-2.05% of base)
         -12 : 105595.dasm (-1.18% of base)
         -12 : 109133.dasm (-0.23% of base)
         -12 : 56183.dasm (-1.74% of base)
         -12 : 49358.dasm (-0.42% of base)
         -11 : 169459.dasm (-2.98% of base)
         -11 : 49083.dasm (-0.29% of base)
         -10 : 105146.dasm (-0.93% of base)

656 total files with Code Size differences (614 improved, 42 regressed), 378 unchanged.

Top method regressions (bytes):
          63 ( 6.35% of base) : 164923.dasm - Microsoft.Extensions.DependencyModel.DependencyContextWriter:WriteCompilationOptions(Microsoft.Extensions.DependencyModel.CompilationOptions,System.Text.Json.Utf8JsonWriter):this
          32 ( 0.95% of base) : 106808.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:CreateObjectUsingCreatorWithParameters(Newtonsoft.Json.JsonReader,Newtonsoft.Json.Serialization.JsonObjectContract,Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.ObjectConstructor`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):System.Object:this
          26 ( 1.93% of base) : 22956.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindArrayCreationWithInitializer(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InitializerExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Symbols.ArrayTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.BoundArrayCreation:this
          15 (22.06% of base) : 166307.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:SetColor(System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):bool:this
          14 ( 0.76% of base) : 189422.dasm - System.DirectoryServices.AccountManagement.ADStoreCtx:PushChangesToNative(System.DirectoryServices.AccountManagement.Principal):System.Object:this
          11 ( 9.48% of base) : 45502.dasm - <>c__DisplayClass0_0:<ComputeDeclarationsInSpan>b__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 (36.67% of base) : 45503.dasm - <>c:<ComputeDeclarationsInNode>b__1_0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 ( 9.48% of base) : 74292.dasm - _Closure$__1-0:_Lambda$__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 (36.67% of base) : 74293.dasm - _Closure$__:_Lambda$__2-0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 ( 5.26% of base) : 166311.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:WriteToConsole(System.String,int,int,System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):this
          10 ( 1.25% of base) : 189465.dasm - System.DirectoryServices.AccountManagement.ADStoreCtx:Move(System.DirectoryServices.AccountManagement.StoreCtx,System.DirectoryServices.AccountManagement.Principal):this
           9 ( 1.36% of base) : 171596.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Int64,Nullable`1][System.Int64,System.Nullable`1[System.Int32]]:TryRemoveInternal(long,byref,bool,System.Nullable`1[Int32]):bool:this
           9 ( 4.29% of base) : 176725.dasm - System.Collections.Generic.PriorityQueue`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:MoveUpDefaultComparer(System.ValueTuple`2[Byte,Nullable`1],int):this
           8 ( 1.10% of base) : 171532.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:TryRemoveInternal(double,byref,bool,System.Nullable`1[Int32]):bool:this
           8 ( 1.14% of base) : 171564.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Vector`1,Nullable`1][System.Numerics.Vector`1[System.Single],System.Nullable`1[System.Int32]]:TryRemoveInternal(System.Numerics.Vector`1[Single],byref,bool,System.Nullable`1[Int32]):bool:this
           8 ( 1.28% of base) : 171344.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:TryRemoveInternal(System.__Canon,byref,bool,System.Nullable`1[Int32]):bool:this
           8 ( 1.20% of base) : 171419.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:TryRemoveInternal(ubyte,byref,bool,System.Nullable`1[Int32]):bool:this
           8 ( 2.23% of base) : 176684.dasm - System.Collections.Generic.PriorityQueue`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:EnqueueDequeue(System.__Canon,System.Nullable`1[Int32]):System.__Canon:this
           8 ( 1.86% of base) : 191167.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           8 ( 1.23% of base) : 171500.dasm - System.Collections.Concurrent.ConcurrentDictionary`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:TryRemoveInternal(int,byref,bool,System.Nullable`1[Int32]):bool:this

Top method improvements (bytes):
         -40 (-27.97% of base) : 107175.dasm - Newtonsoft.Json.Schema.JsonSchemaGenerator:HasFlag(System.Nullable`1[JsonSchemaType],int):bool
         -20 (-1.20% of base) : 206204.dasm - System.Net.Security.SecureChannel:VerifyRemoteCertificate(System.Net.Security.RemoteCertificateValidationCallback,System.Net.Security.SslCertificateTrust,byref,byref,byref):bool:this
         -19 (-0.16% of base) : 147712.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -18 (-5.92% of base) : 127825.dasm - System.Net.Http.Headers.ContentRangeHeaderValue:Equals(System.Object):bool:this
         -17 (-26.98% of base) : 30468.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:DecrementLevel(System.Nullable`1[Int32]):System.Nullable`1[Int32]
         -15 (-1.26% of base) : 218328.dasm - System.Security.Cryptography.Pkcs.Rfc3161TimestampTokenInfo:TryDecode(System.ReadOnlyMemory`1[Byte],bool,byref,byref,byref):bool
         -15 (-2.56% of base) : 169454.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:WithParentId(System.Nullable`1[Int64]):Microsoft.Build.Framework.Profiler.EvaluationLocation:this
         -15 (-2.66% of base) : 105139.dasm - Newtonsoft.Json.JsonSerializer:SetupReader(Newtonsoft.Json.JsonReader,byref,byref,byref,byref,byref,byref):this
         -12 (-0.46% of base) : 189938.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -12 (-8.96% of base) : 56654.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-5.80% of base) : 128343.dasm - System.Net.Http.Headers.RangeItemHeaderValue:Equals(System.Object):bool:this
         -12 (-1.00% of base) : 191667.dasm - System.IO.Compression.Zip64ExtraField:TryGetZip64BlockFromGenericExtraField(System.IO.Compression.ZipGenericExtraField,bool,bool,bool,bool,byref):bool
         -12 (-2.05% of base) : 214181.dasm - System.Security.AccessControl.ObjectSecurity:UpdateWithNewSecurityDescriptor(System.Security.AccessControl.RawSecurityDescriptor,int):this
         -12 (-1.18% of base) : 105595.dasm - Newtonsoft.Json.JsonValidatingReader:ValidateFloat(Newtonsoft.Json.Schema.JsonSchemaModel):this
         -12 (-0.23% of base) : 109133.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -12 (-1.74% of base) : 56183.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -12 (-0.42% of base) : 49358.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -11 (-2.98% of base) : 169459.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:Equals(System.Object):bool:this
         -11 (-0.29% of base) : 49083.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
         -10 (-0.93% of base) : 105146.dasm - Newtonsoft.Json.JsonSerializer:SerializeInternal(Newtonsoft.Json.JsonWriter,System.Object,System.Type):this

Top method regressions (percentages):
          11 (36.67% of base) : 45503.dasm - <>c:<ComputeDeclarationsInNode>b__1_0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 (36.67% of base) : 74293.dasm - _Closure$__:_Lambda$__2-0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          15 (22.06% of base) : 166307.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:SetColor(System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):bool:this
          11 ( 9.48% of base) : 45502.dasm - <>c__DisplayClass0_0:<ComputeDeclarationsInSpan>b__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          11 ( 9.48% of base) : 74292.dasm - _Closure$__1-0:_Lambda$__0(Microsoft.CodeAnalysis.SyntaxNode,System.Nullable`1[Int32]):bool:this
          63 ( 6.35% of base) : 164923.dasm - Microsoft.Extensions.DependencyModel.DependencyContextWriter:WriteCompilationOptions(Microsoft.Extensions.DependencyModel.CompilationOptions,System.Text.Json.Utf8JsonWriter):this
          11 ( 5.26% of base) : 166311.dasm - Microsoft.Extensions.Logging.Console.AnsiParsingLogConsole:WriteToConsole(System.String,int,int,System.Nullable`1[ConsoleColor],System.Nullable`1[ConsoleColor]):this
           9 ( 4.29% of base) : 176725.dasm - System.Collections.Generic.PriorityQueue`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:MoveUpDefaultComparer(System.ValueTuple`2[Byte,Nullable`1],int):this
           5 ( 3.47% of base) : 157220.dasm - System.Text.Json.Serialization.Metadata.JsonPropertyInfo:DetermineIgnoreCondition(System.Nullable`1[JsonIgnoreCondition]):this
           5 ( 3.03% of base) : 106842.dasm - Newtonsoft.Json.Serialization.JsonSerializerInternalReader:ShouldSetPropertyValue(Newtonsoft.Json.Serialization.JsonProperty,Newtonsoft.Json.Serialization.JsonObjectContract,System.Object):bool:this
           8 ( 2.32% of base) : 176714.dasm - System.Collections.Generic.PriorityQueue`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:EnqueueDequeue(ubyte,System.Nullable`1[Int32]):ubyte:this
           8 ( 2.23% of base) : 176684.dasm - System.Collections.Generic.PriorityQueue`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:EnqueueDequeue(System.__Canon,System.Nullable`1[Int32]):System.__Canon:this
           3 ( 2.13% of base) : 214336.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddDiscretionaryAcl(ubyte,int):this
           3 ( 2.13% of base) : 214337.dasm - System.Security.AccessControl.CommonSecurityDescriptor:AddSystemAcl(ubyte,int):this
          26 ( 1.93% of base) : 22956.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindArrayCreationWithInitializer(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InitializerExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Symbols.ArrayTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.CSharp.BoundArrayCreation:this
           8 ( 1.86% of base) : 191167.dasm - System.Formats.Cbor.CborReader:PopDataItem(ubyte):this
           6 ( 1.49% of base) : 169448.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForCondition(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
           6 ( 1.49% of base) : 169450.dasm - Microsoft.Build.Framework.Profiler.EvaluationLocation:CreateLocationForGlob(System.Nullable`1[Int64],ubyte,System.String,System.String,System.Nullable`1[Int32],System.String):Microsoft.Build.Framework.Profiler.EvaluationLocation
           3 ( 1.49% of base) : 189314.dasm - System.DirectoryServices.AccountManagement.ExtensionHelper:get_RdnPrefix():System.String:this
           3 ( 1.49% of base) : 189316.dasm - System.DirectoryServices.AccountManagement.ExtensionHelper:get_StructuralObjectClass():System.String:this

Top method improvements (percentages):
          -3 (-30.00% of base) : 20859.dasm - Microsoft.CSharp.RuntimeBinder.RuntimeBinder:get_IsChecked():bool:this
         -40 (-27.97% of base) : 107175.dasm - Newtonsoft.Json.Schema.JsonSchemaGenerator:HasFlag(System.Nullable`1[JsonSchemaType],int):bool
         -17 (-26.98% of base) : 30468.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:DecrementLevel(System.Nullable`1[Int32]):System.Nullable`1[Int32]
          -3 (-23.08% of base) : 20745.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetIndexBinder:get_IsChecked():bool:this
          -3 (-23.08% of base) : 20753.dasm - Microsoft.CSharp.RuntimeBinder.CSharpSetMemberBinder:get_IsChecked():bool:this
          -3 (-23.08% of base) : 20762.dasm - Microsoft.CSharp.RuntimeBinder.CSharpUnaryOperationBinder:get_IsChecked():bool:this
          -3 (-23.08% of base) : 20670.dasm - Microsoft.CSharp.RuntimeBinder.CSharpBinaryOperationBinder:get_IsChecked():bool:this
          -3 (-23.08% of base) : 20679.dasm - Microsoft.CSharp.RuntimeBinder.CSharpConvertBinder:get_IsChecked():bool:this
          -6 (-14.29% of base) : 27586.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:IntersectWith(byref,byref):bool:this
          -7 (-12.28% of base) : 56311.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitArrayCreation(Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-8.96% of base) : 56654.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-8.11% of base) : 47773.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -8 (-7.62% of base) : 79287.dasm - Microsoft.CodeAnalysis.Emit.AnonymousTypeKeyField:Equals(System.Object):bool:this
          -6 (-7.59% of base) : 79291.dasm - Microsoft.CodeAnalysis.Emit.AnonymousTypeKey:Equals(System.Object):bool:this
          -8 (-6.67% of base) : 77490.dasm - Microsoft.CodeAnalysis.CompilationReference:WithAliases(System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.CompilationReference:this
          -3 (-6.67% of base) : 73224.dasm - LocalVariableSubstituter:VisitLocal(Microsoft.CodeAnalysis.VisualBasic.BoundLocal):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.52% of base) : 48339.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -3 (-6.38% of base) : 48340.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -6 (-6.38% of base) : 76400.dasm - Microsoft.CodeAnalysis.AssemblyPortabilityPolicy:Equals(System.Object):bool:this
          -3 (-6.12% of base) : 47547.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:this

656 total methods with Code Size differences (614 improved, 42 regressed), 378 unchanged.

```

</details>

--------------------------------------------------------------------------------

