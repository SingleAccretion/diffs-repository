## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 58481
Total bytes of diff: 58281
Total bytes of delta: -200 (-0.34% of base)
Total relative delta: -1.01
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           3 : 12197.dasm (0.35% of base)

Top file improvements (bytes):
         -33 : 12196.dasm (-13.15% of base)
         -14 : 12677.dasm (-3.52% of base)
         -12 : 12678.dasm (-0.87% of base)
          -6 : 1073.dasm (-2.36% of base)
          -6 : 4038.dasm (-1.72% of base)
          -6 : 5877.dasm (-0.21% of base)
          -6 : 5965.dasm (-0.29% of base)
          -6 : 5579.dasm (-0.12% of base)
          -4 : 16122.dasm (-0.92% of base)
          -4 : 5968.dasm (-0.25% of base)
          -4 : 5475.dasm (-0.10% of base)
          -4 : 5977.dasm (-0.13% of base)
          -4 : 5607.dasm (-0.13% of base)
          -4 : 9312.dasm (-5.63% of base)
          -4 : 20722.dasm (-0.12% of base)
          -2 : 22804.dasm (-0.16% of base)
          -2 : 5044.dasm (-6.45% of base)
          -2 : 5596.dasm (-0.15% of base)
          -2 : 6842.dasm (-0.28% of base)
          -2 : 8220.dasm (-0.14% of base)

59 total files with Code Size differences (58 improved, 1 regressed), 1 unchanged.

Top method regressions (bytes):
           3 ( 0.35% of base) : 12197.dasm - AssignJagged:first_assignments(System.Int32[][],System.Int16[][]):int

Top method improvements (bytes):
         -33 (-13.15% of base) : 12196.dasm - AssignJagged:calc_minimum_costs(System.Int32[][])
         -14 (-3.52% of base) : 12677.dasm - AssignRect:calc_minimum_costs(System.Int32[,])
         -12 (-0.87% of base) : 12678.dasm - AssignRect:first_assignments(System.Int32[,],System.Int16[,]):int
          -6 (-2.36% of base) : 1073.dasm - System.DateTimeOffset:ValidateOffset(System.TimeSpan):short
          -6 (-1.72% of base) : 4038.dasm - BlockingConfig:.cctor()
          -6 (-0.21% of base) : 5877.dasm - <ReceiveBlobAsync>d__174`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
          -6 (-0.29% of base) : 5965.dasm - <ReadLineAsyncInternal>d__63:MoveNext():this
          -6 (-0.12% of base) : 5579.dasm - <SendWithVersionDetectionAndRetryAsync>d__83:MoveNext():this
          -4 (-0.92% of base) : 16122.dasm - Microsoft.CodeAnalysis.RuntimeMembers.MemberDescriptor:InitializeFromStream(System.IO.Stream,System.String[]):System.Collections.Immutable.ImmutableArray`1[MemberDescriptor]
          -4 (-0.25% of base) : 5968.dasm - <ReadBufferAsync>d__71:MoveNext():this
          -4 (-0.10% of base) : 5475.dasm - <SendAsync>d__4:MoveNext():this
          -4 (-0.13% of base) : 5977.dasm - <ReadAsyncInternal>d__186`1[AsyncReadWriteAdapter][System.Net.Security.AsyncReadWriteAdapter]:MoveNext():this
          -4 (-0.13% of base) : 5607.dasm - <ConnectAsync>d__96:MoveNext():this
          -4 (-5.63% of base) : 9312.dasm - Sigil.Impl.ExtensionMethods:IsTailableCall(System.Reflection.Emit.OpCode):bool
          -4 (-0.12% of base) : 20722.dasm - <ReadAsyncSlowPath>d__39:MoveNext():this
          -2 (-0.16% of base) : 22804.dasm - DynamicClass:ReadDateTimeOffsetFromXml(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.XmlObjectSerializerReadContext,System.Xml.XmlDictionaryString[],System.Xml.XmlDictionaryString[]):System.Object
          -2 (-6.45% of base) : 5044.dasm - OverlappedValueTaskSource:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-0.15% of base) : 5596.dasm - <AddHttp11ConnectionAsync>d__73:MoveNext():this
          -2 (-0.28% of base) : 6842.dasm - <ReadFromStreamAsync>d__67:MoveNext():this
          -2 (-0.14% of base) : 8220.dasm - DynamicClass:ReadDateTimeOffsetFromJson(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.Json.XmlObjectSerializerReadContextComplexJson,System.Xml.XmlDictionaryString,System.Xml.XmlDictionaryString[]):System.Object

Top method regressions (percentages):
           3 ( 0.35% of base) : 12197.dasm - AssignJagged:first_assignments(System.Int32[][],System.Int16[][]):int

Top method improvements (percentages):
         -33 (-13.15% of base) : 12196.dasm - AssignJagged:calc_minimum_costs(System.Int32[][])
          -2 (-6.45% of base) : 5044.dasm - OverlappedValueTaskSource:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-6.45% of base) : 4888.dasm - PipeValueTaskSource:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-6.45% of base) : 10196.dasm - ResettableValueTaskSource:System.Threading.Tasks.Sources.IValueTaskSource.OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-6.45% of base) : 10076.dasm - StateMachineBox[VoidTaskResult][System.Threading.Tasks.VoidTaskResult]:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-6.45% of base) : 8722.dasm - ThreadPoolValueTaskSource:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -2 (-5.88% of base) : 5650.dasm - MultiConnectSocketAsyncEventArgs:OnCompleted(System.Action`1[[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Object,short,int):this
          -4 (-5.63% of base) : 9312.dasm - Sigil.Impl.ExtensionMethods:IsTailableCall(System.Reflection.Emit.OpCode):bool
          -2 (-5.56% of base) : 7620.dasm - MessagePack.Decoders.FixInt16:Read(System.Byte[],int,byref):short:this
          -2 (-3.92% of base) : 4103.dasm - System.Threading.PortableThreadPool:get_MinThreadsGoal():short:this
         -14 (-3.52% of base) : 12677.dasm - AssignRect:calc_minimum_costs(System.Int32[,])
          -2 (-2.53% of base) : 9943.dasm - System.ConsolePal:ConsoleColorToColorAttribute(int,bool):short
          -2 (-2.50% of base) : 16218.dasm - Microsoft.CodeAnalysis.RuntimeMembers.SignatureComparer`5[__Canon,__Canon,__Canon,__Canon,__Canon][System.__Canon,System.__Canon,System.__Canon,System.__Canon,System.__Canon]:ReadTypeId(System.Collections.Immutable.ImmutableArray`1[Byte],byref):short
          -6 (-2.36% of base) : 1073.dasm - System.DateTimeOffset:ValidateOffset(System.TimeSpan):short
          -2 (-1.85% of base) : 12194.dasm - AssignJagged:CopyToAssign(System.Int32[][],System.Int32[][])
          -2 (-1.82% of base) : 9338.dasm - Sigil.Impl.ExtensionMethods:IsPrefix(System.Reflection.Emit.OpCode):bool
          -6 (-1.72% of base) : 4038.dasm - BlockingConfig:.cctor()
          -2 (-1.53% of base) : 12675.dasm - AssignRect:CopyToAssign(System.Int32[,],System.Int32[,])
          -2 (-1.48% of base) : 9410.dasm - <>c:<IsConstant>b__37_0(System.Tuple`5[[System.Reflection.Emit.OpCode, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Nullable`1[[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Nullable`1[[System.Int64, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Nullable`1[[System.Double, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Reflection.FieldInfo, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):bool:this
          -2 (-1.48% of base) : 4094.dasm - System.Threading.PortableThreadPool:ShouldAdjustMaxWorkersActive(int):bool:this

59 total methods with Code Size differences (58 improved, 1 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 897852
Total bytes of diff: 888888
Total bytes of delta: -8964 (-1.00% of base)
Total relative delta: -126.49
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           3 : 177787.dasm (0.35% of base)

Top file improvements (bytes):
        -514 : 218940.dasm (-10.88% of base)
         -33 : 177786.dasm (-13.15% of base)
         -30 : 232696.dasm (-1.42% of base)
         -16 : 207146.dasm (-11.76% of base)
         -14 : 197490.dasm (-0.59% of base)
         -14 : 149986.dasm (-3.30% of base)
         -14 : 177796.dasm (-3.52% of base)
         -14 : 85734.dasm (-7.14% of base)
         -14 : 171287.dasm (-0.59% of base)
         -14 : 171337.dasm (-0.47% of base)
         -12 : 149527.dasm (-1.11% of base)
         -12 : 197526.dasm (-0.52% of base)
         -12 : 177797.dasm (-0.87% of base)
         -12 : 85745.dasm (-6.22% of base)
         -10 : 151917.dasm (-1.06% of base)
         -10 : 149255.dasm (-1.06% of base)
         -10 : 223548.dasm (-4.15% of base)
         -10 : 150133.dasm (-0.88% of base)
          -9 : 147252.dasm (-1.08% of base)
          -8 : 146376.dasm (-2.42% of base)

3654 total files with Code Size differences (3653 improved, 1 regressed), 1 unchanged.

Top method regressions (bytes):
           3 ( 0.35% of base) : 177787.dasm - AssignJagged:first_assignments(System.Int32[][],System.Int16[][]):int

Top method improvements (bytes):
        -514 (-10.88% of base) : 218940.dasm - ldarg_s_i2:test_int16(short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short):int
         -33 (-13.15% of base) : 177786.dasm - AssignJagged:calc_minimum_costs(System.Int32[][])
         -30 (-1.42% of base) : 232696.dasm - ILGEN_0x537f7b0:Method_0x323f83b5(double,byte,int,short,ubyte,double,short,ushort,double,int,int,int,ushort,int,int):float
         -16 (-11.76% of base) : 207146.dasm - GitHub_22815.Program:test128(short):bool
         -14 (-0.59% of base) : 197490.dasm - testout1:Func_0_1_1():int
         -14 (-3.30% of base) : 149986.dasm - testout1:Func_0_5_2_4_3():short
         -14 (-3.52% of base) : 177796.dasm - AssignRect:calc_minimum_costs(System.Int32[,])
         -14 (-7.14% of base) : 85734.dasm - TestCase.Test:compare(short,short):short
         -14 (-0.59% of base) : 171287.dasm - testout1:Func_0_1_1():int
         -14 (-0.47% of base) : 171337.dasm - testout1:Func_0_2_4_3():long
         -12 (-1.11% of base) : 149527.dasm - testout1:Func_0_2_3_6_6():double
         -12 (-0.52% of base) : 197526.dasm - testout1:Func_0_2_4_3():long
         -12 (-0.87% of base) : 177797.dasm - AssignRect:first_assignments(System.Int32[,],System.Int16[,]):int
         -12 (-6.22% of base) : 85745.dasm - TestCase.Test:compare(short,short):int
         -10 (-1.06% of base) : 151917.dasm - testout1:Func_0_1_1_5_4():double
         -10 (-1.06% of base) : 149255.dasm - testout1:Func_0_1_1_5_4():double
         -10 (-4.15% of base) : 223548.dasm - OVFTest:Test_short(short):short
         -10 (-0.88% of base) : 150133.dasm - testout1:Func_0_5_6_4_3():ushort
          -9 (-1.08% of base) : 147252.dasm - testout1:Func_0_5_1_6_3():short
          -8 (-2.42% of base) : 146376.dasm - testout1:Func_0_1_1_5():double

Top method regressions (percentages):
           3 ( 0.35% of base) : 177787.dasm - AssignJagged:first_assignments(System.Int32[][],System.Int16[][]):int

Top method improvements (percentages):
          -2 (-28.57% of base) : 233278.dasm - Wrapper`1[Int16][System.Int16]:op_Implicit(short):Wrapper`1[Int16]
          -2 (-28.57% of base) : 8933.dasm - JIT.HardwareIntrinsics.Arm.Helpers:ZeroExtendWidening(byte):short
          -2 (-22.22% of base) : 8175.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Negate(short):short
          -2 (-22.22% of base) : 9088.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Not(short):short
          -2 (-20.00% of base) : 81069.dasm - ldarg_n:I2_2(short,short,short,short):short
          -2 (-20.00% of base) : 81070.dasm - ldarg_n:I2_3(short,short,short,short):short
          -2 (-16.67% of base) : 8908.dasm - JIT.HardwareIntrinsics.Arm.Helpers:AddWidening(short,byte):short
          -2 (-16.67% of base) : 8278.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Add(short,short):short
          -2 (-16.67% of base) : 8290.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Subtract(short,short):short
          -2 (-16.67% of base) : 9089.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Or(short,short):short
          -2 (-16.67% of base) : 9091.dasm - JIT.HardwareIntrinsics.Arm.Helpers:Xor(short,short):short
          -2 (-16.67% of base) : 8929.dasm - JIT.HardwareIntrinsics.Arm.Helpers:SubtractWidening(byte,byte):short
          -2 (-16.67% of base) : 8930.dasm - JIT.HardwareIntrinsics.Arm.Helpers:SubtractWidening(short,byte):short
          -2 (-16.67% of base) : 8963.dasm - JIT.HardwareIntrinsics.Arm.Helpers:AddWidening(byte,byte):short
          -2 (-16.67% of base) : 9085.dasm - JIT.HardwareIntrinsics.Arm.Helpers:And(short,short):short
          -2 (-15.38% of base) : 88151.dasm - Program:Test_ldind_u1_conv_ovf_i2(byref,byref)
          -2 (-15.38% of base) : 88154.dasm - Program:Test_ldind_u1_conv_ovf_i2_un(byref,byref)
          -2 (-15.38% of base) : 88205.dasm - Program:Test_ldind_u1_conv_i2(byref,byref)
          -2 (-15.38% of base) : 88253.dasm - Program:Test_ldind_i1_conv_i2(byref,byref)
          -2 (-15.38% of base) : 88255.dasm - Program:Test_ldind_i1_conv_ovf_i2(byref,byref)

3654 total methods with Code Size differences (3653 improved, 1 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 165498
Total bytes of diff: 164411
Total bytes of delta: -1087 (-0.66% of base)
Total relative delta: -21.76
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -30 : 57907.dasm (-24.79% of base)
         -14 : 185603.dasm (-1.41% of base)
         -12 : 27655.dasm (-2.80% of base)
         -11 : 158693.dasm (-0.91% of base)
         -10 : 168160.dasm (-0.69% of base)
         -10 : 210838.dasm (-1.98% of base)
          -8 : 203182.dasm (-0.58% of base)
          -8 : 54405.dasm (-0.17% of base)
          -8 : 114305.dasm (-2.69% of base)
          -8 : 185622.dasm (-0.54% of base)
          -8 : 155810.dasm (-3.56% of base)
          -8 : 203073.dasm (-10.13% of base)
          -8 : 28921.dasm (-2.05% of base)
          -6 : 167572.dasm (-0.63% of base)
          -6 : 167725.dasm (-0.28% of base)
          -6 : 203592.dasm (-0.27% of base)
          -6 : 2427.dasm (-0.04% of base)
          -6 : 167705.dasm (-0.22% of base)
          -6 : 167715.dasm (-0.28% of base)
          -6 : 57818.dasm (-16.67% of base)

429 total files with Code Size differences (429 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -30 (-24.79% of base) : 57907.dasm - System.Runtime.Intrinsics.Vector256:Create(short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short):System.Runtime.Intrinsics.Vector256`1[System.Int16]
         -14 (-1.41% of base) : 185603.dasm - System.ConsolePal:SetWindowSize(int,int)
         -12 (-2.80% of base) : 27655.dasm - Microsoft.Diagnostics.Tracing.EventPipeEventSource:FromStream(FastSerialization.Deserializer):this
         -11 (-0.91% of base) : 158693.dasm - System.Data.OleDb.OleDbDataReader:CreateBindingsFromMetaData(bool):System.Data.OleDb.Bindings[]:this
         -10 (-0.69% of base) : 168160.dasm - Microsoft.VisualBasic.CompilerServices.Conversions:ToShort(System.Object):short
         -10 (-1.98% of base) : 210838.dasm - System.Net.FtpControlStream:GetLastModifiedFrom213Response(System.String):System.DateTime:this
          -8 (-0.58% of base) : 203182.dasm - System.Data.Odbc.OdbcParameter:Bind(System.Data.Odbc.OdbcStatementHandle,System.Data.Odbc.OdbcCommand,short,System.Data.Odbc.CNativeBuffer,bool):this
          -8 (-0.17% of base) : 54405.dasm - <WriteToUnderlyingStreamAsync>d__60:MoveNext():this
          -8 (-2.69% of base) : 114305.dasm - System.Xml.Xsl.IlGen.GenerateHelper:TestAndBranch(int,System.Reflection.Emit.Label,System.Reflection.Emit.OpCode):this
          -8 (-0.54% of base) : 185622.dasm - System.ConsolePal:MoveBufferArea(int,int,int,int,int,int,ushort,int,int)
          -8 (-3.56% of base) : 155810.dasm - Newtonsoft.Json.Linq.JToken:op_Explicit(Newtonsoft.Json.Linq.JToken):short
          -8 (-10.13% of base) : 203073.dasm - System.Data.Odbc.OdbcStatementHandle:BindParameter(short,short,short,short,int,int,System.Runtime.InteropServices.HandleRef,int,System.Runtime.InteropServices.HandleRef):short:this
          -8 (-2.05% of base) : 28921.dasm - System.Drawing.Printing.PrinterSettings:GetHdevnames():int:this
          -6 (-0.63% of base) : 167572.dasm - Microsoft.VisualBasic.CompilerServices.ShortType:FromObject(System.Object):short
          -6 (-0.28% of base) : 167725.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AndObject(System.Object,System.Object):System.Object
          -6 (-0.27% of base) : 203592.dasm - System.Data.Odbc.OdbcCommand:ExecuteReaderObject(int,System.String,bool,System.Object[],ushort):System.Data.Odbc.OdbcDataReader:this
          -6 (-0.04% of base) : 2427.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
          -6 (-0.22% of base) : 167705.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
          -6 (-0.28% of base) : 167715.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
          -6 (-16.67% of base) : 57818.dasm - System.Runtime.Intrinsics.Vector64:Create(short,short,short,short):System.Runtime.Intrinsics.Vector64`1[System.Int16]

Top method improvements (percentages):
          -2 (-25.00% of base) : 67180.dasm - System.Int16:System.IIncrementOperators<System.Int16>.op_Increment(short):short
          -2 (-25.00% of base) : 67184.dasm - System.Int16:System.IDecrementOperators<System.Int16>.op_Decrement(short):short
         -30 (-24.79% of base) : 57907.dasm - System.Runtime.Intrinsics.Vector256:Create(short,short,short,short,short,short,short,short,short,short,short,short,short,short,short,short):System.Runtime.Intrinsics.Vector256`1[System.Int16]
          -2 (-22.22% of base) : 60308.dasm - ThreadCounts:get_NumThreadsGoal():short:this
          -2 (-22.22% of base) : 60315.dasm - ThreadCounts:get_NumProcessingWork():short:this
          -2 (-22.22% of base) : 67151.dasm - System.Int16:System.IUnaryNegationOperators<System.Int16,System.Int16>.op_UnaryNegation(short):short
          -2 (-22.22% of base) : 60275.dasm - CountsOfThreadsProcessingUserCallbacks:get_HighWatermark():short:this
          -2 (-22.22% of base) : 166797.dasm - Microsoft.VisualBasic.FileSystem:TAB():Microsoft.VisualBasic.TabInfo
          -2 (-22.22% of base) : 67189.dasm - System.Int16:System.IBitwiseOperators<System.Int16,System.Int16,System.Int16>.op_OnesComplement(short):short
          -2 (-20.00% of base) : 86290.dasm - Microsoft.CodeAnalysis.VisualBasic.CompileTimeCalculations:UncheckedCShort(long):short
          -2 (-20.00% of base) : 156653.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToInt16(System.Object):short:this
          -2 (-20.00% of base) : 86291.dasm - Microsoft.CodeAnalysis.VisualBasic.CompileTimeCalculations:UncheckedCShort(long):short
          -2 (-20.00% of base) : 110203.dasm - System.Xml.XmlBufferReader:ReadInt16():int:this
          -2 (-20.00% of base) : 63672.dasm - System.Version:get_MajorRevision():short:this
          -2 (-20.00% of base) : 155603.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToInt16(System.IFormatProvider):short:this
          -2 (-20.00% of base) : 68815.dasm - System.BitConverter:ToHalf(System.Byte[],int):System.Half
          -2 (-18.18% of base) : 67156.dasm - System.Int16:System.IShiftOperators<System.Int16,System.Int16>.op_RightShift(short,int):short
          -2 (-18.18% of base) : 67198.dasm - System.Int16:System.IBinaryInteger<System.Int16>.PopCount(short):short
          -2 (-18.18% of base) : 210337.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -2 (-18.18% of base) : 210340.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short

429 total methods with Code Size differences (429 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 251973
Total bytes of diff: 251065
Total bytes of delta: -908 (-0.36% of base)
Total relative delta: -12.21
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -18 : 15622.dasm (-2.97% of base)
         -15 : 200873.dasm (-6.07% of base)
         -13 : 15639.dasm (-2.35% of base)
         -10 : 183045.dasm (-0.87% of base)
          -8 : 15633.dasm (-2.08% of base)
          -6 : 12168.dasm (-2.09% of base)
          -6 : 127199.dasm (-0.14% of base)
          -6 : 200874.dasm (-2.86% of base)
          -6 : 130890.dasm (-2.33% of base)
          -6 : 120545.dasm (-1.22% of base)
          -6 : 127422.dasm (-0.12% of base)
          -6 : 184403.dasm (-7.79% of base)
          -4 : 156164.dasm (-0.26% of base)
          -4 : 157782.dasm (-6.78% of base)
          -4 : 174837.dasm (-1.97% of base)
          -4 : 174838.dasm (-2.82% of base)
          -4 : 183065.dasm (-0.24% of base)
          -4 : 223762.dasm (-1.12% of base)
          -4 : 226933.dasm (-0.38% of base)
          -4 : 103593.dasm (-0.40% of base)

383 total files with Code Size differences (383 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
         -18 (-2.97% of base) : 15622.dasm - System.SpanHelpers:IndexOfAny(byref,short,short,short,int):int
         -15 (-6.07% of base) : 200873.dasm - System.Buffers.SequenceReader`1[Int16][System.Int16]:AdvancePastAny(short,short,short,short):long:this
         -13 (-2.35% of base) : 15639.dasm - System.SpanHelpers:LastIndexOfAny(byref,short,short,short,int):int
         -10 (-0.87% of base) : 183045.dasm - System.ConsolePal:SetWindowSize(int,int)
          -8 (-2.08% of base) : 15633.dasm - System.SpanHelpers:LastIndexOfAny(byref,short,short,int):int
          -6 (-2.09% of base) : 12168.dasm - OperatorIntrinsics:loop@5442-14(short,short,Microsoft.FSharp.Core.FSharpFunc`2[[System.Int16, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.FSharp.Core.FSharpFunc`2[[System.Int16, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int16, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]], FSharp.Core, Version=5.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],int):short
          -6 (-0.14% of base) : 127199.dasm - <ProcessServerStreamAsync>d__41:MoveNext():this
          -6 (-2.86% of base) : 200874.dasm - System.Buffers.SequenceReader`1[Int16][System.Int16]:AdvancePastAny(short,short,short):long:this
          -6 (-2.33% of base) : 130890.dasm - System.Runtime.Serialization.DateTimeOffsetAdapter:GetDateTimeOffsetAdapter(System.DateTimeOffset):System.Runtime.Serialization.DateTimeOffsetAdapter
          -6 (-1.22% of base) : 120545.dasm - System.Drawing.Printing.PrinterSettings:GetHdevnames():int:this
          -6 (-0.12% of base) : 127422.dasm - <SendWithVersionDetectionAndRetryAsync>d__83:MoveNext():this
          -6 (-7.79% of base) : 184403.dasm - System.Data.Odbc.OdbcStatementHandle:BindParameter(short,short,short,short,int,int,System.Runtime.InteropServices.HandleRef,int,System.Runtime.InteropServices.HandleRef):short:this
          -4 (-0.26% of base) : 156164.dasm - <DisposePendingDisposablesOnExceptionAsync>d__21:MoveNext():this
          -4 (-6.78% of base) : 157782.dasm - System.Text.Json.Serialization.Converters.Int16Converter:WriteNumberWithCustomHandling(System.Text.Json.Utf8JsonWriter,short,int):this
          -4 (-1.97% of base) : 174837.dasm - Node[Int16][System.Int16]:Insert(int,short):Node[Int16]:this
          -4 (-2.82% of base) : 174838.dasm - Node[Int16][System.Int16]:ReplaceAt(int,short):Node[Int16]:this
          -4 (-0.24% of base) : 183065.dasm - System.ConsolePal:MoveBufferArea(int,int,int,int,int,int,ushort,int,int)
          -4 (-1.12% of base) : 223762.dasm - System.Threading.Tasks.Dataflow.DataflowBlock:Receive(System.Threading.Tasks.Dataflow.ISourceBlock`1[Int16],System.TimeSpan,System.Threading.CancellationToken):short
          -4 (-0.38% of base) : 226933.dasm - System.Media.SoundPlayer:ValidateSoundData(System.Byte[])
          -4 (-0.40% of base) : 103593.dasm - Microsoft.VisualBasic.CompilerServices.ShortType:FromObject(System.Object):short

Top method improvements (percentages):
          -2 (-28.57% of base) : 2662.dasm - dictRefType@165[Int16][System.Int16]:Invoke(short):StructBox`1[Int16]:this
          -2 (-28.57% of base) : 15962.dasm - System.ValueTuple:Create(short):System.ValueTuple`1[Int16]
          -2 (-22.22% of base) : 129803.dasm - System.Xml.XmlBufferReader:ReadInt16():int:this
          -2 (-22.22% of base) : 104311.dasm - Microsoft.VisualBasic.FileSystem:TAB():Microsoft.VisualBasic.TabInfo
          -2 (-20.00% of base) : 75903.dasm - Microsoft.CodeAnalysis.ArrayElement`1[Int16][System.Int16]:op_Implicit(Microsoft.CodeAnalysis.ArrayElement`1[Int16]):short
          -2 (-20.00% of base) : 67562.dasm - Microsoft.CodeAnalysis.VisualBasic.CompileTimeCalculations:UncheckedCShort(long):short
          -2 (-20.00% of base) : 67563.dasm - Microsoft.CodeAnalysis.VisualBasic.CompileTimeCalculations:UncheckedCShort(long):short
          -2 (-20.00% of base) : 2671.dasm - dictRefType@165-1[Int16][System.Int16]:Invoke(StructBox`1[Int16]):short:this
          -2 (-18.18% of base) : 204544.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -2 (-18.18% of base) : 204547.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -2 (-18.18% of base) : 104855.dasm - Newtonsoft.Json.JsonConvert:DeserializeAnonymousType(System.String,short):short
          -4 (-16.67% of base) : 205018.dasm - System.Net.Quic.Implementations.MsQuic.Internal.MsQuicAddressHelpers:SetPort(int,byref,int)
          -2 (-15.38% of base) : 14980.dasm - System.Int16:System.INumber<System.Int16>.CreateTruncating(long):short
          -2 (-15.38% of base) : 179715.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValue():short:this
          -2 (-15.38% of base) : 179729.dasm - System.ComponentModel.Composition.Hosting.ExportProvider:GetExportedValueOrDefault():short:this
          -2 (-13.33% of base) : 226934.dasm - System.Media.SoundPlayer:BytesToInt16(ubyte,ubyte):short
          -2 (-12.50% of base) : 104313.dasm - Microsoft.VisualBasic.FileSystem:SPC(short):Microsoft.VisualBasic.SpcInfo
          -2 (-12.50% of base) : 174332.dasm - System.Collections.Immutable.ImmutableList`1[Int16][System.Int16]:System.Collections.Immutable.IImmutableList<T>.Insert(int,short):System.Collections.Immutable.IImmutableList`1[Int16]:this
          -2 (-12.50% of base) : 16225.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarAdd(short,short):short
          -2 (-12.50% of base) : 16226.dasm - System.Numerics.Vector`1[Int16][System.Int16]:ScalarSubtract(short,short):short

383 total methods with Code Size differences (383 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 322924
Total bytes of diff: 321838
Total bytes of delta: -1086 (-0.34% of base)
Total relative delta: -18.66
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -14 : 333509.dasm (-1.33% of base)
         -14 : 17780.dasm (-0.15% of base)
         -10 : 49801.dasm (-0.54% of base)
         -10 : 50038.dasm (-0.53% of base)
         -10 : 50074.dasm (-0.54% of base)
          -8 : 281225.dasm (-1.59% of base)
          -8 : 281253.dasm (-0.22% of base)
          -6 : 97058.dasm (-1.29% of base)
          -6 : 49837.dasm (-0.25% of base)
          -6 : 16235.dasm (-0.31% of base)
          -6 : 10240.dasm (-1.00% of base)
          -6 : 318867.dasm (-0.20% of base)
          -6 : 50002.dasm (-0.25% of base)
          -6 : 16264.dasm (-0.38% of base)
          -6 : 228250.dasm (-2.76% of base)
          -6 : 228264.dasm (-2.76% of base)
          -4 : 14436.dasm (-0.22% of base)
          -4 : 15926.dasm (-0.21% of base)
          -4 : 16233.dasm (-0.25% of base)
          -4 : 183830.dasm (-0.28% of base)

456 total files with Code Size differences (456 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -14 (-1.33% of base) : 333509.dasm - System.Threading.Tasks.Tests.ValueTaskTests:NonGeneric_Equals_Object():this
         -14 (-0.15% of base) : 17780.dasm - <IdentifyConflictsAsync>d__19:MoveNext():this
         -10 (-0.54% of base) : 49801.dasm - System.Linq.Expressions.Tests.LambdaAddTests:VerifyAddShort(short,short,bool)
         -10 (-0.53% of base) : 50038.dasm - System.Linq.Expressions.Tests.LambdaMultiplyTests:VerifyMultiplyShort(short,short,bool)
         -10 (-0.54% of base) : 50074.dasm - System.Linq.Expressions.Tests.LambdaSubtractTests:VerifySubtractShort(short,short,bool)
          -8 (-1.59% of base) : 281225.dasm - System.Drawing.Primitives.Tests.ColorTests:GetHashCodeForUnknownNamed():this
          -8 (-0.22% of base) : 281253.dasm - System.Drawing.Primitives.Tests.ColorTests:Equality(System.Drawing.Color,System.Drawing.Color,bool):this
          -6 (-1.29% of base) : 97058.dasm - System.Text.Json.Serialization.Tests.NumberHandlingTests:PerformAsRootTypeSerialization(short,System.String,System.String)
          -6 (-0.25% of base) : 49837.dasm - System.Linq.Expressions.Tests.LambdaDivideTests:VerifyDivideShort(short,short,bool)
          -6 (-0.31% of base) : 16235.dasm - <FindReferencesInDocumentWorkerAsync>d__7:MoveNext():this
          -6 (-1.00% of base) : 10240.dasm - Microsoft.CodeAnalysis.Differencing.EditScript`1[Int16][System.Int16]:ProcessNode(System.Collections.Generic.List`1[Edit`1],short):this
          -6 (-0.20% of base) : 318867.dasm - System.Tests.Int16Tests_GenericMath:ParseValidStringTest(System.String,int,System.IFormatProvider,short)
          -6 (-0.25% of base) : 50002.dasm - System.Linq.Expressions.Tests.LambdaModuloTests:VerifyModuloShort(short,short,bool)
          -6 (-0.38% of base) : 16264.dasm - <FindNonAliasReferencesAsync>d__6:MoveNext():this
          -6 (-2.76% of base) : 228250.dasm - ImTools.ImMapSlots:RefAddOrUpdateSlot(byref,int,short)
          -6 (-2.76% of base) : 228264.dasm - ImTools.ImMapSlots:RefAddOrKeepSlot(byref,int,short)
          -4 (-0.22% of base) : 14436.dasm - <GetStorageWorkerAsync>d__14:MoveNext():this
          -4 (-0.21% of base) : 15926.dasm - <FindLinkedSymbolsAsync>d__10:MoveNext():this
          -4 (-0.25% of base) : 16233.dasm - <FindAllReferencesInDocumentAsync>d__6:MoveNext():this
          -4 (-0.28% of base) : 183830.dasm - <FillBufferAsync>d__24:MoveNext():this

Top method improvements (percentages):
          -2 (-28.57% of base) : 119268.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(short):Microsoft.Build.Shared.NGen`1[Int16]
          -2 (-28.57% of base) : 113244.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(short):Microsoft.Build.Shared.NGen`1[Int16]
          -2 (-28.57% of base) : 19005.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -2 (-28.57% of base) : 264269.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -2 (-28.57% of base) : 266463.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -2 (-28.57% of base) : 269453.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -2 (-28.57% of base) : 271237.dasm - System.Collections.Tests.ValueComparable:Create(short):System.Collections.Tests.ValueComparable`1[Int16]
          -2 (-22.22% of base) : 318857.dasm - System.Tests.UnaryNegationOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_UnaryNegation(short):short
          -2 (-22.22% of base) : 124749.dasm - <>c:<GenerateNonEnumValueExpression>b__3_5(short):short:this
          -2 (-20.00% of base) : 318750.dasm - System.Tests.NumberHelper`1[Int16][System.Int16]:CreateTruncating(long):short
          -2 (-20.00% of base) : 119267.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(Microsoft.Build.Shared.NGen`1[Int16]):short
          -2 (-20.00% of base) : 113243.dasm - Microsoft.Build.Shared.NGen`1[Int16][System.Int16]:op_Implicit(Microsoft.Build.Shared.NGen`1[Int16]):short
          -2 (-20.00% of base) : 30341.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001b.cnst001b.MyStruct:op_Division(short,ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001b.cnst001b.MyStruct):short
          -2 (-18.18% of base) : 318840.dasm - System.Tests.ShiftOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_LeftShift(short,int):short
          -2 (-18.18% of base) : 300557.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -2 (-18.18% of base) : 300560.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -2 (-18.18% of base) : 300851.dasm - System.Net.IPAddress:HostToNetworkOrder(short):short
          -2 (-18.18% of base) : 318841.dasm - System.Tests.ShiftOperatorsHelper`2[Int16,Int16][System.Int16,System.Int16]:op_RightShift(short,int):short
          -2 (-18.18% of base) : 300854.dasm - System.Net.IPAddress:NetworkToHostOrder(short):short
          -2 (-18.18% of base) : 318621.dasm - System.Tests.BinaryIntegerHelper`1[Int16][System.Int16]:PopCount(short):short

456 total methods with Code Size differences (456 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

