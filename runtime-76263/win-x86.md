Diffs are based on <span style="color:#1460aa">1,283,630</span> contexts (<span style="color:#1460aa">254,266</span> MinOpts, <span style="color:#1460aa">1,029,364</span> FullOpts).


<details>
<summary>Overall (<span style="color:green">-528,910</span> bytes)</summary>

|Collection|Base size (bytes)|Diff size (bytes)|
|---|--:|--:|
|benchmarks.run.windows.x86.checked.mch|9,071,535|<span style="color:green">-34,926</span>|
|coreclr_tests.run.windows.x86.checked.mch|258,624,728|<span style="color:green">-172,613</span>|
|libraries.crossgen2.windows.x86.checked.mch|28,496,243|<span style="color:green">-74,005</span>|
|libraries.pmi.windows.x86.checked.mch|42,153,850|<span style="color:green">-82,890</span>|
|libraries_tests.pmi.windows.x86.checked.mch|86,700,603|<span style="color:green">-164,476</span>|


</details>

<details>
<summary>FullOpts (<span style="color:green">-528,910</span> bytes)</summary>

|Collection|Base size (bytes)|Diff size (bytes)|
|---|--:|--:|
|benchmarks.run.windows.x86.checked.mch|8,502,431|<span style="color:green">-34,926</span>|
|coreclr_tests.run.windows.x86.checked.mch|78,410,028|<span style="color:green">-172,613</span>|
|libraries.crossgen2.windows.x86.checked.mch|28,495,153|<span style="color:green">-74,005</span>|
|libraries.pmi.windows.x86.checked.mch|41,184,200|<span style="color:green">-82,890</span>|
|libraries_tests.pmi.windows.x86.checked.mch|82,991,964|<span style="color:green">-164,476</span>|


</details>

<details>
<summary>Details</summary>

|Collection|Diffed contexts|MinOpts|FullOpts|Contexts with diffs|Missed, base|Missed, diff|
|---|--:|--:|--:|--:|--:|--:|
|benchmarks.run.windows.x86.checked.mch|34,270|5,731|28,539|566|0|0|
|coreclr_tests.run.windows.x86.checked.mch|421,304|234,439|186,865|3,299|0|0|
|libraries.crossgen2.windows.x86.checked.mch|230,735|16|230,719|3,372|0|0|
|libraries.pmi.windows.x86.checked.mch|264,497|4,880|259,617|4,072|0|0|
|libraries_tests.pmi.windows.x86.checked.mch|332,824|9,200|323,624|5,959|0|0|

---

#### jit-analyze output

<details>

<summary>benchmarks.run.windows.x86.checked.mch</summary>

To reproduce these diffs on Windows x86:
```
superpmi.py asmdiffs -target_os windows -target_arch x86 -arch x86
```

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9071535 (overridden on cmd)
Total bytes of diff: 9036609 (overridden on cmd)
Total bytes of delta: -34926 (-0.39 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         110 : 12507.dasm (10.02% of base)
           8 : 7446.dasm (0.70% of base)
           6 : 7072.dasm (0.55% of base)
           3 : 14338.dasm (0.47% of base)
           1 : 10763.dasm (0.18% of base)
           1 : 7396.dasm (0.64% of base)

Top file improvements (bytes):
       -3859 : 14001.dasm (-10.69% of base)
       -3091 : 8429.dasm (-8.59% of base)
       -1647 : 6799.dasm (-26.22% of base)
       -1098 : 26774.dasm (-12.60% of base)
        -899 : 14933.dasm (-7.16% of base)
        -804 : 12323.dasm (-6.59% of base)
        -776 : 8606.dasm (-8.28% of base)
        -772 : 14931.dasm (-6.18% of base)
        -757 : 14938.dasm (-6.47% of base)
        -751 : 27909.dasm (-6.25% of base)
        -749 : 12327.dasm (-6.67% of base)
        -748 : 28801.dasm (-6.58% of base)
        -746 : 3107.dasm (-6.10% of base)
        -734 : 12326.dasm (-6.51% of base)
        -687 : 14015.dasm (-5.87% of base)
        -660 : 10025.dasm (-4.88% of base)
        -658 : 32590.dasm (-7.87% of base)
        -489 : 8607.dasm (-5.29% of base)
        -489 : 14016.dasm (-5.29% of base)
        -340 : 16062.dasm (-25.62% of base)

562 total files with Code Size differences (556 improved, 6 regressed), 4 unchanged.

Top method regressions (bytes):
         110 (10.02% of base) : 12507.dasm - System.Threading.TimerQueue:FireNextTimers():this
           8 ( 0.70% of base) : 7446.dasm - System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong]:CreateAlternate(System.Text.RegularExpressions.Symbolic.SymbolicRegexBuilder`1[ulong],System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong],System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong],bool,bool):System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong]
           6 ( 0.55% of base) : 7072.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           3 ( 0.47% of base) : 14338.dasm - System.IO.Tests.Perf_RandomAccess:WriteGather(long,int,int):this
           1 ( 0.64% of base) : 7396.dasm - System.Text.RegularExpressions.Symbolic.UInt64Solver:ConvertFromBDD(System.Text.RegularExpressions.Symbolic.BDD,System.Text.RegularExpressions.Symbolic.CharSetSolver):ulong:this
           1 ( 0.18% of base) : 10763.dasm - System.Xml.Schema.XsdDateTime:PrintTime(byref):this

Top method improvements (bytes):
       -3859 (-10.69% of base) : 14001.dasm - <unnamed>:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.IndexViewModel,int)
       -3091 (-8.59% of base) : 8429.dasm - <unnamed>:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.MyEventsListerItem,int)
       -1647 (-26.22% of base) : 6799.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1098 (-12.60% of base) : 26774.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldNeverOverflowBinaryOperators(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -899 (-7.16% of base) : 14933.dasm - Utf8Json.Formatters.ISO8601DateTimeOffsetFormatter:Serialize(byref,System.DateTimeOffset,Utf8Json.IJsonFormatterResolver):this
        -804 (-6.59% of base) : 12323.dasm - Utf8Json.Formatters.ISO8601DateTimeFormatter:Serialize(byref,System.DateTime,Utf8Json.IJsonFormatterResolver):this
        -776 (-8.28% of base) : 8606.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffset(System.IO.TextReader,ushort[]):System.DateTimeOffset
        -772 (-6.18% of base) : 14931.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_ActiveOrUpcomingEventFormatter2:Serialize(byref,MicroBenchmarks.Serializers.ActiveOrUpcomingEvent,Utf8Json.IJsonFormatterResolver):this
        -757 (-6.47% of base) : 14938.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_CampaignSummaryViewModelFormatter3:Serialize(byref,MicroBenchmarks.Serializers.CampaignSummaryViewModel,Utf8Json.IJsonFormatterResolver):this
        -751 (-6.25% of base) : 27909.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_MyEventsListerItemFormatter2:Serialize(byref,MicroBenchmarks.Serializers.MyEventsListerItem,Utf8Json.IJsonFormatterResolver):this
        -749 (-6.67% of base) : 12327.dasm - Utf8Json.JsonWriter:WriteInt64(long):this
        -748 (-6.58% of base) : 28801.dasm - Jil.Deserialize.Methods:_ReadISO8601DateThunkReader(byref,ushort[]):System.DateTime
        -746 (-6.10% of base) : 3107.dasm - Utf8Json.Formatters.MicroBenchmarks_Serializers_LocationFormatter1:Serialize(byref,MicroBenchmarks.Serializers.Location,Utf8Json.IJsonFormatterResolver):this
        -734 (-6.51% of base) : 12326.dasm - Utf8Json.Internal.NumberConverter:WriteInt64(byref,int,long):int
        -687 (-5.87% of base) : 14015.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffsetThunkReader(byref,ushort[]):System.DateTimeOffset
        -660 (-4.88% of base) : 10025.dasm - <unnamed>:_DynamicMethod0(System.IO.TextWriter,MicroBenchmarks.Serializers.CollectionsOfPrimitives,int)
        -658 (-7.87% of base) : 32590.dasm - Jil.Deserialize.Methods:_ReadISO8601Date(System.IO.TextReader,ushort[]):System.DateTime
        -489 (-5.29% of base) : 8607.dasm - Jil.Deserialize.Methods:ParseISO8601Date(System.IO.TextReader,ushort[],int,int):System.DateTime
        -489 (-5.29% of base) : 14016.dasm - Jil.Deserialize.Methods:ParseISO8601DateThunkReader(byref,ushort[],int,int):System.DateTime
        -340 (-25.62% of base) : 16062.dasm - DecCalc:VarDecMul(byref,byref)

Top method regressions (percentages):
         110 (10.02% of base) : 12507.dasm - System.Threading.TimerQueue:FireNextTimers():this
           8 ( 0.70% of base) : 7446.dasm - System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong]:CreateAlternate(System.Text.RegularExpressions.Symbolic.SymbolicRegexBuilder`1[ulong],System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong],System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong],bool,bool):System.Text.RegularExpressions.Symbolic.SymbolicRegexNode`1[ulong]
           1 ( 0.64% of base) : 7396.dasm - System.Text.RegularExpressions.Symbolic.UInt64Solver:ConvertFromBDD(System.Text.RegularExpressions.Symbolic.BDD,System.Text.RegularExpressions.Symbolic.CharSetSolver):ulong:this
           6 ( 0.55% of base) : 7072.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           3 ( 0.47% of base) : 14338.dasm - System.IO.Tests.Perf_RandomAccess:WriteGather(long,int,int):this
           1 ( 0.18% of base) : 10763.dasm - System.Xml.Schema.XsdDateTime:PrintTime(byref):this

Top method improvements (percentages):
         -14 (-43.75% of base) : 4571.dasm - System.IO.Strategies.OSFileStreamStrategy:get_Length():long:this
         -14 (-40.00% of base) : 28947.dasm - System.Threading.Tests.Perf_Interlocked:Exchange_long():long:this
         -10 (-38.46% of base) : 5883.dasm - ThreadPoolValueTaskSource:System.Threading.Tasks.Sources.IValueTaskSource<System.Int32>.GetResult(short):int:this
         -14 (-34.15% of base) : 16190.dasm - System.Threading.Tests.Perf_Interlocked:Add_long():long:this
         -14 (-34.15% of base) : 15165.dasm - System.Threading.Tests.Perf_Interlocked:Decrement_long():long:this
         -14 (-34.15% of base) : 14605.dasm - System.Threading.Tests.Perf_Interlocked:Increment_long():long:this
         -12 (-33.33% of base) : 14168.dasm - System.Tests.Perf_Random:Next_long():long:this
         -12 (-33.33% of base) : 14588.dasm - System.Tests.Perf_Random:Next_long_unseeded():long:this
         -19 (-32.76% of base) : 8437.dasm - System.TimeSpan:get_Hours():int:this
         -19 (-32.76% of base) : 8438.dasm - System.TimeSpan:get_Minutes():int:this
         -56 (-32.18% of base) : 7018.dasm - System.Math:<BigMul>g__SoftwareFallback|48_0(ulong,ulong,byref):ulong
         -57 (-31.84% of base) : 29076.dasm - System.Numerics.BigIntegerCalculator:PowCore(ulong,uint,uint,ulong):uint
         -12 (-30.00% of base) : 29749.dasm - System.Threading.Tests.Perf_Interlocked:CompareExchange_long():long:this
         -12 (-29.27% of base) : 7400.dasm - <>c__DisplayClass43_0[ulong]:<Create>b__0(System.Text.RegularExpressions.Symbolic.SymbolicRegexBuilder`1[ulong],System.Text.RegularExpressions.Symbolic.BDD):ulong:this
         -12 (-29.27% of base) : 25406.dasm - System.IO.FileStream:Seek(long,int):long:this
         -12 (-29.27% of base) : 11019.dasm - System.IO.Tests.Perf_FileStream:Read_NoBuffering(long,int,int):long:this
         -12 (-29.27% of base) : 11873.dasm - System.Runtime.Intrinsics.Scalar`1[long]:Divide(long,long):long
         -12 (-29.27% of base) : 3863.dasm - System.Runtime.Intrinsics.Scalar`1[long]:Multiply(long,long):long
         -12 (-29.27% of base) : 29318.dasm - System.Runtime.Intrinsics.Scalar`1[ulong]:Divide(ulong,ulong):ulong
         -12 (-29.27% of base) : 30352.dasm - System.Runtime.Intrinsics.Scalar`1[ulong]:Multiply(ulong,ulong):ulong

562 total methods with Code Size differences (556 improved, 6 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------


</details>

<details>

<summary>coreclr_tests.run.windows.x86.checked.mch</summary>

To reproduce these diffs on Windows x86:
```
superpmi.py asmdiffs -target_os windows -target_arch x86 -arch x86
```

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 258624728 (overridden on cmd)
Total bytes of diff: 258452115 (overridden on cmd)
Total bytes of delta: -172613 (-0.07 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         115 : 86453.dasm (5.86% of base)
         115 : 86581.dasm (5.86% of base)
         115 : 86588.dasm (5.86% of base)
         115 : 86595.dasm (5.86% of base)
         115 : 86439.dasm (5.86% of base)
         115 : 86446.dasm (5.86% of base)
         115 : 309043.dasm (5.86% of base)
         115 : 309050.dasm (5.86% of base)
         115 : 309057.dasm (5.86% of base)
         115 : 309175.dasm (5.86% of base)
         115 : 309182.dasm (5.86% of base)
         115 : 309189.dasm (5.86% of base)
         110 : 262250.dasm (9.95% of base)
          96 : 81818.dasm (5.14% of base)
          96 : 81928.dasm (5.14% of base)
          96 : 308200.dasm (5.14% of base)
          96 : 308283.dasm (5.14% of base)
          66 : 295619.dasm (3.73% of base)
          44 : 86450.dasm (1.87% of base)
          44 : 86458.dasm (1.87% of base)

Top file improvements (bytes):
       -7068 : 372655.dasm (-5.89% of base)
       -7068 : 372173.dasm (-5.89% of base)
       -7054 : 372659.dasm (-5.57% of base)
       -7054 : 372178.dasm (-5.57% of base)
       -6702 : 373029.dasm (-25.67% of base)
       -4738 : 338134.dasm (-29.10% of base)
       -4179 : 369337.dasm (-5.54% of base)
       -4174 : 374859.dasm (-5.54% of base)
       -2261 : 372168.dasm (-2.11% of base)
       -2183 : 372163.dasm (-2.23% of base)
       -2043 : 372651.dasm (-1.79% of base)
       -1856 : 372319.dasm (-1.81% of base)
       -1856 : 372332.dasm (-1.81% of base)
       -1856 : 376035.dasm (-1.81% of base)
       -1856 : 376036.dasm (-1.81% of base)
       -1647 : 190177.dasm (-26.22% of base)
       -1647 : 266274.dasm (-26.22% of base)
       -1108 : 374416.dasm (-65.99% of base)
       -1104 : 273237.dasm (-14.14% of base)
        -958 : 336765.dasm (-35.88% of base)

3275 total files with Code Size differences (3230 improved, 45 regressed), 24 unchanged.

Top method regressions (bytes):
         115 ( 5.86% of base) : 86439.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309043.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86446.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309050.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86453.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309057.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86581.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309175.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86588.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309182.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86595.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309189.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt643:RunBasicScenario(int,bool):this
         110 ( 9.95% of base) : 262250.dasm - System.Threading.TimerQueue:FireNextTimers():this
          96 ( 5.14% of base) : 81818.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtInt64:ValidateResult(long[],long[],System.String):this
          96 ( 5.14% of base) : 308200.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtInt64:ValidateResult(long[],long[],System.String):this
          96 ( 5.14% of base) : 81928.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtUInt64:ValidateResult(ulong[],ulong[],System.String):this
          96 ( 5.14% of base) : 308283.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtUInt64:ValidateResult(ulong[],ulong[],System.String):this
          66 ( 3.73% of base) : 295619.dasm - testout1:Func_0_4_4():ushort
          44 ( 1.87% of base) : 86443.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunReflectionScenario(int,bool):this
          44 ( 1.87% of base) : 309047.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunReflectionScenario(int,bool):this

Top method improvements (bytes):
       -7068 (-5.89% of base) : 372173.dasm - i8div:TestEntryPoint():int
       -7068 (-5.89% of base) : 372655.dasm - u8div:TestEntryPoint():int
       -7054 (-5.57% of base) : 372178.dasm - i8rem:TestEntryPoint():int
       -7054 (-5.57% of base) : 372659.dasm - u8rem:TestEntryPoint():int
       -6702 (-25.67% of base) : 373029.dasm - LongMulOn32BitTest:Main():int
       -4738 (-29.10% of base) : 338134.dasm - DevDiv_545504:test(int):long
       -4179 (-5.54% of base) : 369337.dasm - Test_1000w1d.testout1:Func_0():int
       -4174 (-5.54% of base) : 374859.dasm - Test_1000w1d.testout1:Func_0():int
       -2261 (-2.11% of base) : 372168.dasm - i4rem:TestEntryPoint():int
       -2183 (-2.23% of base) : 372163.dasm - i4div:TestEntryPoint():int
       -2043 (-1.79% of base) : 372651.dasm - u4rem:TestEntryPoint():int
       -1856 (-1.81% of base) : 372319.dasm - overlddiv:TestEntryPoint():int
       -1856 (-1.81% of base) : 376035.dasm - overlddiv:TestEntryPoint():int
       -1856 (-1.81% of base) : 372332.dasm - overldrem:TestEntryPoint():int
       -1856 (-1.81% of base) : 376036.dasm - overldrem:TestEntryPoint():int
       -1647 (-26.22% of base) : 190177.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1647 (-26.22% of base) : 266274.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1108 (-65.99% of base) : 374416.dasm - JitTest_ldobj_I8_ldobj_il.Test:Main():int
       -1104 (-14.14% of base) : 273237.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldNeverOverflowBinaryOperators(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -958 (-35.88% of base) : 336765.dasm - _sub:main(System.String[]):int

Top method regressions (percentages):
         110 ( 9.95% of base) : 262250.dasm - System.Threading.TimerQueue:FireNextTimers():this
         115 ( 5.86% of base) : 86439.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309043.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86446.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309050.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86453.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309057.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86581.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309175.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt640:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86588.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309182.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt641:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 86595.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt643:RunBasicScenario(int,bool):this
         115 ( 5.86% of base) : 309189.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementUInt643:RunBasicScenario(int,bool):this
          96 ( 5.14% of base) : 81818.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtInt64:ValidateResult(long[],long[],System.String):this
          96 ( 5.14% of base) : 308200.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtInt64:ValidateResult(long[],long[],System.String):this
          96 ( 5.14% of base) : 81928.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtUInt64:ValidateResult(ulong[],ulong[],System.String):this
          96 ( 5.14% of base) : 308283.dasm - JIT.HardwareIntrinsics.General.VectorUnaryOpTest__SqrtUInt64:ValidateResult(ulong[],ulong[],System.String):this
          66 ( 3.73% of base) : 295619.dasm - testout1:Func_0_4_4():ushort
          30 ( 2.15% of base) : 8843.dasm - System.Variant:MarshalHelperConvertObjectToVariant(System.Object,byref)
          44 ( 1.87% of base) : 86443.dasm - JIT.HardwareIntrinsics.General.VectorGetAndWithElement__GetAndWithElementInt640:RunReflectionScenario(int,bool):this

Top method improvements (percentages):
       -1108 (-65.99% of base) : 374416.dasm - JitTest_ldobj_I8_ldobj_il.Test:Main():int
         -14 (-51.85% of base) : 207387.dasm - System.Reflection.Metadata.BlobReader:ReadUInt64():ulong:this
         -12 (-46.15% of base) : 373042.dasm - LongMulOn32BitTest:LongMul_13(int,int):long
         -12 (-46.15% of base) : 373043.dasm - LongMulOn32BitTest:LongMul_14(int,int):long
         -12 (-46.15% of base) : 373051.dasm - LongMulOn32BitTest:LongMul_22(int):long
         -12 (-46.15% of base) : 373052.dasm - LongMulOn32BitTest:LongMul_23(int):long
         -12 (-46.15% of base) : 373053.dasm - LongMulOn32BitTest:LongMul_24(int):long
         -12 (-46.15% of base) : 373066.dasm - LongMulOn32BitTest:LongMul_37(int):long
         -12 (-46.15% of base) : 373067.dasm - LongMulOn32BitTest:LongMul_38(int):long
         -12 (-46.15% of base) : 373068.dasm - LongMulOn32BitTest:LongMul_39(int):long
         -12 (-46.15% of base) : 373081.dasm - LongMulOn32BitTest:LongMul_52(int):long
         -12 (-46.15% of base) : 373082.dasm - LongMulOn32BitTest:LongMul_53(int):long
         -12 (-46.15% of base) : 373083.dasm - LongMulOn32BitTest:LongMul_54(int):long
         -12 (-46.15% of base) : 373087.dasm - LongMulOn32BitTest:LongMul_58(int,int):long
         -12 (-46.15% of base) : 373089.dasm - LongMulOn32BitTest:LongMul_60(int,int):long
         -12 (-46.15% of base) : 373036.dasm - LongMulOn32BitTest:LongMul_7(int):long
         -12 (-46.15% of base) : 373037.dasm - LongMulOn32BitTest:LongMul_8(int):long
         -12 (-46.15% of base) : 373038.dasm - LongMulOn32BitTest:LongMul_9(int):long
         -14 (-43.75% of base) : 207200.dasm - System.IO.Strategies.OSFileStreamStrategy:get_Length():long:this
         -22 (-42.31% of base) : 214304.dasm - System.Diagnostics.Stopwatch:get_ElapsedMilliseconds():long:this

3275 total methods with Code Size differences (3230 improved, 45 regressed), 24 unchanged.

```

</details>

--------------------------------------------------------------------------------


</details>

<details>

<summary>libraries.crossgen2.windows.x86.checked.mch</summary>

To reproduce these diffs on Windows x86:
```
superpmi.py asmdiffs -target_os windows -target_arch x86 -arch x86
```

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 28496243 (overridden on cmd)
Total bytes of diff: 28422238 (overridden on cmd)
Total bytes of delta: -74005 (-0.26 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          77 : 22486.dasm (7.72% of base)
          48 : 38903.dasm (2.49% of base)
          30 : 14234.dasm (2.21% of base)
          29 : 133797.dasm (4.87% of base)
          10 : 16851.dasm (0.96% of base)
           9 : 148179.dasm (0.87% of base)
           9 : 16844.dasm (0.57% of base)
           9 : 189210.dasm (0.87% of base)
           5 : 230475.dasm (0.62% of base)
           3 : 149974.dasm (0.40% of base)
           3 : 132999.dasm (0.74% of base)
           2 : 39543.dasm (0.56% of base)
           2 : 39545.dasm (0.56% of base)
           1 : 151462.dasm (0.50% of base)
           1 : 192150.dasm (0.10% of base)
           1 : 4705.dasm (0.04% of base)
           1 : 151636.dasm (0.48% of base)
           1 : 151947.dasm (0.60% of base)

Top file improvements (bytes):
       -1647 : 156643.dasm (-26.08% of base)
       -1098 : 68767.dasm (-17.06% of base)
        -694 : 67089.dasm (-22.47% of base)
        -568 : 38774.dasm (-3.81% of base)
        -371 : 66938.dasm (-13.08% of base)
        -364 : 67037.dasm (-13.81% of base)
        -335 : 13022.dasm (-25.21% of base)
        -324 : 156582.dasm (-20.74% of base)
        -295 : 67027.dasm (-14.71% of base)
        -289 : 213134.dasm (-6.14% of base)
        -274 : 67080.dasm (-6.29% of base)
        -274 : 114713.dasm (-5.39% of base)
        -259 : 192121.dasm (-22.86% of base)
        -236 : 68759.dasm (-18.67% of base)
        -236 : 21262.dasm (-14.43% of base)
        -228 : 67047.dasm (-7.25% of base)
        -224 : 67057.dasm (-7.65% of base)
        -221 : 99003.dasm (-18.70% of base)
        -215 : 67017.dasm (-10.42% of base)
        -211 : 123310.dasm (-10.69% of base)

3364 total files with Code Size differences (3346 improved, 18 regressed), 8 unchanged.

Top method regressions (bytes):
          77 ( 7.72% of base) : 22486.dasm - System.Threading.TimerQueue:FireNextTimers():this
          48 ( 2.49% of base) : 38903.dasm - System.Data.SqlTypes.SqlDecimal:op_Multiply(System.Data.SqlTypes.SqlDecimal,System.Data.SqlTypes.SqlDecimal):System.Data.SqlTypes.SqlDecimal
          30 ( 2.21% of base) : 14234.dasm - System.Variant:MarshalHelperConvertObjectToVariant(System.Object,byref)
          29 ( 4.87% of base) : 133797.dasm - System.Text.Json.JsonDocument:ReadToEnd(System.IO.Stream):System.ArraySegment`1[ubyte]
          10 ( 0.96% of base) : 16851.dasm - System.Number:TryNumberToDecimal(byref,byref):bool
           9 ( 0.87% of base) : 148179.dasm - System.IPv4AddressHelper:ParseNonCanonical(uint,int,byref,bool):long
           9 ( 0.87% of base) : 189210.dasm - System.IPv4AddressHelper:ParseNonCanonical(uint,int,byref,bool):long
           9 ( 0.57% of base) : 16844.dasm - System.Number:TryParseUInt64IntegerStyle(System.ReadOnlySpan`1[ushort],int,System.Globalization.NumberFormatInfo,byref):int
           5 ( 0.62% of base) : 230475.dasm - FastSerialization.IOStreamStreamReader:Fill(int):this
           3 ( 0.40% of base) : 149974.dasm - System.Numerics.BigInteger:GreatestCommonDivisor(System.ReadOnlySpan`1[uint],System.ReadOnlySpan`1[uint]):System.Numerics.BigInteger
           3 ( 0.74% of base) : 132999.dasm - System.Text.ISO2022Encoding:GetMaxByteCount(int):int:this
           2 ( 0.56% of base) : 39543.dasm - System.Data.SqlTypes.SqlXmlStreamWrapper:Read(ubyte[],int,int):int:this
           2 ( 0.56% of base) : 39545.dasm - System.Data.SqlTypes.SqlXmlStreamWrapper:Write(ubyte[],int,int):this
           1 ( 0.04% of base) : 4705.dasm - Microsoft.Cci.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[int],System.Collections.Immutable.ImmutableArray`1[int],int,int,int,int,bool,bool,bool):this
           1 ( 0.10% of base) : 192150.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           1 ( 0.50% of base) : 151462.dasm - System.Text.RegularExpressions.RegexInterpreter:Scan(System.ReadOnlySpan`1[ushort]):this
           1 ( 0.48% of base) : 151636.dasm - System.Text.RegularExpressions.RegexRunner:InternalScan(System.Text.RegularExpressions.Regex,int,int):System.Text.RegularExpressions.Match:this
           1 ( 0.60% of base) : 151947.dasm - System.Text.RegularExpressions.Symbolic.UInt64Solver:ConvertFromBDD(System.Text.RegularExpressions.Symbolic.BDD,System.Text.RegularExpressions.Symbolic.CharSetSolver):ulong:this

Top method improvements (bytes):
       -1647 (-26.08% of base) : 156643.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1098 (-17.06% of base) : 68767.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldNeverOverflowBinaryOperators(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -694 (-22.47% of base) : 67089.dasm - Microsoft.VisualBasic.CompilerServices.Operators:IntDivideObject(System.Object,System.Object):System.Object
        -568 (-3.81% of base) : 38774.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,int[]):System.Object:this
        -371 (-13.08% of base) : 66938.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:IDivObj(System.Object,System.Object):System.Object
        -364 (-13.81% of base) : 67037.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
        -335 (-25.21% of base) : 13022.dasm - DecCalc:VarDecMul(byref,byref)
        -324 (-20.74% of base) : 156582.dasm - System.Reflection.PortableExecutable.CorHeader:.ctor(byref):this
        -295 (-14.71% of base) : 67027.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
        -289 (-6.14% of base) : 213134.dasm - ILCompiler.PettisHansenSort.PettisHansen:Sort(System.Collections.Generic.List`1[ILCompiler.PettisHansenSort.CallGraphNode]):System.Collections.Generic.List`1[System.Collections.Generic.List`1[int]]
        -274 (-5.39% of base) : 114713.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
        -274 (-6.29% of base) : 67080.dasm - Microsoft.VisualBasic.CompilerServices.Operators:ModObject(System.Object,System.Object):System.Object
        -259 (-22.86% of base) : 192121.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeIso(Newtonsoft.Json.Utilities.StringReference,int,byref):bool
        -236 (-18.67% of base) : 68759.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldUncheckedIntegralBinaryOperator(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -236 (-14.43% of base) : 21262.dasm - System.Globalization.TimeSpanFormat:FormatCustomized(System.TimeSpan,System.ReadOnlySpan`1[ushort],System.Globalization.DateTimeFormatInfo,byref)
        -228 (-7.25% of base) : 67047.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AddObject(System.Object,System.Object):System.Object
        -224 (-7.65% of base) : 67057.dasm - Microsoft.VisualBasic.CompilerServices.Operators:SubtractObject(System.Object,System.Object):System.Object
        -221 (-18.70% of base) : 99003.dasm - System.Xml.Schema.XsdDateTime:op_Implicit(System.Xml.Schema.XsdDateTime):System.DateTime
        -215 (-10.42% of base) : 67017.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AndObject(System.Object,System.Object):System.Object
        -211 (-10.69% of base) : 123310.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:FoldIntegralCharOrDateTimeBinaryOperator(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,byref,byref):Microsoft.CodeAnalysis.ConstantValue

Top method regressions (percentages):
          77 ( 7.72% of base) : 22486.dasm - System.Threading.TimerQueue:FireNextTimers():this
          29 ( 4.87% of base) : 133797.dasm - System.Text.Json.JsonDocument:ReadToEnd(System.IO.Stream):System.ArraySegment`1[ubyte]
          48 ( 2.49% of base) : 38903.dasm - System.Data.SqlTypes.SqlDecimal:op_Multiply(System.Data.SqlTypes.SqlDecimal,System.Data.SqlTypes.SqlDecimal):System.Data.SqlTypes.SqlDecimal
          30 ( 2.21% of base) : 14234.dasm - System.Variant:MarshalHelperConvertObjectToVariant(System.Object,byref)
          10 ( 0.96% of base) : 16851.dasm - System.Number:TryNumberToDecimal(byref,byref):bool
           9 ( 0.87% of base) : 148179.dasm - System.IPv4AddressHelper:ParseNonCanonical(uint,int,byref,bool):long
           9 ( 0.87% of base) : 189210.dasm - System.IPv4AddressHelper:ParseNonCanonical(uint,int,byref,bool):long
           3 ( 0.74% of base) : 132999.dasm - System.Text.ISO2022Encoding:GetMaxByteCount(int):int:this
           5 ( 0.62% of base) : 230475.dasm - FastSerialization.IOStreamStreamReader:Fill(int):this
           1 ( 0.60% of base) : 151947.dasm - System.Text.RegularExpressions.Symbolic.UInt64Solver:ConvertFromBDD(System.Text.RegularExpressions.Symbolic.BDD,System.Text.RegularExpressions.Symbolic.CharSetSolver):ulong:this
           9 ( 0.57% of base) : 16844.dasm - System.Number:TryParseUInt64IntegerStyle(System.ReadOnlySpan`1[ushort],int,System.Globalization.NumberFormatInfo,byref):int
           2 ( 0.56% of base) : 39545.dasm - System.Data.SqlTypes.SqlXmlStreamWrapper:Write(ubyte[],int,int):this
           2 ( 0.56% of base) : 39543.dasm - System.Data.SqlTypes.SqlXmlStreamWrapper:Read(ubyte[],int,int):int:this
           1 ( 0.50% of base) : 151462.dasm - System.Text.RegularExpressions.RegexInterpreter:Scan(System.ReadOnlySpan`1[ushort]):this
           1 ( 0.48% of base) : 151636.dasm - System.Text.RegularExpressions.RegexRunner:InternalScan(System.Text.RegularExpressions.Regex,int,int):System.Text.RegularExpressions.Match:this
           3 ( 0.40% of base) : 149974.dasm - System.Numerics.BigInteger:GreatestCommonDivisor(System.ReadOnlySpan`1[uint],System.ReadOnlySpan`1[uint]):System.Numerics.BigInteger
           1 ( 0.10% of base) : 192150.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           1 ( 0.04% of base) : 4705.dasm - Microsoft.Cci.MetadataSizes:.ctor(System.Collections.Immutable.ImmutableArray`1[int],System.Collections.Immutable.ImmutableArray`1[int],int,int,int,int,bool,bool,bool):this

Top method improvements (percentages):
         -14 (-56.00% of base) : 13004.dasm - DecCalc:UInt32x32To64(uint,uint):ulong
         -14 (-56.00% of base) : 13303.dasm - System.Math:BigMul(int,int):long
         -14 (-51.85% of base) : 230449.dasm - FastSerialization.MemoryStreamReader:<.ctor>b__1_1():long:this
         -14 (-51.85% of base) : 230415.dasm - FastSerialization.SegmentedMemoryStreamReader:<.ctor>b__2_1():long:this
         -14 (-51.85% of base) : 42840.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceLoadedModule:get_ModuleID():long:this
         -14 (-51.85% of base) : 42367.dasm - Microsoft.Diagnostics.Tracing.TraceEvent:GetAddressAt(int):ulong:this
         -14 (-51.85% of base) : 42532.dasm - Microsoft.Diagnostics.Tracing.Utilities.FastStream:ReadULong():ulong:this
         -14 (-51.85% of base) : 193478.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToInt64(System.IFormatProvider):long:this
         -14 (-51.85% of base) : 193479.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToUInt64(System.IFormatProvider):ulong:this
         -14 (-51.85% of base) : 192482.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToInt64(System.Object):long:this
         -14 (-51.85% of base) : 192488.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToUInt64(System.Object):ulong:this
         -14 (-51.85% of base) : 14327.dasm - System.AppDomain:get_MonitoringSurvivedMemorySize():long:this
         -14 (-51.85% of base) : 14458.dasm - System.BitConverter:ToUInt64(ubyte[],int):ulong
         -14 (-51.85% of base) : 30157.dasm - System.Diagnostics.Stopwatch:get_ElapsedTicks():long:this
         -14 (-51.85% of base) : 216856.dasm - System.Linq.Enumerable:Max(System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 216865.dasm - System.Linq.Enumerable:Min(System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 216876.dasm - System.Linq.Enumerable:Sum(System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 157385.dasm - System.Reflection.Metadata.BlobReader:ReadUInt64():ulong:this
         -14 (-51.85% of base) : 62806.dasm - System.Xml.XmlBufferReader:GetInt64(int):long:this
         -14 (-51.85% of base) : 62807.dasm - System.Xml.XmlBufferReader:GetUInt64(int):ulong:this

3364 total methods with Code Size differences (3346 improved, 18 regressed), 8 unchanged.

```

</details>

--------------------------------------------------------------------------------


</details>

<details>

<summary>libraries.pmi.windows.x86.checked.mch</summary>

To reproduce these diffs on Windows x86:
```
superpmi.py asmdiffs -target_os windows -target_arch x86 -arch x86
```

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 42153850 (overridden on cmd)
Total bytes of diff: 42070960 (overridden on cmd)
Total bytes of delta: -82890 (-0.20 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         138 : 187861.dasm (5.15% of base)
          67 : 176539.dasm (1.50% of base)
          55 : 198523.dasm (1.46% of base)
          34 : 100775.dasm (0.77% of base)
          27 : 179231.dasm (2.21% of base)
          26 : 180082.dasm (1.93% of base)
          26 : 92574.dasm (2.15% of base)
          24 : 180284.dasm (1.74% of base)
          23 : 224953.dasm (5.57% of base)
          21 : 233551.dasm (5.87% of base)
          20 : 176531.dasm (0.43% of base)
          18 : 88000.dasm (0.63% of base)
          14 : 258011.dasm (1.74% of base)
          14 : 258012.dasm (1.74% of base)
          12 : 258030.dasm (2.00% of base)
          12 : 258092.dasm (2.00% of base)
           7 : 214837.dasm (0.54% of base)
           6 : 140576.dasm (0.55% of base)
           6 : 185144.dasm (0.22% of base)
           2 : 129018.dasm (0.77% of base)

Top file improvements (bytes):
       -1647 : 211717.dasm (-26.22% of base)
       -1104 : 21348.dasm (-14.08% of base)
        -694 : 137909.dasm (-20.64% of base)
        -616 : 112451.dasm (-46.21% of base)
        -564 : 178028.dasm (-3.70% of base)
        -457 : 213958.dasm (-32.71% of base)
        -405 : 137857.dasm (-12.74% of base)
        -371 : 137758.dasm (-12.61% of base)
        -324 : 211659.dasm (-20.96% of base)
        -313 : 264283.dasm (-4.66% of base)
        -295 : 137847.dasm (-13.84% of base)
        -277 : 55578.dasm (-4.72% of base)
        -274 : 137900.dasm (-5.95% of base)
        -238 : 264292.dasm (-4.15% of base)
        -236 : 138452.dasm (-13.78% of base)
        -236 : 21340.dasm (-17.76% of base)
        -228 : 137867.dasm (-6.84% of base)
        -225 : 66027.dasm (-11.08% of base)
        -224 : 137877.dasm (-7.21% of base)
        -221 : 138451.dasm (-13.93% of base)

4056 total files with Code Size differences (4031 improved, 25 regressed), 16 unchanged.

Top method regressions (bytes):
         138 ( 5.15% of base) : 187861.dasm - <ConstructResponseAsync>d__57:MoveNext():this
          67 ( 1.50% of base) : 176539.dasm - System.Data.DataSet:ReadXml(System.Xml.XmlReader,int,bool):int:this
          55 ( 1.46% of base) : 198523.dasm - System.Management.ManagementClassGenerator:GeneratePropertyHelperEnums(System.Management.PropertyData,System.String,bool):bool:this
          34 ( 0.77% of base) : 100775.dasm - <ProcessIncomingFramesAsync>d__69:MoveNext():this
          27 ( 2.21% of base) : 179231.dasm - System.Data.Common.ByteStorage:Aggregate(int[],int):System.Object:this
          26 ( 2.15% of base) : 92574.dasm - <>c__DisplayClass32_0:<SetupCallbacks>b__33(Microsoft.Diagnostics.Tracing.Parsers.Clr.GCHeapStatsTraceData):this
          26 ( 1.93% of base) : 180082.dasm - System.Data.Common.Int16Storage:Aggregate(int[],int):System.Object:this
          24 ( 1.74% of base) : 180284.dasm - System.Data.Common.UInt32Storage:Aggregate(int[],int):System.Object:this
          23 ( 5.57% of base) : 224953.dasm - System.Text.ISO2022Encoding:GetMaxByteCount(int):int:this
          21 ( 5.87% of base) : 233551.dasm - ILCompiler.IBC.IBCDataReader:ReadBlobEntry():ILCompiler.IBC.BlobEntry:this
          20 ( 0.43% of base) : 176531.dasm - System.Data.DataSet:ReadXml(System.Xml.XmlReader,bool):int:this
          18 ( 0.63% of base) : 88000.dasm - Microsoft.Diagnostics.Tracing.Parsers.Clr.GCPerHeapHistoryTraceData:ToXml(System.Text.StringBuilder):System.Text.StringBuilder:this
          14 ( 1.74% of base) : 258011.dasm - System.Numerics.Tensors.Tensor:CreateFromDiagonal[System.__Canon](System.Numerics.Tensors.Tensor`1[System.__Canon],int):System.Numerics.Tensors.Tensor`1[System.__Canon]
          14 ( 1.74% of base) : 258012.dasm - System.Numerics.Tensors.Tensor:CreateFromDiagonal[ubyte](System.Numerics.Tensors.Tensor`1[ubyte],int):System.Numerics.Tensors.Tensor`1[ubyte]
          12 ( 2.00% of base) : 258030.dasm - System.Numerics.Tensors.Tensor`1[System.__Canon]:GetTriangle(int,bool):System.Numerics.Tensors.Tensor`1[System.__Canon]:this
          12 ( 2.00% of base) : 258092.dasm - System.Numerics.Tensors.Tensor`1[ubyte]:GetTriangle(int,bool):System.Numerics.Tensors.Tensor`1[ubyte]:this
           7 ( 0.54% of base) : 214837.dasm - System.Numerics.BigInteger:op_RightShift(System.Numerics.BigInteger,int):System.Numerics.BigInteger
           6 ( 0.55% of base) : 140576.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           6 ( 0.22% of base) : 185144.dasm - System.Diagnostics.CategorySample:.ctor(ubyte[],System.Diagnostics.CategoryEntry,System.Diagnostics.PerformanceCounterLib):this
           2 ( 0.80% of base) : 128605.dasm - Microsoft.FSharp.Collections.ListModule:ReduceBack[long](Microsoft.FSharp.Core.FSharpFunc`2[long,Microsoft.FSharp.Core.FSharpFunc`2[long,long]],Microsoft.FSharp.Collections.FSharpList`1[long]):long

Top method improvements (bytes):
       -1647 (-26.22% of base) : 211717.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1104 (-14.08% of base) : 21348.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldNeverOverflowBinaryOperators(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -694 (-20.64% of base) : 137909.dasm - Microsoft.VisualBasic.CompilerServices.Operators:IntDivideObject(System.Object,System.Object):System.Object
        -616 (-46.21% of base) : 112451.dasm - System.Xml.Xsl.Xslt.XslVisitor`1[long]:Visit(System.Xml.Xsl.Xslt.XslNode):long:this
        -564 (-3.70% of base) : 178028.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,int[]):System.Object:this
        -457 (-32.71% of base) : 213958.dasm - System.Reflection.Metadata.Ecma335.SignatureDecoder`2[long,System.Nullable`1[int]]:DecodeType(byref,bool,int):long:this
        -405 (-12.74% of base) : 137857.dasm - Microsoft.VisualBasic.CompilerServices.Operators:XorObject(System.Object,System.Object):System.Object
        -371 (-12.61% of base) : 137758.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:IDivObj(System.Object,System.Object):System.Object
        -324 (-20.96% of base) : 211659.dasm - System.Reflection.PortableExecutable.CorHeader:.ctor(byref):this
        -313 (-4.66% of base) : 264283.dasm - TestRunner:DoWorkStress():int:this
        -295 (-13.84% of base) : 137847.dasm - Microsoft.VisualBasic.CompilerServices.Operators:OrObject(System.Object,System.Object):System.Object
        -277 (-4.72% of base) : 55578.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionEvaluator:PerformCompileTimeBinaryOperation(ushort,byte,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CConst
        -274 (-5.95% of base) : 137900.dasm - Microsoft.VisualBasic.CompilerServices.Operators:ModObject(System.Object,System.Object):System.Object
        -238 (-4.15% of base) : 264292.dasm - Program:Main(System.String[]):int
        -236 (-17.76% of base) : 21340.dasm - Microsoft.CodeAnalysis.CSharp.Binder:FoldUncheckedIntegralBinaryOperator(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue):System.Object
        -236 (-13.78% of base) : 138452.dasm - Microsoft.VisualBasic.DateAndTime:DateDiff(int,System.DateTime,System.DateTime,int,int):long
        -228 (-6.84% of base) : 137867.dasm - Microsoft.VisualBasic.CompilerServices.Operators:AddObject(System.Object,System.Object):System.Object
        -225 (-11.08% of base) : 66027.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:FoldIntegralCharOrDateTimeBinaryOperator(int,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.ConstantValue,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,Microsoft.CodeAnalysis.VisualBasic.Symbols.TypeSymbol,byref,byref):Microsoft.CodeAnalysis.ConstantValue
        -224 (-7.21% of base) : 137877.dasm - Microsoft.VisualBasic.CompilerServices.Operators:SubtractObject(System.Object,System.Object):System.Object
        -221 (-13.93% of base) : 138451.dasm - Microsoft.VisualBasic.DateAndTime:DateAdd(int,double,System.DateTime):System.DateTime

Top method regressions (percentages):
          21 ( 5.87% of base) : 233551.dasm - ILCompiler.IBC.IBCDataReader:ReadBlobEntry():ILCompiler.IBC.BlobEntry:this
          23 ( 5.57% of base) : 224953.dasm - System.Text.ISO2022Encoding:GetMaxByteCount(int):int:this
         138 ( 5.15% of base) : 187861.dasm - <ConstructResponseAsync>d__57:MoveNext():this
          27 ( 2.21% of base) : 179231.dasm - System.Data.Common.ByteStorage:Aggregate(int[],int):System.Object:this
          26 ( 2.15% of base) : 92574.dasm - <>c__DisplayClass32_0:<SetupCallbacks>b__33(Microsoft.Diagnostics.Tracing.Parsers.Clr.GCHeapStatsTraceData):this
          12 ( 2.00% of base) : 258030.dasm - System.Numerics.Tensors.Tensor`1[System.__Canon]:GetTriangle(int,bool):System.Numerics.Tensors.Tensor`1[System.__Canon]:this
          12 ( 2.00% of base) : 258092.dasm - System.Numerics.Tensors.Tensor`1[ubyte]:GetTriangle(int,bool):System.Numerics.Tensors.Tensor`1[ubyte]:this
          26 ( 1.93% of base) : 180082.dasm - System.Data.Common.Int16Storage:Aggregate(int[],int):System.Object:this
          14 ( 1.74% of base) : 258012.dasm - System.Numerics.Tensors.Tensor:CreateFromDiagonal[ubyte](System.Numerics.Tensors.Tensor`1[ubyte],int):System.Numerics.Tensors.Tensor`1[ubyte]
          24 ( 1.74% of base) : 180284.dasm - System.Data.Common.UInt32Storage:Aggregate(int[],int):System.Object:this
          14 ( 1.74% of base) : 258011.dasm - System.Numerics.Tensors.Tensor:CreateFromDiagonal[System.__Canon](System.Numerics.Tensors.Tensor`1[System.__Canon],int):System.Numerics.Tensors.Tensor`1[System.__Canon]
          67 ( 1.50% of base) : 176539.dasm - System.Data.DataSet:ReadXml(System.Xml.XmlReader,int,bool):int:this
          55 ( 1.46% of base) : 198523.dasm - System.Management.ManagementClassGenerator:GeneratePropertyHelperEnums(System.Management.PropertyData,System.String,bool):bool:this
           2 ( 1.13% of base) : 229863.dasm - System.Text.RegularExpressions.Symbolic.UInt64Solver:ConvertFromBDD(System.Text.RegularExpressions.Symbolic.BDD,System.Text.RegularExpressions.Symbolic.CharSetSolver):ulong:this
           2 ( 0.80% of base) : 128605.dasm - Microsoft.FSharp.Collections.ListModule:ReduceBack[long](Microsoft.FSharp.Core.FSharpFunc`2[long,Microsoft.FSharp.Core.FSharpFunc`2[long,long]],Microsoft.FSharp.Collections.FSharpList`1[long]):long
          34 ( 0.77% of base) : 100775.dasm - <ProcessIncomingFramesAsync>d__69:MoveNext():this
           2 ( 0.77% of base) : 129018.dasm - Microsoft.FSharp.Collections.SeqModule:ReduceBack[long](Microsoft.FSharp.Core.FSharpFunc`2[long,Microsoft.FSharp.Core.FSharpFunc`2[long,long]],System.Collections.Generic.IEnumerable`1[long]):long
          18 ( 0.63% of base) : 88000.dasm - Microsoft.Diagnostics.Tracing.Parsers.Clr.GCPerHeapHistoryTraceData:ToXml(System.Text.StringBuilder):System.Text.StringBuilder:this
           6 ( 0.55% of base) : 140576.dasm - Newtonsoft.Json.Utilities.EnumUtils:InitializeValuesAndNames(Newtonsoft.Json.Utilities.StructMultiKey`2[System.Type,Newtonsoft.Json.Serialization.NamingStrategy]):Newtonsoft.Json.Utilities.EnumInfo
           7 ( 0.54% of base) : 214837.dasm - System.Numerics.BigInteger:op_RightShift(System.Numerics.BigInteger,int):System.Numerics.BigInteger

Top method improvements (percentages):
         -14 (-51.85% of base) : 119262.dasm - <>c__0`1[long]:<Build>b__0_4(System.Func`1[long]):long:this
         -14 (-51.85% of base) : 167320.dasm - Builder[long]:System.Collections.Immutable.IOrderedCollection<T>.get_Item(int):long:this
         -14 (-51.85% of base) : 240106.dasm - FastSerialization.MemoryStreamReader:<.ctor>b__1_1():long:this
         -14 (-51.85% of base) : 240072.dasm - FastSerialization.SegmentedMemoryStreamReader:<.ctor>b__2_1():long:this
         -14 (-51.85% of base) : 95724.dasm - Microsoft.Build.BackEnd.NodeEndpointOutOfProc:GetClientHandshake():long:this
         -14 (-51.85% of base) : 73868.dasm - Microsoft.Diagnostics.Tracing.TraceEvent:GetAddressAt(int):ulong:this
         -14 (-51.85% of base) : 74075.dasm - Microsoft.Diagnostics.Tracing.Utilities.FastStream:ReadULong():ulong:this
         -14 (-51.85% of base) : 120032.dasm - Microsoft.FSharp.Collections.FSharpList`1[long]:get_Item(int):long:this
         -14 (-51.85% of base) : 128927.dasm - Microsoft.FSharp.Collections.SeqModule:Get[long](int,System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 121751.dasm - Microsoft.FSharp.Core.ExtraTopLevelOperators:PrintFormatToString[long](Microsoft.FSharp.Core.PrintfFormat`4[long,Microsoft.FSharp.Core.Unit,System.String,System.String]):long
         -14 (-51.85% of base) : 131047.dasm - Microsoft.FSharp.Core.Operators:Unbox[long](System.Object):long
         -14 (-51.85% of base) : 142098.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToInt64(System.IFormatProvider):long:this
         -14 (-51.85% of base) : 142099.dasm - Newtonsoft.Json.Linq.JValue:System.IConvertible.ToUInt64(System.IFormatProvider):ulong:this
         -14 (-51.85% of base) : 141010.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToInt64(System.Object):long:this
         -14 (-51.85% of base) : 141016.dasm - Newtonsoft.Json.Serialization.JsonFormatterConverter:ToUInt64(System.Object):ulong:this
         -14 (-51.85% of base) : 14276.dasm - System.Lazy`1[long]:CreateViaDefaultConstructor():long
         -14 (-51.85% of base) : 195973.dasm - System.Linq.Enumerable:Max(System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 196021.dasm - System.Linq.Enumerable:Max[ubyte](System.Collections.Generic.IEnumerable`1[ubyte],System.Func`2[ubyte,long]):long
         -14 (-51.85% of base) : 196047.dasm - System.Linq.Enumerable:Min(System.Collections.Generic.IEnumerable`1[long]):long
         -14 (-51.85% of base) : 196096.dasm - System.Linq.Enumerable:Min[ubyte](System.Collections.Generic.IEnumerable`1[ubyte],System.Func`2[ubyte,long]):long

4056 total methods with Code Size differences (4031 improved, 25 regressed), 16 unchanged.

```

</details>

--------------------------------------------------------------------------------


</details>

<details>

<summary>libraries_tests.pmi.windows.x86.checked.mch</summary>

To reproduce these diffs on Windows x86:
```
superpmi.py asmdiffs -target_os windows -target_arch x86 -arch x86
```

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 86700603 (overridden on cmd)
Total bytes of diff: 86536127 (overridden on cmd)
Total bytes of delta: -164476 (-0.19 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         247 : 184276.dasm (0.80% of base)
          20 : 55086.dasm (1.22% of base)
          10 : 19473.dasm (0.71% of base)
          10 : 36708.dasm (0.71% of base)
           4 : 149009.dasm (0.11% of base)
           4 : 207609.dasm (0.11% of base)
           4 : 319585.dasm (0.34% of base)
           3 : 319577.dasm (0.28% of base)
           3 : 319578.dasm (0.22% of base)
           3 : 198527.dasm (0.27% of base)
           2 : 276467.dasm (0.05% of base)
           2 : 355.dasm (0.33% of base)
           2 : 169201.dasm (0.18% of base)
           2 : 270133.dasm (0.21% of base)
           2 : 221770.dasm (0.33% of base)
           2 : 153617.dasm (0.34% of base)
           2 : 217521.dasm (0.33% of base)
           1 : 264919.dasm (0.08% of base)
           1 : 248493.dasm (0.05% of base)
           1 : 319592.dasm (0.13% of base)

Top file improvements (bytes):
       -1647 : 221384.dasm (-26.22% of base)
       -1494 : 92573.dasm (-25.12% of base)
       -1357 : 219558.dasm (-30.83% of base)
       -1357 : 223923.dasm (-30.83% of base)
       -1266 : 92572.dasm (-18.22% of base)
       -1256 : 92705.dasm (-23.55% of base)
       -1206 : 92704.dasm (-21.52% of base)
       -1118 : 92712.dasm (-16.15% of base)
       -1000 : 92716.dasm (-20.57% of base)
        -972 : 92708.dasm (-10.83% of base)
        -941 : 85859.dasm (-19.59% of base)
        -927 : 92719.dasm (-16.56% of base)
        -861 : 251586.dasm (-15.82% of base)
        -708 : 292039.dasm (-12.40% of base)
        -707 : 92720.dasm (-5.18% of base)
        -707 : 92721.dasm (-5.19% of base)
        -696 : 99458.dasm (-11.64% of base)
        -691 : 92581.dasm (-11.63% of base)
        -663 : 101510.dasm (-10.93% of base)
        -651 : 92709.dasm (-11.57% of base)

5920 total files with Code Size differences (5898 improved, 22 regressed), 39 unchanged.

Top method regressions (bytes):
         247 ( 0.80% of base) : 184276.dasm - MonoTests.System.Drawing.Imaging.IconCodecTest:Bitmap96Pixels():this
          20 ( 1.22% of base) : 55086.dasm - Microsoft.CodeAnalysis.Differencing.EditScript`1[long]:AlignChildren(System.Collections.Generic.List`1[Microsoft.CodeAnalysis.Differencing.Edit`1[long]],long,long):this
          10 ( 0.71% of base) : 19473.dasm - <WriteAsyncEnumerable_LongRunningEnumeration_Cancellation>d__4:MoveNext():this
          10 ( 0.71% of base) : 36708.dasm - <WriteAsyncEnumerable_LongRunningEnumeration_Cancellation>d__4:MoveNext():this
           4 ( 0.11% of base) : 149009.dasm - <get_VerifyUploadServersStreamsAndExpectedData>d__33:MoveNext():bool:this
           4 ( 0.11% of base) : 207609.dasm - <get_VerifyUploadServersStreamsAndExpectedData>d__33:MoveNext():bool:this
           4 ( 0.34% of base) : 319585.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:SlidingExpirationRenewedByAccess():this
           3 ( 0.28% of base) : 319577.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:AbsoluteExpirationExpires():this
           3 ( 0.22% of base) : 319578.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:AbsoluteExpirationExpiresInBackground():this
           3 ( 0.27% of base) : 198527.dasm - System.Text.Tests.EncodingExtensionsTests:GetBytes_Encoding_ReadOnlySequence_IBufferWriter_LargeMultiSegment()
           2 ( 0.05% of base) : 276467.dasm - <CertificateCallbackThrowPropagates>d__6:MoveNext():this
           2 ( 0.33% of base) : 355.dasm - DataContractSerializerTests:DCS_DuplicatedKnownTypesWithAdapterThroughConstructor()
           2 ( 0.34% of base) : 153617.dasm - DataContractSerializerTests:DCS_DuplicatedKnownTypesWithAdapterThroughConstructor()
           2 ( 0.18% of base) : 169201.dasm - Microsoft.IdentityModel.Json.Utilities.EnumUtils:InitializeValuesAndNames(Microsoft.IdentityModel.Json.Utilities.StructMultiKey`2[System.Type,Microsoft.IdentityModel.Json.Serialization.NamingStrategy]):Microsoft.IdentityModel.Json.Utilities.EnumInfo
           2 ( 0.33% of base) : 221770.dasm - Microsoft.SqlServer.Server.ValueUtilsSmi:GetSqlBytes(Microsoft.SqlServer.Server.SmiEventSink_Default,Microsoft.SqlServer.Server.ITypedGettersV3,int,Microsoft.SqlServer.Server.SmiMetaData):System.Data.SqlTypes.SqlBytes
           2 ( 0.33% of base) : 217521.dasm - Microsoft.SqlServer.Server.ValueUtilsSmi:GetSqlBytes(Microsoft.SqlServer.Server.SmiEventSink_Default,Microsoft.SqlServer.Server.ITypedGettersV3,int,Microsoft.SqlServer.Server.SmiMetaData):System.Data.SqlTypes.SqlBytes
           2 ( 0.21% of base) : 270133.dasm - System.IO.Pipelines.Tests.ReadAsyncCancellationTests:ReadAsyncCancellationDeadlock():this
           1 ( 0.14% of base) : 216199.dasm - <Docs_Examples_MDYtoDMY>d__1:MoveNext():this
           1 ( 0.13% of base) : 319592.dasm - Microsoft.Extensions.Caching.Memory.TokenExpirationTests:ExpiredLazyTokenRemovesItemInBackground():this
           1 ( 0.05% of base) : 248493.dasm - ReduceTokensRewriter:VisitLiteralExpression(Microsoft.CodeAnalysis.VisualBasic.Syntax.LiteralExpressionSyntax):Microsoft.CodeAnalysis.SyntaxNode:this

Top method improvements (bytes):
       -1647 (-26.22% of base) : 221384.dasm - System.Reflection.PortableExecutable.PEHeader:.ctor(byref):this
       -1494 (-25.12% of base) : 92573.dasm - System.Tests.TimeOnlyTests:AddTest()
       -1357 (-30.83% of base) : 219558.dasm - System.Data.SqlClient.SqlConnectionTimeoutErrorInternal:GetErrorMessage():System.String:this
       -1357 (-30.83% of base) : 223923.dasm - System.Data.SqlClient.SqlConnectionTimeoutErrorInternal:GetErrorMessage():System.String:this
       -1266 (-18.22% of base) : 92572.dasm - System.Tests.TimeOnlyTests:ConstructorsTest()
       -1256 (-23.55% of base) : 92705.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_PerthRules()
       -1206 (-21.52% of base) : 92704.dasm - System.Tests.TimeZoneInfoTests:ConverTime_DateTime_VariousSystemTimeZonesTest()
       -1118 (-16.15% of base) : 92712.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_MiscUtc()
       -1000 (-20.57% of base) : 92716.dasm - System.Tests.TimeZoneInfoTests:GetAmbiguousTimeOffsets_Invalid()
        -972 (-10.83% of base) : 92708.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToSystem()
        -941 (-19.59% of base) : 85859.dasm - System.Xml.XmlConvertTests.ToTypeTests:ToType43():int:this
        -927 (-16.56% of base) : 92719.dasm - System.Tests.TimeZoneInfoTests:GetAmbiguousTimeOffsets_LocalAmbiguousOffsets()
        -861 (-15.82% of base) : 251586.dasm - <EnumerateMemoryRegions>d__62:MoveNext():bool:this
        -708 (-12.40% of base) : 292039.dasm - System.Numerics.Tests.GetBitLengthTests:RunGetBitLengthTests()
        -707 (-5.18% of base) : 92720.dasm - System.Tests.TimeZoneInfoTests:IsDaylightSavingTime()
        -707 (-5.19% of base) : 92721.dasm - System.Tests.TimeZoneInfoTests:IsInvalidTime()
        -696 (-11.64% of base) : 99458.dasm - <AddMonths_TestData>d__48:MoveNext():bool:this
        -691 (-11.63% of base) : 92581.dasm - System.Tests.TimeOnlyTests:BasicFormatParseTest()
        -663 (-10.93% of base) : 101510.dasm - <CompareTo_TestData>d__19:MoveNext():bool:this
        -651 (-11.57% of base) : 92709.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToLocal()

Top method regressions (percentages):
          20 ( 1.22% of base) : 55086.dasm - Microsoft.CodeAnalysis.Differencing.EditScript`1[long]:AlignChildren(System.Collections.Generic.List`1[Microsoft.CodeAnalysis.Differencing.Edit`1[long]],long,long):this
         247 ( 0.80% of base) : 184276.dasm - MonoTests.System.Drawing.Imaging.IconCodecTest:Bitmap96Pixels():this
          10 ( 0.71% of base) : 19473.dasm - <WriteAsyncEnumerable_LongRunningEnumeration_Cancellation>d__4:MoveNext():this
          10 ( 0.71% of base) : 36708.dasm - <WriteAsyncEnumerable_LongRunningEnumeration_Cancellation>d__4:MoveNext():this
           2 ( 0.34% of base) : 153617.dasm - DataContractSerializerTests:DCS_DuplicatedKnownTypesWithAdapterThroughConstructor()
           4 ( 0.34% of base) : 319585.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:SlidingExpirationRenewedByAccess():this
           2 ( 0.33% of base) : 221770.dasm - Microsoft.SqlServer.Server.ValueUtilsSmi:GetSqlBytes(Microsoft.SqlServer.Server.SmiEventSink_Default,Microsoft.SqlServer.Server.ITypedGettersV3,int,Microsoft.SqlServer.Server.SmiMetaData):System.Data.SqlTypes.SqlBytes
           2 ( 0.33% of base) : 217521.dasm - Microsoft.SqlServer.Server.ValueUtilsSmi:GetSqlBytes(Microsoft.SqlServer.Server.SmiEventSink_Default,Microsoft.SqlServer.Server.ITypedGettersV3,int,Microsoft.SqlServer.Server.SmiMetaData):System.Data.SqlTypes.SqlBytes
           2 ( 0.33% of base) : 355.dasm - DataContractSerializerTests:DCS_DuplicatedKnownTypesWithAdapterThroughConstructor()
           3 ( 0.28% of base) : 319577.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:AbsoluteExpirationExpires():this
           3 ( 0.27% of base) : 198527.dasm - System.Text.Tests.EncodingExtensionsTests:GetBytes_Encoding_ReadOnlySequence_IBufferWriter_LargeMultiSegment()
           3 ( 0.22% of base) : 319578.dasm - Microsoft.Extensions.Caching.Memory.TimeExpirationTests:AbsoluteExpirationExpiresInBackground():this
           2 ( 0.21% of base) : 270133.dasm - System.IO.Pipelines.Tests.ReadAsyncCancellationTests:ReadAsyncCancellationDeadlock():this
           2 ( 0.18% of base) : 169201.dasm - Microsoft.IdentityModel.Json.Utilities.EnumUtils:InitializeValuesAndNames(Microsoft.IdentityModel.Json.Utilities.StructMultiKey`2[System.Type,Microsoft.IdentityModel.Json.Serialization.NamingStrategy]):Microsoft.IdentityModel.Json.Utilities.EnumInfo
           1 ( 0.14% of base) : 216199.dasm - <Docs_Examples_MDYtoDMY>d__1:MoveNext():this
           1 ( 0.13% of base) : 319592.dasm - Microsoft.Extensions.Caching.Memory.TokenExpirationTests:ExpiredLazyTokenRemovesItemInBackground():this
           4 ( 0.11% of base) : 149009.dasm - <get_VerifyUploadServersStreamsAndExpectedData>d__33:MoveNext():bool:this
           4 ( 0.11% of base) : 207609.dasm - <get_VerifyUploadServersStreamsAndExpectedData>d__33:MoveNext():bool:this
           1 ( 0.08% of base) : 264919.dasm - System.Formats.Asn1.Tests.Reader.ReadGeneralizedTime:ExcessivelyPreciseFraction()
           1 ( 0.08% of base) : 214784.dasm - System.Security.Cryptography.Pkcs.Tests.TimestampTokenInfoTests:BuilderCtor_Timestamp_KeepsSubSeconds()

Top method improvements (percentages):
         -14 (-51.85% of base) : 310022.dasm - Castle.Core.Internal.CollectionExtensions:Find[long](long[],System.Predicate`1[long]):long
         -14 (-51.85% of base) : 71701.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.dynamicobj005.dynamicobj005.MyStack`1[long]:get_Item(int):long:this
         -14 (-51.85% of base) : 47672.dasm - Microsoft.CodeAnalysis.AnalyzerConfigOptionsExtensions:GetOption[long](Microsoft.CodeAnalysis.Diagnostics.AnalyzerConfigOptions,Microsoft.CodeAnalysis.Options.Option`1[long]):long
         -14 (-51.85% of base) : 170663.dasm - Microsoft.IdentityModel.Json.Linq.JValue:System.IConvertible.ToInt64(System.IFormatProvider):long:this
         -14 (-51.85% of base) : 170664.dasm - Microsoft.IdentityModel.Json.Linq.JValue:System.IConvertible.ToUInt64(System.IFormatProvider):ulong:this
         -14 (-51.85% of base) : 169610.dasm - Microsoft.IdentityModel.Json.Serialization.JsonFormatterConverter:ToInt64(System.Object):long:this
         -14 (-51.85% of base) : 169616.dasm - Microsoft.IdentityModel.Json.Serialization.JsonFormatterConverter:ToUInt64(System.Object):ulong:this
         -14 (-51.85% of base) : 329809.dasm - Moq.Capture:With[long](Moq.CaptureMatch`1[long]):long
         -14 (-51.85% of base) : 256144.dasm - NuGet.Protocol.JsonExtensions:FromJson[long](System.String,Newtonsoft.Json.JsonSerializerSettings):long
         -14 (-51.85% of base) : 220220.dasm - System.Data.SqlClient.SqlCachedStream:get_Length():long:this
         -14 (-51.85% of base) : 224566.dasm - System.Data.SqlClient.SqlCachedStream:get_Length():long:this
         -14 (-51.85% of base) : 153449.dasm - TestFormatter:Schedule(System.Object):long:this
         -14 (-50.00% of base) : 218754.dasm - System.Data.Common.ADP:TimerFromSeconds(int):long
         -14 (-48.28% of base) : 167922.dasm - Microsoft.IdentityModel.Json.JsonConvert:DeserializeAnonymousType[long](System.String,long,Microsoft.IdentityModel.Json.JsonSerializerSettings):long
         -14 (-46.67% of base) : 57406.dasm - <>c__DisplayClass18_0`1[long]:<ScheduleTaskInProgress>b__0(System.Threading.Tasks.Task):long:this
         -14 (-46.67% of base) : 300691.dasm - <>c__DisplayClass7_0`1[long]:<CallOnEmptyStack>b__0():long:this
         -14 (-46.67% of base) : 226856.dasm - Autofac.Core.ServiceRegistration:GetRegistrationOrder():long:this
         -14 (-46.67% of base) : 310488.dasm - Castle.Components.DictionaryAdapter.DynamicValueDelegate`1[long]:get_Value():long:this
         -14 (-46.67% of base) : 196564.dasm - DelegateIterator`1[long]:get_Current():long:this
         -14 (-46.67% of base) : 50828.dasm - Microsoft.CodeAnalysis.SQLite.v2.Interop.SqlStatement:GetInt64At(int):long:this

5920 total methods with Code Size differences (5898 improved, 22 regressed), 39 unchanged.

```

</details>

--------------------------------------------------------------------------------


</details>

</details>
