## aspnet.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 12349
Total bytes of diff: 12264
Total bytes of delta: -85 (-0.69% of base)
Total relative delta: -0.12
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -17 : 39203.dasm (-0.74% of base)
         -17 : 35164.dasm (-10.12% of base)
         -17 : 35161.dasm (-0.45% of base)
         -17 : 35136.dasm (-0.74% of base)
         -17 : 39197.dasm (-0.44% of base)

5 total files with Code Size differences (5 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -17 (-0.74% of base) : 39203.dasm - CustomAttribute:IsCustomAttributeDefined(RuntimeModule,int,RuntimeType,int,bool):bool
         -17 (-10.12% of base) : 35164.dasm - ModuleHandle:ResolveMethodHandle(int):RuntimeMethodHandle:this
         -17 (-0.45% of base) : 35161.dasm - CustomAttribute:AddCustomAttributes(byref,RuntimeModule,int,RuntimeType,bool,ListBuilder`1)
         -17 (-0.74% of base) : 35136.dasm - CustomAttribute:IsCustomAttributeDefined(RuntimeModule,int,RuntimeType,int,bool):bool
         -17 (-0.44% of base) : 39197.dasm - CustomAttribute:AddCustomAttributes(byref,RuntimeModule,int,RuntimeType,bool,ListBuilder`1)

Top method improvements (percentages):
         -17 (-10.12% of base) : 35164.dasm - ModuleHandle:ResolveMethodHandle(int):RuntimeMethodHandle:this
         -17 (-0.74% of base) : 39203.dasm - CustomAttribute:IsCustomAttributeDefined(RuntimeModule,int,RuntimeType,int,bool):bool
         -17 (-0.74% of base) : 35136.dasm - CustomAttribute:IsCustomAttributeDefined(RuntimeModule,int,RuntimeType,int,bool):bool
         -17 (-0.45% of base) : 35161.dasm - CustomAttribute:AddCustomAttributes(byref,RuntimeModule,int,RuntimeType,bool,ListBuilder`1)
         -17 (-0.44% of base) : 39197.dasm - CustomAttribute:AddCustomAttributes(byref,RuntimeModule,int,RuntimeType,bool,ListBuilder`1)

5 total methods with Code Size differences (5 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 805047
Total bytes of diff: 460318
Total bytes of delta: -344729 (-42.82% of base)
Total relative delta: -647.32
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          19 : 86762.dasm (38.78% of base)
          13 : 149837.dasm (3.04% of base)
          10 : 86380.dasm (2.80% of base)
           9 : 86787.dasm (8.82% of base)
           7 : 86589.dasm (15.91% of base)
           4 : 152295.dasm (0.41% of base)
           4 : 149771.dasm (0.41% of base)
           3 : 150180.dasm (0.26% of base)
           3 : 152331.dasm (1.01% of base)
           1 : 152514.dasm (0.27% of base)
           1 : 150100.dasm (0.27% of base)

Top file improvements (bytes):
        -515 : 4448.dasm (-91.80% of base)
        -515 : 4449.dasm (-91.80% of base)
        -515 : 4450.dasm (-91.80% of base)
        -515 : 4451.dasm (-91.80% of base)
        -515 : 4453.dasm (-91.80% of base)
        -515 : 4455.dasm (-91.80% of base)
        -515 : 4456.dasm (-91.80% of base)
        -515 : 3752.dasm (-91.80% of base)
        -515 : 3743.dasm (-91.80% of base)
        -515 : 3749.dasm (-91.80% of base)
        -515 : 3751.dasm (-91.80% of base)
        -515 : 4457.dasm (-91.80% of base)
        -515 : 4459.dasm (-91.80% of base)
        -515 : 3745.dasm (-91.80% of base)
        -515 : 4446.dasm (-91.80% of base)
        -515 : 3741.dasm (-91.80% of base)
        -515 : 3747.dasm (-91.80% of base)
        -515 : 3748.dasm (-91.80% of base)
        -515 : 4396.dasm (-91.80% of base)
        -515 : 4398.dasm (-91.80% of base)

1051 total files with Code Size differences (1040 improved, 11 regressed), 0 unchanged.

Top method regressions (bytes):
          19 (38.78% of base) : 86762.dasm - C:M(bool,short,short,int):short
          13 ( 3.04% of base) : 149837.dasm - testout1:Func_0_4_3_1_6():long
          10 ( 2.80% of base) : 86380.dasm - ILGEN_0x58f32e86:Method_0x5d38(int):int
           9 ( 8.82% of base) : 86787.dasm - ILGEN_CLASS:ILGEN_METHOD(double,ushort,int):bool
           7 (15.91% of base) : 86589.dasm - ILGEN_0x8485715d:Main():int
           4 ( 0.41% of base) : 152295.dasm - testout1:Func_0_3_6_6_5():long
           4 ( 0.41% of base) : 149771.dasm - testout1:Func_0_3_6_6_5():long
           3 ( 0.26% of base) : 150180.dasm - testout1:Func_0_6_1_6_4():float
           3 ( 1.01% of base) : 152331.dasm - testout1:Func_0_4_3_1_6():long
           1 ( 0.27% of base) : 152514.dasm - testout1:Func_0_5_4_4_1():double
           1 ( 0.27% of base) : 150100.dasm - testout1:Func_0_5_4_4_1():double

Top method improvements (bytes):
        -515 (-91.80% of base) : 4448.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_68()
        -515 (-91.80% of base) : 4449.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneFullIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_69()
        -515 (-91.80% of base) : 4450.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneDecrementUnderUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_70()
        -515 (-91.80% of base) : 4451.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_71()
        -515 (-91.80% of base) : 4453.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmInt64MaxValueCastToUInt64IsFoldedCorrectly|11_73()
        -515 (-91.80% of base) : 4455.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|11_75()
        -515 (-91.80% of base) : 4456.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_76()
        -515 (-91.80% of base) : 3752.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_82()
        -515 (-91.80% of base) : 3743.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_73()
        -515 (-91.80% of base) : 3749.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_79()
        -515 (-91.80% of base) : 3751.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_81()
        -515 (-91.80% of base) : 4457.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneFullIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_77()
        -515 (-91.80% of base) : 4459.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|11_79()
        -515 (-91.80% of base) : 3745.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmInt64MaxValueCastToUInt64IsFoldedCorrectly|19_75()
        -515 (-91.80% of base) : 4446.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_66()
        -515 (-91.80% of base) : 3741.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_71()
        -515 (-91.80% of base) : 3747.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_77()
        -515 (-91.80% of base) : 3748.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_78()
        -515 (-91.80% of base) : 4396.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_80()
        -515 (-91.80% of base) : 4398.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneDecrementUnderUInt64MaxValueCastToUInt64IsFoldedCorrectly|11_82()

Top method regressions (percentages):
          19 (38.78% of base) : 86762.dasm - C:M(bool,short,short,int):short
           7 (15.91% of base) : 86589.dasm - ILGEN_0x8485715d:Main():int
           9 ( 8.82% of base) : 86787.dasm - ILGEN_CLASS:ILGEN_METHOD(double,ushort,int):bool
          13 ( 3.04% of base) : 149837.dasm - testout1:Func_0_4_3_1_6():long
          10 ( 2.80% of base) : 86380.dasm - ILGEN_0x58f32e86:Method_0x5d38(int):int
           3 ( 1.01% of base) : 152331.dasm - testout1:Func_0_4_3_1_6():long
           4 ( 0.41% of base) : 152295.dasm - testout1:Func_0_3_6_6_5():long
           4 ( 0.41% of base) : 149771.dasm - testout1:Func_0_3_6_6_5():long
           1 ( 0.27% of base) : 152514.dasm - testout1:Func_0_5_4_4_1():double
           1 ( 0.27% of base) : 150100.dasm - testout1:Func_0_5_4_4_1():double
           3 ( 0.26% of base) : 150180.dasm - testout1:Func_0_6_1_6_4():float

Top method improvements (percentages):
        -515 (-91.80% of base) : 4448.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_68()
        -515 (-91.80% of base) : 4449.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneFullIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_69()
        -515 (-91.80% of base) : 4450.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneDecrementUnderUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_70()
        -515 (-91.80% of base) : 4451.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_71()
        -515 (-91.80% of base) : 4453.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmInt64MaxValueCastToUInt64IsFoldedCorrectly|11_73()
        -515 (-91.80% of base) : 4455.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|11_75()
        -515 (-91.80% of base) : 4456.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_76()
        -515 (-91.80% of base) : 3752.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_82()
        -515 (-91.80% of base) : 3743.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_73()
        -515 (-91.80% of base) : 3749.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_79()
        -515 (-91.80% of base) : 3751.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmIntegerOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_81()
        -515 (-91.80% of base) : 4457.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneFullIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_77()
        -515 (-91.80% of base) : 4459.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|11_79()
        -515 (-91.80% of base) : 3745.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmInt64MaxValueCastToUInt64IsFoldedCorrectly|19_75()
        -515 (-91.80% of base) : 4446.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmUInt32MaxValueCastToUInt64IsFoldedCorrectly|11_66()
        -515 (-91.80% of base) : 3741.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneFullIncrementAboveUInt32MaxValueCastToUInt64IsFoldedCorrectly|19_71()
        -515 (-91.80% of base) : 3747.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneDecrementUnderInt64MaxValueCastToUInt64IsFoldedCorrectly|19_77()
        -515 (-91.80% of base) : 3748.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingDoubleToUInt64>g__ConfirmDoubleOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|19_78()
        -515 (-91.80% of base) : 4396.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmIntegerOneIncrementAboveInt64MaxValueCastToUInt64IsFoldedCorrectly|11_80()
        -515 (-91.80% of base) : 4398.dasm - ValueNumberingCheckedCastsOfConstants:<TestCastingSingleToUInt64>g__ConfirmSingleOneDecrementUnderUInt64MaxValueCastToUInt64IsFoldedCorrectly|11_82()

1051 total methods with Code Size differences (1040 improved, 11 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 189
Total bytes of diff: 179
Total bytes of delta: -10 (-5.29% of base)
Total relative delta: -0.05
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -10 : 69839.dasm (-5.29% of base)

1 total files with Code Size differences (1 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -10 (-5.29% of base) : 69839.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(long):System.__Canon

Top method improvements (percentages):
         -10 (-5.29% of base) : 69839.dasm - System.Runtime.InteropServices.Marshal:PtrToStructure(long):System.__Canon

1 total methods with Code Size differences (1 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 8666
Total bytes of diff: 8255
Total bytes of delta: -411 (-4.74% of base)
Total relative delta: -13.00
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -27 : 29056.dasm (-46.55% of base)
         -26 : 35152.dasm (-96.30% of base)
         -26 : 35144.dasm (-96.30% of base)
         -26 : 35155.dasm (-96.30% of base)
         -26 : 35146.dasm (-96.30% of base)
         -26 : 35149.dasm (-96.30% of base)
         -26 : 35154.dasm (-96.30% of base)
         -26 : 35157.dasm (-96.30% of base)
         -26 : 35148.dasm (-96.30% of base)
         -26 : 35145.dasm (-96.30% of base)
         -26 : 35156.dasm (-96.30% of base)
         -26 : 35147.dasm (-96.30% of base)
         -26 : 35153.dasm (-96.30% of base)
         -24 : 35143.dasm (-96.00% of base)
         -22 : 102842.dasm (-0.88% of base)
         -22 : 89505.dasm (-0.88% of base)
          -2 : 217934.dasm (-0.12% of base)
          -2 : 222269.dasm (-0.12% of base)

18 total files with Code Size differences (18 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
         -27 (-46.55% of base) : 29056.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.returnType.covariant.method004.method004.BaseObject`1[__Canon][System.__Canon]:RetObjectConstr(System.__Canon):System.__Canon:this
         -26 (-96.30% of base) : 35152.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(ubyte):this
         -26 (-96.30% of base) : 35144.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(ubyte):this
         -26 (-96.30% of base) : 35155.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(double):this
         -26 (-96.30% of base) : 35146.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(int):this
         -26 (-96.30% of base) : 35149.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(long):this
         -26 (-96.30% of base) : 35154.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(int):this
         -26 (-96.30% of base) : 35157.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(long):this
         -26 (-96.30% of base) : 35148.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.Numerics.Vector`1[Single]):this
         -26 (-96.30% of base) : 35145.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(short):this
         -26 (-96.30% of base) : 35156.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(System.Numerics.Vector`1[Single]):this
         -26 (-96.30% of base) : 35147.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(double):this
         -26 (-96.30% of base) : 35153.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(short):this
         -24 (-96.00% of base) : 35143.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.__Canon):this
         -22 (-0.88% of base) : 102842.dasm - <<SerializeUnsupportedType>g__RunTest|6_0>d`1[__Canon][System.__Canon]:MoveNext():this
         -22 (-0.88% of base) : 89505.dasm - <<SerializeUnsupportedType>g__RunTest|6_0>d`1[__Canon][System.__Canon]:MoveNext():this
          -2 (-0.12% of base) : 217934.dasm - System.Data.SqlClient.SqlInternalConnectionTds:LoginWithFailover(bool,System.Data.SqlClient.ServerInfo,System.String,System.String,System.Security.SecureString,bool,System.Data.SqlClient.SqlConnectionString,System.Data.SqlClient.SqlCredential,System.Data.ProviderBase.TimeoutTimer):this
          -2 (-0.12% of base) : 222269.dasm - System.Data.SqlClient.SqlInternalConnectionTds:LoginWithFailover(bool,System.Data.SqlClient.ServerInfo,System.String,System.String,System.Security.SecureString,bool,System.Data.SqlClient.SqlConnectionString,System.Data.SqlClient.SqlCredential,System.Data.ProviderBase.TimeoutTimer):this

Top method improvements (percentages):
         -26 (-96.30% of base) : 35152.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(ubyte):this
         -26 (-96.30% of base) : 35144.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(ubyte):this
         -26 (-96.30% of base) : 35155.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(double):this
         -26 (-96.30% of base) : 35146.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(int):this
         -26 (-96.30% of base) : 35149.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(long):this
         -26 (-96.30% of base) : 35154.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(int):this
         -26 (-96.30% of base) : 35157.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(long):this
         -26 (-96.30% of base) : 35148.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.Numerics.Vector`1[Single]):this
         -26 (-96.30% of base) : 35145.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(short):this
         -26 (-96.30% of base) : 35156.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(System.Numerics.Vector`1[Single]):this
         -26 (-96.30% of base) : 35147.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(double):this
         -26 (-96.30% of base) : 35153.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[Byte][System.Byte]:Foo(short):this
         -24 (-96.00% of base) : 35143.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.generic002.generic002.SubGenericClass`1[__Canon][System.__Canon]:Foo(System.__Canon):this
         -27 (-46.55% of base) : 29056.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.returnType.covariant.method004.method004.BaseObject`1[__Canon][System.__Canon]:RetObjectConstr(System.__Canon):System.__Canon:this
         -22 (-0.88% of base) : 102842.dasm - <<SerializeUnsupportedType>g__RunTest|6_0>d`1[__Canon][System.__Canon]:MoveNext():this
         -22 (-0.88% of base) : 89505.dasm - <<SerializeUnsupportedType>g__RunTest|6_0>d`1[__Canon][System.__Canon]:MoveNext():this
          -2 (-0.12% of base) : 222269.dasm - System.Data.SqlClient.SqlInternalConnectionTds:LoginWithFailover(bool,System.Data.SqlClient.ServerInfo,System.String,System.String,System.Security.SecureString,bool,System.Data.SqlClient.SqlConnectionString,System.Data.SqlClient.SqlCredential,System.Data.ProviderBase.TimeoutTimer):this
          -2 (-0.12% of base) : 217934.dasm - System.Data.SqlClient.SqlInternalConnectionTds:LoginWithFailover(bool,System.Data.SqlClient.ServerInfo,System.String,System.String,System.Security.SecureString,bool,System.Data.SqlClient.SqlConnectionString,System.Data.SqlClient.SqlCredential,System.Data.ProviderBase.TimeoutTimer):this

18 total methods with Code Size differences (18 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

