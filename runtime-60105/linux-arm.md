## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 19302
Total bytes of diff: 19038
Total bytes of delta: -264 (-1.37% of base)
Total relative delta: -0.16
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -62 : 202303.dasm (-1.18% of base)
         -28 : 160948.dasm (-1.19% of base)
         -22 : 160980.dasm (-1.20% of base)
         -20 : 160983.dasm (-1.44% of base)
         -20 : 160978.dasm (-1.30% of base)
         -20 : 161540.dasm (-1.60% of base)
         -20 : 161606.dasm (-1.79% of base)
         -20 : 161547.dasm (-2.05% of base)
         -18 : 161533.dasm (-1.84% of base)
         -18 : 160868.dasm (-1.79% of base)
         -16 : 160979.dasm (-1.00% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -62 (-1.18% of base) : 202303.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -28 (-1.19% of base) : 160948.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -22 (-1.20% of base) : 160980.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -20 (-1.44% of base) : 160983.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -20 (-1.30% of base) : 160978.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -20 (-1.60% of base) : 161540.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
         -20 (-1.79% of base) : 161606.dasm - <Verify>d__9:MoveNext():bool:this
         -20 (-2.05% of base) : 161547.dasm - <GetFields>d__44:MoveNext():bool:this
         -18 (-1.84% of base) : 161533.dasm - <GetMethods>d__38:MoveNext():bool:this
         -18 (-1.79% of base) : 160868.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
         -16 (-1.00% of base) : 160979.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this

Top method improvements (percentages):
         -20 (-2.05% of base) : 161547.dasm - <GetFields>d__44:MoveNext():bool:this
         -18 (-1.84% of base) : 161533.dasm - <GetMethods>d__38:MoveNext():bool:this
         -20 (-1.79% of base) : 161606.dasm - <Verify>d__9:MoveNext():bool:this
         -18 (-1.79% of base) : 160868.dasm - Internal.TypeSystem.Ecma.EcmaMethod:GetParameterMetadata():Internal.TypeSystem.ParameterMetadata[]:this
         -20 (-1.60% of base) : 161540.dasm - <GetVirtualMethods>d__39:MoveNext():bool:this
         -20 (-1.44% of base) : 160983.dasm - Internal.TypeSystem.Ecma.EcmaType:GetField(System.String):Internal.TypeSystem.FieldDesc:this
         -20 (-1.30% of base) : 160978.dasm - Internal.TypeSystem.Ecma.EcmaType:GetMethod(System.String,Internal.TypeSystem.MethodSignature,Internal.TypeSystem.Instantiation):Internal.TypeSystem.MethodDesc:this
         -22 (-1.20% of base) : 160980.dasm - Internal.TypeSystem.Ecma.EcmaType:GetDefaultConstructor():Internal.TypeSystem.MethodDesc:this
         -28 (-1.19% of base) : 160948.dasm - Internal.TypeSystem.Ecma.EcmaType:GetClassLayout():Internal.TypeSystem.ClassLayoutMetadata:this
         -62 (-1.18% of base) : 202303.dasm - IlasmPortablePdbTests.IlasmPortablePdbTester:TestPortablePdbLocalScope(System.String):this
         -16 (-1.00% of base) : 160979.dasm - Internal.TypeSystem.Ecma.EcmaType:GetStaticConstructor():Internal.TypeSystem.MethodDesc:this

11 total methods with Code Size differences (11 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 8484
Total bytes of diff: 7900
Total bytes of delta: -584 (-6.88% of base)
Total relative delta: -1.18
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -120 : 67815.dasm (-7.13% of base)
         -92 : 67792.dasm (-4.33% of base)
         -74 : 67776.dasm (-9.59% of base)
         -70 : 67795.dasm (-9.59% of base)
         -68 : 67784.dasm (-10.79% of base)
         -48 : 67809.dasm (-9.92% of base)
         -26 : 107821.dasm (-5.53% of base)
         -26 : 107822.dasm (-5.53% of base)
         -24 : 67804.dasm (-2.44% of base)
         -18 : 108192.dasm (-26.47% of base)
         -18 : 108193.dasm (-26.47% of base)

11 total files with Code Size differences (11 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -120 (-7.13% of base) : 67815.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -92 (-4.33% of base) : 67792.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -74 (-9.59% of base) : 67776.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
         -70 (-9.59% of base) : 67795.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -68 (-10.79% of base) : 67784.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-9.92% of base) : 67809.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -26 (-5.53% of base) : 107821.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -26 (-5.53% of base) : 107822.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -24 (-2.44% of base) : 67804.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -18 (-26.47% of base) : 108192.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -18 (-26.47% of base) : 108193.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this

Top method improvements (percentages):
         -18 (-26.47% of base) : 108192.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -18 (-26.47% of base) : 108193.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -68 (-10.79% of base) : 67784.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-9.92% of base) : 67809.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -70 (-9.59% of base) : 67795.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -74 (-9.59% of base) : 67776.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression],Microsoft.CodeAnalysis.ArrayBuilder`1[Microsoft.CodeAnalysis.VisualBasic.AsyncRewriter+SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[Microsoft.CodeAnalysis.VisualBasic.BoundExpression]:this
        -120 (-7.13% of base) : 67815.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -26 (-5.53% of base) : 107821.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -26 (-5.53% of base) : 107822.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -92 (-4.33% of base) : 67792.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -24 (-2.44% of base) : 67804.dasm - AsyncMethodToClassRewriter:VisitBinaryOperator(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this

11 total methods with Code Size differences (11 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 230976
Total bytes of diff: 228246
Total bytes of delta: -2730 (-1.18% of base)
Total relative delta: -2.78
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           6 : 32027.dasm (0.63% of base)

Top file improvements (bytes):
        -176 : 165091.dasm (-6.52% of base)
        -124 : 219304.dasm (-6.67% of base)
        -122 : 54198.dasm (-3.69% of base)
         -92 : 54181.dasm (-10.98% of base)
         -84 : 54175.dasm (-2.89% of base)
         -62 : 54157.dasm (-6.75% of base)
         -58 : 24239.dasm (-15.85% of base)
         -58 : 86185.dasm (-4.17% of base)
         -56 : 54188.dasm (-9.69% of base)
         -54 : 159426.dasm (-5.28% of base)
         -50 : 54195.dasm (-5.43% of base)
         -50 : 54149.dasm (-5.30% of base)
         -48 : 86187.dasm (-1.90% of base)
         -44 : 158737.dasm (-4.23% of base)
         -42 : 159388.dasm (-2.02% of base)
         -40 : 5733.dasm (-1.40% of base)
         -38 : 57717.dasm (-8.76% of base)
         -38 : 158812.dasm (-4.46% of base)
         -38 : 57716.dasm (-8.76% of base)
         -38 : 169049.dasm (-1.76% of base)

140 total files with Code Size differences (139 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           6 ( 0.63% of base) : 32027.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods():System.Collections.Generic.Dictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this

Top method improvements (bytes):
        -176 (-6.52% of base) : 165091.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
        -124 (-6.67% of base) : 219304.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
        -122 (-3.69% of base) : 54198.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -92 (-10.98% of base) : 54181.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -84 (-2.89% of base) : 54175.dasm - AsyncMethodToClassRewriter:VisitAwaitOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAwaitOperator):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -62 (-6.75% of base) : 54157.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -58 (-15.85% of base) : 24239.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
         -58 (-4.17% of base) : 86185.dasm - System.Text.Json.Utf8JsonReader:CompareToSequence(System.ReadOnlySpan`1[Byte]):bool:this
         -56 (-9.69% of base) : 54188.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -54 (-5.28% of base) : 159426.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -50 (-5.43% of base) : 54195.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -50 (-5.30% of base) : 54149.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -48 (-1.90% of base) : 86187.dasm - System.Text.Json.Utf8JsonReader:UnescapeSequenceAndCompare(System.ReadOnlySpan`1[Byte]):bool:this
         -44 (-4.23% of base) : 158737.dasm - System.Data.DataView:ResetRowViewCache():this
         -42 (-2.02% of base) : 159388.dasm - System.Data.Select:GetLinearFilteredRecords(System.Data.Range):System.Int32[]:this
         -40 (-1.40% of base) : 5733.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceLog:FastSerialization.IFastSerializable.FromStream(FastSerialization.Deserializer):this
         -38 (-8.76% of base) : 57717.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -38 (-4.46% of base) : 158812.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -38 (-8.76% of base) : 57716.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -38 (-1.76% of base) : 169049.dasm - System.Reflection.TypeLoading.Ecma.EcmaDefinitionType:ComputeEnumUnderlyingType():System.Reflection.TypeLoading.RoType:this

Top method regressions (percentages):
           6 ( 0.63% of base) : 32027.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PENamedTypeSymbol:CreateMethods():System.Collections.Generic.Dictionary`2[[System.Reflection.Metadata.MethodDefinitionHandle, System.Reflection.Metadata, Version=7.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a],[Microsoft.CodeAnalysis.VisualBasic.Symbols.Metadata.PE.PEMethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this

Top method improvements (percentages):
         -18 (-29.03% of base) : 57338.dasm - System.Reflection.Metadata.MetadataReader:get_LocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -18 (-29.03% of base) : 57339.dasm - System.Reflection.Metadata.MetadataReader:get_LocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -58 (-15.85% of base) : 24239.dasm - <>c__DisplayClass13_0:<FastSerialization.IFastSerializable.FromStream>b__0():this
         -92 (-10.98% of base) : 54181.dasm - AsyncMethodToClassRewriter:VisitSequence(Microsoft.CodeAnalysis.VisualBasic.BoundSequence):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -56 (-9.69% of base) : 54188.dasm - AsyncMethodToClassRewriter:ProcessRewrittenAssignmentOperator(Microsoft.CodeAnalysis.VisualBasic.BoundAssignmentOperator):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
         -38 (-8.76% of base) : 57717.dasm - System.Reflection.Metadata.LocalScope:GetLocalConstants():System.Reflection.Metadata.LocalConstantHandleCollection:this
         -38 (-8.76% of base) : 57716.dasm - System.Reflection.Metadata.LocalScope:GetLocalVariables():System.Reflection.Metadata.LocalVariableHandleCollection:this
         -62 (-6.75% of base) : 54157.dasm - AsyncMethodToClassRewriter:SpillArgumentListInner(System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[SpillBuilder],bool,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
        -124 (-6.67% of base) : 219304.dasm - System.Buffers.ReadOnlySequenceDebugView`1[Byte][System.Byte]:.ctor(System.Buffers.ReadOnlySequence`1[Byte]):this
        -176 (-6.52% of base) : 165091.dasm - System.Net.Quic.Implementations.MsQuic.MsQuicStream:SendReadOnlySequenceAsync(System.Buffers.ReadOnlySequence`1[Byte],int):System.Threading.Tasks.ValueTask:this
         -50 (-5.43% of base) : 54195.dasm - AsyncMethodToClassRewriter:VisitTernaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundTernaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -50 (-5.30% of base) : 54149.dasm - AsyncMethodToClassRewriter:VisitBinaryConditionalExpression(Microsoft.CodeAnalysis.VisualBasic.BoundBinaryConditionalExpression):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -54 (-5.28% of base) : 159426.dasm - System.Data.Index:GetRows(System.Data.Range):System.Data.DataRow[]:this
         -38 (-4.46% of base) : 158812.dasm - System.Data.DataView:CopyTo(System.Data.DataRowView[],int):this
         -38 (-4.42% of base) : 158811.dasm - System.Data.DataView:CopyTo(System.Array,int):this
         -44 (-4.23% of base) : 158737.dasm - System.Data.DataView:ResetRowViewCache():this
         -58 (-4.17% of base) : 86185.dasm - System.Text.Json.Utf8JsonReader:CompareToSequence(System.ReadOnlySpan`1[Byte]):bool:this
        -122 (-3.69% of base) : 54198.dasm - AsyncMethodToClassRewriter:VisitLoweredConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundLoweredConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
         -16 (-3.31% of base) : 114989.dasm - Microsoft.CodeAnalysis.PEModule:GetParametersOfMethodOrThrow(System.Reflection.Metadata.MethodDefinitionHandle):System.Reflection.Metadata.ParameterHandleCollection:this
         -16 (-3.31% of base) : 115069.dasm - Microsoft.CodeAnalysis.PEModule:GetMethodsOfTypeOrThrow(System.Reflection.Metadata.TypeDefinitionHandle):System.Reflection.Metadata.MethodDefinitionHandleCollection:this

140 total methods with Code Size differences (139 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 382028
Total bytes of diff: 379734
Total bytes of delta: -2294 (-0.60% of base)
Total relative delta: -1.41
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         188 : 204372.dasm (1.79% of base)
          22 : 226915.dasm (0.83% of base)
          22 : 226917.dasm (0.75% of base)
          10 : 162819.dasm (0.92% of base)
          10 : 162814.dasm (0.92% of base)
          10 : 162802.dasm (0.50% of base)
          10 : 162816.dasm (0.84% of base)
          10 : 162815.dasm (0.78% of base)
           8 : 162806.dasm (0.90% of base)
           6 : 162827.dasm (0.31% of base)
           6 : 162813.dasm (0.58% of base)

Top file improvements (bytes):
        -228 : 162619.dasm (-6.48% of base)
        -156 : 162867.dasm (-3.82% of base)
        -102 : 240575.dasm (-2.22% of base)
        -100 : 162608.dasm (-5.14% of base)
         -78 : 337431.dasm (-6.49% of base)
         -78 : 174310.dasm (-6.49% of base)
         -76 : 240585.dasm (-1.10% of base)
         -58 : 162588.dasm (-2.30% of base)
         -56 : 162728.dasm (-4.49% of base)
         -56 : 162730.dasm (-4.50% of base)
         -56 : 162729.dasm (-4.49% of base)
         -56 : 162594.dasm (-2.18% of base)
         -54 : 51476.dasm (-1.16% of base)
         -52 : 51477.dasm (-1.17% of base)
         -50 : 58539.dasm (-0.73% of base)
         -44 : 64424.dasm (-5.31% of base)
         -42 : 162898.dasm (-0.42% of base)
         -34 : 172826.dasm (-3.11% of base)
         -34 : 205661.dasm (-3.47% of base)
         -32 : 205660.dasm (-1.94% of base)

163 total files with Code Size differences (152 improved, 11 regressed), 0 unchanged.

Top method regressions (bytes):
         188 ( 1.79% of base) : 204372.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.NodeBasedFormattingRule:AddIndentBlockOperationsSlow(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode,byref):this
          22 ( 0.83% of base) : 226915.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          22 ( 0.75% of base) : 226917.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
          10 ( 0.92% of base) : 162819.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceThrowsPastLengthMultipleSegments():this
          10 ( 0.92% of base) : 162814.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvancingPastLengthThrows():this
          10 ( 0.50% of base) : 162802.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsWithoutMoving():this
          10 ( 0.84% of base) : 162816.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:EmptySegmentsAreSkippedOnMoveNext():this
          10 ( 0.78% of base) : 162815.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:CtorFindsFirstNonEmptySegment():this
           8 ( 0.90% of base) : 162806.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset_Empty():this
           6 ( 0.31% of base) : 162827.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:Advance_PositionIsCorrect(int):this
           6 ( 0.58% of base) : 162813.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceToEndThenPeekReturnsDefault():this

Top method improvements (bytes):
        -228 (-6.48% of base) : 162619.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
        -156 (-3.82% of base) : 162867.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
        -102 (-2.22% of base) : 240575.dasm - <HelloWorldAcrossTwoBlocks>d__11:MoveNext():this
        -100 (-5.14% of base) : 162608.dasm - System.Memory.Tests.ReadOnlySequenceTestsDefault:Default_Enumerator():this
         -78 (-6.49% of base) : 337431.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -78 (-6.49% of base) : 174310.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -76 (-1.10% of base) : 240585.dasm - <ReaderShouldNotGetUnflushedBytesWithAppend>d__17:MoveNext():this
         -58 (-2.30% of base) : 162588.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonChar:HelloWorldAcrossTwoBlocks():this
         -56 (-4.49% of base) : 162728.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
         -56 (-4.50% of base) : 162730.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this
         -56 (-4.49% of base) : 162729.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfFull():this
         -56 (-2.18% of base) : 162594.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonByte:HelloWorldAcrossTwoBlocks():this
         -54 (-1.16% of base) : 51476.dasm - Microsoft.CodeAnalysis.Formatting.AbstractTriviaFormatter:FormatTrivia(Formatter`1[__Canon],WhitespaceAppender`1[__Canon],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[__Canon],System.Threading.CancellationToken):Microsoft.CodeAnalysis.Formatting.LineColumn:this
         -52 (-1.17% of base) : 51477.dasm - Microsoft.CodeAnalysis.Formatting.AbstractTriviaFormatter:FormatTrivia(Formatter`1[Byte],WhitespaceAppender`1[Byte],Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[Byte],System.Threading.CancellationToken):Microsoft.CodeAnalysis.Formatting.LineColumn:this
         -50 (-0.73% of base) : 58539.dasm - MetadataInfoCreator:LookupMetadataDefinitions(System.Reflection.Metadata.TypeDefinition,Microsoft.CodeAnalysis.Collections.OrderPreservingMultiDictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.FindSymbols.SymbolTreeInfo+MetadataDefinition, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):this
         -44 (-5.31% of base) : 64424.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
         -42 (-0.42% of base) : 162898.dasm - System.Memory.Tests.SequenceReader.SkipDelimiter:TryReadTo_SkipDelimiter():this
         -34 (-3.11% of base) : 172826.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -34 (-3.47% of base) : 205661.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -32 (-1.94% of base) : 205660.dasm - CodeShapeAnalyzer:ShouldFormatSingleLine(Microsoft.CodeAnalysis.Formatting.TriviaList):bool

Top method regressions (percentages):
         188 ( 1.79% of base) : 204372.dasm - Microsoft.CodeAnalysis.VisualBasic.Formatting.NodeBasedFormattingRule:AddIndentBlockOperationsSlow(System.Collections.Generic.List`1[[Microsoft.CodeAnalysis.Formatting.Rules.IndentBlockOperation, Microsoft.CodeAnalysis.Workspaces, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.SyntaxNode,byref):this
          10 ( 0.92% of base) : 162819.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceThrowsPastLengthMultipleSegments():this
          10 ( 0.92% of base) : 162814.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvancingPastLengthThrows():this
           8 ( 0.90% of base) : 162806.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekOffset_Empty():this
          10 ( 0.84% of base) : 162816.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:EmptySegmentsAreSkippedOnMoveNext():this
          22 ( 0.83% of base) : 226915.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_FirstTypeDef():this
          10 ( 0.78% of base) : 162815.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:CtorFindsFirstNonEmptySegment():this
          22 ( 0.75% of base) : 226917.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:MemberCollections_TypeMembers_LastTypeDef():this
           6 ( 0.58% of base) : 162813.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:AdvanceToEndThenPeekReturnsDefault():this
          10 ( 0.50% of base) : 162802.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:TryPeekReturnsWithoutMoving():this
           6 ( 0.31% of base) : 162827.dasm - System.Memory.Tests.SequenceReader.ReaderBasicTests`1[Byte][System.Byte]:Advance_PositionIsCorrect(int):this

Top method improvements (percentages):
         -78 (-6.49% of base) : 337431.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
         -78 (-6.49% of base) : 174310.dasm - System.Net.Http.HPack.HPackDecoder:Decode(byref,bool,System.Net.Http.IHttpHeadersHandler):this
        -228 (-6.48% of base) : 162619.dasm - System.Memory.Tests.ReadOnlySequenceTestsEmpty:Empty_Enumerator():this
          -8 (-5.97% of base) : 112654.dasm - System.Tests.ExtensionsTests:Deconstruct4()
         -44 (-5.31% of base) : 64424.dasm - System.Tests.StringTests:EnumerateRunes(System.Char[],System.Int32[])
        -100 (-5.14% of base) : 162608.dasm - System.Memory.Tests.ReadOnlySequenceTestsDefault:Default_Enumerator():this
          -6 (-4.84% of base) : 112653.dasm - System.Tests.ExtensionsTests:Deconstruct3()
         -56 (-4.50% of base) : 162730.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfEmpty():this
         -56 (-4.49% of base) : 162728.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsLastItemOfFull():this
         -56 (-4.49% of base) : 162729.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommon`1[Byte][System.Byte]:EnumerableStopsAtEndWhenEndIsFirstItemOfFull():this
        -156 (-3.82% of base) : 162867.dasm - System.Memory.Tests.SequenceReader.ReadTo:TryReadTo_Sequence(bool,bool):this
          -4 (-3.51% of base) : 112652.dasm - System.Tests.ExtensionsTests:Deconstruct2()
         -34 (-3.47% of base) : 205661.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -20 (-3.26% of base) : 245813.dasm - System.Threading.Tasks.Tests.PoolingAsyncValueTaskMethodBuilderTests:Generic_SetException_BeforeAccessTask_FaultsTask():this
         -34 (-3.11% of base) : 172826.dasm - CodeShapeAnalyzer:ContainsSkippedTokensOrText(Microsoft.CodeAnalysis.Formatting.TriviaList):bool
         -16 (-2.57% of base) : 245812.dasm - System.Threading.Tasks.Tests.PoolingAsyncValueTaskMethodBuilderTests:NonGeneric_SetException_BeforeAccessTask_FaultsTask():this
         -58 (-2.30% of base) : 162588.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonChar:HelloWorldAcrossTwoBlocks():this
        -102 (-2.22% of base) : 240575.dasm - <HelloWorldAcrossTwoBlocks>d__11:MoveNext():this
         -56 (-2.18% of base) : 162594.dasm - System.Memory.Tests.ReadOnlySequenceTestsCommonByte:HelloWorldAcrossTwoBlocks():this
         -16 (-1.99% of base) : 245817.dasm - System.Threading.Tasks.Tests.PoolingAsyncValueTaskMethodBuilderTests:Generic_SetException_OperationCanceledException_CancelsTask():this

163 total methods with Code Size differences (152 improved, 11 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

