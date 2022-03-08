## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 21740108 (overridden on cmd)
Total bytes of diff: 21738701 (overridden on cmd)
Total bytes of delta: -1407 (-0.01 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          72 : 42212.dasm (1.57% of base)
          72 : 54932.dasm (1.57% of base)
          23 : 42675.dasm (1.58% of base)
          23 : 39609.dasm (1.66% of base)
          20 : 55924.dasm (0.47% of base)
          20 : 62166.dasm (0.48% of base)
          19 : 27028.dasm (2.83% of base)
          18 : 51058.dasm (0.42% of base)
          18 : 64238.dasm (0.42% of base)
          18 : 35420.dasm (0.41% of base)
          18 : 58900.dasm (0.44% of base)
          16 : 38725.dasm (1.00% of base)
          11 : 39032.dasm (1.26% of base)
           8 : 66614.dasm (4.94% of base)
           8 : 17747.dasm (0.46% of base)
           7 : 67154.dasm (0.94% of base)
           7 : 28350.dasm (0.42% of base)
           6 : 5198.dasm (0.22% of base)
           5 : 42047.dasm (0.53% of base)
           5 : 40807.dasm (0.53% of base)

Top file improvements (bytes):
         -97 : 38741.dasm (-3.15% of base)
         -50 : 684.dasm (-11.04% of base)
         -49 : 63609.dasm (-2.71% of base)
         -49 : 50686.dasm (-2.71% of base)
         -49 : 35246.dasm (-2.70% of base)
         -47 : 63056.dasm (-0.98% of base)
         -44 : 11993.dasm (-0.87% of base)
         -36 : 11346.dasm (-0.82% of base)
         -36 : 6606.dasm (-0.79% of base)
         -34 : 39611.dasm (-1.11% of base)
         -32 : 61058.dasm (-0.76% of base)
         -29 : 57415.dasm (-0.69% of base)
         -29 : 683.dasm (-1.02% of base)
         -29 : 12015.dasm (-0.69% of base)
         -29 : 19394.dasm (-0.69% of base)
         -29 : 56584.dasm (-0.69% of base)
         -29 : 26472.dasm (-0.69% of base)
         -29 : 50766.dasm (-0.70% of base)
         -29 : 61924.dasm (-0.70% of base)
         -29 : 64205.dasm (-0.70% of base)

190 total files with Code Size differences (162 improved, 28 regressed), 242 unchanged.

Top method regressions (bytes):
          72 ( 1.57% of base) : 42212.dasm - SelectExpression:VisitChildren(ExpressionVisitor):Expression:this
          72 ( 1.57% of base) : 54932.dasm - SelectExpression:VisitChildren(ExpressionVisitor):Expression:this
          23 ( 1.58% of base) : 42675.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
          23 ( 1.66% of base) : 39609.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
          20 ( 0.47% of base) : 55924.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          20 ( 0.48% of base) : 62166.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          19 ( 2.83% of base) : 27028.dasm - ClusterDestinationsUpdater:UpdateInternal(ClusterState,IReadOnlyList`1,bool):this
          18 ( 0.42% of base) : 51058.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          18 ( 0.42% of base) : 64238.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          18 ( 0.41% of base) : 35420.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          18 ( 0.44% of base) : 58900.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          16 ( 1.00% of base) : 38725.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
          11 ( 1.26% of base) : 39032.dasm - <<FireOnCompleted>g__ProcessEvents|227_0>d:MoveNext():this
           8 ( 4.94% of base) : 66614.dasm - CompilerScope:Exit():CompilerScope:this
           8 ( 0.46% of base) : 17747.dasm - Pipe:AdvanceReader(BufferSegment,int,BufferSegment,int):this
           7 ( 0.94% of base) : 67154.dasm - <<FireOnStarting>g__ProcessEvents|226_0>d:MoveNext():this
           7 ( 0.42% of base) : 28350.dasm - ProxyConfigManager:UpdateRuntimeClusters(IEnumerable`1):this
           6 ( 0.22% of base) : 5198.dasm - <DoSend>d__28:MoveNext():this
           5 ( 0.53% of base) : 40807.dasm - Model:AddEntityType(EntityType):EntityType:this
           5 ( 0.53% of base) : 42047.dasm - NavigationExpandingExpressionVisitor:ApplyQueryFilter(IEntityType,NavigationExpansionExpression):Expression:this

Top method improvements (bytes):
         -97 (-3.15% of base) : 38741.dasm - <<Write>g__WriteExecute|94_0>d:MoveNext():this
         -50 (-11.04% of base) : 684.dasm - Pipe:GetReadResult(byref):this
         -49 (-2.71% of base) : 63609.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -49 (-2.71% of base) : 50686.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -49 (-2.70% of base) : 35246.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -47 (-0.98% of base) : 63056.dasm - CallSiteFactory:TryCreateEnumerable(Type,CallSiteChain):ServiceCallSite:this
         -44 (-0.87% of base) : 11993.dasm - <ProcessRequestsAsync>d__69:MoveNext():this
         -36 (-0.82% of base) : 11346.dasm - <ProcessRequestsAsync>d__69:MoveNext():this
         -36 (-0.79% of base) : 6606.dasm - <ProcessRequestsAsync>d__69:MoveNext():this
         -34 (-1.11% of base) : 39611.dasm - <<Write>g__WriteExecute|94_0>d:MoveNext():this
         -32 (-0.76% of base) : 61058.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.69% of base) : 57415.dasm - <DoSend>d__28:MoveNext():this
         -29 (-1.02% of base) : 683.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.69% of base) : 12015.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.69% of base) : 19394.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.69% of base) : 56584.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.69% of base) : 26472.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.70% of base) : 50766.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.70% of base) : 61924.dasm - <DoSend>d__28:MoveNext():this
         -29 (-0.70% of base) : 64205.dasm - <DoSend>d__28:MoveNext():this

Top method regressions (percentages):
           8 ( 4.94% of base) : 66614.dasm - CompilerScope:Exit():CompilerScope:this
          19 ( 2.83% of base) : 27028.dasm - ClusterDestinationsUpdater:UpdateInternal(ClusterState,IReadOnlyList`1,bool):this
          23 ( 1.66% of base) : 39609.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
          23 ( 1.58% of base) : 42675.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
          72 ( 1.57% of base) : 54932.dasm - SelectExpression:VisitChildren(ExpressionVisitor):Expression:this
          72 ( 1.57% of base) : 42212.dasm - SelectExpression:VisitChildren(ExpressionVisitor):Expression:this
          11 ( 1.26% of base) : 39032.dasm - <<FireOnCompleted>g__ProcessEvents|227_0>d:MoveNext():this
           4 ( 1.16% of base) : 41648.dasm - RuntimeModel:AddEntityType(String,Type,RuntimeEntityType,bool,String,int,PropertyInfo,bool):RuntimeEntityType:this
          16 ( 1.00% of base) : 38725.dasm - PreparedStatementManager:TryGetAutoPrepared(NpgsqlBatchCommand):PreparedStatement:this
           4 ( 0.99% of base) : 34635.dasm - LoggerFactory:CreateLogger(String):ILogger:this
           7 ( 0.94% of base) : 67154.dasm - <<FireOnStarting>g__ProcessEvents|226_0>d:MoveNext():this
           4 ( 0.59% of base) : 36502.dasm - <<FireOnStarting>g__ProcessEvents|226_0>d:MoveNext():this
           5 ( 0.53% of base) : 40807.dasm - Model:AddEntityType(EntityType):EntityType:this
           5 ( 0.53% of base) : 42047.dasm - NavigationExpandingExpressionVisitor:ApplyQueryFilter(IEntityType,NavigationExpansionExpression):Expression:this
           4 ( 0.52% of base) : 36537.dasm - <<FireOnCompleted>g__ProcessEvents|227_0>d:MoveNext():this
          20 ( 0.48% of base) : 62166.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          20 ( 0.47% of base) : 55924.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
           8 ( 0.46% of base) : 17747.dasm - Pipe:AdvanceReader(BufferSegment,int,BufferSegment,int):this
          18 ( 0.44% of base) : 58900.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this
          18 ( 0.42% of base) : 64238.dasm - SqlQueryParser:ParseRawQuery(NpgsqlCommand,NpgsqlBatchCommand,bool,bool):this

Top method improvements (percentages):
         -50 (-11.04% of base) : 684.dasm - Pipe:GetReadResult(byref):this
         -18 (-6.32% of base) : 25270.dasm - HttpConnection:CheckUsabilityOnScavenge():bool:this
         -27 (-4.86% of base) : 35761.dasm - StreamPipeReader:ReadAsync(CancellationToken):ValueTask`1:this
         -97 (-3.15% of base) : 38741.dasm - <<Write>g__WriteExecute|94_0>d:MoveNext():this
         -23 (-3.14% of base) : 40592.dasm - NpgsqlCharacterCharTypeMapping:.ctor(String):this
         -23 (-3.14% of base) : 40632.dasm - NpgsqlHstoreTypeMapping:.ctor(Type):this
         -23 (-3.09% of base) : 40591.dasm - NpgsqlCharacterStringTypeMapping:.ctor(String,int):this
         -24 (-2.90% of base) : 583.dasm - Pipe:ReadAsync(CancellationToken):ValueTask`1:this
         -49 (-2.71% of base) : 63609.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -49 (-2.71% of base) : 50686.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -49 (-2.70% of base) : 35246.dasm - <InitializeReaderAsync>d__19:MoveNext():this
         -26 (-2.56% of base) : 39725.dasm - <CloseAllConnectionsAsync>d__7:MoveNext():this
         -24 (-2.49% of base) : 29701.dasm - HttpConnection:PrepareForReuse(bool):bool:this
         -24 (-2.37% of base) : 25253.dasm - HttpConnection:PrepareForReuse(bool):bool:this
          -3 (-2.24% of base) : 65387.dasm - Dictionary`2:FindValue(int):byref:this
          -3 (-2.24% of base) : 38587.dasm - Dictionary`2:FindValue(int):byref:this
          -2 (-2.06% of base) : 25803.dasm - IPAddressParser:Ipv4StringToAddress(ReadOnlySpan`1,byref):bool
          -2 (-2.06% of base) : 29496.dasm - IPAddressParser:Ipv4StringToAddress(ReadOnlySpan`1,byref):bool
          -2 (-2.06% of base) : 25126.dasm - IPAddressParser:Ipv4StringToAddress(ReadOnlySpan`1,byref):bool
          -2 (-2.06% of base) : 22887.dasm - IPAddressParser:Ipv4StringToAddress(ReadOnlySpan`1,byref):bool

190 total methods with Code Size differences (162 improved, 28 regressed), 242 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7685845 (overridden on cmd)
Total bytes of diff: 7684171 (overridden on cmd)
Total bytes of delta: -1674 (-0.02 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          54 : 25777.dasm (44.26% of base)
          26 : 18667.dasm (1.14% of base)
          15 : 18495.dasm (0.12% of base)
          14 : 19008.dasm (1.08% of base)
          13 : 13251.dasm (0.51% of base)
          11 : 18805.dasm (0.49% of base)
           8 : 17191.dasm (4.49% of base)
           8 : 17552.dasm (0.19% of base)
           7 : 20558.dasm (0.81% of base)
           6 : 18470.dasm (0.13% of base)
           5 : 11651.dasm (0.22% of base)
           5 : 21569.dasm (1.11% of base)
           5 : 8249.dasm (2.22% of base)
           5 : 11668.dasm (0.27% of base)
           5 : 28270.dasm (0.21% of base)
           4 : 11638.dasm (0.40% of base)
           4 : 5298.dasm (0.86% of base)
           4 : 3071.dasm (0.22% of base)
           4 : 26845.dasm (0.35% of base)
           2 : 28312.dasm (0.14% of base)

Top file improvements (bytes):
        -107 : 16035.dasm (-6.90% of base)
         -98 : 18614.dasm (-22.37% of base)
         -95 : 9401.dasm (-23.57% of base)
         -90 : 5177.dasm (-5.87% of base)
         -72 : 18561.dasm (-2.96% of base)
         -66 : 18610.dasm (-12.27% of base)
         -64 : 13934.dasm (-4.28% of base)
         -54 : 20742.dasm (-27.27% of base)
         -54 : 18913.dasm (-0.69% of base)
         -50 : 9468.dasm (-11.04% of base)
         -50 : 21030.dasm (-5.62% of base)
         -44 : 18810.dasm (-6.26% of base)
         -44 : 20762.dasm (-1.65% of base)
         -44 : 22379.dasm (-2.25% of base)
         -43 : 13267.dasm (-1.01% of base)
         -43 : 18620.dasm (-1.13% of base)
         -41 : 2515.dasm (-2.05% of base)
         -36 : 5637.dasm (-7.52% of base)
         -36 : 6555.dasm (-0.24% of base)
         -36 : 15046.dasm (-2.51% of base)

147 total files with Code Size differences (119 improved, 28 regressed), 119 unchanged.

Top method regressions (bytes):
          54 (44.26% of base) : 25777.dasm - System.Collections.IterateForEach`1[__Canon][System.__Canon]:ImmutableStack():System.__Canon:this
          26 ( 1.14% of base) : 18667.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:CheckAbstractClassImplementations(Microsoft.CodeAnalysis.DiagnosticBag):this
          15 ( 0.12% of base) : 18495.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):this
          14 ( 1.08% of base) : 19008.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          13 ( 0.51% of base) : 13251.dasm - DynamicClass:proto_8(byref,MicroBenchmarks.Serializers.MyEventsListerItem):MicroBenchmarks.Serializers.MyEventsListerItem
          11 ( 0.49% of base) : 18805.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:BindMethodBody(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.TypeCompilationState,Microsoft.CodeAnalysis.DiagnosticBag,byref,byref,byref):Microsoft.CodeAnalysis.CSharp.BoundBlock
           8 ( 0.19% of base) : 17552.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseMemberDeclarationOrStatement(ushort):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.MemberDeclarationSyntax:this
           8 ( 4.49% of base) : 17191.dasm - System.Formats.Cbor.CborWriter:Encode(System.Span`1[Byte]):int:this
           7 ( 0.81% of base) : 20558.dasm - System.Text.RegularExpressions.Regex:Split(System.Text.RegularExpressions.Regex,System.String,int,int):System.String[]
           6 ( 0.13% of base) : 18470.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamedTypeSymbol:MakeTypeParameters(Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
           5 ( 0.27% of base) : 11668.dasm - DynamicClass:proto_10(byref,MicroBenchmarks.Serializers.CampaignSummaryViewModel):MicroBenchmarks.Serializers.CampaignSummaryViewModel
           5 ( 0.21% of base) : 28270.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.Location):MicroBenchmarks.Serializers.Location
           5 ( 0.22% of base) : 11651.dasm - DynamicClass:proto_8(byref,MicroBenchmarks.Serializers.ActiveOrUpcomingEvent):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent
           5 ( 1.11% of base) : 21569.dasm - Newtonsoft.Json.Utilities.ReflectionUtils:GetCollectionItemType(System.Type):System.Type
           5 ( 2.22% of base) : 8249.dasm - System.Linq.Expressions.Compiler.CompilerScope:Exit():System.Linq.Expressions.Compiler.CompilerScope:this
           4 ( 0.40% of base) : 11638.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.IndexViewModel):MicroBenchmarks.Serializers.IndexViewModel
           4 ( 0.35% of base) : 26845.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.LoginViewModel):MicroBenchmarks.Serializers.LoginViewModel
           4 ( 0.86% of base) : 5298.dasm - Microsoft.Extensions.Logging.LoggerFactory:CreateLogger(System.String):Microsoft.Extensions.Logging.ILogger:this
           4 ( 0.22% of base) : 3071.dasm - System.Runtime.Serialization.DataContract:GetDefaultStableLocalName(System.Type):System.String
           2 ( 0.02% of base) : 22281.dasm - <ReceiveAsyncPrivate>d__63`1[ValueWebSocketReceiveResult][System.Net.WebSockets.ValueWebSocketReceiveResult]:MoveNext():this

Top method improvements (bytes):
        -107 (-6.90% of base) : 16035.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemTaskFormatter3:Deserialize(byref,Utf8Json.IJsonFormatterResolver):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
         -98 (-22.37% of base) : 18614.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.LookupPosition:IsInBody(int,Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax):bool
         -95 (-23.57% of base) : 9401.dasm - System.Diagnostics.DiagLinkedList`1[ActivityLink][System.Diagnostics.ActivityLink]:.ctor(System.Collections.Generic.IEnumerator`1[ActivityLink]):this
         -90 (-5.87% of base) : 5177.dasm - Microsoft.Extensions.DependencyInjection.ServiceProvider:.ctor(System.Collections.Generic.ICollection`1[[Microsoft.Extensions.DependencyInjection.ServiceDescriptor, Microsoft.Extensions.DependencyInjection.Abstractions, Version=7.0.0.0, Culture=neutral, PublicKeyToken=adb9793829ddae60]],Microsoft.Extensions.DependencyInjection.ServiceProviderOptions):this
         -72 (-2.96% of base) : 18561.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceOrdinaryMethodSymbol:.ctor(Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,System.String,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.CSharp.Syntax.MethodDeclarationSyntax,int,Microsoft.CodeAnalysis.DiagnosticBag):this
         -66 (-12.27% of base) : 18610.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.LookupPosition:IsInMethodDeclaration(int,Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax):bool
         -64 (-4.28% of base) : 13934.dasm - MessagePack.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemTaskFormatter3:Deserialize(System.Byte[],int,MessagePack.IFormatterResolver,byref):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
         -54 (-0.69% of base) : 18913.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldNeverOverflowBinaryOperators(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
         -54 (-27.27% of base) : 20742.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxTreeSemanticModel:AnalyzeDataFlow(Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax):Microsoft.CodeAnalysis.DataFlowAnalysis:this
         -50 (-5.62% of base) : 21030.dasm - Microsoft.Xml.Serialization.GeneratedAssembly.XmlSerializationReaderMyEventsListerViewModel:Read3_MyEventsListerItemTask(bool,bool):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
         -50 (-11.04% of base) : 9468.dasm - System.IO.Pipelines.Pipe:GetReadResult(byref):this
         -44 (-2.25% of base) : 22379.dasm - <ReadAllAsync>d__65`1[SimpleStructWithProperties][MicroBenchmarks.Serializers.SimpleStructWithProperties]:MoveNext():this
         -44 (-6.26% of base) : 18810.dasm - BinderFactoryVisitor:GetMethodName(Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax,Microsoft.CodeAnalysis.CSharp.Binder):System.String
         -44 (-1.65% of base) : 20762.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxTreeSemanticModel:GetDeclarationName(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode):System.String:this
         -43 (-1.13% of base) : 18620.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ParameterHelpers:MakeParameters(Microsoft.CodeAnalysis.CSharp.Binder,Microsoft.CodeAnalysis.CSharp.Symbol,Microsoft.CodeAnalysis.CSharp.Syntax.BaseParameterListSyntax,byref,Microsoft.CodeAnalysis.DiagnosticBag,bool,bool,bool):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.ParameterSymbol, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
         -43 (-1.01% of base) : 13267.dasm - Utf8Json.Formatters.ISO8601DateTimeOffsetFormatter:Deserialize(byref,Utf8Json.IJsonFormatterResolver):System.DateTimeOffset:this
         -41 (-2.05% of base) : 2515.dasm - System.Reflection.RuntimeCustomAttributeData:.ctor(System.Reflection.RuntimeModule,System.Reflection.MetadataToken,byref):this
         -36 (-2.51% of base) : 15046.dasm - <ParallelReader>d__14:MoveNext():this
         -36 (-0.24% of base) : 6555.dasm - <SendAsyncCore>d__60:MoveNext():this
         -36 (-7.52% of base) : 5637.dasm - System.Collections.Immutable.ImmutableExtensions:GetEnumerableDisposable(System.Collections.Generic.IEnumerable`1[__Canon]):System.Collections.Immutable.DisposableEnumeratorAdapter`2[__Canon,Enumerator]

Top method regressions (percentages):
          54 (44.26% of base) : 25777.dasm - System.Collections.IterateForEach`1[__Canon][System.__Canon]:ImmutableStack():System.__Canon:this
           8 ( 4.49% of base) : 17191.dasm - System.Formats.Cbor.CborWriter:Encode(System.Span`1[Byte]):int:this
           5 ( 2.22% of base) : 8249.dasm - System.Linq.Expressions.Compiler.CompilerScope:Exit():System.Linq.Expressions.Compiler.CompilerScope:this
          26 ( 1.14% of base) : 18667.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:CheckAbstractClassImplementations(Microsoft.CodeAnalysis.DiagnosticBag):this
           5 ( 1.11% of base) : 21569.dasm - Newtonsoft.Json.Utilities.ReflectionUtils:GetCollectionItemType(System.Type):System.Type
          14 ( 1.08% of base) : 19008.dasm - Microsoft.CodeAnalysis.CSharp.ControlFlowPass:RemoveReturns():System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.PreciseAbstractFlowPass`1+PendingBranch[[Microsoft.CodeAnalysis.CSharp.ControlFlowPass+LocalState, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
           4 ( 0.86% of base) : 5298.dasm - Microsoft.Extensions.Logging.LoggerFactory:CreateLogger(System.String):Microsoft.Extensions.Logging.ILogger:this
           7 ( 0.81% of base) : 20558.dasm - System.Text.RegularExpressions.Regex:Split(System.Text.RegularExpressions.Regex,System.String,int,int):System.String[]
           2 ( 0.67% of base) : 1880.dasm - System.Globalization.CultureData:nativeEnumTimeFormats(System.String,int,bool):System.String[]
          13 ( 0.51% of base) : 13251.dasm - DynamicClass:proto_8(byref,MicroBenchmarks.Serializers.MyEventsListerItem):MicroBenchmarks.Serializers.MyEventsListerItem
          11 ( 0.49% of base) : 18805.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:BindMethodBody(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.TypeCompilationState,Microsoft.CodeAnalysis.DiagnosticBag,byref,byref,byref):Microsoft.CodeAnalysis.CSharp.BoundBlock
           4 ( 0.40% of base) : 11638.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.IndexViewModel):MicroBenchmarks.Serializers.IndexViewModel
           2 ( 0.38% of base) : 18557.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceOrdinaryMethodSymbol:CreateMethodSymbol(Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol,Microsoft.CodeAnalysis.CSharp.Binder,Microsoft.CodeAnalysis.CSharp.Syntax.MethodDeclarationSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.Symbols.SourceOrdinaryMethodSymbol
           4 ( 0.35% of base) : 26845.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.LoginViewModel):MicroBenchmarks.Serializers.LoginViewModel
           2 ( 0.29% of base) : 1870.dasm - System.Globalization.CalendarData:CallEnumCalendarInfo(System.String,ushort,int,int,byref):bool
           5 ( 0.27% of base) : 11668.dasm - DynamicClass:proto_10(byref,MicroBenchmarks.Serializers.CampaignSummaryViewModel):MicroBenchmarks.Serializers.CampaignSummaryViewModel
           4 ( 0.22% of base) : 3071.dasm - System.Runtime.Serialization.DataContract:GetDefaultStableLocalName(System.Type):System.String
           5 ( 0.22% of base) : 11651.dasm - DynamicClass:proto_8(byref,MicroBenchmarks.Serializers.ActiveOrUpcomingEvent):MicroBenchmarks.Serializers.ActiveOrUpcomingEvent
           5 ( 0.21% of base) : 28270.dasm - DynamicClass:proto_2(byref,MicroBenchmarks.Serializers.Location):MicroBenchmarks.Serializers.Location
           8 ( 0.19% of base) : 17552.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseMemberDeclarationOrStatement(ushort):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.MemberDeclarationSyntax:this

Top method improvements (percentages):
         -54 (-27.27% of base) : 20742.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxTreeSemanticModel:AnalyzeDataFlow(Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax):Microsoft.CodeAnalysis.DataFlowAnalysis:this
         -95 (-23.57% of base) : 9401.dasm - System.Diagnostics.DiagLinkedList`1[ActivityLink][System.Diagnostics.ActivityLink]:.ctor(System.Collections.Generic.IEnumerator`1[ActivityLink]):this
         -98 (-22.37% of base) : 18614.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.LookupPosition:IsInBody(int,Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax):bool
         -28 (-15.64% of base) : 23865.dasm - System.Numerics.Tests.Perf_Matrix3x2:MultiplyByScalarBenchmark():System.Numerics.Matrix3x2:this
         -28 (-12.79% of base) : 24321.dasm - System.Numerics.Tests.Perf_Matrix3x2:NegateBenchmark():System.Numerics.Matrix3x2:this
         -66 (-12.27% of base) : 18610.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.LookupPosition:IsInMethodDeclaration(int,Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax):bool
         -34 (-11.53% of base) : 5191.dasm - Microsoft.Extensions.DependencyInjection.ServiceLookup.ConstantCallSite:.ctor(System.Type,System.Object):this
         -50 (-11.04% of base) : 9468.dasm - System.IO.Pipelines.Pipe:GetReadResult(byref):this
         -18 (-10.34% of base) : 20948.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:SetSlotUnassigned(int):this
         -36 (-7.52% of base) : 5637.dasm - System.Collections.Immutable.ImmutableExtensions:GetEnumerableDisposable(System.Collections.Generic.IEnumerable`1[__Canon]):System.Collections.Immutable.DisposableEnumeratorAdapter`2[__Canon,Enumerator]
         -36 (-7.52% of base) : 20379.dasm - System.Collections.Immutable.ImmutableExtensions:GetEnumerableDisposable(System.Collections.Generic.IEnumerable`1[Int32]):System.Collections.Immutable.DisposableEnumeratorAdapter`2[Int32,Enumerator]
         -36 (-7.29% of base) : 16902.dasm - System.Numerics.Tests.Perf_Plane:TransformByMatrix4x4Benchmark():System.Numerics.Plane:this
        -107 (-6.90% of base) : 16035.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemTaskFormatter3:Deserialize(byref,Utf8Json.IJsonFormatterResolver):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
         -44 (-6.26% of base) : 18810.dasm - BinderFactoryVisitor:GetMethodName(Microsoft.CodeAnalysis.CSharp.Syntax.BaseMethodDeclarationSyntax,Microsoft.CodeAnalysis.CSharp.Binder):System.String
          -5 (-6.10% of base) : 4222.dasm - System.IO.Pipes.PipeStream:GetSecAttrs(int):SECURITY_ATTRIBUTES
         -90 (-5.87% of base) : 5177.dasm - Microsoft.Extensions.DependencyInjection.ServiceProvider:.ctor(System.Collections.Generic.ICollection`1[[Microsoft.Extensions.DependencyInjection.ServiceDescriptor, Microsoft.Extensions.DependencyInjection.Abstractions, Version=7.0.0.0, Culture=neutral, PublicKeyToken=adb9793829ddae60]],Microsoft.Extensions.DependencyInjection.ServiceProviderOptions):this
         -50 (-5.62% of base) : 21030.dasm - Microsoft.Xml.Serialization.GeneratedAssembly.XmlSerializationReaderMyEventsListerViewModel:Read3_MyEventsListerItemTask(bool,bool):MicroBenchmarks.Serializers.MyEventsListerItemTask:this
          -7 (-5.38% of base) : 16652.dasm - System.Collections.Generic.GenericComparer`1[Decimal][System.Decimal]:Compare(System.Decimal,System.Decimal):int:this
          -9 (-5.36% of base) : 25475.dasm - <>c:<Order00ManualX>b__15_0(Product,Product):int:this
          -9 (-4.84% of base) : 24226.dasm - <>c:<Where01LinqMethodNestedX>b__9_1(Product):bool:this

147 total methods with Code Size differences (119 improved, 28 regressed), 119 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 123756140 (overridden on cmd)
Total bytes of diff: 123744915 (overridden on cmd)
Total bytes of delta: -11225 (-0.01 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          78 : 246938.dasm (18.71% of base)
          25 : 160600.dasm (1.06% of base)
          24 : 246961.dasm (6.65% of base)
          24 : 246936.dasm (6.65% of base)
          24 : 246960.dasm (6.65% of base)
          11 : 233115.dasm (0.02% of base)
          11 : 233120.dasm (0.02% of base)
           6 : 90377.dasm (3.21% of base)
           6 : 89299.dasm (0.56% of base)
           4 : 168265.dasm (0.02% of base)
           2 : 172354.dasm (0.07% of base)
           1 : 252617.dasm (0.18% of base)
           1 : 227384.dasm (0.04% of base)
           1 : 227386.dasm (0.10% of base)
           1 : 227552.dasm (0.11% of base)
           1 : 244911.dasm (0.04% of base)
           1 : 236995.dasm (0.18% of base)
           1 : 236996.dasm (0.11% of base)
           1 : 251935.dasm (0.23% of base)
           1 : 251938.dasm (0.22% of base)

Top file improvements (bytes):
        -189 : 160451.dasm (-2.35% of base)
        -119 : 163065.dasm (-1.78% of base)
        -116 : 160497.dasm (-1.94% of base)
        -116 : 163101.dasm (-1.94% of base)
        -108 : 174081.dasm (-2.71% of base)
        -108 : 174260.dasm (-2.69% of base)
        -102 : 160256.dasm (-4.00% of base)
         -93 : 161149.dasm (-1.69% of base)
         -93 : 163559.dasm (-1.72% of base)
         -93 : 160230.dasm (-2.01% of base)
         -93 : 162899.dasm (-2.01% of base)
         -93 : 160225.dasm (-2.62% of base)
         -87 : 174100.dasm (-2.08% of base)
         -87 : 174261.dasm (-2.06% of base)
         -87 : 160448.dasm (-2.75% of base)
         -87 : 163063.dasm (-2.75% of base)
         -84 : 162921.dasm (-3.55% of base)
         -82 : 160227.dasm (-1.07% of base)
         -75 : 163402.dasm (-2.94% of base)
         -75 : 162894.dasm (-2.49% of base)

665 total files with Code Size differences (640 improved, 25 regressed), 92 unchanged.

Top method regressions (bytes):
          78 (18.71% of base) : 246938.dasm - Test_instance_assignment_struct01:Main():int
          25 ( 1.06% of base) : 160600.dasm - testout1:Func_0_2_6_4_5():double
          24 ( 6.65% of base) : 246936.dasm - Test_instance_assignment_class01:Main():int
          24 ( 6.65% of base) : 246960.dasm - Test_static_assignment_class01:Main():int
          24 ( 6.65% of base) : 246961.dasm - Test_static_assignment_struct01:Main():int
          11 ( 0.02% of base) : 233115.dasm - testout1:Func_0():int
          11 ( 0.02% of base) : 233120.dasm - testout1:Func_0():int
           6 ( 3.21% of base) : 90377.dasm - ForwardSubModOpt:Main():int
           6 ( 0.56% of base) : 89299.dasm - JitTest.LCS:Main():int
           4 ( 0.02% of base) : 168265.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
           2 ( 0.07% of base) : 172354.dasm - <runRouter>d__6:MoveNext():this
           1 ( 0.04% of base) : 244911.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbDebugDirectory(System.String):this
           1 ( 0.11% of base) : 227552.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227571.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227587.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227607.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.18% of base) : 236995.dasm - ILStubClass:IL_STUB_PInvoke(byref):System.String
           1 ( 0.11% of base) : 236996.dasm - ILStubClass:IL_STUB_PInvoke(byref):System.String
           1 ( 0.23% of base) : 251935.dasm - ILStubClass:IL_STUB_PInvoke(System.String,byref)
           1 ( 0.18% of base) : 252617.dasm - JitTest.Column:TestEntryPoint():int

Top method improvements (bytes):
        -189 (-2.35% of base) : 160451.dasm - testout1:Func_0_1_6_6_1():System.Decimal
        -119 (-1.78% of base) : 163065.dasm - testout1:Func_0_1_6_6_1():System.Decimal
        -116 (-1.94% of base) : 160497.dasm - testout1:Func_0_2_3_1_5():System.Decimal
        -116 (-1.94% of base) : 163101.dasm - testout1:Func_0_2_3_1_5():System.Decimal
        -108 (-2.71% of base) : 174081.dasm - NullableTest43:Run()
        -108 (-2.69% of base) : 174260.dasm - NullableTest43:Run()
        -102 (-4.00% of base) : 160256.dasm - testout1:Func_0_5_5_3():System.Decimal
         -93 (-2.01% of base) : 160230.dasm - testout1:Func_0_4_5_1():System.Decimal
         -93 (-2.01% of base) : 162899.dasm - testout1:Func_0_4_5_1():System.Decimal
         -93 (-2.62% of base) : 160225.dasm - testout1:Func_0_4_5_6():System.Decimal
         -93 (-1.69% of base) : 161149.dasm - testout1:Func_0_5_5_5_6():System.Decimal
         -93 (-1.72% of base) : 163559.dasm - testout1:Func_0_5_5_5_6():System.Decimal
         -87 (-2.08% of base) : 174100.dasm - NullableTest44:Run()
         -87 (-2.06% of base) : 174261.dasm - NullableTest44:Run()
         -87 (-2.75% of base) : 160448.dasm - testout1:Func_0_1_6_6_4():System.Decimal
         -87 (-2.75% of base) : 163063.dasm - testout1:Func_0_1_6_6_4():System.Decimal
         -84 (-3.55% of base) : 162921.dasm - testout1:Func_0_5_5_3():System.Decimal
         -82 (-1.07% of base) : 160227.dasm - testout1:Func_0_4_5_4():System.Decimal
         -75 (-2.94% of base) : 163402.dasm - testout1:Func_0_4_5_1_4():System.Decimal
         -75 (-2.94% of base) : 160926.dasm - testout1:Func_0_4_5_1_4():System.Decimal

Top method regressions (percentages):
          78 (18.71% of base) : 246938.dasm - Test_instance_assignment_struct01:Main():int
          24 ( 6.65% of base) : 246936.dasm - Test_instance_assignment_class01:Main():int
          24 ( 6.65% of base) : 246960.dasm - Test_static_assignment_class01:Main():int
          24 ( 6.65% of base) : 246961.dasm - Test_static_assignment_struct01:Main():int
           6 ( 3.21% of base) : 90377.dasm - ForwardSubModOpt:Main():int
          25 ( 1.06% of base) : 160600.dasm - testout1:Func_0_2_6_4_5():double
           6 ( 0.56% of base) : 89299.dasm - JitTest.LCS:Main():int
           1 ( 0.23% of base) : 251935.dasm - ILStubClass:IL_STUB_PInvoke(System.String,byref)
           1 ( 0.22% of base) : 251938.dasm - LCIDTest:Main():int
           1 ( 0.18% of base) : 236995.dasm - ILStubClass:IL_STUB_PInvoke(byref):System.String
           1 ( 0.18% of base) : 252617.dasm - JitTest.Column:TestEntryPoint():int
           1 ( 0.18% of base) : 252616.dasm - JitTest.Column:TestEntryPoint():int
           1 ( 0.13% of base) : 252609.dasm - JitTest.Column:TestEntryPoint():int
           1 ( 0.11% of base) : 227571.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227587.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227552.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 227607.dasm - ILStubClass:IL_STUB_PInvoke(byref):bool
           1 ( 0.11% of base) : 236996.dasm - ILStubClass:IL_STUB_PInvoke(byref):System.String
           1 ( 0.10% of base) : 227386.dasm - NetClient.StringTests:Marshal_BStrString():this
           2 ( 0.07% of base) : 172354.dasm - <runRouter>d__6:MoveNext():this

Top method improvements (percentages):
         -30 (-16.22% of base) : 253503.dasm - Test_structret1_1:Main():int
         -40 (-16.13% of base) : 228654.dasm - NullableTest44:Run()
         -37 (-16.09% of base) : 228743.dasm - NullableTest13:Run()
         -37 (-16.09% of base) : 228596.dasm - NullableTest13:Run()
         -37 (-16.09% of base) : 228764.dasm - NullableTest34:Run()
         -37 (-16.09% of base) : 228638.dasm - NullableTest34:Run()
         -35 (-15.70% of base) : 228602.dasm - NullableTest16:Run()
         -35 (-15.62% of base) : 228746.dasm - NullableTest16:Run()
         -40 (-15.56% of base) : 228772.dasm - NullableTest44:Run()
         -33 (-12.74% of base) : 228652.dasm - NullableTest43:Run()
         -33 (-11.91% of base) : 228771.dasm - NullableTest43:Run()
         -39 (-11.44% of base) : 200655.dasm - ILStubClass:IL_STUB_PInvoke(long,long,long,long,long,long,long,long,long,long,long,long):MCCTest.VType0
         -31 (-10.88% of base) : 228656.dasm - NullableTest45:Run()
         -31 (-10.88% of base) : 228773.dasm - NullableTest45:Run()
         -25 (-10.20% of base) : 295.dasm - ILStubClass:IL_STUB_PInvoke(byref,int):Point4`1[Int64]
         -25 (-9.96% of base) : 168547.dasm - ILStubClass:IL_STUB_PInvoke(int):ManyInts
         -20 (-9.95% of base) : 228753.dasm - NullableTest23:Run()
         -20 (-9.95% of base) : 228616.dasm - NullableTest23:Run()
         -20 (-9.95% of base) : 228760.dasm - NullableTest30:Run()
         -20 (-9.95% of base) : 228630.dasm - NullableTest30:Run()

665 total methods with Code Size differences (640 improved, 25 regressed), 92 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 30067290 (overridden on cmd)
Total bytes of diff: 30053403 (overridden on cmd)
Total bytes of delta: -13887 (-0.05 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          33 : 32949.dasm (15.79% of base)
          33 : 32950.dasm (15.00% of base)
          31 : 55274.dasm (2.89% of base)
          21 : 203107.dasm (3.38% of base)
          20 : 45492.dasm (0.82% of base)
          18 : 99348.dasm (3.12% of base)
          16 : 38521.dasm (0.51% of base)
          15 : 48394.dasm (1.58% of base)
          13 : 134547.dasm (0.63% of base)
          13 : 134549.dasm (0.71% of base)
          13 : 105439.dasm (1.85% of base)
          10 : 204987.dasm (0.84% of base)
           8 : 126791.dasm (0.64% of base)
           7 : 142946.dasm (1.09% of base)
           7 : 177525.dasm (0.82% of base)
           7 : 76048.dasm (1.68% of base)
           7 : 76052.dasm (2.23% of base)
           7 : 139911.dasm (2.03% of base)
           7 : 76625.dasm (2.15% of base)
           7 : 76649.dasm (2.23% of base)

Top file improvements (bytes):
        -111 : 76082.dasm (-7.86% of base)
        -106 : 76111.dasm (-10.34% of base)
        -103 : 28260.dasm (-19.07% of base)
         -92 : 190818.dasm (-24.60% of base)
         -91 : 201196.dasm (-6.40% of base)
         -84 : 76965.dasm (-6.24% of base)
         -80 : 76100.dasm (-12.86% of base)
         -78 : 76680.dasm (-2.37% of base)
         -76 : 201309.dasm (-6.49% of base)
         -68 : 36149.dasm (-12.66% of base)
         -68 : 201891.dasm (-9.20% of base)
         -67 : 216895.dasm (-23.76% of base)
         -67 : 217647.dasm (-23.76% of base)
         -67 : 75933.dasm (-2.20% of base)
         -67 : 217236.dasm (-20.74% of base)
         -66 : 217120.dasm (-13.89% of base)
         -64 : 216819.dasm (-33.86% of base)
         -64 : 217582.dasm (-32.32% of base)
         -64 : 217583.dasm (-32.99% of base)
         -64 : 5201.dasm (-6.54% of base)

820 total files with Code Size differences (682 improved, 138 regressed), 436 unchanged.

Top method regressions (bytes):
          33 (15.79% of base) : 32949.dasm - Microsoft.CodeAnalysis.ArrayBuilderExtensions:All(Microsoft.CodeAnalysis.ArrayBuilder`1[System.__Canon],System.Func`2[System.__Canon, System.Boolean]):bool
          33 (15.00% of base) : 32950.dasm - Microsoft.CodeAnalysis.ArrayBuilderExtensions:Any(Microsoft.CodeAnalysis.ArrayBuilder`1[System.__Canon],System.Func`2[System.__Canon, System.Boolean]):bool
          31 ( 2.89% of base) : 55274.dasm - <WriteAsyncInternal>d__64:MoveNext():this
          21 ( 3.38% of base) : 203107.dasm - Microsoft.CSharp.RuntimeBinder.ComInterop.IDispatchComObject:GetMembers(System.Collections.Generic.IEnumerable`1[System.String]):System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String, System.Object]]:this
          20 ( 0.82% of base) : 45492.dasm - System.Xml.Schema.RangeContentValidator:ValidateElement(System.Xml.XmlQualifiedName,System.Xml.Schema.ValidationState,byref):System.Object:this
          18 ( 3.12% of base) : 99348.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
          16 ( 0.51% of base) : 38521.dasm - System.Xml.Serialization.TypeScope:ImportTypeDesc(System.Type,System.Reflection.MemberInfo,bool):System.Xml.Serialization.TypeDesc:this
          15 ( 1.58% of base) : 48394.dasm - System.Xml.XmlTextReaderImpl:ReadValueChunk(System.Char[],int,int):int:this
          13 ( 0.71% of base) : 134549.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ApplyDirectCastConversion(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          13 ( 0.63% of base) : 134547.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ApplyTryCastConversion(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          13 ( 1.85% of base) : 105439.dasm - Microsoft.FSharp.Reflection.Impl:compileTupleReader(int,Microsoft.FSharp.Core.FSharpFunc`2[System.Type, Microsoft.FSharp.Core.FSharpChoice`2[System.Reflection.FieldInfo[], System.Reflection.PropertyInfo[]]],System.Type):System.Func`2[System.Object, System.Object[]]
          10 ( 0.84% of base) : 204987.dasm - System.Numerics.BigNumber:FormatBigIntegerToHex(bool,System.Numerics.BigInteger,ushort,int,System.Globalization.NumberFormatInfo,System.Span`1[System.Char],byref,byref):System.String
           8 ( 0.64% of base) : 126791.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseXmlProcessingInstruction(int,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlWhitespaceChecker):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlProcessingInstructionSyntax:this
           7 ( 0.63% of base) : 55885.dasm - <InternalWriteAllLinesAsync>d__78:MoveNext():this
           7 ( 1.92% of base) : 65196.dasm - System.Globalization.CalendarData:EnumMonthNames(System.String,ushort,int,byref,byref):bool
           7 ( 0.82% of base) : 177525.dasm - System.Net.Security.NegotiateStreamPal:InitializeSecurityContext(byref,byref,System.String,int,System.Byte[],System.Security.Authentication.ExtendedProtection.ChannelBinding,byref,byref):System.Net.SecurityStatusPal
           7 ( 0.82% of base) : 157281.dasm - System.Net.Security.NegotiateStreamPal:InitializeSecurityContext(byref,byref,System.String,int,System.Byte[],System.Security.Authentication.ExtendedProtection.ChannelBinding,byref,byref):System.Net.SecurityStatusPal
           7 ( 0.80% of base) : 161199.dasm - System.Net.Security.NegotiateStreamPal:InitializeSecurityContext(byref,byref,System.String,int,System.Byte[],System.Security.Authentication.ExtendedProtection.ChannelBinding,byref,byref):System.Net.SecurityStatusPal
           7 ( 0.82% of base) : 186256.dasm - System.Net.Security.NegotiateStreamPal:InitializeSecurityContext(byref,byref,System.String,int,System.Byte[],System.Security.Authentication.ExtendedProtection.ChannelBinding,byref,byref):System.Net.SecurityStatusPal
           7 ( 2.15% of base) : 76662.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.PBES2Params

Top method improvements (bytes):
        -111 (-7.86% of base) : 76082.dasm - System.Security.Cryptography.Pkcs.Asn1.OriginatorIdentifierOrKeyAsn:DecodeCore(byref,System.ReadOnlyMemory`1[System.Byte],byref)
        -106 (-10.34% of base) : 76111.dasm - System.Security.Cryptography.Pkcs.Rfc3161TimestampTokenInfo:Encode(System.Security.Cryptography.Oid,System.Security.Cryptography.Oid,System.ReadOnlyMemory`1[System.Byte],System.ReadOnlyMemory`1[System.Byte],System.DateTimeOffset,bool,System.Nullable`1[System.Int64],System.Nullable`1[System.ReadOnlyMemory`1[System.Byte]],System.Nullable`1[System.ReadOnlyMemory`1[System.Byte]],System.Security.Cryptography.X509Certificates.X509ExtensionCollection):System.Byte[]
        -103 (-19.07% of base) : 28260.dasm - Roslyn.Utilities.TextChangeRangeExtensions:Accumulate(System.Nullable`1[Microsoft.CodeAnalysis.Text.TextChangeRange],System.Collections.Generic.IEnumerable`1[Microsoft.CodeAnalysis.Text.TextChangeRange]):System.Nullable`1[Microsoft.CodeAnalysis.Text.TextChangeRange]
         -92 (-24.60% of base) : 190818.dasm - System.Diagnostics.DiagLinkedList`1:.ctor(System.Collections.Generic.IEnumerator`1[System.Diagnostics.ActivityEvent]):this
         -91 (-6.40% of base) : 201196.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:FindLiteralFollowingLeadingLoop(System.Text.RegularExpressions.RegexNode):System.Nullable`1[System.ValueTuple`2[System.Text.RegularExpressions.RegexNode, System.ValueTuple`3[System.Char, System.String, System.Char[]]]]
         -84 (-6.24% of base) : 76965.dasm - Internal.Cryptography.Pal.AnyOS.ManagedPkcsPal:MakeKtri(System.Byte[],System.Security.Cryptography.Pkcs.CmsRecipient,byref):System.Security.Cryptography.Pkcs.Asn1.KeyTransRecipientInfoAsn:this
         -80 (-12.86% of base) : 76100.dasm - System.Security.Cryptography.Pkcs.Asn1.KeyAgreeRecipientIdentifierAsn:DecodeCore(byref,System.ReadOnlyMemory`1[System.Byte],byref)
         -78 (-2.37% of base) : 76680.dasm - System.Security.Cryptography.Asn1.GeneralNameAsn:DecodeCore(byref,System.ReadOnlyMemory`1[System.Byte],byref)
         -76 (-6.49% of base) : 201309.dasm - System.Text.RegularExpressions.RegexNode:FindStartingLiteral(int):System.Nullable`1[System.ValueTuple`3[System.Char, System.String, System.String]]:this
         -68 (-9.20% of base) : 201891.dasm - PartitionTree:Refine(System.Text.RegularExpressions.Symbolic.IBooleanAlgebra`1[System.Text.RegularExpressions.Symbolic.BitVector],System.Text.RegularExpressions.Symbolic.BitVector):this
         -68 (-12.66% of base) : 36149.dasm - System.Text.Json.Utf8JsonReader:SkipOrConsumeCommentMultiSegmentWithRollback():bool:this
         -67 (-20.74% of base) : 217236.dasm - System.Linq.Parallel.BinaryQueryOperator`3:.ctor(System.Linq.Parallel.QueryOperator`1[System.__Canon],System.Linq.Parallel.QueryOperator`1[System.__Canon]):this
         -67 (-23.76% of base) : 216895.dasm - System.Linq.Parallel.QueryExecutionOption`1:.ctor(System.Linq.Parallel.QueryOperator`1[System.__Canon],System.Linq.Parallel.QuerySettings):this
         -67 (-23.76% of base) : 217647.dasm - System.Linq.Parallel.QueryExecutionOption`1:.ctor(System.Linq.Parallel.QueryOperator`1[System.Int32],System.Linq.Parallel.QuerySettings):this
         -67 (-2.20% of base) : 75933.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161TstInfo:DecodeCore(byref,System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],byref)
         -66 (-13.89% of base) : 217120.dasm - System.Linq.Parallel.ZipQueryOperator`3:.ctor(System.Linq.Parallel.QueryOperator`1[System.__Canon],System.Linq.Parallel.QueryOperator`1[System.__Canon],System.Func`3[System.__Canon, System.__Canon, System.__Canon]):this
         -64 (-6.54% of base) : 5201.dasm - Cursor:MoveToFirstChild():Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.Blender+Cursor:this
         -64 (-33.33% of base) : 217358.dasm - System.Linq.Parallel.EmptyEnumerable`1:get_Instance():System.Linq.Parallel.EmptyEnumerable`1[System.__Canon]
         -64 (-33.86% of base) : 216819.dasm - System.Linq.Parallel.ScanQueryOperator`1:.ctor(System.Collections.Generic.IEnumerable`1[System.__Canon]):this
         -64 (-32.32% of base) : 217582.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.Concurrent.Partitioner`1[System.__Canon]):System.Linq.ParallelQuery`1[System.__Canon]

Top method regressions (percentages):
          33 (15.79% of base) : 32949.dasm - Microsoft.CodeAnalysis.ArrayBuilderExtensions:All(Microsoft.CodeAnalysis.ArrayBuilder`1[System.__Canon],System.Func`2[System.__Canon, System.Boolean]):bool
          33 (15.00% of base) : 32950.dasm - Microsoft.CodeAnalysis.ArrayBuilderExtensions:Any(Microsoft.CodeAnalysis.ArrayBuilder`1[System.__Canon],System.Func`2[System.__Canon, System.Boolean]):bool
          21 ( 3.38% of base) : 203107.dasm - Microsoft.CSharp.RuntimeBinder.ComInterop.IDispatchComObject:GetMembers(System.Collections.Generic.IEnumerable`1[System.String]):System.Collections.Generic.IList`1[System.Collections.Generic.KeyValuePair`2[System.String, System.Object]]:this
          18 ( 3.12% of base) : 99348.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
           2 ( 3.08% of base) : 217295.dasm - OrderedPipeliningMergeEnumerator:get_Current():System.__Canon:this
           7 ( 2.90% of base) : 41041.dasm - System.Xml.Xsl.Runtime.XmlILIndex:Add(System.String,System.Xml.XPath.XPathNavigator):this
          31 ( 2.89% of base) : 55274.dasm - <WriteAsyncInternal>d__64:MoveNext():this
           4 ( 2.60% of base) : 201199.dasm - System.Text.RegularExpressions.RegexPrefixAnalyzer:FindCaseSensitivePrefix(System.Text.RegularExpressions.RegexNode):System.String
           7 ( 2.43% of base) : 75981.dasm - System.Security.Cryptography.Pkcs.Asn1.PkiStatusInfo:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Pkcs.Asn1.PkiStatusInfo
           4 ( 2.38% of base) : 201407.dasm - System.Text.RegularExpressions.RegexCharClass:ToStringClass(int):System.String:this
           7 ( 2.23% of base) : 76649.dasm - System.Security.Cryptography.Asn1.Pbkdf2SaltChoice:Decode(System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.Pbkdf2SaltChoice
           7 ( 2.23% of base) : 76052.dasm - System.Security.Cryptography.Pkcs.Asn1.RecipientIdentifierAsn:Decode(System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Pkcs.Asn1.RecipientIdentifierAsn
           7 ( 2.23% of base) : 75924.dasm - System.Security.Cryptography.Pkcs.Asn1.SignerIdentifierAsn:Decode(System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Pkcs.Asn1.SignerIdentifierAsn
           7 ( 2.20% of base) : 75944.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161TimeStampResp:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Pkcs.Asn1.Rfc3161TimeStampResp
           7 ( 2.15% of base) : 76662.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.PBES2Params
           7 ( 2.15% of base) : 139936.dasm - System.Security.Cryptography.Asn1.PBES2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.PBES2Params
           7 ( 2.15% of base) : 76654.dasm - System.Security.Cryptography.Asn1.Pbkdf2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.Pbkdf2Params
           7 ( 2.15% of base) : 139932.dasm - System.Security.Cryptography.Asn1.Pbkdf2Params:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.Pbkdf2Params
           7 ( 2.15% of base) : 76549.dasm - System.Security.Cryptography.Asn1.Pkcs7.EncryptedContentInfoAsn:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.Pkcs7.EncryptedContentInfoAsn
           7 ( 2.15% of base) : 76625.dasm - System.Security.Cryptography.Asn1.PrivateKeyInfoAsn:Decode(System.Formats.Asn1.Asn1Tag,System.ReadOnlyMemory`1[System.Byte],int):System.Security.Cryptography.Asn1.PrivateKeyInfoAsn

Top method improvements (percentages):
         -54 (-40.00% of base) : 217359.dasm - System.Linq.Parallel.EmptyEnumerable`1:.ctor():this
         -61 (-39.35% of base) : 217339.dasm - System.Linq.Parallel.RangeEnumerable:.ctor(int,int):this
         -61 (-36.75% of base) : 217333.dasm - System.Linq.Parallel.RepeatEnumerable`1:.ctor(System.__Canon,int):this
         -54 (-34.62% of base) : 217345.dasm - System.Linq.Parallel.ParallelEnumerableWrapper:.ctor(System.Collections.IEnumerable):this
         -54 (-34.62% of base) : 217342.dasm - System.Linq.Parallel.ParallelEnumerableWrapper`1:.ctor(System.Collections.Generic.IEnumerable`1[System.__Canon]):this
         -54 (-34.62% of base) : 217766.dasm - System.Linq.Parallel.ParallelEnumerableWrapper`1:.ctor(System.Collections.Generic.IEnumerable`1[System.Int32]):this
         -64 (-33.86% of base) : 216819.dasm - System.Linq.Parallel.ScanQueryOperator`1:.ctor(System.Collections.Generic.IEnumerable`1[System.__Canon]):this
         -54 (-33.75% of base) : 216887.dasm - System.Linq.Parallel.PartitionerQueryOperator`1:.ctor(System.Collections.Concurrent.Partitioner`1[System.__Canon]):this
         -64 (-33.33% of base) : 217358.dasm - System.Linq.Parallel.EmptyEnumerable`1:get_Instance():System.Linq.Parallel.EmptyEnumerable`1[System.__Canon]
         -64 (-32.99% of base) : 217583.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.Generic.IEnumerable`1[System.__Canon]):System.Linq.ParallelQuery`1[System.__Canon]
         -64 (-32.32% of base) : 217582.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.Concurrent.Partitioner`1[System.__Canon]):System.Linq.ParallelQuery`1[System.__Canon]
         -54 (-30.34% of base) : 217701.dasm - System.Linq.Parallel.ScanQueryOperator`1:.ctor(System.Collections.Generic.IEnumerable`1[System.Int64]):this
         -54 (-29.03% of base) : 217578.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.IEnumerable):System.Linq.ParallelQuery
         -26 (-28.57% of base) : 59662.dasm - System.Runtime.Intrinsics.Vector256:<Create>g__SoftwareFallback|44_0(long):System.Runtime.Intrinsics.Vector256`1[System.IntPtr]
         -26 (-28.57% of base) : 59661.dasm - System.Runtime.Intrinsics.Vector256:<Create>g__SoftwareFallback|45_0(long):System.Runtime.Intrinsics.Vector256`1[System.UIntPtr]
         -26 (-28.57% of base) : 59776.dasm - System.Runtime.Intrinsics.Vector256:Create(long):System.Runtime.Intrinsics.Vector256`1[System.IntPtr]
         -26 (-28.57% of base) : 59775.dasm - System.Runtime.Intrinsics.Vector256:Create(long):System.Runtime.Intrinsics.Vector256`1[System.UIntPtr]
         -26 (-28.57% of base) : 59732.dasm - System.Runtime.Intrinsics.Vector256:CreateScalarUnsafe(long):System.Runtime.Intrinsics.Vector256`1[System.IntPtr]
         -26 (-28.57% of base) : 59731.dasm - System.Runtime.Intrinsics.Vector256:CreateScalarUnsafe(long):System.Runtime.Intrinsics.Vector256`1[System.UIntPtr]
         -61 (-27.23% of base) : 217572.dasm - System.Linq.ParallelEnumerable:Range(int,int):System.Linq.ParallelQuery`1[System.Int32]

820 total methods with Code Size differences (682 improved, 138 regressed), 436 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 49196872 (overridden on cmd)
Total bytes of diff: 49146265 (overridden on cmd)
Total bytes of delta: -50607 (-0.10 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         119 : 233423.dasm (2.53% of base)
          26 : 241748.dasm (5.46% of base)
          26 : 241749.dasm (5.21% of base)
          26 : 49401.dasm (1.58% of base)
          25 : 85698.dasm (1.17% of base)
          24 : 56824.dasm (2.64% of base)
          19 : 150468.dasm (0.47% of base)
          17 : 49307.dasm (0.54% of base)
          17 : 210063.dasm (0.81% of base)
          17 : 49605.dasm (0.65% of base)
          16 : 159721.dasm (0.93% of base)
          16 : 140877.dasm (1.00% of base)
          15 : 8173.dasm (1.40% of base)
          15 : 140715.dasm (1.01% of base)
          14 : 42423.dasm (0.80% of base)
          14 : 49174.dasm (0.32% of base)
          14 : 216036.dasm (1.64% of base)
          13 : 71902.dasm (0.69% of base)
          13 : 49603.dasm (0.57% of base)
          13 : 49610.dasm (0.26% of base)

Top file improvements (bytes):
        -899 : 200927.dasm (-18.65% of base)
        -271 : 67417.dasm (-15.42% of base)
        -246 : 33168.dasm (-13.74% of base)
        -239 : 32546.dasm (-14.18% of base)
        -237 : 66444.dasm (-15.67% of base)
        -236 : 67371.dasm (-16.33% of base)
        -216 : 66357.dasm (-17.68% of base)
        -211 : 34293.dasm (-15.00% of base)
        -208 : 34268.dasm (-16.72% of base)
        -208 : 62850.dasm (-13.06% of base)
        -205 : 34244.dasm (-19.90% of base)
        -199 : 33056.dasm (-12.59% of base)
        -199 : 33095.dasm (-12.59% of base)
        -199 : 33133.dasm (-12.59% of base)
        -189 : 66055.dasm (-12.82% of base)
        -185 : 32577.dasm (-13.76% of base)
        -185 : 32061.dasm (-11.55% of base)
        -179 : 32518.dasm (-13.95% of base)
        -167 : 32739.dasm (-12.99% of base)
        -154 : 31017.dasm (-11.65% of base)

1305 total files with Code Size differences (1168 improved, 137 regressed), 737 unchanged.

Top method regressions (bytes):
         119 ( 2.53% of base) : 233423.dasm - System.Text.Json.JsonSerializer:Read(byref,System.Text.Json.Serialization.Metadata.JsonTypeInfo):System.Numerics.Vector`1[Single]
          26 ( 5.21% of base) : 241749.dasm - Internal.CommandLine.ArgumentParser:TryParseOptionList(System.String,System.Collections.Generic.IReadOnlyCollection`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Byte, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,byref,byref):bool:this
          26 ( 5.46% of base) : 241748.dasm - Internal.CommandLine.ArgumentParser:TryParseOptionList(System.String,System.Collections.Generic.IReadOnlyCollection`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Func`2[__Canon,__Canon],bool,byref,byref):bool:this
          26 ( 1.58% of base) : 49401.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindInvocationExpressionPossiblyWithoutArguments(Microsoft.CodeAnalysis.VisualBasic.Syntax.InvocationExpressionSyntax,int,Microsoft.CodeAnalysis.VisualBasic.BoundMethodOrPropertyGroup,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Location, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          25 ( 1.17% of base) : 85698.dasm - Microsoft.Diagnostics.Tracing.Parsers.DynamicTraceEventData:GetPayloadValueAt(byref,int,int):System.Object:this
          24 ( 2.64% of base) : 56824.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceLateBoundReceiver(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Result
          19 ( 0.47% of base) : 150468.dasm - System.Xml.Serialization.TypeScope:ImportTypeDesc(System.Type,System.Reflection.MemberInfo,bool):System.Xml.Serialization.TypeDesc:this
          17 ( 0.65% of base) : 49605.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ApplyTryCastConversion(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          17 ( 0.54% of base) : 49307.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindAggregateQueryExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryExpressionSyntax,Microsoft.CodeAnalysis.SyntaxList`1+Enumerator[[Microsoft.CodeAnalysis.VisualBasic.Syntax.QueryClauseSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundQueryExpression:this
          17 ( 0.81% of base) : 210063.dasm - System.Management.ManagementObject:Initialize(bool):this
          16 ( 1.00% of base) : 140877.dasm - <ParseCDataOrCommentAsync>d__564:MoveNext():this
          16 ( 0.93% of base) : 159721.dasm - ILCompiler.DependencyAnalysis.ReadyToRun.GCRefMapBuilder:GetCallRefMap(Internal.TypeSystem.MethodDesc,bool):this
          15 ( 1.40% of base) : 8173.dasm - Microsoft.FSharp.Reflection.Impl:compileTupleReader(int,Microsoft.FSharp.Core.FSharpFunc`2[[System.Type, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpChoice`2[[System.Reflection.FieldInfo[], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.PropertyInfo[], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], FSharp.Core, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Type):System.Func`2[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object[], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
          15 ( 1.01% of base) : 140715.dasm - System.Xml.XmlTextReaderImpl:ReadValueChunk(System.Char[],int,int):int:this
          14 ( 0.80% of base) : 42423.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceCustomEventAccessorSymbol:.ctor(Microsoft.CodeAnalysis.CSharp.Symbols.SourceEventSymbol,Microsoft.CodeAnalysis.CSharp.Syntax.AccessorDeclarationSyntax,Microsoft.CodeAnalysis.CSharp.Symbols.EventSymbol,System.String,Microsoft.CodeAnalysis.DiagnosticBag):this
          14 ( 0.32% of base) : 49174.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindForEachBlockParts(Microsoft.CodeAnalysis.VisualBasic.Syntax.ForOrForEachBlockSyntax,Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,bool,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement:this
          14 ( 1.64% of base) : 216036.dasm - System.Net.HttpWebResponse:get_Headers():System.Net.WebHeaderCollection:this
          13 ( 0.30% of base) : 77780.dasm - Microsoft.CodeAnalysis.RuleSet:GetEffectiveRuleSet(System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.RuleSet:this
          13 ( 0.57% of base) : 49603.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ApplyDirectCastConversion(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          13 ( 0.26% of base) : 49610.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:CreateConversionAndReportDiagnostic(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.ConversionKind, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag,System.String,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method improvements (bytes):
        -899 (-18.65% of base) : 200927.dasm - System.Drawing.ColorTranslator:InitializeHtmlSysColorTable()
        -271 (-15.42% of base) : 67417.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.ExternalChecksumDirectiveTriviaSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.VisualBasic.Syntax.ExternalChecksumDirectiveTriviaSyntax:this
        -246 (-13.74% of base) : 33168.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax:Update(Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.BaseListSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.EnumMemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.EnumDeclarationSyntax:this
        -239 (-14.18% of base) : 32546.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.ForStatementSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.VariableDeclarationSyntax,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax):Microsoft.CodeAnalysis.CSharp.Syntax.ForStatementSyntax:this
        -237 (-15.67% of base) : 66444.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.GroupJoinClauseSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.CollectionRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.JoinClauseSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.JoinConditionSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.AggregationRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.VisualBasic.Syntax.GroupJoinClauseSyntax:this
        -236 (-16.33% of base) : 67371.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.ExternalSourceDirectiveTriviaSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.VisualBasic.Syntax.ExternalSourceDirectiveTriviaSyntax:this
        -216 (-17.68% of base) : 66357.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.GroupByClauseSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.AggregationRangeVariableSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.VisualBasic.Syntax.GroupByClauseSyntax:this
        -211 (-15.00% of base) : 34293.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.PragmaChecksumDirectiveTriviaSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,bool):Microsoft.CodeAnalysis.CSharp.Syntax.PragmaChecksumDirectiveTriviaSyntax:this
        -208 (-16.72% of base) : 34268.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.PragmaWarningDirectiveTriviaSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SeparatedSyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,bool):Microsoft.CodeAnalysis.CSharp.Syntax.PragmaWarningDirectiveTriviaSyntax:this
        -208 (-13.06% of base) : 62850.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.DeclareStatementSyntax:Update(ushort,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.VisualBasic.Syntax.AttributeListSyntax, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.LiteralExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.LiteralExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.SimpleAsClauseSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.DeclareStatementSyntax:this
        -205 (-19.90% of base) : 34244.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.LineDirectiveTriviaSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,bool):Microsoft.CodeAnalysis.CSharp.Syntax.LineDirectiveTriviaSyntax:this
        -199 (-12.59% of base) : 33056.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.ClassDeclarationSyntax:Update(Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.BaseListSyntax,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterConstraintClauseSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.ClassDeclarationSyntax:this
        -199 (-12.59% of base) : 33133.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InterfaceDeclarationSyntax:Update(Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.BaseListSyntax,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterConstraintClauseSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.InterfaceDeclarationSyntax:this
        -199 (-12.59% of base) : 33095.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.StructDeclarationSyntax:Update(Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxTokenList,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.BaseListSyntax,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.TypeParameterConstraintClauseSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.StructDeclarationSyntax:this
        -189 (-12.82% of base) : 66055.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.TernaryConditionalExpressionSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.VisualBasic.Syntax.TernaryConditionalExpressionSyntax:this
        -185 (-13.76% of base) : 32577.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.ForEachStatementSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.TypeSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax):Microsoft.CodeAnalysis.CSharp.Syntax.ForEachStatementSyntax:this
        -185 (-11.55% of base) : 32061.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.JoinClauseSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.TypeSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.JoinIntoClauseSyntax):Microsoft.CodeAnalysis.CSharp.Syntax.JoinClauseSyntax:this
        -179 (-13.95% of base) : 32518.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.DoStatementSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.StatementSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.DoStatementSyntax:this
        -167 (-12.99% of base) : 32739.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SwitchStatementSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.SwitchSectionSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.SwitchStatementSyntax:this
        -154 (-11.65% of base) : 31017.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.NamespaceDeclarationSyntax:Update(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.NameSyntax,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ExternAliasDirectiveSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.UsingDirectiveSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):Microsoft.CodeAnalysis.CSharp.Syntax.NamespaceDeclarationSyntax:this

Top method regressions (percentages):
           7 ( 5.74% of base) : 110096.dasm - Microsoft.Build.BackEnd.SchedulingPlan:CompleteConfig(System.String):this
          26 ( 5.46% of base) : 241748.dasm - Internal.CommandLine.ArgumentParser:TryParseOptionList(System.String,System.Collections.Generic.IReadOnlyCollection`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Func`2[__Canon,__Canon],bool,byref,byref):bool:this
          26 ( 5.21% of base) : 241749.dasm - Internal.CommandLine.ArgumentParser:TryParseOptionList(System.String,System.Collections.Generic.IReadOnlyCollection`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Func`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Byte, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,byref,byref):bool:this
           8 ( 4.49% of base) : 201413.dasm - System.Formats.Cbor.CborWriter:Encode(System.Span`1[Byte]):int:this
           6 ( 4.29% of base) : 157262.dasm - System.Speech.Internal.SrgsCompiler.AppDomainGrammarProxy:OnError(System.String,System.String,System.Object[],byref):this
           6 ( 3.92% of base) : 157261.dasm - System.Speech.Internal.SrgsCompiler.AppDomainGrammarProxy:OnParse(System.String,System.String,System.Object[],byref):System.Object:this
           5 ( 3.79% of base) : 130802.dasm - System.Net.Http.Headers.NameValueHeaderValue:GetHashCode(System.Net.Http.Headers.UnvalidatedObjectCollection`1[[System.Net.Http.Headers.NameValueHeaderValue, System.Net.Http, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):int
           5 ( 3.29% of base) : 130892.dasm - System.Net.Http.Headers.RangeHeaderValue:GetHashCode():int:this
          24 ( 2.64% of base) : 56824.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceLateBoundReceiver(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Result
         119 ( 2.53% of base) : 233423.dasm - System.Text.Json.JsonSerializer:Read(byref,System.Text.Json.Serialization.Metadata.JsonTypeInfo):System.Numerics.Vector`1[Single]
           2 ( 2.44% of base) : 79738.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:TryPop(System.__Canon,byref):bool:this
           2 ( 2.44% of base) : 79746.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:TryPop(int,byref):bool:this
           2 ( 2.44% of base) : 79752.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[Int64,Nullable`1][System.Int64,System.Nullable`1[System.Int32]]:TryPop(long,byref):bool:this
           2 ( 2.35% of base) : 79741.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:TryPop(ubyte,byref):bool:this
           2 ( 2.35% of base) : 79748.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:TryPop(double,byref):bool:this
           2 ( 2.35% of base) : 79235.dasm - Microsoft.CodeAnalysis.Text.CompositeText:get_Item(int):ushort:this
           2 ( 2.33% of base) : 79744.dasm - Microsoft.CodeAnalysis.Collections.KeyedStack`2[Int16,Nullable`1][System.Int16,System.Nullable`1[System.Int32]]:TryPop(short,byref):bool:this
           5 ( 2.22% of base) : 127007.dasm - System.Linq.Expressions.Compiler.CompilerScope:Exit():System.Linq.Expressions.Compiler.CompilerScope:this
           5 ( 2.11% of base) : 44228.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEAttributeData:EnsureClassAndConstructorSymbolsAreLoaded():this
           7 ( 2.08% of base) : 147874.dasm - System.Xml.Xsl.Runtime.XmlILIndex:Add(System.String,System.Xml.XPath.XPathNavigator):this

Top method improvements (percentages):
         -54 (-40.00% of base) : 204556.dasm - System.Linq.Parallel.EmptyEnumerable`1[__Canon][System.__Canon]:.ctor():this
         -54 (-40.00% of base) : 204559.dasm - System.Linq.Parallel.EmptyEnumerable`1[Byte][System.Byte]:.ctor():this
         -58 (-37.91% of base) : 204589.dasm - System.Linq.Parallel.RangeEnumerable:.ctor(int,int):this
         -58 (-37.91% of base) : 204600.dasm - System.Linq.Parallel.RepeatEnumerable`1[Int32][System.Int32]:.ctor(int,int):this
         -58 (-37.66% of base) : 204598.dasm - System.Linq.Parallel.RepeatEnumerable`1[Byte][System.Byte]:.ctor(ubyte,int):this
         -58 (-37.66% of base) : 204599.dasm - System.Linq.Parallel.RepeatEnumerable`1[Int16][System.Int16]:.ctor(short,int):this
         -58 (-37.42% of base) : 204603.dasm - System.Linq.Parallel.RepeatEnumerable`1[Int64][System.Int64]:.ctor(long,int):this
         -58 (-35.58% of base) : 204595.dasm - System.Linq.Parallel.RepeatEnumerable`1[__Canon][System.__Canon]:.ctor(System.__Canon,int):this
         -54 (-34.84% of base) : 204580.dasm - System.Linq.Parallel.ParallelEnumerableWrapper:.ctor(System.Collections.IEnumerable):this
         -54 (-34.84% of base) : 204583.dasm - System.Linq.Parallel.ParallelEnumerableWrapper`1[__Canon][System.__Canon]:.ctor(System.Collections.Generic.IEnumerable`1[__Canon]):this
         -54 (-34.84% of base) : 204586.dasm - System.Linq.Parallel.ParallelEnumerableWrapper`1[Byte][System.Byte]:.ctor(System.Collections.Generic.IEnumerable`1[Byte]):this
         -54 (-33.96% of base) : 205514.dasm - System.Linq.Parallel.PartitionerQueryOperator`1[__Canon][System.__Canon]:.ctor(System.Collections.Concurrent.Partitioner`1[__Canon]):this
         -54 (-33.96% of base) : 205520.dasm - System.Linq.Parallel.PartitionerQueryOperator`1[Byte][System.Byte]:.ctor(System.Collections.Concurrent.Partitioner`1[Byte]):this
         -55 (-33.74% of base) : 204602.dasm - System.Linq.Parallel.RepeatEnumerable`1[Vector`1][System.Numerics.Vector`1[System.Single]]:.ctor(System.Numerics.Vector`1[Single],int):this
         -61 (-32.62% of base) : 204554.dasm - System.Linq.Parallel.EmptyEnumerable`1[__Canon][System.__Canon]:get_Instance():System.Linq.Parallel.EmptyEnumerable`1[__Canon]
         -61 (-31.77% of base) : 205715.dasm - System.Linq.Parallel.ScanQueryOperator`1[__Canon][System.__Canon]:.ctor(System.Collections.Generic.IEnumerable`1[__Canon]):this
         -51 (-30.36% of base) : 204601.dasm - System.Linq.Parallel.RepeatEnumerable`1[Double][System.Double]:.ctor(double,int):this
         -61 (-30.20% of base) : 204449.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.Generic.IEnumerable`1[__Canon]):System.Linq.ParallelQuery`1[__Canon]
         -61 (-29.61% of base) : 204451.dasm - System.Linq.ParallelEnumerable:AsParallel(System.Collections.Concurrent.Partitioner`1[__Canon]):System.Linq.ParallelQuery`1[__Canon]
         -58 (-29.44% of base) : 204557.dasm - System.Linq.Parallel.EmptyEnumerable`1[Byte][System.Byte]:get_Instance():System.Linq.Parallel.EmptyEnumerable`1[Byte]

1305 total methods with Code Size differences (1168 improved, 137 regressed), 737 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 127184627 (overridden on cmd)
Total bytes of diff: 127138101 (overridden on cmd)
Total bytes of delta: -46526 (-0.04 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         659 : 94903.dasm (5.18% of base)
          56 : 268902.dasm (10.11% of base)
          41 : 94619.dasm (2.00% of base)
          33 : 11003.dasm (2.19% of base)
          33 : 11008.dasm (2.19% of base)
          25 : 336509.dasm (2.90% of base)
          25 : 11016.dasm (1.85% of base)
          24 : 4276.dasm (1.19% of base)
          24 : 336507.dasm (2.16% of base)
          24 : 336508.dasm (1.68% of base)
          21 : 4279.dasm (1.49% of base)
          19 : 66662.dasm (0.93% of base)
          18 : 283110.dasm (0.37% of base)
          18 : 157959.dasm (0.37% of base)
          17 : 352525.dasm (1.02% of base)
          15 : 4267.dasm (1.10% of base)
          15 : 4270.dasm (1.11% of base)
          15 : 4273.dasm (1.03% of base)
          15 : 11020.dasm (0.93% of base)
          15 : 137986.dasm (2.84% of base)

Top file improvements (bytes):
       -2321 : 121014.dasm (-10.70% of base)
        -976 : 121016.dasm (-10.53% of base)
        -393 : 163584.dasm (-8.84% of base)
        -347 : 117653.dasm (-4.13% of base)
        -321 : 163578.dasm (-7.59% of base)
        -285 : 163579.dasm (-9.27% of base)
        -285 : 163585.dasm (-9.78% of base)
        -213 : 162928.dasm (-16.32% of base)
        -180 : 338772.dasm (-6.57% of base)
        -149 : 118501.dasm (-5.27% of base)
        -124 : 121025.dasm (-5.91% of base)
        -120 : 8242.dasm (-3.38% of base)
        -115 : 122895.dasm (-6.16% of base)
        -110 : 118129.dasm (-15.67% of base)
        -109 : 121746.dasm (-25.12% of base)
        -107 : 118986.dasm (-1.27% of base)
        -106 : 122931.dasm (-8.50% of base)
        -105 : 165367.dasm (-8.76% of base)
        -105 : 165368.dasm (-8.81% of base)
        -105 : 165369.dasm (-8.81% of base)

1659 total files with Code Size differences (1530 improved, 129 regressed), 1097 unchanged.

Top method regressions (bytes):
         659 ( 5.18% of base) : 94903.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:WriteNumbers(bool,bool,System.String):this
          56 (10.11% of base) : 268902.dasm - System.Collections.Immutable.Tests.ImmutableStackTest:EnumeratorTestHelper(System.__Canon[]):this
          41 ( 2.00% of base) : 94619.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestSingleStringsMultiSegment()
          33 ( 2.19% of base) : 11003.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Byte][System.Byte]:ComputeEditPaths(ubyte,int,ubyte,int):VStack:this
          33 ( 2.19% of base) : 11008.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Int16][System.Int16]:ComputeEditPaths(short,int,short,int):VStack:this
          25 ( 1.85% of base) : 11016.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Double][System.Double]:ComputeEditPaths(double,int,double,int):VStack:this
          25 ( 2.90% of base) : 336509.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostAllThenReceive():this
          24 ( 1.19% of base) : 4276.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Vector`1][System.Numerics.Vector`1[System.Single]]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Vector`1],int,int,System.Numerics.Vector`1[Single],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):System.Numerics.Vector`1[Single]
          24 ( 2.16% of base) : 336507.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostThenReceive2():this
          24 ( 1.68% of base) : 336508.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostThenReceive3():this
          21 ( 1.49% of base) : 4279.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Int64][System.Int64]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Int64],int,int,long,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):long
          19 ( 0.93% of base) : 66662.dasm - <<ConnectCallback_ContextHasCorrectProperties_Success>b__0>d:MoveNext():this
          18 ( 0.37% of base) : 283110.dasm - <SystemColors_TestData>d__0:MoveNext():bool:this
          18 ( 0.37% of base) : 157959.dasm - <SystemColors_TestData>d__0:MoveNext():bool:this
          17 ( 1.02% of base) : 352525.dasm - System.AssertExtensions:CollectionEqual(System.Collections.Generic.IEnumerable`1[Byte],System.Collections.Generic.IEnumerable`1[Byte],System.Collections.Generic.IEqualityComparer`1[Byte])
          15 ( 0.93% of base) : 11020.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Vector`1][System.Numerics.Vector`1[System.Single]]:ComputeEditPaths(System.Numerics.Vector`1[Single],int,System.Numerics.Vector`1[Single],int):VStack:this
          15 ( 1.03% of base) : 4251.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[__Canon][System.__Canon]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[__Canon],int,int,System.__Canon,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):System.__Canon
          15 ( 1.10% of base) : 4260.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Byte][System.Byte]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Byte],int,int,ubyte,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):ubyte
          15 ( 1.03% of base) : 4273.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Double][System.Double]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Double],int,int,double,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):double
          15 ( 1.10% of base) : 4267.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Int16][System.Int16]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Int16],int,int,short,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):short

Top method improvements (bytes):
       -2321 (-10.70% of base) : 121014.dasm - Microsoft.CodeAnalysis.VisualBasic.Extensions.ContextQuery.SyntaxTreeExtensions:IsExpressionContext(Microsoft.CodeAnalysis.SyntaxTree,int,Microsoft.CodeAnalysis.SyntaxToken,System.Threading.CancellationToken,Microsoft.CodeAnalysis.SemanticModel):bool
        -976 (-10.53% of base) : 121016.dasm - Microsoft.CodeAnalysis.VisualBasic.Extensions.ContextQuery.SyntaxTreeExtensions:IsTypeContext(Microsoft.CodeAnalysis.SyntaxTree,int,Microsoft.CodeAnalysis.SyntaxToken,System.Threading.CancellationToken,Microsoft.CodeAnalysis.SemanticModel):bool
        -393 (-8.84% of base) : 163584.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Double_Overflow()
        -347 (-4.13% of base) : 117653.dasm - Microsoft.CodeAnalysis.CSharp.FindSymbols.CSharpDeclaredSymbolInfoFactoryService:AddDeclaredSymbolInfosWorker(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax,Roslyn.Utilities.StringTable,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[DeclaredSymbolInfo],System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], Microsoft.CodeAnalysis.Workspaces, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.String,System.String,System.Threading.CancellationToken):this
        -321 (-7.59% of base) : 163578.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Float_Overflow()
        -285 (-9.78% of base) : 163585.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Double_NaN()
        -285 (-9.27% of base) : 163579.dasm - System.Linq.Parallel.Tests.SumTests:Sum_Float_NaN()
        -213 (-16.32% of base) : 162928.dasm - System.Linq.Parallel.Tests.ConcatTests:Concat_UnionSources_PrematureMerges()
        -180 (-6.57% of base) : 338772.dasm - System.Threading.Tasks.Test.ParallelStateTest:RealRun():this
        -149 (-5.27% of base) : 118501.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:WithTypeInternal(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.SyntaxNode):Microsoft.CodeAnalysis.SyntaxNode
        -124 (-5.91% of base) : 121025.dasm - Microsoft.CodeAnalysis.VisualBasic.Extensions.ContextQuery.SyntaxTreeExtensions:IsQueryIntoClauseContext(Microsoft.CodeAnalysis.SyntaxTree,int,Microsoft.CodeAnalysis.SyntaxToken,System.Threading.CancellationToken):bool
        -120 (-3.38% of base) : 8242.dasm - Microsoft.CodeAnalysis.PatternMatching.PatternMatcher:NonFuzzyMatchPatternChunk(System.String,byref,bool):System.Nullable`1[PatternMatch]:this
        -115 (-6.16% of base) : 122895.dasm - TypeInferrer:InferTypeInTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.TernaryConditionalExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken):System.Collections.Generic.IEnumerable`1[TypeInferenceInfo]:this
        -110 (-15.67% of base) : 118129.dasm - Microsoft.CodeAnalysis.CSharp.Extensions.ContextQuery.SyntaxTokenExtensions:IsLastTokenOfQueryClause(Microsoft.CodeAnalysis.SyntaxToken):bool
        -109 (-25.12% of base) : 121746.dasm - Microsoft.CodeAnalysis.VisualBasic.LanguageServices.VisualBasicSyntaxFacts:GetDeclarationIdentifierIfOverride(Microsoft.CodeAnalysis.SyntaxToken):System.Nullable`1[SyntaxToken]:this
        -107 (-1.27% of base) : 118986.dasm - TypeInferrer:InferTypesWorker_DoNotCallDirectly(int):System.Collections.Generic.IEnumerable`1[TypeInferenceInfo]:this
        -106 (-8.50% of base) : 122931.dasm - TypeInferrer:InferTypeInBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.BinaryConditionalExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SyntaxToken):System.Collections.Generic.IEnumerable`1[TypeInferenceInfo]:this
        -105 (-15.67% of base) : 165206.dasm - <>c:<Except_NoDuplicateSettings>b__26_1():System.Object:this
        -105 (-15.81% of base) : 165207.dasm - <>c:<Except_NoDuplicateSettings>b__26_2():System.Object:this
        -105 (-15.81% of base) : 165208.dasm - <>c:<Except_NoDuplicateSettings>b__26_3():System.Object:this

Top method regressions (percentages):
          56 (10.11% of base) : 268902.dasm - System.Collections.Immutable.Tests.ImmutableStackTest:EnumeratorTestHelper(System.__Canon[]):this
         659 ( 5.18% of base) : 94903.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:WriteNumbers(bool,bool,System.String):this
           5 ( 4.72% of base) : 134544.dasm - NuGet.Packaging.PackagePathHelper:FileNameMatchesPattern(NuGet.Packaging.Core.PackageIdentity,System.String):bool
           5 ( 3.79% of base) : 177865.dasm - System.Net.Http.Headers.NameValueHeaderValue:GetHashCode(System.Net.Http.Headers.UnvalidatedObjectCollection`1[[System.Net.Http.Headers.NameValueHeaderValue, System.Net.Http.Unit.Tests, Version=7.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51]]):int
           5 ( 3.29% of base) : 177946.dasm - System.Net.Http.Headers.RangeHeaderValue:GetHashCode():int:this
          25 ( 2.90% of base) : 336509.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostAllThenReceive():this
          15 ( 2.84% of base) : 137986.dasm - NuGet.Protocol.Plugins.MessageDispatcher:OnMessageReceived(System.Object,NuGet.Protocol.Plugins.MessageEventArgs):this
           5 ( 2.51% of base) : 2558.dasm - Microsoft.CodeAnalysis.DocumentState:GetNewTreeVersionForUpdatedTree(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.VersionStamp,int):Microsoft.CodeAnalysis.VersionStamp:this
          33 ( 2.19% of base) : 11003.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Byte][System.Byte]:ComputeEditPaths(ubyte,int,ubyte,int):VStack:this
          33 ( 2.19% of base) : 11008.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Int16][System.Int16]:ComputeEditPaths(short,int,short,int):VStack:this
          24 ( 2.16% of base) : 336507.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostThenReceive2():this
          41 ( 2.00% of base) : 94619.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestSingleStringsMultiSegment()
          25 ( 1.85% of base) : 11016.dasm - Microsoft.CodeAnalysis.Differencing.LongestCommonSubsequence`1[Double][System.Double]:ComputeEditPaths(double,int,double,int):VStack:this
           4 ( 1.79% of base) : 219744.dasm - System.Data.SqlClient.SqlSequentialTextReader:InternalRead(System.Char[],int,int):int:this
           4 ( 1.79% of base) : 215464.dasm - System.Data.SqlClient.SqlSequentialTextReader:InternalRead(System.Char[],int,int):int:this
           3 ( 1.70% of base) : 267043.dasm - <>c__DisplayClass16_0:<TryPopRange_InvalidArguments_Throws>b__3():System.Object:this
           3 ( 1.70% of base) : 267044.dasm - <>c__DisplayClass16_0:<TryPopRange_InvalidArguments_Throws>b__4():System.Object:this
          24 ( 1.68% of base) : 336508.dasm - System.Threading.Tasks.Dataflow.Tests.BatchedJoinBlockTests:TestPostThenReceive3():this
           5 ( 1.58% of base) : 2501.dasm - Microsoft.CodeAnalysis.Document:TryGetSyntaxRoot(byref):bool:this
          21 ( 1.49% of base) : 4279.dasm - Microsoft.CodeAnalysis.FlowAnalysis.CustomDataFlowAnalysis`1[Int64][System.Int64]:RunCore(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.FlowAnalysis.DataFlowAnalyzer`1[Int64],int,int,long,Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.FlowAnalysis.BasicBlock, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.SortedSet`1[Int32],Microsoft.CodeAnalysis.PooledObjects.PooledDictionary`2[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],Microsoft.CodeAnalysis.PooledObjects.PooledHashSet`1[[Microsoft.CodeAnalysis.FlowAnalysis.ControlFlowRegion, Microsoft.CodeAnalysis, Version=4.2.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Threading.CancellationToken):long

Top method improvements (percentages):
         -91 (-33.33% of base) : 11618.dasm - Microsoft.CodeAnalysis.Diagnostics.Analyzers.NamingStyles.MutableNamingStyle:.ctor():this
         -58 (-32.95% of base) : 165561.dasm - <>c:<Max_AggregateException_NotComparable>b__32_0():this
         -58 (-32.95% of base) : 165710.dasm - <>c:<Min_AggregateException_NotComparable>b__34_0():this
         -58 (-30.69% of base) : 166587.dasm - <>c:<DegreeOfParallelism_Multiple>b__9_0():System.Object:this
         -55 (-30.56% of base) : 164783.dasm - <>c:<Aggregate_ArgumentNullException>b__32_1():System.Object:this
         -55 (-30.56% of base) : 164785.dasm - <>c:<Aggregate_ArgumentNullException>b__32_3():System.Object:this
         -55 (-30.56% of base) : 164914.dasm - <>c:<Average_ArgumentNullException>b__27_1():System.Object:this
         -55 (-30.56% of base) : 164922.dasm - <>c:<Average_ArgumentNullException>b__27_9():System.Object:this
         -55 (-30.56% of base) : 165077.dasm - <>c:<Concat_ArgumentNullException>b__12_0():System.Object:this
         -55 (-30.56% of base) : 165078.dasm - <>c:<Concat_ArgumentNullException>b__12_1():System.Object:this
         -55 (-30.56% of base) : 165298.dasm - <>c:<ForAll_ArgumentNullException>b__6_1():this
         -55 (-30.56% of base) : 165324.dasm - <>c:<GroupBy_ArgumentNullException>b__33_1():System.Object:this
         -55 (-30.56% of base) : 165565.dasm - <>c:<Max_ArgumentNullException>b__33_1():System.Object:this
         -55 (-30.56% of base) : 165585.dasm - <>c:<Max_ArgumentNullException>b__33_21():System.Object:this
         -55 (-30.56% of base) : 165573.dasm - <>c:<Max_ArgumentNullException>b__33_9():System.Object:this
         -55 (-30.56% of base) : 165713.dasm - <>c:<Min_ArgumentNullException>b__35_1():System.Object:this
         -55 (-30.56% of base) : 165733.dasm - <>c:<Min_ArgumentNullException>b__35_21():System.Object:this
         -55 (-30.56% of base) : 165721.dasm - <>c:<Min_ArgumentNullException>b__35_9():System.Object:this
         -55 (-30.56% of base) : 165892.dasm - <>c:<OrderBy_ArgumentNullException>b__40_1():System.Object:this
         -55 (-30.56% of base) : 165887.dasm - <>c:<OrderByDescending_ArgumentNullException>b__41_1():System.Object:this

1659 total methods with Code Size differences (1530 improved, 129 regressed), 1097 unchanged.

```

</details>

--------------------------------------------------------------------------------

