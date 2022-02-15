## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 11614343 (overridden on cmd)
Total bytes of diff: 11602999 (overridden on cmd)
Total bytes of delta: -11344 (-0.10 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 18492.dasm (0.37% of base)

Top file improvements (bytes):
       -1018 : 6005.dasm (-6.79% of base)
        -255 : 9780.dasm (-15.24% of base)
        -175 : 1766.dasm (-7.93% of base)
        -174 : 2396.dasm (-5.86% of base)
        -146 : 7250.dasm (-4.71% of base)
        -141 : 2333.dasm (-4.91% of base)
        -103 : 2313.dasm (-2.01% of base)
         -93 : 2690.dasm (-5.67% of base)
         -83 : 9771.dasm (-18.28% of base)
         -80 : 7237.dasm (-12.94% of base)
         -80 : 2292.dasm (-12.94% of base)
         -70 : 9338.dasm (-12.37% of base)
         -68 : 6530.dasm (-0.38% of base)
         -67 : 2421.dasm (-4.20% of base)
         -63 : 18952.dasm (-0.90% of base)
         -63 : 1142.dasm (-5.80% of base)
         -60 : 38676.dasm (-3.23% of base)
         -55 : 2383.dasm (-20.99% of base)
         -55 : 2382.dasm (-20.99% of base)
         -55 : 2751.dasm (-6.17% of base)

1068 total files with Code Size differences (1067 improved, 1 regressed), 4 unchanged.

Top method regressions (bytes):
           4 ( 0.37% of base) : 18492.dasm - System.IPv6AddressHelper:Parse(System.ReadOnlySpan`1[Char],System.Span`1[UInt16],int,byref)

Top method improvements (bytes):
       -1018 (-6.79% of base) : 6005.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
        -255 (-15.24% of base) : 9780.dasm - Microsoft.Extensions.DependencyInjection.ServiceLookup.ILEmitResolverBuilder:GenerateMethodBody(Microsoft.Extensions.DependencyInjection.ServiceLookup.ServiceCallSite,System.Reflection.Emit.ILGenerator):ILEmitResolverBuilderRuntimeContext:this
        -175 (-7.93% of base) : 1766.dasm - ProtoBuf.Internal.Serializers.DefaultValueDecorator:EmitBranchIfDefaultValue(ProtoBuf.Compiler.CompilerContext,ProtoBuf.Compiler.CodeLabel):this
        -174 (-5.86% of base) : 2396.dasm - AutomataNode:EmitSearchNextCore(System.Reflection.Emit.ILGenerator,System.Reflection.Emit.LocalBuilder,System.Reflection.Emit.LocalBuilder,System.Reflection.Emit.LocalBuilder,System.Action`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Action,Utf8Json.Internal.AutomataDictionary+AutomataNode[],int)
        -146 (-4.71% of base) : 7250.dasm - MessagePack.Internal.DynamicObjectTypeBuilder:BuildDeserialize(System.Type,MessagePack.Internal.ObjectSerializationInfo,System.Reflection.Emit.ILGenerator,System.Func`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[MessagePack.Internal.ObjectSerializationInfo+EmittableMember, MessagePack, Version=1.9.0.0, Culture=neutral, PublicKeyToken=b4a0369545f0a1be],[System.Action, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int)
        -141 (-4.91% of base) : 2333.dasm - Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder:BuildDeserialize(System.Type,Utf8Json.Internal.Emit.MetaType,System.Reflection.Emit.ILGenerator,System.Func`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Utf8Json.Internal.Emit.MetaMember, Utf8Json, Version=1.3.7.0, Culture=neutral, PublicKeyToken=8a73d3ba7e392e27],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,int)
        -103 (-2.01% of base) : 2313.dasm - Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder:BuildSerialize(System.Type,Utf8Json.Internal.Emit.MetaType,System.Reflection.Emit.ILGenerator,System.Action,System.Func`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Utf8Json.Internal.Emit.MetaMember, Utf8Json, Version=1.3.7.0, Culture=neutral, PublicKeyToken=8a73d3ba7e392e27],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,int)
         -93 (-5.67% of base) : 2690.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadConstant(int):Sigil.Emit`1[__Canon]:this
         -83 (-18.28% of base) : 9771.dasm - System.Linq.Expressions.Compiler.ILGen:EmitLoadElement(System.Reflection.Emit.ILGenerator,System.Type)
         -80 (-12.94% of base) : 7237.dasm - MessagePack.Internal.ILGeneratorExtensions:EmitLdc_I4(System.Reflection.Emit.ILGenerator,int)
         -80 (-12.94% of base) : 2292.dasm - Utf8Json.Internal.Emit.ILGeneratorExtensions:EmitLdc_I4(System.Reflection.Emit.ILGenerator,int)
         -70 (-12.37% of base) : 9338.dasm - System.Linq.Expressions.Compiler.ILGen:EmitDefault(System.Reflection.Emit.ILGenerator,System.Type,System.Linq.Expressions.Compiler.ILocalCache)
         -68 (-0.38% of base) : 6530.dasm - System.Reflection.Metadata.MetadataReader:InitializeTableReaders(System.Reflection.Internal.MemoryBlock,ubyte,System.Int32[],System.Int32[]):this
         -67 (-4.20% of base) : 2421.dasm - Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder:EmitNewObject(System.Reflection.Emit.ILGenerator,System.Type,Utf8Json.Internal.Emit.MetaType,Utf8Json.Resolvers.Internal.DynamicObjectTypeBuilder+DeserializeInfo[],bool):System.Reflection.Emit.LocalBuilder
         -63 (-0.90% of base) : 18952.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ParameterHelpers:CheckParameterModifiers(Microsoft.CodeAnalysis.CSharp.Syntax.ParameterSyntax,Microsoft.CodeAnalysis.DiagnosticBag)
         -63 (-5.80% of base) : 1142.dasm - System.Reflection.Emit.ILGenerator:Emit(System.Reflection.Emit.OpCode,int):this
         -60 (-3.23% of base) : 38676.dasm - System.Text.Tests.Perf_StringBuilder:Append_ValueTypes():System.Text.StringBuilder:this
         -55 (-20.99% of base) : 7249.dasm - MessagePack.Internal.ILGeneratorExtensions:EmitLdloc(System.Reflection.Emit.ILGenerator,int)
         -55 (-20.99% of base) : 7230.dasm - MessagePack.Internal.ILGeneratorExtensions:EmitStloc(System.Reflection.Emit.ILGenerator,int)
         -55 (-6.19% of base) : 2755.dasm - Sigil.Emit`1[__Canon][System.__Canon]:LoadLocal(Sigil.Local):Sigil.Emit`1[__Canon]:this

Top method regressions (percentages):
           4 ( 0.37% of base) : 18492.dasm - System.IPv6AddressHelper:Parse(System.ReadOnlySpan`1[Char],System.Span`1[UInt16],int,byref)

Top method improvements (percentages):
         -10 (-47.62% of base) : 2016.dasm - System.TimeSpan:ToString():System.String:this
         -10 (-41.67% of base) : 19708.dasm - System.Xml.Tests.Perf_XmlConvert:TimeSpan_ToString():System.String:this
         -12 (-38.71% of base) : 13724.dasm - System.Runtime.Serialization.CodeGenerator:Break(System.Object):this
         -12 (-38.71% of base) : 12252.dasm - System.Runtime.Serialization.CodeGenerator:IfFalseBreak(System.Object):this
         -10 (-38.46% of base) : 15014.dasm - System.Xml.Tests.Perf_XmlConvert:DateTime_ToString_Local():System.String:this
         -33 (-37.08% of base) : 38577.dasm - System.Drawing.Tests.Perf_Graphics_DrawBeziers:DrawBezier_Point():this
         -19 (-35.19% of base) : 15243.dasm - Devirtualization.EqualityComparerFixture`1[ValueTuple`3][System.ValueTuple`3[System.Byte,Devirtualization.EqualityComparer+E,System.Int32]]:CompareCached(byref,byref):bool:this
         -10 (-34.48% of base) : 19336.dasm - System.Xml.Tests.Perf_XmlConvert:DateTime_ToString_RoundtripKind():System.String:this
         -10 (-34.48% of base) : 18512.dasm - System.Xml.Tests.Perf_XmlConvert:DateTime_ToString_Unspecified():System.String:this
         -19 (-33.33% of base) : 37833.dasm - Devirtualization.EqualityComparerFixture`1[ValueTuple`3][System.ValueTuple`3[System.Byte,Devirtualization.EqualityComparer+E,System.Int32]]:CompareWrapped(byref,byref):bool:this
         -17 (-32.08% of base) : 7022.dasm - System.Collections.Generic.Dictionary`2[ValueTuple`2,__Canon][System.ValueTuple`2[System.Int32,System.Int32],System.__Canon]:get_Item(System.ValueTuple`2[Int32,Int32]):System.__Canon:this
         -12 (-31.58% of base) : 7959.dasm - System.Linq.Expressions.Compiler.ILGen:EmitLoadArg(System.Reflection.Emit.ILGenerator,int)
         -12 (-31.58% of base) : 9768.dasm - System.Linq.Expressions.Compiler.ILGen:EmitPrimitive(System.Reflection.Emit.ILGenerator,int)
         -12 (-31.58% of base) : 2315.dasm - Utf8Json.Internal.Emit.ILGeneratorExtensions:EmitLdfld(System.Reflection.Emit.ILGenerator,System.Reflection.FieldInfo)
         -12 (-30.00% of base) : 1140.dasm - System.Text.RegularExpressions.RegexCompiler:Ldloc(System.Reflection.Emit.LocalBuilder):this
         -12 (-30.00% of base) : 1155.dasm - System.Text.RegularExpressions.RegexCompiler:Ldloca(System.Reflection.Emit.LocalBuilder):this
         -12 (-30.00% of base) : 1134.dasm - System.Text.RegularExpressions.RegexCompiler:Stloc(System.Reflection.Emit.LocalBuilder):this
         -12 (-30.00% of base) : 12864.dasm - System.Xml.Serialization.CodeGenerator:Box(System.Type):this
         -12 (-30.00% of base) : 8187.dasm - System.Xml.Serialization.CodeGenerator:Castclass(System.Type):this
         -12 (-30.00% of base) : 14790.dasm - System.Xml.Serialization.CodeGenerator:InitObj(System.Type):this

1068 total methods with Code Size differences (1067 improved, 1 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 114467668 (overridden on cmd)
Total bytes of diff: 114285402 (overridden on cmd)
Total bytes of delta: -182266 (-0.16 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 91909.dasm (4.26% of base)

Top file improvements (bytes):
        -195 : 197299.dasm (-2.41% of base)
        -160 : 197451.dasm (-3.62% of base)
        -126 : 169960.dasm (-9.17% of base)
        -126 : 169827.dasm (-9.17% of base)
        -104 : 168867.dasm (-4.50% of base)
        -104 : 169370.dasm (-4.66% of base)
        -104 : 169377.dasm (-4.66% of base)
        -104 : 169000.dasm (-4.50% of base)
         -92 : 260348.dasm (-17.33% of base)
         -79 : 197274.dasm (-1.90% of base)
         -73 : 167086.dasm (-13.32% of base)
         -70 : 169903.dasm (-5.83% of base)
         -70 : 169922.dasm (-5.83% of base)
         -70 : 197426.dasm (-2.14% of base)
         -70 : 169523.dasm (-5.58% of base)
         -70 : 169542.dasm (-5.58% of base)
         -70 : 169808.dasm (-5.83% of base)
         -70 : 169656.dasm (-5.58% of base)
         -70 : 169675.dasm (-5.58% of base)
         -70 : 169713.dasm (-5.83% of base)

10964 total files with Code Size differences (10963 improved, 1 regressed), 2 unchanged.

Top method regressions (bytes):
           2 ( 4.26% of base) : 91909.dasm - Runtime_58373:Main():int

Top method improvements (bytes):
        -195 (-2.41% of base) : 197299.dasm - ABIStress.Program:DoStubCall(int,bool,bool,int,int):bool
        -160 (-3.62% of base) : 197451.dasm - ABIStress.Program:DoStubCall(int,bool,bool,int,int):bool
        -126 (-9.17% of base) : 169827.dasm - NullableTest23:Run()
        -126 (-9.17% of base) : 169960.dasm - NullableTest30:Run()
        -104 (-4.50% of base) : 168867.dasm - NullableTest23:Run()
        -104 (-4.66% of base) : 169370.dasm - NullableTest23:Run()
        -104 (-4.66% of base) : 169377.dasm - NullableTest30:Run()
        -104 (-4.50% of base) : 169000.dasm - NullableTest30:Run()
         -92 (-17.33% of base) : 260348.dasm - R3Contention.LayoutOptions:GetPreferredSizeCore(R3Contention.Size):R3Contention.Size:this
         -79 (-1.90% of base) : 197274.dasm - ABIStress.Program:DoPInvokes(int):bool
         -73 (-13.32% of base) : 167086.dasm - NativeVarargTest.VarArg:TestPassingTenEightBytes():bool
         -70 (-2.14% of base) : 197426.dasm - ABIStress.Program:DoPInvokes(int):bool
         -70 (-5.58% of base) : 169656.dasm - NullableTest14:Run()
         -70 (-5.58% of base) : 169675.dasm - NullableTest15:Run()
         -70 (-5.83% of base) : 169713.dasm - NullableTest17:Run()
         -70 (-5.58% of base) : 169751.dasm - NullableTest19:Run()
         -70 (-5.83% of base) : 169808.dasm - NullableTest22:Run()
         -70 (-5.83% of base) : 169903.dasm - NullableTest27:Run()
         -70 (-5.83% of base) : 169922.dasm - NullableTest28:Run()
         -70 (-5.58% of base) : 169523.dasm - NullableTest7:Run()

Top method regressions (percentages):
           2 ( 4.26% of base) : 91909.dasm - Runtime_58373:Main():int

Top method improvements (percentages):
         -24 (-35.29% of base) : 15219.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_Byte):this
         -24 (-35.29% of base) : 15227.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_Int16):this
         -24 (-35.29% of base) : 15235.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_Int32):this
         -24 (-35.29% of base) : 15243.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_SByte):this
         -24 (-35.29% of base) : 15251.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_UInt16):this
         -24 (-35.29% of base) : 15259.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__AbsoluteDifferenceAdd_Vector64_UInt32):this
         -24 (-35.29% of base) : 129306.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Byte):this
         -24 (-35.29% of base) : 129314.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Double):this
         -24 (-35.29% of base) : 129322.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Int16):this
         -24 (-35.29% of base) : 129330.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Int32):this
         -24 (-35.29% of base) : 129338.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Int64):this
         -24 (-35.29% of base) : 129346.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_SByte):this
         -24 (-35.29% of base) : 129354.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_Single):this
         -24 (-35.29% of base) : 129362.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_UInt16):this
         -24 (-35.29% of base) : 129370.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_UInt32):this
         -24 (-35.29% of base) : 129378.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__BitwiseSelect_Vector64_UInt64):this
         -24 (-35.29% of base) : 184828.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__DotProduct_Vector64_Int32):this
         -24 (-35.29% of base) : 184836.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__DotProduct_Vector64_UInt32):this
         -24 (-35.29% of base) : 120326.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__FusedMultiplyAdd_Vector64_Single):this
         -24 (-35.29% of base) : 137627.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleTernaryOpTest__FusedMultiplyAddByScalar_Vector64_Single):this

10964 total methods with Code Size differences (10963 improved, 1 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 38873394 (overridden on cmd)
Total bytes of diff: 38799289 (overridden on cmd)
Total bytes of delta: -74105 (-0.19 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 210648.dasm (0.32% of base)
           8 : 76046.dasm (1.61% of base)
           5 : 41860.dasm (0.48% of base)
           4 : 9275.dasm (1.09% of base)
           4 : 9276.dasm (1.10% of base)
           1 : 156659.dasm (0.10% of base)
           1 : 156687.dasm (0.14% of base)

Top file improvements (bytes):
       -2438 : 75907.dasm (-9.47% of base)
       -1018 : 129100.dasm (-6.79% of base)
        -382 : 126046.dasm (-7.22% of base)
        -255 : 174444.dasm (-14.88% of base)
        -203 : 190274.dasm (-4.68% of base)
        -191 : 126811.dasm (-9.34% of base)
        -178 : 126010.dasm (-9.59% of base)
        -145 : 117022.dasm (-0.93% of base)
        -141 : 154125.dasm (-12.24% of base)
        -130 : 225274.dasm (-5.74% of base)
        -118 : 154199.dasm (-11.92% of base)
        -118 : 229419.dasm (-11.92% of base)
        -115 : 126179.dasm (-7.35% of base)
        -110 : 229853.dasm (-4.47% of base)
        -108 : 126173.dasm (-5.54% of base)
        -103 : 119420.dasm (-3.08% of base)
        -101 : 126063.dasm (-9.44% of base)
         -85 : 29933.dasm (-1.37% of base)
         -83 : 125940.dasm (-11.94% of base)
         -83 : 230158.dasm (-4.73% of base)

10256 total files with Code Size differences (10249 improved, 7 regressed), 14 unchanged.

Top method regressions (bytes):
           8 ( 1.61% of base) : 76046.dasm - Microsoft.CodeAnalysis.SmallDictionary`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:Insert(int,double,System.Nullable`1[Int32],bool):this
           8 ( 0.32% of base) : 210648.dasm - System.Linq.Parallel.SortHelper`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:MergeSortCooperatively():this
           5 ( 0.48% of base) : 41860.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference:GetConstantValueDependencies(bool):System.Collections.Immutable.ImmutableHashSet`1[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
           4 ( 1.10% of base) : 9276.dasm - Microsoft.FSharp.Collections.ArrayModule:IterateIndexed2(Microsoft.FSharp.Core.FSharpFunc`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpFunc`2[[System.Byte, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpFunc`2[[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.Unit, FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Byte[],System.Nullable`1[System.Int32][])
           4 ( 1.09% of base) : 9275.dasm - Microsoft.FSharp.Collections.ArrayModule:IterateIndexed2(Microsoft.FSharp.Core.FSharpFunc`2[Int32,__Canon],System.__Canon[],System.Nullable`1[System.Int32][])
           1 ( 0.10% of base) : 156659.dasm - System.Security.Cryptography.X509Certificates.RSAPssX509SignatureGenerator:GetSignatureAlgorithmIdentifier(System.Security.Cryptography.HashAlgorithmName):System.Byte[]:this
           1 ( 0.14% of base) : 156687.dasm - System.Security.Cryptography.X509Certificates.SubjectAlternativeNameBuilder:AddUserPrincipalName(System.String):this

Top method improvements (bytes):
       -2438 (-9.47% of base) : 75907.dasm - Microsoft.CodeAnalysis.DesktopAssemblyIdentityComparer:.cctor()
       -1018 (-6.79% of base) : 129100.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
        -382 (-7.22% of base) : 126046.dasm - System.Linq.Expressions.Compiler.LambdaCompiler:EmitLift(int,System.Type,System.Linq.Expressions.MethodCallExpression,System.Linq.Expressions.ParameterExpression[],System.Linq.Expressions.Expression[]):this
        -255 (-14.88% of base) : 174444.dasm - Microsoft.Extensions.DependencyInjection.ServiceLookup.ILEmitResolverBuilder:GenerateMethodBody(Microsoft.Extensions.DependencyInjection.ServiceLookup.ServiceCallSite,System.Reflection.Emit.ILGenerator):ILEmitResolverBuilderRuntimeContext:this
        -203 (-4.68% of base) : 190274.dasm - System.ComponentModel.Composition.MetadataViewGenerator:GenerateInterfaceViewProxyType(System.Type):System.Type
        -191 (-9.34% of base) : 126811.dasm - System.Dynamic.Utils.DelegateHelpers:CreateObjectArrayDelegateRefEmit(System.Type,System.Func`2[[System.Object[], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Delegate
        -178 (-9.59% of base) : 126010.dasm - System.Linq.Expressions.Compiler.LambdaCompiler:EmitUnaryOperator(int,System.Type,System.Type):this
        -145 (-0.93% of base) : 117022.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
        -141 (-12.24% of base) : 154125.dasm - System.Security.Cryptography.EccKeyFormatHelper:WriteSpecifiedECDomain(System.Security.Cryptography.ECParameters,System.Formats.Asn1.AsnWriter)
        -130 (-5.74% of base) : 225274.dasm - ProxyBuilder:AddMethodImpl(System.Reflection.MethodInfo,int):System.Reflection.Emit.MethodBuilder:this
        -118 (-11.92% of base) : 154199.dasm - System.Security.Cryptography.PasswordBasedEncryption:WritePbeAlgorithmIdentifier(System.Formats.Asn1.AsnWriter,bool,System.String,System.Span`1[Byte],int,System.String,System.Span`1[Byte])
        -118 (-11.92% of base) : 229419.dasm - System.Security.Cryptography.PasswordBasedEncryption:WritePbeAlgorithmIdentifier(System.Formats.Asn1.AsnWriter,bool,System.String,System.Span`1[Byte],int,System.String,System.Span`1[Byte])
        -115 (-7.35% of base) : 126179.dasm - System.Linq.Expressions.Compiler.LambdaCompiler:EmitLiftedBinaryArithmetic(int,System.Type,System.Type,System.Type):this
        -110 (-4.47% of base) : 229853.dasm - System.Security.Cryptography.Pkcs.Pkcs12Builder:SealWithMac(System.ReadOnlySpan`1[Char],System.Security.Cryptography.HashAlgorithmName,int):this
        -108 (-5.54% of base) : 126173.dasm - System.Linq.Expressions.Compiler.LambdaCompiler:EmitUnliftedBinaryOp(int,System.Type,System.Type):this
        -103 (-3.08% of base) : 119420.dasm - System.Data.Common.SqlByteStorage:Aggregate(System.Int32[],int):System.Object:this
        -101 (-9.44% of base) : 126063.dasm - System.Linq.Expressions.Compiler.LambdaCompiler:EmitLiftedAndAlso(System.Linq.Expressions.BinaryExpression):this
         -85 (-1.37% of base) : 29933.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:ComputeDeclarations(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,System.Collections.Generic.List`1[DeclarationInfo],System.Nullable`1[Int32],System.Threading.CancellationToken)
         -83 (-11.94% of base) : 125940.dasm - System.Linq.Expressions.Compiler.ILGen:EmitLoadElement(System.Reflection.Emit.ILGenerator,System.Type)
         -83 (-4.73% of base) : 230158.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161TstInfo:Encode(System.Formats.Asn1.AsnWriter,System.Formats.Asn1.Asn1Tag):this

Top method regressions (percentages):
           8 ( 1.61% of base) : 76046.dasm - Microsoft.CodeAnalysis.SmallDictionary`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:Insert(int,double,System.Nullable`1[Int32],bool):this
           4 ( 1.10% of base) : 9276.dasm - Microsoft.FSharp.Collections.ArrayModule:IterateIndexed2(Microsoft.FSharp.Core.FSharpFunc`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpFunc`2[[System.Byte, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpFunc`2[[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.Unit, FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Byte[],System.Nullable`1[System.Int32][])
           4 ( 1.09% of base) : 9275.dasm - Microsoft.FSharp.Collections.ArrayModule:IterateIndexed2(Microsoft.FSharp.Core.FSharpFunc`2[Int32,__Canon],System.__Canon[],System.Nullable`1[System.Int32][])
           5 ( 0.48% of base) : 41860.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference:GetConstantValueDependencies(bool):System.Collections.Immutable.ImmutableHashSet`1[[Microsoft.CodeAnalysis.CSharp.Symbols.SourceFieldSymbolWithSyntaxReference, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
           8 ( 0.32% of base) : 210648.dasm - System.Linq.Parallel.SortHelper`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:MergeSortCooperatively():this
           1 ( 0.14% of base) : 156687.dasm - System.Security.Cryptography.X509Certificates.SubjectAlternativeNameBuilder:AddUserPrincipalName(System.String):this
           1 ( 0.10% of base) : 156659.dasm - System.Security.Cryptography.X509Certificates.RSAPssX509SignatureGenerator:GetSignatureAlgorithmIdentifier(System.Security.Cryptography.HashAlgorithmName):System.Byte[]:this

Top method improvements (percentages):
         -10 (-47.62% of base) : 165459.dasm - Internal.JitInterface.InstructionSetFlags:ExpandInstructionSetByImplication(int):this
         -10 (-47.62% of base) : 165461.dasm - Internal.JitInterface.InstructionSetFlags:ExpandInstructionSetByReverseImplication(int):this
         -10 (-47.62% of base) : 117428.dasm - System.Data.SqlTypes.SqlInt32:ToSqlBoolean():System.Data.SqlTypes.SqlBoolean:this
         -10 (-47.62% of base) : 117429.dasm - System.Data.SqlTypes.SqlInt32:ToSqlByte():System.Data.SqlTypes.SqlByte:this
         -10 (-47.62% of base) : 117431.dasm - System.Data.SqlTypes.SqlInt32:ToSqlInt16():System.Data.SqlTypes.SqlInt16:this
         -10 (-47.62% of base) : 117630.dasm - System.Data.SqlTypes.SqlSingle:ToSqlBoolean():System.Data.SqlTypes.SqlBoolean:this
         -10 (-47.62% of base) : 117631.dasm - System.Data.SqlTypes.SqlSingle:ToSqlByte():System.Data.SqlTypes.SqlByte:this
         -10 (-47.62% of base) : 117633.dasm - System.Data.SqlTypes.SqlSingle:ToSqlInt16():System.Data.SqlTypes.SqlInt16:this
         -12 (-46.15% of base) : 204092.dasm - System.DirectoryServices.Protocols.LdapConnection:SendRequest(System.DirectoryServices.Protocols.DirectoryRequest):System.DirectoryServices.Protocols.DirectoryResponse:this
         -10 (-43.48% of base) : 117394.dasm - System.Data.SqlTypes.SqlInt32:ToSqlDecimal():System.Data.SqlTypes.SqlDecimal:this
         -10 (-43.48% of base) : 117430.dasm - System.Data.SqlTypes.SqlInt32:ToSqlDouble():System.Data.SqlTypes.SqlDouble:this
         -10 (-43.48% of base) : 117392.dasm - System.Data.SqlTypes.SqlInt32:ToSqlInt64():System.Data.SqlTypes.SqlInt64:this
         -10 (-43.48% of base) : 117393.dasm - System.Data.SqlTypes.SqlInt32:ToSqlMoney():System.Data.SqlTypes.SqlMoney:this
         -10 (-43.48% of base) : 117395.dasm - System.Data.SqlTypes.SqlInt32:ToSqlSingle():System.Data.SqlTypes.SqlSingle:this
         -10 (-43.48% of base) : 117396.dasm - System.Data.SqlTypes.SqlInt32:ToSqlString():System.Data.SqlTypes.SqlString:this
         -10 (-43.48% of base) : 117637.dasm - System.Data.SqlTypes.SqlSingle:ToSqlDecimal():System.Data.SqlTypes.SqlDecimal:this
         -10 (-43.48% of base) : 117632.dasm - System.Data.SqlTypes.SqlSingle:ToSqlDouble():System.Data.SqlTypes.SqlDouble:this
         -10 (-43.48% of base) : 117634.dasm - System.Data.SqlTypes.SqlSingle:ToSqlInt32():System.Data.SqlTypes.SqlInt32:this
         -10 (-43.48% of base) : 117635.dasm - System.Data.SqlTypes.SqlSingle:ToSqlInt64():System.Data.SqlTypes.SqlInt64:this
         -10 (-43.48% of base) : 117636.dasm - System.Data.SqlTypes.SqlSingle:ToSqlMoney():System.Data.SqlTypes.SqlMoney:this

10256 total methods with Code Size differences (10249 improved, 7 regressed), 14 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 94352246 (overridden on cmd)
Total bytes of diff: 94229033 (overridden on cmd)
Total bytes of delta: -123213 (-0.13 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 250050.dasm (0.14% of base)
           6 : 67567.dasm (0.32% of base)
           6 : 187448.dasm (0.32% of base)
           4 : 67566.dasm (0.24% of base)
           4 : 187447.dasm (0.24% of base)
           2 : 237348.dasm (0.40% of base)
           2 : 34494.dasm (0.29% of base)
           2 : 66307.dasm (0.25% of base)
           2 : 67569.dasm (0.07% of base)
           2 : 187450.dasm (0.07% of base)
           1 : 237346.dasm (0.19% of base)
           1 : 237347.dasm (0.19% of base)
           1 : 92835.dasm (0.04% of base)
           1 : 92837.dasm (0.04% of base)

Top file improvements (bytes):
       -1221 : 85523.dasm (-2.96% of base)
       -1221 : 82641.dasm (-2.96% of base)
       -1221 : 83394.dasm (-2.96% of base)
       -1221 : 83804.dasm (-2.96% of base)
       -1221 : 84189.dasm (-2.96% of base)
       -1221 : 84472.dasm (-2.96% of base)
       -1221 : 84671.dasm (-2.96% of base)
       -1221 : 85430.dasm (-2.96% of base)
       -1018 : 176492.dasm (-6.80% of base)
        -818 : 69929.dasm (-5.13% of base)
        -799 : 69968.dasm (-14.40% of base)
        -664 : 69932.dasm (-4.77% of base)
        -655 : 51480.dasm (-2.45% of base)
        -652 : 69931.dasm (-4.68% of base)
        -637 : 285969.dasm (-1.39% of base)
        -637 : 285323.dasm (-1.39% of base)
        -545 : 69975.dasm (-5.39% of base)
        -476 : 51580.dasm (-1.91% of base)
        -431 : 282611.dasm (-5.53% of base)
        -376 : 282895.dasm (-4.36% of base)

13907 total files with Code Size differences (13893 improved, 14 regressed), 15 unchanged.

Top method regressions (bytes):
          16 ( 0.14% of base) : 250050.dasm - Parser:GetLogClasses(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ClassDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):System.Collections.Generic.IReadOnlyList`1[[Microsoft.Extensions.Logging.Generators.LoggerMessageGenerator+LoggerClass, Microsoft.Extensions.Logging.Generators, Version=42.42.42.42, Culture=neutral, PublicKeyToken=adb9793829ddae60]]:this
           6 ( 0.32% of base) : 67567.dasm - System.Tests.StringTests:TrimCharactersAtStartAndEnd()
           6 ( 0.32% of base) : 187448.dasm - System.Tests.StringTests:TrimCharactersAtStartAndEnd()
           4 ( 0.24% of base) : 67566.dasm - System.Tests.StringTests:TrimCharactersAtEnd()
           4 ( 0.24% of base) : 187447.dasm - System.Tests.StringTests:TrimCharactersAtEnd()
           2 ( 0.40% of base) : 237348.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],long,System.Func`3[Int64,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
           2 ( 0.29% of base) : 34494.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.indexer.regclass.regclass032.regclass032.Test:MainMethod():int
           2 ( 0.07% of base) : 67569.dasm - System.Tests.StringTests:TrimCharactersMultipleTimes()
           2 ( 0.07% of base) : 187450.dasm - System.Tests.StringTests:TrimCharactersMultipleTimes()
           2 ( 0.25% of base) : 66307.dasm - System.Text.Tests.AsciiUtilityTests:NarrowUtf16ToAscii_SomeNonAsciiInput()
           1 ( 0.19% of base) : 237346.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],double,System.Func`3[Double,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
           1 ( 0.19% of base) : 237347.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],System.Numerics.Vector`1[Single],System.Func`3[Vector`1,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
           1 ( 0.04% of base) : 92835.dasm - System.Text.Json.Nodes.Tests.OperatorTests:ExplicitOperators_FromNullableValues()
           1 ( 0.04% of base) : 92837.dasm - System.Text.Json.Nodes.Tests.OperatorTests:ImplicitOperators_FromNullableValues()

Top method improvements (bytes):
       -1221 (-2.96% of base) : 83394.dasm - CollectionTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 82641.dasm - CollectionTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 84189.dasm - ConstructorTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 83804.dasm - ConstructorTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 84671.dasm - ExtensionDataTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 84472.dasm - ExtensionDataTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 85523.dasm - PropertyNameTestsContext_Default:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1221 (-2.96% of base) : 85430.dasm - PropertyNameTestsContext_Metadata:SimpleTestClassPropInit(System.Text.Json.Serialization.JsonSerializerContext):System.Text.Json.Serialization.Metadata.JsonPropertyInfo[]
       -1018 (-6.80% of base) : 176492.dasm - System.Net.Http.Headers.KnownHeaders:.cctor()
        -818 (-5.13% of base) : 69929.dasm - System.Tests.TimeZoneInfoTests:GetAmbiguousTimeOffsets_Amsterdam()
        -799 (-14.40% of base) : 69968.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTimeOffset_VariousSystemTimeZones()
        -664 (-4.77% of base) : 69932.dasm - System.Tests.TimeZoneInfoTests:IsInvalidTime()
        -655 (-2.45% of base) : 51480.dasm - System.Linq.Expressions.Tests.Compiler_Tests:BinaryOperators(bool)
        -652 (-4.68% of base) : 69931.dasm - System.Tests.TimeZoneInfoTests:IsDaylightSavingTime()
        -637 (-1.39% of base) : 285969.dasm - FileData:.cctor()
        -637 (-1.39% of base) : 285323.dasm - FileData:.cctor()
        -545 (-5.39% of base) : 69975.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToSystem()
        -476 (-1.91% of base) : 51580.dasm - System.Linq.Expressions.Tests.Compiler_Tests:Conversions(bool)
        -431 (-5.53% of base) : 282611.dasm - System.Formats.Asn1.Tests.Writer.ComprehensiveWriteTest:WriteMicrosoftDotComCert()
        -376 (-4.36% of base) : 282895.dasm - System.Formats.Asn1.Tests.Reader.ComprehensiveReadTests:ReadMicrosoftComCert()

Top method regressions (percentages):
           2 ( 0.40% of base) : 237348.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],long,System.Func`3[Int64,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
           6 ( 0.32% of base) : 67567.dasm - System.Tests.StringTests:TrimCharactersAtStartAndEnd()
           6 ( 0.32% of base) : 187448.dasm - System.Tests.StringTests:TrimCharactersAtStartAndEnd()
           2 ( 0.29% of base) : 34494.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.indexer.regclass.regclass032.regclass032.Test:MainMethod():int
           2 ( 0.25% of base) : 66307.dasm - System.Text.Tests.AsciiUtilityTests:NarrowUtf16ToAscii_SomeNonAsciiInput()
           4 ( 0.24% of base) : 67566.dasm - System.Tests.StringTests:TrimCharactersAtEnd()
           4 ( 0.24% of base) : 187447.dasm - System.Tests.StringTests:TrimCharactersAtEnd()
           1 ( 0.19% of base) : 237346.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],double,System.Func`3[Double,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
           1 ( 0.19% of base) : 237347.dasm - LamarCodeGeneration.Util.ArrayTools:Match(System.Nullable`1[System.Int32][],System.Numerics.Vector`1[Single],System.Func`3[Vector`1,Nullable`1,Boolean]):System.Nullable`1[System.Int32][]
          16 ( 0.14% of base) : 250050.dasm - Parser:GetLogClasses(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ClassDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):System.Collections.Generic.IReadOnlyList`1[[Microsoft.Extensions.Logging.Generators.LoggerMessageGenerator+LoggerClass, Microsoft.Extensions.Logging.Generators, Version=42.42.42.42, Culture=neutral, PublicKeyToken=adb9793829ddae60]]:this
           2 ( 0.07% of base) : 67569.dasm - System.Tests.StringTests:TrimCharactersMultipleTimes()
           2 ( 0.07% of base) : 187450.dasm - System.Tests.StringTests:TrimCharactersMultipleTimes()
           1 ( 0.04% of base) : 92837.dasm - System.Text.Json.Nodes.Tests.OperatorTests:ImplicitOperators_FromNullableValues()
           1 ( 0.04% of base) : 92835.dasm - System.Text.Json.Nodes.Tests.OperatorTests:ExplicitOperators_FromNullableValues()

Top method improvements (percentages):
         -10 (-41.67% of base) : 60259.dasm - System.Net.Test.Common.Http2LoopbackConnection:ReadPingAsync():System.Threading.Tasks.Task`1[[System.Net.Test.Common.PingFrame, System.Net.Http.Functional.Tests, Version=7.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51]]:this
         -10 (-41.67% of base) : 178279.dasm - System.Net.Test.Common.Http2LoopbackConnection:ReadPingAsync():System.Threading.Tasks.Task`1[[System.Net.Test.Common.PingFrame, System.Net.Http.WinHttpHandler.Functional.Tests, Version=7.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51]]:this
         -19 (-38.00% of base) : 128617.dasm - Microsoft.IdentityModel.Tokens.EventBasedLRUCache`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:SetValue(System.__Canon,System.Nullable`1[Int32]):this
         -19 (-38.00% of base) : 128664.dasm - Microsoft.IdentityModel.Tokens.EventBasedLRUCache`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:SetValue(int,System.Nullable`1[Int32]):this
         -12 (-37.50% of base) : 108217.dasm - ForAll@33-7[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:Invoke(System.__Canon):Microsoft.FSharp.Core.Unit:this
         -12 (-37.50% of base) : 108222.dasm - ForAll@33-7[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:Invoke(int):Microsoft.FSharp.Core.Unit:this
         -12 (-36.36% of base) : 332026.dasm - <>c__DisplayClass2_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<CallOnEmptyStack>b__0():this
         -12 (-36.36% of base) : 221041.dasm - <>c__DisplayClass2_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<CreateContinuationTask>b__0():this
         -12 (-36.36% of base) : 216669.dasm - <>c__DisplayClass2_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<CreateContinuationTask>b__0():this
         -12 (-36.36% of base) : 15633.dasm - LazyLogMessage`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:CreateMessage():System.String:this
         -17 (-36.17% of base) : 137358.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 257214.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 257881.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 134879.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 258701.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 259021.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 259774.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 260111.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 260584.dasm - <>c__DisplayClass3_0`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this
         -17 (-36.17% of base) : 137359.dasm - <>c__DisplayClass3_0`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:<DictionaryEquals>b__0(System.Nullable`1[Int32],System.Nullable`1[Int32]):bool:this

13907 total methods with Code Size differences (13893 improved, 14 regressed), 15 unchanged.

```

</details>

--------------------------------------------------------------------------------

