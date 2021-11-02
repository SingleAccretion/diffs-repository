## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 5760924 (overridden on cmd)
Total bytes of diff: 5756514 (overridden on cmd)
Total bytes of delta: -4410 (-0.08 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           9 : 20758.dasm (7.83% of base)
           7 : 10997.dasm (5.56% of base)
           1 : 20253.dasm (0.15% of base)

Top file improvements (bytes):
         -52 : 21313.dasm (-0.51% of base)
         -20 : 20443.dasm (-11.63% of base)
          -8 : 8071.dasm (-4.82% of base)
          -7 : 6072.dasm (-0.74% of base)
          -4 : 3333.dasm (-0.37% of base)
          -2 : 3541.dasm (-1.20% of base)
          -1 : 2933.dasm (-0.61% of base)

10 total files with Code Size differences (7 improved, 3 regressed), 0 unchanged.

Top method regressions (bytes):
           9 ( 7.83% of base) : 20758.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           7 ( 5.56% of base) : 10997.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.15% of base) : 20253.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
         -52 (-0.51% of base) : 21313.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
         -20 (-11.63% of base) : 20443.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -8 (-4.82% of base) : 8071.dasm - NamespaceManager:ExitScope():this
          -7 (-0.74% of base) : 6072.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -4 (-0.37% of base) : 3333.dasm - System.Uri:CreateUriInfo(long):this
          -2 (-1.20% of base) : 3541.dasm - NamespaceManager:ExitScope():this
          -1 (-0.61% of base) : 2933.dasm - HashtableEnumerator:MoveNext():bool:this

Top method regressions (percentages):
           9 ( 7.83% of base) : 20758.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           7 ( 5.56% of base) : 10997.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.15% of base) : 20253.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
         -20 (-11.63% of base) : 20443.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -8 (-4.82% of base) : 8071.dasm - NamespaceManager:ExitScope():this
          -2 (-1.20% of base) : 3541.dasm - NamespaceManager:ExitScope():this
          -7 (-0.74% of base) : 6072.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -1 (-0.61% of base) : 2933.dasm - HashtableEnumerator:MoveNext():bool:this
         -52 (-0.51% of base) : 21313.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
          -4 (-0.37% of base) : 3333.dasm - System.Uri:CreateUriInfo(long):this

10 total methods with Code Size differences (7 improved, 3 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 111079340 (overridden on cmd)
Total bytes of diff: 111067544 (overridden on cmd)
Total bytes of delta: -11796 (-0.01 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           9 : 239516.dasm (7.83% of base)

Top file improvements (bytes):
         -20 : 219419.dasm (-11.63% of base)
          -6 : 251576.dasm (-1.39% of base)
          -3 : 233361.dasm (-0.12% of base)

4 total files with Code Size differences (3 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           9 ( 7.83% of base) : 239516.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (bytes):
         -20 (-11.63% of base) : 219419.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -6 (-1.39% of base) : 251576.dasm - RandomTwister64:.ctor(long):this
          -3 (-0.12% of base) : 233361.dasm - MemoryAlloc:SteadyState():this

Top method regressions (percentages):
           9 ( 7.83% of base) : 239516.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (percentages):
         -20 (-11.63% of base) : 219419.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -6 (-1.39% of base) : 251576.dasm - RandomTwister64:.ctor(long):this
          -3 (-0.12% of base) : 233361.dasm - MemoryAlloc:SteadyState():this

4 total methods with Code Size differences (3 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 36001024 (overridden on cmd)
Total bytes of diff: 36000992 (overridden on cmd)
Total bytes of delta: -32 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          11 : 106186.dasm (8.73% of base)
           7 : 215592.dasm (5.56% of base)
           7 : 134483.dasm (0.29% of base)
           3 : 159450.dasm (0.21% of base)
           1 : 138453.dasm (0.76% of base)
           1 : 224017.dasm (0.14% of base)

Top file improvements (bytes):
          -8 : 129243.dasm (-4.82% of base)
          -7 : 105540.dasm (-0.79% of base)
          -7 : 134225.dasm (-0.74% of base)
          -6 : 196948.dasm (-5.56% of base)
          -6 : 149805.dasm (-2.08% of base)
          -6 : 196951.dasm (-5.83% of base)
          -4 : 136390.dasm (-0.59% of base)
          -4 : 211262.dasm (-0.37% of base)
          -3 : 108111.dasm (-5.17% of base)
          -3 : 112655.dasm (-2.07% of base)
          -3 : 83728.dasm (-1.23% of base)
          -2 : 112657.dasm (-1.46% of base)
          -2 : 129276.dasm (-1.20% of base)
          -1 : 108119.dasm (-0.38% of base)

20 total files with Code Size differences (14 improved, 6 regressed), 2 unchanged.

Top method regressions (bytes):
          11 ( 8.73% of base) : 106186.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           7 ( 0.29% of base) : 134483.dasm - <ReadDataAsync>d__504:MoveNext():this
           7 ( 5.56% of base) : 215592.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           3 ( 0.21% of base) : 159450.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
           1 ( 0.14% of base) : 224017.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,int):this
           1 ( 0.76% of base) : 138453.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this

Top method improvements (bytes):
          -8 (-4.82% of base) : 129243.dasm - NamespaceManager:ExitScope():this
          -7 (-0.79% of base) : 105540.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -7 (-0.74% of base) : 134225.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -6 (-5.56% of base) : 196948.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -6 (-5.83% of base) : 196951.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -6 (-2.08% of base) : 149805.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -4 (-0.37% of base) : 211262.dasm - System.Uri:CreateUriInfo(long):this
          -4 (-0.59% of base) : 136390.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -3 (-5.17% of base) : 108111.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-2.07% of base) : 112655.dasm - System.Data.ExpressionParser:ScanDate():this
          -3 (-1.23% of base) : 83728.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -2 (-1.20% of base) : 129276.dasm - NamespaceManager:ExitScope():this
          -2 (-1.46% of base) : 112657.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -1 (-0.38% of base) : 108119.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method regressions (percentages):
          11 ( 8.73% of base) : 106186.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           7 ( 5.56% of base) : 215592.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           1 ( 0.76% of base) : 138453.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
           7 ( 0.29% of base) : 134483.dasm - <ReadDataAsync>d__504:MoveNext():this
           3 ( 0.21% of base) : 159450.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
           1 ( 0.14% of base) : 224017.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,int):this

Top method improvements (percentages):
          -6 (-5.83% of base) : 196951.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -6 (-5.56% of base) : 196948.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -3 (-5.17% of base) : 108111.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-4.82% of base) : 129243.dasm - NamespaceManager:ExitScope():this
          -6 (-2.08% of base) : 149805.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -3 (-2.07% of base) : 112655.dasm - System.Data.ExpressionParser:ScanDate():this
          -2 (-1.46% of base) : 112657.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -3 (-1.23% of base) : 83728.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -2 (-1.20% of base) : 129276.dasm - NamespaceManager:ExitScope():this
          -7 (-0.79% of base) : 105540.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -7 (-0.74% of base) : 134225.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -4 (-0.59% of base) : 136390.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -1 (-0.38% of base) : 108119.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -4 (-0.37% of base) : 211262.dasm - System.Uri:CreateUriInfo(long):this

20 total methods with Code Size differences (14 improved, 6 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 86291266 (overridden on cmd)
Total bytes of diff: 86289558 (overridden on cmd)
Total bytes of delta: -1708 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 104946.dasm (0.13% of base)

Top file improvements (bytes):
        -122 : 276370.dasm (-79.74% of base)
        -111 : 325156.dasm (-41.57% of base)
          -9 : 64772.dasm (-3.45% of base)
          -5 : 12150.dasm (-1.18% of base)
          -5 : 12163.dasm (-1.17% of base)
          -3 : 133630.dasm (-0.17% of base)
          -3 : 118682.dasm (-1.02% of base)
          -1 : 352729.dasm (-0.57% of base)

9 total files with Code Size differences (8 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           2 ( 0.13% of base) : 104946.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (bytes):
        -122 (-79.74% of base) : 276370.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -111 (-41.57% of base) : 325156.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -9 (-3.45% of base) : 64772.dasm - <>c__DisplayClass1_0:<Send_NullRequest_ThrowsException>b__1():System.Threading.Tasks.Task:this
          -5 (-1.18% of base) : 12150.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.17% of base) : 12163.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-0.17% of base) : 133630.dasm - <PathsTo>d__25:MoveNext():bool:this
          -3 (-1.02% of base) : 118682.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.57% of base) : 352729.dasm - BufferWriter:Write(ushort):this

Top method regressions (percentages):
           2 ( 0.13% of base) : 104946.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (percentages):
        -122 (-79.74% of base) : 276370.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -111 (-41.57% of base) : 325156.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -9 (-3.45% of base) : 64772.dasm - <>c__DisplayClass1_0:<Send_NullRequest_ThrowsException>b__1():System.Threading.Tasks.Task:this
          -5 (-1.18% of base) : 12150.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.17% of base) : 12163.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.02% of base) : 118682.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.57% of base) : 352729.dasm - BufferWriter:Write(ushort):this
          -3 (-0.17% of base) : 133630.dasm - <PathsTo>d__25:MoveNext():bool:this

9 total methods with Code Size differences (8 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

