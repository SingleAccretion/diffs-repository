## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 9863
Total bytes of diff: 9161
Total bytes of delta: -702 (-7.12% of base)
Total relative delta: -0.54
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -219 : 1063.dasm (-11.35% of base)
        -177 : 10766.dasm (-18.73% of base)
         -78 : 5749.dasm (-4.49% of base)
         -75 : 8915.dasm (-3.01% of base)
         -75 : 13468.dasm (-4.91% of base)
         -62 : 13479.dasm (-7.97% of base)
         -16 : 4099.dasm (-3.51% of base)

7 total files with Code Size differences (7 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -219 (-11.35% of base) : 1063.dasm - MicroBenchmarks.Serializers.DataGenerator:CreateMyEventsListerItem():MicroBenchmarks.Serializers.MyEventsListerItem
        -177 (-18.73% of base) : 10766.dasm - MicroBenchmarks.Serializers.DataGenerator:CreateDateTimeArray(int):System.DateTime[]
         -78 (-4.49% of base) : 5749.dasm - System.TimeZoneInfo:CreateAdjustmentRuleFromTimeZoneInformation(byref,System.DateTime,System.DateTime,int):AdjustmentRule
         -75 (-3.01% of base) : 8915.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeIso(Newtonsoft.Json.Utilities.StringReference,int,byref):bool
         -75 (-4.91% of base) : 13468.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
         -62 (-7.97% of base) : 13479.dasm - Microsoft.Extensions.Caching.Memory.Tests.MemoryCacheTests:AddThenRemove_AbsoluteExpiration():this
         -16 (-3.51% of base) : 4099.dasm - System.Threading.PortableThreadPool:AdjustMaxWorkersActive():this

Top method improvements (percentages):
        -177 (-18.73% of base) : 10766.dasm - MicroBenchmarks.Serializers.DataGenerator:CreateDateTimeArray(int):System.DateTime[]
        -219 (-11.35% of base) : 1063.dasm - MicroBenchmarks.Serializers.DataGenerator:CreateMyEventsListerItem():MicroBenchmarks.Serializers.MyEventsListerItem
         -62 (-7.97% of base) : 13479.dasm - Microsoft.Extensions.Caching.Memory.Tests.MemoryCacheTests:AddThenRemove_AbsoluteExpiration():this
         -75 (-4.91% of base) : 13468.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
         -78 (-4.49% of base) : 5749.dasm - System.TimeZoneInfo:CreateAdjustmentRuleFromTimeZoneInformation(byref,System.DateTime,System.DateTime,int):AdjustmentRule
         -16 (-3.51% of base) : 4099.dasm - System.Threading.PortableThreadPool:AdjustMaxWorkersActive():this
         -75 (-3.01% of base) : 8915.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeIso(Newtonsoft.Json.Utilities.StringReference,int,byref):bool

7 total methods with Code Size differences (7 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2655558
Total bytes of diff: 2277643
Total bytes of delta: -377915 (-14.23% of base)
Total relative delta: -849.82
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         143 : 86759.dasm (130.00% of base)
          62 : 84711.dasm (30.24% of base)
          13 : 84742.dasm (3.71% of base)
          12 : 171300.dasm (1.36% of base)
          12 : 197497.dasm (1.36% of base)
           7 : 86575.dasm (15.91% of base)
           3 : 84757.dasm (0.69% of base)

Top file improvements (bytes):
       -3097 : 196710.dasm (-8.94% of base)
       -3077 : 206839.dasm (-8.82% of base)
       -2272 : 196637.dasm (-7.77% of base)
       -2252 : 196647.dasm (-7.64% of base)
       -1730 : 206840.dasm (-6.42% of base)
       -1730 : 196746.dasm (-6.46% of base)
       -1684 : 196674.dasm (-6.04% of base)
       -1680 : 206838.dasm (-5.96% of base)
       -1493 : 206837.dasm (-5.93% of base)
       -1476 : 196593.dasm (-5.86% of base)
       -1138 : 149729.dasm (-78.92% of base)
        -879 : 177513.dasm (-0.57% of base)
        -768 : 177396.dasm (-0.49% of base)
        -768 : 177259.dasm (-0.49% of base)
        -721 : 177456.dasm (-0.44% of base)
        -721 : 177573.dasm (-0.44% of base)
        -717 : 177533.dasm (-0.47% of base)
        -587 : 177356.dasm (-0.46% of base)
        -564 : 177335.dasm (-0.43% of base)
        -550 : 177553.dasm (-0.38% of base)

1474 total files with Code Size differences (1467 improved, 7 regressed), 0 unchanged.

Top method regressions (bytes):
         143 (130.00% of base) : 86759.dasm - ILGEN_CLASS:ILGEN_METHOD(short,ushort,ushort,int):float
          62 (30.24% of base) : 84711.dasm - ILGEN_939264028:main(System.String[]):int
          13 ( 3.71% of base) : 84742.dasm - ILGEN_0xce8ea34:Method_0xdf08df47(short,double,ushort,int,ubyte):int
          12 ( 1.36% of base) : 171300.dasm - testout1:Func_0_1_3_4():double
          12 ( 1.36% of base) : 197497.dasm - testout1:Func_0_1_3_4():double
           7 (15.91% of base) : 86575.dasm - ILGEN_0x8485715d:Main():int
           3 ( 0.69% of base) : 84757.dasm - ILGEN_0x1c24c9c8:Method_0x70ae6ea7(int,int,byte,int,int):int

Top method improvements (bytes):
       -3097 (-8.94% of base) : 196710.dasm - lclfldrem:Main():int
       -3077 (-8.82% of base) : 206839.dasm - lclfldrem:Main():int
       -2272 (-7.77% of base) : 196637.dasm - lclflddiv:Main():int
       -2252 (-7.64% of base) : 196647.dasm - lclflddiv:Main():int
       -1730 (-6.42% of base) : 206840.dasm - lclfldsub:Main():int
       -1730 (-6.46% of base) : 196746.dasm - lclfldsub:Main():int
       -1684 (-6.04% of base) : 196674.dasm - lclfldmul:Main():int
       -1680 (-5.96% of base) : 206838.dasm - lclfldmul:Main():int
       -1493 (-5.93% of base) : 206837.dasm - lclfldadd:Main():int
       -1476 (-5.86% of base) : 196593.dasm - lclfldadd:Main():int
       -1138 (-78.92% of base) : 149729.dasm - testout1:Func_0_4_1_1_3():int
        -879 (-0.57% of base) : 177513.dasm - r4rem:Main():int
        -768 (-0.49% of base) : 177396.dasm - u8div:Main():int
        -768 (-0.49% of base) : 177259.dasm - i8div:Main():int
        -721 (-0.44% of base) : 177456.dasm - i8rem:Main():int
        -721 (-0.44% of base) : 177573.dasm - u8rem:Main():int
        -717 (-0.47% of base) : 177533.dasm - r8rem:Main():int
        -587 (-0.46% of base) : 177356.dasm - r8div:Main():int
        -564 (-0.43% of base) : 177335.dasm - r4div:Main():int
        -550 (-0.38% of base) : 177553.dasm - u4rem:Main():int

Top method regressions (percentages):
         143 (130.00% of base) : 86759.dasm - ILGEN_CLASS:ILGEN_METHOD(short,ushort,ushort,int):float
          62 (30.24% of base) : 84711.dasm - ILGEN_939264028:main(System.String[]):int
           7 (15.91% of base) : 86575.dasm - ILGEN_0x8485715d:Main():int
          13 ( 3.71% of base) : 84742.dasm - ILGEN_0xce8ea34:Method_0xdf08df47(short,double,ushort,int,ubyte):int
          12 ( 1.36% of base) : 171300.dasm - testout1:Func_0_1_3_4():double
          12 ( 1.36% of base) : 197497.dasm - testout1:Func_0_1_3_4():double
           3 ( 0.69% of base) : 84757.dasm - ILGEN_0x1c24c9c8:Method_0x70ae6ea7(int,int,byte,int,int):int

Top method improvements (percentages):
        -150 (-93.75% of base) : 86217.dasm - ILGEN_941132142:main():int
        -432 (-91.53% of base) : 3762.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_77()
        -432 (-91.53% of base) : 3763.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_78()
        -432 (-91.53% of base) : 3843.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneIncrementAboveInt64MinValueCastToInt64IsFoldedCorrectly|18_76()
        -432 (-91.53% of base) : 3844.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToInt64IsFoldedCorrectly|18_77()
        -429 (-91.47% of base) : 3894.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmIntegerOneDecrementUnderSByteMinValueCastToInt64IsFoldedCorrectly|18_15()
        -429 (-91.47% of base) : 3855.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmInt16MinValueCastToInt64IsFoldedCorrectly|18_32()
        -429 (-91.47% of base) : 3857.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneDecrementUnderInt16MinValueCastToInt64IsFoldedCorrectly|18_34()
        -429 (-91.47% of base) : 3858.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullDecrementUnderInt16MinValueCastToInt64IsFoldedCorrectly|18_35()
        -429 (-91.47% of base) : 3859.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneIncrementAboveInt16MinValueCastToInt64IsFoldedCorrectly|18_36()
        -429 (-91.47% of base) : 3823.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullDecrementUnderInt32MinValueCastToInt64IsFoldedCorrectly|18_56()
        -429 (-91.47% of base) : 3824.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_57()
        -429 (-91.47% of base) : 3825.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_58()
        -429 (-91.47% of base) : 3887.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneFullDecrementUnderSByteMinValueCastToInt64IsFoldedCorrectly|18_8()
        -429 (-91.47% of base) : 4556.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToInt64>g__ConfirmIntegerOneDecrementUnderSByteMinValueCastToInt64IsFoldedCorrectly|10_17()
        -429 (-91.47% of base) : 3830.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmIntegerOneDecrementUnderInt32MinValueCastToInt64IsFoldedCorrectly|18_63()
        -429 (-91.47% of base) : 3831.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmIntegerOneIncrementAboveInt32MinValueCastToInt64IsFoldedCorrectly|18_64()
        -429 (-91.47% of base) : 3876.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmInt32MinValueCastToInt64IsFoldedCorrectly|18_53()
        -429 (-91.47% of base) : 3878.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToInt64>g__ConfirmDoubleOneDecrementUnderInt32MinValueCastToInt64IsFoldedCorrectly|18_55()
        -429 (-91.47% of base) : 4411.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_68()

1474 total methods with Code Size differences (1467 improved, 7 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 153
Total bytes of diff: 145
Total bytes of delta: -8 (-5.23% of base)
Total relative delta: -0.05
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 57642.dasm (-5.23% of base)

1 total files with Code Size differences (1 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -8 (-5.23% of base) : 57642.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(int):System.__Canon

Top method improvements (percentages):
          -8 (-5.23% of base) : 57642.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(int):System.__Canon

1 total methods with Code Size differences (1 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 10123
Total bytes of diff: 9569
Total bytes of delta: -554 (-5.47% of base)
Total relative delta: -0.62
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -84 : 208284.dasm (-8.71% of base)
         -76 : 105996.dasm (-4.77% of base)
         -76 : 167889.dasm (-4.85% of base)
         -76 : 105995.dasm (-3.41% of base)
         -76 : 167888.dasm (-3.48% of base)
         -56 : 83352.dasm (-20.36% of base)
         -55 : 167890.dasm (-8.40% of base)
         -55 : 105997.dasm (-8.40% of base)

8 total files with Code Size differences (8 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -84 (-8.71% of base) : 208284.dasm - <WaitForServerToCloseConnectionAsync>d__66:MoveNext():this
         -76 (-4.77% of base) : 105996.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
         -76 (-4.85% of base) : 167889.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(System.String,byref):bool
         -76 (-3.41% of base) : 105995.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeIso(Newtonsoft.Json.Utilities.StringReference,int,byref):bool
         -76 (-3.48% of base) : 167888.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:TryParseDateTimeIso(System.String,int,byref):bool
         -56 (-20.36% of base) : 83352.dasm - PEFile.PEHeader:TimeDateStampToDate(int):System.DateTime
         -55 (-8.40% of base) : 167890.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:CreateDateTime(Newtonsoft.Json.Bson.Utilities.DateTimeParser):System.DateTime
         -55 (-8.40% of base) : 105997.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:CreateDateTime(Newtonsoft.Json.Utilities.DateTimeParser):System.DateTime

Top method improvements (percentages):
         -56 (-20.36% of base) : 83352.dasm - PEFile.PEHeader:TimeDateStampToDate(int):System.DateTime
         -84 (-8.71% of base) : 208284.dasm - <WaitForServerToCloseConnectionAsync>d__66:MoveNext():this
         -55 (-8.40% of base) : 167890.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:CreateDateTime(Newtonsoft.Json.Bson.Utilities.DateTimeParser):System.DateTime
         -55 (-8.40% of base) : 105997.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:CreateDateTime(Newtonsoft.Json.Utilities.DateTimeParser):System.DateTime
         -76 (-4.85% of base) : 167889.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(System.String,byref):bool
         -76 (-4.77% of base) : 105996.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeOffsetIso(Newtonsoft.Json.Utilities.StringReference,byref):bool
         -76 (-3.48% of base) : 167888.dasm - Newtonsoft.Json.Bson.Utilities.DateTimeUtils:TryParseDateTimeIso(System.String,int,byref):bool
         -76 (-3.41% of base) : 105995.dasm - Newtonsoft.Json.Utilities.DateTimeUtils:TryParseDateTimeIso(Newtonsoft.Json.Utilities.StringReference,int,byref):bool

8 total methods with Code Size differences (8 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 654595
Total bytes of diff: 603799
Total bytes of delta: -50796 (-7.76% of base)
Total relative delta: -92.98
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -988 : 69751.dasm (-19.96% of base)
        -720 : 133212.dasm (-18.93% of base)
        -720 : 133207.dasm (-17.92% of base)
        -604 : 69752.dasm (-9.82% of base)
        -507 : 69755.dasm (-8.49% of base)
        -478 : 69563.dasm (-8.23% of base)
        -397 : 69754.dasm (-23.93% of base)
        -361 : 69759.dasm (-3.45% of base)
        -294 : 133199.dasm (-2.42% of base)
        -290 : 203938.dasm (-11.93% of base)
        -261 : 318064.dasm (-8.90% of base)
        -249 : 318076.dasm (-7.13% of base)
        -248 : 299662.dasm (-19.18% of base)
        -247 : 69756.dasm (-4.12% of base)
        -240 : 204135.dasm (-6.23% of base)
        -222 : 164066.dasm (-13.07% of base)
        -222 : 160549.dasm (-13.07% of base)
        -214 : 204625.dasm (-7.44% of base)
        -198 : 204631.dasm (-12.84% of base)
        -198 : 204630.dasm (-9.67% of base)

569 total files with Code Size differences (569 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -988 (-19.96% of base) : 69751.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTimeOffset_NearMinMaxValue()
        -720 (-18.93% of base) : 133212.dasm - <DateDiff_StringInterval_TestData>d__11:MoveNext():bool:this
        -720 (-17.92% of base) : 133207.dasm - <DateDiff_DateInterval_TestData>d__9:MoveNext():bool:this
        -604 (-9.82% of base) : 69752.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTimeOffset_VariousSystemTimeZones()
        -507 (-8.49% of base) : 69755.dasm - System.Tests.TimeZoneInfoTests:ConverTime_DateTime_VariousSystemTimeZonesTest()
        -478 (-8.23% of base) : 69563.dasm - System.Tests.TimeOnlyTests:AddTest()
        -397 (-23.93% of base) : 69754.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_NearMinAndMaxValue()
        -361 (-3.45% of base) : 69759.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_LocalToSystem()
        -294 (-2.42% of base) : 133199.dasm - <DateAdd_StringInterval_TestData>d__6:MoveNext():bool:this
        -290 (-11.93% of base) : 203938.dasm - System.Security.Cryptography.X509Certificates.Tests.DynamicChainTests:BuildInvalidSignatureTwice(int,int,int)
        -261 (-8.90% of base) : 318064.dasm - <TimedExpirationAsync>d__0:MoveNext():this
        -249 (-7.13% of base) : 318076.dasm - <TestCacheShrink>d__2:MoveNext():this
        -248 (-19.18% of base) : 299662.dasm - <<ResolutionsWaitingOnQueue_ResolutionStartCalledBeforeEnqueued>b__2>d:MoveNext():this
        -247 (-4.12% of base) : 69756.dasm - System.Tests.TimeZoneInfoTests:ConvertTime_DateTime_PerthRules()
        -240 (-6.23% of base) : 204135.dasm - System.Security.Cryptography.X509Certificates.Tests.CertificateCreation.CertificateRequestUsageTests:CheckTimeNested()
        -222 (-13.07% of base) : 164066.dasm - System.IO.Tests.FileInfo_GetSetTimes:BirthTimeIsNotNewerThanLowestOfAccessModifiedTimes():this
        -222 (-13.07% of base) : 160549.dasm - System.IO.Tests.FileInfo_GetSetTimes:BirthTimeIsNotNewerThanLowestOfAccessModifiedTimes():this
        -214 (-7.44% of base) : 204625.dasm - <>c__DisplayClass20_0:<RevokeEndEntity_RootUnrelatedOcsp>b__0(System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.Tests.ChainHolder,System.Security.Cryptography.X509Certificates.Tests.Common.RevocationResponder):this
        -198 (-12.84% of base) : 204631.dasm - <>c__DisplayClass24_0:<RevokeEndEntity_PolicyErrors_NotTimeValid>b__0(System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.Tests.ChainHolder,System.Security.Cryptography.X509Certificates.Tests.Common.RevocationResponder):this
        -198 (-9.67% of base) : 204630.dasm - <>c__DisplayClass23_0:<RevokeIntermediate_PolicyErrors_NotTimeValid>b__0(System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.Tests.Common.CertificateAuthority,System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.Tests.ChainHolder,System.Security.Cryptography.X509Certificates.Tests.Common.RevocationResponder):this

Top method improvements (percentages):
         -12 (-92.31% of base) : 34690.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(short):this
         -12 (-92.31% of base) : 34691.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(int):this
         -12 (-92.31% of base) : 34689.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(ubyte):this
         -12 (-80.00% of base) : 34681.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(ubyte):this
         -12 (-80.00% of base) : 34682.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(short):this
         -12 (-80.00% of base) : 34683.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(int):this
         -12 (-80.00% of base) : 34692.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(double):this
         -12 (-80.00% of base) : 34693.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(System.Numerics.Vector`1[Single]):this
         -12 (-80.00% of base) : 34694.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(long):this
         -12 (-80.00% of base) : 34684.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(double):this
         -12 (-80.00% of base) : 34685.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.Numerics.Vector`1[Single]):this
         -12 (-80.00% of base) : 34686.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(long):this
         -19 (-73.08% of base) : 34680.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.__Canon):this
        -155 (-53.82% of base) : 336547.dasm - <>c__DisplayClass1_0:<Timer_Change_DueTime_OutOfRange_Throws>b__4():System.Object:this
        -155 (-53.82% of base) : 336552.dasm - <>c__DisplayClass2_0:<Timer_Change_Period_OutOfRange_Throws>b__4():System.Object:this
        -152 (-53.33% of base) : 336545.dasm - <>c__DisplayClass1_0:<Timer_Change_DueTime_OutOfRange_Throws>b__2():System.Object:this
        -152 (-53.33% of base) : 336550.dasm - <>c__DisplayClass2_0:<Timer_Change_Period_OutOfRange_Throws>b__2():System.Object:this
        -138 (-50.92% of base) : 336556.dasm - <>c__DisplayClass3_0:<Timer_Change_AfterDispose_Throws>b__3():System.Object:this
         -65 (-45.45% of base) : 265303.dasm - <>c__DisplayClass11_0:<Test4_Dispose>b__15():System.Object:this
         -65 (-44.83% of base) : 265295.dasm - <>c__DisplayClass11_0:<Test4_Dispose>b__7():System.Object:this

569 total methods with Code Size differences (569 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

