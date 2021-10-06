## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 238789
Total bytes of diff: 237865
Total bytes of delta: -924 (-0.39% of base)
Total relative delta: -0.94
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          94 : 32927.dasm (2.86% of base)
          80 : 39996.dasm (2.38% of base)
          19 : 10034.dasm (1.90% of base)

Top file improvements (bytes):
         -33 : 17407.dasm (-0.35% of base)
         -33 : 14914.dasm (-0.34% of base)
         -28 : 27636.dasm (-1.59% of base)
         -25 : 7355.dasm (-1.44% of base)
         -25 : 14956.dasm (-0.16% of base)
         -25 : 27890.dasm (-0.64% of base)
         -25 : 27553.dasm (-0.51% of base)
         -22 : 27909.dasm (-0.58% of base)
         -22 : 30111.dasm (-1.04% of base)
         -19 : 6214.dasm (-0.40% of base)
         -18 : 29696.dasm (-1.47% of base)
         -17 : 10478.dasm (-1.33% of base)
         -14 : 27642.dasm (-3.74% of base)
         -14 : 9969.dasm (-4.53% of base)
         -14 : 28013.dasm (-0.74% of base)
         -14 : 28301.dasm (-0.52% of base)
         -13 : 15023.dasm (-4.59% of base)
         -13 : 17415.dasm (-4.59% of base)
         -13 : 44208.dasm (-4.26% of base)
         -13 : 29704.dasm (-0.68% of base)

92 total files with Code Size differences (89 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
          94 ( 2.86% of base) : 32927.dasm - <<ReadMessage>g__ReadMessageLong|208_0>d:MoveNext():this
          80 ( 2.38% of base) : 39996.dasm - <<ReadMessage>g__ReadMessageLong|208_0>d:MoveNext():this
          19 ( 1.90% of base) : 10034.dasm - PathUtils:PathNavigatesAboveRoot(String):bool

Top method improvements (bytes):
         -33 (-0.35% of base) : 17407.dasm - <SendAsync>d__6:MoveNext():this
         -33 (-0.34% of base) : 14914.dasm - <SendAsync>d__6:MoveNext():this
         -28 (-1.59% of base) : 27636.dasm - SslStream:FillHandshakeBufferAsync(AsyncReadWriteAdapter,int):ValueTask`1:this
         -25 (-1.44% of base) : 7355.dasm - Http1Connection:TryParseRequest(ReadResult,byref):bool:this
         -25 (-0.16% of base) : 14956.dasm - <SendAsyncCore>d__60:MoveNext():this
         -25 (-0.64% of base) : 27890.dasm - <ReadAsyncInternal>d__186`1:MoveNext():this
         -25 (-0.51% of base) : 27553.dasm - <ReceiveBlobAsync>d__174`1:MoveNext():this
         -22 (-0.58% of base) : 27909.dasm - <<ReadAsync>g__Core|36_0>d:MoveNext():this
         -22 (-1.04% of base) : 30111.dasm - Http1OutputProducer:FlushAsync(CancellationToken):ValueTask`1:this
         -19 (-0.40% of base) : 6214.dasm - <ProcessRequestsAsync>d__69:MoveNext():this
         -18 (-1.47% of base) : 29696.dasm - ConcurrentPipeWriter:FlushAsync(CancellationToken):ValueTask`1:this
         -17 (-1.33% of base) : 10478.dasm - BufferedFileStreamStrategy:ReadAsync(Memory`1,CancellationToken):ValueTask`1:this
         -14 (-3.74% of base) : 27642.dasm - AsyncReadWriteAdapter:ReadAsync(Memory`1):ValueTask`1:this
         -14 (-4.53% of base) : 9969.dasm - GenericConnectionListener:AcceptAsync(CancellationToken):ValueTask`1:this
         -14 (-0.74% of base) : 28013.dasm - <EnsureFullTlsFrameAsync>d__184`1:MoveNext():this
         -14 (-0.52% of base) : 28301.dasm - <LoadFortunesRows>d__9:MoveNext():this
         -13 (-4.59% of base) : 15023.dasm - HttpForwarder:CopyResponseTrailingHeadersAsync(HttpResponseMessage,HttpContext,HttpTransformer):ValueTask
         -13 (-4.59% of base) : 17415.dasm - HttpForwarder:CopyResponseTrailingHeadersAsync(HttpResponseMessage,HttpContext,HttpTransformer):ValueTask
         -13 (-4.26% of base) : 44208.dasm - RelationalConnection:Microsoft.EntityFrameworkCore.Infrastructure.IResettableService.ResetStateAsync(CancellationToken):Task:this
         -13 (-0.68% of base) : 29704.dasm - TimingPipeFlusher:FlushAsync(MinDataRate,long,IHttpOutputAborter,CancellationToken):ValueTask`1:this

Top method regressions (percentages):
          94 ( 2.86% of base) : 32927.dasm - <<ReadMessage>g__ReadMessageLong|208_0>d:MoveNext():this
          80 ( 2.38% of base) : 39996.dasm - <<ReadMessage>g__ReadMessageLong|208_0>d:MoveNext():this
          19 ( 1.90% of base) : 10034.dasm - PathUtils:PathNavigatesAboveRoot(String):bool

Top method improvements (percentages):
         -13 (-4.59% of base) : 15023.dasm - HttpForwarder:CopyResponseTrailingHeadersAsync(HttpResponseMessage,HttpContext,HttpTransformer):ValueTask
         -13 (-4.59% of base) : 17415.dasm - HttpForwarder:CopyResponseTrailingHeadersAsync(HttpResponseMessage,HttpContext,HttpTransformer):ValueTask
         -14 (-4.53% of base) : 9969.dasm - GenericConnectionListener:AcceptAsync(CancellationToken):ValueTask`1:this
         -13 (-4.26% of base) : 44208.dasm - RelationalConnection:Microsoft.EntityFrameworkCore.Infrastructure.IResettableService.ResetStateAsync(CancellationToken):Task:this
         -14 (-3.74% of base) : 27642.dasm - AsyncReadWriteAdapter:ReadAsync(Memory`1):ValueTask`1:this
         -11 (-3.68% of base) : 30193.dasm - RelationalConnection:Microsoft.EntityFrameworkCore.Infrastructure.IResettableService.ResetStateAsync(CancellationToken):Task:this
         -11 (-3.59% of base) : 14400.dasm - GenericConnectionListener:AcceptAsync(CancellationToken):ValueTask`1:this
         -11 (-3.56% of base) : 4910.dasm - GenericConnectionListener:AcceptAsync(CancellationToken):ValueTask`1:this
         -11 (-3.33% of base) : 31931.dasm - NpgsqlDataReader:ReadMessage(bool):ValueTask`1:this
         -11 (-3.33% of base) : 39607.dasm - NpgsqlDataReader:ReadMessage(bool):ValueTask`1:this
         -11 (-2.85% of base) : 29697.dasm - StreamPipeWriter:FlushAsync(CancellationToken):ValueTask`1:this
         -11 (-2.61% of base) : 29747.dasm - AsyncEnumerator:DisposeAsync():ValueTask:this
         -11 (-2.58% of base) : 44127.dasm - AsyncEnumerator:DisposeAsync():ValueTask:this
         -11 (-2.47% of base) : 29762.dasm - NpgsqlDataReader:DisposeAsync():ValueTask:this
         -11 (-2.47% of base) : 44148.dasm - NpgsqlDataReader:DisposeAsync():ValueTask:this
         -11 (-2.31% of base) : 15501.dasm - HttpConnectionPool:SendWithProxyAuthAsync(HttpRequestMessage,bool,bool,CancellationToken):ValueTask`1:this
         -11 (-1.98% of base) : 15800.dasm - HttpConnection:CheckUsabilityOnScavenge():bool:this
         -11 (-1.83% of base) : 15499.dasm - HttpConnectionPool:SendAsync(HttpRequestMessage,bool,bool,CancellationToken):ValueTask`1:this
         -28 (-1.59% of base) : 27636.dasm - SslStream:FillHandshakeBufferAsync(AsyncReadWriteAdapter,int):ValueTask`1:this
         -11 (-1.49% of base) : 31665.dasm - NpgsqlCommand:ExecuteReaderAsync(int,CancellationToken):Task`1:this

92 total methods with Code Size differences (89 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 38901
Total bytes of diff: 38355
Total bytes of delta: -546 (-1.40% of base)
Total relative delta: -0.31
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           7 : 25082.dasm (0.45% of base)

Top file improvements (bytes):
        -222 : 15623.dasm (-7.92% of base)
         -45 : 17695.dasm (-3.32% of base)
         -37 : 17711.dasm (-6.21% of base)
         -34 : 8684.dasm (-1.66% of base)
         -34 : 17504.dasm (-2.07% of base)
         -34 : 20176.dasm (-1.62% of base)
         -32 : 17692.dasm (-1.80% of base)
         -31 : 18921.dasm (-1.92% of base)
         -31 : 8655.dasm (-2.77% of base)
         -15 : 23054.dasm (-0.77% of base)
         -11 : 17682.dasm (-0.38% of base)
         -11 : 17714.dasm (-0.58% of base)
          -8 : 5166.dasm (-0.44% of base)
          -8 : 21255.dasm (-0.40% of base)

15 total files with Code Size differences (14 improved, 1 regressed), 5 unchanged.

Top method regressions (bytes):
           7 ( 0.45% of base) : 25082.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this

Top method improvements (bytes):
        -222 (-7.92% of base) : 15623.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -45 (-3.32% of base) : 17695.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -37 (-6.21% of base) : 17711.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -34 (-1.66% of base) : 8684.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -34 (-2.07% of base) : 17504.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -34 (-1.62% of base) : 20176.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         -32 (-1.80% of base) : 17692.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -31 (-1.92% of base) : 18921.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
         -31 (-2.77% of base) : 8655.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -15 (-0.77% of base) : 23054.dasm - <ReadScatterAsync>d__15:MoveNext():this
         -11 (-0.38% of base) : 17682.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this
         -11 (-0.58% of base) : 17714.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
          -8 (-0.44% of base) : 5166.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -8 (-0.40% of base) : 21255.dasm - <WriteGatherAsync>d__22:MoveNext():this

Top method regressions (percentages):
           7 ( 0.45% of base) : 25082.dasm - System.Memory.SequenceReader:TryReadTo():System.Buffers.ReadOnlySequence`1[Int32]:this

Top method improvements (percentages):
        -222 (-7.92% of base) : 15623.dasm - System.Text.Json.Tests.Perf_Segment:ReadMultiSegmentSequenceUsingSpan(int):this
         -37 (-6.21% of base) : 17711.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -45 (-3.32% of base) : 17695.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -31 (-2.77% of base) : 8655.dasm - System.Buffers.Tests.ReadOnlySequenceTests`1[Char][System.Char]:IterateForEach(System.Buffers.ReadOnlySequence`1[Char]):int:this
         -34 (-2.07% of base) : 17504.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetWellKnownType(int):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -31 (-1.92% of base) : 18921.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureEnumUnderlyingTypeIsLoaded(UncommonProperties):this
         -32 (-1.80% of base) : 17692.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:CreateFields(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEFieldSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -34 (-1.66% of base) : 8684.dasm - System.Collections.Immutable.ImmutableHashSet`1[Int32][System.Int32]:Union(System.Collections.Generic.IEnumerable`1[Int32],MutationInput[Int32]):MutationResult[Int32]
         -34 (-1.62% of base) : 20176.dasm - Microsoft.CodeAnalysis.CSharp.InMethodBinder:LookupSymbolsInSingleBinder(Microsoft.CodeAnalysis.CSharp.LookupResult,System.String,int,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         -15 (-0.77% of base) : 23054.dasm - <ReadScatterAsync>d__15:MoveNext():this
         -11 (-0.58% of base) : 17714.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:GetSignatureForMethod(System.Reflection.Metadata.MethodDefinitionHandle,byref,byref,bool):Microsoft.CodeAnalysis.ParamInfo`1[System.__Canon][]:this
          -8 (-0.44% of base) : 5166.dasm - <WriteGatherAsync>d__16:MoveNext():this
          -8 (-0.40% of base) : 21255.dasm - <WriteGatherAsync>d__22:MoveNext():this
         -11 (-0.38% of base) : 17682.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamedTypeSymbol:LoadMembers():this

15 total methods with Code Size differences (14 improved, 1 regressed), 5 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 22132
Total bytes of diff: 21770
Total bytes of delta: -362 (-1.64% of base)
Total relative delta: -0.15
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -119 : 205836.dasm (-1.91% of base)
        -109 : 164263.dasm (-5.48% of base)
         -48 : 164274.dasm (-1.74% of base)
         -18 : 164265.dasm (-0.93% of base)
         -16 : 164153.dasm (-1.49% of base)
         -12 : 164268.dasm (-0.83% of base)
         -11 : 164895.dasm (-0.83% of base)
         -11 : 164264.dasm (-0.65% of base)
          -7 : 164829.dasm (-0.50% of base)
          -7 : 164836.dasm (-0.62% of base)
          -4 : 164822.dasm (-0.35% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -119 (-1.91% of base) : 205836.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
        -109 (-5.48% of base) : 164263.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -48 (-1.74% of base) : 164274.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -18 (-0.93% of base) : 164265.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -16 (-1.49% of base) : 164153.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
         -12 (-0.83% of base) : 164268.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -11 (-0.83% of base) : 164895.dasm - <Verify>d__9:MoveNext():bool:this
         -11 (-0.65% of base) : 164264.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
          -7 (-0.50% of base) : 164829.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -7 (-0.62% of base) : 164836.dasm - <GetFields>d__44:MoveNext():bool:this
          -4 (-0.35% of base) : 164822.dasm - <GetMethods>d__38:MoveNext():bool:this

Top method improvements (percentages):
        -109 (-5.48% of base) : 164263.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
        -119 (-1.91% of base) : 205836.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -48 (-1.74% of base) : 164274.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -16 (-1.49% of base) : 164153.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
         -18 (-0.93% of base) : 164265.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -11 (-0.83% of base) : 164895.dasm - <Verify>d__9:MoveNext():bool:this
         -12 (-0.83% of base) : 164268.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -11 (-0.65% of base) : 164264.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this
          -7 (-0.62% of base) : 164836.dasm - <GetFields>d__44:MoveNext():bool:this
          -7 (-0.50% of base) : 164829.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -4 (-0.35% of base) : 164822.dasm - <GetMethods>d__38:MoveNext():bool:this

11 total methods with Code Size differences (11 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7895
Total bytes of diff: 7395
Total bytes of delta: -500 (-6.33% of base)
Total relative delta: -1.30
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -90 : 71928.dasm (-9.13% of base)
         -66 : 147777.dasm (-13.36% of base)
         -66 : 147776.dasm (-13.36% of base)
         -60 : 71967.dasm (-4.24% of base)
         -48 : 71944.dasm (-2.55% of base)
         -39 : 71947.dasm (-6.12% of base)
         -36 : 71936.dasm (-6.84% of base)
         -35 : 71961.dasm (-7.48% of base)
         -24 : 148153.dasm (-32.88% of base)
         -24 : 148152.dasm (-32.88% of base)
         -12 : 71956.dasm (-1.42% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -90 (-9.13% of base) : 71928.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -66 (-13.36% of base) : 147777.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -66 (-13.36% of base) : 147776.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -60 (-4.24% of base) : 71967.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-2.55% of base) : 71944.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -39 (-6.12% of base) : 71947.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -36 (-6.84% of base) : 71936.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -35 (-7.48% of base) : 71961.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-32.88% of base) : 148153.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -24 (-32.88% of base) : 148152.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -12 (-1.42% of base) : 71956.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method improvements (percentages):
         -24 (-32.88% of base) : 148153.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -24 (-32.88% of base) : 148152.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -66 (-13.36% of base) : 147777.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -66 (-13.36% of base) : 147776.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -90 (-9.13% of base) : 71928.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -35 (-7.48% of base) : 71961.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -36 (-6.84% of base) : 71936.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -39 (-6.12% of base) : 71947.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -60 (-4.24% of base) : 71967.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-2.55% of base) : 71944.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -12 (-1.42% of base) : 71956.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

11 total methods with Code Size differences (11 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 252555
Total bytes of diff: 248778
Total bytes of delta: -3777 (-1.50% of base)
Total relative delta: -3.41
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 25745.dasm (0.88% of base)

Top file improvements (bytes):
        -284 : 205616.dasm (-7.86% of base)
        -109 : 160358.dasm (-5.48% of base)
         -98 : 73819.dasm (-2.63% of base)
         -85 : 160376.dasm (-5.19% of base)
         -79 : 201433.dasm (-3.77% of base)
         -74 : 154205.dasm (-2.17% of base)
         -74 : 26222.dasm (-2.02% of base)
         -72 : 73778.dasm (-6.34% of base)
         -71 : 149430.dasm (-14.43% of base)
         -71 : 149431.dasm (-14.43% of base)
         -66 : 112195.dasm (-5.41% of base)
         -64 : 112863.dasm (-5.47% of base)
         -62 : 51957.dasm (-1.71% of base)
         -57 : 212809.dasm (-2.36% of base)
         -55 : 73802.dasm (-6.17% of base)
         -55 : 103212.dasm (-13.06% of base)
         -55 : 72907.dasm (-1.89% of base)
         -55 : 73796.dasm (-1.89% of base)
         -48 : 160324.dasm (-1.74% of base)
         -46 : 112242.dasm (-4.56% of base)

107 total files with Code Size differences (106 improved, 1 regressed), 32 unchanged.

Top method regressions (bytes):
           8 ( 0.88% of base) : 25745.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetHostObjectTypeSymbol():Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:this

Top method improvements (bytes):
        -284 (-7.86% of base) : 205616.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
        -109 (-5.48% of base) : 160358.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -98 (-2.63% of base) : 73819.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -85 (-5.19% of base) : 160376.dasm - Internal.TypeSystem.Ecma.PortablePdbSymbolReader:ProbeScopeForLocals(System.Collections.Generic.List`1[ILLocalVariable],System.Reflection.Metadata.LocalScopeHandle):this
         -79 (-3.77% of base) : 201433.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
         -74 (-2.17% of base) : 154205.dasm - System.Text.Json.Utf8JsonReader:UnescapeSequenceAndCompare(System.ReadOnlySpan`1[Byte]):bool:this
         -74 (-2.02% of base) : 26222.dasm - Microsoft.CodeAnalysis.CSharp.ClsComplianceChecker:CheckSymbolDistinctness(Microsoft.CodeAnalysis.CSharp.Symbol,System.String,Roslyn.Utilities.MultiDictionary`2+ValueSet[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -72 (-6.34% of base) : 73778.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -71 (-14.43% of base) : 149430.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -71 (-14.43% of base) : 149431.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -66 (-5.41% of base) : 112195.dasm - System.Data.DataView:ResetRowViewCache():this
         -64 (-5.47% of base) : 112863.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -62 (-1.71% of base) : 51957.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureNonTypeMemberNamesAreLoaded():this
         -57 (-2.36% of base) : 212809.dasm - System.Reflection.TypeLoading.Ecma.EcmaDefinitionType:ComputeEnumUnderlyingType():System.Reflection.TypeLoading.RoType:this
         -55 (-6.17% of base) : 73802.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -55 (-13.06% of base) : 103212.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
         -55 (-1.89% of base) : 72907.dasm - VB$StateMachine_69_GetMethodsToEmit:MoveNext():bool:this
         -55 (-1.89% of base) : 73796.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-1.74% of base) : 160324.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -46 (-4.56% of base) : 112242.dasm - System.Data.DataView:CopyTo(System.Array,int):this

Top method regressions (percentages):
           8 ( 0.88% of base) : 25745.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetHostObjectTypeSymbol():Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:this

Top method improvements (percentages):
         -29 (-37.66% of base) : 149102.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -29 (-37.66% of base) : 149103.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -71 (-14.43% of base) : 149430.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -71 (-14.43% of base) : 149431.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -55 (-13.06% of base) : 103212.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
        -284 (-7.86% of base) : 205616.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
         -72 (-6.34% of base) : 73778.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -55 (-6.17% of base) : 73802.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -37 (-6.00% of base) : 73809.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -34 (-5.91% of base) : 42389.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MissingCorLibrarySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
         -34 (-5.88% of base) : 52764.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.MissingCorLibrarySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
         -34 (-5.54% of base) : 42356.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MetadataOrSourceAssemblySymbol:GetDeclaredSpecialType(byte):Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:this
        -109 (-5.48% of base) : 160358.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -64 (-5.47% of base) : 112863.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -66 (-5.41% of base) : 112195.dasm - System.Data.DataView:ResetRowViewCache():this
         -85 (-5.19% of base) : 160376.dasm - Internal.TypeSystem.Ecma.PortablePdbSymbolReader:ProbeScopeForLocals(System.Collections.Generic.List`1[ILLocalVariable],System.Reflection.Metadata.LocalScopeHandle):this
         -46 (-4.59% of base) : 112243.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -46 (-4.56% of base) : 112242.dasm - System.Data.DataView:CopyTo(System.Array,int):this
         -20 (-3.80% of base) : 77926.dasm - Microsoft.CodeAnalysis.PEModule:GetParametersOfMethodOrThrow(System.Reflection.Metadata.MethodDefinitionHandle):System.Reflection.Metadata.ParameterHandleCollection:this
         -20 (-3.80% of base) : 78028.dasm - Microsoft.CodeAnalysis.PEModule:GetMethodsOfTypeOrThrow(System.Reflection.Metadata.TypeDefinitionHandle):System.Reflection.Metadata.MethodDefinitionHandleCollection:this

107 total methods with Code Size differences (106 improved, 1 regressed), 32 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 421423
Total bytes of diff: 419425
Total bytes of delta: -1998 (-0.47% of base)
Total relative delta: -1.18
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          40 : 175856.dasm (2.21% of base)
          33 : 175841.dasm (2.57% of base)
          32 : 315810.dasm (1.03% of base)
          32 : 315808.dasm (1.13% of base)
          26 : 175842.dasm (1.89% of base)
          26 : 175847.dasm (1.90% of base)
          24 : 175830.dasm (1.05% of base)
          19 : 175855.dasm (0.83% of base)
          18 : 175844.dasm (1.23% of base)
          18 : 175834.dasm (1.65% of base)
          18 : 175843.dasm (1.20% of base)
           4 : 175869.dasm (0.20% of base)
           1 : 175900.dasm (0.02% of base)

Top file improvements (bytes):
        -216 : 175652.dasm (-5.10% of base)
        -135 : 290109.dasm (-1.75% of base)
        -109 : 290099.dasm (-2.11% of base)
         -78 : 128583.dasm (-8.18% of base)
         -72 : 125317.dasm (-6.56% of base)
         -69 : 128582.dasm (-3.87% of base)
         -67 : 68188.dasm (-8.11% of base)
         -67 : 192346.dasm (-8.11% of base)
         -66 : 125316.dasm (-2.92% of base)
         -66 : 9154.dasm (-1.23% of base)
         -66 : 128596.dasm (-3.91% of base)
         -64 : 128624.dasm (-3.99% of base)
         -64 : 125355.dasm (-3.60% of base)
         -58 : 16029.dasm (-1.95% of base)
         -56 : 125328.dasm (-2.62% of base)
         -55 : 175899.dasm (-1.24% of base)
         -42 : 16252.dasm (-0.54% of base)
         -37 : 9567.dasm (-1.90% of base)
         -36 : 16266.dasm (-1.67% of base)
         -34 : 12482.dasm (-2.44% of base)

112 total files with Code Size differences (99 improved, 13 regressed), 51 unchanged.

Top method regressions (bytes):
          40 ( 2.21% of base) : 175856.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo():this
          33 ( 2.57% of base) : 175841.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceToEndThenPeekReturnsDefault():this
          32 ( 1.03% of base) : 315810.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
          32 ( 1.13% of base) : 315808.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          26 ( 1.89% of base) : 175842.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvancingPastLengthThrows():this
          26 ( 1.90% of base) : 175847.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceThrowsPastLengthMultipleSegments():this
          24 ( 1.05% of base) : 175830.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsWithoutMoving():this
          19 ( 0.83% of base) : 175855.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:Advance_PositionIsCorrect(int):this
          18 ( 1.23% of base) : 175844.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:EmptySegmentsAreSkippedOnMoveNext():this
          18 ( 1.65% of base) : 175834.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset_Empty():this
          18 ( 1.20% of base) : 175843.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:CtorFindsFirstNonEmptySegment():this
           4 ( 0.20% of base) : 175869.dasm - System.Memory.Tests.SequenceReader.IsNext:IsNext_Value():this
           1 ( 0.02% of base) : 175900.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadToSpan_Sequence(bool):this

Top method improvements (bytes):
        -216 (-5.10% of base) : 175652.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
        -135 (-1.75% of base) : 290109.dasm - <ReaderShouldNotGetUnflushedBytesWithAppend>d__17:MoveNext():this
        -109 (-2.11% of base) : 290099.dasm - <HelloWorldAcrossTwoBlocks>d__11:MoveNext():this
         -78 (-8.18% of base) : 128583.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -72 (-6.56% of base) : 125317.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -69 (-3.87% of base) : 128582.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -67 (-8.11% of base) : 68188.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -67 (-8.11% of base) : 192346.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -66 (-2.92% of base) : 125316.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -66 (-1.23% of base) : 9154.dasm - Microsoft.CodeAnalysis.Formatting.AbstractTriviaFormatter:FormatTrivia(Formatter`1[Byte],WhitespaceAppender`1[Byte],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[Byte],System.Threading.CancellationToken):Microsoft.CodeAnalysis.Formatting.LineColumn:this
         -66 (-3.91% of base) : 128596.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -64 (-3.99% of base) : 128624.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -64 (-3.60% of base) : 125355.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -58 (-1.95% of base) : 16029.dasm - <AddMatchingTypesAsync>d__23:MoveNext():this
         -56 (-2.62% of base) : 125328.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -55 (-1.24% of base) : 175899.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
         -42 (-0.54% of base) : 16252.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -37 (-1.90% of base) : 9567.dasm - Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo:GenerateSourceNodes(System.String,int,Roslyn.Utilities.MultiDictionary`2+ValueSet[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[BuilderNode],System.Action`2[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]])
         -36 (-1.67% of base) : 16266.dasm - MetadataInfoCreator:AddUnsortedNodes(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[BuilderNode],Roslyn.Utilities.MultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+ExtensionMethodInfo, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],MetadataNode,int,System.String):this
         -34 (-2.44% of base) : 12482.dasm - ValueSet[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Contains(System.Nullable`1[Int32],System.Collections.Generic.IEqualityComparer`1[Nullable`1]):bool:this

Top method regressions (percentages):
          33 ( 2.57% of base) : 175841.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceToEndThenPeekReturnsDefault():this
          40 ( 2.21% of base) : 175856.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceTo():this
          26 ( 1.90% of base) : 175847.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceThrowsPastLengthMultipleSegments():this
          26 ( 1.89% of base) : 175842.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvancingPastLengthThrows():this
          18 ( 1.65% of base) : 175834.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset_Empty():this
          18 ( 1.23% of base) : 175844.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:EmptySegmentsAreSkippedOnMoveNext():this
          18 ( 1.20% of base) : 175843.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:CtorFindsFirstNonEmptySegment():this
          32 ( 1.13% of base) : 315808.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          24 ( 1.05% of base) : 175830.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsWithoutMoving():this
          32 ( 1.03% of base) : 315810.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
          19 ( 0.83% of base) : 175855.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:Advance_PositionIsCorrect(int):this
           4 ( 0.20% of base) : 175869.dasm - System.Memory.Tests.SequenceReader.IsNext:IsNext_Value():this
           1 ( 0.02% of base) : 175900.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadToSpan_Sequence(bool):this

Top method improvements (percentages):
         -78 (-8.18% of base) : 128583.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -67 (-8.11% of base) : 68188.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -67 (-8.11% of base) : 192346.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -72 (-6.56% of base) : 125317.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -12 (-6.45% of base) : 339525.dasm - System.Tests.ExtensionsTests:Deconstruct4()
          -9 (-5.33% of base) : 339524.dasm - System.Tests.ExtensionsTests:Deconstruct3()
        -216 (-5.10% of base) : 175652.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
         -64 (-3.99% of base) : 128624.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
          -6 (-3.95% of base) : 339523.dasm - System.Tests.ExtensionsTests:Deconstruct2()
         -66 (-3.91% of base) : 128596.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -69 (-3.87% of base) : 128582.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -64 (-3.60% of base) : 125355.dasm - ModifiedComplexTrivia:Format(Microsoft.CodeAnalysis.Formatting.FormattingContext,Microsoft.CodeAnalysis.Formatting.ChainedFormattingRules,System.Action`3[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.Formatting.TokenStream, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.Formatting.TriviaData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken,int):this
         -66 (-2.92% of base) : 125316.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -56 (-2.62% of base) : 125328.dasm - CodeShapeAnalyzer:ShouldFormat():bool:this
         -33 (-2.47% of base) : 179952.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -33 (-2.47% of base) : 228025.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -34 (-2.44% of base) : 12482.dasm - ValueSet[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Contains(System.Nullable`1[Int32],System.Collections.Generic.IEqualityComparer`1[Nullable`1]):bool:this
         -34 (-2.37% of base) : 12473.dasm - ValueSet[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:Contains(System.Nullable`1[Int32],System.Collections.Generic.IEqualityComparer`1[Nullable`1]):bool:this
          -3 (-2.22% of base) : 339522.dasm - System.Tests.ExtensionsTests:Deconstruct1()
         -14 (-2.18% of base) : 335914.dasm - System.Threading.Tasks.Tests.PoolingAsyncValueTaskMethodBuilderTests:Generic_SetException_BeforeAccessTask_FaultsTask():this

112 total methods with Code Size differences (99 improved, 13 regressed), 51 unchanged.

```

</details>

--------------------------------------------------------------------------------

