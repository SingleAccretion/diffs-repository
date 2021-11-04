## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 5760924 (overridden on cmd)
Total bytes of diff: 5760689 (overridden on cmd)
Total bytes of delta: -235 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -148 : 4470.dasm (-7.95% of base)
         -42 : 4486.dasm (-5.36% of base)
         -27 : 4479.dasm (-6.94% of base)
         -18 : 16958.dasm (-0.46% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -148 (-7.95% of base) : 4470.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -42 (-5.36% of base) : 4486.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -27 (-6.94% of base) : 4479.dasm - System.Diagnostics.ActivityCreationOptions`1[ActivityContext][System.Diagnostics.ActivityContext]:.ctor(System.Diagnostics.ActivitySource,System.String,System.Diagnostics.ActivityContext,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -18 (-0.46% of base) : 16958.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckValueKind(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ushort,bool,Microsoft.CodeAnalysis.DiagnosticBag):bool:this

Top method improvements (percentages):
        -148 (-7.95% of base) : 4470.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -27 (-6.94% of base) : 4479.dasm - System.Diagnostics.ActivityCreationOptions`1[ActivityContext][System.Diagnostics.ActivityContext]:.ctor(System.Diagnostics.ActivitySource,System.String,System.Diagnostics.ActivityContext,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -42 (-5.36% of base) : 4486.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -18 (-0.46% of base) : 16958.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckValueKind(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,ushort,bool,Microsoft.CodeAnalysis.DiagnosticBag):bool:this

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 111079340 (overridden on cmd)
Total bytes of diff: 111073884 (overridden on cmd)
Total bytes of delta: -5456 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           1 : 89109.dasm (0.44% of base)

Top file improvements (bytes):
        -704 : 152449.dasm (-6.15% of base)
        -662 : 154858.dasm (-5.97% of base)
        -424 : 154203.dasm (-2.70% of base)
        -338 : 217586.dasm (-1.36% of base)
        -328 : 192187.dasm (-33.33% of base)
        -305 : 217580.dasm (-1.22% of base)
        -216 : 192153.dasm (-32.43% of base)
        -214 : 192184.dasm (-31.75% of base)
        -204 : 192178.dasm (-23.02% of base)
        -192 : 192149.dasm (-29.09% of base)
        -190 : 192166.dasm (-34.11% of base)
        -180 : 192148.dasm (-24.10% of base)
        -143 : 192177.dasm (-12.48% of base)
        -139 : 192172.dasm (-36.20% of base)
         -91 : 217708.dasm (-0.36% of base)
         -91 : 217714.dasm (-0.36% of base)
         -71 : 217697.dasm (-0.28% of base)
         -71 : 217691.dasm (-0.28% of base)
         -71 : 217752.dasm (-0.28% of base)
         -71 : 217746.dasm (-0.28% of base)

48 total files with Code Size differences (47 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           1 ( 0.44% of base) : 89109.dasm - X:Main():int

Top method improvements (bytes):
        -704 (-6.15% of base) : 152449.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -662 (-5.97% of base) : 154858.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -424 (-2.70% of base) : 154203.dasm - testout1:Func_0_4_5_4():System.Decimal
        -338 (-1.36% of base) : 217586.dasm - r4NaNadd:Main():int
        -328 (-33.33% of base) : 192187.dasm - testout1:Func_0_5_2():double
        -305 (-1.22% of base) : 217580.dasm - r4NaNadd:Main():int
        -216 (-32.43% of base) : 192153.dasm - testout1:Func_0_1_9():long
        -214 (-31.75% of base) : 192184.dasm - testout1:Func_0_5_5():long
        -204 (-23.02% of base) : 192178.dasm - testout1:Func_0_6_4():long
        -192 (-29.09% of base) : 192149.dasm - testout1:Func_0_2_4():double
        -190 (-34.11% of base) : 192166.dasm - testout1:Func_0_8_3():double
        -180 (-24.10% of base) : 192148.dasm - testout1:Func_0_2_5():short
        -143 (-12.48% of base) : 192177.dasm - testout1:Func_0_6_5():long
        -139 (-36.20% of base) : 192172.dasm - testout1:Func_0_7_5():double
         -91 (-0.36% of base) : 217708.dasm - r8NaNmul:Main():int
         -91 (-0.36% of base) : 217714.dasm - r8NaNmul:Main():int
         -71 (-0.28% of base) : 217697.dasm - r8NaNdiv:Main():int
         -71 (-0.28% of base) : 217691.dasm - r8NaNdiv:Main():int
         -71 (-0.28% of base) : 217752.dasm - r8NaNsub:Main():int
         -71 (-0.28% of base) : 217746.dasm - r8NaNsub:Main():int

Top method regressions (percentages):
           1 ( 0.44% of base) : 89109.dasm - X:Main():int

Top method improvements (percentages):
         -35 (-92.11% of base) : 248905.dasm - Runtime_45090.ProbeBeforeSubSp1:VirtMethodEspBasedFrame():int:this
         -35 (-92.11% of base) : 248906.dasm - Runtime_45090.ProbeBeforeSubSp2:VirtMethodEspBasedFrame():int:this
         -35 (-92.11% of base) : 248907.dasm - Runtime_45090.ProbeBeforeSubSp3:VirtMethodEspBasedFrame():int:this
         -35 (-92.11% of base) : 248908.dasm - Runtime_45090.ProbeBeforeSubSp4:VirtMethodEspBasedFrame():int:this
         -35 (-92.11% of base) : 248909.dasm - Runtime_45090.ProbeBeforeSubSp5:VirtMethodEspBasedFrame():int:this
         -30 (-90.91% of base) : 248904.dasm - Runtime_45090.ProbeAfterSubSp:VirtMethodEspBasedFrame():int:this
         -27 (-90.00% of base) : 248903.dasm - Runtime_45090.SubSp:VirtMethodEspBasedFrame():int:this
         -36 (-80.00% of base) : 86408.dasm - Runtime_55141:Run(long):int
         -49 (-59.76% of base) : 86405.dasm - Runtime_55141_2:Main():int
        -139 (-36.20% of base) : 192172.dasm - testout1:Func_0_7_5():double
        -190 (-34.11% of base) : 192166.dasm - testout1:Func_0_8_3():double
        -328 (-33.33% of base) : 192187.dasm - testout1:Func_0_5_2():double
        -216 (-32.43% of base) : 192153.dasm - testout1:Func_0_1_9():long
        -214 (-31.75% of base) : 192184.dasm - testout1:Func_0_5_5():long
          -5 (-29.41% of base) : 86466.dasm - Runtime_57912:test_0_17(int,AA,AA):short
        -192 (-29.09% of base) : 192149.dasm - testout1:Func_0_2_4():double
        -180 (-24.10% of base) : 192148.dasm - testout1:Func_0_2_5():short
        -204 (-23.02% of base) : 192178.dasm - testout1:Func_0_6_4():long
         -56 (-19.18% of base) : 166003.dasm - NativeVarargTest.VarArg:TestEchoSixteenByteStructManagedNoVararg():bool
         -56 (-19.18% of base) : 166036.dasm - NativeVarargTest.VarArg:TestEchoSixteenByteStructNoVararg():bool

48 total methods with Code Size differences (47 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 36001024 (overridden on cmd)
Total bytes of diff: 36000723 (overridden on cmd)
Total bytes of delta: -301 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -116 : 186416.dasm (-6.30% of base)
         -42 : 186204.dasm (-5.36% of base)
         -30 : 186370.dasm (-11.11% of base)
         -27 : 186374.dasm (-4.88% of base)
         -12 : 53213.dasm (-0.19% of base)
         -11 : 152645.dasm (-0.72% of base)
         -10 : 174348.dasm (-7.04% of base)
          -7 : 151610.dasm (-1.95% of base)
          -6 : 49482.dasm (-0.08% of base)
          -6 : 49477.dasm (-0.10% of base)
          -6 : 49299.dasm (-0.10% of base)
          -6 : 49257.dasm (-0.10% of base)
          -6 : 49332.dasm (-0.11% of base)
          -4 : 160560.dasm (-0.22% of base)
          -3 : 49487.dasm (-0.02% of base)
          -3 : 78887.dasm (-0.79% of base)
          -3 : 78856.dasm (-1.01% of base)
          -3 : 78889.dasm (-1.07% of base)

18 total files with Code Size differences (18 improved, 0 regressed), 7 unchanged.

Top method improvements (bytes):
        -116 (-6.30% of base) : 186416.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -42 (-5.36% of base) : 186204.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -30 (-11.11% of base) : 186370.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
         -27 (-4.88% of base) : 186374.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -12 (-0.19% of base) : 53213.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberMethodSymbol:BindSingleHandlesClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.HandlesClauseItemSyntax,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):Microsoft.CodeAnalysis.VisualBasic.HandledEvent:this
         -11 (-0.72% of base) : 152645.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
         -10 (-7.04% of base) : 174348.dasm - <>c:<ToString>b__18_0(System.Span`1[Char],System.Collections.Specialized.BitVector32):this
          -7 (-1.95% of base) : 151610.dasm - System.Text.Json.JsonDocument:<CreateForLiteral>g__Create|73_0(System.Byte[],byref):System.Text.Json.JsonDocument
          -6 (-0.10% of base) : 49477.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindObjectCreationExpression(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.VisualBasic.BoundObjectInitializerExpressionBase,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-0.11% of base) : 49332.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindRaiseEventStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.RaiseEventStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
          -6 (-0.10% of base) : 49257.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
          -6 (-0.10% of base) : 49299.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:InterpretForEachStatementCollection(Microsoft.CodeAnalysis.VisualBasic.BoundExpression,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-0.08% of base) : 49482.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureAndProduceBoundNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,Microsoft.CodeAnalysis.ArrayBuilder`1[CandidateAnalysisResult],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.Location):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -4 (-0.22% of base) : 160560.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
          -3 (-0.79% of base) : 78887.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -3 (-1.07% of base) : 78889.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -3 (-1.01% of base) : 78856.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -3 (-0.02% of base) : 49487.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureForASingleCandidate(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.Location,int,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,bool,bool,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbol):this

Top method improvements (percentages):
         -30 (-11.11% of base) : 186370.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
         -10 (-7.04% of base) : 174348.dasm - <>c:<ToString>b__18_0(System.Span`1[Char],System.Collections.Specialized.BitVector32):this
        -116 (-6.30% of base) : 186416.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -42 (-5.36% of base) : 186204.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -27 (-4.88% of base) : 186374.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
          -7 (-1.95% of base) : 151610.dasm - System.Text.Json.JsonDocument:<CreateForLiteral>g__Create|73_0(System.Byte[],byref):System.Text.Json.JsonDocument
          -3 (-1.07% of base) : 78889.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -3 (-1.01% of base) : 78856.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -3 (-0.79% of base) : 78887.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
         -11 (-0.72% of base) : 152645.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
          -4 (-0.22% of base) : 160560.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
         -12 (-0.19% of base) : 53213.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberMethodSymbol:BindSingleHandlesClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.HandlesClauseItemSyntax,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):Microsoft.CodeAnalysis.VisualBasic.HandledEvent:this
          -6 (-0.11% of base) : 49332.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindRaiseEventStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.RaiseEventStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
          -6 (-0.10% of base) : 49299.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:InterpretForEachStatementCollection(Microsoft.CodeAnalysis.VisualBasic.BoundExpression,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-0.10% of base) : 49257.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
          -6 (-0.10% of base) : 49477.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindObjectCreationExpression(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.VisualBasic.BoundObjectInitializerExpressionBase,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-0.08% of base) : 49482.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureAndProduceBoundNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,Microsoft.CodeAnalysis.ArrayBuilder`1[CandidateAnalysisResult],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.Location):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -3 (-0.02% of base) : 49487.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureForASingleCandidate(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.Location,int,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,bool,bool,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbol):this

18 total methods with Code Size differences (18 improved, 0 regressed), 7 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 86291266 (overridden on cmd)
Total bytes of diff: 86291028 (overridden on cmd)
Total bytes of delta: -238 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -80 : 341523.dasm (-27.68% of base)
         -34 : 326451.dasm (-0.27% of base)
         -28 : 311362.dasm (-0.46% of base)
         -15 : 311288.dasm (-3.79% of base)
         -15 : 311291.dasm (-3.99% of base)
         -15 : 311294.dasm (-4.41% of base)
         -12 : 126264.dasm (-1.17% of base)
         -12 : 128349.dasm (-0.99% of base)
          -9 : 311595.dasm (-3.59% of base)
          -5 : 338027.dasm (-0.63% of base)
          -5 : 16344.dasm (-0.27% of base)
          -3 : 128875.dasm (-0.74% of base)
          -3 : 125174.dasm (-1.11% of base)
          -1 : 94790.dasm (-0.20% of base)
          -1 : 2119.dasm (-0.21% of base)

15 total files with Code Size differences (15 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -80 (-27.68% of base) : 341523.dasm - System.Tests.ExtensionsTests:ConvertToRef8()
         -34 (-0.27% of base) : 326451.dasm - System.Numerics.Tests.ComparisonTest:RunPositiveTests(System.Random)
         -28 (-0.46% of base) : 311362.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2EqualsNanTest():this
         -15 (-4.41% of base) : 311294.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector2Test1():this
         -15 (-3.99% of base) : 311291.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector3Test1():this
         -15 (-3.79% of base) : 311288.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector4Test1():this
         -12 (-1.17% of base) : 126264.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
         -12 (-0.99% of base) : 128349.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGeneration.VisualBasicSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
          -9 (-3.59% of base) : 311595.dasm - System.Numerics.Tests.QuaternionTests:QuaternionConstructorTest1():this
          -5 (-0.27% of base) : 16344.dasm - <FindReferencesThroughAliasSymbolsAsync>d__26:MoveNext():this
          -5 (-0.63% of base) : 338027.dasm - System.Threading.Tasks.Tests.ValueTaskTests:Generic_CreateFromSuccessfullyCompleted_IsCompletedSuccessfully(int):this
          -3 (-1.11% of base) : 125174.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.CSharpTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -3 (-0.74% of base) : 128875.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.VisualBasicTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -1 (-0.21% of base) : 2119.dasm - Roslyn.Utilities.SyntaxPath:TryResolve(Microsoft.CodeAnalysis.SyntaxNode,byref):bool:this
          -1 (-0.20% of base) : 94790.dasm - System.Text.Json.Tests.JsonDocumentTests:DefaultArrayEnumeratorDoesNotThrow()

Top method improvements (percentages):
         -80 (-27.68% of base) : 341523.dasm - System.Tests.ExtensionsTests:ConvertToRef8()
         -15 (-4.41% of base) : 311294.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector2Test1():this
         -15 (-3.99% of base) : 311291.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector3Test1():this
         -15 (-3.79% of base) : 311288.dasm - System.Numerics.Tests.Vector4Tests:Vector4TransformVector4Test1():this
          -9 (-3.59% of base) : 311595.dasm - System.Numerics.Tests.QuaternionTests:QuaternionConstructorTest1():this
         -12 (-1.17% of base) : 126264.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
          -3 (-1.11% of base) : 125174.dasm - Microsoft.CodeAnalysis.CSharp.Formatting.CSharpTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
         -12 (-0.99% of base) : 128349.dasm - Microsoft.CodeAnalysis.VisualBasic.CodeGeneration.VisualBasicSyntaxGenerator:DocumentationCommentTrivia(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTriviaList,Microsoft.CodeAnalysis.SyntaxTrivia,System.String):Microsoft.CodeAnalysis.SyntaxNode:this
          -3 (-0.74% of base) : 128875.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.VisualBasicTriviaFormatter:CreateEndOfLine():Microsoft.CodeAnalysis.SyntaxTrivia:this
          -5 (-0.63% of base) : 338027.dasm - System.Threading.Tasks.Tests.ValueTaskTests:Generic_CreateFromSuccessfullyCompleted_IsCompletedSuccessfully(int):this
         -28 (-0.46% of base) : 311362.dasm - System.Numerics.Tests.Matrix3x2Tests:Matrix3x2EqualsNanTest():this
          -5 (-0.27% of base) : 16344.dasm - <FindReferencesThroughAliasSymbolsAsync>d__26:MoveNext():this
         -34 (-0.27% of base) : 326451.dasm - System.Numerics.Tests.ComparisonTest:RunPositiveTests(System.Random)
          -1 (-0.21% of base) : 2119.dasm - Roslyn.Utilities.SyntaxPath:TryResolve(Microsoft.CodeAnalysis.SyntaxNode,byref):bool:this
          -1 (-0.20% of base) : 94790.dasm - System.Text.Json.Tests.JsonDocumentTests:DefaultArrayEnumeratorDoesNotThrow()

15 total methods with Code Size differences (15 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

