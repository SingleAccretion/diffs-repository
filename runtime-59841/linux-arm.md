## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3309792
Total bytes of diff: 2845234
Total bytes of delta: -464558 (-14.04% of base)
Total relative delta: -852.98
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          84 : 86094.dasm (57.53% of base)
          68 : 83697.dasm (35.79% of base)
          56 : 90676.dasm (7.63% of base)
          56 : 159233.dasm (7.63% of base)
          52 : 85737.dasm (12.62% of base)
          28 : 186433.dasm (3.52% of base)
          12 : 85534.dasm (2.24% of base)
          10 : 233283.dasm (23.81% of base)
           6 : 84987.dasm (1.20% of base)
           2 : 83666.dasm (3.57% of base)

Top file improvements (bytes):
       -2480 : 216837.dasm (-5.47% of base)
       -2420 : 206559.dasm (-5.58% of base)
       -1744 : 202904.dasm (-4.46% of base)
       -1676 : 206609.dasm (-4.43% of base)
       -1276 : 203598.dasm (-3.43% of base)
       -1252 : 208664.dasm (-3.26% of base)
       -1172 : 222421.dasm (-14.75% of base)
       -1132 : 204760.dasm (-20.12% of base)
       -1132 : 204769.dasm (-20.21% of base)
       -1132 : 204789.dasm (-20.23% of base)
       -1102 : 204715.dasm (-17.76% of base)
       -1102 : 204723.dasm (-17.93% of base)
       -1020 : 229480.dasm (-25.20% of base)
       -1020 : 229481.dasm (-25.71% of base)
       -1020 : 229476.dasm (-25.71% of base)
       -1020 : 229478.dasm (-25.71% of base)
       -1006 : 222442.dasm (-29.55% of base)
        -974 : 204218.dasm (-3.10% of base)
        -974 : 213714.dasm (-2.98% of base)
        -960 : 214223.dasm (-2.88% of base)

1760 total files with Code Size differences (1750 improved, 10 regressed), 3 unchanged.

Top method regressions (bytes):
          84 (57.53% of base) : 86094.dasm - ILGEN_CLASS:ILGEN_METHOD(short,ushort,ushort,int):float
          68 (35.79% of base) : 83697.dasm - ILGEN_939264028:main(System.String[]):int
          56 ( 7.63% of base) : 90676.dasm - testout1:Func_0_6_6_1_3():double
          56 ( 7.63% of base) : 159233.dasm - testout1:Func_0_6_6_1_3():double
          52 (12.62% of base) : 85737.dasm - ILGEN_0x19b572e2:Method_0x1a700c9c(double,byte):int
          28 ( 3.52% of base) : 186433.dasm - testout1:Func_0_4_2_3():double
          12 ( 2.24% of base) : 85534.dasm - ILGEN_0x1c24c9c8:Method_0x70ae6ea7(int,int,byte,int,int):int
          10 (23.81% of base) : 233283.dasm - JitTest.Test:Main():int
           6 ( 1.20% of base) : 84987.dasm - ILGEN_0xce8ea34:Method_0xdf08df47(short,double,ushort,int,ubyte):int
           2 ( 3.57% of base) : 83666.dasm - ILGEN_0x8485715d:Main():int

Top method improvements (bytes):
       -2480 (-5.47% of base) : 216837.dasm - lclfldrem:Main():int
       -2420 (-5.58% of base) : 206559.dasm - lclfldrem:Main():int
       -1744 (-4.46% of base) : 202904.dasm - lclflddiv:Main():int
       -1676 (-4.43% of base) : 206609.dasm - lclflddiv:Main():int
       -1276 (-3.43% of base) : 203598.dasm - lclfldmul:Main():int
       -1252 (-3.26% of base) : 208664.dasm - lclfldmul:Main():int
       -1172 (-14.75% of base) : 222421.dasm - BilinearTest:BilinearInterpol_Vector(System.Double[],System.Double[],double,double,System.Double[],double,double,double):System.Double[]:this
       -1132 (-20.12% of base) : 204760.dasm - <>c__DisplayClass5_0:<RenderMultiThreadedNoADT>b__1(int):this
       -1132 (-20.21% of base) : 204769.dasm - <>c__DisplayClass5_0:<RenderMultiThreadedNoADT>b__1(int):this
       -1132 (-20.23% of base) : 204789.dasm - <>c__DisplayClass5_0:<RenderMultiThreadedNoADT>b__1(int):this
       -1102 (-17.76% of base) : 204715.dasm - Algorithms.VectorDoubleRenderer:RenderSingleThreadedNoADT(float,float,float,float,float):this
       -1102 (-17.93% of base) : 204723.dasm - Algorithms.VectorDoubleStrictRenderer:RenderSingleThreadedNoADT(float,float,float,float,float):this
       -1020 (-25.20% of base) : 229480.dasm - GitHub_11816:TestStructManuallyInlined():float
       -1020 (-25.71% of base) : 229481.dasm - GitHub_11816:DoSomeWorkStructless(byref,byref)
       -1020 (-25.71% of base) : 229476.dasm - GitHub_11816:DoSomeWorkWithAStruct(byref,byref)
       -1020 (-25.71% of base) : 229478.dasm - GitHub_11816:DoSomeWorkWithAStructAggressiveInlining(byref,byref)
       -1006 (-29.55% of base) : 222442.dasm - VectorTest:Main():int
        -974 (-3.10% of base) : 204218.dasm - lclfldadd:Main():int
        -974 (-2.98% of base) : 213714.dasm - lclfldadd:Main():int
        -960 (-2.88% of base) : 214223.dasm - lclfldsub:Main():int

Top method regressions (percentages):
          84 (57.53% of base) : 86094.dasm - ILGEN_CLASS:ILGEN_METHOD(short,ushort,ushort,int):float
          68 (35.79% of base) : 83697.dasm - ILGEN_939264028:main(System.String[]):int
          10 (23.81% of base) : 233283.dasm - JitTest.Test:Main():int
          52 (12.62% of base) : 85737.dasm - ILGEN_0x19b572e2:Method_0x1a700c9c(double,byte):int
          56 ( 7.63% of base) : 90676.dasm - testout1:Func_0_6_6_1_3():double
          56 ( 7.63% of base) : 159233.dasm - testout1:Func_0_6_6_1_3():double
           2 ( 3.57% of base) : 83666.dasm - ILGEN_0x8485715d:Main():int
          28 ( 3.52% of base) : 186433.dasm - testout1:Func_0_4_2_3():double
          12 ( 2.24% of base) : 85534.dasm - ILGEN_0x1c24c9c8:Method_0x70ae6ea7(int,int,byte,int,int):int
           6 ( 1.20% of base) : 84987.dasm - ILGEN_0xce8ea34:Method_0xdf08df47(short,double,ushort,int,ubyte):int

Top method improvements (percentages):
        -162 (-93.10% of base) : 84360.dasm - ILGEN_941132142:main():int
         -62 (-91.18% of base) : 86795.dasm - ILGEN_0xb37e58f3:Method_0xf9cacde1():byte
        -504 (-90.97% of base) : 65189.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_58()
        -504 (-90.97% of base) : 65195.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmIntegerOneIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_64()
        -500 (-90.91% of base) : 65191.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullDecrementUnderInt32MaxValueCastToInt64IsFoldedCorrectly|18_60()
        -500 (-90.91% of base) : 65196.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmIntegerOneDecrementUnderInt32MaxValueCastToInt64IsFoldedCorrectly|18_65()
        -500 (-90.91% of base) : 65109.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullDecrementUnderInt32MaxValueCastToUInt64IsFoldedCorrectly|19_60()
        -500 (-90.91% of base) : 65114.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneDecrementUnderInt32MaxValueCastToUInt64IsFoldedCorrectly|19_65()
        -496 (-90.84% of base) : 65118.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullDecrementUnderUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_69()
        -496 (-90.84% of base) : 65121.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneDecrementUnderUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_72()
        -496 (-90.84% of base) : 65126.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_77()
        -496 (-90.84% of base) : 65208.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToInt64IsFoldedCorrectly|18_77()
        -496 (-90.84% of base) : 65192.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneIncrementAboveInt32MaxValueCastToInt64IsFoldedCorrectly|18_61()
        -496 (-90.84% of base) : 65904.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToInt64>g__ConfirmSingleOneDecrementUnderInt32MinValueCastToInt64IsFoldedCorrectly|10_57()
        -496 (-90.84% of base) : 65905.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToInt64>g__ConfirmSingleOneIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|10_58()
        -496 (-90.84% of base) : 65241.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmInt32MaxValueCastToInt64IsFoldedCorrectly|18_54()
        -496 (-90.84% of base) : 65103.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmInt32MaxValueCastToUInt64IsFoldedCorrectly|19_54()
        -496 (-90.84% of base) : 65110.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneIncrementAboveInt32MaxValueCastToUInt64IsFoldedCorrectly|19_61()
        -496 (-90.84% of base) : 65188.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_57()
        -496 (-90.84% of base) : 65200.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullDecrementUnderUInt32MaxValueCastToInt64IsFoldedCorrectly|18_69()

1760 total methods with Code Size differences (1750 improved, 10 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 13978
Total bytes of diff: 13370
Total bytes of delta: -608 (-4.35% of base)
Total relative delta: -1.03
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -54 : 82269.dasm (-6.01% of base)
         -40 : 79614.dasm (-6.41% of base)
         -40 : 80025.dasm (-5.88% of base)
         -40 : 80240.dasm (-6.73% of base)
         -40 : 80879.dasm (-5.90% of base)
         -40 : 80930.dasm (-2.70% of base)
         -40 : 79803.dasm (-4.99% of base)
         -40 : 79897.dasm (-7.46% of base)
         -40 : 80086.dasm (-5.90% of base)
         -38 : 82230.dasm (-3.17% of base)
         -22 : 82271.dasm (-1.75% of base)
         -22 : 80258.dasm (-6.25% of base)
         -20 : 80102.dasm (-4.41% of base)
         -20 : 79817.dasm (-5.68% of base)
         -20 : 79649.dasm (-3.56% of base)
         -20 : 80205.dasm (-5.81% of base)
         -20 : 80353.dasm (-7.19% of base)
         -20 : 81039.dasm (-5.99% of base)
         -16 : 75553.dasm (-6.61% of base)
         -16 : 82191.dasm (-0.98% of base)

20 total files with Code Size differences (20 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -54 (-6.01% of base) : 82269.dasm - System.TimeZoneInfo:ParseTimeOfDay(System.ReadOnlySpan`1[System.Char]):System.DateTime
         -40 (-6.41% of base) : 79614.dasm - System.Globalization.UmAlQuraCalendar:.cctor()
         -40 (-5.88% of base) : 80025.dasm - System.Globalization.KoreanLunisolarCalendar:.cctor()
         -40 (-6.73% of base) : 80240.dasm - System.Globalization.HebrewCalendar:.cctor()
         -40 (-5.90% of base) : 80879.dasm - System.Globalization.ChineseLunisolarCalendar:.cctor()
         -40 (-2.70% of base) : 80930.dasm - System.Globalization.CalendricalCalculationsHelper:.cctor()
         -40 (-4.99% of base) : 79803.dasm - System.Globalization.TaiwanLunisolarCalendar:.cctor()
         -40 (-7.46% of base) : 79897.dasm - System.Globalization.PersianCalendar:.cctor()
         -40 (-5.90% of base) : 80086.dasm - System.Globalization.JapaneseLunisolarCalendar:.cctor()
         -38 (-3.17% of base) : 82230.dasm - System.TimeZoneInfo:.cctor()
         -22 (-1.75% of base) : 82271.dasm - System.TimeZoneInfo:TZif_CreateAdjustmentRuleForPosixFormat(System.String,System.DateTime,System.TimeSpan):System.TimeZoneInfo+AdjustmentRule
         -22 (-6.25% of base) : 80258.dasm - System.Globalization.HebrewCalendar:GetDayOfYear(System.DateTime):int:this
         -20 (-4.41% of base) : 80102.dasm - System.Globalization.JapaneseCalendar:.cctor()
         -20 (-5.68% of base) : 79817.dasm - System.Globalization.TaiwanCalendar:.cctor()
         -20 (-3.56% of base) : 79649.dasm - System.Globalization.UmAlQuraCalendar:InitDateMapping():System.Globalization.UmAlQuraCalendar+DateMapping[]
         -20 (-5.81% of base) : 80205.dasm - System.Globalization.HijriCalendar:.cctor()
         -20 (-7.19% of base) : 80353.dasm - System.Globalization.EastAsianLunisolarCalendar:get_TwoDigitYearMax():int:this
         -20 (-5.99% of base) : 81039.dasm - HtmlEntities:InitializeLookupTable():System.Collections.Generic.Dictionary`2[System.UInt64, System.Char]
         -16 (-6.61% of base) : 75553.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(int):System.__Canon
         -16 (-0.98% of base) : 82191.dasm - StringSerializer:GetNextTransitionTimeValue():System.TimeZoneInfo+TransitionTime:this

Top method improvements (percentages):
         -40 (-7.46% of base) : 79897.dasm - System.Globalization.PersianCalendar:.cctor()
         -20 (-7.19% of base) : 80353.dasm - System.Globalization.EastAsianLunisolarCalendar:get_TwoDigitYearMax():int:this
         -40 (-6.73% of base) : 80240.dasm - System.Globalization.HebrewCalendar:.cctor()
         -16 (-6.61% of base) : 75553.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(int):System.__Canon
         -40 (-6.41% of base) : 79614.dasm - System.Globalization.UmAlQuraCalendar:.cctor()
         -22 (-6.25% of base) : 80258.dasm - System.Globalization.HebrewCalendar:GetDayOfYear(System.DateTime):int:this
         -54 (-6.01% of base) : 82269.dasm - System.TimeZoneInfo:ParseTimeOfDay(System.ReadOnlySpan`1[System.Char]):System.DateTime
         -20 (-5.99% of base) : 81039.dasm - HtmlEntities:InitializeLookupTable():System.Collections.Generic.Dictionary`2[System.UInt64, System.Char]
         -40 (-5.90% of base) : 80879.dasm - System.Globalization.ChineseLunisolarCalendar:.cctor()
         -40 (-5.90% of base) : 80086.dasm - System.Globalization.JapaneseLunisolarCalendar:.cctor()
         -40 (-5.88% of base) : 80025.dasm - System.Globalization.KoreanLunisolarCalendar:.cctor()
         -20 (-5.81% of base) : 80205.dasm - System.Globalization.HijriCalendar:.cctor()
         -20 (-5.68% of base) : 79817.dasm - System.Globalization.TaiwanCalendar:.cctor()
         -40 (-4.99% of base) : 79803.dasm - System.Globalization.TaiwanLunisolarCalendar:.cctor()
         -20 (-4.41% of base) : 80102.dasm - System.Globalization.JapaneseCalendar:.cctor()
         -20 (-3.56% of base) : 79649.dasm - System.Globalization.UmAlQuraCalendar:InitDateMapping():System.Globalization.UmAlQuraCalendar+DateMapping[]
         -38 (-3.17% of base) : 82230.dasm - System.TimeZoneInfo:.cctor()
         -40 (-2.70% of base) : 80930.dasm - System.Globalization.CalendricalCalculationsHelper:.cctor()
         -22 (-1.75% of base) : 82271.dasm - System.TimeZoneInfo:TZif_CreateAdjustmentRuleForPosixFormat(System.String,System.DateTime,System.TimeSpan):System.TimeZoneInfo+AdjustmentRule
         -16 (-0.98% of base) : 82191.dasm - StringSerializer:GetNextTransitionTimeValue():System.TimeZoneInfo+TransitionTime:this

20 total methods with Code Size differences (20 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 125800
Total bytes of diff: 113122
Total bytes of delta: -12678 (-10.08% of base)
Total relative delta: -30.87
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -224 : 89406.dasm (-7.25% of base)
        -224 : 89411.dasm (-4.02% of base)
        -224 : 89417.dasm (-2.51% of base)
        -200 : 89389.dasm (-6.18% of base)
        -200 : 89394.dasm (-3.46% of base)
        -200 : 89385.dasm (-6.24% of base)
        -200 : 89400.dasm (-2.17% of base)
        -200 : 175471.dasm (-17.12% of base)
        -184 : 89828.dasm (-36.22% of base)
        -184 : 89825.dasm (-36.22% of base)
        -182 : 89829.dasm (-35.00% of base)
        -182 : 89830.dasm (-34.21% of base)
        -182 : 89826.dasm (-35.00% of base)
        -170 : 89783.dasm (-39.91% of base)
        -170 : 89784.dasm (-39.91% of base)
        -170 : 89787.dasm (-39.91% of base)
        -170 : 89788.dasm (-37.78% of base)
        -170 : 89786.dasm (-39.91% of base)
        -156 : 89782.dasm (-39.20% of base)
        -156 : 89785.dasm (-39.20% of base)

171 total files with Code Size differences (171 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -224 (-7.25% of base) : 89406.dasm - System.SpanHelpers:LastIndexOf(byref,System.Numerics.Vector`1[Single],int):int
        -224 (-4.02% of base) : 89411.dasm - System.SpanHelpers:LastIndexOfAny(byref,System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],int):int
        -224 (-2.51% of base) : 89417.dasm - System.SpanHelpers:LastIndexOfAny(byref,System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],int):int
        -200 (-6.18% of base) : 89389.dasm - System.SpanHelpers:IndexOf(byref,System.Numerics.Vector`1[Single],int):int
        -200 (-3.46% of base) : 89394.dasm - System.SpanHelpers:IndexOfAny(byref,System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],int):int
        -200 (-6.24% of base) : 89385.dasm - System.SpanHelpers:Contains(byref,System.Numerics.Vector`1[Single],int):bool
        -200 (-2.17% of base) : 89400.dasm - System.SpanHelpers:IndexOfAny(byref,System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],int):int
        -200 (-17.12% of base) : 175471.dasm - System.Buffers.SequenceReader`1[Vector`1][System.Numerics.Vector`1[System.Single]]:AdvancePastAny(System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single],System.Numerics.Vector`1[Single]):long:this
        -184 (-36.22% of base) : 89828.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Int16],byref,byref)
        -184 (-36.22% of base) : 89825.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[UInt16],byref,byref)
        -182 (-35.00% of base) : 89829.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Int32],byref,byref)
        -182 (-34.21% of base) : 89830.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Single],byref,byref)
        -182 (-35.00% of base) : 89826.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[UInt32],byref,byref)
        -170 (-39.91% of base) : 89783.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt32],System.Numerics.Vector`1[UInt32]):System.Numerics.Vector`1[UInt16]
        -170 (-39.91% of base) : 89784.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt64],System.Numerics.Vector`1[UInt64]):System.Numerics.Vector`1[UInt32]
        -170 (-39.91% of base) : 89787.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int64],System.Numerics.Vector`1[Int64]):System.Numerics.Vector`1[Int32]
        -170 (-37.78% of base) : 89788.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Double],System.Numerics.Vector`1[Double]):System.Numerics.Vector`1[Single]
        -170 (-39.91% of base) : 89786.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int32],System.Numerics.Vector`1[Int32]):System.Numerics.Vector`1[Int16]
        -156 (-39.20% of base) : 89782.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):System.Numerics.Vector`1[Byte]
        -156 (-39.20% of base) : 89785.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):System.Numerics.Vector`1[SByte]

Top method improvements (percentages):
         -16 (-57.14% of base) : 143776.dasm - ErrorCollection:AddRevocationUnknown():this
         -16 (-53.33% of base) : 143771.dasm - ErrorCollection:ClearRevoked():this
         -30 (-46.88% of base) : 143773.dasm - ErrorCollection:HasCorruptRevocation():bool:this
         -16 (-42.11% of base) : 143772.dasm - ErrorCollection:IsRevoked():bool:this
        -170 (-39.91% of base) : 89783.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt32],System.Numerics.Vector`1[UInt32]):System.Numerics.Vector`1[UInt16]
        -170 (-39.91% of base) : 89784.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt64],System.Numerics.Vector`1[UInt64]):System.Numerics.Vector`1[UInt32]
        -170 (-39.91% of base) : 89787.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int64],System.Numerics.Vector`1[Int64]):System.Numerics.Vector`1[Int32]
        -170 (-39.91% of base) : 89786.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int32],System.Numerics.Vector`1[Int32]):System.Numerics.Vector`1[Int16]
        -156 (-39.20% of base) : 89782.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[UInt16],System.Numerics.Vector`1[UInt16]):System.Numerics.Vector`1[Byte]
        -156 (-39.20% of base) : 89785.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Int16],System.Numerics.Vector`1[Int16]):System.Numerics.Vector`1[SByte]
        -108 (-38.85% of base) : 143774.dasm - ErrorCollection:ClearRevocationUnknown():this
        -170 (-37.78% of base) : 89788.dasm - System.Numerics.Vector:Narrow(System.Numerics.Vector`1[Double],System.Numerics.Vector`1[Double]):System.Numerics.Vector`1[Single]
        -184 (-36.22% of base) : 89828.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Int16],byref,byref)
        -184 (-36.22% of base) : 89825.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[UInt16],byref,byref)
        -104 (-35.62% of base) : 143775.dasm - ErrorCollection:HasRevocationUnknown():bool:this
         -42 (-35.59% of base) : 90022.dasm - System.Numerics.Vector`1[Int32][System.Int32]:.ctor(int):this
         -42 (-35.59% of base) : 89999.dasm - System.Numerics.Vector`1[Int16][System.Int16]:.ctor(short):this
        -182 (-35.00% of base) : 89829.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Int32],byref,byref)
        -182 (-35.00% of base) : 89826.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[UInt32],byref,byref)
        -182 (-34.21% of base) : 89830.dasm - System.Numerics.Vector:Widen(System.Numerics.Vector`1[Single],byref,byref)

171 total methods with Code Size differences (171 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1963688
Total bytes of diff: 1875004
Total bytes of delta: -88684 (-4.52% of base)
Total relative delta: -130.61
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          62 : 139624.dasm (9.09% of base)
          32 : 240164.dasm (15.24% of base)
           6 : 139435.dasm (0.64% of base)

Top file improvements (bytes):
       -1458 : 51925.dasm (-14.51% of base)
       -1102 : 51924.dasm (-20.38% of base)
        -912 : 51932.dasm (-7.91% of base)
        -822 : 51928.dasm (-12.24% of base)
        -788 : 51929.dasm (-11.37% of base)
        -526 : 51934.dasm (-7.08% of base)
        -512 : 51938.dasm (-9.28% of base)
        -480 : 51940.dasm (-5.48% of base)
        -468 : 231622.dasm (-9.34% of base)
        -466 : 231625.dasm (-9.85% of base)
        -464 : 51888.dasm (-5.56% of base)
        -444 : 51936.dasm (-6.03% of base)
        -418 : 290175.dasm (-6.98% of base)
        -394 : 313121.dasm (-25.32% of base)
        -342 : 51931.dasm (-7.75% of base)
        -318 : 51927.dasm (-20.76% of base)
        -292 : 51910.dasm (-7.44% of base)
        -288 : 51890.dasm (-1.90% of base)
        -286 : 51737.dasm (-4.65% of base)
        -272 : 188635.dasm (-11.14% of base)

1338 total files with Code Size differences (1335 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
          62 ( 9.09% of base) : 139624.dasm - System.Threading.Tasks.Tests.WaitAllAny.TaskWaitAllAnyTest:RealRun():this
          32 (15.24% of base) : 240164.dasm - shrink@868-4:GenerateNext(byref):int:this
           6 ( 0.64% of base) : 139435.dasm - System.Threading.Tasks.Tests.CancelWait.TaskCancelWaitTest:RealRun():this

Top method improvements (bytes):
       -1458 (-14.51% of base) : 51925.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTimeOffset_VariousSystemTimeZones()
       -1102 (-20.38% of base) : 51924.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTimeOffset_NearMinMaxValue()
        -912 (-7.91% of base) : 51932.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToSystem()
        -822 (-12.24% of base) : 51928.dasm - System.Tests.TimeZoneInfoTests:ConverTime_DateTime_VariousSystemTimeZonesTest()
        -788 (-11.37% of base) : 51929.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_PerthRules()
        -526 (-7.08% of base) : 51934.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToUtc()
        -512 (-9.28% of base) : 51938.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_Tonga()
        -480 (-5.48% of base) : 51940.dasm - System.Tests.TimeZoneInfoTests:GetAmbiguousTimeOffsets_Invalid()
        -468 (-9.34% of base) : 231622.dasm - <DateDiff_DateInterval_TestData>d__9:MoveNext():bool:this
        -466 (-9.85% of base) : 231625.dasm - <DateDiff_StringInterval_TestData>d__11:MoveNext():bool:this
        -464 (-5.56% of base) : 51888.dasm - System.Tests.TimeZoneInfoTests:GetAmbiguousTimeOffsets_LocalAmbiguousOffsets()
        -444 (-6.03% of base) : 51936.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_MiscUtc()
        -418 (-6.98% of base) : 290175.dasm - <AddMonths_TestData>d__0:MoveNext():bool:this
        -394 (-25.32% of base) : 313121.dasm - <<ResolutionsWaitingOnQueue_ResolutionStartCalledBeforeEnqueued>b__2>d:MoveNext():this
        -342 (-7.75% of base) : 51931.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_UtcToLocal()
        -318 (-20.76% of base) : 51927.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_NearMinAndMaxValue()
        -292 (-7.44% of base) : 51910.dasm - System.Tests.TimeZoneInfoTests:CreateCustomTimeZone_InvalidTimeZone()
        -288 (-1.90% of base) : 51890.dasm - System.Tests.TimeZoneInfoTests:IsInvalidTime()
        -286 (-4.65% of base) : 51737.dasm - System.Tests.TimeOnlyTests:AddTest()
        -272 (-11.14% of base) : 188635.dasm - <WaitForSecureConnection>d__47:MoveNext():this

Top method regressions (percentages):
          32 (15.24% of base) : 240164.dasm - shrink@868-4:GenerateNext(byref):int:this
          62 ( 9.09% of base) : 139624.dasm - System.Threading.Tasks.Tests.WaitAllAny.TaskWaitAllAnyTest:RealRun():this
           6 ( 0.64% of base) : 139435.dasm - System.Threading.Tasks.Tests.CancelWait.TaskCancelWaitTest:RealRun():this

Top method improvements (percentages):
         -20 (-83.33% of base) : 99851.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(int):this
         -20 (-83.33% of base) : 99852.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(double):this
         -20 (-83.33% of base) : 99854.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(long):this
         -20 (-83.33% of base) : 99857.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(ubyte):this
         -20 (-83.33% of base) : 99858.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(short):this
         -20 (-83.33% of base) : 99859.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(int):this
         -20 (-83.33% of base) : 99860.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(double):this
         -20 (-83.33% of base) : 99862.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(long):this
         -20 (-83.33% of base) : 99848.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.__Canon):this
         -20 (-83.33% of base) : 99849.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(ubyte):this
         -20 (-83.33% of base) : 99850.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(short):this
         -20 (-62.50% of base) : 99853.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.Numerics.Vector`1[Single]):this
         -20 (-62.50% of base) : 99861.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(System.Numerics.Vector`1[Single]):this
        -210 (-61.40% of base) : 279346.dasm - <>c__DisplayClass1_0:<Timer_Change_DueTime_OutOfRange_Throws>b__2():System.Object:this
        -210 (-61.40% of base) : 279351.dasm - <>c__DisplayClass2_0:<Timer_Change_Period_OutOfRange_Throws>b__2():System.Object:this
        -194 (-58.79% of base) : 279357.dasm - <>c__DisplayClass3_0:<Timer_Change_AfterDispose_Throws>b__3():System.Object:this
        -200 (-58.48% of base) : 279348.dasm - <>c__DisplayClass1_0:<Timer_Change_DueTime_OutOfRange_Throws>b__4():System.Object:this
        -200 (-58.48% of base) : 279353.dasm - <>c__DisplayClass2_0:<Timer_Change_Period_OutOfRange_Throws>b__4():System.Object:this
        -124 (-53.45% of base) : 140876.dasm - <>c__DisplayClass13_0:<ConfigureAwait_TimeoutOrCanceled_Throws>b__1():System.Threading.Tasks.Task:this
        -124 (-53.45% of base) : 140879.dasm - <>c__DisplayClass13_0:<ConfigureAwait_TimeoutOrCanceled_Throws>b__4():System.Threading.Tasks.Task:this

1338 total methods with Code Size differences (1335 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

