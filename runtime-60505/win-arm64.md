## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 2240
Total bytes of diff: 2220
Total bytes of delta: -20 (-0.89% of base)
Total relative delta: -0.09
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 10234.dasm (0.53% of base)

Top file improvements (bytes):
          -8 : 3227.dasm (-2.86% of base)
          -4 : 2739.dasm (-1.45% of base)
          -4 : 20585.dasm (-1.56% of base)
          -4 : 20964.dasm (-2.04% of base)
          -4 : 3471.dasm (-1.43% of base)

6 total files with Code Size differences (5 improved, 1 regressed), 1 unchanged.

Top method regressions (bytes):
           4 ( 0.53% of base) : 10234.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
          -8 (-2.86% of base) : 3227.dasm - NamespaceManager:ExitScope():this
          -4 (-1.45% of base) : 2739.dasm - NamespaceManager:ExitScope():this
          -4 (-1.56% of base) : 20585.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.04% of base) : 20964.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.43% of base) : 3471.dasm - HashtableEnumerator:MoveNext():bool:this

Top method regressions (percentages):
           4 ( 0.53% of base) : 10234.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
          -8 (-2.86% of base) : 3227.dasm - NamespaceManager:ExitScope():this
          -4 (-2.04% of base) : 20964.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.56% of base) : 20585.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-1.45% of base) : 2739.dasm - NamespaceManager:ExitScope():this
          -4 (-1.43% of base) : 3471.dasm - HashtableEnumerator:MoveNext():bool:this

6 total methods with Code Size differences (5 improved, 1 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3620
Total bytes of diff: 3600
Total bytes of delta: -20 (-0.55% of base)
Total relative delta: -0.06
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 80753.dasm (-2.15% of base)
          -4 : 215520.dasm (-0.14% of base)
          -4 : 221712.dasm (-2.04% of base)
          -4 : 202649.dasm (-1.56% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -8 (-2.15% of base) : 80753.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -4 (-0.14% of base) : 215520.dasm - MemoryAlloc:SteadyState():this
          -4 (-2.04% of base) : 221712.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.56% of base) : 202649.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this

Top method improvements (percentages):
          -8 (-2.15% of base) : 80753.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -4 (-2.04% of base) : 221712.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.56% of base) : 202649.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-0.14% of base) : 215520.dasm - MemoryAlloc:SteadyState():this

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7008
Total bytes of diff: 6964
Total bytes of delta: -44 (-0.63% of base)
Total relative delta: -0.13
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 2574.dasm (1.43% of base)
           4 : 57997.dasm (0.44% of base)

Top file improvements (bytes):
         -12 : 90586.dasm (-0.88% of base)
          -8 : 145064.dasm (-2.63% of base)
          -4 : 2837.dasm (-0.19% of base)
          -4 : 214089.dasm (-1.96% of base)
          -4 : 47012.dasm (-1.16% of base)
          -4 : 88407.dasm (-3.12% of base)
          -4 : 2576.dasm (-1.28% of base)
          -4 : 87341.dasm (-1.10% of base)
          -4 : 145096.dasm (-1.28% of base)
          -4 : 88399.dasm (-0.93% of base)

12 total files with Code Size differences (10 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
           4 ( 1.43% of base) : 2574.dasm - System.Data.ExpressionParser:ScanString(ushort):this
           4 ( 0.44% of base) : 57997.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
         -12 (-0.88% of base) : 90586.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -8 (-2.63% of base) : 145064.dasm - NamespaceManager:ExitScope():this
          -4 (-0.19% of base) : 2837.dasm - System.Data.Select:CreateIndex():this
          -4 (-1.96% of base) : 214089.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -4 (-1.16% of base) : 47012.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-3.12% of base) : 88407.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -4 (-1.28% of base) : 2576.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.10% of base) : 87341.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -4 (-1.28% of base) : 145096.dasm - NamespaceManager:ExitScope():this
          -4 (-0.93% of base) : 88399.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method regressions (percentages):
           4 ( 1.43% of base) : 2574.dasm - System.Data.ExpressionParser:ScanString(ushort):this
           4 ( 0.44% of base) : 57997.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
          -4 (-3.12% of base) : 88407.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-2.63% of base) : 145064.dasm - NamespaceManager:ExitScope():this
          -4 (-1.96% of base) : 214089.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -4 (-1.28% of base) : 2576.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.28% of base) : 145096.dasm - NamespaceManager:ExitScope():this
          -4 (-1.16% of base) : 47012.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-1.10% of base) : 87341.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -4 (-0.93% of base) : 88399.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
         -12 (-0.88% of base) : 90586.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-0.19% of base) : 2837.dasm - System.Data.Select:CreateIndex():this

12 total methods with Code Size differences (10 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 6840
Total bytes of diff: 6776
Total bytes of delta: -64 (-0.94% of base)
Total relative delta: -0.20
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 109375.dasm (1.72% of base)

Top file improvements (bytes):
         -12 : 102264.dasm (-0.95% of base)
          -8 : 119200.dasm (-2.86% of base)
          -8 : 126303.dasm (-0.84% of base)
          -4 : 104819.dasm (-3.45% of base)
          -4 : 109373.dasm (-1.75% of base)
          -4 : 128394.dasm (-1.89% of base)
          -4 : 119167.dasm (-1.45% of base)
          -4 : 104827.dasm (-0.93% of base)
          -4 : 102891.dasm (-1.89% of base)
          -4 : 191731.dasm (-2.17% of base)
          -4 : 191728.dasm (-2.08% of base)
          -4 : 82252.dasm (-1.19% of base)
          -4 : 109106.dasm (-0.23% of base)

14 total files with Code Size differences (13 improved, 1 regressed), 1 unchanged.

Top method regressions (bytes):
           4 ( 1.72% of base) : 109375.dasm - System.Data.ExpressionParser:ScanString(ushort):this

Top method improvements (bytes):
         -12 (-0.95% of base) : 102264.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -8 (-2.86% of base) : 119200.dasm - NamespaceManager:ExitScope():this
          -8 (-0.84% of base) : 126303.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-3.45% of base) : 104819.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -4 (-1.75% of base) : 109373.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.89% of base) : 128394.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -4 (-1.45% of base) : 119167.dasm - NamespaceManager:ExitScope():this
          -4 (-0.93% of base) : 104827.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -4 (-1.89% of base) : 102891.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
          -4 (-2.17% of base) : 191731.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-2.08% of base) : 191728.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-1.19% of base) : 82252.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -4 (-0.23% of base) : 109106.dasm - System.Data.Select:CreateIndex():this

Top method regressions (percentages):
           4 ( 1.72% of base) : 109375.dasm - System.Data.ExpressionParser:ScanString(ushort):this

Top method improvements (percentages):
          -4 (-3.45% of base) : 104819.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-2.86% of base) : 119200.dasm - NamespaceManager:ExitScope():this
          -4 (-2.17% of base) : 191731.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-2.08% of base) : 191728.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-1.89% of base) : 128394.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -4 (-1.89% of base) : 102891.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
          -4 (-1.75% of base) : 109373.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.45% of base) : 119167.dasm - NamespaceManager:ExitScope():this
          -4 (-1.19% of base) : 82252.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
         -12 (-0.95% of base) : 102264.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-0.93% of base) : 104827.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -8 (-0.84% of base) : 126303.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-0.23% of base) : 109106.dasm - System.Data.Select:CreateIndex():this

14 total methods with Code Size differences (13 improved, 1 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4324
Total bytes of diff: 4008
Total bytes of delta: -316 (-7.31% of base)
Total relative delta: -1.13
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -156 : 273266.dasm (-72.22% of base)
        -148 : 321768.dasm (-38.54% of base)
          -4 : 102629.dasm (-0.19% of base)
          -4 : 116304.dasm (-0.99% of base)
          -4 : 213751.dasm (-1.47% of base)

5 total files with Code Size differences (5 improved, 0 regressed), 2 unchanged.

Top method improvements (bytes):
        -156 (-72.22% of base) : 273266.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -148 (-38.54% of base) : 321768.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -4 (-0.19% of base) : 102629.dasm - <TestData>d__7:MoveNext():bool:this
          -4 (-0.99% of base) : 116304.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -4 (-1.47% of base) : 213751.dasm - BufferWriter:Write(ushort):this

Top method improvements (percentages):
        -156 (-72.22% of base) : 273266.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -148 (-38.54% of base) : 321768.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -4 (-1.47% of base) : 213751.dasm - BufferWriter:Write(ushort):this
          -4 (-0.99% of base) : 116304.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -4 (-0.19% of base) : 102629.dasm - <TestData>d__7:MoveNext():bool:this

5 total methods with Code Size differences (5 improved, 0 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

