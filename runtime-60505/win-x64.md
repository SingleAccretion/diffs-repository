## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1697
Total bytes of diff: 1696
Total bytes of delta: -1 (-0.06% of base)
Total relative delta: 0.03
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 21474.dasm (6.15% of base)
           6 : 16277.dasm (4.20% of base)

Top file improvements (bytes):
          -6 : 20866.dasm (-3.02% of base)
          -4 : 8479.dasm (-2.01% of base)
          -2 : 3329.dasm (-0.88% of base)
          -2 : 8362.dasm (-1.16% of base)
          -1 : 11532.dasm (-0.16% of base)

7 total files with Code Size differences (5 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 6.15% of base) : 21474.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           6 ( 4.20% of base) : 16277.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this

Top method improvements (bytes):
          -6 (-3.02% of base) : 20866.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.01% of base) : 8479.dasm - NamespaceManager:ExitScope():this
          -2 (-0.88% of base) : 3329.dasm - HashtableEnumerator:MoveNext():bool:this
          -2 (-1.16% of base) : 8362.dasm - NamespaceManager:ExitScope():this
          -1 (-0.16% of base) : 11532.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method regressions (percentages):
           8 ( 6.15% of base) : 21474.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           6 ( 4.20% of base) : 16277.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this

Top method improvements (percentages):
          -6 (-3.02% of base) : 20866.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.01% of base) : 8479.dasm - NamespaceManager:ExitScope():this
          -2 (-1.16% of base) : 8362.dasm - NamespaceManager:ExitScope():this
          -2 (-0.88% of base) : 3329.dasm - HashtableEnumerator:MoveNext():bool:this
          -1 (-0.16% of base) : 11532.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

7 total methods with Code Size differences (5 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3581
Total bytes of diff: 3554
Total bytes of delta: -27 (-0.75% of base)
Total relative delta: -0.06
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 222028.dasm (6.15% of base)

Top file improvements (bytes):
         -25 : 80753.dasm (-8.42% of base)
          -6 : 202795.dasm (-3.02% of base)
          -3 : 215866.dasm (-0.11% of base)
          -1 : 231470.dasm (-0.40% of base)

5 total files with Code Size differences (4 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 6.15% of base) : 222028.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (bytes):
         -25 (-8.42% of base) : 80753.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -6 (-3.02% of base) : 202795.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -3 (-0.11% of base) : 215866.dasm - MemoryAlloc:SteadyState():this
          -1 (-0.40% of base) : 231470.dasm - RandomTwister64:.ctor(long):this

Top method regressions (percentages):
           8 ( 6.15% of base) : 222028.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (percentages):
         -25 (-8.42% of base) : 80753.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -6 (-3.02% of base) : 202795.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -1 (-0.40% of base) : 231470.dasm - RandomTwister64:.ctor(long):this
          -3 (-0.11% of base) : 215866.dasm - MemoryAlloc:SteadyState():this

5 total methods with Code Size differences (4 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4763
Total bytes of diff: 4720
Total bytes of delta: -43 (-0.90% of base)
Total relative delta: -0.18
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           3 : 7863.dasm (1.24% of base)

Top file improvements (bytes):
         -15 : 10118.dasm (-1.47% of base)
         -10 : 19200.dasm (-5.71% of base)
          -5 : 125931.dasm (-2.46% of base)
          -4 : 97204.dasm (-1.99% of base)
          -3 : 19202.dasm (-1.68% of base)
          -2 : 97236.dasm (-1.14% of base)
          -2 : 46076.dasm (-0.77% of base)
          -2 : 7871.dasm (-2.82% of base)
          -1 : 136817.dasm (-0.17% of base)
          -1 : 19462.dasm (-0.07% of base)
          -1 : 197229.dasm (-0.99% of base)

12 total files with Code Size differences (11 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           3 ( 1.24% of base) : 7863.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (bytes):
         -15 (-1.47% of base) : 10118.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
         -10 (-5.71% of base) : 19200.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -5 (-2.46% of base) : 125931.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-1.99% of base) : 97204.dasm - NamespaceManager:ExitScope():this
          -3 (-1.68% of base) : 19202.dasm - System.Data.ExpressionParser:ScanDate():this
          -2 (-1.14% of base) : 97236.dasm - NamespaceManager:ExitScope():this
          -2 (-0.77% of base) : 46076.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -2 (-2.82% of base) : 7871.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -1 (-0.17% of base) : 136817.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this
          -1 (-0.07% of base) : 19462.dasm - System.Data.Select:CreateIndex():this
          -1 (-0.99% of base) : 197229.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this

Top method regressions (percentages):
           3 ( 1.24% of base) : 7863.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (percentages):
         -10 (-5.71% of base) : 19200.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -2 (-2.82% of base) : 7871.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -5 (-2.46% of base) : 125931.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-1.99% of base) : 97204.dasm - NamespaceManager:ExitScope():this
          -3 (-1.68% of base) : 19202.dasm - System.Data.ExpressionParser:ScanDate():this
         -15 (-1.47% of base) : 10118.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -2 (-1.14% of base) : 97236.dasm - NamespaceManager:ExitScope():this
          -1 (-0.99% of base) : 197229.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -2 (-0.77% of base) : 46076.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -1 (-0.17% of base) : 136817.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this
          -1 (-0.07% of base) : 19462.dasm - System.Data.Select:CreateIndex():this

12 total methods with Code Size differences (11 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 5831
Total bytes of diff: 5787
Total bytes of delta: -44 (-0.75% of base)
Total relative delta: -0.13
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          12 : 106590.dasm (9.02% of base)
           6 : 214326.dasm (4.20% of base)
           3 : 108524.dasm (0.95% of base)

Top file improvements (bytes):
         -15 : 105963.dasm (-1.29% of base)
         -12 : 112737.dasm (-3.70% of base)
          -7 : 113095.dasm (-4.07% of base)
          -6 : 113097.dasm (-3.59% of base)
          -5 : 138458.dasm (-0.61% of base)
          -4 : 131361.dasm (-2.01% of base)
          -3 : 140538.dasm (-1.79% of base)
          -3 : 195117.dasm (-2.54% of base)
          -3 : 195114.dasm (-2.36% of base)
          -2 : 108516.dasm (-2.86% of base)
          -2 : 131328.dasm (-1.16% of base)
          -2 : 84168.dasm (-0.78% of base)
          -1 : 112826.dasm (-0.07% of base)

16 total files with Code Size differences (13 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
          12 ( 9.02% of base) : 106590.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           6 ( 4.20% of base) : 214326.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           3 ( 0.95% of base) : 108524.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (bytes):
         -15 (-1.29% of base) : 105963.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
         -12 (-3.70% of base) : 112737.dasm - System.Data.RBTree`1[Vector`1][System.Numerics.Vector`1[System.Single]]:GetNewNode(System.Numerics.Vector`1[Single]):int:this
          -7 (-4.07% of base) : 113095.dasm - System.Data.ExpressionParser:ScanDate():this
          -6 (-3.59% of base) : 113097.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -5 (-0.61% of base) : 138458.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-2.01% of base) : 131361.dasm - NamespaceManager:ExitScope():this
          -3 (-1.79% of base) : 140538.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -3 (-2.54% of base) : 195117.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -3 (-2.36% of base) : 195114.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -2 (-2.86% of base) : 108516.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -2 (-1.16% of base) : 131328.dasm - NamespaceManager:ExitScope():this
          -2 (-0.78% of base) : 84168.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -1 (-0.07% of base) : 112826.dasm - System.Data.Select:CreateIndex():this

Top method regressions (percentages):
          12 ( 9.02% of base) : 106590.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           6 ( 4.20% of base) : 214326.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           3 ( 0.95% of base) : 108524.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (percentages):
          -7 (-4.07% of base) : 113095.dasm - System.Data.ExpressionParser:ScanDate():this
         -12 (-3.70% of base) : 112737.dasm - System.Data.RBTree`1[Vector`1][System.Numerics.Vector`1[System.Single]]:GetNewNode(System.Numerics.Vector`1[Single]):int:this
          -6 (-3.59% of base) : 113097.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -2 (-2.86% of base) : 108516.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-2.54% of base) : 195117.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -3 (-2.36% of base) : 195114.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-2.01% of base) : 131361.dasm - NamespaceManager:ExitScope():this
          -3 (-1.79% of base) : 140538.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
         -15 (-1.29% of base) : 105963.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -2 (-1.16% of base) : 131328.dasm - NamespaceManager:ExitScope():this
          -2 (-0.78% of base) : 84168.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -5 (-0.61% of base) : 138458.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -1 (-0.07% of base) : 112826.dasm - System.Data.Select:CreateIndex():this

16 total methods with Code Size differences (13 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4090
Total bytes of diff: 3832
Total bytes of delta: -258 (-6.31% of base)
Total relative delta: -1.12
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          18 : 103326.dasm (0.82% of base)

Top file improvements (bytes):
        -136 : 274588.dasm (-72.34% of base)
        -126 : 323154.dasm (-36.63% of base)
          -5 : 12221.dasm (-1.12% of base)
          -5 : 12234.dasm (-1.11% of base)
          -3 : 117014.dasm (-1.03% of base)
          -1 : 214570.dasm (-0.56% of base)

7 total files with Code Size differences (6 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
          18 ( 0.82% of base) : 103326.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (bytes):
        -136 (-72.34% of base) : 274588.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -126 (-36.63% of base) : 323154.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -5 (-1.12% of base) : 12221.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.11% of base) : 12234.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.03% of base) : 117014.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.56% of base) : 214570.dasm - BufferWriter:Write(ushort):this

Top method regressions (percentages):
          18 ( 0.82% of base) : 103326.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (percentages):
        -136 (-72.34% of base) : 274588.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -126 (-36.63% of base) : 323154.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -5 (-1.12% of base) : 12221.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.11% of base) : 12234.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.03% of base) : 117014.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.56% of base) : 214570.dasm - BufferWriter:Write(ushort):this

7 total methods with Code Size differences (6 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

