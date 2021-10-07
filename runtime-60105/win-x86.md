## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 33135
Total bytes of diff: 32646
Total bytes of delta: -489 (-1.48% of base)
Total relative delta: -0.35
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -138 : 8492.dasm (-13.91% of base)
         -80 : 14286.dasm (-3.20% of base)
         -47 : 18483.dasm (-2.83% of base)
         -43 : 8515.dasm (-2.77% of base)
         -34 : 16120.dasm (-2.56% of base)
         -28 : 15929.dasm (-1.88% of base)
         -25 : 16107.dasm (-0.93% of base)
         -25 : 16139.dasm (-1.27% of base)
         -22 : 16117.dasm (-1.04% of base)
         -16 : 17345.dasm (-1.16% of base)
          -8 : 16136.dasm (-1.87% of base)
          -8 : 20704.dasm (-0.45% of base)
          -5 : 19385.dasm (-0.28% of base)
          -5 : 5097.dasm (-0.32% of base)
          -5 : 22102.dasm (-0.42% of base)

15 total files with Code Size differences (15 improved, 0 regressed), 5 unchanged.

Top method improvements (bytes):
        -138 (-13.91% of base) : 8492.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -80 (-3.20% of base) : 14286.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -47 (-2.83% of base) : 18483.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         -43 (-2.77% of base) : 8515.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -34 (-2.56% of base) : 16120.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -28 (-1.88% of base) : 15929.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -25 (-0.93% of base) : 16107.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this
         -25 (-1.27% of base) : 16139.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
         -22 (-1.04% of base) : 16117.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-1.16% of base) : 17345.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
          -8 (-1.87% of base) : 16136.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
          -8 (-0.45% of base) : 20704.dasm - <ReadScatterAsync>d__15:MoveNext():this
          -5 (-0.28% of base) : 19385.dasm - <WriteGatherAsync>d__22:MoveNext():this
          -5 (-0.32% of base) : 5097.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -5 (-0.42% of base) : 22102.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this

Top method improvements (percentages):
        -138 (-13.91% of base) : 8492.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -80 (-3.20% of base) : 14286.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -47 (-2.83% of base) : 18483.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         -43 (-2.77% of base) : 8515.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -34 (-2.56% of base) : 16120.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -28 (-1.88% of base) : 15929.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
          -8 (-1.87% of base) : 16136.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -25 (-1.27% of base) : 16139.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
         -16 (-1.16% of base) : 17345.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
         -22 (-1.04% of base) : 16117.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -25 (-0.93% of base) : 16107.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this
          -8 (-0.45% of base) : 20704.dasm - <ReadScatterAsync>d__15:MoveNext():this
          -5 (-0.42% of base) : 22102.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this
          -5 (-0.32% of base) : 5097.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -5 (-0.28% of base) : 19385.dasm - <WriteGatherAsync>d__22:MoveNext():this

15 total methods with Code Size differences (15 improved, 0 regressed), 5 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 24811
Total bytes of diff: 23934
Total bytes of delta: -877 (-3.53% of base)
Total relative delta: -0.42
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -230 : 164247.dasm (-12.43% of base)
        -193 : 205637.dasm (-3.00% of base)
        -178 : 164252.dasm (-10.04% of base)
         -50 : 164217.dasm (-1.67% of base)
         -48 : 164137.dasm (-3.67% of base)
         -48 : 164249.dasm (-1.95% of base)
         -40 : 164248.dasm (-1.83% of base)
         -32 : 164809.dasm (-2.33% of base)
         -22 : 164802.dasm (-2.10% of base)
         -20 : 164816.dasm (-1.91% of base)
         -16 : 164875.dasm (-1.50% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
        -230 (-12.43% of base) : 164247.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
        -193 (-3.00% of base) : 205637.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
        -178 (-10.04% of base) : 164252.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -50 (-1.67% of base) : 164217.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -48 (-3.67% of base) : 164137.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
         -48 (-1.95% of base) : 164249.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -40 (-1.83% of base) : 164248.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
         -32 (-2.33% of base) : 164809.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
         -22 (-2.10% of base) : 164802.dasm - <GetMethods>d__38:MoveNext():bool:this
         -20 (-1.91% of base) : 164816.dasm - <GetFields>d__44:MoveNext():bool:this
         -16 (-1.50% of base) : 164875.dasm - <Verify>d__9:MoveNext():bool:this

Top method improvements (percentages):
        -230 (-12.43% of base) : 164247.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
        -178 (-10.04% of base) : 164252.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -48 (-3.67% of base) : 164137.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
        -193 (-3.00% of base) : 205637.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -32 (-2.33% of base) : 164809.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
         -22 (-2.10% of base) : 164802.dasm - <GetMethods>d__38:MoveNext():bool:this
         -48 (-1.95% of base) : 164249.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -20 (-1.91% of base) : 164816.dasm - <GetFields>d__44:MoveNext():bool:this
         -40 (-1.83% of base) : 164248.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
         -50 (-1.67% of base) : 164217.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -16 (-1.50% of base) : 164875.dasm - <Verify>d__9:MoveNext():bool:this

11 total methods with Code Size differences (11 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 6857
Total bytes of diff: 6491
Total bytes of delta: -366 (-5.34% of base)
Total relative delta: -1.34
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -102 : 134589.dasm (-8.35% of base)
         -62 : 134566.dasm (-3.55% of base)
         -36 : 134558.dasm (-8.57% of base)
         -32 : 134569.dasm (-6.41% of base)
         -30 : 76286.dasm (-46.15% of base)
         -30 : 76287.dasm (-46.15% of base)
         -28 : 134583.dasm (-7.27% of base)
         -24 : 134550.dasm (-3.70% of base)
         -12 : 134578.dasm (-1.62% of base)
          -5 : 75904.dasm (-0.94% of base)
          -5 : 75903.dasm (-0.94% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -102 (-8.35% of base) : 134589.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -62 (-3.55% of base) : 134566.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -36 (-8.57% of base) : 134558.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -32 (-6.41% of base) : 134569.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -30 (-46.15% of base) : 76286.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -30 (-46.15% of base) : 76287.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -28 (-7.27% of base) : 134583.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-3.70% of base) : 134550.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -12 (-1.62% of base) : 134578.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -5 (-0.94% of base) : 75904.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
          -5 (-0.94% of base) : 75903.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this

Top method improvements (percentages):
         -30 (-46.15% of base) : 76286.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -30 (-46.15% of base) : 76287.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -36 (-8.57% of base) : 134558.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
        -102 (-8.35% of base) : 134589.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -28 (-7.27% of base) : 134583.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -32 (-6.41% of base) : 134569.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-3.70% of base) : 134550.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -62 (-3.55% of base) : 134566.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-1.62% of base) : 134578.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -5 (-0.94% of base) : 75904.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
          -5 (-0.94% of base) : 75903.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this

11 total methods with Code Size differences (11 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 212520
Total bytes of diff: 207664
Total bytes of delta: -4856 (-2.28% of base)
Total relative delta: -4.32
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          13 : 156089.dasm (0.85% of base)
           1 : 84598.dasm (0.49% of base)

Top file improvements (bytes):
        -235 : 205003.dasm (-8.04% of base)
        -230 : 162793.dasm (-12.43% of base)
        -178 : 162798.dasm (-10.04% of base)
        -168 : 155500.dasm (-5.31% of base)
        -144 : 200841.dasm (-7.62% of base)
        -138 : 162858.dasm (-8.08% of base)
        -101 : 73129.dasm (-2.62% of base)
        -100 : 114214.dasm (-4.96% of base)
         -94 : 25551.dasm (-3.39% of base)
         -91 : 46872.dasm (-4.24% of base)
         -85 : 84468.dasm (-3.05% of base)
         -85 : 73106.dasm (-2.87% of base)
         -83 : 46879.dasm (-3.19% of base)
         -82 : 51207.dasm (-7.30% of base)
         -72 : 162807.dasm (-3.41% of base)
         -71 : 155498.dasm (-4.68% of base)
         -64 : 114252.dasm (-6.34% of base)
         -62 : 113584.dasm (-6.11% of base)
         -57 : 75551.dasm (-4.21% of base)
         -57 : 75552.dasm (-2.26% of base)

107 total files with Code Size differences (105 improved, 2 regressed), 32 unchanged.

Top method regressions (bytes):
          13 ( 0.85% of base) : 156089.dasm - <DisposePendingDisposablesOnExceptionAsync>d__21:MoveNext():this
           1 ( 0.49% of base) : 84598.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceEventCounts:FastSerialization.IFastSerializable.FromStream(FastSerialization.Deserializer):this

Top method improvements (bytes):
        -235 (-8.04% of base) : 205003.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
        -230 (-12.43% of base) : 162793.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
        -178 (-10.04% of base) : 162798.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
        -168 (-5.31% of base) : 155500.dasm - System.Text.Json.Utf8JsonReader:UnescapeSequenceAndCompare(System.ReadOnlySpan`1[Byte]):bool:this
        -144 (-7.62% of base) : 200841.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
        -138 (-8.08% of base) : 162858.dasm - <GetParameterNames>d__6:MoveNext():bool:this
        -101 (-2.62% of base) : 73129.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
        -100 (-4.96% of base) : 114214.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
         -94 (-3.39% of base) : 25551.dasm - Microsoft.CodeAnalysis.CSharp.ClsComplianceChecker:CheckSymbolDistinctness(Microsoft.CodeAnalysis.CSharp.Symbol,System.String,Roslyn.Utilities.MultiDictionary`2+ValueSet[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -91 (-4.24% of base) : 46872.dasm - <GetEnumFieldsToEmit>d__66:MoveNext():bool:this
         -85 (-3.05% of base) : 84468.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceLog:FastSerialization.IFastSerializable.FromStream(FastSerialization.Deserializer):this
         -85 (-2.87% of base) : 73106.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -83 (-3.19% of base) : 46879.dasm - <GetMethodsToEmit>d__68:MoveNext():bool:this
         -82 (-7.30% of base) : 51207.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods():System.Collections.Generic.Dictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -72 (-3.41% of base) : 162807.dasm - Internal.TypeSystem.Ecma.PortablePdbSymbolReader:ProbeScopeForLocals(System.Collections.Generic.List`1[ILLocalVariable],System.Reflection.Metadata.LocalScopeHandle):this
         -71 (-4.68% of base) : 155498.dasm - System.Text.Json.Utf8JsonReader:CompareToSequence(System.ReadOnlySpan`1[Byte]):bool:this
         -64 (-6.34% of base) : 114252.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -62 (-6.11% of base) : 113584.dasm - System.Data.DataView:ResetRowViewCache():this
         -57 (-4.21% of base) : 75551.dasm - Microsoft.Cci.PdbWriter:AssertAllDefinitionsHaveTokens(Roslyn.Utilities.MultiDictionary`2[[Microsoft.Cci.DebugSourceDocument, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.Cci.DefinitionWithLocation, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -57 (-2.26% of base) : 75552.dasm - Microsoft.Cci.PdbWriter:WriteDefinitionLocations(Roslyn.Utilities.MultiDictionary`2[[Microsoft.Cci.DebugSourceDocument, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.Cci.DefinitionWithLocation, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

Top method regressions (percentages):
          13 ( 0.85% of base) : 156089.dasm - <DisposePendingDisposablesOnExceptionAsync>d__21:MoveNext():this
           1 ( 0.49% of base) : 84598.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceEventCounts:FastSerialization.IFastSerializable.FromStream(FastSerialization.Deserializer):this

Top method improvements (percentages):
         -30 (-46.88% of base) : 150425.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -30 (-46.88% of base) : 150424.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -49 (-14.58% of base) : 102497.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
        -230 (-12.43% of base) : 162793.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -55 (-10.42% of base) : 73119.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
        -178 (-10.04% of base) : 162798.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
        -138 (-8.08% of base) : 162858.dasm - <GetParameterNames>d__6:MoveNext():bool:this
        -235 (-8.04% of base) : 205003.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
        -144 (-7.62% of base) : 200841.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
         -82 (-7.30% of base) : 51207.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods():System.Collections.Generic.Dictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -55 (-7.21% of base) : 73112.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -64 (-6.34% of base) : 114252.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -62 (-6.11% of base) : 113584.dasm - System.Data.DataView:ResetRowViewCache():this
         -51 (-5.90% of base) : 113659.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -31 (-5.62% of base) : 150881.dasm - System.Reflection.Metadata.TypeDefinition:GetMethods():System.Reflection.Metadata.MethodDefinitionHandleCollection:this
         -31 (-5.62% of base) : 150541.dasm - System.Reflection.Metadata.MethodDefinition:GetParameters():System.Reflection.Metadata.ParameterHandleCollection:this
         -31 (-5.62% of base) : 150882.dasm - System.Reflection.Metadata.TypeDefinition:GetFields():System.Reflection.Metadata.FieldDefinitionHandleCollection:this
        -168 (-5.31% of base) : 155500.dasm - System.Text.Json.Utf8JsonReader:UnescapeSequenceAndCompare(System.ReadOnlySpan`1[Byte]):bool:this
        -100 (-4.96% of base) : 114214.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
         -71 (-4.68% of base) : 155498.dasm - System.Text.Json.Utf8JsonReader:CompareToSequence(System.ReadOnlySpan`1[Byte]):bool:this

107 total methods with Code Size differences (105 improved, 2 regressed), 32 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 361396
Total bytes of diff: 358520
Total bytes of delta: -2876 (-0.80% of base)
Total relative delta: -1.78
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         203 : 126498.dasm (2.44% of base)
          17 : 175086.dasm (0.19% of base)
          11 : 174999.dasm (0.76% of base)
          11 : 175009.dasm (0.68% of base)
          11 : 175007.dasm (0.67% of base)

Top file improvements (bytes):
        -276 : 175054.dasm (-5.76% of base)
        -240 : 174807.dasm (-6.46% of base)
        -136 : 175085.dasm (-1.31% of base)
        -124 : 314391.dasm (-4.29% of base)
        -124 : 314389.dasm (-4.54% of base)
        -112 : 174782.dasm (-4.29% of base)
        -108 : 288690.dasm (-2.37% of base)
         -98 : 174776.dasm (-3.88% of base)
         -74 : 314390.dasm (-2.76% of base)
         -70 : 15818.dasm (-2.98% of base)
         -69 : 174917.dasm (-5.93% of base)
         -69 : 179105.dasm (-6.15% of base)
         -69 : 174916.dasm (-5.88% of base)
         -69 : 174915.dasm (-5.88% of base)
         -69 : 227115.dasm (-6.15% of base)
         -66 : 288700.dasm (-1.03% of base)
         -61 : 314083.dasm (-2.32% of base)
         -60 : 67638.dasm (-9.12% of base)
         -60 : 191474.dasm (-9.12% of base)
         -58 : 16041.dasm (-0.58% of base)

111 total files with Code Size differences (106 improved, 5 regressed), 56 unchanged.

Top method regressions (bytes):
         203 ( 2.44% of base) : 126498.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.NodeBasedFormattingRule:AddIndentBlockOperationsSlow(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode,byref):this
          17 ( 0.19% of base) : 175086.dasm - System.Memory.Tests.SequenceReader.SkipDelimiter:TryReadTo_SkipDelimiter_Runs():this
          11 ( 0.76% of base) : 174999.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsDefaultInTheEnd():this
          11 ( 0.68% of base) : 175009.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:PeekWorkesWithEmptySegments():this
          11 ( 0.67% of base) : 175007.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryReadTraversesSegments():this

Top method improvements (bytes):
        -276 (-5.76% of base) : 175054.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
        -240 (-6.46% of base) : 174807.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
        -136 (-1.31% of base) : 175085.dasm - System.Memory.Tests.SequenceReader.SkipDelimiter:TryReadTo_SkipDelimiter():this
        -124 (-4.29% of base) : 314391.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
        -124 (-4.54% of base) : 314389.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
        -112 (-4.29% of base) : 174782.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonByte:HelloWorldAcrossTwoBlocks():this
        -108 (-2.37% of base) : 288690.dasm - <HelloWorldAcrossTwoBlocks>d__11:MoveNext():this
         -98 (-3.88% of base) : 174776.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonChar:HelloWorldAcrossTwoBlocks():this
         -74 (-2.76% of base) : 314390.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_MiddleTypeDef():this
         -70 (-2.98% of base) : 15818.dasm - <AddMatchingTypesAsync>d__23:MoveNext():this
         -69 (-5.93% of base) : 174917.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this
         -69 (-6.15% of base) : 179105.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -69 (-5.88% of base) : 174916.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfFull():this
         -69 (-5.88% of base) : 174915.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
         -69 (-6.15% of base) : 227115.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -66 (-1.03% of base) : 288700.dasm - <ReaderShouldNotGetUnflushedBytesWithAppend>d__17:MoveNext():this
         -61 (-2.32% of base) : 314083.dasm - System.Reflection.Metadata.Decoding.Tests.SignatureDecoderTests:PinnedAndUnpinnedLocals():this
         -60 (-9.12% of base) : 67638.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -60 (-9.12% of base) : 191474.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -58 (-0.58% of base) : 16041.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

Top method regressions (percentages):
         203 ( 2.44% of base) : 126498.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.NodeBasedFormattingRule:AddIndentBlockOperationsSlow(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode,byref):this
          11 ( 0.76% of base) : 174999.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsDefaultInTheEnd():this
          11 ( 0.68% of base) : 175009.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:PeekWorkesWithEmptySegments():this
          11 ( 0.67% of base) : 175007.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryReadTraversesSegments():this
          17 ( 0.19% of base) : 175086.dasm - System.Memory.Tests.SequenceReader.SkipDelimiter:TryReadTo_SkipDelimiter_Runs():this

Top method improvements (percentages):
         -60 (-9.12% of base) : 67638.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -60 (-9.12% of base) : 191474.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
        -240 (-6.46% of base) : 174807.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
         -69 (-6.15% of base) : 179105.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -69 (-6.15% of base) : 227115.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -69 (-5.93% of base) : 174917.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this
         -69 (-5.88% of base) : 174916.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfFull():this
         -69 (-5.88% of base) : 174915.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
        -276 (-5.76% of base) : 175054.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
          -8 (-5.67% of base) : 338046.dasm - System.Tests.ExtensionsTests:Deconstruct4()
          -6 (-4.76% of base) : 338045.dasm - System.Tests.ExtensionsTests:Deconstruct3()
         -30 (-4.58% of base) : 127801.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
        -124 (-4.54% of base) : 314389.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
         -44 (-4.44% of base) : 12304.dasm - ValueSet[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Contains(System.Nullable`1[Int32],System.Collections.Generic.IEqualityComparer`1[Nullable`1]):bool:this
        -112 (-4.29% of base) : 174782.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonByte:HelloWorldAcrossTwoBlocks():this
        -124 (-4.29% of base) : 314391.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
         -44 (-4.11% of base) : 12295.dasm - ValueSet[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:Contains(System.Nullable`1[Int32],System.Collections.Generic.IEqualityComparer`1[Nullable`1]):bool:this
         -51 (-3.93% of base) : 127842.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -30 (-3.93% of base) : 124538.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -98 (-3.88% of base) : 174776.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonChar:HelloWorldAcrossTwoBlocks():this

111 total methods with Code Size differences (106 improved, 5 regressed), 56 unchanged.

```

</details>

--------------------------------------------------------------------------------

