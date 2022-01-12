## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 23623418 (overridden on cmd)
Total bytes of diff: 23623432 (overridden on cmd)
Total bytes of delta: 14 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          14 : 40699.dasm (1.32% of base)

1 total files with Code Size differences (0 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          14 ( 1.32% of base) : 40699.dasm - EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this

Top method regressions (percentages):
          14 ( 1.32% of base) : 40699.dasm - EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this

1 total methods with Code Size differences (0 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 127546366 (overridden on cmd)
Total bytes of diff: 127546416 (overridden on cmd)
Total bytes of delta: 50 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 112969.dasm (7.52% of base)
          10 : 238406.dasm (7.52% of base)
          10 : 112671.dasm (7.52% of base)
          10 : 225505.dasm (7.52% of base)
          10 : 225229.dasm (7.52% of base)

5 total files with Code Size differences (0 improved, 5 regressed), 0 unchanged.

Top method regressions (bytes):
          10 ( 7.52% of base) : 112969.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 238406.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 112671.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 225505.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 225229.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct

Top method regressions (percentages):
          10 ( 7.52% of base) : 112969.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 238406.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 112671.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 225505.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct
          10 ( 7.52% of base) : 225229.dasm - Helper:Create(WithMultipleGCHandleStruct):WithMultipleGCHandleStruct

5 total methods with Code Size differences (0 improved, 5 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 34449434 (overridden on cmd)
Total bytes of diff: 34449700 (overridden on cmd)
Total bytes of delta: 266 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         118 : 106925.dasm (2.03% of base)
          96 : 106895.dasm (3.64% of base)
          12 : 131306.dasm (1.32% of base)
          11 : 162988.dasm (10.19% of base)
          11 : 42876.dasm (0.51% of base)
          11 : 42938.dasm (1.02% of base)
          10 : 42923.dasm (0.82% of base)

Top file improvements (bytes):
          -3 : 131087.dasm (-0.10% of base)

8 total files with Code Size differences (1 improved, 7 regressed), 0 unchanged.

Top method regressions (bytes):
         118 ( 2.03% of base) : 106925.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindCompoundAssignment(Microsoft.CodeAnalysis.CSharp.Syntax.AssignmentExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          96 ( 3.64% of base) : 106895.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindIncrementOperator(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          12 ( 1.32% of base) : 131306.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this
          11 (10.19% of base) : 162988.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          11 ( 1.02% of base) : 42938.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this
          11 ( 0.51% of base) : 42876.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
          10 ( 0.82% of base) : 42923.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this

Top method improvements (bytes):
          -3 (-0.10% of base) : 131087.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this

Top method regressions (percentages):
          11 (10.19% of base) : 162988.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          96 ( 3.64% of base) : 106895.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindIncrementOperator(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         118 ( 2.03% of base) : 106925.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindCompoundAssignment(Microsoft.CodeAnalysis.CSharp.Syntax.AssignmentExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          12 ( 1.32% of base) : 131306.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this
          11 ( 1.02% of base) : 42938.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this
          10 ( 0.82% of base) : 42923.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this
          11 ( 0.51% of base) : 42876.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this

Top method improvements (percentages):
          -3 (-0.10% of base) : 131087.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this

8 total methods with Code Size differences (1 improved, 7 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 46220900 (overridden on cmd)
Total bytes of diff: 46220944 (overridden on cmd)
Total bytes of delta: 44 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          33 : 216531.dasm (0.91% of base)
          11 : 154165.dasm (7.01% of base)

2 total files with Code Size differences (0 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
          33 ( 0.91% of base) : 216531.dasm - System.Security.AccessControl.CommonAcl:RemoveQualifiedAces(System.Security.Principal.SecurityIdentifier,int,int,ubyte,bool,int,System.Guid,System.Guid):bool:this
          11 ( 7.01% of base) : 154165.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this

Top method regressions (percentages):
          11 ( 7.01% of base) : 154165.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          33 ( 0.91% of base) : 216531.dasm - System.Security.AccessControl.CommonAcl:RemoveQualifiedAces(System.Security.Principal.SecurityIdentifier,int,int,ubyte,bool,int,System.Guid,System.Guid):bool:this

2 total methods with Code Size differences (0 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 118080437 (overridden on cmd)
Total bytes of diff: 118080480 (overridden on cmd)
Total bytes of delta: 43 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          30 : 132453.dasm (1.07% of base)
          13 : 56449.dasm (10.40% of base)

2 total files with Code Size differences (0 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
          30 ( 1.07% of base) : 132453.dasm - Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbFile:LoadManagedLines(Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbFunction[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.Diagnostics.Runtime.Utilities.Pdb.BitAccess,Microsoft.Diagnostics.Runtime.Utilities.Pdb.MsfDirectory,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbStreamHelper,int,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbSource, Microsoft.Diagnostics.Runtime, Version=1.0.5.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]])
          13 (10.40% of base) : 56449.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_3():System.Object:this

Top method regressions (percentages):
          13 (10.40% of base) : 56449.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_3():System.Object:this
          30 ( 1.07% of base) : 132453.dasm - Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbFile:LoadManagedLines(Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbFunction[],System.Collections.Generic.Dictionary`2[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.Diagnostics.Runtime.Utilities.Pdb.BitAccess,Microsoft.Diagnostics.Runtime.Utilities.Pdb.MsfDirectory,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbStreamHelper,int,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Runtime.Utilities.Pdb.PdbSource, Microsoft.Diagnostics.Runtime, Version=1.0.5.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]])

2 total methods with Code Size differences (0 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

