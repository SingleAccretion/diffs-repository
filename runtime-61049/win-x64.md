## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 11893704 (overridden on cmd)
Total bytes of diff: 11893669 (overridden on cmd)
Total bytes of delta: -35 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           1 : 7396.dasm (0.11% of base)

Top file improvements (bytes):
          -6 : 36201.dasm (-3.55% of base)
          -6 : 28462.dasm (-3.55% of base)
          -6 : 30200.dasm (-3.55% of base)
          -3 : 30249.dasm (-0.08% of base)
          -3 : 30228.dasm (-0.15% of base)
          -3 : 33438.dasm (-0.06% of base)
          -3 : 30192.dasm (-0.06% of base)
          -3 : 33443.dasm (-0.15% of base)
          -3 : 33471.dasm (-0.08% of base)

10 total files with Code Size differences (9 improved, 1 regressed), 3 unchanged.

Top method regressions (bytes):
           1 ( 0.11% of base) : 7396.dasm - RangeHelper:ParseRange(HttpContext,RequestHeaders,long,ILogger):ValueTuple`2

Top method improvements (bytes):
          -6 (-3.55% of base) : 36201.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -6 (-3.55% of base) : 28462.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -6 (-3.55% of base) : 30200.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -3 (-0.15% of base) : 30228.dasm - <Authenticate>d__0:MoveNext():this
          -3 (-0.15% of base) : 33443.dasm - <Authenticate>d__0:MoveNext():this
          -3 (-0.06% of base) : 33438.dasm - <Open>d__188:MoveNext():this
          -3 (-0.06% of base) : 30192.dasm - <Open>d__188:MoveNext():this
          -3 (-0.08% of base) : 30249.dasm - <RawOpen>d__193:MoveNext():this
          -3 (-0.08% of base) : 33471.dasm - <RawOpen>d__193:MoveNext():this

Top method regressions (percentages):
           1 ( 0.11% of base) : 7396.dasm - RangeHelper:ParseRange(HttpContext,RequestHeaders,long,ILogger):ValueTuple`2

Top method improvements (percentages):
          -6 (-3.55% of base) : 36201.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -6 (-3.55% of base) : 28462.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -6 (-3.55% of base) : 30200.dasm - NpgsqlTimeout:CheckAndApply(NpgsqlConnector):this
          -3 (-0.15% of base) : 33443.dasm - <Authenticate>d__0:MoveNext():this
          -3 (-0.15% of base) : 30228.dasm - <Authenticate>d__0:MoveNext():this
          -3 (-0.08% of base) : 33471.dasm - <RawOpen>d__193:MoveNext():this
          -3 (-0.08% of base) : 30249.dasm - <RawOpen>d__193:MoveNext():this
          -3 (-0.06% of base) : 30192.dasm - <Open>d__188:MoveNext():this
          -3 (-0.06% of base) : 33438.dasm - <Open>d__188:MoveNext():this

10 total methods with Code Size differences (9 improved, 1 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7236062 (overridden on cmd)
Total bytes of diff: 7235837 (overridden on cmd)
Total bytes of delta: -225 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          15 : 17526.dasm (0.76% of base)
           8 : 26634.dasm (0.40% of base)
           8 : 14917.dasm (0.53% of base)
           8 : 10664.dasm (0.56% of base)
           8 : 13100.dasm (0.57% of base)
           8 : 25400.dasm (0.56% of base)
           7 : 10676.dasm (1.24% of base)
           6 : 13101.dasm (0.30% of base)
           6 : 17532.dasm (1.28% of base)
           6 : 10678.dasm (0.32% of base)
           6 : 10689.dasm (0.36% of base)
           5 : 14927.dasm (0.89% of base)
           5 : 13103.dasm (0.33% of base)
           3 : 14921.dasm (0.49% of base)
           3 : 19964.dasm (0.71% of base)

Top file improvements (bytes):
         -84 : 18724.dasm (-4.43% of base)
         -75 : 18710.dasm (-6.44% of base)
         -45 : 18167.dasm (-1.85% of base)
         -32 : 18522.dasm (-0.36% of base)
         -21 : 9719.dasm (-2.72% of base)
         -13 : 18559.dasm (-1.17% of base)
          -9 : 15619.dasm (-0.38% of base)
          -8 : 19657.dasm (-1.41% of base)
          -7 : 13162.dasm (-0.37% of base)
          -4 : 17916.dasm (-0.39% of base)
          -3 : 17466.dasm (-0.12% of base)
          -3 : 2418.dasm (-0.04% of base)
          -3 : 3607.dasm (-0.93% of base)
          -3 : 6064.dasm (-0.15% of base)
          -3 : 18743.dasm (-0.62% of base)
          -3 : 3305.dasm (-0.47% of base)
          -2 : 10479.dasm (-0.78% of base)
          -2 : 19307.dasm (-0.34% of base)
          -2 : 4683.dasm (-1.22% of base)
          -2 : 26159.dasm (-0.24% of base)

38 total files with Code Size differences (23 improved, 15 regressed), 20 unchanged.

Top method regressions (bytes):
          15 ( 0.76% of base) : 17526.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Immutable.ImmutableHashSet`1+Builder[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref)
           8 ( 0.53% of base) : 14917.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CollectionsOfPrimitivesFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CollectionsOfPrimitives:this
           8 ( 0.56% of base) : 10664.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_IndexViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.IndexViewModel:this
           8 ( 0.40% of base) : 26634.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.Location:this
           8 ( 0.56% of base) : 25400.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LoginViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.LoginViewModel:this
           8 ( 0.57% of base) : 13100.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerViewModel:this
           7 ( 1.24% of base) : 10676.dasm - MessagePack.Formatters.ListFormatter`1[__Canon][System.__Canon]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.Collections.Generic.List`1[__Canon]:this
           6 ( 0.32% of base) : 10678.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent:this
           6 ( 0.36% of base) : 10689.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CampaignSummaryViewModelFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CampaignSummaryViewModel:this
           6 ( 0.30% of base) : 13101.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItem:this
           6 ( 1.28% of base) : 17532.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CheckMethodMemberForExtensionSyntax(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode):bool
           5 ( 0.89% of base) : 14927.dasm - MessagePack.Formatters.ListFormatter`1[Int32][System.Int32]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.Collections.Generic.List`1[Int32]:this
           5 ( 0.33% of base) : 13103.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemTaskFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
           3 ( 0.49% of base) : 14921.dasm - MessagePack.Formatters.DictionaryFormatterBase`5[Int32,__Canon,__Canon,Enumerator,__Canon][System.Int32,System.__Canon,System.__Canon,System.Collections.Generic.Dictionary`2+Enumerator[System.Int32,System.__Canon],System.__Canon]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.__Canon:this
           3 ( 0.71% of base) : 19964.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this

Top method improvements (bytes):
         -84 (-4.43% of base) : 18724.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -75 (-6.44% of base) : 18710.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -45 (-1.85% of base) : 18167.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:MakeDeclaredBases(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Tuple`2[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
         -32 (-0.36% of base) : 18522.dasm - Microsoft.CodeAnalysis.CSharp.Imports:FromSyntax(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.InContainerBinder,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool):Microsoft.CodeAnalysis.CSharp.Imports
         -21 (-2.72% of base) : 9719.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
         -13 (-1.17% of base) : 18559.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindBlockParts(Microsoft.CodeAnalysis.CSharp.Syntax.BlockSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
          -9 (-0.38% of base) : 15619.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-1.41% of base) : 19657.dasm - Microsoft.Cci.MetadataWriter:AddCustomAttributesToTable(System.Collections.Generic.IEnumerable`1[__Canon],System.Func`2[__Canon,EntityHandle]):this
          -7 (-0.37% of base) : 13162.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.39% of base) : 17916.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamespaceSymbol:LazyInitializeTypes(System.Collections.Generic.IEnumerable`1[[System.Linq.IGrouping`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.Metadata.TypeDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], System.Linq, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
          -3 (-0.47% of base) : 3305.dasm - DataContractCriticalHelper:GetId(System.RuntimeTypeHandle):int
          -3 (-0.62% of base) : 18743.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -3 (-0.12% of base) : 17466.dasm - ReferenceManager:CreateAndSetSourceAssemblyFullBind(Microsoft.CodeAnalysis.CSharp.CSharpCompilation):bool:this
          -3 (-0.93% of base) : 3607.dasm - System.DateTimeOffset:get_UtcNow():System.DateTimeOffset
          -3 (-0.15% of base) : 6064.dasm - System.Text.RegularExpressions.RegexCompiler:<TryGenerateNonBacktrackingGo>g__EmitSingleCharAtomicLoop|205_19(System.Text.RegularExpressions.RegexNode,byref):this
          -3 (-0.04% of base) : 2418.dasm - System.Text.RegularExpressions.RegexCompiler:GenerateFindFirstChar():this
          -2 (-0.34% of base) : 19307.dasm - Microsoft.Cci.MetadataWriter:GetMethodSignatureHandleAndBlob(Microsoft.Cci.IMethodReference,byref):System.Reflection.Metadata.BlobHandle:this
          -2 (-1.22% of base) : 4683.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
          -2 (-0.24% of base) : 26159.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.String,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
          -2 (-0.78% of base) : 10479.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this

Top method regressions (percentages):
           6 ( 1.28% of base) : 17532.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CheckMethodMemberForExtensionSyntax(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode):bool
           7 ( 1.24% of base) : 10676.dasm - MessagePack.Formatters.ListFormatter`1[__Canon][System.__Canon]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.Collections.Generic.List`1[__Canon]:this
           5 ( 0.89% of base) : 14927.dasm - MessagePack.Formatters.ListFormatter`1[Int32][System.Int32]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.Collections.Generic.List`1[Int32]:this
          15 ( 0.76% of base) : 17526.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Immutable.ImmutableHashSet`1+Builder[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref)
           3 ( 0.71% of base) : 19964.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
           8 ( 0.57% of base) : 13100.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerViewModel:this
           8 ( 0.56% of base) : 10664.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_IndexViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.IndexViewModel:this
           8 ( 0.56% of base) : 25400.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LoginViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.LoginViewModel:this
           8 ( 0.53% of base) : 14917.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CollectionsOfPrimitivesFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CollectionsOfPrimitives:this
           3 ( 0.49% of base) : 14921.dasm - MessagePack.Formatters.DictionaryFormatterBase`5[Int32,__Canon,__Canon,Enumerator,__Canon][System.Int32,System.__Canon,System.__Canon,System.Collections.Generic.Dictionary`2+Enumerator[System.Int32,System.__Canon],System.__Canon]:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):System.__Canon:this
           8 ( 0.40% of base) : 26634.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.Location:this
           6 ( 0.36% of base) : 10689.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CampaignSummaryViewModelFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CampaignSummaryViewModel:this
           5 ( 0.33% of base) : 13103.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemTaskFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
           6 ( 0.32% of base) : 10678.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent:this
           6 ( 0.30% of base) : 13101.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItem:this

Top method improvements (percentages):
         -75 (-6.44% of base) : 18710.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -84 (-4.43% of base) : 18724.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -21 (-2.72% of base) : 9719.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
         -45 (-1.85% of base) : 18167.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:MakeDeclaredBases(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Tuple`2[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
          -8 (-1.41% of base) : 19657.dasm - Microsoft.Cci.MetadataWriter:AddCustomAttributesToTable(System.Collections.Generic.IEnumerable`1[__Canon],System.Func`2[__Canon,EntityHandle]):this
          -2 (-1.22% of base) : 4683.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
         -13 (-1.17% of base) : 18559.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindBlockParts(Microsoft.CodeAnalysis.CSharp.Syntax.BlockSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
          -3 (-0.93% of base) : 3607.dasm - System.DateTimeOffset:get_UtcNow():System.DateTimeOffset
          -2 (-0.78% of base) : 10479.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -3 (-0.62% of base) : 18743.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -3 (-0.47% of base) : 3305.dasm - DataContractCriticalHelper:GetId(System.RuntimeTypeHandle):int
          -4 (-0.39% of base) : 17916.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamespaceSymbol:LazyInitializeTypes(System.Collections.Generic.IEnumerable`1[[System.Linq.IGrouping`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.Metadata.TypeDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], System.Linq, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
          -9 (-0.38% of base) : 15619.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -7 (-0.37% of base) : 13162.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -32 (-0.36% of base) : 18522.dasm - Microsoft.CodeAnalysis.CSharp.Imports:FromSyntax(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.InContainerBinder,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool):Microsoft.CodeAnalysis.CSharp.Imports
          -2 (-0.34% of base) : 19307.dasm - Microsoft.Cci.MetadataWriter:GetMethodSignatureHandleAndBlob(Microsoft.Cci.IMethodReference,byref):System.Reflection.Metadata.BlobHandle:this
          -1 (-0.29% of base) : 17605.dasm - Microsoft.CodeAnalysis.PEAssembly:.ctor(Microsoft.CodeAnalysis.AssemblyMetadata,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -2 (-0.24% of base) : 26159.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.String,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
          -1 (-0.15% of base) : 4649.dasm - System.Drawing.Image:Save(System.IO.Stream,System.Drawing.Imaging.ImageCodecInfo,System.Drawing.Imaging.EncoderParameters):this
          -3 (-0.15% of base) : 6064.dasm - System.Text.RegularExpressions.RegexCompiler:<TryGenerateNonBacktrackingGo>g__EmitSingleCharAtomicLoop|205_19(System.Text.RegularExpressions.RegexNode,byref):this

38 total methods with Code Size differences (23 improved, 15 regressed), 20 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 127268821 (overridden on cmd)
Total bytes of diff: 127268496 (overridden on cmd)
Total bytes of delta: -325 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 210714.dasm (1.33% of base)

Top file improvements (bytes):
        -247 : 89397.dasm (-94.64% of base)
         -21 : 84407.dasm (-2.72% of base)
         -20 : 209649.dasm (-1.24% of base)
          -9 : 83703.dasm (-1.64% of base)
          -6 : 168586.dasm (-0.42% of base)
          -6 : 169197.dasm (-0.44% of base)
          -4 : 169209.dasm (-0.24% of base)
          -4 : 169205.dasm (-0.27% of base)
          -4 : 168814.dasm (-0.23% of base)
          -4 : 168852.dasm (-0.25% of base)
          -4 : 168719.dasm (-0.23% of base)
          -4 : 169204.dasm (-0.24% of base)
          -4 : 169211.dasm (-0.27% of base)
          -4 : 168738.dasm (-0.25% of base)

15 total files with Code Size differences (14 improved, 1 regressed), 2 unchanged.

Top method regressions (bytes):
          16 ( 1.33% of base) : 210714.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this

Top method improvements (bytes):
        -247 (-94.64% of base) : 89397.dasm - <Module>:Main():int
         -21 (-2.72% of base) : 84407.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
         -20 (-1.24% of base) : 209649.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          -9 (-1.64% of base) : 83703.dasm - X:F():int
          -6 (-0.42% of base) : 168586.dasm - NullableTest17:Run()
          -6 (-0.44% of base) : 169197.dasm - NullableTest17:Run()
          -4 (-0.23% of base) : 168719.dasm - NullableTest24:Run()
          -4 (-0.24% of base) : 169204.dasm - NullableTest24:Run()
          -4 (-0.27% of base) : 169205.dasm - NullableTest25:Run()
          -4 (-0.25% of base) : 168738.dasm - NullableTest25:Run()
          -4 (-0.24% of base) : 169209.dasm - NullableTest29:Run()
          -4 (-0.23% of base) : 168814.dasm - NullableTest29:Run()
          -4 (-0.25% of base) : 168852.dasm - NullableTest31:Run()
          -4 (-0.27% of base) : 169211.dasm - NullableTest31:Run()

Top method regressions (percentages):
          16 ( 1.33% of base) : 210714.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this

Top method improvements (percentages):
        -247 (-94.64% of base) : 89397.dasm - <Module>:Main():int
         -21 (-2.72% of base) : 84407.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
          -9 (-1.64% of base) : 83703.dasm - X:F():int
         -20 (-1.24% of base) : 209649.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          -6 (-0.44% of base) : 169197.dasm - NullableTest17:Run()
          -6 (-0.42% of base) : 168586.dasm - NullableTest17:Run()
          -4 (-0.27% of base) : 169205.dasm - NullableTest25:Run()
          -4 (-0.27% of base) : 169211.dasm - NullableTest31:Run()
          -4 (-0.25% of base) : 168738.dasm - NullableTest25:Run()
          -4 (-0.25% of base) : 168852.dasm - NullableTest31:Run()
          -4 (-0.24% of base) : 169204.dasm - NullableTest24:Run()
          -4 (-0.24% of base) : 169209.dasm - NullableTest29:Run()
          -4 (-0.23% of base) : 168719.dasm - NullableTest24:Run()
          -4 (-0.23% of base) : 168814.dasm - NullableTest29:Run()

15 total methods with Code Size differences (14 improved, 1 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 34150239 (overridden on cmd)
Total bytes of diff: 34149992 (overridden on cmd)
Total bytes of delta: -247 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           5 : 2880.dasm (2.59% of base)
           5 : 2879.dasm (1.39% of base)
           5 : 2882.dasm (2.54% of base)
           5 : 47042.dasm (4.72% of base)
           3 : 20265.dasm (0.25% of base)
           3 : 5184.dasm (2.22% of base)
           3 : 78806.dasm (0.27% of base)
           3 : 2881.dasm (0.90% of base)
           3 : 3318.dasm (0.44% of base)
           1 : 85598.dasm (0.07% of base)

Top file improvements (bytes):
         -92 : 181242.dasm (-14.96% of base)
         -78 : 20819.dasm (-2.73% of base)
         -35 : 181096.dasm (-2.35% of base)
         -14 : 92185.dasm (-4.09% of base)
         -14 : 161143.dasm (-2.59% of base)
         -12 : 20703.dasm (-1.98% of base)
          -7 : 161173.dasm (-1.18% of base)
          -4 : 2891.dasm (-1.47% of base)
          -3 : 212369.dasm (-0.77% of base)
          -3 : 212370.dasm (-0.42% of base)
          -3 : 212308.dasm (-0.23% of base)
          -2 : 42783.dasm (-0.81% of base)
          -2 : 169443.dasm (-0.41% of base)
          -2 : 3822.dasm (-0.49% of base)
          -2 : 91123.dasm (-0.34% of base)
          -2 : 212307.dasm (-0.24% of base)
          -2 : 3326.dasm (-1.04% of base)
          -1 : 2000.dasm (-0.29% of base)
          -1 : 1995.dasm (-0.20% of base)
          -1 : 2890.dasm (-0.95% of base)

33 total files with Code Size differences (23 improved, 10 regressed), 3 unchanged.

Top method regressions (bytes):
           5 ( 1.39% of base) : 2879.dasm - System.Drawing.Font:get_SizeInPoints():float:this
           5 ( 2.59% of base) : 2880.dasm - System.Drawing.Font:GetHeight():float:this
           5 ( 2.54% of base) : 2882.dasm - System.Drawing.Font:ToLogFont(System.Object):this
           5 ( 4.72% of base) : 47042.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           3 ( 0.27% of base) : 78806.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Generic.HashSet`1[System.String],byref)
           3 ( 0.25% of base) : 20265.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlPIData(int):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
           3 ( 2.22% of base) : 5184.dasm - SkippedTriviaBuilder:AddTrivia(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode):this
           3 ( 0.90% of base) : 2881.dasm - System.Drawing.Font:ToHfont():long:this
           3 ( 0.44% of base) : 3318.dasm - System.Drawing.Image:Save(System.IO.Stream,System.Drawing.Imaging.ImageCodecInfo,System.Drawing.Imaging.EncoderParameters):this
           1 ( 0.07% of base) : 85598.dasm - System.Configuration.BaseConfigurationRecord:ScanLocationSection(System.Configuration.XmlUtil):this

Top method improvements (bytes):
         -92 (-14.96% of base) : 181242.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -78 (-2.73% of base) : 20819.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
         -35 (-2.35% of base) : 181096.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
         -14 (-2.59% of base) : 161143.dasm - Choice@1280-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[Microsoft.FSharp.Core.FSharpOption`1[System.__Canon]]):Microsoft.FSharp.Control.AsyncReturn:this
         -14 (-4.09% of base) : 92185.dasm - System.Reflection.Metadata.MetadataReader:GetWellKnownTypeDefinitionTreatment(System.Reflection.Metadata.TypeDefinitionHandle):ubyte:this
         -12 (-1.98% of base) : 20703.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:TryReinterpretAsArraySpecifier(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArgumentListSyntax,byref):bool:this
          -7 (-1.18% of base) : 161173.dasm - Parallel@1178-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[System.__Canon[]]):Microsoft.FSharp.Control.AsyncReturn:this
          -4 (-1.47% of base) : 2891.dasm - System.Drawing.Font:FromHfont(long):System.Drawing.Font
          -3 (-0.77% of base) : 212369.dasm - System.Runtime.Caching.ExpiresBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -3 (-0.42% of base) : 212370.dasm - System.Runtime.Caching.ExpiresBucket:Reduce():this
          -3 (-0.23% of base) : 212308.dasm - System.Runtime.Caching.UsageBucket:Reduce():this
          -2 (-0.49% of base) : 3822.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -2 (-1.04% of base) : 3326.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
          -2 (-0.41% of base) : 169443.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.String,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
          -2 (-0.81% of base) : 42783.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -2 (-0.34% of base) : 91123.dasm - System.Reflection.Metadata.Ecma335.NamespaceCache:PopulateTableWithTypeDefinitions(System.Collections.Generic.Dictionary`2[System.Reflection.Metadata.NamespaceDefinitionHandle, System.Reflection.Metadata.Ecma335.NamespaceCache+NamespaceDataBuilder]):this
          -2 (-0.24% of base) : 212307.dasm - System.Runtime.Caching.UsageBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -1 (-0.95% of base) : 2890.dasm - System.Drawing.Font:FromLogFont(System.Object):System.Drawing.Font
          -1 (-0.30% of base) : 2006.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream):this
          -1 (-0.29% of base) : 2001.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,int,System.String):this

Top method regressions (percentages):
           5 ( 4.72% of base) : 47042.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 2.59% of base) : 2880.dasm - System.Drawing.Font:GetHeight():float:this
           5 ( 2.54% of base) : 2882.dasm - System.Drawing.Font:ToLogFont(System.Object):this
           3 ( 2.22% of base) : 5184.dasm - SkippedTriviaBuilder:AddTrivia(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode):this
           5 ( 1.39% of base) : 2879.dasm - System.Drawing.Font:get_SizeInPoints():float:this
           3 ( 0.90% of base) : 2881.dasm - System.Drawing.Font:ToHfont():long:this
           3 ( 0.44% of base) : 3318.dasm - System.Drawing.Image:Save(System.IO.Stream,System.Drawing.Imaging.ImageCodecInfo,System.Drawing.Imaging.EncoderParameters):this
           3 ( 0.27% of base) : 78806.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Generic.HashSet`1[System.String],byref)
           3 ( 0.25% of base) : 20265.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlPIData(int):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
           1 ( 0.07% of base) : 85598.dasm - System.Configuration.BaseConfigurationRecord:ScanLocationSection(System.Configuration.XmlUtil):this

Top method improvements (percentages):
         -92 (-14.96% of base) : 181242.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -14 (-4.09% of base) : 92185.dasm - System.Reflection.Metadata.MetadataReader:GetWellKnownTypeDefinitionTreatment(System.Reflection.Metadata.TypeDefinitionHandle):ubyte:this
         -78 (-2.73% of base) : 20819.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
         -14 (-2.59% of base) : 161143.dasm - Choice@1280-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[Microsoft.FSharp.Core.FSharpOption`1[System.__Canon]]):Microsoft.FSharp.Control.AsyncReturn:this
         -35 (-2.35% of base) : 181096.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
         -12 (-1.98% of base) : 20703.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:TryReinterpretAsArraySpecifier(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArgumentListSyntax,byref):bool:this
          -4 (-1.47% of base) : 2891.dasm - System.Drawing.Font:FromHfont(long):System.Drawing.Font
          -7 (-1.18% of base) : 161173.dasm - Parallel@1178-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[System.__Canon[]]):Microsoft.FSharp.Control.AsyncReturn:this
          -2 (-1.04% of base) : 3326.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
          -1 (-0.95% of base) : 2890.dasm - System.Drawing.Font:FromLogFont(System.Object):System.Drawing.Font
          -2 (-0.81% of base) : 42783.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -3 (-0.77% of base) : 212369.dasm - System.Runtime.Caching.ExpiresBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -2 (-0.49% of base) : 3822.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -3 (-0.42% of base) : 212370.dasm - System.Runtime.Caching.ExpiresBucket:Reduce():this
          -2 (-0.41% of base) : 169443.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.String,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
          -2 (-0.34% of base) : 91123.dasm - System.Reflection.Metadata.Ecma335.NamespaceCache:PopulateTableWithTypeDefinitions(System.Collections.Generic.Dictionary`2[System.Reflection.Metadata.NamespaceDefinitionHandle, System.Reflection.Metadata.Ecma335.NamespaceCache+NamespaceDataBuilder]):this
          -1 (-0.30% of base) : 2006.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream):this
          -1 (-0.29% of base) : 2001.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,int,System.String):this
          -1 (-0.29% of base) : 2000.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,System.Drawing.RectangleF,int,int,System.String):this
          -2 (-0.24% of base) : 212307.dasm - System.Runtime.Caching.UsageBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this

33 total methods with Code Size differences (23 improved, 10 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 45569892 (overridden on cmd)
Total bytes of diff: 45567171 (overridden on cmd)
Total bytes of delta: -2721 (-0.01 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         149 : 50063.dasm (6.35% of base)
         128 : 49916.dasm (18.80% of base)
         120 : 74193.dasm (12.53% of base)
         120 : 74206.dasm (12.53% of base)
         113 : 75326.dasm (35.42% of base)
         113 : 75366.dasm (31.83% of base)
         103 : 57447.dasm (29.01% of base)
          97 : 24461.dasm (9.08% of base)
          50 : 53226.dasm (4.96% of base)
          27 : 58085.dasm (0.55% of base)
          26 : 28859.dasm (10.66% of base)
          16 : 160013.dasm (1.33% of base)
          12 : 58047.dasm (0.51% of base)
          10 : 73838.dasm (0.40% of base)
          10 : 46075.dasm (0.53% of base)
           9 : 59524.dasm (1.35% of base)
           9 : 59504.dasm (1.67% of base)
           9 : 59343.dasm (1.17% of base)
           9 : 59408.dasm (1.17% of base)
           7 : 54112.dasm (0.49% of base)

Top file improvements (bytes):
       -1052 : 72956.dasm (-19.69% of base)
        -570 : 53203.dasm (-15.94% of base)
        -442 : 75144.dasm (-23.71% of base)
        -396 : 75131.dasm (-31.30% of base)
        -291 : 50333.dasm (-19.93% of base)
        -255 : 70487.dasm (-39.60% of base)
        -136 : 30173.dasm (-5.46% of base)
         -84 : 55012.dasm (-12.84% of base)
         -80 : 159198.dasm (-7.54% of base)
         -76 : 28525.dasm (-6.59% of base)
         -59 : 28613.dasm (-3.37% of base)
         -56 : 50084.dasm (-1.17% of base)
         -51 : 42621.dasm (-1.58% of base)
         -48 : 51953.dasm (-16.22% of base)
         -48 : 57987.dasm (-1.97% of base)
         -43 : 45026.dasm (-10.97% of base)
         -43 : 43821.dasm (-5.58% of base)
         -39 : 44474.dasm (-4.27% of base)
         -38 : 54004.dasm (-1.40% of base)
         -36 : 50088.dasm (-0.82% of base)

236 total files with Code Size differences (88 improved, 148 regressed), 73 unchanged.

Top method regressions (bytes):
         149 ( 6.35% of base) : 50063.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindQueryOperatorCall(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.String,Microsoft.CodeAnalysis.VisualBasic.BoundMethodGroup,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.Text.TextSpan,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         128 (18.80% of base) : 49916.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ConstructAndValidateConstraints(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
         120 (12.53% of base) : 74193.dasm - SynthesizedWrapperMethod[__Canon][System.__Canon]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         120 (12.53% of base) : 74206.dasm - SynthesizedWrapperMethod[Byte][System.Byte]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         113 (35.42% of base) : 75326.dasm - SynthesizedComMethod:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):this
         113 (31.83% of base) : 75366.dasm - SynthesizedComProperty:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,SynthesizedComMethod,SynthesizedComMethod,int):this
         103 (29.01% of base) : 57447.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedStateMachineMethod:.ctor(Microsoft.CodeAnalysis.VisualBasic.StateMachineTypeSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol):this
          97 ( 9.08% of base) : 24461.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:HasExplicitDelegateConversion(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):bool:this
          50 ( 4.96% of base) : 53226.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int):this
          27 ( 0.55% of base) : 58085.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
          26 (10.66% of base) : 28859.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:IsComCallWithRefOmitted(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[RefKind]):bool
          16 ( 1.33% of base) : 160013.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this
          12 ( 0.51% of base) : 58047.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseFunctionOrSubLambdaHeader(byref,bool):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.LambdaHeaderSyntax:this
          10 ( 0.53% of base) : 46075.dasm - ReferenceManager:SetupReferencesForRetargetingAssembly(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.CSharp.CSharpCompilation,Microsoft.CodeAnalysis.CSharp.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol)
          10 ( 0.40% of base) : 73838.dasm - ReferenceManager:SetupReferencesForRetargetingAssembly(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)
           9 ( 1.17% of base) : 59408.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxRewriter:VisitAggregateClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.AggregateClauseSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:this
           9 ( 1.35% of base) : 59524.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxRewriter:VisitCompilationUnit(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CompilationUnitSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:this
           9 ( 1.67% of base) : 59504.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxRewriter:VisitFieldDeclaration(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.FieldDeclarationSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:this
           9 ( 1.17% of base) : 59343.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxRewriter:VisitSimpleJoinClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleJoinClauseSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode:this
           7 ( 0.49% of base) : 54112.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNamedTypeSymbol:MakeAcyclicInterfaces(Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this

Top method improvements (bytes):
       -1052 (-19.69% of base) : 72956.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
        -570 (-15.94% of base) : 53203.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:Create(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
        -442 (-23.71% of base) : 75144.dasm - InferenceGraph:InferTypeArgumentsFromArgumentDirectly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol,int,int):bool:this
        -396 (-31.30% of base) : 75131.dasm - InferenceGraph:PopulateGraph():this
        -291 (-19.93% of base) : 50333.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:GetDelegateMethodConversionBasedOnArguments(CandidateAnalysisResult,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,byref):int
        -255 (-39.60% of base) : 70487.dasm - Microsoft.CodeAnalysis.VisualBasic.VarianceAmbiguity:HasVarianceAmbiguity(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):bool
        -136 (-5.46% of base) : 30173.dasm - Microsoft.CodeAnalysis.CSharp.CSharpSyntaxTree:BuildPreprocessorStateChangeMap():this
         -84 (-12.84% of base) : 55012.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSubstitution:GetTypeArgumentsFor(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -80 (-7.54% of base) : 159198.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -76 (-6.59% of base) : 28525.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -59 (-3.37% of base) : 28613.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -56 (-1.17% of base) : 50084.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindCollectionRangeVariables(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.CollectionRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase:this
         -51 (-1.58% of base) : 42621.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbolExtensions:InferExtensionMethodTypeArguments(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.Compilation,byref):Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol
         -48 (-16.22% of base) : 51953.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol][]):bool
         -48 (-1.97% of base) : 57987.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseStatementInMethodBodyCore():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.StatementSyntax:this
         -43 (-10.97% of base) : 45026.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol][]):bool
         -43 (-5.58% of base) : 43821.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourcePropertySymbol:ComputeParameters(Microsoft.CodeAnalysis.CSharp.Binder,Microsoft.CodeAnalysis.CSharp.Syntax.BasePropertyDeclarationSyntax,Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -39 (-4.27% of base) : 44474.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:ReportAnyMismatchedConstraints(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.DiagnosticBag)
         -38 (-1.40% of base) : 54004.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNonPropertyAccessorMethodSymbol:EnsureSignature():this
         -36 (-0.82% of base) : 50088.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindInnerJoinClause(Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase,Microsoft.CodeAnalysis.VisualBasic.Syntax.SimpleJoinClauseSyntax,System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase:this

Top method regressions (percentages):
         113 (35.42% of base) : 75326.dasm - SynthesizedComMethod:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):this
         113 (31.83% of base) : 75366.dasm - SynthesizedComProperty:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,SynthesizedComMethod,SynthesizedComMethod,int):this
         103 (29.01% of base) : 57447.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedStateMachineMethod:.ctor(Microsoft.CodeAnalysis.VisualBasic.StateMachineTypeSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol):this
         128 (18.80% of base) : 49916.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ConstructAndValidateConstraints(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
         120 (12.53% of base) : 74193.dasm - SynthesizedWrapperMethod[__Canon][System.__Canon]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         120 (12.53% of base) : 74206.dasm - SynthesizedWrapperMethod[Byte][System.Byte]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
          26 (10.66% of base) : 28859.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:IsComCallWithRefOmitted(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[RefKind]):bool
          97 ( 9.08% of base) : 24461.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:HasExplicitDelegateConversion(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):bool:this
         149 ( 6.35% of base) : 50063.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindQueryOperatorCall(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.String,Microsoft.CodeAnalysis.VisualBasic.BoundMethodGroup,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.Text.TextSpan,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          50 ( 4.96% of base) : 53226.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int):this
           5 ( 4.90% of base) : 122896.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 192539.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 205422.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 207615.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 194923.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 205579.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 192718.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 206915.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 220195.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 203946.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon

Top method improvements (percentages):
        -255 (-39.60% of base) : 70487.dasm - Microsoft.CodeAnalysis.VisualBasic.VarianceAmbiguity:HasVarianceAmbiguity(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):bool
        -396 (-31.30% of base) : 75131.dasm - InferenceGraph:PopulateGraph():this
        -442 (-23.71% of base) : 75144.dasm - InferenceGraph:InferTypeArgumentsFromArgumentDirectly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol,int,int):bool:this
        -291 (-19.93% of base) : 50333.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:GetDelegateMethodConversionBasedOnArguments(CandidateAnalysisResult,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,byref):int
       -1052 (-19.69% of base) : 72956.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
         -48 (-16.22% of base) : 51953.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol][]):bool
        -570 (-15.94% of base) : 53203.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:Create(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
         -84 (-12.84% of base) : 55012.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSubstitution:GetTypeArgumentsFor(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -11 (-11.46% of base) : 41791.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:TypeArgumentsWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -11 (-11.46% of base) : 51515.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:GetDeclaredInterfacesWithDefinitionUseSiteDiagnostics(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -11 (-11.46% of base) : 51552.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:TypeArgumentsWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -43 (-10.97% of base) : 45026.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol][]):bool
         -11 (-9.73% of base) : 51809.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol:ConstraintTypesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -80 (-7.54% of base) : 159198.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -11 (-7.24% of base) : 42073.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol:ConstraintTypesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -11 (-6.92% of base) : 44489.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:AllInterfacesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -76 (-6.59% of base) : 28525.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -22 (-6.43% of base) : 75311.dasm - SynthesizedComMethod:GetAttributes():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.VisualBasicAttributeData, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -11 (-6.32% of base) : 42053.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol:AllEffectiveInterfacesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -33 (-6.27% of base) : 44072.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SubstitutedMethodSymbol:Equals(System.Object):bool:this

236 total methods with Code Size differences (88 improved, 148 regressed), 73 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 113764434 (overridden on cmd)
Total bytes of diff: 113763586 (overridden on cmd)
Total bytes of delta: -848 (-0.00 % of base)
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         132 : 314415.dasm (3.48% of base)
          28 : 314143.dasm (0.36% of base)
          17 : 7986.dasm (0.42% of base)
           8 : 1767.dasm (2.20% of base)
           8 : 13038.dasm (2.53% of base)
           8 : 12839.dasm (2.53% of base)
           6 : 12838.dasm (0.81% of base)
           5 : 261295.dasm (4.90% of base)
           5 : 301238.dasm (4.90% of base)
           5 : 327961.dasm (4.90% of base)
           5 : 13037.dasm (0.88% of base)
           5 : 326014.dasm (4.90% of base)
           5 : 216082.dasm (3.40% of base)
           5 : 291844.dasm (4.90% of base)
           5 : 296786.dasm (4.90% of base)
           5 : 227299.dasm (4.90% of base)
           5 : 58784.dasm (4.90% of base)
           5 : 185350.dasm (4.90% of base)
           5 : 302886.dasm (4.90% of base)
           5 : 304556.dasm (4.90% of base)

Top file improvements (bytes):
        -193 : 318440.dasm (-8.72% of base)
        -193 : 72117.dasm (-8.72% of base)
         -58 : 314302.dasm (-2.06% of base)
         -49 : 314178.dasm (-4.68% of base)
         -49 : 314179.dasm (-4.68% of base)
         -47 : 314299.dasm (-1.58% of base)
         -32 : 314413.dasm (-0.95% of base)
         -32 : 314414.dasm (-0.96% of base)
         -32 : 11559.dasm (-2.32% of base)
         -30 : 72703.dasm (-1.86% of base)
         -28 : 164703.dasm (-3.61% of base)
         -25 : 314197.dasm (-0.44% of base)
         -21 : 72113.dasm (-0.91% of base)
         -21 : 108458.dasm (-2.72% of base)
         -21 : 318438.dasm (-0.91% of base)
         -21 : 100110.dasm (-0.69% of base)
         -16 : 203595.dasm (-0.99% of base)
         -15 : 73060.dasm (-3.25% of base)
         -15 : 100107.dasm (-0.57% of base)
         -15 : 135269.dasm (-1.10% of base)

143 total files with Code Size differences (83 improved, 60 regressed), 60 unchanged.

Top method regressions (bytes):
         132 ( 3.48% of base) : 314415.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameForAssemblyDefinition():this
          28 ( 0.36% of base) : 314143.dasm - System.Reflection.Metadata.Decoding.Tests.SignatureDecoderTests:SimpleSignatureProviderCoverage():this
          17 ( 0.42% of base) : 7986.dasm - Microsoft.CodeAnalysis.Options.GlobalOptionService:GetSerializableOptionValues(System.Collections.Immutable.ImmutableHashSet`1[[Microsoft.CodeAnalysis.Options.IOption, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableHashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):System.Collections.Immutable.ImmutableDictionary`2[[Microsoft.CodeAnalysis.Options.OptionKey, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]:this
           8 ( 2.53% of base) : 12839.dasm - AnonymousTypeSymbolKey:ReadPropertyLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           8 ( 2.20% of base) : 1767.dasm - Roslyn.Utilities.AsyncLazy`1[Byte][System.Byte]:OnAsynchronousRequestCancelled(System.Object):this
           8 ( 2.53% of base) : 13038.dasm - TupleTypeSymbolKey:ReadElementLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           6 ( 0.81% of base) : 12838.dasm - AnonymousTypeSymbolKey:Resolve(SymbolKeyReader,byref):Microsoft.CodeAnalysis.SymbolKeyResolution
           5 ( 4.90% of base) : 261295.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 301238.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 327961.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 326014.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 3.40% of base) : 216082.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 291844.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 296786.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 227299.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 58784.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 185350.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 302886.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 304556.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 178930.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon

Top method improvements (bytes):
        -193 (-8.72% of base) : 318440.dasm - System.Tests.HalfTests:Parse_Span_Valid(System.String,int,int,int,System.IFormatProvider,float)
        -193 (-8.72% of base) : 72117.dasm - System.Tests.HalfTests:Parse_Span_Valid(System.String,int,int,int,System.IFormatProvider,float)
         -58 (-2.06% of base) : 314302.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps_StartOffsets():this
         -49 (-4.68% of base) : 314178.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors2():this
         -49 (-4.68% of base) : 314179.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors3():this
         -47 (-1.58% of base) : 314299.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps():this
         -32 (-2.32% of base) : 11559.dasm - Microsoft.CodeAnalysis.CodeGeneration.INamedTypeSymbolExtensions:ToCodeGenerationSymbol(Microsoft.CodeAnalysis.INamedTypeSymbol):Microsoft.CodeAnalysis.CodeGeneration.CodeGenerationAbstractNamedTypeSymbol
         -32 (-0.95% of base) : 314413.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameWithCultureSet():this
         -32 (-0.96% of base) : 314414.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameWithPublicKey():this
         -30 (-1.86% of base) : 72703.dasm - System.Tests.TimeZoneInfoTests:ConvertTimeBySystemTimeZoneIdTests()
         -28 (-3.61% of base) : 164703.dasm - System.IO.Tests.File_GetSetTimes:SetUptoNanoseconds():this
         -25 (-0.44% of base) : 314197.dasm - System.Reflection.Metadata.Ecma335.Tests.InstructionEncoderTests:Branch():this
         -21 (-2.72% of base) : 108458.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
         -21 (-0.91% of base) : 72113.dasm - System.Tests.HalfTests:Parse(System.String,int,System.IFormatProvider,float)
         -21 (-0.91% of base) : 318438.dasm - System.Tests.HalfTests:Parse(System.String,int,System.IFormatProvider,float)
         -21 (-0.69% of base) : 100110.dasm - System.Text.Json.Serialization.Tests.NullableTests:EnumerableWithNullableValue()
         -16 (-0.99% of base) : 203595.dasm - System.Security.Cryptography.X509Certificates.Tests.CertTests:X509Cert2Test()
         -15 (-1.10% of base) : 135269.dasm - Microsoft.VisualBasic.Tests.DateAndTimeTests:Fields():this
         -15 (-3.25% of base) : 73060.dasm - System.Tests.TypeTests:TypeHandle(System.Type,System.Type):this
         -15 (-0.57% of base) : 100107.dasm - System.Text.Json.Serialization.Tests.NullableTests:DictionaryWithNullableValue()

Top method regressions (percentages):
           5 ( 4.90% of base) : 261295.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 301238.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 327961.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 326014.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 291844.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 296786.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 227299.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 58784.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 185350.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 302886.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 304556.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 178930.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 284847.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 4.90% of base) : 285188.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
         132 ( 3.48% of base) : 314415.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameForAssemblyDefinition():this
           5 ( 3.40% of base) : 216082.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           5 ( 3.40% of base) : 220367.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           8 ( 2.53% of base) : 12839.dasm - AnonymousTypeSymbolKey:ReadPropertyLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           8 ( 2.53% of base) : 13038.dasm - TupleTypeSymbolKey:ReadElementLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           8 ( 2.20% of base) : 1767.dasm - Roslyn.Utilities.AsyncLazy`1[Byte][System.Byte]:OnAsynchronousRequestCancelled(System.Object):this

Top method improvements (percentages):
        -193 (-8.72% of base) : 318440.dasm - System.Tests.HalfTests:Parse_Span_Valid(System.String,int,int,int,System.IFormatProvider,float)
        -193 (-8.72% of base) : 72117.dasm - System.Tests.HalfTests:Parse_Span_Valid(System.String,int,int,int,System.IFormatProvider,float)
         -49 (-4.68% of base) : 314178.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors2():this
         -49 (-4.68% of base) : 314179.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors3():this
          -7 (-3.89% of base) : 212356.dasm - System.Xml.XPath.XDocument.Tests.XDocument.NavigatorComparer:get_ValueAsDateTime():System.DateTime:this
         -28 (-3.61% of base) : 164703.dasm - System.IO.Tests.File_GetSetTimes:SetUptoNanoseconds():this
         -15 (-3.25% of base) : 73060.dasm - System.Tests.TypeTests:TypeHandle(System.Type,System.Type):this
         -21 (-2.72% of base) : 108458.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
          -8 (-2.33% of base) : 6251.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Vector`1,Nullable`1],System.Numerics.Vector`1[Single],System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-2.33% of base) : 6257.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Vector`1,Nullable`1],System.Numerics.Vector`1[Single],System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
         -32 (-2.32% of base) : 11559.dasm - Microsoft.CodeAnalysis.CodeGeneration.INamedTypeSymbolExtensions:ToCodeGenerationSymbol(Microsoft.CodeAnalysis.INamedTypeSymbol):Microsoft.CodeAnalysis.CodeGeneration.CodeGenerationAbstractNamedTypeSymbol
          -7 (-2.18% of base) : 71330.dasm - System.Tests.DateTimeTests:FromFileTimeUtc_Invoke_ReturnsExpected(long,System.DateTime):this
         -13 (-2.15% of base) : 6667.dasm - Microsoft.CodeAnalysis.Shared.Utilities.PathMetadataUtilities:TryBuildNamespaceFromFolders(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.LanguageServices.ISyntaxFacts,System.String):System.String
         -58 (-2.06% of base) : 314302.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps_StartOffsets():this
          -7 (-1.99% of base) : 71323.dasm - System.Tests.DateTimeTests:FromFileTime_Invoke_ReturnsExpected(long,System.DateTime):this
         -30 (-1.86% of base) : 72703.dasm - System.Tests.TimeZoneInfoTests:ConvertTimeBySystemTimeZoneIdTests()
         -47 (-1.58% of base) : 314299.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps():this
          -9 (-1.49% of base) : 100720.dasm - System.Text.Json.Serialization.Tests.ValueTests:TimeSpan_Read_KnownDifferences()
          -5 (-1.34% of base) : 141848.dasm - NuGet.Protocol.Plugins.MessageDispatcher:HandleInboundRequest(NuGet.Protocol.Plugins.IConnection,NuGet.Protocol.Plugins.Message):this
          -8 (-1.33% of base) : 9484.dasm - Microsoft.CodeAnalysis.FindSymbols.FindReferenceCache:GetIdentifierOrGlobalNamespaceTokensWithText(Microsoft.CodeAnalysis.LanguageServices.ISyntaxFactsService,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.Text.SourceText,System.String,System.Threading.CancellationToken):System.Collections.Immutable.ImmutableArray`1[SyntaxToken]

143 total methods with Code Size differences (83 improved, 60 regressed), 60 unchanged.

```

</details>

--------------------------------------------------------------------------------

