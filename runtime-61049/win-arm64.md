## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7633828 (overridden on cmd)
Total bytes of diff: 7633680 (overridden on cmd)
Total bytes of delta: -148 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          20 : 16025.dasm (0.88% of base)
           8 : 16031.dasm (1.30% of base)
           8 : 11919.dasm (0.36% of base)
           4 : 8801.dasm (0.21% of base)
           4 : 22059.dasm (0.25% of base)
           4 : 8777.dasm (0.25% of base)
           4 : 22858.dasm (0.18% of base)
           4 : 8791.dasm (0.20% of base)

Top file improvements (bytes):
         -36 : 17223.dasm (-1.82% of base)
         -16 : 17058.dasm (-1.25% of base)
         -16 : 17021.dasm (-0.22% of base)
         -16 : 16666.dasm (-0.67% of base)
         -16 : 16736.dasm (-5.56% of base)
         -12 : 11982.dasm (-0.55% of base)
         -12 : 14148.dasm (-0.46% of base)
          -8 : 16934.dasm (-0.45% of base)
          -8 : 15104.dasm (-1.77% of base)
          -8 : 16129.dasm (-1.63% of base)
          -8 : 4667.dasm (-4.88% of base)
          -8 : 17824.dasm (-0.41% of base)
          -8 : 16104.dasm (-1.80% of base)
          -4 : 10829.dasm (-0.52% of base)
          -4 : 6893.dasm (-1.20% of base)
          -4 : 2026.dasm (-0.05% of base)
          -4 : 17209.dasm (-0.34% of base)
          -4 : 16415.dasm (-0.37% of base)
          -4 : 9960.dasm (-0.56% of base)
          -4 : 17242.dasm (-0.76% of base)

29 total files with Code Size differences (21 improved, 8 regressed), 23 unchanged.

Top method regressions (bytes):
          20 ( 0.88% of base) : 16025.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Immutable.ImmutableHashSet`1+Builder[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref)
           8 ( 0.36% of base) : 11919.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItem:this
           8 ( 1.30% of base) : 16031.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CheckMethodMemberForExtensionSyntax(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode):bool
           4 ( 0.20% of base) : 8791.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent:this
           4 ( 0.21% of base) : 8801.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CampaignSummaryViewModelFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CampaignSummaryViewModel:this
           4 ( 0.25% of base) : 8777.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_IndexViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.IndexViewModel:this
           4 ( 0.18% of base) : 22858.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.Location:this
           4 ( 0.25% of base) : 22059.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LoginViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.LoginViewModel:this

Top method improvements (bytes):
         -36 (-1.82% of base) : 17223.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-1.25% of base) : 17058.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindBlockParts(Microsoft.CodeAnalysis.CSharp.Syntax.BlockSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
         -16 (-5.56% of base) : 16736.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetAllUnaliasedModules(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.ModuleSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -16 (-0.22% of base) : 17021.dasm - Microsoft.CodeAnalysis.CSharp.Imports:FromSyntax(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.InContainerBinder,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool):Microsoft.CodeAnalysis.CSharp.Imports
         -16 (-0.67% of base) : 16666.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:MakeDeclaredBases(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Tuple`2[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
         -12 (-0.55% of base) : 11982.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
         -12 (-0.46% of base) : 14148.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-1.63% of base) : 16129.dasm - AssemblyDataForAssemblyBeingBuilt[__Canon,__Canon][System.__Canon,System.__Canon]:.ctor(Microsoft.CodeAnalysis.AssemblyIdentity,System.Collections.Immutable.ImmutableArray`1[__Canon],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -8 (-0.41% of base) : 17824.dasm - Microsoft.Cci.MetadataWriter:SerializeTypeReference(System.Reflection.Metadata.Ecma335.SignatureTypeEncoder,Microsoft.Cci.ITypeReference):this
          -8 (-0.45% of base) : 16934.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ReportNameCollisionDiagnosticsForAddedModules(Microsoft.CodeAnalysis.CSharp.Symbols.NamespaceSymbol,Microsoft.CodeAnalysis.DiagnosticBag):this
          -8 (-1.80% of base) : 16104.dasm - Microsoft.CodeAnalysis.PEAssembly:.ctor(Microsoft.CodeAnalysis.AssemblyMetadata,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -8 (-1.77% of base) : 15104.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -8 (-4.88% of base) : 4667.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
          -4 (-0.64% of base) : 18160.dasm - Microsoft.Cci.MetadataWriter:AddCustomAttributesToTable(System.Collections.Generic.IEnumerable`1[__Canon],System.Func`2[__Canon,EntityHandle]):this
          -4 (-0.34% of base) : 17209.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -4 (-0.76% of base) : 17242.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -4 (-0.37% of base) : 16415.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamespaceSymbol:LazyInitializeTypes(System.Collections.Generic.IEnumerable`1[[System.Linq.IGrouping`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.Metadata.TypeDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], System.Linq, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
          -4 (-0.52% of base) : 10829.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
          -4 (-1.20% of base) : 6893.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -4 (-0.56% of base) : 9960.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this

Top method regressions (percentages):
           8 ( 1.30% of base) : 16031.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CheckMethodMemberForExtensionSyntax(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode):bool
          20 ( 0.88% of base) : 16025.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Immutable.ImmutableHashSet`1+Builder[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref)
           8 ( 0.36% of base) : 11919.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItem:this
           4 ( 0.25% of base) : 8777.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_IndexViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.IndexViewModel:this
           4 ( 0.25% of base) : 22059.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LoginViewModelFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.LoginViewModel:this
           4 ( 0.21% of base) : 8801.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_CampaignSummaryViewModelFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.CampaignSummaryViewModel:this
           4 ( 0.20% of base) : 8791.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent:this
           4 ( 0.18% of base) : 22858.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.Location:this

Top method improvements (percentages):
         -16 (-5.56% of base) : 16736.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetAllUnaliasedModules(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.ModuleSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -8 (-4.88% of base) : 4667.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
         -36 (-1.82% of base) : 17223.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -8 (-1.80% of base) : 16104.dasm - Microsoft.CodeAnalysis.PEAssembly:.ctor(Microsoft.CodeAnalysis.AssemblyMetadata,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -8 (-1.77% of base) : 15104.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -8 (-1.63% of base) : 16129.dasm - AssemblyDataForAssemblyBeingBuilt[__Canon,__Canon][System.__Canon,System.__Canon]:.ctor(Microsoft.CodeAnalysis.AssemblyIdentity,System.Collections.Immutable.ImmutableArray`1[__Canon],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -16 (-1.25% of base) : 17058.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindBlockParts(Microsoft.CodeAnalysis.CSharp.Syntax.BlockSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
          -4 (-1.20% of base) : 6893.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -4 (-0.76% of base) : 17242.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-0.67% of base) : 16666.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:MakeDeclaredBases(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Tuple`2[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]:this
          -4 (-0.64% of base) : 18160.dasm - Microsoft.Cci.MetadataWriter:AddCustomAttributesToTable(System.Collections.Generic.IEnumerable`1[__Canon],System.Func`2[__Canon,EntityHandle]):this
          -4 (-0.56% of base) : 9960.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
         -12 (-0.55% of base) : 11982.dasm - DynamicClass:WriteActiveOrUpcomingEventToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -4 (-0.52% of base) : 10829.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
         -12 (-0.46% of base) : 14148.dasm - DynamicClass:WriteMyEventsListerItemToJson(System.Runtime.Serialization.XmlWriterDelegator,System.Object,System.Runtime.Serialization.Json.XmlObjectSerializerWriteContextComplexJson,System.Runtime.Serialization.ClassDataContract,System.Xml.XmlDictionaryString[])
          -8 (-0.45% of base) : 16934.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ReportNameCollisionDiagnosticsForAddedModules(Microsoft.CodeAnalysis.CSharp.Symbols.NamespaceSymbol,Microsoft.CodeAnalysis.DiagnosticBag):this
          -8 (-0.41% of base) : 17824.dasm - Microsoft.Cci.MetadataWriter:SerializeTypeReference(System.Reflection.Metadata.Ecma335.SignatureTypeEncoder,Microsoft.Cci.ITypeReference):this
          -4 (-0.37% of base) : 16415.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PENamespaceSymbol:LazyInitializeTypes(System.Collections.Generic.IEnumerable`1[[System.Linq.IGrouping`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.Metadata.TypeDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], System.Linq, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
          -4 (-0.34% of base) : 17209.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-0.22% of base) : 17021.dasm - Microsoft.CodeAnalysis.CSharp.Imports:FromSyntax(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.InContainerBinder,Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool):Microsoft.CodeAnalysis.CSharp.Imports

29 total methods with Code Size differences (21 improved, 8 regressed), 23 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 165279168 (overridden on cmd)
Total bytes of diff: 165278852 (overridden on cmd)
Total bytes of delta: -316 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 210729.dasm (0.58% of base)

Top file improvements (bytes):
        -268 : 89503.dasm (-93.06% of base)
          -8 : 83792.dasm (-1.21% of base)
          -4 : 168084.dasm (-0.36% of base)
          -4 : 167970.dasm (-0.35% of base)
          -4 : 209664.dasm (-0.25% of base)
          -4 : 167951.dasm (-0.30% of base)
          -4 : 167818.dasm (-0.37% of base)
          -4 : 169361.dasm (-0.36% of base)
          -4 : 169347.dasm (-0.38% of base)
          -4 : 169359.dasm (-0.31% of base)
          -4 : 169355.dasm (-0.36% of base)
          -4 : 168046.dasm (-0.31% of base)
          -4 : 84498.dasm (-0.56% of base)
          -4 : 169354.dasm (-0.31% of base)

15 total files with Code Size differences (14 improved, 1 regressed), 2 unchanged.

Top method regressions (bytes):
           8 ( 0.58% of base) : 210729.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this

Top method improvements (bytes):
        -268 (-93.06% of base) : 89503.dasm - <Module>:Main():int
          -8 (-1.21% of base) : 83792.dasm - X:F():int
          -4 (-0.25% of base) : 209664.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          -4 (-0.37% of base) : 167818.dasm - NullableTest17:Run()
          -4 (-0.38% of base) : 169347.dasm - NullableTest17:Run()
          -4 (-0.30% of base) : 167951.dasm - NullableTest24:Run()
          -4 (-0.31% of base) : 169354.dasm - NullableTest24:Run()
          -4 (-0.35% of base) : 167970.dasm - NullableTest25:Run()
          -4 (-0.36% of base) : 169355.dasm - NullableTest25:Run()
          -4 (-0.31% of base) : 169359.dasm - NullableTest29:Run()
          -4 (-0.31% of base) : 168046.dasm - NullableTest29:Run()
          -4 (-0.36% of base) : 168084.dasm - NullableTest31:Run()
          -4 (-0.36% of base) : 169361.dasm - NullableTest31:Run()
          -4 (-0.56% of base) : 84498.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this

Top method regressions (percentages):
           8 ( 0.58% of base) : 210729.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this

Top method improvements (percentages):
        -268 (-93.06% of base) : 89503.dasm - <Module>:Main():int
          -8 (-1.21% of base) : 83792.dasm - X:F():int
          -4 (-0.56% of base) : 84498.dasm - System.Reflection.PortableExecutable.PEReader:TryOpenAssociatedPortablePdb(System.String,System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.IO.Stream, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref,byref):bool:this
          -4 (-0.38% of base) : 169347.dasm - NullableTest17:Run()
          -4 (-0.37% of base) : 167818.dasm - NullableTest17:Run()
          -4 (-0.36% of base) : 169361.dasm - NullableTest31:Run()
          -4 (-0.36% of base) : 169355.dasm - NullableTest25:Run()
          -4 (-0.36% of base) : 168084.dasm - NullableTest31:Run()
          -4 (-0.35% of base) : 167970.dasm - NullableTest25:Run()
          -4 (-0.31% of base) : 169359.dasm - NullableTest29:Run()
          -4 (-0.31% of base) : 169354.dasm - NullableTest24:Run()
          -4 (-0.31% of base) : 168046.dasm - NullableTest29:Run()
          -4 (-0.30% of base) : 167951.dasm - NullableTest24:Run()
          -4 (-0.25% of base) : 209664.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this

15 total methods with Code Size differences (14 improved, 1 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51809972 (overridden on cmd)
Total bytes of diff: 51809796 (overridden on cmd)
Total bytes of delta: -176 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 168835.dasm (1.82% of base)
           8 : 168833.dasm (1.72% of base)
           8 : 168836.dasm (2.94% of base)
           8 : 168834.dasm (2.94% of base)
           4 : 13959.dasm (1.89% of base)
           4 : 29036.dasm (0.20% of base)
           4 : 107824.dasm (2.08% of base)
           4 : 150632.dasm (0.33% of base)

Top file improvements (bytes):
        -104 : 185958.dasm (-11.21% of base)
         -28 : 29589.dasm (-0.71% of base)
         -12 : 4336.dasm (-1.37% of base)
          -8 : 29473.dasm (-0.88% of base)
          -8 : 169764.dasm (-1.14% of base)
          -8 : 169273.dasm (-2.50% of base)
          -4 : 184589.dasm (-0.23% of base)
          -4 : 167992.dasm (-0.74% of base)
          -4 : 184654.dasm (-0.68% of base)
          -4 : 167986.dasm (-0.74% of base)
          -4 : 184655.dasm (-0.40% of base)
          -4 : 212048.dasm (-0.18% of base)
          -4 : 167981.dasm (-0.49% of base)
          -4 : 184588.dasm (-0.34% of base)
          -4 : 103608.dasm (-1.00% of base)
          -4 : 200730.dasm (-0.77% of base)
          -4 : 4366.dasm (-0.46% of base)
          -4 : 167987.dasm (-0.76% of base)
          -4 : 185814.dasm (-0.21% of base)
          -4 : 199674.dasm (-0.49% of base)

28 total files with Code Size differences (20 improved, 8 regressed), 7 unchanged.

Top method regressions (bytes):
           8 ( 1.72% of base) : 168833.dasm - System.Drawing.Font:get_SizeInPoints():float:this
           8 ( 2.94% of base) : 168834.dasm - System.Drawing.Font:GetHeight():float:this
           8 ( 1.82% of base) : 168835.dasm - System.Drawing.Font:ToHfont():long:this
           8 ( 2.94% of base) : 168836.dasm - System.Drawing.Font:ToLogFont(System.Object):this
           4 ( 0.20% of base) : 29036.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlPIData(int):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
           4 ( 1.89% of base) : 13959.dasm - SkippedTriviaBuilder:AddTrivia(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode):this
           4 ( 0.33% of base) : 150632.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.Net.IPAddress,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
           4 ( 2.08% of base) : 107824.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon

Top method improvements (bytes):
        -104 (-11.21% of base) : 185958.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -28 (-0.71% of base) : 29589.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
         -12 (-1.37% of base) : 4336.dasm - Choice@1280-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[Microsoft.FSharp.Core.FSharpOption`1[System.__Canon]]):Microsoft.FSharp.Control.AsyncReturn:this
          -8 (-0.88% of base) : 29473.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:TryReinterpretAsArraySpecifier(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArgumentListSyntax,byref):bool:this
          -8 (-1.14% of base) : 169764.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -8 (-2.50% of base) : 169273.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
          -4 (-0.21% of base) : 185814.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          -4 (-0.46% of base) : 4366.dasm - Parallel@1178-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[System.__Canon[]]):Microsoft.FSharp.Control.AsyncReturn:this
          -4 (-0.18% of base) : 212048.dasm - System.Configuration.BaseConfigurationRecord:ScanLocationSection(System.Configuration.XmlUtil):this
          -4 (-0.74% of base) : 167992.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream):this
          -4 (-0.76% of base) : 167987.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,int,System.String):this
          -4 (-0.74% of base) : 167986.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,System.Drawing.RectangleF,int,int,System.String):this
          -4 (-0.49% of base) : 167981.dasm - System.Drawing.Imaging.Metafile:GetMetafileHeader(System.IO.Stream):System.Drawing.Imaging.MetafileHeader
          -4 (-1.00% of base) : 103608.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -4 (-0.49% of base) : 199674.dasm - System.Reflection.Metadata.Ecma335.NamespaceCache:PopulateTableWithTypeDefinitions(System.Collections.Generic.Dictionary`2[System.Reflection.Metadata.NamespaceDefinitionHandle, System.Reflection.Metadata.Ecma335.NamespaceCache+NamespaceDataBuilder]):this
          -4 (-0.77% of base) : 200730.dasm - System.Reflection.Metadata.MetadataReader:GetWellKnownTypeDefinitionTreatment(System.Reflection.Metadata.TypeDefinitionHandle):ubyte:this
          -4 (-0.68% of base) : 184654.dasm - System.Runtime.Caching.ExpiresBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -4 (-0.40% of base) : 184655.dasm - System.Runtime.Caching.ExpiresBucket:Reduce():this
          -4 (-0.34% of base) : 184588.dasm - System.Runtime.Caching.UsageBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -4 (-0.23% of base) : 184589.dasm - System.Runtime.Caching.UsageBucket:Reduce():this

Top method regressions (percentages):
           8 ( 2.94% of base) : 168834.dasm - System.Drawing.Font:GetHeight():float:this
           8 ( 2.94% of base) : 168836.dasm - System.Drawing.Font:ToLogFont(System.Object):this
           4 ( 2.08% of base) : 107824.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 1.89% of base) : 13959.dasm - SkippedTriviaBuilder:AddTrivia(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.VisualBasicSyntaxNode):this
           8 ( 1.82% of base) : 168835.dasm - System.Drawing.Font:ToHfont():long:this
           8 ( 1.72% of base) : 168833.dasm - System.Drawing.Font:get_SizeInPoints():float:this
           4 ( 0.33% of base) : 150632.dasm - System.Net.Dns:GetHostEntryOrAddressesCore(System.Net.IPAddress,bool,int,Microsoft.Extensions.Internal.ValueStopwatch):System.Object
           4 ( 0.20% of base) : 29036.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlPIData(int):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this

Top method improvements (percentages):
        -104 (-11.21% of base) : 185958.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
          -8 (-2.50% of base) : 169273.dasm - System.Drawing.Image:LoadGdipImageFromStream(System.Drawing.Internal.GPStream,bool):long
         -12 (-1.37% of base) : 4336.dasm - Choice@1280-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[Microsoft.FSharp.Core.FSharpOption`1[System.__Canon]]):Microsoft.FSharp.Control.AsyncReturn:this
          -8 (-1.14% of base) : 169764.dasm - System.Drawing.Bitmap:.ctor(System.IO.Stream,bool):this
          -4 (-1.00% of base) : 103608.dasm - System.Reflection.Emit.ILGenerator:BeginFinallyBlock():this
          -8 (-0.88% of base) : 29473.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:TryReinterpretAsArraySpecifier(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArgumentListSyntax,byref):bool:this
          -4 (-0.77% of base) : 200730.dasm - System.Reflection.Metadata.MetadataReader:GetWellKnownTypeDefinitionTreatment(System.Reflection.Metadata.TypeDefinitionHandle):ubyte:this
          -4 (-0.76% of base) : 167987.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,int,System.String):this
          -4 (-0.74% of base) : 167992.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream):this
          -4 (-0.74% of base) : 167986.dasm - System.Drawing.Imaging.Metafile:.ctor(System.IO.Stream,long,System.Drawing.RectangleF,int,int,System.String):this
         -28 (-0.71% of base) : 29589.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
          -4 (-0.68% of base) : 184654.dasm - System.Runtime.Caching.ExpiresBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -4 (-0.49% of base) : 167981.dasm - System.Drawing.Imaging.Metafile:GetMetafileHeader(System.IO.Stream):System.Drawing.Imaging.MetafileHeader
          -4 (-0.49% of base) : 199674.dasm - System.Reflection.Metadata.Ecma335.NamespaceCache:PopulateTableWithTypeDefinitions(System.Collections.Generic.Dictionary`2[System.Reflection.Metadata.NamespaceDefinitionHandle, System.Reflection.Metadata.Ecma335.NamespaceCache+NamespaceDataBuilder]):this
          -4 (-0.46% of base) : 4366.dasm - Parallel@1178-1:Invoke(Microsoft.FSharp.Control.AsyncActivation`1[System.__Canon[]]):Microsoft.FSharp.Control.AsyncReturn:this
          -4 (-0.40% of base) : 184655.dasm - System.Runtime.Caching.ExpiresBucket:Reduce():this
          -4 (-0.34% of base) : 184588.dasm - System.Runtime.Caching.UsageBucket:AddCacheEntry(System.Runtime.Caching.MemoryCacheEntry):this
          -4 (-0.23% of base) : 184589.dasm - System.Runtime.Caching.UsageBucket:Reduce():this
          -4 (-0.21% of base) : 185814.dasm - Internal.TypeSystem.MetadataFieldLayoutAlgorithm:ComputeExplicitFieldLayout(Internal.TypeSystem.MetadataType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          -4 (-0.18% of base) : 212048.dasm - System.Configuration.BaseConfigurationRecord:ScanLocationSection(System.Configuration.XmlUtil):this

28 total methods with Code Size differences (20 improved, 8 regressed), 7 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51524128 (overridden on cmd)
Total bytes of diff: 51520464 (overridden on cmd)
Total bytes of delta: -3664 (-0.01 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         152 : 72422.dasm (14.13% of base)
         152 : 72435.dasm (14.13% of base)
         148 : 48140.dasm (18.88% of base)
         136 : 73595.dasm (33.33% of base)
         136 : 73555.dasm (35.42% of base)
         124 : 55676.dasm (30.39% of base)
         116 : 48287.dasm (5.16% of base)
          60 : 22653.dasm (5.15% of base)
          48 : 51457.dasm (4.46% of base)
          36 : 27063.dasm (9.38% of base)
          24 : 56275.dasm (1.01% of base)
           8 : 143102.dasm (0.58% of base)
           8 : 26482.dasm (0.49% of base)
           8 : 75438.dasm (0.18% of base)
           4 : 113136.dasm (0.75% of base)
           4 : 196326.dasm (3.23% of base)
           4 : 200089.dasm (3.23% of base)
           4 : 224392.dasm (4.76% of base)
           4 : 225144.dasm (0.85% of base)
           4 : 232049.dasm (0.10% of base)

Top file improvements (bytes):
        -736 : 71185.dasm (-16.33% of base)
        -476 : 51434.dasm (-14.97% of base)
        -464 : 73373.dasm (-23.63% of base)
        -392 : 73360.dasm (-28.49% of base)
        -372 : 228829.dasm (-29.52% of base)
        -364 : 48557.dasm (-21.67% of base)
        -252 : 68716.dasm (-37.28% of base)
        -104 : 53241.dasm (-12.38% of base)
         -88 : 142283.dasm (-7.21% of base)
         -72 : 52341.dasm (-5.28% of base)
         -72 : 43234.dasm (-13.64% of base)
         -68 : 50175.dasm (-16.67% of base)
         -44 : 26817.dasm (-2.36% of base)
         -44 : 42280.dasm (-6.92% of base)
         -36 : 28376.dasm (-1.35% of base)
         -36 : 40829.dasm (-1.25% of base)
         -28 : 48308.dasm (-0.74% of base)
         -28 : 52514.dasm (-2.33% of base)
         -24 : 52235.dasm (-0.94% of base)
         -24 : 56313.dasm (-0.41% of base)

245 total files with Code Size differences (206 improved, 39 regressed), 72 unchanged.

Top method regressions (bytes):
         152 (14.13% of base) : 72422.dasm - SynthesizedWrapperMethod[__Canon][System.__Canon]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         152 (14.13% of base) : 72435.dasm - SynthesizedWrapperMethod[Byte][System.Byte]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         148 (18.88% of base) : 48140.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ConstructAndValidateConstraints(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
         136 (35.42% of base) : 73555.dasm - SynthesizedComMethod:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):this
         136 (33.33% of base) : 73595.dasm - SynthesizedComProperty:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,SynthesizedComMethod,SynthesizedComMethod,int):this
         124 (30.39% of base) : 55676.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedStateMachineMethod:.ctor(Microsoft.CodeAnalysis.VisualBasic.StateMachineTypeSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol):this
         116 ( 5.16% of base) : 48287.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindQueryOperatorCall(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.String,Microsoft.CodeAnalysis.VisualBasic.BoundMethodGroup,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.Text.TextSpan,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          60 ( 5.15% of base) : 22653.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:HasExplicitDelegateConversion(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):bool:this
          48 ( 4.46% of base) : 51457.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int):this
          36 ( 9.38% of base) : 27063.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:IsComCallWithRefOmitted(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[RefKind]):bool
          24 ( 1.01% of base) : 56275.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseFunctionOrSubLambdaHeader(byref,bool):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.LambdaHeaderSyntax:this
           8 ( 0.58% of base) : 143102.dasm - EcmaObjectLookupHashtable:CreateValueFromKey(System.Reflection.Metadata.EntityHandle):IEntityHandleObject:this
           8 ( 0.18% of base) : 75438.dasm - Microsoft.CodeAnalysis.CommonCompiler:RunCore(System.IO.TextWriter,Microsoft.CodeAnalysis.ErrorLogger,System.Threading.CancellationToken):int:this
           8 ( 0.49% of base) : 26482.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:AddNonTypeMemberNames(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],byref)
           4 ( 4.76% of base) : 224392.dasm - <>c__5`1[__Canon][System.__Canon]:<CallOnEmptyStack>b__5_1(System.Threading.Tasks.Task`1[__Canon]):System.__Canon:this
           4 ( 0.10% of base) : 232049.dasm - ILCompiler.Program:Run(System.String[]):int:this
           4 ( 0.14% of base) : 56199.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParsePropertyDefinition(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.AttributeListSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PropertyStatementSyntax:this
           4 ( 0.15% of base) : 56608.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlPIData(int):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
           4 ( 0.37% of base) : 56527.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:TryScanXmlDocComment(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxListBuilder):bool:this
           4 ( 1.15% of base) : 146871.dasm - Microsoft.Extensions.DependencyInjection.ServiceLookup.StackGuard:RunOnEmptyStackCore(System.Func`2[__Canon,__Canon],System.Object):System.__Canon:this

Top method improvements (bytes):
        -736 (-16.33% of base) : 71185.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
        -476 (-14.97% of base) : 51434.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:Create(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
        -464 (-23.63% of base) : 73373.dasm - InferenceGraph:InferTypeArgumentsFromArgumentDirectly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol,int,int):bool:this
        -392 (-28.49% of base) : 73360.dasm - InferenceGraph:PopulateGraph():this
        -372 (-29.52% of base) : 228829.dasm - ILCompiler.ReadyToRunCompilationModuleGroupBase:ComputeInstantiationVersionsWithCode(Internal.TypeSystem.Instantiation,Internal.TypeSystem.TypeSystemEntity):bool:this
        -364 (-21.67% of base) : 48557.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:GetDelegateMethodConversionBasedOnArguments(CandidateAnalysisResult,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,byref):int
        -252 (-37.28% of base) : 68716.dasm - Microsoft.CodeAnalysis.VisualBasic.VarianceAmbiguity:HasVarianceAmbiguity(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):bool
        -104 (-12.38% of base) : 53241.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSubstitution:GetTypeArgumentsFor(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -88 (-7.21% of base) : 142283.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -72 (-13.64% of base) : 43234.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol][]):bool
         -72 (-5.28% of base) : 52341.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNamedTypeSymbol:MakeAcyclicInterfaces(Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -68 (-16.67% of base) : 50175.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol][]):bool
         -44 (-2.36% of base) : 26817.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:Scan(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.DataFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -44 (-6.92% of base) : 42280.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SubstitutedMethodSymbol:Equals(System.Object):bool:this
         -36 (-1.35% of base) : 28376.dasm - Microsoft.CodeAnalysis.CSharp.CSharpSyntaxTree:BuildPreprocessorStateChangeMap():this
         -36 (-1.25% of base) : 40829.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbolExtensions:InferExtensionMethodTypeArguments(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.Compilation,byref):Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol
         -28 (-0.74% of base) : 48308.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindCollectionRangeVariables(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.CollectionRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundQueryClauseBase:this
         -28 (-2.33% of base) : 52514.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
         -24 (-0.94% of base) : 52235.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNonPropertyAccessorMethodSymbol:EnsureSignature():this
         -24 (-0.41% of base) : 56313.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseIfExpression():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this

Top method regressions (percentages):
         136 (35.42% of base) : 73555.dasm - SynthesizedComMethod:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):this
         136 (33.33% of base) : 73595.dasm - SynthesizedComProperty:.ctor(SynthesizedComInterface,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol,SynthesizedComMethod,SynthesizedComMethod,int):this
         124 (30.39% of base) : 55676.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedStateMachineMethod:.ctor(Microsoft.CodeAnalysis.VisualBasic.StateMachineTypeSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.PropertySymbol):this
         148 (18.88% of base) : 48140.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ConstructAndValidateConstraints(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:this
         152 (14.13% of base) : 72422.dasm - SynthesizedWrapperMethod[__Canon][System.__Canon]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
         152 (14.13% of base) : 72435.dasm - SynthesizedWrapperMethod[Byte][System.Byte]:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):this
          36 ( 9.38% of base) : 27063.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:IsComCallWithRefOmitted(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[RefKind]):bool
         116 ( 5.16% of base) : 48287.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindQueryOperatorCall(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.String,Microsoft.CodeAnalysis.VisualBasic.BoundMethodGroup,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.Text.TextSpan,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          60 ( 5.15% of base) : 22653.dasm - Microsoft.CodeAnalysis.CSharp.ConversionsBase:HasExplicitDelegateConversion(Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,byref):bool:this
           4 ( 4.76% of base) : 224392.dasm - <>c__5`1[__Canon][System.__Canon]:<CallOnEmptyStack>b__5_1(System.Threading.Tasks.Task`1[__Canon]):System.__Canon:this
          48 ( 4.46% of base) : 51457.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[[System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int):this
           4 ( 3.23% of base) : 196326.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 200089.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 181387.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 194579.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 198888.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 113122.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 181565.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 199363.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 216309.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon

Top method improvements (percentages):
        -252 (-37.28% of base) : 68716.dasm - Microsoft.CodeAnalysis.VisualBasic.VarianceAmbiguity:HasVarianceAmbiguity(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):bool
        -372 (-29.52% of base) : 228829.dasm - ILCompiler.ReadyToRunCompilationModuleGroupBase:ComputeInstantiationVersionsWithCode(Internal.TypeSystem.Instantiation,Internal.TypeSystem.TypeSystemEntity):bool:this
        -392 (-28.49% of base) : 73360.dasm - InferenceGraph:PopulateGraph():this
        -464 (-23.63% of base) : 73373.dasm - InferenceGraph:InferTypeArgumentsFromArgumentDirectly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol,int,int):bool:this
        -364 (-21.67% of base) : 48557.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:GetDelegateMethodConversionBasedOnArguments(CandidateAnalysisResult,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,byref):int
         -68 (-16.67% of base) : 50175.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol][]):bool
        -736 (-16.33% of base) : 71185.dasm - AnonymousDelegateTemplateSymbol:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeManager,Microsoft.CodeAnalysis.VisualBasic.Symbols.AnonymousTypeDescriptor):this
        -476 (-14.97% of base) : 51434.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ReducedExtensionMethodSymbol:Create(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
         -72 (-13.64% of base) : 43234.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.MemberRefMetadataDecoder:MethodSymbolMatchesParamInfo(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.ParamInfo`1[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol][]):bool
        -104 (-12.38% of base) : 53241.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSubstitution:GetTypeArgumentsFor(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -8 (-11.11% of base) : 50041.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol:GetConstraints(Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterConstraint]):this
         -12 (-8.57% of base) : 39995.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol:TypeArgumentsWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -12 (-8.57% of base) : 49737.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:GetDeclaredInterfacesWithDefinitionUseSiteDiagnostics(Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -12 (-8.57% of base) : 49774.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol:TypeArgumentsWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -12 (-7.50% of base) : 50031.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol:ConstraintTypesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -88 (-7.21% of base) : 142283.dasm - Internal.TypeSystem.ConstructedTypeRewritingHelpers:ReplaceTypesInConstructionOfMethod(Internal.TypeSystem.MethodDesc,Internal.TypeSystem.TypeDesc[],Internal.TypeSystem.TypeDesc[]):Internal.TypeSystem.MethodDesc
         -44 (-6.92% of base) : 42280.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SubstitutedMethodSymbol:Equals(System.Object):bool:this
         -12 (-5.77% of base) : 40280.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol:ConstraintTypesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -12 (-5.66% of base) : 42697.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:AllInterfacesWithDefinitionUseSiteDiagnostics(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -16 (-5.56% of base) : 24241.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:GetAllUnaliasedModules(Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.ModuleSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

245 total methods with Code Size differences (206 improved, 39 regressed), 72 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 117618116 (overridden on cmd)
Total bytes of diff: 117617280 (overridden on cmd)
Total bytes of delta: -836 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          12 : 12703.dasm (0.88% of base)
          12 : 16218.dasm (0.82% of base)
           8 : 12874.dasm (2.25% of base)
           8 : 12675.dasm (2.25% of base)
           4 : 184713.dasm (3.23% of base)
           4 : 213888.dasm (2.27% of base)
           4 : 68703.dasm (0.72% of base)
           4 : 72214.dasm (1.27% of base)
           4 : 307004.dasm (3.23% of base)
           4 : 41296.dasm (0.39% of base)
           4 : 58298.dasm (3.23% of base)
           4 : 12674.dasm (0.49% of base)
           4 : 178292.dasm (3.23% of base)
           4 : 219551.dasm (0.41% of base)
           4 : 225137.dasm (3.23% of base)
           4 : 294087.dasm (3.23% of base)
           4 : 299031.dasm (3.23% of base)
           4 : 9910.dasm (1.12% of base)
           4 : 12709.dasm (0.22% of base)
           4 : 263461.dasm (3.23% of base)

Top file improvements (bytes):
         -72 : 317704.dasm (-1.21% of base)
         -40 : 317562.dasm (-1.19% of base)
         -32 : 317920.dasm (-1.17% of base)
         -32 : 317921.dasm (-1.17% of base)
         -28 : 317806.dasm (-1.22% of base)
         -28 : 99511.dasm (-0.96% of base)
         -24 : 10538.dasm (-1.99% of base)
         -24 : 72223.dasm (-1.85% of base)
         -24 : 317922.dasm (-0.71% of base)
         -20 : 321904.dasm (-1.05% of base)
         -20 : 7878.dasm (-1.49% of base)
         -20 : 99508.dasm (-0.87% of base)
         -20 : 134625.dasm (-1.62% of base)
         -20 : 317809.dasm (-0.89% of base)
         -16 : 16455.dasm (-1.25% of base)
         -16 : 2352.dasm (-1.90% of base)
         -16 : 6824.dasm (-7.14% of base)
         -16 : 317685.dasm (-1.53% of base)
         -16 : 7512.dasm (-1.67% of base)
         -16 : 71030.dasm (-2.37% of base)

141 total files with Code Size differences (100 improved, 41 regressed), 73 unchanged.

Top method regressions (bytes):
          12 ( 0.82% of base) : 16218.dasm - <FuzzyFindAsync>d__19:MoveNext():this
          12 ( 0.88% of base) : 12703.dasm - FunctionPointerTypeSymbolKey:Resolve(SymbolKeyReader,byref):Microsoft.CodeAnalysis.SymbolKeyResolution
           8 ( 2.25% of base) : 12675.dasm - AnonymousTypeSymbolKey:ReadPropertyLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           8 ( 2.25% of base) : 12874.dasm - TupleTypeSymbolKey:ReadElementLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           4 ( 4.76% of base) : 335166.dasm - <>c__5`1[__Canon][System.__Canon]:<CallOnEmptyStack>b__5_1(System.Threading.Tasks.Task`1[__Canon]):System.__Canon:this
           4 ( 0.49% of base) : 12674.dasm - AnonymousTypeSymbolKey:Resolve(SymbolKeyReader,byref):Microsoft.CodeAnalysis.SymbolKeyResolution
           4 ( 0.22% of base) : 12709.dasm - MethodSymbolKey:Resolve(SymbolKeyReader,byref):Microsoft.CodeAnalysis.SymbolKeyResolution
           4 ( 1.12% of base) : 9910.dasm - Microsoft.CodeAnalysis.EmbeddedLanguages.VirtualChars.VirtualCharSequence:CreateString():System.String:this
           4 ( 0.23% of base) : 12759.dasm - PropertySymbolKey:Resolve(SymbolKeyReader,byref):Microsoft.CodeAnalysis.SymbolKeyResolution
           4 ( 0.92% of base) : 1757.dasm - Roslyn.Utilities.AsyncLazy`1[Byte][System.Byte]:OnAsynchronousRequestCancelled(System.Object):this
           4 ( 0.42% of base) : 269832.dasm - System.Collections.Immutable.Tests.ImmutableArrayTest:Remove(System.Collections.Generic.IEnumerable`1[Vector`1],System.Numerics.Vector`1[Single],System.Collections.Generic.IEqualityComparer`1[Vector`1]):this
           4 ( 0.41% of base) : 219551.dasm - System.Data.SqlClient.SqlDependencyPerAppDomainDispatcher:TimeoutTimerCallback(System.Object)
           4 ( 0.41% of base) : 215285.dasm - System.Data.SqlClient.SqlDependencyPerAppDomainDispatcher:TimeoutTimerCallback(System.Object)
           4 ( 0.39% of base) : 41296.dasm - System.Globalization.Tests.DateTimeFormatInfoMiscTests:DateSeparatorTimeSeparator_Get_ReturnsExpected():this
           4 ( 0.39% of base) : 39545.dasm - System.Globalization.Tests.DateTimeFormatInfoMiscTests:DateSeparatorTimeSeparator_Get_ReturnsExpected():this
           4 ( 1.16% of base) : 69697.dasm - System.Runtime.Tests.DependentHandleTests:DependentDoesNotKeepTargetAlive():this
           4 ( 0.93% of base) : 69700.dasm - System.Runtime.Tests.DependentHandleTests:DependentIsCollectedAfterTargetIsSetToNull():this
           4 ( 0.90% of base) : 69698.dasm - System.Runtime.Tests.DependentHandleTests:DependentIsCollectedOnTargetNotReachable():this
           4 ( 0.90% of base) : 69699.dasm - System.Runtime.Tests.DependentHandleTests:DependentIsCollectedOnTargetNotReachable_EvenWithReferenceCycles():this
           4 ( 0.90% of base) : 69696.dasm - System.Runtime.Tests.DependentHandleTests:TargetKeepsDependentAlive():this

Top method improvements (bytes):
         -72 (-1.21% of base) : 317704.dasm - System.Reflection.Metadata.Ecma335.Tests.InstructionEncoderTests:Branch():this
         -40 (-1.19% of base) : 317562.dasm - System.Reflection.PortableExecutable.Tests.PEBuilderTests:BasicValidationEmit(System.Reflection.Metadata.Ecma335.MetadataBuilder,System.Reflection.Metadata.BlobBuilder):System.Reflection.Metadata.MethodDefinitionHandle
         -32 (-1.17% of base) : 317920.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameWithCultureSet():this
         -32 (-1.17% of base) : 317921.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameWithPublicKey():this
         -28 (-1.22% of base) : 317806.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps():this
         -28 (-0.96% of base) : 99511.dasm - System.Text.Json.Serialization.Tests.NullableTests:EnumerableWithNullableValue()
         -24 (-1.99% of base) : 10538.dasm - Microsoft.CodeAnalysis.Workspaces.Diagnostics.DiagnosticAnalysisResult:GetAllDiagnostics():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Diagnostics.DiagnosticData, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -24 (-0.71% of base) : 317922.dasm - System.Reflection.Metadata.Tests.AssemblyDefinitionTests:ValidateAssemblyNameForAssemblyDefinition():this
         -24 (-1.85% of base) : 72223.dasm - System.Tests.TimeZoneInfoTests:ConvertTimeBySystemTimeZoneIdTests()
         -20 (-1.49% of base) : 7878.dasm - Microsoft.CodeAnalysis.Options.GlobalOptionService:SetOptions(Microsoft.CodeAnalysis.Options.OptionSet):this
         -20 (-1.62% of base) : 134625.dasm - Microsoft.VisualBasic.Tests.DateAndTimeTests:Fields():this
         -20 (-0.89% of base) : 317809.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:Heaps_StartOffsets():this
         -20 (-1.05% of base) : 321904.dasm - System.Tests.HalfTests:Parse_Span_Valid(System.String,int,int,int,System.IFormatProvider,float)
         -20 (-0.87% of base) : 99508.dasm - System.Text.Json.Serialization.Tests.NullableTests:DictionaryWithNullableValue()
         -16 (-1.25% of base) : 16455.dasm - <FindOverriddenAndImplementedMembersAsync>d__1:MoveNext():this
         -16 (-1.90% of base) : 2352.dasm - Microsoft.CodeAnalysis.FileTextLoader:LoadTextAndVersionSynchronously(Microsoft.CodeAnalysis.Workspace,Microsoft.CodeAnalysis.DocumentId,System.Threading.CancellationToken):Microsoft.CodeAnalysis.TextAndVersion:this
         -16 (-1.67% of base) : 7512.dasm - Microsoft.CodeAnalysis.Rename.ConflictEngine.DeclarationConflictHelpers:GetConflictLocations(Microsoft.CodeAnalysis.ISymbol,System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool,System.Func`2[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Collections.Immutable.ImmutableArray`1[[System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ITypeSymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]], System.Collections.Immutable, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
         -16 (-7.14% of base) : 6824.dasm - Microsoft.CodeAnalysis.Shared.Extensions.ISymbolExtensions:GetAllTypeArguments(Microsoft.CodeAnalysis.ISymbol):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ITypeSymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
         -16 (-1.53% of base) : 317685.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors2():this
         -16 (-1.53% of base) : 317686.dasm - System.Reflection.Metadata.Ecma335.Tests.ControlFlowBuilderTests:AddRegion_Errors3():this

Top method regressions (percentages):
           4 ( 4.76% of base) : 335166.dasm - <>c__5`1[__Canon][System.__Canon]:<CallOnEmptyStack>b__5_1(System.Threading.Tasks.Task`1[__Canon]):System.__Canon:this
           4 ( 3.23% of base) : 184713.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 307004.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 58298.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 178292.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 225137.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 294087.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 299031.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 263461.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 331140.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 333081.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 287321.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 286980.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 305329.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 3.23% of base) : 303652.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 2.27% of base) : 213888.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           4 ( 2.27% of base) : 218169.dasm - System.Threading.Tasks.TaskToApm:End(System.IAsyncResult):System.__Canon
           8 ( 2.25% of base) : 12675.dasm - AnonymousTypeSymbolKey:ReadPropertyLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           8 ( 2.25% of base) : 12874.dasm - TupleTypeSymbolKey:ReadElementLocations(SymbolKeyReader,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
           4 ( 1.27% of base) : 72214.dasm - System.Tests.TimeZoneInfoTests:ConvertTimeFromUtc()

Top method improvements (percentages):
         -16 (-7.14% of base) : 6824.dasm - Microsoft.CodeAnalysis.Shared.Extensions.ISymbolExtensions:GetAllTypeArguments(Microsoft.CodeAnalysis.ISymbol):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ITypeSymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
         -12 (-5.66% of base) : 210534.dasm - System.Xml.XPath.XDocument.Tests.XDocument.NavigatorComparer:get_ValueAsDateTime():System.DateTime:this
          -8 (-4.65% of base) : 6822.dasm - Microsoft.CodeAnalysis.Shared.Extensions.ISymbolExtensions:GetAllTypeParameters(Microsoft.CodeAnalysis.ISymbol):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ITypeParameterSymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
          -8 (-3.85% of base) : 6127.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Byte,Nullable`1],ubyte,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6130.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Double,Nullable`1],double,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6128.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Int16,Nullable`1],short,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6129.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Int32,Nullable`1],int,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6132.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Int64,Nullable`1],long,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6133.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Byte,Nullable`1],ubyte,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6136.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Double,Nullable`1],double,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6134.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Int16,Nullable`1],short,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6135.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Int32,Nullable`1],int,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-3.85% of base) : 6138.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Int64,Nullable`1],long,System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
         -12 (-3.75% of base) : 134628.dasm - Microsoft.VisualBasic.Tests.DateAndTimeTests:Today():this
          -8 (-2.94% of base) : 6131.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformReadAsync(System.Func`2[Vector`1,Nullable`1],System.Numerics.Vector`1[Single],System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
          -8 (-2.94% of base) : 6137.dasm - Microsoft.CodeAnalysis.SQLite.v2.SQLitePersistentStorage:PerformWriteAsync(System.Func`2[Vector`1,Nullable`1],System.Numerics.Vector`1[Single],System.Threading.CancellationToken):System.Threading.Tasks.Task`1[Nullable`1]:this
         -16 (-2.37% of base) : 71030.dasm - System.Tests.DateTimeOffsetTests:UtcDateTime()
          -8 (-2.27% of base) : 7296.dasm - Microsoft.CodeAnalysis.Shared.Extensions.SymbolInfoExtensions:GetAllSymbolsWorker(Microsoft.CodeAnalysis.SymbolInfo):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.ISymbol, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
          -8 (-2.15% of base) : 141188.dasm - NuGet.Protocol.Plugins.MessageDispatcher:HandleInboundRequest(NuGet.Protocol.Plugins.IConnection,NuGet.Protocol.Plugins.Message):this
          -8 (-2.00% of base) : 253555.dasm - Microsoft.VisualStudio.Composition.ExportDefinition:ToString(System.IO.TextWriter):this

141 total methods with Code Size differences (100 improved, 41 regressed), 73 unchanged.

```

</details>

--------------------------------------------------------------------------------

