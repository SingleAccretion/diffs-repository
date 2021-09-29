## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 784248
Total bytes of diff: 782412
Total bytes of delta: -1836 (-0.23% of base)
Total relative delta: -6.40
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -93 : 9089.dasm (-2.50% of base)
         -62 : 9627.dasm (-0.87% of base)
         -20 : 1966.dasm (-0.56% of base)
         -18 : 25964.dasm (-0.11% of base)
         -16 : 2706.dasm (-0.65% of base)
         -16 : 1873.dasm (-0.37% of base)
         -15 : 37619.dasm (-1.48% of base)
         -15 : 42837.dasm (-0.39% of base)
         -13 : 42796.dasm (-1.99% of base)
         -13 : 4413.dasm (-0.66% of base)
         -11 : 2192.dasm (-0.44% of base)
         -11 : 15658.dasm (-0.37% of base)
         -10 : 15848.dasm (-0.45% of base)
         -10 : 1865.dasm (-0.33% of base)
          -9 : 42175.dasm (-0.24% of base)
          -9 : 9154.dasm (-0.76% of base)
          -9 : 14800.dasm (-0.46% of base)
          -9 : 3752.dasm (-1.23% of base)
          -9 : 39897.dasm (-0.10% of base)
          -9 : 33002.dasm (-0.25% of base)

591 total files with Code Size differences (591 improved, 0 regressed), 7 unchanged.

Top method improvements (bytes):
         -93 (-2.50% of base) : 9089.dasm - HttpResponseHeaders:ClearFast():this
         -62 (-0.87% of base) : 9627.dasm - HttpResponseHeaders:SetValueFast(String,StringValues):this
         -20 (-0.56% of base) : 1966.dasm - Utf8Utility:TranscodeToUtf8(long,int,long,int,byref,byref):int
         -18 (-0.11% of base) : 25964.dasm - NpgsqlTypeMappingSource:.ctor(TypeMappingSourceDependencies,RelationalTypeMappingSourceDependencies,ISqlGenerationHelper,INpgsqlOptions):this
         -16 (-0.65% of base) : 2706.dasm - Utf16Utility:GetPointerToFirstInvalidChar(long,int,byref,byref):long
         -16 (-0.37% of base) : 1873.dasm - Utf8Utility:TranscodeToUtf16(long,int,long,int,byref,byref):int
         -15 (-1.48% of base) : 37619.dasm - String:CompareOrdinalHelper(String,String):int
         -15 (-0.39% of base) : 42837.dasm - RegexWriter:EmitFragment(int,RegexNode,int):this
         -13 (-1.99% of base) : 42796.dasm - RegexCharClass:CharInClassInternal(ushort,String,int,int,int):bool
         -13 (-0.66% of base) : 4413.dasm - IPv4AddressHelper:ParseNonCanonical(long,int,byref,bool):long
         -11 (-0.44% of base) : 2192.dasm - JsonWriterHelper:ToUtf8(ReadOnlySpan`1,Span`1,byref,byref):int
         -11 (-0.37% of base) : 15658.dasm - Uri:PrivateParseMinimal():int:this
         -10 (-0.45% of base) : 15848.dasm - Uri:CheckCanonical(long,byref,int,ushort):int:this
         -10 (-0.33% of base) : 1865.dasm - Utf8Utility:GetPointerToFirstInvalidByte(long,int,byref,byref):long
          -9 (-0.24% of base) : 42175.dasm - <WriteBind>d__272:MoveNext():this
          -9 (-0.76% of base) : 9154.dasm - PathNormalizer:RemoveDotSegments(long,long):int
          -9 (-0.46% of base) : 14800.dasm - XmlUtf8RawTextWriter:WriteCommentOrPi(String,int):this
          -9 (-1.23% of base) : 3752.dasm - AppContextConfigHelper:GetInt16Config(String,short,bool):short
          -9 (-0.10% of base) : 39897.dasm - ILEmitResolverBuilder:GenerateMethodBody(ServiceCallSite,ILGenerator):ILEmitResolverBuilderRuntimeContext:this
          -9 (-0.25% of base) : 33002.dasm - <WriteBind>d__272:MoveNext():this

Top method improvements (percentages):
          -3 (-25.00% of base) : 5264.dasm - ThreadCounts:get_NumThreadsGoal():short:this
          -3 (-25.00% of base) : 5322.dasm - ThreadCounts:get_NumExistingThreads():short:this
          -3 (-25.00% of base) : 24877.dasm - BinaryPrimitives:ReverseEndianness(short):short
          -3 (-21.43% of base) : 5251.dasm - ThreadCounts:GetInt16Value(ubyte):short:this
          -9 (-12.86% of base) : 3776.dasm - Math:Max(short,short):short
          -9 (-12.86% of base) : 4017.dasm - Math:Min(short,short):short
          -3 (-9.38% of base) : 5894.dasm - ThreadCounts:SubtractNumProcessingWork(short):this
          -3 (-9.09% of base) : 3773.dasm - ThreadCounts:GetInt16Value(ubyte):short:this
          -3 (-8.33% of base) : 5376.dasm - ThreadCounts:SubtractNumExistingThreads(short):this
          -3 (-7.89% of base) : 1784.dasm - BinaryPrimitives:ReverseEndianness(short):short
          -1 (-6.67% of base) : 19642.dasm - RelationalExtensionInfo:GetServiceProviderHashCode():long:this
          -1 (-6.67% of base) : 28831.dasm - RelationalExtensionInfo:GetServiceProviderHashCode():long:this
          -3 (-6.52% of base) : 7916.dasm - PortableThreadPool:get_MinThreadsGoal():short:this
          -3 (-6.38% of base) : 25311.dasm - NpgsqlRelationalConnection:get_DbConnection():NpgsqlConnection:this
          -3 (-6.38% of base) : 28204.dasm - NpgsqlRelationalConnection:get_DbConnection():NpgsqlConnection:this
          -3 (-5.36% of base) : 11262.dasm - RuntimeResourceSet:GetString(String,bool):String:this
          -3 (-4.76% of base) : 40452.dasm - StreamPipeWriter:ReturnSegmentUnsynchronized(BufferSegment):this
          -3 (-4.76% of base) : 40716.dasm - StreamPipeReader:ReturnSegmentUnsynchronized(BufferSegment):this
          -3 (-4.69% of base) : 25946.dasm - NpgsqlConnection:GetSchema(String):DataTable:this
          -2 (-4.55% of base) : 37590.dasm - Stopwatch:Reset():this

591 total methods with Code Size differences (591 improved, 0 regressed), 7 unchanged.

```

</details>

--------------------------------------------------------------------------------

## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 470717
Total bytes of diff: 469679
Total bytes of delta: -1038 (-0.22% of base)
Total relative delta: -2.72
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 14025.dasm (0.22% of base)

Top file improvements (bytes):
         -24 : 15702.dasm (-0.11% of base)
         -22 : 20694.dasm (-6.75% of base)
         -22 : 15987.dasm (-3.98% of base)
         -19 : 14066.dasm (-0.11% of base)
         -12 : 3363.dasm (-0.37% of base)
         -12 : 8581.dasm (-0.45% of base)
         -10 : 21294.dasm (-2.40% of base)
         -10 : 13525.dasm (-0.77% of base)
         -10 : 4824.dasm (-2.87% of base)
          -9 : 20702.dasm (-0.85% of base)
          -9 : 4072.dasm (-2.20% of base)
          -9 : 18441.dasm (-0.23% of base)
          -9 : 5964.dasm (-0.24% of base)
          -9 : 10501.dasm (-0.35% of base)
          -9 : 12920.dasm (-3.46% of base)
          -9 : 6052.dasm (-0.33% of base)
          -9 : 5664.dasm (-0.14% of base)
          -9 : 6064.dasm (-0.25% of base)
          -8 : 6432.dasm (-0.74% of base)
          -7 : 19981.dasm (-2.70% of base)

346 total files with Code Size differences (345 improved, 1 regressed), 4 unchanged.

Top method regressions (bytes):
           2 ( 0.22% of base) : 14025.dasm - IDEAEncryption:de_key_idea(System.Char[],System.Char[])

Top method improvements (bytes):
         -24 (-0.11% of base) : 15702.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.MyEventsListerItem,int)
         -22 (-6.75% of base) : 20694.dasm - System.SpanHelpers:LastIndexOf(byref,int,int):int
         -22 (-3.98% of base) : 15987.dasm - System.SpanHelpers:IndexOfAny(byref,int,int,int,int):int
         -19 (-0.11% of base) : 14066.dasm - DynamicClass:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)
         -12 (-0.37% of base) : 3363.dasm - System.Xml.Serialization.XmlSerializationWriterILGen:WriteElement(System.Xml.Serialization.SourceInfo,System.Xml.Serialization.ElementAccessor,System.String,bool):this
         -12 (-0.45% of base) : 8581.dasm - System.Xml.XmlBaseWriter:StartAttribute(byref,System.String,System.String,System.Xml.XmlDictionaryString):this
         -10 (-2.40% of base) : 21294.dasm - System.SpanHelpers:LastIndexOfAny(byref,int,int,int):int
         -10 (-0.77% of base) : 13525.dasm - AssignRect:first_assignments(System.Int32[,],System.Int16[,]):int
         -10 (-2.87% of base) : 4824.dasm - System.SpanHelpers:LastIndexOf(byref,ushort,int):int
          -9 (-0.85% of base) : 20702.dasm - System.Net.WebUtility:HtmlDecode(System.ReadOnlySpan`1[Char],byref)
          -9 (-2.20% of base) : 4072.dasm - BlockingConfig:.cctor()
          -9 (-0.23% of base) : 18441.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:MakeConversionNode(Microsoft.CodeAnalysis.CSharp.BoundConversion,Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
          -9 (-0.24% of base) : 5964.dasm - <ReceiveBlobAsync>d__174`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
          -9 (-0.35% of base) : 10501.dasm - System.Uri:GetCanonicalPath(byref,int):this
          -9 (-3.46% of base) : 12920.dasm - AssignJagged:calc_minimum_costs(System.Int32[][])
          -9 (-0.33% of base) : 6052.dasm - <ReadLineAsyncInternal>d__63:MoveNext():this
          -9 (-0.14% of base) : 5664.dasm - <SendWithVersionDetectionAndRetryAsync>d__83:MoveNext():this
          -9 (-0.25% of base) : 6064.dasm - <ReadAsyncInternal>d__186`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
          -8 (-0.74% of base) : 6432.dasm - Enumerator:MoveNext():bool:this
          -7 (-2.70% of base) : 19981.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.LanguageParser:ParseIdentifierName(int):Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IdentifierNameSyntax:this

Top method regressions (percentages):
           2 ( 0.22% of base) : 14025.dasm - IDEAEncryption:de_key_idea(System.Char[],System.Char[])

Top method improvements (percentages):
          -1 (-14.29% of base) : 6309.dasm - System.Reflection.Internal.ReadOnlyUnmanagedMemoryStream:get_Position():long:this
          -1 (-14.29% of base) : 6308.dasm - System.Reflection.Internal.ReadOnlyUnmanagedMemoryStream:get_Length():long:this
          -3 (-7.50% of base) : 7766.dasm - MessagePack.Decoders.FixInt16:Read(System.Byte[],int,byref):short:this
         -22 (-6.75% of base) : 20694.dasm - System.SpanHelpers:LastIndexOf(byref,int,int):int
          -3 (-6.52% of base) : 18709.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilation:BindScriptClass():Microsoft.CodeAnalysis.CSharp.Symbols.ImplicitNamedTypeSymbol:this
          -3 (-5.88% of base) : 11085.dasm - Newtonsoft.Json.JsonTextReader:ReadAsString():System.String:this
          -3 (-5.36% of base) : 1026.dasm - System.Resources.RuntimeResourceSet:GetString(System.String,bool):System.String:this
          -3 (-5.26% of base) : 17990.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceOrdinaryMethodSymbol:GetSyntax():Microsoft.CodeAnalysis.CSharp.Syntax.MethodDeclarationSyntax:this
          -3 (-4.62% of base) : 4139.dasm - System.Threading.PortableThreadPool:get_MinThreadsGoal():short:this
          -3 (-4.48% of base) : 8000.dasm - System.Runtime.Serialization.CodeGenerator:PopIfState():System.Runtime.Serialization.IfState:this
         -22 (-3.98% of base) : 15987.dasm - System.SpanHelpers:IndexOfAny(byref,int,int,int,int):int
          -3 (-3.85% of base) : 9580.dasm - Sigil.Impl.ExtensionMethods:IsTailableCall(System.Reflection.Emit.OpCode):bool
          -7 (-3.63% of base) : 11910.dasm - System.Xml.Serialization.CodeGenerator:Ldobj(System.Type):this
          -2 (-3.57% of base) : 19724.dasm - System.MathBenchmarks.MathTests:.cctor()
          -9 (-3.46% of base) : 12920.dasm - AssignJagged:calc_minimum_costs(System.Int32[][])
          -3 (-3.45% of base) : 17768.dasm - Microsoft.CodeAnalysis.RuntimeMembers.SignatureComparer`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:ReadTypeId(System.Collections.Immutable.ImmutableArray`1[Byte],byref):short
          -3 (-3.26% of base) : 3267.dasm - System.Xml.Serialization.XmlReflectionImporter:ReconcileLocalAccessor(System.Xml.Serialization.ElementAccessor,System.String):System.Xml.Serialization.ElementAccessor:this
          -1 (-3.12% of base) : 1788.dasm - System.IO.MemoryStream:get_Position():long:this
          -1 (-3.12% of base) : 3301.dasm - System.IO.MemoryStream:get_Length():long:this
          -3 (-3.09% of base) : 18664.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.StackOptimizerPass1:VisitCallReceiver(Microsoft.CodeAnalysis.CSharp.BoundExpression):Microsoft.CodeAnalysis.CSharp.BoundExpression:this

346 total methods with Code Size differences (345 improved, 1 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3193859
Total bytes of diff: 3176629
Total bytes of delta: -17230 (-0.54% of base)
Total relative delta: -174.76
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           5 : 164897.dasm (0.28% of base)
           2 : 177904.dasm (0.22% of base)
           1 : 83411.dasm (0.31% of base)

Top file improvements (bytes):
        -757 : 219311.dasm (-14.35% of base)
        -217 : 177284.dasm (-0.17% of base)
        -168 : 177482.dasm (-0.13% of base)
        -144 : 177273.dasm (-0.12% of base)
        -128 : 177472.dasm (-0.10% of base)
         -64 : 200118.dasm (-0.38% of base)
         -49 : 177531.dasm (-0.04% of base)
         -49 : 177541.dasm (-0.04% of base)
         -49 : 177343.dasm (-0.04% of base)
         -49 : 177362.dasm (-0.04% of base)
         -48 : 198383.dasm (-0.84% of base)
         -48 : 198406.dasm (-0.89% of base)
         -48 : 207215.dasm (-0.89% of base)
         -43 : 177628.dasm (-0.07% of base)
         -43 : 177634.dasm (-0.07% of base)
         -39 : 207449.dasm (-0.81% of base)
         -39 : 207451.dasm (-0.81% of base)
         -38 : 207154.dasm (-0.83% of base)
         -38 : 207520.dasm (-0.84% of base)
         -31 : 209795.dasm (-0.23% of base)

5323 total files with Code Size differences (5320 improved, 3 regressed), 3 unchanged.

Top method regressions (bytes):
           5 ( 0.28% of base) : 164897.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this
           2 ( 0.22% of base) : 177904.dasm - IDEAEncryption:de_key_idea(System.Char[],System.Char[])
           1 ( 0.31% of base) : 83411.dasm - <Module>:Main():int

Top method improvements (bytes):
        -757 (-14.35% of base) : 219311.dasm - ldarg_s_i2:test_int16(short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short):int
        -217 (-0.17% of base) : 177284.dasm - i4div:Main():int
        -168 (-0.13% of base) : 177482.dasm - i4rem:Main():int
        -144 (-0.12% of base) : 177273.dasm - i4div:Main():int
        -128 (-0.10% of base) : 177472.dasm - i4rem:Main():int
         -64 (-0.38% of base) : 200118.dasm - test:Main():int
         -49 (-0.04% of base) : 177531.dasm - overldrem:Main():int
         -49 (-0.04% of base) : 177541.dasm - overldrem:Main():int
         -49 (-0.04% of base) : 177343.dasm - overlddiv:Main():int
         -49 (-0.04% of base) : 177362.dasm - overlddiv:Main():int
         -48 (-0.84% of base) : 198383.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -48 (-0.89% of base) : 198406.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -48 (-0.89% of base) : 207215.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -43 (-0.07% of base) : 177628.dasm - testout1:Func_0():int
         -43 (-0.07% of base) : 177634.dasm - testout1:Func_0():int
         -39 (-0.81% of base) : 207449.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -39 (-0.81% of base) : 207451.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -38 (-0.83% of base) : 207154.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -38 (-0.84% of base) : 207520.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -31 (-0.23% of base) : 209795.dasm - ILGEN_0x372a9ae6:Method_0xdc6ff1a4(byte,byte,int,long,ushort,double,long,long):int

Top method regressions (percentages):
           1 ( 0.31% of base) : 83411.dasm - <Module>:Main():int
           5 ( 0.28% of base) : 164897.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this
           2 ( 0.22% of base) : 177904.dasm - IDEAEncryption:de_key_idea(System.Char[],System.Char[])

Top method improvements (percentages):
          -3 (-33.33% of base) : 233698.dasm - Wrapper`1[Int16][System.Int16]:op_Implicit(short):Wrapper`1[Int16]
          -3 (-33.33% of base) : 10269.dasm - JIT.HardwareIntrinsics.Arm.Helpers:ZeroExtendWidening(byte):short
          -3 (-30.00% of base) : 88203.dasm - Program:Test_ldind_u1_conv_i2(byref,byref)
          -3 (-30.00% of base) : 88205.dasm - Program:Test_ldind_u1_conv_ovf_i2(byref,byref)
          -3 (-30.00% of base) : 88208.dasm - Program:Test_ldind_u1_conv_ovf_i2_un(byref,byref)
          -3 (-27.27% of base) : 10408.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Not(short):short
          -3 (-27.27% of base) : 88267.dasm - Program:Test_ldind_i1_conv_i2(byref,byref)
          -3 (-27.27% of base) : 88269.dasm - Program:Test_ldind_i1_conv_ovf_i2(byref,byref)
          -3 (-27.27% of base) : 9487.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Negate(short):short
          -3 (-25.00% of base) : 207888.dasm - FloatOvfToInt:FloatToShort(float):short
          -3 (-25.00% of base) : 207889.dasm - FloatOvfToInt:FloatToShortInline(float):short
          -3 (-25.00% of base) : 207901.dasm - FloatOvfToInt:DoubleToShort(double):short
          -3 (-25.00% of base) : 207902.dasm - FloatOvfToInt:DoubleToShortInline(double):short
          -6 (-23.08% of base) : 172067.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 37464.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 126610.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 132449.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 115750.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 118183.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short
          -6 (-23.08% of base) : 113167.dasm - JIT.HardwareIntrinsics.Arm.Helpers:MultiplyWideningAndAdd(short,byte,byte):short

5323 total methods with Code Size differences (5320 improved, 3 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 665225
Total bytes of diff: 662273
Total bytes of delta: -2952 (-0.44% of base)
Total relative delta: -35.92
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -48 : 6698.dasm (-1.18% of base)
         -22 : 84317.dasm (-6.73% of base)
         -21 : 163575.dasm (-0.76% of base)
         -15 : 33928.dasm (-1.00% of base)
         -15 : 158406.dasm (-0.48% of base)
         -12 : 16640.dasm (-3.85% of base)
         -12 : 66613.dasm (-0.25% of base)
         -12 : 33338.dasm (-1.20% of base)
         -12 : 80461.dasm (-1.66% of base)
         -10 : 84318.dasm (-2.82% of base)
         -10 : 84319.dasm (-1.38% of base)
         -10 : 84320.dasm (-1.30% of base)
         -10 : 84307.dasm (-2.87% of base)
          -9 : 152318.dasm (-0.45% of base)
          -9 : 12584.dasm (-0.27% of base)
          -9 : 195065.dasm (-2.09% of base)
          -9 : 151230.dasm (-1.23% of base)
          -9 : 167623.dasm (-0.17% of base)
          -9 : 10177.dasm (-0.05% of base)
          -9 : 65485.dasm (-0.26% of base)

1325 total files with Code Size differences (1325 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -48 (-1.18% of base) : 6698.dasm - System.Data.OleDb.OleDbDataReader:DumpToSchemaTable(System.Data.Common.UnsafeNativeMethods+IRowset):this
         -22 (-6.73% of base) : 84317.dasm - System.SpanHelpers:LastIndexOf(byref,int,int):int
         -21 (-0.76% of base) : 163575.dasm - Newtonsoft.Json.Utilities.ConvertUtils:.cctor()
         -15 (-1.00% of base) : 33928.dasm - Microsoft.VisualBasic.CompilerServices.Conversions:ToShort(System.Object):short
         -15 (-0.48% of base) : 158406.dasm - Microsoft.CodeAnalysis.VisualBasic.BinderFactory:CreateBinderForNodeAndUsage(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,ubyte,Microsoft.CodeAnalysis.VisualBasic.Binder):Microsoft.CodeAnalysis.VisualBasic.Binder:this
         -12 (-3.85% of base) : 16640.dasm - System.Xml.Xsl.IlGen.GenerateHelper:TestAndBranch(int,System.Reflection.Emit.Label,System.Reflection.Emit.OpCode):this
         -12 (-0.25% of base) : 66613.dasm - <WriteToUnderlyingStreamAsync>d__60:MoveNext():this
         -12 (-1.20% of base) : 33338.dasm - Microsoft.VisualBasic.CompilerServices.ShortType:FromObject(System.Object):short
         -12 (-1.66% of base) : 80461.dasm - System.Convert:ConvertToBase64Array(long,long,int,int,bool):int
         -10 (-2.82% of base) : 84318.dasm - System.SpanHelpers:LastIndexOf(byref,long,int):int
         -10 (-1.38% of base) : 84319.dasm - System.SpanHelpers:LastIndexOf(byref,float,int):int
         -10 (-1.30% of base) : 84320.dasm - System.SpanHelpers:LastIndexOf(byref,double,int):int
         -10 (-2.87% of base) : 84307.dasm - System.SpanHelpers:LastIndexOf(byref,ushort,int):int
          -9 (-0.45% of base) : 152318.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:VisitConditionalAccess(Microsoft.CodeAnalysis.VisualBasic.BoundConditionalAccess):Microsoft.CodeAnalysis.VisualBasic.BoundNode:this
          -9 (-0.27% of base) : 12584.dasm - System.Data.XSDSchema:HandleElementColumn(System.Xml.Schema.XmlSchemaElement,System.Data.DataTable,bool):this
          -9 (-2.09% of base) : 195065.dasm - System.ConsolePal:SetWindowPosition(int,int)
          -9 (-1.23% of base) : 151230.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:ConvertToBool(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
          -9 (-0.17% of base) : 167623.dasm - System.Text.RegularExpressions.RegexWriter:EmitFragment(int,System.Text.RegularExpressions.RegexNode,int):this
          -9 (-0.05% of base) : 10177.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
          -9 (-0.26% of base) : 65485.dasm - <WriteAsyncSlowPath>d__50:MoveNext():this

Top method improvements (percentages):
          -3 (-30.00% of base) : 32541.dasm - Microsoft.VisualBasic.FileSystem:TAB():Microsoft.VisualBasic.TabInfo
          -3 (-30.00% of base) : 72475.dasm - CountsOfThreadsProcessingUserCallbacks:get_HighWatermark():short:this
          -3 (-27.27% of base) : 79377.dasm - System.Int16:System.IUnaryNegationOperators<System.Int16,System.Int16>.op_UnaryNegation(short):short
          -3 (-27.27% of base) : 79406.dasm - System.Int16:System.IIncrementOperators<System.Int16>.op_Increment(short):short
          -3 (-27.27% of base) : 79410.dasm - System.Int16:System.IDecrementOperators<System.Int16>.op_Decrement(short):short
          -3 (-27.27% of base) : 79415.dasm - System.Int16:System.IBitwiseOperators<System.Int16,System.Int16,System.Int16>.op_OnesComplement(short):short
          -3 (-27.27% of base) : 75878.dasm - System.Version:get_MajorRevision():short:this
          -3 (-25.00% of base) : 73672.dasm - System.Buffers.Binary.BinaryPrimitives:ReverseEndianness(short):short
          -3 (-25.00% of base) : 79424.dasm - System.Int16:System.IBinaryInteger<System.Int16>.PopCount(short):short
          -3 (-25.00% of base) : 72480.dasm - CountsOfThreadsProcessingUserCallbacks:GetInt16Value(ubyte):short:this
          -3 (-25.00% of base) : 72508.dasm - ThreadCounts:get_NumThreadsGoal():short:this
          -3 (-25.00% of base) : 72511.dasm - ThreadCounts:get_NumExistingThreads():short:this
          -3 (-23.08% of base) : 193934.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -3 (-23.08% of base) : 79382.dasm - System.Int16:System.IShiftOperators<System.Int16,System.Int16>.op_RightShift(short,int):short
          -3 (-23.08% of base) : 79383.dasm - System.Int16:System.IShiftOperators<System.Int16,System.Int16>.op_LeftShift(short,int):short
          -3 (-23.08% of base) : 193937.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -6 (-22.22% of base) : 200349.dasm - System.Formats.Cbor.HalfHelpers:ReadHalfBigEndian(System.ReadOnlySpan`1[System.Byte]):System.Half
          -3 (-21.43% of base) : 72517.dasm - ThreadCounts:GetInt16Value(ubyte):short:this
          -3 (-20.00% of base) : 79378.dasm - System.Int16:System.ISubtractionOperators<System.Int16,System.Int16,System.Int16>.op_Subtraction(short,short):short
          -3 (-20.00% of base) : 79416.dasm - System.Int16:System.IBitwiseOperators<System.Int16,System.Int16,System.Int16>.op_ExclusiveOr(short,short):short

1325 total methods with Code Size differences (1325 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2123663
Total bytes of diff: 2115504
Total bytes of delta: -8159 (-0.38% of base)
Total relative delta: -40.56
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           5 : 160669.dasm (0.28% of base)

Top file improvements (bytes):
         -29 : 6243.dasm (-2.70% of base)
         -27 : 57635.dasm (-1.03% of base)
         -25 : 57570.dasm (-0.75% of base)
         -22 : 15883.dasm (-3.98% of base)
         -21 : 163463.dasm (-0.89% of base)
         -19 : 147597.dasm (-0.26% of base)
         -18 : 147567.dasm (-0.28% of base)
         -18 : 57718.dasm (-0.41% of base)
         -16 : 114267.dasm (-0.48% of base)
         -16 : 15880.dasm (-3.31% of base)
         -16 : 114268.dasm (-0.34% of base)
         -16 : 15886.dasm (-2.58% of base)
         -15 : 57636.dasm (-0.55% of base)
         -15 : 147283.dasm (-0.25% of base)
         -15 : 147285.dasm (-0.35% of base)
         -15 : 50315.dasm (-0.36% of base)
         -15 : 68721.dasm (-1.31% of base)
         -14 : 15900.dasm (-2.60% of base)
         -13 : 1929.dasm (-0.09% of base)
         -12 : 147613.dasm (-0.37% of base)

2707 total files with Code Size differences (2706 improved, 1 regressed), 6 unchanged.

Top method regressions (bytes):
           5 ( 0.28% of base) : 160669.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this

Top method improvements (bytes):
         -29 (-2.70% of base) : 6243.dasm - select@1054:Invoke(System.Reflection.MethodInfo):bool:this
         -27 (-1.03% of base) : 57635.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseExitStatement():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.StatementSyntax:this
         -25 (-0.75% of base) : 57570.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseInterpolatedStringInterpolation():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationSyntax:this
         -22 (-3.98% of base) : 15883.dasm - System.SpanHelpers:IndexOfAny(byref,int,int,int,int):int
         -21 (-0.89% of base) : 163463.dasm - Microsoft.Extensions.FileSystemGlobbing.Internal.Patterns.PatternBuilder:Build(System.String):Microsoft.Extensions.FileSystemGlobbing.Internal.IPattern:this
         -19 (-0.26% of base) : 147597.dasm - System.Xml.Serialization.XmlSerializationWriterCodeGen:GenerateMembersElement(System.Xml.Serialization.XmlMembersMapping):System.String:this
         -18 (-0.28% of base) : 147567.dasm - System.Xml.Serialization.XmlSerializationWriterCodeGen:WriteElement(System.String,System.Xml.Serialization.ElementAccessor,System.String,bool):this
         -18 (-0.41% of base) : 57718.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseGenericParameters():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax:this
         -16 (-0.48% of base) : 114267.dasm - System.Data.ProviderBase.SchemaMapping:SetupSchemaWithoutKeyInfo(int,int,bool,System.Data.DataColumn,System.Object):System.Object[]:this
         -16 (-3.31% of base) : 15880.dasm - System.SpanHelpers:IndexOfAny(byref,long,long,int):int
         -16 (-0.34% of base) : 114268.dasm - System.Data.ProviderBase.SchemaMapping:SetupSchemaWithKeyInfo(int,int,bool,System.Data.DataColumn,System.Object):System.Object[]:this
         -16 (-2.58% of base) : 15886.dasm - System.SpanHelpers:IndexOfAny(byref,long,long,long,int):int
         -15 (-0.55% of base) : 57636.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseCaseStatement():Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CaseStatementSyntax:this
         -15 (-0.25% of base) : 147283.dasm - System.Xml.Serialization.XmlSerializationReaderCodeGen:GenerateLiteralMembersElement(System.Xml.Serialization.XmlMembersMapping):System.String:this
         -15 (-0.35% of base) : 147285.dasm - System.Xml.Serialization.XmlSerializationReaderCodeGen:GenerateEncodedMembersElement(System.Xml.Serialization.XmlMembersMapping):System.String:this
         -15 (-0.36% of base) : 50315.dasm - Microsoft.CodeAnalysis.VisualBasic.BinderFactory:CreateBinderForNodeAndUsage(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,ubyte,Microsoft.CodeAnalysis.VisualBasic.Binder):Microsoft.CodeAnalysis.VisualBasic.Binder:this
         -15 (-1.31% of base) : 68721.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFactory:ConstDirectiveTrivia(Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.SyntaxToken,Microsoft.CodeAnalysis.VisualBasic.Syntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.ConstDirectiveTriviaSyntax
         -14 (-2.60% of base) : 15900.dasm - System.SpanHelpers:LastIndexOfAny(byref,int,int,int,int):int
         -13 (-0.09% of base) : 1929.dasm - Microsoft.FSharp.Quotations.FSharpExpr:GetLayout(bool):Microsoft.FSharp.Text.StructuredPrintfImpl.Layout:this
         -12 (-0.37% of base) : 147613.dasm - System.Xml.Serialization.XmlSerializationWriterILGen:WriteElement(System.Xml.Serialization.SourceInfo,System.Xml.Serialization.ElementAccessor,System.String,bool):this

Top method regressions (percentages):
           5 ( 0.28% of base) : 160669.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this

Top method improvements (percentages):
          -3 (-33.33% of base) : 16232.dasm - System.ValueTuple:Create(short):System.ValueTuple`1[Int16]
          -3 (-33.33% of base) : 2741.dasm - dictRefType@165[Int16][System.Int16]:Invoke(short):StructBox`1[Int16]:this
          -3 (-30.00% of base) : 105069.dasm - Microsoft.VisualBasic.FileSystem:TAB():Microsoft.VisualBasic.TabInfo
          -3 (-25.00% of base) : 15228.dasm - System.Int16:System.INumber<System.Int16>.CreateTruncating(double):short
          -3 (-23.08% of base) : 205666.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -3 (-23.08% of base) : 205669.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -3 (-20.00% of base) : 16489.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarAdd(short,short):short
          -3 (-20.00% of base) : 16490.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarSubtract(short,short):short
          -3 (-18.75% of base) : 16491.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarMultiply(short,short):short
          -3 (-18.75% of base) : 16492.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarDivide(short,short):short
          -3 (-18.75% of base) : 228094.dasm - System.Media.SoundPlayer:BytesToInt16(ubyte,ubyte):short
          -3 (-16.67% of base) : 128832.dasm - System.Xml.XmlBufferReader:ReadInt16():int:this
          -3 (-15.79% of base) : 105071.dasm - Microsoft.VisualBasic.FileSystem:SPC(short):Microsoft.VisualBasic.SpcInfo
          -3 (-15.00% of base) : 206106.dasm - System.Net.Quic.Implementations.MsQuic.Internal.MsQuicAddressHelpers:SetPort(int,byref,int)
          -1 (-14.29% of base) : 161552.dasm - FastSerialization.SegmentedMemoryStreamReader:get_Length():long:this
          -1 (-14.29% of base) : 161581.dasm - FastSerialization.MemoryStreamReader:get_Length():long:this
          -1 (-14.29% of base) : 208829.dasm - System.IO.ChunkedMemoryStream:get_Length():long:this
          -1 (-14.29% of base) : 124704.dasm - System.Net.Http.HttpClient:get_MaxResponseContentBufferSize():long:this
          -1 (-14.29% of base) : 124861.dasm - LimitArrayPoolWriteStream:get_Length():long:this
          -1 (-14.29% of base) : 151180.dasm - System.Reflection.Internal.ReadOnlyUnmanagedMemoryStream:get_Length():long:this

2707 total methods with Code Size differences (2706 improved, 1 regressed), 6 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3197744
Total bytes of diff: 3192386
Total bytes of delta: -5358 (-0.17% of base)
Total relative delta: -29.24
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -117 : 141821.dasm (-0.46% of base)
        -117 : 141827.dasm (-0.46% of base)
         -36 : 143089.dasm (-0.04% of base)
         -30 : 148533.dasm (-0.39% of base)
         -30 : 148572.dasm (-0.39% of base)
         -30 : 148575.dasm (-0.39% of base)
         -30 : 148536.dasm (-0.39% of base)
         -28 : 251808.dasm (-0.19% of base)
         -24 : 148501.dasm (-0.97% of base)
         -21 : 246393.dasm (-0.89% of base)
         -21 : 148551.dasm (-0.44% of base)
         -21 : 148556.dasm (-0.44% of base)
         -21 : 17993.dasm (-0.18% of base)
         -21 : 206810.dasm (-0.12% of base)
         -21 : 148558.dasm (-0.44% of base)
         -21 : 148549.dasm (-0.44% of base)
         -21 : 68653.dasm (-0.33% of base)
         -18 : 349157.dasm (-0.94% of base)
         -18 : 118492.dasm (-0.64% of base)
         -18 : 148517.dasm (-0.43% of base)

1669 total files with Code Size differences (1669 improved, 0 regressed), 11 unchanged.

Top method improvements (bytes):
        -117 (-0.46% of base) : 141821.dasm - System.CodeDom.Compiler.Tests.VBCodeGenerationTests:ProviderSupports():this
        -117 (-0.46% of base) : 141827.dasm - System.CodeDom.Compiler.Tests.CSharpCodeGenerationTests:ProviderSupports():this
         -36 (-0.04% of base) : 143089.dasm - <ValidateIdentifiers_Valid_TestData>d__0:MoveNext():bool:this
         -30 (-0.39% of base) : 148533.dasm - System.ComponentModel.Tests.TypeDescriptorTests:RemoveProviderTransparent_InvokeObject_RemovesProvider():this
         -30 (-0.39% of base) : 148572.dasm - System.ComponentModel.Tests.TypeDescriptorTests:RemoveProvider_InvokeObject_RemovesProvider():this
         -30 (-0.39% of base) : 148575.dasm - System.ComponentModel.Tests.TypeDescriptorTests:RemoveProvider_InvokeType_RemovesProvider():this
         -30 (-0.39% of base) : 148536.dasm - System.ComponentModel.Tests.TypeDescriptorTests:RemoveProviderTransparent_InvokeType_RemovesProvider():this
         -28 (-0.19% of base) : 251808.dasm - Parser:GetLogClasses(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.CSharp.Syntax.ClassDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=4.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):System.Collections.Generic.IReadOnlyList`1[[Microsoft.Extensions.Logging.Generators.LoggerMessageGenerator+LoggerClass, Microsoft.Extensions.Logging.Generators, Version=42.42.42.42, Culture=neutral, PublicKeyToken=adb9793829ddae60]]:this
         -24 (-0.97% of base) : 148501.dasm - System.ComponentModel.Tests.TypeDescriptionProviderTests:CreateInstance_InvokeWithParent_ReturnsExpected(System.IServiceProvider,System.Type,System.Type[],System.Object[],System.Object):this
         -21 (-0.89% of base) : 246393.dasm - Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.Patterns.PatternBuilder:Build(System.String):Microsoft.DotNet.ProjectModel.FileSystemGlobbing.Internal.IPattern:this
         -21 (-0.44% of base) : 148551.dasm - System.ComponentModel.Tests.TypeDescriptorTests:AddProvider_InvokeTypeMultipleTimes_Refreshes():this
         -21 (-0.44% of base) : 148556.dasm - System.ComponentModel.Tests.TypeDescriptorTests:AddProviderTransparent_InvokeObjectMultipleTimes_Refreshes():this
         -21 (-0.18% of base) : 17993.dasm - <IdentifyConflictsAsync>d__19:MoveNext():this
         -21 (-0.12% of base) : 206810.dasm - <>c__DisplayClass28_0:<Read_FullItem_ReturnsExpected>b__0(System.ServiceModel.Syndication.SyndicationFeed):this
         -21 (-0.44% of base) : 148558.dasm - System.ComponentModel.Tests.TypeDescriptorTests:AddProviderTransparent_InvokeTypeMultipleTimes_Refreshes():this
         -21 (-0.44% of base) : 148549.dasm - System.ComponentModel.Tests.TypeDescriptorTests:AddProvider_InvokeObjectMultipleTimes_Refreshes():this
         -21 (-0.33% of base) : 68653.dasm - System.Tests.AttributeGetCustomAttributes:RunPosTests()
         -18 (-0.94% of base) : 349157.dasm - System.Xml.Tests.CArgAddParam:AddParam14(int,int,int,int):this
         -18 (-0.64% of base) : 118492.dasm - Microsoft.Build.BackEnd.ItemGroupIntrinsicTask:ExecuteTask(Microsoft.Build.BackEnd.Lookup):this
         -18 (-0.43% of base) : 148517.dasm - System.ComponentModel.Tests.TypeDescriptionProviderTests:GetFullComponentName_InvokeWithCustomTypeDescriptor_ReturnsExpected(System.Object,System.String):this

Top method improvements (percentages):
          -3 (-33.33% of base) : 114000.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(short):Microsoft.Build.Shared.NGen`1[Int16]
          -3 (-33.33% of base) : 120032.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(short):Microsoft.Build.Shared.NGen`1[Int16]
          -3 (-33.33% of base) : 265645.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -3 (-33.33% of base) : 267839.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -3 (-33.33% of base) : 270859.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -3 (-33.33% of base) : 272644.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -3 (-33.33% of base) : 19222.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -3 (-27.27% of base) : 320327.dasm - System.Tests.UnaryNegationOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_UnaryNegation(short):short
          -3 (-27.27% of base) : 125528.dasm - <>c:<GenerateNonEnumValueExpression>b__3_5(short):short:this
          -3 (-27.27% of base) : 30610.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001b.cnst001b.MyStruct:op_Division(short,ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001b.cnst001b.MyStruct):short
          -3 (-25.00% of base) : 320091.dasm - System.Tests.BinaryIntegerHelper`1[Int16][System.Int16]:PopCount(short):short
          -3 (-25.00% of base) : 320219.dasm - System.Tests.NumberHelper`1[Int16][System.Int16]:CreateTruncating(double):short
          -3 (-23.08% of base) : 301971.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -3 (-23.08% of base) : 302006.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -3 (-23.08% of base) : 302265.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -3 (-23.08% of base) : 320310.dasm - System.Tests.ShiftOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_LeftShift(short,int):short
          -3 (-23.08% of base) : 320311.dasm - System.Tests.ShiftOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_RightShift(short,int):short
          -3 (-23.08% of base) : 302300.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -3 (-20.00% of base) : 310891.dasm - <>c:<SumInt16>b__803_1(short,short):short:this
          -3 (-20.00% of base) : 50778.dasm - System.Linq.Expressions.Tests.LiftedAddNullableTests:AddNullableShort(short,short):short

1669 total methods with Code Size differences (1669 improved, 0 regressed), 11 unchanged.

```

</details>

--------------------------------------------------------------------------------

