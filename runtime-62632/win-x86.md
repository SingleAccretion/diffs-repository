## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 27766168 (overridden on cmd)
Total bytes of diff: 27766230 (overridden on cmd)
Total bytes of delta: 62 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          24 : 162971.dasm (1.07% of base)
          11 : 1626.dasm (0.82% of base)
          11 : 1641.dasm (0.93% of base)
          11 : 1579.dasm (0.67% of base)
           5 : 163190.dasm (0.82% of base)

5 total files with Code Size differences (0 improved, 5 regressed), 0 unchanged.

Top method regressions (bytes):
          24 ( 1.07% of base) : 162971.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
          11 ( 0.82% of base) : 1626.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,int,System.Object[]):this
          11 ( 0.93% of base) : 1641.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,int,int,int):this
          11 ( 0.67% of base) : 1579.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,int,int,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
           5 ( 0.82% of base) : 163190.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this

Top method regressions (percentages):
          24 ( 1.07% of base) : 162971.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
          11 ( 0.93% of base) : 1641.dasm - System.Diagnostics.Tracing.EventSource:WriteEventWithRelatedActivityIdCore(int,int,int,int):this
          11 ( 0.82% of base) : 1626.dasm - System.Diagnostics.Tracing.EventSource:WriteEventVarargs(int,int,System.Object[]):this
           5 ( 0.82% of base) : 163190.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAttributeArguments(Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentListSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.Binder+AnalyzedAttributeArguments:this
          11 ( 0.67% of base) : 1579.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,int,int,System.Diagnostics.Tracing.TraceLoggingEventTypes):this

5 total methods with Code Size differences (0 improved, 5 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

