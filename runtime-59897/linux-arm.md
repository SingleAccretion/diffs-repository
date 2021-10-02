## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1765900
Total bytes of diff: 1749692
Total bytes of delta: -16208 (-0.92% of base)
Total relative delta: -42.92
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          22 : 205139.dasm (1.27% of base)
          22 : 205142.dasm (1.27% of base)
          22 : 206119.dasm (1.27% of base)
          22 : 206122.dasm (1.27% of base)
           2 : 174578.dasm (0.17% of base)
           2 : 174953.dasm (0.17% of base)
           2 : 181906.dasm (0.17% of base)

Top file improvements (bytes):
       -1102 : 221682.dasm (-35.80% of base)
        -318 : 221680.dasm (-14.43% of base)
        -212 : 187721.dasm (-1.11% of base)
        -154 : 210260.dasm (-1.98% of base)
        -154 : 210661.dasm (-2.04% of base)
        -154 : 209318.dasm (-2.04% of base)
        -154 : 217008.dasm (-1.98% of base)
        -154 : 213832.dasm (-2.21% of base)
        -154 : 216879.dasm (-2.21% of base)
        -136 : 171737.dasm (-2.44% of base)
        -100 : 220885.dasm (-6.08% of base)
        -100 : 217863.dasm (-4.56% of base)
        -100 : 225238.dasm (-2.12% of base)
        -100 : 223083.dasm (-2.12% of base)
        -100 : 223155.dasm (-2.12% of base)
        -100 : 223398.dasm (-4.56% of base)
        -100 : 224220.dasm (-5.08% of base)
        -100 : 224427.dasm (-6.08% of base)
        -100 : 224428.dasm (-2.12% of base)
        -100 : 225577.dasm (-6.08% of base)

2476 total files with Code Size differences (2469 improved, 7 regressed), 14 unchanged.

Top method regressions (bytes):
          22 ( 1.27% of base) : 205139.dasm - VectorConvertTest:VectorConvertInt16And8(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):int
          22 ( 1.27% of base) : 205142.dasm - VectorConvertTest:VectorConvertUInt16And8(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):int
          22 ( 1.27% of base) : 206119.dasm - VectorConvertTest:VectorConvertInt16And8(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):int
          22 ( 1.27% of base) : 206122.dasm - VectorConvertTest:VectorConvertUInt16And8(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):int
           2 ( 0.17% of base) : 174578.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this
           2 ( 0.17% of base) : 174953.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this
           2 ( 0.17% of base) : 181906.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this

Top method improvements (bytes):
       -1102 (-35.80% of base) : 221682.dasm - GCHandleTest:GetTargetTest():this
        -318 (-14.43% of base) : 221680.dasm - GCHandleTest:FreeTest():this
        -212 (-1.11% of base) : 187721.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
        -154 (-1.98% of base) : 210260.dasm - Test:Main():int
        -154 (-2.04% of base) : 210661.dasm - Test:Main():int
        -154 (-2.04% of base) : 209318.dasm - Test:Main():int
        -154 (-1.98% of base) : 217008.dasm - Test:Main():int
        -154 (-2.21% of base) : 213832.dasm - Test:Main():int
        -154 (-2.21% of base) : 216879.dasm - Test:Main():int
        -136 (-2.44% of base) : 171737.dasm - TailcallVerify.Program:Run(System.String):int
        -100 (-6.08% of base) : 220885.dasm - Test:Main():int
        -100 (-4.56% of base) : 217863.dasm - Test:Main():int
        -100 (-2.12% of base) : 225238.dasm - Test:Main():int
        -100 (-2.12% of base) : 223083.dasm - Test:Main():int
        -100 (-2.12% of base) : 223155.dasm - Test:Main():int
        -100 (-4.56% of base) : 223398.dasm - Test:Main():int
        -100 (-5.08% of base) : 224220.dasm - Test:Main():int
        -100 (-6.08% of base) : 224427.dasm - Test:Main():int
        -100 (-2.12% of base) : 224428.dasm - Test:Main():int
        -100 (-6.08% of base) : 225577.dasm - Test:Main():int

Top method regressions (percentages):
          22 ( 1.27% of base) : 205139.dasm - VectorConvertTest:VectorConvertInt16And8(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):int
          22 ( 1.27% of base) : 205142.dasm - VectorConvertTest:VectorConvertUInt16And8(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):int
          22 ( 1.27% of base) : 206119.dasm - VectorConvertTest:VectorConvertInt16And8(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):int
          22 ( 1.27% of base) : 206122.dasm - VectorConvertTest:VectorConvertUInt16And8(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):int
           2 ( 0.17% of base) : 174578.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this
           2 ( 0.17% of base) : 174953.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this
           2 ( 0.17% of base) : 181906.dasm - IntelHardwareIntrinsicTest.TestTableSse2`2[Byte,Int64][System.Byte,System.Int64]:InitializeWithVectorNumbering():this

Top method improvements (percentages):
       -1102 (-35.80% of base) : 221682.dasm - GCHandleTest:GetTargetTest():this
         -28 (-34.15% of base) : 80161.dasm - GCUtil:GetTarget(System.Runtime.InteropServices.GCHandle):System.Object
         -16 (-29.63% of base) : 84829.dasm - ILGEN_CLASS:ILGEN_METHOD(int):ubyte
         -28 (-17.72% of base) : 234434.dasm - DefaultNamespace.NDPinFinal:Finalize():this
         -76 (-15.97% of base) : 211451.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
         -76 (-15.97% of base) : 215950.dasm - PartialCompactionTest.PartialCompactionTest:UpdateReferences()
         -50 (-15.53% of base) : 85534.dasm - C:M(bool,bool):int
        -318 (-14.43% of base) : 221680.dasm - GCHandleTest:FreeTest():this
         -46 (-14.11% of base) : 219626.dasm - Program:Main(System.String[]):int
         -46 (-14.11% of base) : 215954.dasm - PartialCompactionTest.PartialCompactionTest:CleanupWeakReferenceArr()
         -46 (-14.11% of base) : 211455.dasm - PartialCompactionTest.PartialCompactionTest:CleanupWeakReferenceArr()
         -46 (-13.86% of base) : 215957.dasm - PartialCompactionTest.PartialCompactionTest:AddRefTo(System.Object)
         -46 (-13.86% of base) : 211461.dasm - PartialCompactionTest.PartialCompactionTest:AddRefTo(System.Object)
         -46 (-13.77% of base) : 215956.dasm - PartialCompactionTest.PartialCompactionTest:AddRefFrom(System.Object)
         -46 (-13.77% of base) : 211460.dasm - PartialCompactionTest.PartialCompactionTest:AddRefFrom(System.Object)
         -28 (-13.21% of base) : 236136.dasm - CastingTest:CastTest():bool:this
         -28 (-13.21% of base) : 233933.dasm - ToFromIntPtrTest:ToFromTest():bool:this
         -28 (-12.61% of base) : 215952.dasm - PartialCompactionTest.PartialCompactionTest:RemoveAllPinnedObjects()
         -28 (-12.61% of base) : 211453.dasm - PartialCompactionTest.PartialCompactionTest:RemoveAllPinnedObjects()
          -2 (-12.50% of base) : 120406.dasm - Program:Test_ldind_u1_conv_i2(byref,byref)

2476 total methods with Code Size differences (2469 improved, 7 regressed), 14 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 15626202
Total bytes of diff: 15554708
Total bytes of delta: -71494 (-0.46% of base)
Total relative delta: -518.95
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         238 : 58154.dasm (5.75% of base)
         176 : 69431.dasm (5.42% of base)
         146 : 10099.dasm (6.10% of base)
         146 : 9369.dasm (5.19% of base)
         144 : 166971.dasm (2.79% of base)
         132 : 10103.dasm (6.83% of base)
         130 : 6841.dasm (6.74% of base)
         124 : 21413.dasm (4.91% of base)
         122 : 101078.dasm (7.92% of base)
         114 : 64643.dasm (4.81% of base)
         114 : 88977.dasm (5.26% of base)
         106 : 40951.dasm (1.93% of base)
         104 : 10742.dasm (3.72% of base)
         102 : 65703.dasm (6.65% of base)
         100 : 66137.dasm (9.36% of base)
          98 : 186111.dasm (10.36% of base)
          98 : 48866.dasm (2.06% of base)
          96 : 97344.dasm (3.18% of base)
          96 : 9434.dasm (5.54% of base)
          94 : 176859.dasm (2.04% of base)

Top file improvements (bytes):
        -466 : 131003.dasm (-2.81% of base)
        -458 : 199958.dasm (-3.32% of base)
        -270 : 63723.dasm (-1.24% of base)
        -164 : 59709.dasm (-3.17% of base)
        -156 : 76559.dasm (-5.35% of base)
        -138 : 135554.dasm (-2.42% of base)
        -130 : 83312.dasm (-4.28% of base)
        -118 : 48719.dasm (-4.97% of base)
        -116 : 104950.dasm (-4.33% of base)
        -112 : 149245.dasm (-1.87% of base)
        -110 : 4184.dasm (-2.31% of base)
        -108 : 164525.dasm (-0.58% of base)
        -106 : 154463.dasm (-3.22% of base)
        -104 : 196863.dasm (-1.05% of base)
        -100 : 4188.dasm (-2.09% of base)
         -96 : 111396.dasm (-0.81% of base)
         -94 : 4196.dasm (-2.31% of base)
         -94 : 135876.dasm (-0.97% of base)
         -92 : 82189.dasm (-1.79% of base)
         -92 : 83512.dasm (-2.26% of base)

36006 total files with Code Size differences (32360 improved, 3646 regressed), 94 unchanged.

Top method regressions (bytes):
         238 ( 5.75% of base) : 58154.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:ComputeDeclarations(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[Microsoft.CodeAnalysis.SyntaxNode, System.Nullable`1[System.Int32], System.Boolean],bool,System.Collections.Generic.List`1[Microsoft.CodeAnalysis.DeclarationInfo],System.Nullable`1[System.Int32],System.Threading.CancellationToken)
         176 ( 5.42% of base) : 69431.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicDeclarationComputer:ComputeDeclarationsCore(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[Microsoft.CodeAnalysis.SyntaxNode, System.Nullable`1[System.Int32], System.Boolean],bool,System.Collections.Generic.List`1[Microsoft.CodeAnalysis.DeclarationInfo],System.Nullable`1[System.Int32],System.Threading.CancellationToken)
         146 ( 6.10% of base) : 10099.dasm - System.Xml.Schema.Compiler:Compile():bool:this
         146 ( 5.19% of base) : 9369.dasm - System.Xml.Schema.SchemaCollectionCompiler:Compile():this
         144 ( 2.79% of base) : 166971.dasm - System.Data.XmlDataTreeWriter:XmlDataRowWriter(System.Data.DataRow,System.String):this
         132 ( 6.83% of base) : 10103.dasm - System.Xml.Schema.Compiler:Prepare(System.Xml.Schema.XmlSchema,bool):this
         130 ( 6.74% of base) : 6841.dasm - System.Xml.Xsl.Xslt.XslAstAnalyzer:Analyze(System.Xml.Xsl.Xslt.Compiler):int:this
         124 ( 4.91% of base) : 21413.dasm - Newtonsoft.Json.JsonValidatingReader:ValidateCurrentToken():this
         122 ( 7.92% of base) : 101078.dasm - Microsoft.Cci.FullMetadataWriter:CreateIndicesForNonTypeMembers(Microsoft.Cci.ITypeDefinition):this
         114 ( 4.81% of base) : 64643.dasm - Microsoft.CodeAnalysis.CSharp.MethodTypeInferrer:Fix(int,byref):bool:this
         114 ( 5.26% of base) : 88977.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.DeclarationTreeBuilder:GetNonTypeMemberNames(Microsoft.CodeAnalysis.SyntaxList`1[Microsoft.CodeAnalysis.VisualBasic.Syntax.StatementSyntax],byref):System.String[]:this
         106 ( 1.93% of base) : 40951.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceLog:CopyRawEvents(Microsoft.Diagnostics.Tracing.TraceEventDispatcher,FastSerialization.IStreamWriter):this
         104 ( 3.72% of base) : 10742.dasm - System.Xml.XmlLoader:LoadDocumentType(System.Xml.IDtdInfo,System.Xml.XmlDocumentType):this
         102 ( 6.65% of base) : 65703.dasm - Microsoft.CodeAnalysis.CSharp.Binder:AddWinRTMembers(Microsoft.CodeAnalysis.CSharp.LookupResult,Microsoft.CodeAnalysis.CSharp.Symbols.NamedTypeSymbol,System.String,int,int,Microsoft.CodeAnalysis.CSharp.Binder,bool,byref):this
         100 ( 9.36% of base) : 66137.dasm - Microsoft.CodeAnalysis.CSharp.AbstractFlowPass`1:VisitTryStatement(Microsoft.CodeAnalysis.CSharp.BoundTryStatement):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          98 (10.36% of base) : 186111.dasm - System.IO.Compression.ZipArchive:WriteFile():this
          98 ( 2.06% of base) : 48866.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol+MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax],Microsoft.CodeAnalysis.DiagnosticBag):this
          96 ( 3.18% of base) : 97344.dasm - Microsoft.CodeAnalysis.Emit.DeltaMetadataWriter:CreateIndicesForNonTypeMembers(Microsoft.Cci.ITypeDefinition):this
          96 ( 5.54% of base) : 9434.dasm - System.Xml.Schema.Preprocessor:CopyIncludedComponents(System.Xml.Schema.XmlSchema,System.Xml.Schema.XmlSchema):this
          94 ( 2.04% of base) : 176859.dasm - R2RTest.CompileSerpCommand:.ctor(R2RTest.BuildOptions):this

Top method improvements (bytes):
        -466 (-2.81% of base) : 131003.dasm - System.Globalization.CultureData:get_RegionNames():System.Collections.Generic.Dictionary`2[System.String, System.String]
        -458 (-3.32% of base) : 199958.dasm - Sys:GetDriveType(System.String):int
        -270 (-1.24% of base) : 63723.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[System.String],System.String,System.String,System.String):Microsoft.CodeAnalysis.CSharp.CSharpCommandLineArguments:this
        -164 (-3.17% of base) : 59709.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -156 (-5.35% of base) : 76559.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:NeedsSeparator(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken):bool:this
        -138 (-2.42% of base) : 135554.dasm - System.DateTimeParse:ParseByFormat(byref,byref,byref,System.Globalization.DateTimeFormatInfo,byref):bool
        -130 (-4.28% of base) : 83312.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:TransformRewrittenBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
        -118 (-4.97% of base) : 48719.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMethodSymbol:DecodeDllImportAttribute(byref):this
        -116 (-4.33% of base) : 104950.dasm - System.Text.GB18030Encoding:GetChars(int,int,int,int,System.Text.DecoderNLS):int:this
        -112 (-1.87% of base) : 149245.dasm - DataContractCriticalHelper:TryCreateBuiltInDataContract(System.String,System.String,byref):bool
        -110 (-2.31% of base) : 4184.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitDocOrderDistinct(System.Xml.Xsl.Qil.QilUnary):System.Xml.Xsl.Qil.QilNode:this
        -108 (-0.58% of base) : 164525.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
        -106 (-3.22% of base) : 154463.dasm - System.Configuration.MgmtConfigurationRecord:GetConfigDefinitionUpdates(bool,int,bool,byref,byref):this
        -104 (-1.05% of base) : 196863.dasm - TerminalFormatStrings:.ctor(System.TermInfo+Database):this
        -100 (-2.09% of base) : 4188.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitLoop(System.Xml.Xsl.Qil.QilLoop):System.Xml.Xsl.Qil.QilNode:this
         -96 (-0.81% of base) : 111396.dasm - <SendAsyncCore>d__60:MoveNext():this
         -94 (-2.31% of base) : 4196.dasm - System.Xml.Xsl.IlGen.XmlILOptimizerVisitor:VisitEq(System.Xml.Xsl.Qil.QilBinary):System.Xml.Xsl.Qil.QilNode:this
         -94 (-0.97% of base) : 135876.dasm - System.DefaultBinder:BindToMethod(int,System.Reflection.MethodBase[],byref,System.Reflection.ParameterModifier[],System.Globalization.CultureInfo,System.String[],byref):System.Reflection.MethodBase:this
         -92 (-1.79% of base) : 82189.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
         -92 (-2.26% of base) : 83512.dasm - Microsoft.CodeAnalysis.VisualBasic.ExpressionLambdaRewriter:CreateBuiltInConversion(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,bool,bool,int,bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this

Top method regressions (percentages):
          24 (40.00% of base) : 137117.dasm - System.Type:GetRootElementType():System.Type:this
          16 (34.78% of base) : 3829.dasm - System.Xml.XPath.XPathNavigator:GetDepth(System.Xml.XPath.XPathNavigator):int
          30 (31.91% of base) : 21006.dasm - Newtonsoft.Json.Utilities.DynamicProxyMetaObject`1:Constant(System.Dynamic.DynamicMetaObjectBinder):System.Linq.Expressions.ConstantExpression
          26 (29.55% of base) : 204087.dasm - PropertyExpressionAdapter:Reduce(System.Linq.Expressions.Expression`1[System.Func`2[System.__Canon, System.Object]]):System.Linq.Expressions.Expression`1[System.Func`2[System.__Canon, System.Object]]
          26 (29.55% of base) : 192768.dasm - PropertyExpressionAdapter:Reduce(System.Linq.Expressions.Expression`1[System.Func`2[System.__Canon, System.Object]]):System.Linq.Expressions.Expression`1[System.Func`2[System.__Canon, System.Object]]
          26 (29.55% of base) : 192774.dasm - MethodExpressionAdapter:Reduce(System.Linq.Expressions.Expression`1[System.Action`1[System.__Canon]]):System.Linq.Expressions.Expression`1[System.Action`1[System.__Canon]]
          16 (27.59% of base) : 204082.dasm - ConstructorExpressionAdapter:Reduce(System.Linq.Expressions.Expression`1[System.Func`2[System.ComponentModel.Composition.Registration.ParameterImportBuilder, System.__Canon]]):System.Linq.Expressions.Expression`1[System.Func`2[System.ComponentModel.Composition.Registration.ParameterImportBuilder, System.__Canon]]
          16 (27.59% of base) : 192763.dasm - ConstructorExpressionAdapter:Reduce(System.Linq.Expressions.Expression`1[System.Func`2[System.Composition.Convention.ParameterImportConventionBuilder, System.__Canon]]):System.Linq.Expressions.Expression`1[System.Func`2[System.Composition.Convention.ParameterImportConventionBuilder, System.__Canon]]
          52 (25.74% of base) : 171943.dasm - Microsoft.Extensions.Internal.TypeNameHelper:ProcessArrayType(System.Text.StringBuilder,System.Type,byref)
          52 (25.74% of base) : 181566.dasm - Microsoft.Extensions.Internal.TypeNameHelper:ProcessArrayType(System.Text.StringBuilder,System.Type,byref)
          52 (25.74% of base) : 204456.dasm - Microsoft.Extensions.Internal.TypeNameHelper:ProcessArrayType(System.Text.StringBuilder,System.Type,byref)
          38 (20.88% of base) : 109851.dasm - System.Net.Http.Headers.RangeHeaderValue:.ctor(System.Net.Http.Headers.RangeHeaderValue):this
          14 (20.00% of base) : 167220.dasm - System.Xml.BaseTreeIterator:NextRowElement():bool:this
          18 (18.75% of base) : 10513.dasm - System.Xml.XmlText:get_ParentNode():System.Xml.XmlNode:this
          20 (18.52% of base) : 109938.dasm - System.Net.Http.Headers.NameValueHeaderValue:GetHashCode(System.Net.Http.Headers.ObjectCollection`1[System.Net.Http.Headers.NameValueHeaderValue]):int
          26 (18.06% of base) : 88893.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ArrayTypeSymbol:GetHashCode():int:this
          48 (18.05% of base) : 41593.dasm - Microsoft.Diagnostics.Tracing.CLRRuntimeActivityComputer:ProcessingComplete():this
          44 (17.60% of base) : 90568.dasm - Microsoft.CodeAnalysis.VisualBasic.AbstractFlowPass`1:VisitLateBoundArguments(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],bool):this
          16 (17.39% of base) : 50180.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.PointerTypeSymbol:GetHashCode():int:this
          22 (16.67% of base) : 109848.dasm - System.Net.Http.Headers.RangeHeaderValue:GetHashCode():int:this

Top method improvements (percentages):
         -34 (-77.27% of base) : 125880.dasm - System.Runtime.InteropServices.GCHandle:GetHandleValue(int):int
         -32 (-37.21% of base) : 125892.dasm - System.Runtime.InteropServices.GCHandle:get_Target():System.Object:this
         -32 (-32.00% of base) : 125893.dasm - System.Runtime.InteropServices.GCHandle:Free():this
         -32 (-27.12% of base) : 126184.dasm - System.Runtime.Loader.AssemblyLoadContext:Resolve(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -32 (-27.12% of base) : 126241.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUsingResolvingEvent(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -32 (-27.12% of base) : 126243.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUnmanagedDll(System.String,int):int
         -32 (-27.12% of base) : 126244.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveSatelliteAssembly(int,System.Reflection.AssemblyName):System.Reflection.Assembly
         -32 (-25.81% of base) : 126242.dasm - System.Runtime.Loader.AssemblyLoadContext:ResolveUnmanagedDllUsingEvent(System.String,System.Reflection.Assembly,int):int
         -18 (-21.43% of base) : 120516.dasm - System.Diagnostics.Tracing.DataCollector:ScalarsEnd():this
         -32 (-19.51% of base) : 120758.dasm - System.Diagnostics.Tracing.EventSource:WriteCleanup(int,int)
         -34 (-18.09% of base) : 152003.dasm - System.Xml.XmlStreamNodeWriter:UnsafeGetUTF8Length(int,int):int:this
         -34 (-15.74% of base) : 125891.dasm - System.Runtime.InteropServices.GCHandle:set_Target(System.Object):this
         -32 (-13.33% of base) : 125890.dasm - System.Runtime.InteropServices.GCHandle:AddrOfPinnedObject():int:this
          -6 (-11.54% of base) : 164499.dasm - System.Data.SqlTypes.SqlChars:get_MaxLength():long:this
          -6 (-11.54% of base) : 163592.dasm - System.Data.SqlTypes.SqlBytes:get_MaxLength():long:this
         -32 (-11.11% of base) : 126240.dasm - System.Runtime.Loader.AssemblyLoadContext:GetLoadContext(System.Reflection.Assembly):System.Runtime.Loader.AssemblyLoadContext
         -10 (-11.11% of base) : 134702.dasm - System.MemoryExtensions:ClampStart(System.ReadOnlySpan`1[System.Char]):int
          -2 (-10.00% of base) : 106573.dasm - System.DefaultBinder:CanChangePrimitive(System.Type,System.Type):bool
          -2 (-10.00% of base) : 130874.dasm - System.Globalization.CultureData:InitCultureDataCore():bool:this
          -2 (-10.00% of base) : 134041.dasm - System.Single:System.IFloatingPoint<System.Single>.IsSubnormal(float):bool

36006 total methods with Code Size differences (32360 improved, 3646 regressed), 94 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3753488
Total bytes of diff: 3733236
Total bytes of delta: -20252 (-0.54% of base)
Total relative delta: -57.46
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          10 : 100482.dasm (1.01% of base)
           4 : 148439.dasm (0.11% of base)
           2 : 144137.dasm (0.18% of base)
           2 : 79404.dasm (0.19% of base)
           2 : 76009.dasm (1.05% of base)
           2 : 76010.dasm (1.05% of base)
           2 : 5693.dasm (0.71% of base)

Top file improvements (bytes):
        -462 : 217024.dasm (-2.99% of base)
        -220 : 90906.dasm (-1.07% of base)
        -164 : 206506.dasm (-1.55% of base)
        -164 : 94709.dasm (-2.07% of base)
        -148 : 206501.dasm (-1.90% of base)
        -112 : 154190.dasm (-1.75% of base)
        -100 : 198145.dasm (-1.93% of base)
         -72 : 195240.dasm (-1.72% of base)
         -70 : 2582.dasm (-1.51% of base)
         -68 : 94715.dasm (-1.72% of base)
         -68 : 77295.dasm (-1.17% of base)
         -58 : 109578.dasm (-1.55% of base)
         -58 : 131352.dasm (-0.81% of base)
         -58 : 76787.dasm (-1.66% of base)
         -56 : 166283.dasm (-0.79% of base)
         -54 : 25042.dasm (-1.70% of base)
         -54 : 6307.dasm (-5.92% of base)
         -52 : 94710.dasm (-1.65% of base)
         -52 : 58353.dasm (-1.31% of base)
         -52 : 62376.dasm (-2.59% of base)

4793 total files with Code Size differences (4786 improved, 7 regressed), 79 unchanged.

Top method regressions (bytes):
          10 ( 1.01% of base) : 100482.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseMethodDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxListBuilder`1[[Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxListBuilder,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TypeSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ExplicitInterfaceSpecifierSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TypeParameterListSyntax):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.MethodDeclarationSyntax:this
           4 ( 0.11% of base) : 148439.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
           2 ( 0.18% of base) : 144137.dasm - System.Text.ISO2022Encoding:GetCharsCP52936(int,int,int,int,ISO2022Decoder):int:this
           2 ( 0.19% of base) : 79404.dasm - System.Xml.Serialization.AccessorMapping:ElementsMatch(System.Xml.Serialization.ElementAccessor[],System.Xml.Serialization.ElementAccessor[]):bool
           2 ( 1.05% of base) : 76009.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           2 ( 1.05% of base) : 76010.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           2 ( 0.71% of base) : 5693.dasm - Microsoft.Diagnostics.Tracing.Utilities.FastStream:FillBufferFromStreamPosition(int):int:this

Top method improvements (bytes):
        -462 (-2.99% of base) : 217024.dasm - Sys:GetDriveType(System.String):int
        -220 (-1.07% of base) : 90906.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String,System.String,System.String):Microsoft.CodeAnalysis.CSharp.CSharpCommandLineArguments:this
        -164 (-1.55% of base) : 206506.dasm - System.Formats.Asn1.AsnWriter:WriteGeneralizedTimeCore(System.Formats.Asn1.Asn1Tag,System.DateTimeOffset,bool):this
        -164 (-2.07% of base) : 94709.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetKeywordKind(System.String):ushort
        -148 (-1.90% of base) : 206501.dasm - System.Formats.Asn1.AsnWriter:WriteUtcTimeCore(System.Formats.Asn1.Asn1Tag,System.DateTimeOffset):this
        -112 (-1.75% of base) : 154190.dasm - DataContractCriticalHelper:TryCreateBuiltInDataContract(System.String,System.String,byref):bool
        -100 (-1.93% of base) : 198145.dasm - System.ComponentModel.CategoryAttribute:GetLocalizedString(System.String):System.String:this
         -72 (-1.72% of base) : 195240.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
         -70 (-1.51% of base) : 2582.dasm - Newtonsoft.Json.Schema.JsonSchemaBuilder:ProcessSchemaProperties(Newtonsoft.Json.Linq.JObject):this
         -68 (-1.72% of base) : 94715.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetContextualKeywordKind(System.String):ushort
         -68 (-1.17% of base) : 77295.dasm - System.Xml.Xsl.Runtime.XmlCollation:Create(System.String,bool):System.Xml.Xsl.Runtime.XmlCollation
         -58 (-1.55% of base) : 109578.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Metadata.PE.PEMethodSymbol:ComputeMethodKind():int:this
         -58 (-0.81% of base) : 131352.dasm - Microsoft.FSharp.Linq.QueryModule:EvalNonNestedOuter(int,Microsoft.FSharp.Quotations.FSharpExpr):System.Object
         -58 (-1.66% of base) : 76787.dasm - System.Xml.Xsl.XsltOld.XsltCompileContext:FunctionAvailable(System.String):bool:this
         -56 (-0.79% of base) : 166283.dasm - Xunit.ConsoleClient.CommandLine:Parse(System.Predicate`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Xunit.XunitProject:this
         -54 (-1.70% of base) : 25042.dasm - Microsoft.CSharp.RuntimeBinder.SymbolTable:IsOperator(System.Reflection.MethodInfo):bool
         -54 (-5.92% of base) : 6307.dasm - Microsoft.Diagnostics.Tracing.StackSources.LinuxPerfScriptEventParser:FindEndOfProcessCommand(Microsoft.Diagnostics.Tracing.Utilities.FastStream):int
         -52 (-1.65% of base) : 94710.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetOperatorKind(System.String):ushort
         -52 (-1.31% of base) : 58353.dasm - System.Reflection.Metadata.Ecma335.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],System.Collections.Immutable.ImmutableArray`1[Int32],int,bool):this
         -52 (-2.59% of base) : 62376.dasm - System.Configuration.ConfigurationElement:HandleLockedAttributes(System.Configuration.ConfigurationElement):this

Top method regressions (percentages):
           2 ( 1.05% of base) : 76009.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
           2 ( 1.05% of base) : 76010.dasm - System.Xml.Xsl.XsltOld.ActionFrame:NewNextNode(System.Xml.Xsl.XsltOld.Processor):bool:this
          10 ( 1.01% of base) : 100482.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseMethodDeclaration(Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxListBuilder`1[[Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.AttributeListSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxListBuilder,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TypeSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ExplicitInterfaceSpecifierSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TypeParameterListSyntax):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.MethodDeclarationSyntax:this
           2 ( 0.71% of base) : 5693.dasm - Microsoft.Diagnostics.Tracing.Utilities.FastStream:FillBufferFromStreamPosition(int):int:this
           2 ( 0.19% of base) : 79404.dasm - System.Xml.Serialization.AccessorMapping:ElementsMatch(System.Xml.Serialization.ElementAccessor[],System.Xml.Serialization.ElementAccessor[]):bool
           2 ( 0.18% of base) : 144137.dasm - System.Text.ISO2022Encoding:GetCharsCP52936(int,int,int,int,ISO2022Decoder):int:this
           4 ( 0.11% of base) : 148439.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object

Top method improvements (percentages):
         -28 (-22.95% of base) : 165079.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:NativeCallbackHandler(int,int,byref):int
         -30 (-13.76% of base) : 151247.dasm - System.Xml.XmlStreamNodeWriter:UnsafeGetUTF8Length(int,int):int:this
          -2 (-12.50% of base) : 216579.dasm - System.Security.NamedPermissionSet:Equals(System.Object):bool:this
          -2 (-12.50% of base) : 216608.dasm - System.Security.Policy.FileCodeGroup:Equals(System.Object):bool:this
          -2 (-12.50% of base) : 216641.dasm - System.Security.Permissions.FileIOPermission:Equals(System.Object):bool:this
         -28 (-11.97% of base) : 58020.dasm - System.Reflection.Metadata.Ecma335.VirtualHeap:Release():this
          -4 (-11.76% of base) : 35032.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbolExtensions:AllowsCompileTimeConversions(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol):bool
          -6 (-11.54% of base) : 160723.dasm - System.Data.SqlTypes.SqlBytes:get_MaxLength():long:this
          -6 (-11.54% of base) : 159815.dasm - System.Data.SqlTypes.SqlChars:get_MaxLength():long:this
          -2 (-11.11% of base) : 248.dasm - Newtonsoft.Json.JsonConvert:DeserializeAnonymousType(System.String,ubyte):ubyte
          -2 (-11.11% of base) : 249.dasm - Newtonsoft.Json.JsonConvert:DeserializeAnonymousType(System.String,short):short
          -2 (-11.11% of base) : 221173.dasm - <>c__DisplayClass2_0:<.ctor>b__1(System.String):bool:this
          -6 (-10.71% of base) : 24250.dasm - <>c:<ParseSymbolFile>b__23_0(ubyte):bool:this
          -2 (-10.00% of base) : 65094.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValue():ubyte:this
          -2 (-10.00% of base) : 65095.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValue():short:this
          -2 (-10.00% of base) : 65108.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValueOrDefault():ubyte:this
          -2 (-10.00% of base) : 65109.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValueOrDefault():short:this
          -2 (-10.00% of base) : 25958.dasm - Microsoft.CSharp.RuntimeBinder.Semantics.AggregateType:get_IsNonNullableValueType():bool:this
          -2 (-10.00% of base) : 32245.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Retargeting.RetargetingAssemblySymbol:GetGuidString(byref):bool:this
          -2 (-10.00% of base) : 109098.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.Retargeting.RetargetingAssemblySymbol:GetGuidString(byref):bool:this

4793 total methods with Code Size differences (4786 improved, 7 regressed), 79 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9928192
Total bytes of diff: 9878476
Total bytes of delta: -49716 (-0.50% of base)
Total relative delta: -147.56
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          18 : 141875.dasm (0.63% of base)
           8 : 181023.dasm (0.93% of base)
           8 : 74966.dasm (0.39% of base)
           6 : 183131.dasm (0.92% of base)
           4 : 309259.dasm (0.17% of base)
           4 : 242337.dasm (0.69% of base)
           4 : 322609.dasm (0.17% of base)

Top file improvements (bytes):
        -160 : 273476.dasm (-0.88% of base)
        -154 : 171607.dasm (-1.13% of base)
        -114 : 201034.dasm (-4.07% of base)
         -96 : 200139.dasm (-1.26% of base)
         -96 : 65188.dasm (-1.66% of base)
         -92 : 172906.dasm (-7.77% of base)
         -82 : 333969.dasm (-1.35% of base)
         -80 : 164381.dasm (-0.82% of base)
         -80 : 71362.dasm (-0.54% of base)
         -74 : 265128.dasm (-11.94% of base)
         -72 : 199468.dasm (-3.09% of base)
         -72 : 274105.dasm (-1.01% of base)
         -68 : 192087.dasm (-3.31% of base)
         -60 : 172894.dasm (-7.94% of base)
         -58 : 162440.dasm (-3.47% of base)
         -56 : 241641.dasm (-1.39% of base)
         -56 : 317977.dasm (-3.09% of base)
         -56 : 54415.dasm (-1.73% of base)
         -54 : 201002.dasm (-1.51% of base)
         -54 : 201036.dasm (-3.27% of base)

13208 total files with Code Size differences (13201 improved, 7 regressed), 253 unchanged.

Top method regressions (bytes):
          18 ( 0.63% of base) : 141875.dasm - System.Collections.Immutable.Tests.ImmutableListTest:IndexOfAndContainsTest():this
           8 ( 0.93% of base) : 181023.dasm - <ContentEncoding_SetAfterHeadersSent_DoesNothing>d__12:MoveNext():this
           8 ( 0.39% of base) : 74966.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestTextEqualsLargeMatch()
           6 ( 0.92% of base) : 183131.dasm - ImTools.ArrayTools:Match(System.__Canon[],System.Func`2[__Canon,Boolean],System.Func`2[__Canon,Nullable`1]):System.Nullable`1[System.Int32][]
           4 ( 0.17% of base) : 309259.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
           4 ( 0.69% of base) : 242337.dasm - NuGet.Packaging.Signing.SignedPackageArchiveIOUtility:WriteSignatureIntoZip(System.IO.MemoryStream,System.IO.BinaryReader,System.IO.BinaryWriter)
           4 ( 0.17% of base) : 322609.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this

Top method improvements (bytes):
        -160 (-0.88% of base) : 273476.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4EqualsNanTest():this
        -154 (-1.13% of base) : 171607.dasm - Microsoft.CodeAnalysis.CSharp.Extensions.ContextQuery.SyntaxTreeExtensions:IsExpressionContext(Microsoft.CodeAnalysis.SyntaxTree,int,Microsoft.CodeAnalysis.SyntaxToken,bool,System.Threading.CancellationToken,Microsoft.CodeAnalysis.SemanticModel):bool
        -114 (-4.07% of base) : 201034.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:Remove():this
         -96 (-1.26% of base) : 200139.dasm - System.Data.Tests.DataTableTest4:XmlTest10():this
         -96 (-1.66% of base) : 65188.dasm - System.Tests.AttributeGetCustomAttributes:RunPosTests()
         -92 (-7.77% of base) : 172906.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
         -82 (-1.35% of base) : 333969.dasm - NuGet.Frameworks.NuGetFramework:TryParseCommonFramework(System.String,byref):bool
         -80 (-0.82% of base) : 164381.dasm - System.Buffers.Text.Tests.FormatterTests:TryFormatUtf8(System.Object,System.Span`1[Byte],byref,System.Buffers.StandardFormat):bool
         -80 (-0.54% of base) : 71362.dasm - <ToString_MatchesExpected_MemberData>d__105:MoveNext():bool:this
         -74 (-11.94% of base) : 265128.dasm - Microsoft.NET.StringTools.WeakStringCache:Scavenge():this
         -72 (-3.09% of base) : 199468.dasm - System.Data.Tests.DataRowTest2:HasVersion_ByDataRowVersion():this
         -72 (-1.01% of base) : 274105.dasm - TCNamespace:TestNamespace6():this
         -68 (-3.31% of base) : 192087.dasm - System.ComponentModel.TypeConverterTests.IconConverterTest:TestCanConvertTo():this
         -60 (-7.94% of base) : 172894.dasm - CachedOptions:.ctor(Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions):this
         -58 (-3.47% of base) : 162440.dasm - System.MemoryTests.MemoryPoolTests:EachRentalIsUniqueUntilDisposed()
         -56 (-1.39% of base) : 241641.dasm - NuGet.Packaging.ManifestReader:ReadMetadataValue(NuGet.Packaging.ManifestMetadata,System.Xml.Linq.XElement,System.Collections.Generic.HashSet`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]])
         -56 (-3.09% of base) : 317977.dasm - Microsoft.Extensions.Logging.Test.EventSourceLoggerTest:FilterSpecs_UseAppFilters_IncreaseLoggingLevelForOneCategory_GuaranteesAllRulesRemainAvailable():this
         -56 (-1.73% of base) : 54415.dasm - Microsoft.CodeAnalysis.Classification.Classifier:GetClassificationKind(System.String):System.Nullable`1[SymbolDisplayPartKind]
         -54 (-1.51% of base) : 201002.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:TryGetValueTest():this
         -54 (-3.27% of base) : 201036.dasm - System.Data.Tests.Common.DbConnectionStringBuilderTest:ContainsKey():this

Top method regressions (percentages):
           8 ( 0.93% of base) : 181023.dasm - <ContentEncoding_SetAfterHeadersSent_DoesNothing>d__12:MoveNext():this
           6 ( 0.92% of base) : 183131.dasm - ImTools.ArrayTools:Match(System.__Canon[],System.Func`2[__Canon,Boolean],System.Func`2[__Canon,Nullable`1]):System.Nullable`1[System.Int32][]
           4 ( 0.69% of base) : 242337.dasm - NuGet.Packaging.Signing.SignedPackageArchiveIOUtility:WriteSignatureIntoZip(System.IO.MemoryStream,System.IO.BinaryReader,System.IO.BinaryWriter)
          18 ( 0.63% of base) : 141875.dasm - System.Collections.Immutable.Tests.ImmutableListTest:IndexOfAndContainsTest():this
           8 ( 0.39% of base) : 74966.dasm - System.Text.Json.Tests.Utf8JsonReaderTests:TestTextEqualsLargeMatch()
           4 ( 0.17% of base) : 309259.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this
           4 ( 0.17% of base) : 322609.dasm - <>c__DisplayClass17_0:<IsZipSameAsDir>b__0(FileData):this

Top method improvements (percentages):
         -28 (-37.84% of base) : 178823.dasm - <>c__DisplayClass0_0:<Ctor_Default>b__0():System.Object:this
         -28 (-33.33% of base) : 265148.dasm - StringWeakHandle:get_IsUsed():bool:this
         -28 (-31.11% of base) : 275409.dasm - SQLitePCL.log_hook_info:from_ptr(int):SQLitePCL.log_hook_info
         -28 (-31.11% of base) : 275413.dasm - SQLitePCL.commit_hook_info:from_ptr(int):SQLitePCL.commit_hook_info
         -28 (-31.11% of base) : 275415.dasm - SQLitePCL.rollback_hook_info:from_ptr(int):SQLitePCL.rollback_hook_info
         -28 (-31.11% of base) : 275418.dasm - SQLitePCL.trace_hook_info:from_ptr(int):SQLitePCL.trace_hook_info
         -28 (-31.11% of base) : 275421.dasm - SQLitePCL.profile_hook_info:from_ptr(int):SQLitePCL.profile_hook_info
         -28 (-31.11% of base) : 275424.dasm - SQLitePCL.progress_hook_info:from_ptr(int):SQLitePCL.progress_hook_info
         -28 (-31.11% of base) : 275427.dasm - SQLitePCL.update_hook_info:from_ptr(int):SQLitePCL.update_hook_info
         -28 (-31.11% of base) : 275430.dasm - SQLitePCL.collation_hook_info:from_ptr(int):SQLitePCL.collation_hook_info
         -28 (-31.11% of base) : 275433.dasm - SQLitePCL.exec_hook_info:from_ptr(int):SQLitePCL.exec_hook_info
         -28 (-31.11% of base) : 275436.dasm - SQLitePCL.function_hook_info:from_ptr(int):SQLitePCL.function_hook_info
         -28 (-31.11% of base) : 275443.dasm - SQLitePCL.authorizer_hook_info:from_ptr(int):SQLitePCL.authorizer_hook_info
         -28 (-20.90% of base) : 265149.dasm - StringWeakHandle:GetString(byref):System.String:this
         -28 (-19.18% of base) : 251726.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToTypeTest:CheckTypeNotUnloaded():this
         -28 (-19.18% of base) : 251730.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToInstanceTest:CheckInstanceNotUnloaded():this
         -28 (-18.92% of base) : 251725.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToTypeTest:FreeHandle():this
         -28 (-18.92% of base) : 251729.dasm - CollectibleWithOneAssemblyLoadedWithStrongReferenceToInstanceTest:FreeHandle():this
         -30 (-18.75% of base) : 234210.dasm - System.Data.SqlClient.SNILoadHandle:ReadDispatcher(int,int,int)
         -30 (-18.75% of base) : 234211.dasm - System.Data.SqlClient.SNILoadHandle:WriteDispatcher(int,int,int)

13208 total methods with Code Size differences (13201 improved, 7 regressed), 253 unchanged.

```

</details>

--------------------------------------------------------------------------------

