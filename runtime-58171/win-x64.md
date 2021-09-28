## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1723
Total bytes of diff: 1736
Total bytes of delta: 13 (0.75% of base)
Total relative delta: 0.76
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           7 : 15873.dasm (29.17% of base)
           6 : 14306.dasm (24.00% of base)
           6 : 16401.dasm (24.00% of base)

Top file improvements (bytes):
          -5 : 10651.dasm (-0.33% of base)
          -1 : 4175.dasm (-0.71% of base)

5 total files with Code Size differences (2 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
           7 (29.17% of base) : 15873.dasm - System.Numerics.Tests.Perf_Quaternion:ConjugateBenchmark():System.Numerics.Quaternion:this
           6 (24.00% of base) : 14306.dasm - System.Numerics.Tests.Perf_Quaternion:NegationOperatorBenchmark():System.Numerics.Quaternion:this
           6 (24.00% of base) : 16401.dasm - System.Numerics.Tests.Perf_Quaternion:NegateBenchmark():System.Numerics.Quaternion:this

Top method improvements (bytes):
          -5 (-0.33% of base) : 10651.dasm - System.Number:TryParseSingle(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):bool
          -1 (-0.71% of base) : 4175.dasm - System.Tests.Perf_Single:get_Values():System.Collections.Generic.IEnumerable`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]

Top method regressions (percentages):
           7 (29.17% of base) : 15873.dasm - System.Numerics.Tests.Perf_Quaternion:ConjugateBenchmark():System.Numerics.Quaternion:this
           6 (24.00% of base) : 14306.dasm - System.Numerics.Tests.Perf_Quaternion:NegationOperatorBenchmark():System.Numerics.Quaternion:this
           6 (24.00% of base) : 16401.dasm - System.Numerics.Tests.Perf_Quaternion:NegateBenchmark():System.Numerics.Quaternion:this

Top method improvements (percentages):
          -1 (-0.71% of base) : 4175.dasm - System.Tests.Perf_Single:get_Values():System.Collections.Generic.IEnumerable`1[[System.Object, System.Private.CoreLib, Version=6.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
          -5 (-0.33% of base) : 10651.dasm - System.Number:TryParseSingle(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):bool

5 total methods with Code Size differences (2 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 6596962
Total bytes of diff: 6587491
Total bytes of delta: -9471 (-0.14% of base)
Total relative delta: -18.86
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           9 : 218364.dasm (8.82% of base)
           9 : 218369.dasm (15.79% of base)
           9 : 218360.dasm (10.98% of base)
           1 : 218287.dasm (1.11% of base)
           1 : 218291.dasm (0.93% of base)
           1 : 218296.dasm (1.54% of base)

Top file improvements (bytes):
         -37 : 131886.dasm (-0.05% of base)
         -37 : 134588.dasm (-0.05% of base)
         -14 : 215479.dasm (-0.24% of base)
         -14 : 174945.dasm (-0.24% of base)
          -8 : 226667.dasm (-0.02% of base)
          -8 : 226673.dasm (-0.02% of base)
          -8 : 226679.dasm (-0.02% of base)
          -8 : 226655.dasm (-0.02% of base)
          -8 : 226661.dasm (-0.02% of base)
          -7 : 238374.dasm (-1.52% of base)
          -7 : 238377.dasm (-1.61% of base)
          -6 : 131035.dasm (-0.86% of base)
          -6 : 218358.dasm (-0.02% of base)
          -4 : 218285.dasm (-0.01% of base)
          -4 : 82961.dasm (-4.21% of base)
          -4 : 218327.dasm (-3.67% of base)
          -4 : 251907.dasm (-0.28% of base)
          -4 : 219531.dasm (-0.14% of base)
          -3 : 131865.dasm (-1.26% of base)
          -3 : 134505.dasm (-1.01% of base)

4229 total files with Code Size differences (4223 improved, 6 regressed), 0 unchanged.

Top method regressions (bytes):
           9 ( 8.82% of base) : 218364.dasm - CL:.ctor():this
           9 (15.79% of base) : 218369.dasm - r4NaNsub:.cctor()
           9 (10.98% of base) : 218360.dasm - r4NaNsub:.cctor()
           1 ( 1.11% of base) : 218287.dasm - r4NaNadd:.cctor()
           1 ( 0.93% of base) : 218291.dasm - CL:.ctor():this
           1 ( 1.54% of base) : 218296.dasm - r4NaNadd:.cctor()

Top method improvements (bytes):
         -37 (-0.05% of base) : 131886.dasm - testout1:.cctor()
         -37 (-0.05% of base) : 134588.dasm - testout1:.cctor()
         -14 (-0.24% of base) : 215479.dasm - testout1:.cctor()
         -14 (-0.24% of base) : 174945.dasm - testout1:.cctor()
          -8 (-0.02% of base) : 226667.dasm - floatMDArrTest:Main():int
          -8 (-0.02% of base) : 226673.dasm - intMDArrTest:Main():int
          -8 (-0.02% of base) : 226679.dasm - longMDArrTest:Main():int
          -8 (-0.02% of base) : 226655.dasm - decimalMDArrTest:Main():int
          -8 (-0.02% of base) : 226661.dasm - doubleMDArrTest:Main():int
          -7 (-1.52% of base) : 238374.dasm - testout1:.cctor()
          -7 (-1.61% of base) : 238377.dasm - testout1:.cctor()
          -6 (-0.86% of base) : 131035.dasm - testout1:Func_0_2_3_5_1():int
          -6 (-0.02% of base) : 218358.dasm - r4NaNsub:Main():int
          -4 (-0.01% of base) : 218285.dasm - r4NaNadd:Main():int
          -4 (-4.21% of base) : 82961.dasm - _bgt:initialize()
          -4 (-3.67% of base) : 218327.dasm - CL:.ctor():this
          -4 (-0.28% of base) : 251907.dasm - GitHub_18144:Main(System.String[]):int
          -4 (-0.14% of base) : 219531.dasm - testout1:Main():int
          -3 (-1.26% of base) : 131865.dasm - testout1:Func_0_6_6_4_6():float
          -3 (-1.01% of base) : 134505.dasm - testout1:Func_0_6_4_5_1():float

Top method regressions (percentages):
           9 (15.79% of base) : 218369.dasm - r4NaNsub:.cctor()
           9 (10.98% of base) : 218360.dasm - r4NaNsub:.cctor()
           9 ( 8.82% of base) : 218364.dasm - CL:.ctor():this
           1 ( 1.54% of base) : 218296.dasm - r4NaNadd:.cctor()
           1 ( 1.11% of base) : 218287.dasm - r4NaNadd:.cctor()
           1 ( 0.93% of base) : 218291.dasm - CL:.ctor():this

Top method improvements (percentages):
          -1 (-12.50% of base) : 249884.dasm - JitInliningTest.Args1:f11b(byref)
          -2 (-11.76% of base) : 135698.dasm - CL_0_3_2_3_4:.ctor():this
          -2 (-11.76% of base) : 194820.dasm - CL_0_1_1_1_1_1_1_1_1_1_1_1_1_1_1_1_1_1_1_1:.ctor():this
          -2 (-11.76% of base) : 135846.dasm - CL_0_2_1_1_1:.ctor():this
          -1 (-11.11% of base) : 135296.dasm - CL_0_6_5_3_4:.ctor():this
          -1 (-11.11% of base) : 135310.dasm - CL_0_6_4_5_1:.ctor():this
          -1 (-11.11% of base) : 135656.dasm - CL_0_3_5_4_6:.ctor():this
          -1 (-11.11% of base) : 135664.dasm - CL_0_3_5_2_6:.ctor():this
          -1 (-11.11% of base) : 135371.dasm - CL_0_6_1_5_2:.ctor():this
          -1 (-11.11% of base) : 135410.dasm - CL_0_5_5_5_5:.ctor():this
          -1 (-11.11% of base) : 135427.dasm - CL_0_5_4_5_6:.ctor():this
          -1 (-11.11% of base) : 135455.dasm - CL_0_5_3_1_4:.ctor():this
          -1 (-11.11% of base) : 135728.dasm - CL_0_3_1_1_2:.ctor():this
          -1 (-11.11% of base) : 135271.dasm - CL_0_6_6_6_3:.ctor():this
          -1 (-11.11% of base) : 135283.dasm - CL_0_6_6_2_4:.ctor():this
          -1 (-11.11% of base) : 135467.dasm - CL_0_5_2_4_1:.ctor():this
          -1 (-11.11% of base) : 135469.dasm - CL_0_5_2_3_4:.ctor():this
          -1 (-11.11% of base) : 135794.dasm - CL_0_2_3_2_1:.ctor():this
          -1 (-11.11% of base) : 194829.dasm - CL_0_1_1_1_1_1_1_1_1:.ctor():this
          -1 (-11.11% of base) : 194830.dasm - CL_0_1_1_1_1_1_1_1:.ctor():this

4229 total methods with Code Size differences (4223 improved, 6 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2793
Total bytes of diff: 2779
Total bytes of delta: -14 (-0.50% of base)
Total relative delta: -0.03
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -6 : 160160.dasm (-1.23% of base)
          -5 : 94735.dasm (-0.29% of base)
          -2 : 12556.dasm (-0.73% of base)
          -1 : 52173.dasm (-0.31% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -6 (-1.23% of base) : 160160.dasm - System.Text.Json.JsonReaderHelper:TryGetFloatingPointConstant(System.ReadOnlySpan`1[System.Byte],byref):bool
          -5 (-0.29% of base) : 94735.dasm - System.Number:TryParseSingle(System.ReadOnlySpan`1[System.Char],int,System.Globalization.NumberFormatInfo,byref):bool
          -2 (-0.73% of base) : 12556.dasm - System.Xml.XmlConvert:TryToSingle(System.String,byref):System.Exception
          -1 (-0.31% of base) : 52173.dasm - System.Data.SqlTypes.SqlSingle:.cctor()

Top method improvements (percentages):
          -6 (-1.23% of base) : 160160.dasm - System.Text.Json.JsonReaderHelper:TryGetFloatingPointConstant(System.ReadOnlySpan`1[System.Byte],byref):bool
          -2 (-0.73% of base) : 12556.dasm - System.Xml.XmlConvert:TryToSingle(System.String,byref):System.Exception
          -1 (-0.31% of base) : 52173.dasm - System.Data.SqlTypes.SqlSingle:.cctor()
          -5 (-0.29% of base) : 94735.dasm - System.Number:TryParseSingle(System.ReadOnlySpan`1[System.Char],int,System.Globalization.NumberFormatInfo,byref):bool

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1500
Total bytes of diff: 1482
Total bytes of delta: -18 (-1.20% of base)
Total relative delta: -0.05
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -10 : 133181.dasm (-1.12% of base)
          -6 : 152412.dasm (-3.16% of base)
          -1 : 86052.dasm (-0.32% of base)
          -1 : 149916.dasm (-0.89% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -10 (-1.12% of base) : 133181.dasm - System.Xml.XmlConvert:TryToSingle(System.String,byref):System.Exception
          -6 (-3.16% of base) : 152412.dasm - System.Text.Json.JsonReaderHelper:TryGetFloatingPointConstant(System.ReadOnlySpan`1[Byte],byref):bool
          -1 (-0.32% of base) : 86052.dasm - Microsoft.Diagnostics.Tracing.Stacks.InternStackSource:Diff(Microsoft.Diagnostics.Tracing.Stacks.StackSource,Microsoft.Diagnostics.Tracing.Stacks.StackSourceStacks,Microsoft.Diagnostics.Tracing.Stacks.StackSource,Microsoft.Diagnostics.Tracing.Stacks.StackSourceStacks):Microsoft.Diagnostics.Tracing.Stacks.InternStackSource
          -1 (-0.89% of base) : 149916.dasm - System.Speech.Recognition.SemanticValue:.ctor(System.Object):this

Top method improvements (percentages):
          -6 (-3.16% of base) : 152412.dasm - System.Text.Json.JsonReaderHelper:TryGetFloatingPointConstant(System.ReadOnlySpan`1[Byte],byref):bool
         -10 (-1.12% of base) : 133181.dasm - System.Xml.XmlConvert:TryToSingle(System.String,byref):System.Exception
          -1 (-0.89% of base) : 149916.dasm - System.Speech.Recognition.SemanticValue:.ctor(System.Object):this
          -1 (-0.32% of base) : 86052.dasm - Microsoft.Diagnostics.Tracing.Stacks.InternStackSource:Diff(Microsoft.Diagnostics.Tracing.Stacks.StackSource,Microsoft.Diagnostics.Tracing.Stacks.StackSourceStacks,Microsoft.Diagnostics.Tracing.Stacks.StackSource,Microsoft.Diagnostics.Tracing.Stacks.StackSourceStacks):Microsoft.Diagnostics.Tracing.Stacks.InternStackSource

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1448552
Total bytes of diff: 1447575
Total bytes of delta: -977 (-0.07% of base)
Total relative delta: -1.94
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          11 : 171269.dasm (1.33% of base)
          11 : 173748.dasm (0.22% of base)
          11 : 173821.dasm (0.47% of base)
          11 : 171180.dasm (1.33% of base)
           3 : 171268.dasm (0.41% of base)
           3 : 292939.dasm (0.83% of base)
           3 : 292941.dasm (0.96% of base)
           3 : 171166.dasm (0.31% of base)
           3 : 171197.dasm (0.44% of base)
           3 : 171175.dasm (0.41% of base)
           3 : 171195.dasm (0.46% of base)

Top file improvements (bytes):
         -35 : 59512.dasm (-0.97% of base)
         -32 : 145004.dasm (-0.01% of base)
         -31 : 143847.dasm (-0.28% of base)
         -30 : 209113.dasm (-0.52% of base)
         -27 : 145183.dasm (-0.36% of base)
         -26 : 144892.dasm (-0.03% of base)
         -26 : 59644.dasm (-0.69% of base)
         -10 : 59488.dasm (-0.34% of base)
         -10 : 144803.dasm (-0.03% of base)
          -9 : 144974.dasm (-0.02% of base)
          -9 : 334258.dasm (-0.11% of base)
          -8 : 172391.dasm (-0.18% of base)
          -8 : 209519.dasm (-1.51% of base)
          -8 : 144876.dasm (-0.02% of base)
          -8 : 83237.dasm (-0.35% of base)
          -8 : 83251.dasm (-0.58% of base)
          -8 : 172377.dasm (-0.12% of base)
          -8 : 172384.dasm (-0.12% of base)
          -8 : 59619.dasm (-0.25% of base)
          -7 : 82814.dasm (-0.35% of base)

285 total files with Code Size differences (274 improved, 11 regressed), 3 unchanged.

Top method regressions (bytes):
          11 ( 1.33% of base) : 171269.dasm - System.Drawing.Tests.RegionTests:Complement_InfiniteRegion_Success():this
          11 ( 0.22% of base) : 173748.dasm - <Exclude_TestData>d__43:MoveNext():bool:this
          11 ( 0.47% of base) : 173821.dasm - <Xor_TestData>d__126:MoveNext():bool:this
          11 ( 1.33% of base) : 171180.dasm - System.Drawing.Tests.RegionTests:Xor_InfiniteRegion_Success():this
           3 ( 0.41% of base) : 171268.dasm - System.Drawing.Tests.RegionTests:Complement_InfiniteAndWithIntersectRegion_Success():this
           3 ( 0.83% of base) : 292939.dasm - System.Drawing.Primitives.Tests.DataContractSerializerTests:DCS_RectangleF()
           3 ( 0.96% of base) : 292941.dasm - System.Drawing.Primitives.Tests.DataContractSerializerTests:DCS_SizeF()
           3 ( 0.31% of base) : 171166.dasm - System.Drawing.Tests.RegionTests:Transform_Infinity_Nop(float,float,int):this
           3 ( 0.44% of base) : 171197.dasm - System.Drawing.Tests.RegionTests:Intersect_InfiniteRegionWithSmallerRectangleF_Success():this
           3 ( 0.41% of base) : 171175.dasm - System.Drawing.Tests.RegionTests:Translate_Infinity_Nop():this
           3 ( 0.46% of base) : 171195.dasm - System.Drawing.Tests.RegionTests:Intersect_InfiniteRegionWithSmallerRectangle_Success():this

Top method improvements (bytes):
         -35 (-0.97% of base) : 59512.dasm - <Max_NullableFloat_TestData>d__35:MoveNext():bool:this
         -32 (-0.01% of base) : 145004.dasm - <Compare_Primitives_TestData>d__139:MoveNext():bool:this
         -31 (-0.28% of base) : 143847.dasm - <ToSingle_Object_TestData>d__102:MoveNext():bool:this
         -30 (-0.52% of base) : 209113.dasm - <get_Round_Digits_TestData>d__43:MoveNext():bool:this
         -27 (-0.36% of base) : 145183.dasm - <FromObject_TestData>d__9:MoveNext():bool:this
         -26 (-0.03% of base) : 144892.dasm - <ModObject_TestData>d__67:MoveNext():bool:this
         -26 (-0.69% of base) : 59644.dasm - <Min_NullableFloat_TestData>d__29:MoveNext():bool:this
         -10 (-0.34% of base) : 59488.dasm - <Max_Float_TestData>d__10:MoveNext():bool:this
         -10 (-0.03% of base) : 144803.dasm - <DivideObject_TestData>d__27:MoveNext():bool:this
          -9 (-0.02% of base) : 144974.dasm - <SubtractObject_TestData>d__109:MoveNext():bool:this
          -9 (-0.11% of base) : 334258.dasm - System.Tests.ValueTupleTests:TestEquals_GetHashCode()
          -8 (-0.18% of base) : 172391.dasm - <Translate_TestData>d__49:MoveNext():bool:this
          -8 (-1.51% of base) : 209519.dasm - System.Runtime.InteropServices.Tests.NativeMemoryTests:AlignedReallocTest(int):this
          -8 (-0.02% of base) : 144876.dasm - <MultiplyObject_Idempotent_TestData>d__60:MoveNext():bool:this
          -8 (-0.35% of base) : 83237.dasm - <ToString_TestData>d__23:MoveNext():bool:this
          -8 (-0.58% of base) : 83251.dasm - <ToStringRoundtrip_TestData>d__33:MoveNext():bool:this
          -8 (-0.12% of base) : 172377.dasm - <Scale_TestData>d__41:MoveNext():bool:this
          -8 (-0.12% of base) : 172384.dasm - <Shear_TestData>d__45:MoveNext():bool:this
          -8 (-0.25% of base) : 59619.dasm - <Min_Float_TestData>d__10:MoveNext():bool:this
          -7 (-0.35% of base) : 82814.dasm - <ToString_TestData>d__44:MoveNext():bool:this

Top method regressions (percentages):
          11 ( 1.33% of base) : 171269.dasm - System.Drawing.Tests.RegionTests:Complement_InfiniteRegion_Success():this
          11 ( 1.33% of base) : 171180.dasm - System.Drawing.Tests.RegionTests:Xor_InfiniteRegion_Success():this
           3 ( 0.96% of base) : 292941.dasm - System.Drawing.Primitives.Tests.DataContractSerializerTests:DCS_SizeF()
           3 ( 0.83% of base) : 292939.dasm - System.Drawing.Primitives.Tests.DataContractSerializerTests:DCS_RectangleF()
          11 ( 0.47% of base) : 173821.dasm - <Xor_TestData>d__126:MoveNext():bool:this
           3 ( 0.46% of base) : 171195.dasm - System.Drawing.Tests.RegionTests:Intersect_InfiniteRegionWithSmallerRectangle_Success():this
           3 ( 0.44% of base) : 171197.dasm - System.Drawing.Tests.RegionTests:Intersect_InfiniteRegionWithSmallerRectangleF_Success():this
           3 ( 0.41% of base) : 171268.dasm - System.Drawing.Tests.RegionTests:Complement_InfiniteAndWithIntersectRegion_Success():this
           3 ( 0.41% of base) : 171175.dasm - System.Drawing.Tests.RegionTests:Translate_Infinity_Nop():this
           3 ( 0.31% of base) : 171166.dasm - System.Drawing.Tests.RegionTests:Transform_Infinity_Nop(float,float,int):this
          11 ( 0.22% of base) : 173748.dasm - <Exclude_TestData>d__43:MoveNext():bool:this

Top method improvements (percentages):
          -1 (-3.12% of base) : 22084.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.Oneclass2operates.binary.onedynamicparam004.onedynamicparam004.Target:op_Addition(System.String,ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.Oneclass2operates.binary.onedynamicparam004.onedynamicparam004.Target):System.Object
          -1 (-2.08% of base) : 22005.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.Oneclass2operates.binary.oneparamdifftypesconv016.oneparamdifftypesconv016.Target:op_BitwiseAnd(ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.Oneclass2operates.binary.oneparamdifftypesconv016.oneparamdifftypesconv016.Base,ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.Oneclass2operates.binary.oneparamdifftypesconv016.oneparamdifftypesconv016.Target):System.Nullable`1[System.Single][]
          -4 (-1.72% of base) : 50467.dasm - System.Linq.Expressions.Tests.UnaryArithmeticNegateCheckedNullableTests:CheckUnaryArithmeticNegateCheckedNullableFloatTest(bool)
          -4 (-1.72% of base) : 50486.dasm - System.Linq.Expressions.Tests.UnaryArithmeticNegateNullableTests:CheckUnaryArithmeticNegateNullableFloatTest(bool)
          -4 (-1.72% of base) : 50608.dasm - System.Linq.Expressions.Tests.UnaryDecrementNullableTests:CheckDecrementFloatTest(bool)
          -4 (-1.72% of base) : 50630.dasm - System.Linq.Expressions.Tests.UnaryIncrementNullableTests:CheckIncrementFloatTest(bool)
          -4 (-1.72% of base) : 50772.dasm - System.Linq.Expressions.Tests.UnaryPlusNullableTests:CheckUnaryArithmeticUnaryPlusNullableFloatTest(bool)
          -1 (-1.61% of base) : 173850.dasm - <>c__DisplayClass16_0:<SetTabStops_NegativeInfinityInTabStops_ThrowsNotImplementedException>b__0():this
          -6 (-1.59% of base) : 305151.dasm - System.Linq.Tests.MaxTests:NullableSingleMaxRepeated():this
          -4 (-1.55% of base) : 47266.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToNullableFloatTest(bool)
          -4 (-1.55% of base) : 47267.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToIntTest(bool)
          -4 (-1.55% of base) : 47268.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToNullableIntTest(bool)
          -4 (-1.55% of base) : 47269.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToLongTest(bool)
          -4 (-1.55% of base) : 45694.dasm - System.Linq.Expressions.Tests.ConvertCheckedTests:ConvertCheckedNullableFloatToNullableUShortTest(bool)
          -4 (-1.55% of base) : 45731.dasm - System.Linq.Expressions.Tests.ConvertCheckedTests:ConvertCheckedNullableFloatToByteTest(bool)
          -4 (-1.55% of base) : 47264.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToNullableEnumLongTest(bool)
          -4 (-1.55% of base) : 47265.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToFloatTest(bool)
          -4 (-1.55% of base) : 47276.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToNullableUIntTest(bool)
          -4 (-1.55% of base) : 47277.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToULongTest(bool)
          -4 (-1.55% of base) : 47320.dasm - System.Linq.Expressions.Tests.ConvertTests:ConvertNullableFloatToNullableCharTest(bool)

285 total methods with Code Size differences (274 improved, 11 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------
