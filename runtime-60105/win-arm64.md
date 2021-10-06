## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 39136
Total bytes of diff: 38816
Total bytes of delta: -320 (-0.82% of base)
Total relative delta: -0.19
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -60 : 14841.dasm (-2.66% of base)
         -48 : 3970.dasm (-4.05% of base)
         -32 : 17363.dasm (-1.76% of base)
         -32 : 16131.dasm (-1.63% of base)
         -24 : 15943.dasm (-1.52% of base)
         -16 : 4173.dasm (-0.82% of base)
         -12 : 18595.dasm (-0.60% of base)
         -12 : 16134.dasm (-0.91% of base)
         -12 : 16150.dasm (-1.96% of base)
          -8 : 15930.dasm (-0.20% of base)
          -8 : 16121.dasm (-0.24% of base)
          -8 : 19007.dasm (-0.38% of base)
          -8 : 16153.dasm (-0.39% of base)
          -8 : 5106.dasm (-0.44% of base)
          -8 : 16298.dasm (-0.22% of base)
          -8 : 20445.dasm (-0.42% of base)
          -4 : 21864.dasm (-0.31% of base)
          -4 : 16490.dasm (-0.18% of base)
          -4 : 23121.dasm (-0.37% of base)
          -4 : 23368.dasm (-0.34% of base)

20 total files with Code Size differences (20 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -60 (-2.66% of base) : 14841.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -48 (-4.05% of base) : 3970.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -32 (-1.76% of base) : 17363.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
         -32 (-1.63% of base) : 16131.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -24 (-1.52% of base) : 15943.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -16 (-0.82% of base) : 4173.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -12 (-0.60% of base) : 18595.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         -12 (-0.91% of base) : 16134.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -12 (-1.96% of base) : 16150.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
          -8 (-0.20% of base) : 15930.dasm - Microsoft.CodeAnalysis.CSharp.Imports:Validate():this
          -8 (-0.24% of base) : 16121.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this
          -8 (-0.38% of base) : 19007.dasm - <WriteGatherAsync>d__22:MoveNext():this
          -8 (-0.39% of base) : 16153.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
          -8 (-0.44% of base) : 5106.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -8 (-0.22% of base) : 16298.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:CheckInterfaces(Microsoft.CodeAnalysis.DiagnosticBag):this
          -8 (-0.42% of base) : 20445.dasm - <ReadScatterAsync>d__15:MoveNext():this
          -4 (-0.31% of base) : 21864.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this
          -4 (-0.18% of base) : 16490.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:CheckAbstractClassImplementations(Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-0.37% of base) : 23121.dasm - System.Collections.IterateForEach`1[Int32][System.Int32]:ImmutableDictionary():int:this
          -4 (-0.34% of base) : 23368.dasm - System.Collections.IterateForEach`1[Int32][System.Int32]:ImmutableHashSet():int:this

Top method improvements (percentages):
         -48 (-4.05% of base) : 3970.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -60 (-2.66% of base) : 14841.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -12 (-1.96% of base) : 16150.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -32 (-1.76% of base) : 17363.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
         -32 (-1.63% of base) : 16131.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -24 (-1.52% of base) : 15943.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -12 (-0.91% of base) : 16134.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-0.82% of base) : 4173.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -12 (-0.60% of base) : 18595.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
          -8 (-0.44% of base) : 5106.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -8 (-0.42% of base) : 20445.dasm - <ReadScatterAsync>d__15:MoveNext():this
          -8 (-0.39% of base) : 16153.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
          -8 (-0.38% of base) : 19007.dasm - <WriteGatherAsync>d__22:MoveNext():this
          -4 (-0.37% of base) : 23121.dasm - System.Collections.IterateForEach`1[Int32][System.Int32]:ImmutableDictionary():int:this
          -4 (-0.34% of base) : 23368.dasm - System.Collections.IterateForEach`1[Int32][System.Int32]:ImmutableHashSet():int:this
          -4 (-0.31% of base) : 21864.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this
          -8 (-0.24% of base) : 16121.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this
          -8 (-0.22% of base) : 16298.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:CheckInterfaces(Microsoft.CodeAnalysis.DiagnosticBag):this
          -8 (-0.20% of base) : 15930.dasm - Microsoft.CodeAnalysis.CSharp.Imports:Validate():this
          -4 (-0.18% of base) : 16490.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:CheckAbstractClassImplementations(Microsoft.CodeAnalysis.DiagnosticBag):this

20 total methods with Code Size differences (20 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 20364
Total bytes of diff: 20212
Total bytes of delta: -152 (-0.75% of base)
Total relative delta: -0.06
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -72 : 205690.dasm (-1.16% of base)
         -20 : 164257.dasm (-1.12% of base)
          -8 : 164262.dasm (-0.51% of base)
          -8 : 164259.dasm (-0.37% of base)
          -8 : 164830.dasm (-0.62% of base)
          -8 : 164147.dasm (-0.68% of base)
          -8 : 164889.dasm (-0.57% of base)
          -8 : 164823.dasm (-0.50% of base)
          -8 : 164258.dasm (-0.43% of base)
          -4 : 164816.dasm (-0.31% of base)

10 total files with Code Size differences (10 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -72 (-1.16% of base) : 205690.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -20 (-1.12% of base) : 164257.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
          -8 (-0.51% of base) : 164262.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
          -8 (-0.37% of base) : 164259.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
          -8 (-0.62% of base) : 164830.dasm - <GetFields>d__44:MoveNext():bool:this
          -8 (-0.68% of base) : 164147.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
          -8 (-0.57% of base) : 164889.dasm - <Verify>d__9:MoveNext():bool:this
          -8 (-0.50% of base) : 164823.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -8 (-0.43% of base) : 164258.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
          -4 (-0.31% of base) : 164816.dasm - <GetMethods>d__38:MoveNext():bool:this

Top method improvements (percentages):
         -72 (-1.16% of base) : 205690.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -20 (-1.12% of base) : 164257.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
          -8 (-0.68% of base) : 164147.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
          -8 (-0.62% of base) : 164830.dasm - <GetFields>d__44:MoveNext():bool:this
          -8 (-0.57% of base) : 164889.dasm - <Verify>d__9:MoveNext():bool:this
          -8 (-0.51% of base) : 164262.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
          -8 (-0.50% of base) : 164823.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -8 (-0.43% of base) : 164258.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
          -8 (-0.37% of base) : 164259.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
          -4 (-0.31% of base) : 164816.dasm - <GetMethods>d__38:MoveNext():bool:this

10 total methods with Code Size differences (10 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 10812
Total bytes of diff: 10280
Total bytes of delta: -532 (-4.92% of base)
Total relative delta: -0.46
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -120 : 113787.dasm (-5.62% of base)
         -96 : 113764.dasm (-3.63% of base)
         -84 : 113748.dasm (-8.71% of base)
         -72 : 113767.dasm (-7.63% of base)
         -72 : 113756.dasm (-8.87% of base)
         -48 : 113781.dasm (-6.90% of base)
         -24 : 113776.dasm (-1.86% of base)
          -8 : 155896.dasm (-1.31% of base)
          -8 : 155897.dasm (-1.31% of base)

9 total files with Code Size differences (9 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -120 (-5.62% of base) : 113787.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -96 (-3.63% of base) : 113764.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -84 (-8.71% of base) : 113748.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -72 (-7.63% of base) : 113767.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -72 (-8.87% of base) : 113756.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-6.90% of base) : 113781.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-1.86% of base) : 113776.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-1.31% of base) : 155896.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
          -8 (-1.31% of base) : 155897.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this

Top method improvements (percentages):
         -72 (-8.87% of base) : 113756.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -84 (-8.71% of base) : 113748.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -72 (-7.63% of base) : 113767.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-6.90% of base) : 113781.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
        -120 (-5.62% of base) : 113787.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -96 (-3.63% of base) : 113764.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-1.86% of base) : 113776.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-1.31% of base) : 155896.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
          -8 (-1.31% of base) : 155897.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this

9 total methods with Code Size differences (9 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 257188
Total bytes of diff: 254896
Total bytes of delta: -2292 (-0.89% of base)
Total relative delta: -1.63
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          28 : 74342.dasm (0.91% of base)
          20 : 109116.dasm (0.77% of base)

Top file improvements (bytes):
        -100 : 201559.dasm (-3.29% of base)
         -88 : 71917.dasm (-2.42% of base)
         -80 : 43144.dasm (-2.11% of base)
         -72 : 108551.dasm (-6.43% of base)
         -72 : 108552.dasm (-6.47% of base)
         -68 : 108504.dasm (-5.31% of base)
         -64 : 197397.dasm (-3.13% of base)
         -64 : 109143.dasm (-5.08% of base)
         -60 : 109117.dasm (-4.18% of base)
         -60 : 71900.dasm (-6.67% of base)
         -60 : 71894.dasm (-1.86% of base)
         -60 : 71005.dasm (-1.78% of base)
         -52 : 145019.dasm (-3.13% of base)
         -48 : 71876.dasm (-4.65% of base)
         -44 : 71907.dasm (-6.83% of base)
         -44 : 101311.dasm (-9.40% of base)
         -36 : 71914.dasm (-3.27% of base)
         -36 : 71924.dasm (-3.26% of base)
         -32 : 138773.dasm (-1.06% of base)
         -32 : 43072.dasm (-1.63% of base)

139 total files with Code Size differences (137 improved, 2 regressed), 2 unchanged.

Top method regressions (bytes):
          28 ( 0.91% of base) : 74342.dasm - Microsoft.Cci.PdbWriter:WriteDefinitionLocations(Roslyn.Utilities.MultiDictionary`2[[Microsoft.Cci.DebugSourceDocument, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.Cci.DefinitionWithLocation, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          20 ( 0.77% of base) : 109116.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this

Top method improvements (bytes):
        -100 (-3.29% of base) : 201559.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
         -88 (-2.42% of base) : 71917.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -80 (-2.11% of base) : 43144.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureNonTypeMemberNamesAreLoaded():this
         -72 (-6.43% of base) : 108551.dasm - System.Data.DataView:CopyTo(System.Array,int):this
         -72 (-6.47% of base) : 108552.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -68 (-5.31% of base) : 108504.dasm - System.Data.DataView:ResetRowViewCache():this
         -64 (-3.13% of base) : 197397.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
         -64 (-5.08% of base) : 109143.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -60 (-4.18% of base) : 109117.dasm - System.Data.Select:GetLinearFilteredRows(System.Data.Range):System.Data.DataRow[]:this
         -60 (-6.67% of base) : 71900.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -60 (-1.86% of base) : 71894.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -60 (-1.78% of base) : 71005.dasm - VB$StateMachine_69_GetMethodsToEmit:MoveNext():bool:this
         -52 (-3.13% of base) : 145019.dasm - Internal.TypeSystem.Ecma.PortablePdbSymbolReader:ProbeScopeForLocals(System.Collections.Generic.List`1[ILLocalVariable],System.Reflection.Metadata.LocalScopeHandle):this
         -48 (-4.65% of base) : 71876.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -44 (-6.83% of base) : 71907.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -44 (-9.40% of base) : 101311.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
         -36 (-3.27% of base) : 71914.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -36 (-3.26% of base) : 71924.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -32 (-1.06% of base) : 138773.dasm - System.Text.Json.Utf8JsonReader:UnescapeSequenceAndCompare(System.ReadOnlySpan`1[Byte]):bool:this
         -32 (-1.63% of base) : 43072.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this

Top method regressions (percentages):
          28 ( 0.91% of base) : 74342.dasm - Microsoft.Cci.PdbWriter:WriteDefinitionLocations(Roslyn.Utilities.MultiDictionary`2[[Microsoft.Cci.DebugSourceDocument, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.Cci.DefinitionWithLocation, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          20 ( 0.77% of base) : 109116.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this

Top method improvements (percentages):
         -44 (-9.40% of base) : 101311.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
         -44 (-6.83% of base) : 71907.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -60 (-6.67% of base) : 71900.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -72 (-6.47% of base) : 108552.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -72 (-6.43% of base) : 108551.dasm - System.Data.DataView:CopyTo(System.Array,int):this
         -68 (-5.31% of base) : 108504.dasm - System.Data.DataView:ResetRowViewCache():this
         -64 (-5.08% of base) : 109143.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -48 (-4.65% of base) : 71876.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -60 (-4.18% of base) : 109117.dasm - System.Data.Select:GetLinearFilteredRows(System.Data.Range):System.Data.DataRow[]:this
        -100 (-3.29% of base) : 201559.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
         -36 (-3.27% of base) : 71914.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -36 (-3.26% of base) : 71924.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -52 (-3.13% of base) : 145019.dasm - Internal.TypeSystem.Ecma.PortablePdbSymbolReader:ProbeScopeForLocals(System.Collections.Generic.List`1[ILLocalVariable],System.Reflection.Metadata.LocalScopeHandle):this
         -64 (-3.13% of base) : 197397.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
         -16 (-2.88% of base) : 210955.dasm - System.Reflection.Metadata.TypeDefinition:GetMethods():System.Reflection.Metadata.MethodDefinitionHandleCollection:this
         -16 (-2.88% of base) : 210615.dasm - System.Reflection.Metadata.MethodDefinition:GetParameters():System.Reflection.Metadata.ParameterHandleCollection:this
         -16 (-2.88% of base) : 210956.dasm - System.Reflection.Metadata.TypeDefinition:GetFields():System.Reflection.Metadata.FieldDefinitionHandleCollection:this
         -88 (-2.42% of base) : 71917.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-2.16% of base) : 40466.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MissingCorLibrarySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -12 (-2.16% of base) : 50863.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.MissingCorLibrarySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this

139 total methods with Code Size differences (137 improved, 2 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 394280
Total bytes of diff: 392492
Total bytes of delta: -1788 (-0.45% of base)
Total relative delta: -1.27
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          52 : 314465.dasm (1.79% of base)
          48 : 314467.dasm (1.57% of base)
          28 : 175080.dasm (0.54% of base)
          20 : 175051.dasm (1.06% of base)
          20 : 175088.dasm (0.49% of base)
           8 : 175078.dasm (0.27% of base)
           8 : 175081.dasm (0.27% of base)

Top file improvements (bytes):
        -128 : 174872.dasm (-3.30% of base)
         -64 : 174861.dasm (-2.97% of base)
         -60 : 67628.dasm (-6.85% of base)
         -60 : 191536.dasm (-6.85% of base)
         -56 : 122919.dasm (-2.30% of base)
         -52 : 127900.dasm (-3.23% of base)
         -52 : 124595.dasm (-5.00% of base)
         -52 : 124633.dasm (-2.90% of base)
         -52 : 127859.dasm (-5.83% of base)
         -48 : 127872.dasm (-2.93% of base)
         -48 : 127858.dasm (-2.72% of base)
         -48 : 174841.dasm (-1.68% of base)
         -44 : 16048.dasm (-0.59% of base)
         -44 : 8997.dasm (-1.01% of base)
         -44 : 175119.dasm (-1.08% of base)
         -44 : 8998.dasm (-1.01% of base)
         -44 : 124594.dasm (-1.89% of base)
         -40 : 124606.dasm (-1.88% of base)
         -32 : 175017.dasm (-2.22% of base)
         -32 : 174978.dasm (-2.22% of base)

161 total files with Code Size differences (154 improved, 7 regressed), 0 unchanged.

Top method regressions (bytes):
          52 ( 1.79% of base) : 314465.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          48 ( 1.57% of base) : 314467.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
          28 ( 0.54% of base) : 175080.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End_Rewind_Advance():this
          20 ( 1.06% of base) : 175051.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset():this
          20 ( 0.49% of base) : 175088.dasm - System.Memory.Tests.SequenceReader.IsNext:IsNext_Span():this
           8 ( 0.27% of base) : 175078.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End():this
           8 ( 0.27% of base) : 175081.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End_Multiple():this

Top method improvements (bytes):
        -128 (-3.30% of base) : 174872.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
         -64 (-2.97% of base) : 174861.dasm - System.Memory.Tests.ReadOnlySequenceTestsDefault:Default_Enumerator():this
         -60 (-6.85% of base) : 67628.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -60 (-6.85% of base) : 191536.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -56 (-2.30% of base) : 122919.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.IndentBlockFormattingRule:AddBlockIndentationOperation(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode):this
         -52 (-3.23% of base) : 127900.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -52 (-5.00% of base) : 124595.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -52 (-2.90% of base) : 124633.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -52 (-5.83% of base) : 127859.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -48 (-2.93% of base) : 127872.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -48 (-2.72% of base) : 127858.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -48 (-1.68% of base) : 174841.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonChar:HelloWorldAcrossTwoBlocks():this
         -44 (-0.59% of base) : 16048.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -44 (-1.01% of base) : 8997.dasm - Microsoft.CodeAnalysis.Formatting.AbstractTriviaFormatter:FormatTrivia(Formatter`1[__Canon],WhitespaceAppender`1[__Canon],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[__Canon],System.Threading.CancellationToken):Microsoft.CodeAnalysis.Formatting.LineColumn:this
         -44 (-1.08% of base) : 175119.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
         -44 (-1.01% of base) : 8998.dasm - Microsoft.CodeAnalysis.Formatting.AbstractTriviaFormatter:FormatTrivia(Formatter`1[Byte],WhitespaceAppender`1[Byte],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[Byte],System.Threading.CancellationToken):Microsoft.CodeAnalysis.Formatting.LineColumn:this
         -44 (-1.89% of base) : 124594.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -40 (-1.88% of base) : 124606.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -32 (-2.22% of base) : 175017.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
         -32 (-2.22% of base) : 174978.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this

Top method regressions (percentages):
          52 ( 1.79% of base) : 314465.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          48 ( 1.57% of base) : 314467.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
          20 ( 1.06% of base) : 175051.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset():this
          28 ( 0.54% of base) : 175080.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End_Rewind_Advance():this
          20 ( 0.49% of base) : 175088.dasm - System.Memory.Tests.SequenceReader.IsNext:IsNext_Span():this
           8 ( 0.27% of base) : 175078.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End():this
           8 ( 0.27% of base) : 175081.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo_End_Multiple():this

Top method improvements (percentages):
         -16 (-8.89% of base) : 338129.dasm - System.Tests.ExtensionsTests:Deconstruct4()
         -12 (-7.50% of base) : 338128.dasm - System.Tests.ExtensionsTests:Deconstruct3()
         -60 (-6.85% of base) : 67628.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -60 (-6.85% of base) : 191536.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -52 (-5.83% of base) : 127859.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
          -8 (-5.71% of base) : 338127.dasm - System.Tests.ExtensionsTests:Deconstruct2()
         -52 (-5.00% of base) : 124595.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
          -4 (-3.33% of base) : 338126.dasm - System.Tests.ExtensionsTests:Deconstruct1()
        -128 (-3.30% of base) : 174872.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
         -52 (-3.23% of base) : 127900.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -64 (-2.97% of base) : 174861.dasm - System.Memory.Tests.ReadOnlySequenceTestsDefault:Default_Enumerator():this
         -48 (-2.93% of base) : 127872.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -52 (-2.90% of base) : 124633.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -48 (-2.72% of base) : 127858.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -32 (-2.46% of base) : 227182.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -32 (-2.46% of base) : 179167.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -56 (-2.30% of base) : 122919.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.IndentBlockFormattingRule:AddBlockIndentationOperation(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode):this
         -32 (-2.22% of base) : 175017.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
         -32 (-2.22% of base) : 174978.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this
         -32 (-2.22% of base) : 174977.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfFull():this

161 total methods with Code Size differences (154 improved, 7 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

