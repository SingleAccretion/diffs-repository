## coreclr_tests.pmi.Linux.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 351632
Total bytes of diff: 345876
Total bytes of delta: -5756 (-1.64% of base)
Total relative delta: -50.43
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -80 : 175840.dasm (-3.47% of base)
         -80 : 226159.dasm (-0.44% of base)
         -80 : 231534.dasm (-0.43% of base)
         -60 : 130471.dasm (-0.46% of base)
         -32 : 82760.dasm (-7.84% of base)
         -32 : 253289.dasm (-1.17% of base)
         -24 : 130321.dasm (-0.63% of base)
         -20 : 212002.dasm (-41.67% of base)
         -20 : 248445.dasm (-1.82% of base)
         -20 : 249871.dasm (-1.82% of base)
         -20 : 211985.dasm (-41.67% of base)
         -20 : 81639.dasm (-1.82% of base)
         -16 : 187857.dasm (-18.18% of base)
         -16 : 212014.dasm (-33.33% of base)
         -16 : 249607.dasm (-3.23% of base)
         -16 : 251116.dasm (-5.56% of base)
         -16 : 211982.dasm (-33.33% of base)
         -16 : 211990.dasm (-33.33% of base)
         -16 : 251117.dasm (-8.51% of base)
         -16 : 251654.dasm (-8.70% of base)

757 total files with Code Size differences (757 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -80 (-3.47% of base) : 175840.dasm - Huffman:DoHuffIteration(System.Byte[],System.Byte[],System.Byte[],int,int,huff_node[]):long
         -80 (-0.44% of base) : 226159.dasm - lclfldmul:Main():int
         -80 (-0.43% of base) : 231534.dasm - lclfldmul:Main():int
         -60 (-0.46% of base) : 130471.dasm - Internal.IL.ILImporter:ImportBasicBlock(BasicBlock):this
         -32 (-7.84% of base) : 82760.dasm - DoubleStackAlloc:Main():int
         -32 (-1.17% of base) : 253289.dasm - Complex_Array_Test:Main(System.String[]):int
         -24 (-0.63% of base) : 130321.dasm - Internal.TypeSystem.Ecma.EcmaModule:ResolveTypeReference(System.Reflection.Metadata.TypeReferenceHandle):System.Object:this
         -20 (-41.67% of base) : 212002.dasm - LongMulOn32BitTest:LongMul_14(int,int):long
         -20 (-1.82% of base) : 248445.dasm - KnightMove.SQ:Main():int
         -20 (-1.82% of base) : 249871.dasm - KnightMove.SQ:Main():int
         -20 (-41.67% of base) : 211985.dasm - LongMulOn32BitTest:LongMul_60(int,int):long
         -20 (-1.82% of base) : 81639.dasm - KnightMove.SQ:Main():int
         -16 (-18.18% of base) : 187857.dasm - <>c:<Main>b__2_0(int,int,int,int,long,long,byref,byref):bool:this
         -16 (-33.33% of base) : 212014.dasm - LongMulOn32BitTest:LongMul_26(int):long
         -16 (-3.23% of base) : 249607.dasm - BigFrames.Test:Test1(int)
         -16 (-5.56% of base) : 251116.dasm - ThreadData:Run():this
         -16 (-33.33% of base) : 211982.dasm - LongMulOn32BitTest:LongMul_57(int):long
         -16 (-33.33% of base) : 211990.dasm - LongMulOn32BitTest:LongMul_2(int):long
         -16 (-8.51% of base) : 251117.dasm - ThreadData:AllocateMore(int):int:this
         -16 (-8.70% of base) : 251654.dasm - OriginalStackalloc:F(int,int,int):int

Top method improvements (percentages):
         -20 (-41.67% of base) : 212002.dasm - LongMulOn32BitTest:LongMul_14(int,int):long
         -20 (-41.67% of base) : 211985.dasm - LongMulOn32BitTest:LongMul_60(int,int):long
         -16 (-33.33% of base) : 212014.dasm - LongMulOn32BitTest:LongMul_26(int):long
         -16 (-33.33% of base) : 211982.dasm - LongMulOn32BitTest:LongMul_57(int):long
         -16 (-33.33% of base) : 211990.dasm - LongMulOn32BitTest:LongMul_2(int):long
         -16 (-33.33% of base) : 211993.dasm - LongMulOn32BitTest:LongMul_5(int):long
         -16 (-33.33% of base) : 211999.dasm - LongMulOn32BitTest:LongMul_11(int):long
         -16 (-33.33% of base) : 211966.dasm - LongMulOn32BitTest:LongMul_41(int):long
         -16 (-33.33% of base) : 211967.dasm - LongMulOn32BitTest:LongMul_42(int):long
         -16 (-33.33% of base) : 211981.dasm - LongMulOn32BitTest:LongMul_56(int):long
          -8 (-28.57% of base) : 211983.dasm - LongMulOn32BitTest:LongMul_58(int,int):long
          -8 (-28.57% of base) : 212001.dasm - LongMulOn32BitTest:LongMul_13(int,int):long
          -8 (-28.57% of base) : 7842.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWidening(int,int):long
          -8 (-28.57% of base) : 7911.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWidening(int,int):long
          -8 (-25.00% of base) : 161919.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(long,int,int):long
          -8 (-25.00% of base) : 161920.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long
          -8 (-25.00% of base) : 174401.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long
          -8 (-25.00% of base) : 195946.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long
          -8 (-25.00% of base) : 92954.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(long,int,int):long
          -8 (-25.00% of base) : 92955.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndSubtract(long,int,int):long

757 total methods with Code Size differences (757 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 592684
Total bytes of diff: 586564
Total bytes of delta: -6120 (-1.03% of base)
Total relative delta: -14.82
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -304 : 121080.dasm (-3.47% of base)
        -176 : 121075.dasm (-3.41% of base)
        -128 : 63549.dasm (-11.51% of base)
        -124 : 121076.dasm (-2.17% of base)
         -56 : 188790.dasm (-3.10% of base)
         -44 : 121081.dasm (-3.30% of base)
         -44 : 121082.dasm (-3.30% of base)
         -40 : 188793.dasm (-2.72% of base)
         -36 : 95008.dasm (-1.82% of base)
         -36 : 63553.dasm (-1.79% of base)
         -36 : 66153.dasm (-3.41% of base)
         -32 : 63548.dasm (-2.90% of base)
         -32 : 45856.dasm (-1.23% of base)
         -32 : 45858.dasm (-1.92% of base)
         -28 : 118390.dasm (-0.69% of base)
         -28 : 95007.dasm (-2.28% of base)
         -24 : 134436.dasm (-2.65% of base)
         -24 : 121066.dasm (-4.08% of base)
         -20 : 137143.dasm (-1.06% of base)
         -20 : 64187.dasm (-1.21% of base)

797 total files with Code Size differences (797 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -304 (-3.47% of base) : 121080.dasm - System.Data.RBTree`1:RBInsert(int,int,int,int,bool):int:this
        -176 (-3.41% of base) : 121075.dasm - System.Data.RBTree`1:RBDeleteFixup(int,int,int,int):int:this
        -128 (-11.51% of base) : 63549.dasm - DecCalc:VarDecMul(byref,byref)
        -124 (-2.17% of base) : 121076.dasm - System.Data.RBTree`1:RBDeleteX(int,int,int):int:this
         -56 (-3.10% of base) : 188790.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
         -44 (-3.30% of base) : 121081.dasm - System.Data.RBTree`1:RightRotate(int,int,int):int:this
         -44 (-3.30% of base) : 121082.dasm - System.Data.RBTree`1:LeftRotate(int,int,int):int:this
         -40 (-2.72% of base) : 188793.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)
         -36 (-1.82% of base) : 95008.dasm - Microsoft.VisualBasic.CompilerServices.LikeOperator:BuildPatternGroups(System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],byref,byref,System.Globalization.CompareInfo,int,byref)
         -36 (-1.79% of base) : 63553.dasm - DecCalc:DecAddSub(byref,byref,bool)
         -36 (-3.41% of base) : 66153.dasm - PastEventInfo:LogEvent(Microsoft.Diagnostics.Tracing.TraceEvent,int,Microsoft.Diagnostics.Tracing.Etlx.TraceEventCounts):this
         -32 (-2.90% of base) : 63548.dasm - DecCalc:VarDecFromR4(float,byref)
         -32 (-1.23% of base) : 45856.dasm - System.Diagnostics.Tracing.EventSource:WriteImpl(System.String,byref,System.Object,long,long,System.Diagnostics.Tracing.TraceLoggingEventTypes):this
         -32 (-1.92% of base) : 45858.dasm - System.Diagnostics.Tracing.EventSource:WriteMultiMergeInner(System.String,byref,System.Diagnostics.Tracing.TraceLoggingEventTypes,long,long,System.Object[]):this
         -28 (-0.69% of base) : 118390.dasm - System.Data.Common.SqlDecimalStorage:Aggregate(System.Int32[],int):System.Object:this
         -28 (-2.28% of base) : 95007.dasm - Microsoft.VisualBasic.CompilerServices.LikeOperator:MatchAsterisk(System.String,int,int,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],System.String,int,int,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],byref,byref,System.Globalization.CompareInfo,int)
         -24 (-2.65% of base) : 134436.dasm - System.Xml.XmlTextWriter:WriteEndStartTag(bool):this
         -24 (-4.08% of base) : 121066.dasm - System.Data.RBTree`1:ComputeIndexWithSatelliteByNode(int):int:this
         -20 (-1.06% of base) : 137143.dasm - System.Xml.XmlSqlBinaryReader:ScanAttributes():this
         -20 (-1.21% of base) : 64187.dasm - System.Collections.Generic.Dictionary`2:TryInsert(System.__Canon,bool,ubyte):bool:this

Top method improvements (percentages):
          -8 (-28.57% of base) : 63567.dasm - DecCalc:UInt32x32To64(int,int):long
          -8 (-28.57% of base) : 63290.dasm - System.Math:BigMul(int,int):long
         -16 (-25.00% of base) : 9326.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -8 (-20.00% of base) : 129784.dasm - System.Xml.Xsl.XPathConvert:MulU(int,int,byref):int
          -8 (-18.18% of base) : 50696.dasm - System.Runtime.InteropServices.SafeBuffer:Initialize(int,int):this
         -20 (-12.20% of base) : 94745.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyInt32(int,int):System.Object
         -20 (-12.20% of base) : 94898.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:MulInt32(int,int):System.Object
        -128 (-11.51% of base) : 63549.dasm - DecCalc:VarDecMul(byref,byref)
          -8 (-11.11% of base) : 50630.dasm - System.Runtime.CompilerServices.RuntimeHelpers:GetRawObjectDataSize(System.Object):long
          -8 (-10.53% of base) : 170637.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161Accuracy:get_TotalMicros():long:this
          -4 (-10.00% of base) : 50659.dasm - System.Runtime.CompilerServices.CastHelpers:Element(byref,int):byref
          -4 (-10.00% of base) : 120093.dasm - System.Data.SqlTypes.SqlMoney:.ctor(int):this
         -16 (-9.76% of base) : 9545.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
         -16 (-8.70% of base) : 94231.dasm - Microsoft.VisualBasic.DateAndTime:TimeSerial(int,int,int):System.DateTime
         -16 (-6.90% of base) : 93763.dasm - Microsoft.VisualBasic.VBMath:Rnd(float):float
          -8 (-6.45% of base) : 57953.dasm - System.TimeSpan:TimeToTicks(int,int,int):long
          -8 (-6.25% of base) : 57988.dasm - System.TimeSpan:.ctor(int,int,int):this
         -20 (-6.10% of base) : 94744.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyUInt32(int,int):System.Object
         -16 (-5.97% of base) : 95256.dasm - FixedList:MoveToFront(int):this
          -8 (-5.88% of base) : 118400.dasm - System.Data.Common.SqlDateTimeStorage:Copy(int,int):this

797 total methods with Code Size differences (797 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1221948
Total bytes of diff: 1210892
Total bytes of delta: -11056 (-0.90% of base)
Total relative delta: -21.57
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -304 : 5388.dasm (-3.51% of base)
        -236 : 86630.dasm (-6.09% of base)
        -176 : 5393.dasm (-3.51% of base)
        -136 : 5392.dasm (-2.47% of base)
         -92 : 66066.dasm (-1.25% of base)
         -72 : 60939.dasm (-1.50% of base)
         -68 : 36540.dasm (-1.65% of base)
         -56 : 129602.dasm (-2.24% of base)
         -56 : 181545.dasm (-3.66% of base)
         -56 : 68130.dasm (-1.04% of base)
         -56 : 31729.dasm (-1.03% of base)
         -56 : 40093.dasm (-0.91% of base)
         -52 : 20018.dasm (-0.82% of base)
         -52 : 67637.dasm (-0.78% of base)
         -52 : 60940.dasm (-1.61% of base)
         -44 : 5386.dasm (-3.36% of base)
         -44 : 5387.dasm (-3.36% of base)
         -40 : 36536.dasm (-1.48% of base)
         -40 : 181542.dasm (-2.96% of base)
         -40 : 36541.dasm (-1.59% of base)

1390 total files with Code Size differences (1390 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -304 (-3.51% of base) : 5388.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBInsert(int,int,int,int,bool):int:this
        -236 (-6.09% of base) : 86630.dasm - Microsoft.Diagnostics.Tracing.Session.TraceEventSession:SetStackTraceIds(int,long,int):int
        -176 (-3.51% of base) : 5393.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteFixup(int,int,int,int):int:this
        -136 (-2.47% of base) : 5392.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RBDeleteX(int,int,int):int:this
         -92 (-1.25% of base) : 66066.dasm - Microsoft.CodeAnalysis.CSharp.SymbolDisplayVisitor:VisitMethod(Microsoft.CodeAnalysis.IMethodSymbol):this
         -72 (-1.50% of base) : 60939.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:GetEnumOperation(int,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[BinaryOperatorSignature]):this
         -68 (-1.65% of base) : 36540.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:AddMethodKind(Microsoft.CodeAnalysis.IMethodSymbol):this
         -56 (-2.24% of base) : 129602.dasm - Microsoft.CodeAnalysis.SyntaxDiffer:GetNextAction():DiffAction:this
         -56 (-3.66% of base) : 181545.dasm - System.Numerics.BigIntegerCalculator:Multiply(long,int,long,int,long,int)
         -56 (-1.04% of base) : 68130.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.SyntaxNormalizer:RewriteTrivia(Microsoft.CodeAnalysis.SyntaxTriviaList,int,bool,bool,bool,int):Microsoft.CodeAnalysis.SyntaxTriviaList:this
         -56 (-1.03% of base) : 31729.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.SyntaxNormalizer:RewriteTrivia(Microsoft.CodeAnalysis.SyntaxTriviaList,int,bool,bool,bool,int,int):Microsoft.CodeAnalysis.SyntaxTriviaList:this
         -56 (-0.91% of base) : 40093.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicDeclarationComputer:ComputeDeclarationsCore(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,System.Collections.Generic.List`1[DeclarationInfo],System.Nullable`1[Int32],System.Threading.CancellationToken)
         -52 (-0.82% of base) : 20018.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.ConstraintsHelper:RemoveDirectConstraintConflicts(Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol,System.Collections.Immutable.ImmutableArray`1[TypeParameterConstraint],Roslyn.Utilities.ConsList`1[[Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeParameterSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.CodeAnalysis.ArrayBuilder`1[TypeParameterDiagnosticInfo]):System.Collections.Immutable.ImmutableArray`1[TypeParameterConstraint]
         -52 (-0.78% of base) : 67637.dasm - Microsoft.CodeAnalysis.CSharp.CSharpDeclarationComputer:ComputeDeclarations(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.SyntaxNode,System.Func`3[[Microsoft.CodeAnalysis.SyntaxNode, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Boolean, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,System.Collections.Generic.List`1[DeclarationInfo],System.Nullable`1[Int32],System.Threading.CancellationToken)
         -52 (-1.61% of base) : 60940.dasm - Microsoft.CodeAnalysis.CSharp.OverloadResolution:GetPointerArithmeticOperators(int,Microsoft.CodeAnalysis.CSharp.Symbols.PointerTypeSymbol,Microsoft.CodeAnalysis.ArrayBuilder`1[BinaryOperatorSignature]):this
         -44 (-3.36% of base) : 5386.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:LeftRotate(int,int,int):int:this
         -44 (-3.36% of base) : 5387.dasm - System.Data.RBTree`1[__Canon][System.__Canon]:RightRotate(int,int,int):int:this
         -40 (-1.48% of base) : 36536.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:VisitProperty(Microsoft.CodeAnalysis.IPropertySymbol):this
         -40 (-2.96% of base) : 181542.dasm - System.Numerics.BigIntegerCalculator:Square(long,int,long,int)
         -40 (-1.59% of base) : 36541.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:AddMethodName(Microsoft.CodeAnalysis.IMethodSymbol):this

Top method improvements (percentages):
         -16 (-30.77% of base) : 163832.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -8 (-20.00% of base) : 114155.dasm - System.Xml.Xsl.XPathConvert:MulU(int,int,byref):int
          -8 (-15.38% of base) : 13659.dasm - System.Runtime.InteropServices.SafeBuffer:Initialize(int):this
         -20 (-13.16% of base) : 833.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:MulInt32(int,int):System.Object
         -20 (-13.16% of base) : 917.dasm - Microsoft.VisualBasic.CompilerServices.Operators:MultiplyInt32(int,int):System.Object
         -16 (-12.50% of base) : 163740.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
          -4 (-11.11% of base) : 217714.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_PingWaitTimeout():System.TimeSpan:this
          -8 (-10.53% of base) : 84808.dasm - System.Security.Cryptography.Pkcs.Asn1.Rfc3161Accuracy:get_TotalMicros():long:this
          -4 (-10.00% of base) : 6588.dasm - System.Data.SqlTypes.SqlMoney:.ctor(int):this
          -4 (-10.00% of base) : 217670.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_SendTimeout():System.TimeSpan:this
          -4 (-10.00% of base) : 217710.dasm - System.DirectoryServices.Protocols.LdapSessionOptions:get_PingKeepAliveTimeout():System.TimeSpan:this
         -16 (-9.30% of base) : 1520.dasm - Microsoft.VisualBasic.DateAndTime:TimeSerial(int,int,int):System.DateTime
          -8 (-6.67% of base) : 84648.dasm - System.Security.Cryptography.Pkcs.Rfc3161TimestampTokenInfo:get_AccuracyInMicroseconds():System.Nullable`1[Int64]:this
         -16 (-6.56% of base) : 2010.dasm - Microsoft.VisualBasic.VBMath:Rnd(float):float
          -8 (-6.45% of base) : 8272.dasm - System.Data.Common.SqlDateTimeStorage:Compare(int,int):int:this
          -8 (-6.45% of base) : 8275.dasm - System.Data.Common.SqlDateTimeStorage:Copy(int,int):this
          -8 (-6.45% of base) : 8286.dasm - System.Data.Common.SqlDecimalStorage:Compare(int,int):int:this
          -4 (-6.25% of base) : 55057.dasm - DebugView:<GetInstructionViews>b__4_0(int):int:this
          -4 (-6.25% of base) : 7363.dasm - System.Data.Common.DataRecordInternal:GetName(int):System.String:this
          -4 (-6.25% of base) : 212846.dasm - WorkingChain:get_Item(int):byref:this

1390 total methods with Code Size differences (1390 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1868204
Total bytes of diff: 1856328
Total bytes of delta: -11876 (-0.64% of base)
Total relative delta: -14.11
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -156 : 260164.dasm (-1.64% of base)
        -152 : 259996.dasm (-1.41% of base)
        -144 : 260037.dasm (-1.09% of base)
        -132 : 259995.dasm (-1.26% of base)
        -104 : 299321.dasm (-2.91% of base)
         -88 : 170270.dasm (-1.98% of base)
         -88 : 259997.dasm (-1.17% of base)
         -84 : 259374.dasm (-1.28% of base)
         -72 : 260081.dasm (-1.19% of base)
         -68 : 260094.dasm (-1.30% of base)
         -64 : 259552.dasm (-1.39% of base)
         -60 : 259612.dasm (-1.70% of base)
         -60 : 260082.dasm (-1.12% of base)
         -60 : 260307.dasm (-0.65% of base)
         -60 : 260092.dasm (-1.32% of base)
         -56 : 237338.dasm (-1.97% of base)
         -56 : 259561.dasm (-1.14% of base)
         -56 : 260088.dasm (-1.30% of base)
         -56 : 88635.dasm (-0.94% of base)
         -56 : 260090.dasm (-1.30% of base)

1387 total files with Code Size differences (1387 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -156 (-1.64% of base) : 260164.dasm - System.Data.Tests.DataTableTest:ImportRowTest():this
        -152 (-1.41% of base) : 259996.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestOverwriteChanges():this
        -144 (-1.09% of base) : 260037.dasm - System.Data.Tests.DataTableReaderTest:TestSchemaTable():this
        -132 (-1.26% of base) : 259995.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestUpsert():this
        -104 (-2.91% of base) : 299321.dasm - System.Xml.Tests.ToTypeTests:ToType57():int:this
         -88 (-1.98% of base) : 170270.dasm - Microsoft.CodeAnalysis.CSharp.CodeGeneration.CSharpSyntaxGenerator:AsModifierList(int,Microsoft.CodeAnalysis.Editing.DeclarationModifiers):Microsoft.CodeAnalysis.SyntaxTokenList
         -88 (-1.17% of base) : 259997.dasm - System.Data.Tests.DataTableLoadRowTest:LoadRowTestPreserveChanges():this
         -84 (-1.28% of base) : 259374.dasm - System.Data.Tests.DataColumnTest:ExpressionOperator():this
         -72 (-1.19% of base) : 260081.dasm - System.Data.Tests.DataTableTest:Load_MissingColsDefault():this
         -68 (-1.30% of base) : 260094.dasm - System.Data.Tests.DataTableTest:Load_RowStateUpsertDuplicateKey1():this
         -64 (-1.39% of base) : 259552.dasm - System.Data.Tests.DataRowTest:ParentRowTest():this
         -60 (-1.70% of base) : 259612.dasm - System.Data.Tests.DataRowTest2:TestRowErrors():this
         -60 (-1.12% of base) : 260082.dasm - System.Data.Tests.DataTableTest:Load_MissingColsNullable():this
         -60 (-0.65% of base) : 260307.dasm - System.Data.Tests.DataTableTest4:XmlTest9():this
         -60 (-1.32% of base) : 260092.dasm - System.Data.Tests.DataTableTest:Load_RowStateOverwriteChanges():this
         -56 (-1.97% of base) : 237338.dasm - System.Reflection.Metadata.Ecma335.Tests.MetadataBuilderTests:ValidateGenericParamTable():this
         -56 (-1.14% of base) : 259561.dasm - System.Data.Tests.DataRowTest:AutoIncrementInItemArray():this
         -56 (-1.30% of base) : 260088.dasm - System.Data.Tests.DataTableTest:Load_RowStateChangesDefault():this
         -56 (-0.94% of base) : 88635.dasm - Microsoft.CodeAnalysis.Diagnostics.Analyzers.NamingStyles.EditorConfigNamingStyleParser:ParseSymbolKindList(System.String):System.Collections.Immutable.ImmutableArray`1[SymbolKindOrTypeKind]
         -56 (-1.30% of base) : 260090.dasm - System.Data.Tests.DataTableTest:Load_RowStatePreserveChanges():this

Top method improvements (percentages):
         -16 (-30.77% of base) : 165611.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
          -4 (-14.29% of base) : 258350.dasm - System.Data.SqlClient.TdsParserStateObject:SetTimeoutSeconds(int):this
          -4 (-14.29% of base) : 167706.dasm - System.Data.SqlClient.TdsParserStateObject:SetTimeoutSeconds(int):this
          -8 (-12.50% of base) : 95539.dasm - System.Text.Encodings.Web.Tests.EncoderCommon:GetCapacityOfOutputStringBuilder(int,int):int
         -16 (-9.30% of base) : 165470.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
         -16 (-9.30% of base) : 256161.dasm - System.Data.ProviderBase.TimeoutTimer:SetTimeoutSeconds(int):this
          -8 (-9.09% of base) : 231694.dasm - NuGet.Packaging.Signing.Accuracy:GetTotalMicroseconds():System.Nullable`1[Int64]:this
         -16 (-7.84% of base) : 167749.dasm - System.Data.SqlClient.TdsParserStaticMethods:GetRemainingTimeout(int,long):int
         -16 (-7.84% of base) : 258393.dasm - System.Data.SqlClient.TdsParserStaticMethods:GetRemainingTimeout(int,long):int
          -4 (-5.88% of base) : 289552.dasm - Unity.Storage.MiniHashSet`1[Byte][System.Byte]:get_Item(int):ubyte:this
          -4 (-5.88% of base) : 289564.dasm - Unity.Storage.MiniHashSet`1[Int16][System.Int16]:get_Item(int):short:this
          -4 (-5.88% of base) : 289569.dasm - Unity.Storage.MiniHashSet`1[Int32][System.Int32]:get_Item(int):int:this
          -4 (-5.88% of base) : 289574.dasm - Unity.Storage.MiniHashSet`1[Double][System.Double]:get_Item(int):double:this
          -4 (-5.88% of base) : 289584.dasm - Unity.Storage.MiniHashSet`1[Int64][System.Int64]:get_Item(int):long:this
          -4 (-4.76% of base) : 140391.dasm - <>c:<CastReadOnlySpanOverflow>b__19_0(System.ReadOnlySpan`1[TestStructExplicit]):this
          -4 (-4.76% of base) : 140395.dasm - <>c:<CastSpanOverflow>b__26_0(System.Span`1[TestStructExplicit]):this
          -4 (-4.55% of base) : 140396.dasm - <>c:<CastSpanOverflow>b__26_1(System.Span`1[TestStructExplicit]):this
          -4 (-4.55% of base) : 140392.dasm - <>c:<CastReadOnlySpanOverflow>b__19_1(System.ReadOnlySpan`1[TestStructExplicit]):this
         -16 (-4.12% of base) : 183397.dasm - Microsoft.Build.Shared.NativeMethodsShared:GetFullPath(System.String):System.String
         -16 (-4.12% of base) : 27582.dasm - Microsoft.Build.Shared.NativeMethodsShared:GetFullPath(System.String):System.String

1387 total methods with Code Size differences (1387 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------
