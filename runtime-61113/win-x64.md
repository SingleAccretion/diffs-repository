## benchmarks.run.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7236062 (overridden on cmd)
Total bytes of diff: 7236054 (overridden on cmd)
Total bytes of delta: -8 (-0.00 % of base)
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 23102.dasm (6.15% of base)
           6 : 11544.dasm (4.20% of base)

Top file improvements (bytes):
          -6 : 22663.dasm (-3.02% of base)
          -4 : 3583.dasm (-2.01% of base)
          -4 : 3375.dasm (-0.39% of base)
          -3 : 6219.dasm (-0.28% of base)
          -2 : 2973.dasm (-0.88% of base)
          -2 : 8343.dasm (-1.07% of base)
          -1 : 22401.dasm (-0.16% of base)

9 total files with Code Size differences (7 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 6.15% of base) : 23102.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           6 ( 4.20% of base) : 11544.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this

Top method improvements (bytes):
          -6 (-3.02% of base) : 22663.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.01% of base) : 3583.dasm - NamespaceManager:ExitScope():this
          -4 (-0.39% of base) : 3375.dasm - System.Uri:CreateUriInfo(long):this
          -3 (-0.28% of base) : 6219.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -2 (-0.88% of base) : 2973.dasm - HashtableEnumerator:MoveNext():bool:this
          -2 (-1.07% of base) : 8343.dasm - NamespaceManager:ExitScope():this
          -1 (-0.16% of base) : 22401.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method regressions (percentages):
           8 ( 6.15% of base) : 23102.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
           6 ( 4.20% of base) : 11544.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this

Top method improvements (percentages):
          -6 (-3.02% of base) : 22663.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.01% of base) : 3583.dasm - NamespaceManager:ExitScope():this
          -2 (-1.07% of base) : 8343.dasm - NamespaceManager:ExitScope():this
          -2 (-0.88% of base) : 2973.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-0.39% of base) : 3375.dasm - System.Uri:CreateUriInfo(long):this
          -3 (-0.28% of base) : 6219.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -1 (-0.16% of base) : 22401.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

9 total methods with Code Size differences (7 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 127268821 (overridden on cmd)
Total bytes of diff: 127268794 (overridden on cmd)
Total bytes of delta: -27 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 239879.dasm (6.15% of base)

Top file improvements (bytes):
         -25 : 82564.dasm (-8.42% of base)
          -6 : 219689.dasm (-3.02% of base)
          -3 : 233617.dasm (-0.11% of base)
          -1 : 252220.dasm (-0.40% of base)

5 total files with Code Size differences (4 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 6.15% of base) : 239879.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (bytes):
         -25 (-8.42% of base) : 82564.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -6 (-3.02% of base) : 219689.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -3 (-0.11% of base) : 233617.dasm - MemoryAlloc:SteadyState():this
          -1 (-0.40% of base) : 252220.dasm - RandomTwister64:.ctor(long):this

Top method regressions (percentages):
           8 ( 6.15% of base) : 239879.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (percentages):
         -25 (-8.42% of base) : 82564.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -6 (-3.02% of base) : 219689.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -1 (-0.40% of base) : 252220.dasm - RandomTwister64:.ctor(long):this
          -3 (-0.11% of base) : 233617.dasm - MemoryAlloc:SteadyState():this

5 total methods with Code Size differences (4 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 34150239 (overridden on cmd)
Total bytes of diff: 34150175 (overridden on cmd)
Total bytes of delta: -64 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 131220.dasm (2.27% of base)
           3 : 35656.dasm (1.27% of base)

Top file improvements (bytes):
         -15 : 37875.dasm (-1.40% of base)
          -9 : 195624.dasm (-0.61% of base)
          -9 : 135309.dasm (-0.61% of base)
          -6 : 140739.dasm (-3.57% of base)
          -5 : 39037.dasm (-2.46% of base)
          -4 : 86594.dasm (-2.13% of base)
          -4 : 137057.dasm (-1.39% of base)
          -4 : 86560.dasm (-1.99% of base)
          -4 : 130850.dasm (-0.22% of base)
          -3 : 131218.dasm (-0.28% of base)
          -2 : 35664.dasm (-2.82% of base)
          -2 : 120179.dasm (-0.77% of base)
          -1 : 171290.dasm (-0.99% of base)
          -1 : 140741.dasm (-0.57% of base)
          -1 : 140993.dasm (-0.07% of base)
          -1 : 50057.dasm (-0.17% of base)

18 total files with Code Size differences (16 improved, 2 regressed), 0 unchanged.

Top method regressions (bytes):
           4 ( 2.27% of base) : 131220.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           3 ( 1.27% of base) : 35656.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (bytes):
         -15 (-1.40% of base) : 37875.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -9 (-0.61% of base) : 195624.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -9 (-0.61% of base) : 135309.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -6 (-3.57% of base) : 140739.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -5 (-2.46% of base) : 39037.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-0.22% of base) : 130850.dasm - <ReadDataAsync>d__504:MoveNext():this
          -4 (-2.13% of base) : 86594.dasm - NamespaceManager:ExitScope():this
          -4 (-1.99% of base) : 86560.dasm - NamespaceManager:ExitScope():this
          -4 (-1.39% of base) : 137057.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -3 (-0.28% of base) : 131218.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -2 (-2.82% of base) : 35664.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -2 (-0.77% of base) : 120179.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -1 (-0.57% of base) : 140741.dasm - System.Data.ExpressionParser:ScanDate():this
          -1 (-0.07% of base) : 140993.dasm - System.Data.Select:CreateIndex():this
          -1 (-0.17% of base) : 50057.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this
          -1 (-0.99% of base) : 171290.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this

Top method regressions (percentages):
           4 ( 2.27% of base) : 131220.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           3 ( 1.27% of base) : 35656.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this

Top method improvements (percentages):
          -6 (-3.57% of base) : 140739.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -2 (-2.82% of base) : 35664.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -5 (-2.46% of base) : 39037.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-2.13% of base) : 86594.dasm - NamespaceManager:ExitScope():this
          -4 (-1.99% of base) : 86560.dasm - NamespaceManager:ExitScope():this
         -15 (-1.40% of base) : 37875.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-1.39% of base) : 137057.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -1 (-0.99% of base) : 171290.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -2 (-0.77% of base) : 120179.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -9 (-0.61% of base) : 195624.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -9 (-0.61% of base) : 135309.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -1 (-0.57% of base) : 140741.dasm - System.Data.ExpressionParser:ScanDate():this
          -3 (-0.28% of base) : 131218.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -4 (-0.22% of base) : 130850.dasm - <ReadDataAsync>d__504:MoveNext():this
          -1 (-0.17% of base) : 50057.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this
          -1 (-0.07% of base) : 140993.dasm - System.Data.Select:CreateIndex():this

18 total methods with Code Size differences (16 improved, 2 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 45569892 (overridden on cmd)
Total bytes of diff: 45569840 (overridden on cmd)
Total bytes of delta: -52 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          12 : 106845.dasm (9.02% of base)
           6 : 214982.dasm (4.20% of base)
           4 : 135311.dasm (2.30% of base)
           3 : 108779.dasm (0.95% of base)
           1 : 223298.dasm (0.12% of base)

Top file improvements (bytes):
         -15 : 106218.dasm (-1.29% of base)
          -6 : 113352.dasm (-3.66% of base)
          -6 : 158416.dasm (-0.38% of base)
          -6 : 158407.dasm (-0.38% of base)
          -5 : 113350.dasm (-2.99% of base)
          -5 : 137506.dasm (-0.63% of base)
          -4 : 130412.dasm (-2.01% of base)
          -4 : 135615.dasm (-0.14% of base)
          -4 : 210975.dasm (-0.39% of base)
          -4 : 151328.dasm (-1.18% of base)
          -3 : 196153.dasm (-2.36% of base)
          -3 : 135313.dasm (-0.28% of base)
          -3 : 139586.dasm (-1.79% of base)
          -3 : 196156.dasm (-2.54% of base)
          -2 : 130379.dasm (-1.07% of base)
          -2 : 108771.dasm (-2.86% of base)
          -2 : 84423.dasm (-0.78% of base)
          -1 : 113081.dasm (-0.07% of base)

23 total files with Code Size differences (18 improved, 5 regressed), 0 unchanged.

Top method regressions (bytes):
          12 ( 9.02% of base) : 106845.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           6 ( 4.20% of base) : 214982.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           4 ( 2.30% of base) : 135311.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           3 ( 0.95% of base) : 108779.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
           1 ( 0.12% of base) : 223298.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,long):this

Top method improvements (bytes):
         -15 (-1.29% of base) : 106218.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -6 (-0.38% of base) : 158407.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -6 (-0.38% of base) : 158416.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
          -6 (-3.66% of base) : 113352.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -5 (-2.99% of base) : 113350.dasm - System.Data.ExpressionParser:ScanDate():this
          -5 (-0.63% of base) : 137506.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-0.14% of base) : 135615.dasm - <ReadDataAsync>d__504:MoveNext():this
          -4 (-2.01% of base) : 130412.dasm - NamespaceManager:ExitScope():this
          -4 (-1.18% of base) : 151328.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -4 (-0.39% of base) : 210975.dasm - System.Uri:CreateUriInfo(long):this
          -3 (-2.36% of base) : 196153.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -3 (-2.54% of base) : 196156.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -3 (-1.79% of base) : 139586.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -3 (-0.28% of base) : 135313.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -2 (-1.07% of base) : 130379.dasm - NamespaceManager:ExitScope():this
          -2 (-2.86% of base) : 108771.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -2 (-0.78% of base) : 84423.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -1 (-0.07% of base) : 113081.dasm - System.Data.Select:CreateIndex():this

Top method regressions (percentages):
          12 ( 9.02% of base) : 106845.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
           6 ( 4.20% of base) : 214982.dasm - System.Runtime.Serialization.ObjectHolderListEnumerator:MoveNext():bool:this
           4 ( 2.30% of base) : 135311.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           3 ( 0.95% of base) : 108779.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
           1 ( 0.12% of base) : 223298.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,long):this

Top method improvements (percentages):
          -6 (-3.66% of base) : 113352.dasm - System.Data.ExpressionParser:ScanString(ushort):this
          -5 (-2.99% of base) : 113350.dasm - System.Data.ExpressionParser:ScanDate():this
          -2 (-2.86% of base) : 108771.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -3 (-2.54% of base) : 196156.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -3 (-2.36% of base) : 196153.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-2.01% of base) : 130412.dasm - NamespaceManager:ExitScope():this
          -3 (-1.79% of base) : 139586.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
         -15 (-1.29% of base) : 106218.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-1.18% of base) : 151328.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -2 (-1.07% of base) : 130379.dasm - NamespaceManager:ExitScope():this
          -2 (-0.78% of base) : 84423.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
          -5 (-0.63% of base) : 137506.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-0.39% of base) : 210975.dasm - System.Uri:CreateUriInfo(long):this
          -6 (-0.38% of base) : 158407.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -6 (-0.38% of base) : 158416.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
          -3 (-0.28% of base) : 135313.dasm - System.Xml.XmlTextReaderImpl:ReadData():int:this
          -4 (-0.14% of base) : 135615.dasm - <ReadDataAsync>d__504:MoveNext():this
          -1 (-0.07% of base) : 113081.dasm - System.Data.Select:CreateIndex():this

23 total methods with Code Size differences (18 improved, 5 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 113764434 (overridden on cmd)
Total bytes of diff: 113764157 (overridden on cmd)
Total bytes of delta: -277 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 105570.dasm (0.09% of base)

Top file improvements (bytes):
        -136 : 274331.dasm (-72.34% of base)
        -126 : 191933.dasm (-36.63% of base)
          -5 : 12345.dasm (-1.11% of base)
          -5 : 12332.dasm (-1.12% of base)
          -3 : 119429.dasm (-1.03% of base)
          -2 : 65258.dasm (-0.54% of base)
          -1 : 134402.dasm (-0.04% of base)
          -1 : 214176.dasm (-0.56% of base)

9 total files with Code Size differences (8 improved, 1 regressed), 0 unchanged.

Top method regressions (bytes):
           2 ( 0.09% of base) : 105570.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (bytes):
        -136 (-72.34% of base) : 274331.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -126 (-36.63% of base) : 191933.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -5 (-1.12% of base) : 12332.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.11% of base) : 12345.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.03% of base) : 119429.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -2 (-0.54% of base) : 65258.dasm - <>c__DisplayClass1_0:<Send_NullRequest_ThrowsException>b__1():System.Threading.Tasks.Task:this
          -1 (-0.04% of base) : 134402.dasm - <PathsTo>d__25:MoveNext():bool:this
          -1 (-0.56% of base) : 214176.dasm - BufferWriter:Write(ushort):this

Top method regressions (percentages):
           2 ( 0.09% of base) : 105570.dasm - <TestData>d__7:MoveNext():bool:this

Top method improvements (percentages):
        -136 (-72.34% of base) : 274331.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -126 (-36.63% of base) : 191933.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -5 (-1.12% of base) : 12332.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[__Canon,Nullable`1],ValueOrListBucket[__Canon,Nullable`1]):this
          -5 (-1.11% of base) : 12345.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.ctor(int,ValueOrListBucket[Byte,Nullable`1],ValueOrListBucket[Byte,Nullable`1]):this
          -3 (-1.03% of base) : 119429.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -1 (-0.56% of base) : 214176.dasm - BufferWriter:Write(ushort):this
          -2 (-0.54% of base) : 65258.dasm - <>c__DisplayClass1_0:<Send_NullRequest_ThrowsException>b__1():System.Threading.Tasks.Task:this
          -1 (-0.04% of base) : 134402.dasm - <PathsTo>d__25:MoveNext():bool:this

9 total methods with Code Size differences (8 improved, 1 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

