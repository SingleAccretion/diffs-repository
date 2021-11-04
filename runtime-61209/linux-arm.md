## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 161234818 (overridden on cmd)
Total bytes of diff: 161233082 (overridden on cmd)
Total bytes of delta: -1736 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -302 : 105043.dasm (-4.44% of base)
        -300 : 119392.dasm (-4.34% of base)
        -182 : 177290.dasm (-17.98% of base)
        -166 : 177296.dasm (-21.73% of base)
        -150 : 177289.dasm (-11.66% of base)
        -132 : 177261.dasm (-19.53% of base)
         -86 : 104129.dasm (-0.94% of base)
         -44 : 118737.dasm (-0.48% of base)
         -38 : 248804.dasm (-79.17% of base)
         -38 : 248807.dasm (-79.17% of base)
         -38 : 248806.dasm (-79.17% of base)
         -38 : 248803.dasm (-79.17% of base)
         -38 : 248805.dasm (-79.17% of base)
         -32 : 104353.dasm (-0.44% of base)
         -30 : 83416.dasm (-36.59% of base)
         -26 : 248802.dasm (-81.25% of base)
         -22 : 248801.dasm (-78.57% of base)
         -22 : 83723.dasm (-40.74% of base)
         -18 : 239298.dasm (-5.20% of base)
         -10 : 83509.dasm (-6.25% of base)

25 total files with Code Size differences (25 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -302 (-4.44% of base) : 105043.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -300 (-4.34% of base) : 119392.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -182 (-17.98% of base) : 177290.dasm - testout1:Func_0_6_4():long
        -166 (-21.73% of base) : 177296.dasm - testout1:Func_0_5_5():long
        -150 (-11.66% of base) : 177289.dasm - testout1:Func_0_6_5():long
        -132 (-19.53% of base) : 177261.dasm - testout1:Func_0_2_4():double
         -86 (-0.94% of base) : 104129.dasm - testout1:Func_0_4_5_4():System.Decimal
         -44 (-0.48% of base) : 118737.dasm - testout1:Func_0_4_5_4():System.Decimal
         -38 (-79.17% of base) : 248803.dasm - Runtime_45090.ProbeBeforeSubSp1:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248804.dasm - Runtime_45090.ProbeBeforeSubSp2:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248805.dasm - Runtime_45090.ProbeBeforeSubSp3:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248806.dasm - Runtime_45090.ProbeBeforeSubSp4:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248807.dasm - Runtime_45090.ProbeBeforeSubSp5:VirtMethodEspBasedFrame():int:this
         -32 (-0.44% of base) : 104353.dasm - testout1:Func_0_1_6_6_1():System.Decimal
         -30 (-36.59% of base) : 83416.dasm - Runtime_55141_2:Main():int
         -26 (-81.25% of base) : 248802.dasm - Runtime_45090.ProbeAfterSubSp:VirtMethodEspBasedFrame():int:this
         -22 (-78.57% of base) : 248801.dasm - Runtime_45090.SubSp:VirtMethodEspBasedFrame():int:this
         -22 (-40.74% of base) : 83723.dasm - Runtime_55141:Run(long):int
         -18 (-5.20% of base) : 239298.dasm - Program:Test25()
         -10 (-6.25% of base) : 83509.dasm - Program:Test():int

Top method improvements (percentages):
         -26 (-81.25% of base) : 248802.dasm - Runtime_45090.ProbeAfterSubSp:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248803.dasm - Runtime_45090.ProbeBeforeSubSp1:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248804.dasm - Runtime_45090.ProbeBeforeSubSp2:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248805.dasm - Runtime_45090.ProbeBeforeSubSp3:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248806.dasm - Runtime_45090.ProbeBeforeSubSp4:VirtMethodEspBasedFrame():int:this
         -38 (-79.17% of base) : 248807.dasm - Runtime_45090.ProbeBeforeSubSp5:VirtMethodEspBasedFrame():int:this
         -22 (-78.57% of base) : 248801.dasm - Runtime_45090.SubSp:VirtMethodEspBasedFrame():int:this
         -22 (-40.74% of base) : 83723.dasm - Runtime_55141:Run(long):int
         -30 (-36.59% of base) : 83416.dasm - Runtime_55141_2:Main():int
          -8 (-28.57% of base) : 84248.dasm - Runtime_57912:test_0_17(int,AA,AA):short
        -166 (-21.73% of base) : 177296.dasm - testout1:Func_0_5_5():long
        -132 (-19.53% of base) : 177261.dasm - testout1:Func_0_2_4():double
        -182 (-17.98% of base) : 177290.dasm - testout1:Func_0_6_4():long
        -150 (-11.66% of base) : 177289.dasm - testout1:Func_0_6_5():long
         -10 (-6.25% of base) : 83509.dasm - Program:Test():int
         -18 (-5.20% of base) : 239298.dasm - Program:Test25()
        -302 (-4.44% of base) : 105043.dasm - testout1:Func_0_5_5_5_6():System.Decimal
        -300 (-4.34% of base) : 119392.dasm - testout1:Func_0_5_5_5_6():System.Decimal
          -4 (-2.78% of base) : 249733.dasm - A:Test(B):int:this
          -4 (-2.78% of base) : 249734.dasm - B:Test(A):int:this

25 total methods with Code Size differences (25 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 36670612 (overridden on cmd)
Total bytes of diff: 36670600 (overridden on cmd)
Total bytes of delta: -12 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -6 : 43395.dasm (-0.50% of base)
          -2 : 68492.dasm (-0.50% of base)
          -2 : 177765.dasm (-0.10% of base)
          -2 : 68496.dasm (-0.52% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -6 (-0.50% of base) : 43395.dasm - Microsoft.CodeAnalysis.CSharp.LambdaRewriter:GetStaticFrame(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.BoundNode):Microsoft.CodeAnalysis.CSharp.LambdaFrame:this
          -2 (-0.10% of base) : 177765.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,Internal.TypeSystem.MetadataVirtualMethodAlgorithm+UnificationGroup)
          -2 (-0.52% of base) : 68496.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.50% of base) : 68492.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this

Top method improvements (percentages):
          -2 (-0.52% of base) : 68496.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -6 (-0.50% of base) : 43395.dasm - Microsoft.CodeAnalysis.CSharp.LambdaRewriter:GetStaticFrame(Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.BoundNode):Microsoft.CodeAnalysis.CSharp.LambdaFrame:this
          -2 (-0.50% of base) : 68492.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.10% of base) : 177765.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,Internal.TypeSystem.MetadataVirtualMethodAlgorithm+UnificationGroup)

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 40196036 (overridden on cmd)
Total bytes of diff: 40195922 (overridden on cmd)
Total bytes of delta: -114 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          12 : 2823.dasm (0.23% of base)
           6 : 2459.dasm (0.14% of base)
           6 : 2701.dasm (0.09% of base)
           6 : 2428.dasm (0.11% of base)
           4 : 2386.dasm (0.08% of base)
           4 : 2461.dasm (0.08% of base)
           4 : 2858.dasm (0.13% of base)
           4 : 6442.dasm (0.06% of base)
           2 : 2611.dasm (0.03% of base)
           2 : 2819.dasm (0.05% of base)
           2 : 2677.dasm (0.06% of base)
           2 : 2370.dasm (0.07% of base)
           2 : 2499.dasm (0.04% of base)

Top file improvements (bytes):
         -72 : 200270.dasm (-4.23% of base)
         -26 : 200221.dasm (-8.28% of base)
         -24 : 200054.dasm (-2.52% of base)
         -24 : 200226.dasm (-3.74% of base)
          -8 : 171497.dasm (-4.76% of base)
          -4 : 127903.dasm (-0.25% of base)
          -2 : 154802.dasm (-0.53% of base)
          -2 : 126855.dasm (-0.50% of base)
          -2 : 94812.dasm (-0.12% of base)
          -2 : 154832.dasm (-0.48% of base)
          -2 : 154834.dasm (-0.55% of base)
          -2 : 2616.dasm (-0.02% of base)

25 total files with Code Size differences (12 improved, 13 regressed), 0 unchanged.

Top method regressions (bytes):
          12 ( 0.23% of base) : 2823.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportNoConversionError(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag,System.String):this
           6 ( 0.14% of base) : 2459.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAddRemoveHandlerStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.AddRemoveHandlerStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundAddRemoveHandlerStatement:this
           6 ( 0.09% of base) : 2701.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindSymbolAccess(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.LookupResult,int,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeArgumentListSyntax,int,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           6 ( 0.11% of base) : 2428.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:InterpretForEachStatementCollection(Microsoft.CodeAnalysis.VisualBasic.BoundExpression,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           4 ( 0.08% of base) : 2461.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindRaiseEventStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.RaiseEventStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
           4 ( 0.13% of base) : 2858.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindTypeParameterConstraint(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ConstraintSyntax,byref,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterConstraint],Microsoft.CodeAnalysis.DiagnosticBag):this
           4 ( 0.08% of base) : 2386.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
           4 ( 0.06% of base) : 6442.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberMethodSymbol:BindSingleHandlesClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.HandlesClauseItemSyntax,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):Microsoft.CodeAnalysis.VisualBasic.HandledEvent:this
           2 ( 0.06% of base) : 2677.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindArrayInitializerList(Microsoft.CodeAnalysis.VisualBasic.Syntax.CollectionInitializerSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.ArrayTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize[],int,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundArrayInitialization:this
           2 ( 0.04% of base) : 2499.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindVariableDeclaration(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.ModifiedIdentifierSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.AsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.EqualsValueSyntax,Microsoft.CodeAnalysis.DiagnosticBag,bool):Microsoft.CodeAnalysis.VisualBasic.BoundLocalDeclaration:this
           2 ( 0.07% of base) : 2370.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeModifiedIdentifierType(Microsoft.CodeAnalysis.VisualBasic.Syntax.ModifiedIdentifierSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.AsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,System.Func`1[[Microsoft.CodeAnalysis.DiagnosticInfo, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol:this
           2 ( 0.05% of base) : 2819.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReclassifyQueryLambdaExpression(Microsoft.CodeAnalysis.VisualBasic.BoundQueryLambda,ushort,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           2 ( 0.03% of base) : 2611.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureAndProduceBoundNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,Microsoft.CodeAnalysis.ArrayBuilder`1[CandidateAnalysisResult],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.Location):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method improvements (bytes):
         -72 (-4.23% of base) : 200270.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -26 (-8.28% of base) : 200221.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
         -24 (-2.52% of base) : 200054.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
         -24 (-3.74% of base) : 200226.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
          -8 (-4.76% of base) : 171497.dasm - <>c:<ToString>b__18_0(System.Span`1[Char],System.Collections.Specialized.BitVector32):this
          -4 (-0.25% of base) : 127903.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
          -2 (-0.12% of base) : 94812.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
          -2 (-0.48% of base) : 154832.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.55% of base) : 154834.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.53% of base) : 154802.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.02% of base) : 2616.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureForASingleCandidate(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.Location,int,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,bool,bool,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbol):this
          -2 (-0.50% of base) : 126855.dasm - System.Text.Json.JsonDocument:<CreateForLiteral>g__Create|73_0(System.Byte[],byref):System.Text.Json.JsonDocument

Top method regressions (percentages):
          12 ( 0.23% of base) : 2823.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportNoConversionError(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag,System.String):this
           6 ( 0.14% of base) : 2459.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAddRemoveHandlerStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.AddRemoveHandlerStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundAddRemoveHandlerStatement:this
           4 ( 0.13% of base) : 2858.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindTypeParameterConstraint(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ConstraintSyntax,byref,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterConstraint],Microsoft.CodeAnalysis.DiagnosticBag):this
           6 ( 0.11% of base) : 2428.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:InterpretForEachStatementCollection(Microsoft.CodeAnalysis.VisualBasic.BoundExpression,byref,byref,byref,byref,byref,byref,byref,byref,byref,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           6 ( 0.09% of base) : 2701.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindSymbolAccess(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.LookupResult,int,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Syntax.TypeArgumentListSyntax,int,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           4 ( 0.08% of base) : 2386.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeParameterList(Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,int,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],CheckParameterModifierDelegate,Microsoft.CodeAnalysis.DiagnosticBag):this
           4 ( 0.08% of base) : 2461.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindRaiseEventStatement(Microsoft.CodeAnalysis.VisualBasic.Syntax.RaiseEventStatementSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
           2 ( 0.07% of base) : 2370.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:DecodeModifiedIdentifierType(Microsoft.CodeAnalysis.VisualBasic.Syntax.ModifiedIdentifierSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.AsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,System.Func`1[[Microsoft.CodeAnalysis.DiagnosticInfo, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag,int):Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol:this
           4 ( 0.06% of base) : 6442.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMemberMethodSymbol:BindSingleHandlesClause(Microsoft.CodeAnalysis.VisualBasic.Syntax.HandlesClauseItemSyntax,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref):Microsoft.CodeAnalysis.VisualBasic.HandledEvent:this
           2 ( 0.06% of base) : 2677.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindArrayInitializerList(Microsoft.CodeAnalysis.VisualBasic.Syntax.CollectionInitializerSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.ArrayTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Binder+DimensionSize[],int,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundArrayInitialization:this
           2 ( 0.05% of base) : 2819.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReclassifyQueryLambdaExpression(Microsoft.CodeAnalysis.VisualBasic.BoundQueryLambda,ushort,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
           2 ( 0.04% of base) : 2499.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindVariableDeclaration(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.ModifiedIdentifierSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.AsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.EqualsValueSyntax,Microsoft.CodeAnalysis.DiagnosticBag,bool):Microsoft.CodeAnalysis.VisualBasic.BoundLocalDeclaration:this
           2 ( 0.03% of base) : 2611.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureAndProduceBoundNode(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,int,Microsoft.CodeAnalysis.ArrayBuilder`1[CandidateAnalysisResult],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.Location):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method improvements (percentages):
         -26 (-8.28% of base) : 200221.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:get_TraceId():System.Diagnostics.ActivityTraceId:this
          -8 (-4.76% of base) : 171497.dasm - <>c:<ToString>b__18_0(System.Span`1[Char],System.Collections.Specialized.BitVector32):this
         -72 (-4.23% of base) : 200270.dasm - System.Diagnostics.ActivitySource:CreateActivity(System.String,int,System.Diagnostics.ActivityContext,System.String,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,bool,int):System.Diagnostics.Activity:this
         -24 (-3.74% of base) : 200226.dasm - System.Diagnostics.ActivityCreationOptions`1[__Canon][System.__Canon]:.ctor(System.Diagnostics.ActivitySource,System.String,System.__Canon,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],int):this
         -24 (-2.52% of base) : 200054.dasm - System.Diagnostics.Activity:Create(System.Diagnostics.ActivitySource,System.String,int,System.String,System.Diagnostics.ActivityContext,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[ActivityLink],System.DateTimeOffset,System.Diagnostics.ActivityTagsCollection,int,bool,int):System.Diagnostics.Activity
          -2 (-0.55% of base) : 154834.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Insert(int,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.53% of base) : 154802.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Replace(Microsoft.CodeAnalysis.SyntaxTrivia,Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -2 (-0.50% of base) : 126855.dasm - System.Text.Json.JsonDocument:<CreateForLiteral>g__Create|73_0(System.Byte[],byref):System.Text.Json.JsonDocument
          -2 (-0.48% of base) : 154832.dasm - Microsoft.CodeAnalysis.SyntaxTriviaList:Add(Microsoft.CodeAnalysis.SyntaxTrivia):Microsoft.CodeAnalysis.SyntaxTriviaList:this
          -4 (-0.25% of base) : 127903.dasm - <DisposePendingDisposablesOnExceptionAsync>d__22:MoveNext():this
          -2 (-0.12% of base) : 94812.dasm - Internal.TypeSystem.MetadataVirtualMethodAlgorithm:FindBaseUnificationGroup(Internal.TypeSystem.MetadataType,UnificationGroup)
          -2 (-0.02% of base) : 2616.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ReportOverloadResolutionFailureForASingleCandidate(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.Location,int,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,bool,bool,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.VisualBasic.Symbol,bool,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Symbol):this

25 total methods with Code Size differences (12 improved, 13 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

