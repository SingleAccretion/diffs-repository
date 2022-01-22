## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 13180161 (overridden on cmd)
Total bytes of diff: 13180129 (overridden on cmd)
Total bytes of delta: -32 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          12 : 33512.dasm (0.97% of base)

Top file improvements (bytes):
         -14 : 8208.dasm (-0.15% of base)
         -14 : 12553.dasm (-0.15% of base)
          -8 : 969.dasm (-6.50% of base)
          -8 : 31720.dasm (-3.69% of base)

5 total files with Code Size differences (4 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          12 ( 0.97% of base) : 33512.dasm - Microsoft.CodeAnalysis.CommonReferenceManager`2[__Canon,__Canon][System.__Canon,System.__Canon]:BuildReferencedAssembliesAndModulesMaps(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[System.__Canon,System.__Canon][],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.MetadataReference, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[ResolvedReference],int,int,System.Collections.Generic.IReadOnlyDictionary`2[__Canon,__Canon],bool,byref,byref,byref)

Top method improvements (bytes):
         -14 (-0.15% of base) : 12553.dasm - Jil.Deserialize.Methods:ParseISO8601Date(System.IO.TextReader,System.Char[],int,int):System.DateTime
         -14 (-0.15% of base) : 8208.dasm - Jil.Deserialize.Methods:ParseISO8601DateThunkReader(byref,System.Char[],int,int):System.DateTime
          -8 (-3.69% of base) : 31720.dasm - Benchstone.BenchF.Whetsto:PA(System.Double[])
          -8 (-6.50% of base) : 969.dasm - System.TimeSpan:.ctor(int,int,int,int,int):this

Top method regressions (percentages):
          12 ( 0.97% of base) : 33512.dasm - Microsoft.CodeAnalysis.CommonReferenceManager`2[__Canon,__Canon][System.__Canon,System.__Canon]:BuildReferencedAssembliesAndModulesMaps(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[System.__Canon,System.__Canon][],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.MetadataReference, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[ResolvedReference],int,int,System.Collections.Generic.IReadOnlyDictionary`2[__Canon,__Canon],bool,byref,byref,byref)

Top method improvements (percentages):
          -8 (-6.50% of base) : 969.dasm - System.TimeSpan:.ctor(int,int,int,int,int):this
          -8 (-3.69% of base) : 31720.dasm - Benchstone.BenchF.Whetsto:PA(System.Double[])
         -14 (-0.15% of base) : 12553.dasm - Jil.Deserialize.Methods:ParseISO8601Date(System.IO.TextReader,System.Char[],int,int):System.DateTime
         -14 (-0.15% of base) : 8208.dasm - Jil.Deserialize.Methods:ParseISO8601DateThunkReader(byref,System.Char[],int,int):System.DateTime

5 total methods with Code Size differences (4 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 127502916 (overridden on cmd)
Total bytes of diff: 127502671 (overridden on cmd)
Total bytes of delta: -245 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -159 : 98010.dasm (-60.92% of base)
         -22 : 216489.dasm (-1.96% of base)
         -22 : 216482.dasm (-1.97% of base)
         -22 : 216501.dasm (-1.57% of base)
          -9 : 215940.dasm (-0.33% of base)
          -8 : 256412.dasm (-3.69% of base)
          -2 : 215931.dasm (-0.10% of base)
          -1 : 97256.dasm (-0.39% of base)

8 total files with Code Size differences (8 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -159 (-60.92% of base) : 98010.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
         -22 (-1.97% of base) : 216482.dasm - <GetFields>d__44:MoveNext():bool:this
         -22 (-1.96% of base) : 216489.dasm - <GetMethods>d__38:MoveNext():bool:this
         -22 (-1.57% of base) : 216501.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -9 (-0.33% of base) : 215940.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
          -8 (-3.69% of base) : 256412.dasm - Benchstone.BenchF.Whetsto:PA(System.Double[])
          -2 (-0.10% of base) : 215931.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
          -1 (-0.39% of base) : 97256.dasm - DevDiv_545500:Test(float,int,long):ubyte

Top method improvements (percentages):
        -159 (-60.92% of base) : 98010.dasm - ILGEN_CLASS:ILGEN_METHOD(ubyte,long,int):long
          -8 (-3.69% of base) : 256412.dasm - Benchstone.BenchF.Whetsto:PA(System.Double[])
         -22 (-1.97% of base) : 216482.dasm - <GetFields>d__44:MoveNext():bool:this
         -22 (-1.96% of base) : 216489.dasm - <GetMethods>d__38:MoveNext():bool:this
         -22 (-1.57% of base) : 216501.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
          -1 (-0.39% of base) : 97256.dasm - DevDiv_545500:Test(float,int,long):ubyte
          -9 (-0.33% of base) : 215940.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
          -2 (-0.10% of base) : 215931.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this

8 total methods with Code Size differences (8 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 34476220 (overridden on cmd)
Total bytes of diff: 34476014 (overridden on cmd)
Total bytes of delta: -206 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          38 : 49751.dasm (1.62% of base)
          13 : 13756.dasm (1.44% of base)
           3 : 68477.dasm (1.09% of base)
           2 : 63847.dasm (0.34% of base)
           2 : 48788.dasm (0.13% of base)

Top file improvements (bytes):
         -26 : 48787.dasm (-2.27% of base)
          -9 : 49964.dasm (-0.26% of base)
          -8 : 89844.dasm (-2.31% of base)
          -8 : 90225.dasm (-2.68% of base)
          -8 : 93051.dasm (-6.45% of base)
          -8 : 93052.dasm (-7.02% of base)
          -8 : 25075.dasm (-0.33% of base)
          -7 : 63851.dasm (-0.47% of base)
          -7 : 52154.dasm (-0.71% of base)
          -4 : 25076.dasm (-5.80% of base)
          -4 : 53913.dasm (-0.09% of base)
          -3 : 69354.dasm (-0.65% of base)
          -3 : 47495.dasm (-0.14% of base)
          -3 : 64091.dasm (-0.21% of base)
          -3 : 48453.dasm (-0.27% of base)
          -3 : 48786.dasm (-0.34% of base)
          -3 : 50087.dasm (-0.15% of base)
          -3 : 65869.dasm (-0.22% of base)
          -3 : 68983.dasm (-0.54% of base)
          -3 : 69148.dasm (-0.65% of base)

121 total files with Code Size differences (116 improved, 5 regressed), 18 unchanged.

Top method regressions (bytes):
          38 ( 1.62% of base) : 49751.dasm - AnonymousTypeToStringMethodSymbol:GetBoundMethodBody(Microsoft.CodeAnalysis.DiagnosticBag,byref):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          13 ( 1.44% of base) : 13756.dasm - Microsoft.CodeAnalysis.CommonReferenceManager`2:BuildReferencedAssembliesAndModulesMaps(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[System.__Canon, System.__Canon][],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.MetadataReference],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ResolvedReference[System.__Canon, System.__Canon]],int,int,System.Collections.Generic.IReadOnlyDictionary`2[System.String, System.Collections.Generic.List`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ReferencedAssemblyIdentity[System.__Canon, System.__Canon]]],bool,byref,byref,byref)
           3 ( 1.09% of base) : 68477.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceErrorTypeSymbol:get_TypeParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol]:this
           2 ( 0.34% of base) : 63847.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceParamArrayArgument(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal],byref,byref)
           2 ( 0.13% of base) : 48788.dasm - ReferenceManager:SetupReferencesForRetargetingAssembly(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation, Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)

Top method improvements (bytes):
         -26 (-2.27% of base) : 48787.dasm - ReferenceManager:SetupReferencesForFileAssembly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation+ReferenceManager+AssemblyDataForFile,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation, Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)
          -9 (-0.26% of base) : 49964.dasm - IntoClauseBinder:BindIntoSelector(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol],System.Collections.Generic.HashSet`1[System.String],Microsoft.CodeAnalysis.SeparatedSyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.AggregationRangeVariableSyntax],bool,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -8 (-2.31% of base) : 89844.dasm - System.Buffers.Text.Utf8Parser:TryCreateTimeSpan(bool,int,int,int,int,int,byref):bool
          -8 (-2.68% of base) : 90225.dasm - System.Globalization.TimeSpanParse:TryTimeToTicks(bool,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,byref):bool
          -8 (-0.33% of base) : 25075.dasm - System.Text.GB18030Encoding:GetChars(long,int,long,int,System.Text.DecoderNLS):int:this
          -8 (-7.02% of base) : 93052.dasm - System.TimeSpan:.ctor(int,int,int,int):this
          -8 (-6.45% of base) : 93051.dasm - System.TimeSpan:.ctor(int,int,int,int,int):this
          -7 (-0.71% of base) : 52154.dasm - Microsoft.CodeAnalysis.VisualBasic.TypeUnification:AddSubstitution(byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeWithModifiers)
          -7 (-0.47% of base) : 63851.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwicePropertyAccess(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundPropertyAccess,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal]):Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter+Result
          -4 (-0.09% of base) : 53913.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:MatchArguments(Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],Microsoft.CodeAnalysis.VisualBasic.Binder,byref,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,bool,byref)
          -4 (-5.80% of base) : 25076.dasm - System.Text.GB18030Encoding:GetFourBytesOffset(short,short,short,short):int:this
          -3 (-0.15% of base) : 50087.dasm - AnonymousTypeCreationBinder:.ctor(Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.VisualBasic.Syntax.ObjectMemberInitializerSyntax,Microsoft.CodeAnalysis.DiagnosticBag):this
          -3 (-0.14% of base) : 47495.dasm - InferenceGraph:Infer(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.ArrayBuilder`1[System.Int32],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundNode,byref,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.BitVector):bool
          -3 (-0.13% of base) : 70897.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAggregateQueryExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryExpressionSyntax,Microsoft.CodeAnalysis.SyntaxList`1+Enumerator[Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundQueryExpression:this
          -3 (-0.60% of base) : 71090.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAssignmentTarget(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-0.15% of base) : 70952.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindLambdaForErrorRecovery(Microsoft.CodeAnalysis.VisualBasic.UnboundLambda):Microsoft.CodeAnalysis.VisualBasic.BoundLambda:this
          -3 (-0.12% of base) : 70736.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ResolveOverloadedMembers(System.Collections.Immutable.ImmutableArray`1[System.__Canon],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentSyntax]):Microsoft.CodeAnalysis.VisualBasic.OverloadResolutionResult`1[System.__Canon]:this
          -3 (-0.15% of base) : 64266.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:BuildDelegateRelaxationLambda(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundLateMemberAccess,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression
          -3 (-0.08% of base) : 64251.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:LateCallOrGet(Microsoft.CodeAnalysis.VisualBasic.BoundLateMemberAccess,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],System.Collections.Immutable.ImmutableArray`1[System.String],bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-0.78% of base) : 64186.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitRedimStatement(Microsoft.CodeAnalysis.VisualBasic.BoundRedimStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method regressions (percentages):
          38 ( 1.62% of base) : 49751.dasm - AnonymousTypeToStringMethodSymbol:GetBoundMethodBody(Microsoft.CodeAnalysis.DiagnosticBag,byref):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          13 ( 1.44% of base) : 13756.dasm - Microsoft.CodeAnalysis.CommonReferenceManager`2:BuildReferencedAssembliesAndModulesMaps(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[System.__Canon, System.__Canon][],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.MetadataReference],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ResolvedReference[System.__Canon, System.__Canon]],int,int,System.Collections.Generic.IReadOnlyDictionary`2[System.String, System.Collections.Generic.List`1[Microsoft.CodeAnalysis.CommonReferenceManager`2+ReferencedAssemblyIdentity[System.__Canon, System.__Canon]]],bool,byref,byref,byref)
           3 ( 1.09% of base) : 68477.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.InstanceErrorTypeSymbol:get_TypeParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol]:this
           2 ( 0.34% of base) : 63847.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceParamArrayArgument(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal],byref,byref)
           2 ( 0.13% of base) : 48788.dasm - ReferenceManager:SetupReferencesForRetargetingAssembly(Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation, Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)

Top method improvements (percentages):
          -8 (-7.02% of base) : 93052.dasm - System.TimeSpan:.ctor(int,int,int,int):this
          -8 (-6.45% of base) : 93051.dasm - System.TimeSpan:.ctor(int,int,int,int,int):this
          -4 (-5.80% of base) : 25076.dasm - System.Text.GB18030Encoding:GetFourBytesOffset(short,short,short,short):int:this
          -8 (-2.68% of base) : 90225.dasm - System.Globalization.TimeSpanParse:TryTimeToTicks(bool,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,System.Globalization.TimeSpanParse+TimeSpanToken,byref):bool
          -1 (-2.56% of base) : 30931.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrPrivate.CCWRefCountChangeTraceData:get_COMInterfacePointer():long:this
          -8 (-2.31% of base) : 89844.dasm - System.Buffers.Text.Utf8Parser:TryCreateTimeSpan(bool,int,int,int,int,int,byref):bool
         -26 (-2.27% of base) : 48787.dasm - ReferenceManager:SetupReferencesForFileAssembly(Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation+ReferenceManager+AssemblyDataForFile,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation, Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)
          -1 (-1.25% of base) : 36277.dasm - Microsoft.Diagnostics.Tracing.Parsers.Kernel.FileIODirEnumTraceData:get_FileKey():long:this
          -2 (-0.88% of base) : 64616.dasm - Microsoft.CodeAnalysis.VisualBasic.ExpressionLambdaRewriter:BuildIndices(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-0.88% of base) : 68890.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingMethodSymbol:RetargetParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol]:this
          -2 (-0.88% of base) : 68660.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingPropertySymbol:RetargetParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol]:this
          -2 (-0.88% of base) : 48569.dasm - AsyncMethodToClassRewriter:VisitArrayInitializationParts(Microsoft.CodeAnalysis.VisualBasic.BoundArrayInitialization):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-0.78% of base) : 71199.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeTypes(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Binder],System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.AttributeSyntax],Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol]
          -3 (-0.78% of base) : 64186.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitRedimStatement(Microsoft.CodeAnalysis.VisualBasic.BoundRedimStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -7 (-0.71% of base) : 52154.dasm - Microsoft.CodeAnalysis.VisualBasic.TypeUnification:AddSubstitution(byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeWithModifiers)
          -3 (-0.65% of base) : 69354.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PEAssemblySymbol:.ctor(Microsoft.CodeAnalysis.PEAssembly,Microsoft.CodeAnalysis.DocumentationProvider,bool,ubyte):this
          -3 (-0.65% of base) : 69148.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:EnsureTypeParametersAreLoaded():this
          -2 (-0.63% of base) : 66686.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SubstitutedPropertySymbol:SubstituteParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol]:this
          -2 (-0.62% of base) : 48523.dasm - CapturedArrayAccessExpression:Materialize(Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+AsyncMethodToClassRewriter,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-0.61% of base) : 66863.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SubstitutedMethodSymbol:SubstituteParameters():System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol]:this

121 total methods with Code Size differences (116 improved, 5 regressed), 18 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 46234580 (overridden on cmd)
Total bytes of diff: 46234238 (overridden on cmd)
Total bytes of delta: -342 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          16 : 56182.dasm (3.99% of base)
           7 : 69104.dasm (3.12% of base)
           2 : 56604.dasm (0.27% of base)
           2 : 69100.dasm (0.55% of base)

Top file improvements (bytes):
         -37 : 71846.dasm (-0.87% of base)
         -23 : 73010.dasm (-1.55% of base)
         -22 : 154780.dasm (-1.57% of base)
         -22 : 154770.dasm (-1.96% of base)
         -22 : 154587.dasm (-1.44% of base)
         -22 : 154764.dasm (-1.96% of base)
         -21 : 212159.dasm (-1.33% of base)
         -14 : 214183.dasm (-2.90% of base)
         -14 : 213838.dasm (-2.90% of base)
         -14 : 214184.dasm (-2.90% of base)
         -12 : 147465.dasm (-0.41% of base)
         -12 : 67838.dasm (-0.24% of base)
          -9 : 72047.dasm (-0.26% of base)
          -9 : 154483.dasm (-0.33% of base)
          -8 : 203477.dasm (-2.07% of base)
          -8 : 199338.dasm (-0.48% of base)
          -7 : 73009.dasm (-0.56% of base)
          -4 : 147463.dasm (-5.80% of base)
          -4 : 199339.dasm (-0.25% of base)
          -4 : 73268.dasm (-1.23% of base)

67 total files with Code Size differences (63 improved, 4 regressed), 42 unchanged.

Top method regressions (bytes):
          16 ( 3.99% of base) : 56182.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitRedimStatement(Microsoft.CodeAnalysis.VisualBasic.BoundRedimStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
           7 ( 3.12% of base) : 69104.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFactory:TriviaList(Microsoft.CodeAnalysis.SyntaxTrivia[]):Microsoft.CodeAnalysis.SyntaxTriviaList
           2 ( 0.55% of base) : 69100.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFactory:TokenList(Microsoft.CodeAnalysis.SyntaxToken[]):Microsoft.CodeAnalysis.SyntaxTokenList
           2 ( 0.27% of base) : 56604.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedContainer:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

Top method improvements (bytes):
         -37 (-0.87% of base) : 71846.dasm - IntoClauseBinder:BindIntoSelector(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.AggregationRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -23 (-1.55% of base) : 73010.dasm - ReferenceManager:SetupReferencesForSourceAssembly(Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],byref,byref)
         -22 (-1.96% of base) : 154764.dasm - <GetFields>d__49:MoveNext():bool:this
         -22 (-1.96% of base) : 154770.dasm - <GetMethods>d__43:MoveNext():bool:this
         -22 (-1.44% of base) : 154587.dasm - <GetParameterNames>d__6:MoveNext():bool:this
         -22 (-1.57% of base) : 154780.dasm - <GetVirtualMethods>d__44:MoveNext():bool:this
         -21 (-1.33% of base) : 212159.dasm - <SpecializeFields>d__3:MoveNext():bool:this
         -14 (-2.90% of base) : 213838.dasm - System.Reflection.Metadata.MethodDefinition:GetParameters():System.Reflection.Metadata.ParameterHandleCollection:this
         -14 (-2.90% of base) : 214184.dasm - System.Reflection.Metadata.TypeDefinition:GetFields():System.Reflection.Metadata.FieldDefinitionHandleCollection:this
         -14 (-2.90% of base) : 214183.dasm - System.Reflection.Metadata.TypeDefinition:GetMethods():System.Reflection.Metadata.MethodDefinitionHandleCollection:this
         -12 (-0.24% of base) : 67838.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:MatchArguments(Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.VisualBasic.Binder,byref,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,bool,byref)
         -12 (-0.41% of base) : 147465.dasm - System.Text.GB18030Encoding:GetChars(long,int,long,int,System.Text.DecoderNLS):int:this
          -9 (-0.26% of base) : 72047.dasm - AnonymousTypeGetHashCodeMethodSymbol:GetBoundMethodBody(Microsoft.CodeAnalysis.DiagnosticBag,byref):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          -9 (-0.33% of base) : 154483.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
          -8 (-0.48% of base) : 199338.dasm - System.Management.ManagementDateTimeConverter:ToTimeSpan(System.String):System.TimeSpan
          -8 (-2.07% of base) : 203477.dasm - System.Net.Mime.SmtpDateTime:ValidateAndGetSanitizedTimeSpan(System.TimeSpan):System.TimeSpan:this
          -7 (-0.56% of base) : 73009.dasm - ReferenceManager:SetupReferencesForFileAssembly(AssemblyDataForFile,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)
          -4 (-1.23% of base) : 73268.dasm - CapturedArrayAccessExpression:Materialize(AsyncMethodToClassRewriter,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -4 (-0.25% of base) : 199339.dasm - System.Management.ManagementDateTimeConverter:ToDmtfTimeInterval(System.TimeSpan):System.String
          -4 (-5.80% of base) : 147463.dasm - System.Text.GB18030Encoding:GetFourBytesOffset(short,short,short,short):int:this

Top method regressions (percentages):
          16 ( 3.99% of base) : 56182.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitRedimStatement(Microsoft.CodeAnalysis.VisualBasic.BoundRedimStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
           7 ( 3.12% of base) : 69104.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFactory:TriviaList(Microsoft.CodeAnalysis.SyntaxTrivia[]):Microsoft.CodeAnalysis.SyntaxTriviaList
           2 ( 0.55% of base) : 69100.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFactory:TokenList(Microsoft.CodeAnalysis.SyntaxToken[]):Microsoft.CodeAnalysis.SyntaxTokenList
           2 ( 0.27% of base) : 56604.dasm - Microsoft.CodeAnalysis.VisualBasic.SynthesizedContainer:.ctor(Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,System.String,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

Top method improvements (percentages):
          -4 (-5.80% of base) : 147463.dasm - System.Text.GB18030Encoding:GetFourBytesOffset(short,short,short,short):int:this
         -14 (-2.90% of base) : 213838.dasm - System.Reflection.Metadata.MethodDefinition:GetParameters():System.Reflection.Metadata.ParameterHandleCollection:this
         -14 (-2.90% of base) : 214184.dasm - System.Reflection.Metadata.TypeDefinition:GetFields():System.Reflection.Metadata.FieldDefinitionHandleCollection:this
         -14 (-2.90% of base) : 214183.dasm - System.Reflection.Metadata.TypeDefinition:GetMethods():System.Reflection.Metadata.MethodDefinitionHandleCollection:this
          -8 (-2.07% of base) : 203477.dasm - System.Net.Mime.SmtpDateTime:ValidateAndGetSanitizedTimeSpan(System.TimeSpan):System.TimeSpan:this
         -22 (-1.96% of base) : 154764.dasm - <GetFields>d__49:MoveNext():bool:this
         -22 (-1.96% of base) : 154770.dasm - <GetMethods>d__43:MoveNext():bool:this
         -22 (-1.57% of base) : 154780.dasm - <GetVirtualMethods>d__44:MoveNext():bool:this
         -23 (-1.55% of base) : 73010.dasm - ReferenceManager:SetupReferencesForSourceAssembly(Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.PEModule, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],byref,byref)
         -22 (-1.44% of base) : 154587.dasm - <GetParameterNames>d__6:MoveNext():bool:this
         -21 (-1.33% of base) : 212159.dasm - <SpecializeFields>d__3:MoveNext():bool:this
          -4 (-1.23% of base) : 73268.dasm - CapturedArrayAccessExpression:Materialize(AsyncMethodToClassRewriter,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-0.99% of base) : 56771.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureArrayAccess(Microsoft.CodeAnalysis.VisualBasic.BoundArrayAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -37 (-0.87% of base) : 71846.dasm - IntoClauseBinder:BindIntoSelector(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.RangeVariableSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.AggregationRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-0.85% of base) : 51641.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingMethodSymbol:RetargetParameters():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -2 (-0.85% of base) : 51852.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingPropertySymbol:RetargetParameters():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -3 (-0.63% of base) : 56768.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceParamArrayArgument(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref,byref)
          -1 (-0.57% of base) : 54496.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGen.CodeGenerator:EmitSwitch(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundGotoStatement, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -7 (-0.56% of base) : 73009.dasm - ReferenceManager:SetupReferencesForFileAssembly(AssemblyDataForFile,Microsoft.CodeAnalysis.CommonReferenceManager`2+BoundInputAssembly[Microsoft.CodeAnalysis.VisualBasic.VisualBasicCompilation,Microsoft.CodeAnalysis.VisualBasic.Symbols.AssemblySymbol][],int,byref,Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceAssemblySymbol)
          -2 (-0.53% of base) : 72392.dasm - RetargetingSymbolTranslator:RetargetModifiers(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CustomModifier, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CustomModifier, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this

67 total methods with Code Size differences (63 improved, 4 regressed), 42 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 118424275 (overridden on cmd)
Total bytes of diff: 118424167 (overridden on cmd)
Total bytes of delta: -108 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -12 : 16399.dasm (-0.15% of base)
          -8 : 76236.dasm (-1.73% of base)
          -8 : 76241.dasm (-1.73% of base)
          -8 : 302833.dasm (-2.07% of base)
          -8 : 76239.dasm (-1.73% of base)
          -8 : 76245.dasm (-1.73% of base)
          -8 : 76240.dasm (-1.73% of base)
          -8 : 76243.dasm (-1.73% of base)
          -8 : 76237.dasm (-1.73% of base)
          -8 : 76238.dasm (-1.73% of base)
          -8 : 76242.dasm (-1.73% of base)
          -8 : 231634.dasm (-0.88% of base)
          -8 : 76244.dasm (-1.73% of base)

13 total files with Code Size differences (13 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -12 (-0.15% of base) : 16399.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
          -8 (-1.73% of base) : 76236.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__0():System.Object:this
          -8 (-1.73% of base) : 76237.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__1():System.Object:this
          -8 (-1.73% of base) : 76238.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__2():System.Object:this
          -8 (-1.73% of base) : 76239.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__3():System.Object:this
          -8 (-1.73% of base) : 76240.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__4():System.Object:this
          -8 (-1.73% of base) : 76241.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__5():System.Object:this
          -8 (-1.73% of base) : 76242.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__6():System.Object:this
          -8 (-1.73% of base) : 76243.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__7():System.Object:this
          -8 (-1.73% of base) : 76244.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__8():System.Object:this
          -8 (-1.73% of base) : 76245.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__9():System.Object:this
          -8 (-0.88% of base) : 231634.dasm - FluentAssertions.Primitives.SimpleTimeSpanAssertions:BeCloseTo(System.TimeSpan,int,System.String,System.Object[]):FluentAssertions.AndConstraint`1[[FluentAssertions.Primitives.SimpleTimeSpanAssertions, FluentAssertions.Core, Version=4.19.4.0, Culture=neutral, PublicKeyToken=33f2691a05b67b6a]]:this
          -8 (-2.07% of base) : 302833.dasm - System.Net.Mime.SmtpDateTime:ValidateAndGetSanitizedTimeSpan(System.TimeSpan):System.TimeSpan:this

Top method improvements (percentages):
          -8 (-2.07% of base) : 302833.dasm - System.Net.Mime.SmtpDateTime:ValidateAndGetSanitizedTimeSpan(System.TimeSpan):System.TimeSpan:this
          -8 (-1.73% of base) : 76240.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__4():System.Object:this
          -8 (-1.73% of base) : 76245.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__9():System.Object:this
          -8 (-1.73% of base) : 76236.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__0():System.Object:this
          -8 (-1.73% of base) : 76237.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__1():System.Object:this
          -8 (-1.73% of base) : 76238.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__2():System.Object:this
          -8 (-1.73% of base) : 76239.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__3():System.Object:this
          -8 (-1.73% of base) : 76241.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__5():System.Object:this
          -8 (-1.73% of base) : 76242.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__6():System.Object:this
          -8 (-1.73% of base) : 76243.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__7():System.Object:this
          -8 (-1.73% of base) : 76244.dasm - <>c__DisplayClass8_0:<Ctor_Int_Int_Int_Int_Int_Invalid>b__8():System.Object:this
          -8 (-0.88% of base) : 231634.dasm - FluentAssertions.Primitives.SimpleTimeSpanAssertions:BeCloseTo(System.TimeSpan,int,System.String,System.Object[]):FluentAssertions.AndConstraint`1[[FluentAssertions.Primitives.SimpleTimeSpanAssertions, FluentAssertions.Core, Version=4.19.4.0, Culture=neutral, PublicKeyToken=33f2691a05b67b6a]]:this
         -12 (-0.15% of base) : 16399.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this

13 total methods with Code Size differences (13 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

