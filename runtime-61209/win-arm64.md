## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7633828 (overridden on cmd)
Total bytes of diff: 7633752 (overridden on cmd)
Total bytes of delta: -76 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -28 : 17078.dasm (-0.63% of base)
         -24 : 4541.dasm (-5.50% of base)
         -24 : 4548.dasm (-2.18% of base)

3 total files with Code Size differences (3 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -28 (-0.63% of base) : 17078.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckValueKind(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ushort,bool,Microsoft.CodeAnalysis.DiagnosticBag):bool:this
         -24 (-2.18% of base) : 4548.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -24 (-5.50% of base) : 4541.dasm - System.Diagnostics.ActivityCreationOptions`1[ActivityContext][System.Diagnostics.ActivityContext]:.ctor(System.Diagnostics.ActivitySource,System.String,System.Diagnostics.ActivityContext,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this

Top method improvements (percentages):
         -24 (-5.50% of base) : 4541.dasm - System.Diagnostics.ActivityCreationOptions`1[ActivityContext][System.Diagnostics.ActivityContext]:.ctor(System.Diagnostics.ActivitySource,System.String,System.Diagnostics.ActivityContext,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -24 (-2.18% of base) : 4548.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -28 (-0.63% of base) : 17078.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckValueKind(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ushort,bool,Microsoft.CodeAnalysis.DiagnosticBag):bool:this

3 total methods with Code Size differences (3 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 165279580 (overridden on cmd)
Total bytes of diff: 165276592 (overridden on cmd)
Total bytes of delta: -2988 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -228 : 152471.dasm (-5.20% of base)
        -228 : 154881.dasm (-5.26% of base)
        -140 : 192230.dasm (-19.34% of base)
        -136 : 192192.dasm (-26.15% of base)
        -136 : 192224.dasm (-30.36% of base)
        -136 : 192229.dasm (-20.24% of base)
        -136 : 192222.dasm (-30.91% of base)
        -128 : 192196.dasm (-18.93% of base)
        -120 : 192191.dasm (-22.22% of base)
        -116 : 192216.dasm (-27.88% of base)
        -112 : 192235.dasm (-20.90% of base)
        -108 : 192217.dasm (-26.73% of base)
        -100 : 151773.dasm (-1.51% of base)
         -96 : 192223.dasm (-29.63% of base)
         -76 : 192228.dasm (-9.69% of base)
         -64 : 166064.dasm (-13.68% of base)
         -64 : 166134.dasm (-13.91% of base)
         -64 : 166093.dasm (-13.91% of base)
         -56 : 248968.dasm (-73.68% of base)
         -52 : 86425.dasm (-48.15% of base)

47 total files with Code Size differences (47 improved, 0 regressed), 6 unchanged.

Top method improvements (bytes):
        -228 (-5.20% of base) : 152471.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -228 (-5.26% of base) : 154881.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -140 (-19.34% of base) : 192230.dasm - testout1:Func_0_6_3():long
        -136 (-26.15% of base) : 192192.dasm - testout1:Func_0_2_4():double
        -136 (-20.24% of base) : 192229.dasm - testout1:Func_0_6_4():long
        -136 (-30.36% of base) : 192224.dasm - testout1:Func_0_7_4():double
        -136 (-30.91% of base) : 192222.dasm - testout1:Func_0_7_6():double
        -128 (-18.93% of base) : 192196.dasm - testout1:Func_0_1_9():long
        -120 (-22.22% of base) : 192191.dasm - testout1:Func_0_2_5():short
        -116 (-27.88% of base) : 192216.dasm - testout1:Func_0_8_4():double
        -112 (-20.90% of base) : 192235.dasm - testout1:Func_0_5_5():long
        -108 (-26.73% of base) : 192217.dasm - testout1:Func_0_8_3():double
        -100 (-1.51% of base) : 151773.dasm - testout1:Func_0_1_6_6_1():System.Decimal
         -96 (-29.63% of base) : 192223.dasm - testout1:Func_0_7_5():double
         -76 (-9.69% of base) : 192228.dasm - testout1:Func_0_6_5():long
         -64 (-13.68% of base) : 166064.dasm - NativeVarargTest.VarArg:TestEchoSixteenByteStructManaged():bool
         -64 (-13.91% of base) : 166093.dasm - NativeVarargTest.VarArg:TestEchoSixteenByteStructManagedNoVararg():bool
         -64 (-13.91% of base) : 166134.dasm - NativeVarargTest.VarArg:TestEchoSixteenByteStructNoVararg():bool
         -56 (-73.68% of base) : 248968.dasm - Runtime_45090.ProbeBeforeSubSp5:VirtMethodEspBasedFrame():int:this
         -52 (-48.15% of base) : 86425.dasm - Runtime_55141_2:Main():int

Top method improvements (percentages):
         -56 (-73.68% of base) : 248968.dasm - Runtime_45090.ProbeBeforeSubSp5:VirtMethodEspBasedFrame():int:this
         -48 (-70.59% of base) : 248966.dasm - Runtime_45090.ProbeBeforeSubSp3:VirtMethodEspBasedFrame():int:this
         -48 (-70.59% of base) : 248967.dasm - Runtime_45090.ProbeBeforeSubSp4:VirtMethodEspBasedFrame():int:this
         -40 (-66.67% of base) : 248964.dasm - Runtime_45090.ProbeBeforeSubSp1:VirtMethodEspBasedFrame():int:this
         -40 (-66.67% of base) : 248965.dasm - Runtime_45090.ProbeBeforeSubSp2:VirtMethodEspBasedFrame():int:this
         -36 (-56.25% of base) : 86423.dasm - Runtime_55141:Run(long):int
         -24 (-54.55% of base) : 248963.dasm - Runtime_45090.ProbeAfterSubSp:VirtMethodEspBasedFrame():int:this
         -52 (-48.15% of base) : 86425.dasm - Runtime_55141_2:Main():int
         -16 (-44.44% of base) : 248962.dasm - Runtime_45090.SubSp:VirtMethodEspBasedFrame():int:this
         -16 (-44.44% of base) : 86484.dasm - Runtime_57912:test_0_17(int,AA,AA):short
        -136 (-30.91% of base) : 192222.dasm - testout1:Func_0_7_6():double
        -136 (-30.36% of base) : 192224.dasm - testout1:Func_0_7_4():double
         -96 (-29.63% of base) : 192223.dasm - testout1:Func_0_7_5():double
        -116 (-27.88% of base) : 192216.dasm - testout1:Func_0_8_4():double
        -108 (-26.73% of base) : 192217.dasm - testout1:Func_0_8_3():double
        -136 (-26.15% of base) : 192192.dasm - testout1:Func_0_2_4():double
        -120 (-22.22% of base) : 192191.dasm - testout1:Func_0_2_5():short
        -112 (-20.90% of base) : 192235.dasm - testout1:Func_0_5_5():long
        -136 (-20.24% of base) : 192229.dasm - testout1:Func_0_6_4():long
        -140 (-19.34% of base) : 192230.dasm - testout1:Func_0_6_3():long

47 total methods with Code Size differences (47 improved, 0 regressed), 6 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51809972 (overridden on cmd)
Total bytes of diff: 51809964 (overridden on cmd)
Total bytes of delta: -8 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 185679.dasm (-0.32% of base)

1 total files with Code Size differences (1 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
          -8 (-0.32% of base) : 185679.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,Internal.TypeSystem.MetadataVirtualMethodAlgorithm+UnificationGroup)

Top method improvements (percentages):
          -8 (-0.32% of base) : 185679.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,Internal.TypeSystem.MetadataVirtualMethodAlgorithm+UnificationGroup)

1 total methods with Code Size differences (1 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51524128 (overridden on cmd)
Total bytes of diff: 51523948 (overridden on cmd)
Total bytes of delta: -180 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -24 : 172397.dasm (-7.41% of base)
         -24 : 172402.dasm (-3.64% of base)
         -24 : 48547.dasm (-0.40% of base)
         -24 : 172270.dasm (-2.18% of base)
         -12 : 48207.dasm (-0.24% of base)
          -8 : 77796.dasm (-2.15% of base)
          -8 : 77800.dasm (-2.15% of base)
          -8 : 48590.dasm (-0.22% of base)
          -8 : 142614.dasm (-0.44% of base)
          -8 : 228675.dasm (-4.55% of base)
          -8 : 77794.dasm (-1.83% of base)
          -8 : 228672.dasm (-1.94% of base)
          -8 : 48112.dasm (-0.13% of base)
          -4 : 221295.dasm (-0.21% of base)
          -4 : 48607.dasm (-0.09% of base)

15 total files with Code Size differences (15 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
         -24 (-0.40% of base) : 48547.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportNoConversionError(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag,System.String):this
         -24 (-2.18% of base) : 172270.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -24 (-3.64% of base) : 172402.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -24 (-7.41% of base) : 172397.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
         -12 (-0.24% of base) : 48207.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAddRemoveHandlerStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.AddRemoveHandlerStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundAddRemoveHandlerStatement:this
          -8 (-1.94% of base) : 228672.dasm - ILCompiler.CompilerTypeSystemContext:GetOrAddModuleFromPath(System.String,bool):Internal.TypeSystem.Ecma.EcmaModule:this
          -8 (-4.55% of base) : 228675.dasm - ILCompiler.CompilerTypeSystemContext:InheritOpenModules(ILCompiler.CompilerTypeSystemContext):this
          -8 (-0.44% of base) : 142614.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
          -8 (-1.83% of base) : 77794.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-2.15% of base) : 77796.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-2.15% of base) : 77800.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-0.22% of base) : 48590.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindTypeParameterConstraint(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ConstraintSyntax,byref,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterConstraint],Microsoft.CodeAnalysis.DiagnosticBag):this
          -8 (-0.13% of base) : 48112.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-0.21% of base) : 221295.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
          -4 (-0.09% of base) : 48607.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReclassifyQueryLambdaExpression(Microsoft.CodeAnalysis.VisualBasic.BoundQueryLambda,ushort,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method improvements (percentages):
         -24 (-7.41% of base) : 172397.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
          -8 (-4.55% of base) : 228675.dasm - ILCompiler.CompilerTypeSystemContext:InheritOpenModules(ILCompiler.CompilerTypeSystemContext):this
         -24 (-3.64% of base) : 172402.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -24 (-2.18% of base) : 172270.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
          -8 (-2.15% of base) : 77796.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-2.15% of base) : 77800.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-1.94% of base) : 228672.dasm - ILCompiler.CompilerTypeSystemContext:GetOrAddModuleFromPath(System.String,bool):Internal.TypeSystem.Ecma.EcmaModule:this
          -8 (-1.83% of base) : 77794.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -8 (-0.44% of base) : 142614.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
         -24 (-0.40% of base) : 48547.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportNoConversionError(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag,System.String):this
         -12 (-0.24% of base) : 48207.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAddRemoveHandlerStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.AddRemoveHandlerStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundAddRemoveHandlerStatement:this
          -8 (-0.22% of base) : 48590.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindTypeParameterConstraint(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ConstraintSyntax,byref,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterConstraint],Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-0.21% of base) : 221295.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
          -8 (-0.13% of base) : 48112.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-0.09% of base) : 48607.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReclassifyQueryLambdaExpression(Microsoft.CodeAnalysis.VisualBasic.BoundQueryLambda,ushort,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

15 total methods with Code Size differences (15 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 117618056 (overridden on cmd)
Total bytes of diff: 117617796 (overridden on cmd)
Total bytes of delta: -260 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -100 : 341716.dasm (-27.78% of base)
         -20 : 311368.dasm (-6.02% of base)
         -20 : 311362.dasm (-5.32% of base)
         -20 : 128409.dasm (-1.50% of base)
         -20 : 311365.dasm (-5.62% of base)
         -20 : 126321.dasm (-1.44% of base)
         -16 : 311444.dasm (-0.34% of base)
         -16 : 326541.dasm (-0.17% of base)
          -8 : 128938.dasm (-1.52% of base)
          -8 : 125232.dasm (-1.79% of base)
          -4 : 16356.dasm (-0.16% of base)
          -4 : 338164.dasm (-0.36% of base)
          -4 : 2129.dasm (-0.67% of base)

13 total files with Code Size differences (13 improved, 0 regressed), 4 unchanged.

Top method improvements (bytes):
        -100 (-27.78% of base) : 341716.dasm - System.Tests.ExtensionsTests:ConvertToRef8()
         -20 (-1.44% of base) : 126321.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
         -20 (-1.50% of base) : 128409.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGeneration.VisualBasicSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
         -20 (-6.02% of base) : 311368.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector2Test1():this
         -20 (-5.62% of base) : 311365.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector3Test1():this
         -20 (-5.32% of base) : 311362.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector4Test1():this
         -16 (-0.17% of base) : 326541.dasm - System.Numerics.Tests.ComparisonTest:RunPositiveTests(System.Random)
         -16 (-0.34% of base) : 311444.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2EqualsNanTest():this
          -8 (-1.79% of base) : 125232.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.CSharpTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -8 (-1.52% of base) : 128938.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.VisualBasicTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -4 (-0.16% of base) : 16356.dasm - <FindReferencesThroughAliasSymbolsAsync>d__26:MoveNext():this
          -4 (-0.67% of base) : 2129.dasm - Roslyn.Utilities.SyntaxPath:TryResolve(Microsoft.CodeAnalysis.SyntaxNode,byref):bool:this
          -4 (-0.36% of base) : 338164.dasm - System.Threading.Tasks.Tests.ValueTaskTests:Generic_CreateFromSuccessfullyCompleted_IsCompletedSuccessfully(int):this

Top method improvements (percentages):
        -100 (-27.78% of base) : 341716.dasm - System.Tests.ExtensionsTests:ConvertToRef8()
         -20 (-6.02% of base) : 311368.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector2Test1():this
         -20 (-5.62% of base) : 311365.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector3Test1():this
         -20 (-5.32% of base) : 311362.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector4Test1():this
          -8 (-1.79% of base) : 125232.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.CSharpTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -8 (-1.52% of base) : 128938.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.VisualBasicTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
         -20 (-1.50% of base) : 128409.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGeneration.VisualBasicSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
         -20 (-1.44% of base) : 126321.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
          -4 (-0.67% of base) : 2129.dasm - Roslyn.Utilities.SyntaxPath:TryResolve(Microsoft.CodeAnalysis.SyntaxNode,byref):bool:this
          -4 (-0.36% of base) : 338164.dasm - System.Threading.Tasks.Tests.ValueTaskTests:Generic_CreateFromSuccessfullyCompleted_IsCompletedSuccessfully(int):this
         -16 (-0.34% of base) : 311444.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2EqualsNanTest():this
         -16 (-0.17% of base) : 326541.dasm - System.Numerics.Tests.ComparisonTest:RunPositiveTests(System.Random)
          -4 (-0.16% of base) : 16356.dasm - <FindReferencesThroughAliasSymbolsAsync>d__26:MoveNext():this

13 total methods with Code Size differences (13 improved, 0 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

