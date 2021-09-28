## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 245006
Total bytes of diff: 244766
Total bytes of delta: -240 (-0.10% of base)
Total relative delta: -0.92
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         110 : 218094.dasm (0.11% of base)
         110 : 214339.dasm (0.11% of base)

Top file improvements (bytes):
         -64 : 235824.dasm (-1.82% of base)
         -64 : 235820.dasm (-1.97% of base)
         -64 : 235822.dasm (-1.88% of base)
         -64 : 235818.dasm (-1.94% of base)
         -64 : 235816.dasm (-2.01% of base)
         -18 : 84838.dasm (-3.11% of base)
          -8 : 233325.dasm (-3.05% of base)
          -6 : 84957.dasm (-1.13% of base)
          -4 : 252045.dasm (-0.15% of base)
          -2 : 141.dasm (-0.30% of base)
          -2 : 196746.dasm (-1.54% of base)
          -2 : 196750.dasm (-1.32% of base)
          -2 : 227922.dasm (-2.70% of base)
          -2 : 230069.dasm (-2.22% of base)
          -2 : 230499.dasm (-2.44% of base)
          -2 : 230633.dasm (-2.70% of base)
          -2 : 234716.dasm (-1.64% of base)
          -2 : 238213.dasm (-0.92% of base)
          -2 : 82413.dasm (-0.68% of base)
          -2 : 180089.dasm (-1.43% of base)

63 total files with Code Size differences (61 improved, 2 regressed), 2 unchanged.

Top method regressions (bytes):
         110 ( 0.11% of base) : 218094.dasm - testout1:Func_0():int
         110 ( 0.11% of base) : 214339.dasm - testout1:Func_0():int

Top method improvements (bytes):
         -64 (-1.82% of base) : 235824.dasm - VectorGetTest`1[Int64][System.Int64]:VectorGet(long,int):int
         -64 (-1.97% of base) : 235820.dasm - VectorGetTest`1[Int32][System.Int32]:VectorGet(int,int):int
         -64 (-1.88% of base) : 235822.dasm - VectorGetTest`1[Double][System.Double]:VectorGet(double,int):int
         -64 (-1.94% of base) : 235818.dasm - VectorGetTest`1[Int16][System.Int16]:VectorGet(short,int):int
         -64 (-2.01% of base) : 235816.dasm - VectorGetTest`1[Byte][System.Byte]:VectorGet(ubyte,int):int
         -18 (-3.11% of base) : 84838.dasm - ILGEN_0xace3f910:Method_0xf9cc7d6a(long,long,float,int,ushort,int,long,long,long):float
          -8 (-3.05% of base) : 233325.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -6 (-1.13% of base) : 84957.dasm - DevDiv_605447:ILGEN_METHOD(int,int,int,ushort,float):ushort
          -4 (-0.15% of base) : 252045.dasm - GitHub_23861.Program:TestVectorLessThanAll()
          -2 (-0.30% of base) : 141.dasm - System.Text.RegularExpressions.RegexRunner:Scan(System.Text.RegularExpressions.Regex,System.String,int,byref,System.Text.RegularExpressions.MatchCallback`1[ValueTuple`5],bool,System.TimeSpan):this
          -2 (-1.54% of base) : 196746.dasm - NullableTest2:BoxUnboxToNQGen(ubyte):bool
          -2 (-1.32% of base) : 196750.dasm - NullableTest2:BoxUnboxToNQGen(System.Numerics.Vector`1[Single]):bool
          -2 (-2.70% of base) : 227922.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -2 (-2.22% of base) : 230069.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -2 (-2.44% of base) : 230499.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -2 (-2.70% of base) : 230633.dasm - NullableTest:BoxUnboxToNQ(System.ValueType):bool
          -2 (-1.64% of base) : 234716.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
          -2 (-0.92% of base) : 238213.dasm - VectorTest:compareMMPoint(Matrix`1[Byte],Matrix`1[Byte],int,int):ubyte
          -2 (-0.68% of base) : 82413.dasm - System.Net.Sockets.SafeSocketHandle:CloseHandle(bool,bool):bool:this
          -2 (-1.43% of base) : 180089.dasm - NullableTest2:BoxUnboxToNQGen(long):bool

Top method regressions (percentages):
         110 ( 0.11% of base) : 214339.dasm - testout1:Func_0():int
         110 ( 0.11% of base) : 218094.dasm - testout1:Func_0():int

Top method improvements (percentages):
         -18 (-3.11% of base) : 84838.dasm - ILGEN_0xace3f910:Method_0xf9cc7d6a(long,long,float,int,ushort,int,long,long,long):float
          -8 (-3.05% of base) : 233325.dasm - GCSimulator.ClientSimulator:objectDied(GCSimulator.LifeTime,int)
          -2 (-2.70% of base) : 227922.dasm - NullableTest:BoxUnboxToNQ(System.IComparable):bool
          -2 (-2.70% of base) : 230633.dasm - NullableTest:BoxUnboxToNQ(System.ValueType):bool
          -2 (-2.70% of base) : 230497.dasm - NullableTest:BoxUnboxToNQ(System.__Canon):bool
          -2 (-2.44% of base) : 230499.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -2 (-2.44% of base) : 230068.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -2 (-2.44% of base) : 230498.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -2 (-2.44% of base) : 230066.dasm - NullableTest:BoxUnboxToNQ(ubyte):bool
          -2 (-2.44% of base) : 230500.dasm - NullableTest:BoxUnboxToNQ(int):bool
          -2 (-2.44% of base) : 230067.dasm - NullableTest:BoxUnboxToNQ(short):bool
          -2 (-2.22% of base) : 230069.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -2 (-2.22% of base) : 230501.dasm - NullableTest:BoxUnboxToNQ(double):bool
          -2 (-2.17% of base) : 230071.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -2 (-2.17% of base) : 230503.dasm - NullableTest:BoxUnboxToNQ(long):bool
          -2 (-2.13% of base) : 234476.dasm - NullableTest:BoxUnboxToNQ(System.Object):bool
         -64 (-2.01% of base) : 235816.dasm - VectorGetTest`1[Byte][System.Byte]:VectorGet(ubyte,int):int
         -64 (-1.97% of base) : 235820.dasm - VectorGetTest`1[Int32][System.Int32]:VectorGet(int,int):int
          -2 (-1.96% of base) : 230502.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool
          -2 (-1.96% of base) : 230070.dasm - NullableTest:BoxUnboxToNQ(System.Numerics.Vector`1[Single]):bool

63 total methods with Code Size differences (61 improved, 2 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 358494
Total bytes of diff: 357380
Total bytes of delta: -1114 (-0.31% of base)
Total relative delta: -3.19
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 130492.dasm (1.18% of base)
           2 : 202777.dasm (0.19% of base)
           2 : 130886.dasm (0.25% of base)

Top file improvements (bytes):
         -12 : 89267.dasm (-1.13% of base)
         -12 : 93171.dasm (-0.59% of base)
         -10 : 86457.dasm (-1.93% of base)
         -10 : 205111.dasm (-0.48% of base)
         -10 : 53794.dasm (-0.23% of base)
         -10 : 86437.dasm (-0.37% of base)
          -8 : 86289.dasm (-3.51% of base)
          -8 : 10439.dasm (-0.43% of base)
          -8 : 6332.dasm (-0.05% of base)
          -8 : 198753.dasm (-1.88% of base)
          -8 : 86425.dasm (-0.29% of base)
          -8 : 86386.dasm (-0.19% of base)
          -8 : 59457.dasm (-0.78% of base)
          -8 : 92889.dasm (-0.32% of base)
          -6 : 128846.dasm (-2.97% of base)
          -6 : 56618.dasm (-0.16% of base)
          -6 : 69749.dasm (-0.59% of base)
          -6 : 166651.dasm (-1.41% of base)
          -6 : 53853.dasm (-0.13% of base)
          -6 : 86273.dasm (-0.34% of base)

409 total files with Code Size differences (406 improved, 3 regressed), 11 unchanged.

Top method regressions (bytes):
           2 ( 1.18% of base) : 130492.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:GetHashCode():int:this
           2 ( 0.19% of base) : 202777.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.__Canon[]:this
           2 ( 0.25% of base) : 130886.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:FindMethodSymbolInSuperType(System.Reflection.Metadata.TypeDefinitionHandle,System.Reflection.Metadata.MethodDefinitionHandle):System.__Canon:this

Top method improvements (bytes):
         -12 (-1.13% of base) : 89267.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourcePropertySymbol:EnsureSignature():this
         -12 (-0.59% of base) : 93171.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -10 (-1.93% of base) : 86457.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -10 (-0.48% of base) : 205111.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -10 (-0.23% of base) : 53794.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteEnumeratorForEachStatement(Microsoft.CodeAnalysis.CSharp.BoundForEachStatement):Microsoft.CodeAnalysis.CSharp.BoundStatement:this
         -10 (-0.37% of base) : 86437.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteForEachIEnumerable(Microsoft.CodeAnalysis.VisualBasic.BoundForEachStatement,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol]):this
          -8 (-3.51% of base) : 86289.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:ApplyUnliftedUnaryOp(Microsoft.CodeAnalysis.VisualBasic.BoundUnaryOperator,Microsoft.CodeAnalysis.VisualBasic.BoundExpression):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -8 (-0.43% of base) : 10439.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadTemplate(System.Xml.Xsl.Xslt.NsDecl):this
          -8 (-0.05% of base) : 6332.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
          -8 (-1.88% of base) : 198753.dasm - System.Net.Mail.SmtpClient:SendMailCallback(System.IAsyncResult):this
          -8 (-0.29% of base) : 86425.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteIfStatement(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,Microsoft.CodeAnalysis.VisualBasic.BoundStatement,bool,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundStatement]):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
          -8 (-0.19% of base) : 86386.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:EnforceStaticLocalInitializationSemantics(System.Collections.Generic.KeyValuePair`2[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField, Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedStaticLocalBackingField],Microsoft.CodeAnalysis.VisualBasic.BoundStatement):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
          -8 (-0.78% of base) : 59457.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindCollectionInitializerElementAddMethod(Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],bool,Microsoft.CodeAnalysis.CSharp.Binder,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.BoundImplicitReceiver):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -8 (-0.32% of base) : 92889.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindMethodBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBlockBaseSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
          -6 (-2.97% of base) : 128846.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -6 (-0.16% of base) : 56618.dasm - Microsoft.CodeAnalysis.CSharp.MethodCompiler:CompileMethod(Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,int,byref,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.TypeCompilationState):this
          -6 (-0.59% of base) : 69749.dasm - RetargetedTypeMethodFinder:FindWorker(Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingModuleSymbol+RetargetingSymbolTranslator,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.NamedTypeSymbol,System.Collections.Generic.IEqualityComparer`1[Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol]):Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol
          -6 (-1.41% of base) : 166651.dasm - ScopeManager:TranslateImport(System.ComponentModel.Composition.Primitives.ImportDefinition):System.ComponentModel.Composition.Primitives.ImportDefinition
          -6 (-0.13% of base) : 53853.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:TransformCompoundAssignmentLHS(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.CSharp.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol],bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -6 (-0.34% of base) : 86273.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitUsingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUsingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method regressions (percentages):
           2 ( 1.18% of base) : 130492.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:GetHashCode():int:this
           2 ( 0.25% of base) : 130886.dasm - Microsoft.CodeAnalysis.MetadataDecoder`5:FindMethodSymbolInSuperType(System.Reflection.Metadata.TypeDefinitionHandle,System.Reflection.Metadata.MethodDefinitionHandle):System.__Canon:this
           2 ( 0.19% of base) : 202777.dasm - System.Linq.Parallel.QueryOperator`1:ExecuteAndGetResultsAsArray():System.__Canon[]:this

Top method improvements (percentages):
          -2 (-6.25% of base) : 40644.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.DynamicTypeDecoder:ConsumeFlag():bool:this
          -4 (-5.71% of base) : 192426.dasm - CommandLine.NamedError:GetHashCode():int:this
          -4 (-5.71% of base) : 192431.dasm - CommandLine.TokenError:GetHashCode():int:this
          -4 (-4.76% of base) : 93987.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-3.85% of base) : 94580.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -4 (-3.57% of base) : 58310.dasm - Microsoft.CodeAnalysis.CSharp.MethodTypeInferrer:InferTypeArgs(Microsoft.CodeAnalysis.CSharp.Binder,byref):Microsoft.CodeAnalysis.CSharp.MethodTypeInferenceResult:this
          -8 (-3.51% of base) : 86289.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:ApplyUnliftedUnaryOp(Microsoft.CodeAnalysis.VisualBasic.BoundUnaryOperator,Microsoft.CodeAnalysis.VisualBasic.BoundExpression):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-3.45% of base) : 39948.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -2 (-3.33% of base) : 94028.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-3.33% of base) : 94029.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-2.99% of base) : 173892.dasm - CredentialEnumerator:MoveNext():bool:this
          -6 (-2.97% of base) : 128846.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -4 (-2.94% of base) : 26185.dasm - leftJustify@875-4:Invoke(System.String,int,System.Object):System.String:this
          -2 (-2.86% of base) : 131315.dasm - Microsoft.CodeAnalysis.PreprocessingSymbolInfo:GetHashCode():int:this
          -2 (-2.78% of base) : 94021.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalGoto):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-2.78% of base) : 57620.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeRewriter:VisitConditionalGoto(Microsoft.CodeAnalysis.CSharp.BoundConditionalGoto):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -2 (-2.63% of base) : 112010.dasm - TryWriteInterpolatedStringHandler:.ctor(int,int,System.Span`1[System.Char],byref):this
          -4 (-2.56% of base) : 44795.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.56% of base) : 44796.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -2 (-2.50% of base) : 192386.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[System.String],System.Collections.Generic.IEnumerable`1[CommandLine.Core.OptionSpecification],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[System.Collections.Generic.IEnumerable`1[CommandLine.Core.Token], CommandLine.Error]

409 total methods with Code Size differences (406 improved, 3 regressed), 11 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 302772
Total bytes of diff: 301502
Total bytes of delta: -1270 (-0.42% of base)
Total relative delta: -3.93
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 216801.dasm (1.47% of base)
           4 : 195356.dasm (1.87% of base)
           2 : 112177.dasm (0.04% of base)
           2 : 210526.dasm (0.72% of base)

Top file improvements (bytes):
         -16 : 18775.dasm (-0.55% of base)
         -16 : 25661.dasm (-2.23% of base)
         -14 : 98317.dasm (-0.24% of base)
         -12 : 166610.dasm (-0.48% of base)
         -10 : 25705.dasm (-0.93% of base)
          -8 : 26134.dasm (-5.71% of base)
          -8 : 109699.dasm (-0.28% of base)
          -8 : 114915.dasm (-3.81% of base)
          -8 : 25489.dasm (-3.74% of base)
          -8 : 62985.dasm (-9.09% of base)
          -6 : 113880.dasm (-0.54% of base)
          -6 : 125572.dasm (-1.85% of base)
          -6 : 125595.dasm (-1.85% of base)
          -6 : 54835.dasm (-0.31% of base)
          -6 : 54839.dasm (-0.35% of base)
          -6 : 125596.dasm (-1.85% of base)
          -6 : 125618.dasm (-2.29% of base)
          -6 : 25727.dasm (-0.27% of base)
          -6 : 114476.dasm (-0.58% of base)
          -6 : 17733.dasm (-6.12% of base)

476 total files with Code Size differences (472 improved, 4 regressed), 19 unchanged.

Top method regressions (bytes):
           4 ( 1.47% of base) : 216801.dasm - System.Net.Mail.SmtpClient:ContextSafeCompleteCallback(System.IAsyncResult)
           4 ( 1.87% of base) : 195356.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this
           2 ( 0.04% of base) : 112177.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:MakeSubmissionInitialization(Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundStatement, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.CSharpCompilation)
           2 ( 0.72% of base) : 210526.dasm - CommandLine.Core.SpecificationExtensions:WithLongName(CommandLine.Core.OptionSpecification,System.String):CommandLine.Core.OptionSpecification

Top method improvements (bytes):
         -16 (-0.55% of base) : 18775.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:TryDefaultInstanceProperty(Microsoft.CodeAnalysis.VisualBasic.BoundTypeExpression,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -16 (-2.23% of base) : 25661.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteFloatingToIntegralConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -14 (-0.24% of base) : 98317.dasm - System.Configuration.BaseConfigurationRecord:ScanFactoriesRecursive(System.Configuration.XmlUtil,System.String,System.Collections.Hashtable):this
         -12 (-0.48% of base) : 166610.dasm - System.DirectoryServices.Protocols.DirectoryControl:TransformControls(System.DirectoryServices.Protocols.DirectoryControl[])
         -10 (-0.93% of base) : 25705.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:FinishRewriteNullableConversion(Microsoft.CodeAnalysis.VisualBasic.BoundConversion,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.LocalSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -8 (-5.71% of base) : 26134.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -8 (-0.28% of base) : 109699.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CreateUserDefinedConversion(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -8 (-3.81% of base) : 114915.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -8 (-3.74% of base) : 25489.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:ApplyUnliftedUnaryOp(Microsoft.CodeAnalysis.VisualBasic.BoundUnaryOperator,Microsoft.CodeAnalysis.VisualBasic.BoundExpression):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -8 (-9.09% of base) : 62985.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:WithAliases(System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.MetadataReferenceProperties:this
          -6 (-0.54% of base) : 113880.dasm - Microsoft.CodeAnalysis.CSharp.DeclarationTreeBuilder:CreateScriptRootDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.CompilationUnitSyntax):Microsoft.CodeAnalysis.CSharp.RootSingleNamespaceDeclaration:this
          -6 (-1.85% of base) : 125572.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -6 (-1.85% of base) : 125595.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          -6 (-0.31% of base) : 54835.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadDecimalFormat(System.Xml.Xsl.Xslt.NsDecl):this
          -6 (-0.35% of base) : 54839.dasm - System.Xml.Xsl.Xslt.XsltLoader:LoadTemplate(System.Xml.Xsl.Xslt.NsDecl):this
          -6 (-1.85% of base) : 125596.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElifDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -6 (-2.29% of base) : 125618.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ElseDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          -6 (-0.27% of base) : 25727.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteLiftedBooleanBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,bool,bool,bool,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -6 (-0.58% of base) : 114476.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckCompoundAssignmentOperator(Microsoft.CodeAnalysis.CSharp.BoundCompoundAssignmentOperator):this
          -6 (-6.12% of base) : 17733.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

Top method regressions (percentages):
           4 ( 1.87% of base) : 195356.dasm - System.Net.WebClient:DownloadFileAsyncCallback(System.Byte[],System.Exception,System.Object):this
           4 ( 1.47% of base) : 216801.dasm - System.Net.Mail.SmtpClient:ContextSafeCompleteCallback(System.IAsyncResult)
           2 ( 0.72% of base) : 210526.dasm - CommandLine.Core.SpecificationExtensions:WithLongName(CommandLine.Core.OptionSpecification,System.String):CommandLine.Core.OptionSpecification
           2 ( 0.04% of base) : 112177.dasm - Microsoft.CodeAnalysis.CSharp.MethodBodySynthesizer:MakeSubmissionInitialization(Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundStatement, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Symbols.MethodSymbol,Microsoft.CodeAnalysis.CSharp.SynthesizedSubmissionFields,Microsoft.CodeAnalysis.CSharp.CSharpCompilation)

Top method improvements (percentages):
          -8 (-9.09% of base) : 62985.dasm - Microsoft.CodeAnalysis.MetadataReferenceProperties:WithAliases(System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Microsoft.CodeAnalysis.MetadataReferenceProperties:this
          -6 (-7.89% of base) : 25789.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitArrayCreation(Microsoft.CodeAnalysis.VisualBasic.BoundArrayCreation):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -6 (-6.12% of base) : 17733.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitUnstructuredExceptionHandlingStatement(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-6.06% of base) : 210119.dasm - CommandLine.TokenError:GetHashCode():int:this
          -4 (-6.06% of base) : 210124.dasm - CommandLine.NamedError:GetHashCode():int:this
          -8 (-5.71% of base) : 26134.dasm - Microsoft.CodeAnalysis.VisualBasic.WithExpressionRewriter:CaptureFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,State):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -2 (-4.76% of base) : 17209.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundParameter:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundParameter:this
          -2 (-3.85% of base) : 17752.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitPseudoVariable(Microsoft.CodeAnalysis.VisualBasic.BoundPseudoVariable):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-3.85% of base) : 17753.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitParameter(Microsoft.CodeAnalysis.VisualBasic.BoundParameter):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -8 (-3.81% of base) : 114915.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:VisitCall(Microsoft.CodeAnalysis.CSharp.BoundCall):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -8 (-3.74% of base) : 25489.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:ApplyUnliftedUnaryOp(Microsoft.CodeAnalysis.VisualBasic.BoundUnaryOperator,Microsoft.CodeAnalysis.VisualBasic.BoundExpression):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          -4 (-3.51% of base) : 17778.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundTreeRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-3.45% of base) : 17005.dasm - Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:MakeRValue():Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess:this
          -6 (-3.26% of base) : 64734.dasm - Microsoft.CodeAnalysis.Emit.EmitOptions:.ctor(Microsoft.CodeAnalysis.Emit.EmitOptions):this
          -4 (-3.12% of base) : 25673.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitFieldAccess(Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -2 (-3.03% of base) : 210168.dasm - CommandLine.Parser:Tokenize(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.IEnumerable`1[[CommandLine.Core.OptionSpecification, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]],CommandLine.ParserSettings):RailwaySharp.ErrorHandling.Result`2[[System.Collections.Generic.IEnumerable`1[[CommandLine.Core.Token, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[CommandLine.Error, commandline, Version=2.0.275.0, Culture=neutral, PublicKeyToken=de6f01bd326f8c32]]
          -2 (-2.94% of base) : 114418.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitAddressOfOperator(Microsoft.CodeAnalysis.CSharp.BoundAddressOfOperator):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -2 (-2.63% of base) : 114431.dasm - Microsoft.CodeAnalysis.CSharp.AwaitExpressionSpiller:VisitDelegateCreationExpression(Microsoft.CodeAnalysis.CSharp.BoundDelegateCreationExpression):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          -6 (-2.61% of base) : 25662.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitDirectCast(Microsoft.CodeAnalysis.VisualBasic.BoundDirectCast):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -4 (-2.41% of base) : 26124.dasm - Microsoft.CodeAnalysis.VisualBasic.UseTwiceRewriter:UseTwiceFieldAccess(Microsoft.CodeAnalysis.VisualBasic.Symbol,Microsoft.CodeAnalysis.VisualBasic.BoundFieldAccess,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.SynthesizedLocal, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Result

476 total methods with Code Size differences (472 improved, 4 regressed), 19 unchanged.

```

</details>

--------------------------------------------------------------------------------
