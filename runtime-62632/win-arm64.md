## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 14930964 (overridden on cmd)
Total bytes of diff: 14930980 (overridden on cmd)
Total bytes of delta: 16 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 11453.dasm (0.69% of base)
           8 : 23974.dasm (0.60% of base)

2 total files with Code Size differences (0 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 0.60% of base) : 23974.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this
           8 ( 0.69% of base) : 11453.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this

Top method regressions (percentages):
           8 ( 0.69% of base) : 11453.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this
           8 ( 0.60% of base) : 23974.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this

2 total methods with Code Size differences (0 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 167949280 (overridden on cmd)
Total bytes of diff: 167949280 (overridden on cmd)
Total bytes of delta: 0 (0.00 % of base)
```
<details>

<summary>Detail diffs</summary>

```


0 total files with Code Size differences (0 improved, 0 regressed), 5 unchanged.

0 total methods with Code Size differences (0 improved, 0 regressed), 5 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51874016 (overridden on cmd)
Total bytes of diff: 51874272 (overridden on cmd)
Total bytes of delta: 256 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         116 : 146215.dasm (1.55% of base)
          76 : 146185.dasm (2.32% of base)
          20 : 21592.dasm (0.81% of base)
          12 : 96300.dasm (0.37% of base)
          12 : 96519.dasm (1.11% of base)
           8 : 21639.dasm (0.51% of base)
           8 : 21654.dasm (0.62% of base)
           4 : 157844.dasm (2.50% of base)

8 total files with Code Size differences (0 improved, 8 regressed), 0 unchanged.

Top method regressions (bytes):
         116 ( 1.55% of base) : 146215.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindCompoundAssignment(Microsoft.CodeAnalysis.CSharp.Syntax.AssignmentExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          76 ( 2.32% of base) : 146185.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindIncrementOperator(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          20 ( 0.81% of base) : 21592.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
          12 ( 1.11% of base) : 96519.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this
          12 ( 0.37% of base) : 96300.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
           8 ( 0.51% of base) : 21639.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this
           8 ( 0.62% of base) : 21654.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this
           4 ( 2.50% of base) : 157844.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this

Top method regressions (percentages):
           4 ( 2.50% of base) : 157844.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          76 ( 2.32% of base) : 146185.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindIncrementOperator(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         116 ( 1.55% of base) : 146215.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindCompoundAssignment(Microsoft.CodeAnalysis.CSharp.Syntax.AssignmentExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          12 ( 1.11% of base) : 96519.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this
          20 ( 0.81% of base) : 21592.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
           8 ( 0.62% of base) : 21654.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,long,int,long):this
           8 ( 0.51% of base) : 21639.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,long,System.Object[]):this
          12 ( 0.37% of base) : 96300.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this

8 total methods with Code Size differences (0 improved, 8 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 52177492 (overridden on cmd)
Total bytes of diff: 52177544 (overridden on cmd)
Total bytes of delta: 52 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          20 : 102651.dasm (13.89% of base)
          16 : 179483.dasm (0.61% of base)
          16 : 212195.dasm (0.53% of base)
           8 : 179484.dasm (0.53% of base)
           4 : 141399.dasm (2.17% of base)

Top file improvements (bytes):
         -12 : 84565.dasm (-9.68% of base)

6 total files with Code Size differences (1 improved, 5 regressed), 1 unchanged.

Top method regressions (bytes):
          20 (13.89% of base) : 102651.dasm - <>c:<InitializeFromFile>b__117_18():FastSerialization.IFastSerializable:this
          16 ( 0.53% of base) : 212195.dasm - System.Security.AccessControl.CommonAcl:RemoveQualifiedAces(System.Security.Principal.SecurityIdentifier,int,int,ubyte,bool,int,System.Guid,System.Guid):bool:this
          16 ( 0.61% of base) : 179483.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAccess(int,System.Security.AccessControl.ObjectAccessRule,byref):bool:this
           8 ( 0.53% of base) : 179484.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAudit(int,System.Security.AccessControl.ObjectAuditRule,byref):bool:this
           4 ( 2.17% of base) : 141399.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this

Top method improvements (bytes):
         -12 (-9.68% of base) : 84565.dasm - Microsoft.Diagnostics.Tracing.UnhandledTraceEvent:.ctor():this

Top method regressions (percentages):
          20 (13.89% of base) : 102651.dasm - <>c:<InitializeFromFile>b__117_18():FastSerialization.IFastSerializable:this
           4 ( 2.17% of base) : 141399.dasm - Internal.TypeSystem.UniversalCanonLayoutAlgorithm:ComputeInstanceLayout(Internal.TypeSystem.DefType,int):Internal.TypeSystem.ComputedInstanceFieldLayout:this
          16 ( 0.61% of base) : 179483.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAccess(int,System.Security.AccessControl.ObjectAccessRule,byref):bool:this
          16 ( 0.53% of base) : 212195.dasm - System.Security.AccessControl.CommonAcl:RemoveQualifiedAces(System.Security.Principal.SecurityIdentifier,int,int,ubyte,bool,int,System.Guid,System.Guid):bool:this
           8 ( 0.53% of base) : 179484.dasm - System.Security.AccessControl.DirectoryObjectSecurity:ModifyAudit(int,System.Security.AccessControl.ObjectAuditRule,byref):bool:this

Top method improvements (percentages):
         -12 (-9.68% of base) : 84565.dasm - Microsoft.Diagnostics.Tracing.UnhandledTraceEvent:.ctor():this

6 total methods with Code Size differences (1 improved, 5 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 121532712 (overridden on cmd)
Total bytes of diff: 121532780 (overridden on cmd)
Total bytes of delta: 68 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          36 : 156385.dasm (5.26% of base)
          28 : 55880.dasm (22.58% of base)
           4 : 55879.dasm (3.85% of base)

3 total files with Code Size differences (0 improved, 3 regressed), 1 unchanged.

Top method regressions (bytes):
          36 ( 5.26% of base) : 156385.dasm - System.Drawing.Printing.Tests.PreviewPrintControllerTests:OnStartPage_InvokeWithPrint_ReturnsNull():this
          28 (22.58% of base) : 55880.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_3():System.Object:this
           4 ( 3.85% of base) : 55879.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_2():System.Object:this

Top method regressions (percentages):
          28 (22.58% of base) : 55880.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_3():System.Object:this
          36 ( 5.26% of base) : 156385.dasm - System.Drawing.Printing.Tests.PreviewPrintControllerTests:OnStartPage_InvokeWithPrint_ReturnsNull():this
           4 ( 3.85% of base) : 55879.dasm - <>c:<SymbolDocument_NullFileName_ThrowsArgumentNullException>b__2_2():System.Object:this

3 total methods with Code Size differences (0 improved, 3 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

