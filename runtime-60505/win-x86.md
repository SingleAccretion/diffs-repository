## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 13143
Total bytes of diff: 13200
Total bytes of delta: 57 (0.43% of base)
Total relative delta: 0.15
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         128 : 23257.dasm (16.75% of base)
           9 : 19547.dasm (7.83% of base)
           7 : 14813.dasm (5.56% of base)
           1 : 11102.dasm (0.15% of base)

Top file improvements (bytes):
         -63 : 12727.dasm (-0.58% of base)
         -20 : 19058.dasm (-11.63% of base)
          -2 : 8215.dasm (-1.37% of base)
          -2 : 8330.dasm (-1.20% of base)
          -1 : 3306.dasm (-0.61% of base)

9 total files with Code Size differences (5 improved, 4 regressed), 0 unchanged.

Top method regressions (bytes):
         128 (16.75% of base) : 23257.dasm - Benchstone.BenchF.Lorenz:Test():bool:this
           9 ( 7.83% of base) : 19547.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           7 ( 5.56% of base) : 14813.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.15% of base) : 11102.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
         -63 (-0.58% of base) : 12727.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
         -20 (-11.63% of base) : 19058.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -2 (-1.37% of base) : 8215.dasm - NamespaceManager:ExitScope():this
          -2 (-1.20% of base) : 8330.dasm - NamespaceManager:ExitScope():this
          -1 (-0.61% of base) : 3306.dasm - HashtableEnumerator:MoveNext():bool:this

Top method regressions (percentages):
         128 (16.75% of base) : 23257.dasm - Benchstone.BenchF.Lorenz:Test():bool:this
           9 ( 7.83% of base) : 19547.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           7 ( 5.56% of base) : 14813.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.15% of base) : 11102.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
         -20 (-11.63% of base) : 19058.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -2 (-1.37% of base) : 8215.dasm - NamespaceManager:ExitScope():this
          -2 (-1.20% of base) : 8330.dasm - NamespaceManager:ExitScope():this
          -1 (-0.61% of base) : 3306.dasm - HashtableEnumerator:MoveNext():bool:this
         -63 (-0.58% of base) : 12727.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)

9 total methods with Code Size differences (5 improved, 4 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4214
Total bytes of diff: 4249
Total bytes of delta: 35 (0.83% of base)
Total relative delta: -0.05
    diff is a regression.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         128 : 228662.dasm (16.75% of base)
           9 : 221653.dasm (7.83% of base)

Top file improvements (bytes):
         -79 : 231055.dasm (-18.24% of base)
         -20 : 202596.dasm (-11.63% of base)
          -3 : 215458.dasm (-0.12% of base)

5 total files with Code Size differences (3 improved, 2 regressed), 1 unchanged.

Top method regressions (bytes):
         128 (16.75% of base) : 228662.dasm - Benchstone.BenchF.Lorenz:Bench():bool
           9 ( 7.83% of base) : 221653.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (bytes):
         -79 (-18.24% of base) : 231055.dasm - RandomTwister64:.ctor(long):this
         -20 (-11.63% of base) : 202596.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -3 (-0.12% of base) : 215458.dasm - MemoryAlloc:SteadyState():this

Top method regressions (percentages):
         128 (16.75% of base) : 228662.dasm - Benchstone.BenchF.Lorenz:Bench():bool
           9 ( 7.83% of base) : 221653.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (percentages):
         -79 (-18.24% of base) : 231055.dasm - RandomTwister64:.ctor(long):this
         -20 (-11.63% of base) : 202596.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -3 (-0.12% of base) : 215458.dasm - MemoryAlloc:SteadyState():this

5 total methods with Code Size differences (3 improved, 2 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3971
Total bytes of diff: 3934
Total bytes of delta: -37 (-0.93% of base)
Total relative delta: -0.23
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           1 : 62193.dasm (0.15% of base)

Top file improvements (bytes):
          -8 : 123751.dasm (-4.88% of base)
          -8 : 164894.dasm (-5.44% of base)
          -7 : 50076.dasm (-0.87% of base)
          -3 : 164896.dasm (-2.03% of base)
          -3 : 47910.dasm (-5.08% of base)
          -3 : 97265.dasm (-1.22% of base)
          -2 : 123786.dasm (-1.34% of base)
          -2 : 51210.dasm (-1.27% of base)
          -1 : 187023.dasm (-1.11% of base)
          -1 : 165143.dasm (-0.08% of base)

11 total files with Code Size differences (10 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           1 ( 0.15% of base) : 62193.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
          -8 (-4.88% of base) : 123751.dasm - NamespaceManager:ExitScope():this
          -8 (-5.44% of base) : 164894.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -7 (-0.87% of base) : 50076.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -3 (-2.03% of base) : 164896.dasm - System.Data.ExpressionParser:ScanDate():this
          -3 (-5.08% of base) : 47910.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-1.22% of base) : 97265.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -2 (-1.34% of base) : 123786.dasm - NamespaceManager:ExitScope():this
          -2 (-1.27% of base) : 51210.dasm - HashtableEnumerator:MoveNext():bool:this
          -1 (-1.11% of base) : 187023.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -1 (-0.08% of base) : 165143.dasm - System.Data.Select:CreateIndex():this

Top method regressions (percentages):
           1 ( 0.15% of base) : 62193.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
          -8 (-5.44% of base) : 164894.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -3 (-5.08% of base) : 47910.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-4.88% of base) : 123751.dasm - NamespaceManager:ExitScope():this
          -3 (-2.03% of base) : 164896.dasm - System.Data.ExpressionParser:ScanDate():this
          -2 (-1.34% of base) : 123786.dasm - NamespaceManager:ExitScope():this
          -2 (-1.27% of base) : 51210.dasm - HashtableEnumerator:MoveNext():bool:this
          -3 (-1.22% of base) : 97265.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -1 (-1.11% of base) : 187023.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -7 (-0.87% of base) : 50076.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -1 (-0.08% of base) : 165143.dasm - System.Data.Select:CreateIndex():this

11 total methods with Code Size differences (10 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 4554
Total bytes of diff: 4528
Total bytes of delta: -26 (-0.57% of base)
Total relative delta: -0.15
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          11 : 105874.dasm (8.73% of base)
           7 : 213657.dasm (5.56% of base)
           1 : 141862.dasm (0.76% of base)

Top file improvements (bytes):
          -8 : 114470.dasm (-5.59% of base)
          -7 : 105228.dasm (-0.78% of base)
          -6 : 195176.dasm (-5.83% of base)
          -6 : 195173.dasm (-5.56% of base)
          -4 : 139799.dasm (-0.59% of base)
          -3 : 114468.dasm (-2.01% of base)
          -3 : 107799.dasm (-5.17% of base)
          -3 : 83453.dasm (-1.23% of base)
          -2 : 132657.dasm (-1.37% of base)
          -2 : 132690.dasm (-1.20% of base)
          -1 : 107807.dasm (-0.38% of base)

14 total files with Code Size differences (11 improved, 3 regressed), 1 unchanged.

Top method regressions (bytes):
          11 ( 8.73% of base) : 105874.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           7 ( 5.56% of base) : 213657.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.76% of base) : 141862.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this

Top method improvements (bytes):
          -8 (-5.59% of base) : 114470.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -7 (-0.78% of base) : 105228.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -6 (-5.83% of base) : 195176.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -6 (-5.56% of base) : 195173.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-0.59% of base) : 139799.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -3 (-2.01% of base) : 114468.dasm - System.Data.ExpressionParser:ScanDate():this
          -3 (-5.17% of base) : 107799.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-1.23% of base) : 83453.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -2 (-1.37% of base) : 132657.dasm - NamespaceManager:ExitScope():this
          -2 (-1.20% of base) : 132690.dasm - NamespaceManager:ExitScope():this
          -1 (-0.38% of base) : 107807.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method regressions (percentages):
          11 ( 8.73% of base) : 105874.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           7 ( 5.56% of base) : 213657.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.76% of base) : 141862.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this

Top method improvements (percentages):
          -6 (-5.83% of base) : 195176.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -8 (-5.59% of base) : 114470.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -6 (-5.56% of base) : 195173.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -3 (-5.17% of base) : 107799.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-2.01% of base) : 114468.dasm - System.Data.ExpressionParser:ScanDate():this
          -2 (-1.37% of base) : 132657.dasm - NamespaceManager:ExitScope():this
          -3 (-1.23% of base) : 83453.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -2 (-1.20% of base) : 132690.dasm - NamespaceManager:ExitScope():this
          -7 (-0.78% of base) : 105228.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-0.59% of base) : 139799.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -1 (-0.38% of base) : 107807.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

14 total methods with Code Size differences (11 improved, 3 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3699
Total bytes of diff: 3420
Total bytes of delta: -279 (-7.54% of base)
Total relative delta: -1.40
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 102613.dasm (0.13% of base)

Top file improvements (bytes):
        -122 : 273181.dasm (-79.74% of base)
        -111 : 321684.dasm (-41.57% of base)
         -17 : 182777.dasm (-7.62% of base)
         -17 : 60549.dasm (-7.62% of base)
          -5 : 12043.dasm (-1.18% of base)
          -5 : 12056.dasm (-1.17% of base)
          -3 : 116251.dasm (-1.02% of base)
          -1 : 213686.dasm (-0.57% of base)

9 total files with Code Size differences (8 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           2 ( 0.13% of base) : 102613.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (bytes):
        -122 (-79.74% of base) : 273181.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -111 (-41.57% of base) : 321684.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
         -17 (-7.62% of base) : 182777.dasm - CustomStream:Read(System.Byte[],int,int):int:this
         -17 (-7.62% of base) : 60549.dasm - CustomStream:Read(System.Byte[],int,int):int:this
          -5 (-1.18% of base) : 12043.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.17% of base) : 12056.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.02% of base) : 116251.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.57% of base) : 213686.dasm - BufferWriter:Write(ushort):this

Top method regressions (percentages):
           2 ( 0.13% of base) : 102613.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (percentages):
        -122 (-79.74% of base) : 273181.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -111 (-41.57% of base) : 321684.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
         -17 (-7.62% of base) : 182777.dasm - CustomStream:Read(System.Byte[],int,int):int:this
         -17 (-7.62% of base) : 60549.dasm - CustomStream:Read(System.Byte[],int,int):int:this
          -5 (-1.18% of base) : 12043.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.17% of base) : 12056.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.02% of base) : 116251.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.57% of base) : 213686.dasm - BufferWriter:Write(ushort):this

9 total methods with Code Size differences (8 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

