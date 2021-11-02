## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 7633852 (overridden on cmd)
Total bytes of diff: 7633828 (overridden on cmd)
Total bytes of delta: -24 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 19933.dasm (0.53% of base)

Top file improvements (bytes):
          -8 : 12232.dasm (-2.67% of base)
          -8 : 7932.dasm (-2.86% of base)
          -4 : 6702.dasm (-2.00% of base)
          -4 : 3194.dasm (-1.45% of base)
          -4 : 7738.dasm (-0.36% of base)

6 total files with Code Size differences (5 improved, 1 regressed), 2 unchanged.

Top method regressions (bytes):
           4 ( 0.53% of base) : 19933.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (bytes):
          -8 (-2.67% of base) : 12232.dasm - NamespaceManager:ExitScope():this
          -8 (-2.86% of base) : 7932.dasm - NamespaceManager:ExitScope():this
          -4 (-1.45% of base) : 3194.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-0.36% of base) : 7738.dasm - System.Uri:CreateUriInfo(long):this
          -4 (-2.00% of base) : 6702.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method regressions (percentages):
           4 ( 0.53% of base) : 19933.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
          -8 (-2.86% of base) : 7932.dasm - NamespaceManager:ExitScope():this
          -8 (-2.67% of base) : 12232.dasm - NamespaceManager:ExitScope():this
          -4 (-2.00% of base) : 6702.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.45% of base) : 3194.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-0.36% of base) : 7738.dasm - System.Uri:CreateUriInfo(long):this

6 total methods with Code Size differences (5 improved, 1 regressed), 2 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 165278388 (overridden on cmd)
Total bytes of diff: 165278368 (overridden on cmd)
Total bytes of delta: -20 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 82669.dasm (-2.15% of base)
          -4 : 233435.dasm (-0.14% of base)
          -4 : 239569.dasm (-2.00% of base)
          -4 : 219512.dasm (-1.56% of base)

4 total files with Code Size differences (4 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -8 (-2.15% of base) : 82669.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -4 (-0.14% of base) : 233435.dasm - MemoryAlloc:SteadyState():this
          -4 (-1.56% of base) : 219512.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-2.00% of base) : 239569.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this

Top method improvements (percentages):
          -8 (-2.15% of base) : 82669.dasm - Test.AA:Method2(System.Boolean[],System.UInt32[],float,System.Object[],int)
          -4 (-2.00% of base) : 239569.dasm - V8.Richards.WorkerTask:run(V8.Richards.Packet):V8.Richards.TaskControlBlock:this
          -4 (-1.56% of base) : 219512.dasm - V8.Crypto.SecureRandom:rng_get_byte():ubyte:this
          -4 (-0.14% of base) : 233435.dasm - MemoryAlloc:SteadyState():this

4 total methods with Code Size differences (4 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51809972 (overridden on cmd)
Total bytes of diff: 51809904 (overridden on cmd)
Total bytes of delta: -68 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 144905.dasm (1.43% of base)
           4 : 138303.dasm (1.92% of base)
           4 : 110810.dasm (0.44% of base)

Top file improvements (bytes):
         -12 : 65791.dasm (-0.85% of base)
          -8 : 137933.dasm (-0.33% of base)
          -8 : 8603.dasm (-2.63% of base)
          -8 : 121961.dasm (-1.69% of base)
          -8 : 8639.dasm (-2.38% of base)
          -4 : 180160.dasm (-0.21% of base)
          -4 : 165751.dasm (-1.96% of base)
          -4 : 99894.dasm (-1.18% of base)
          -4 : 63613.dasm (-0.95% of base)
          -4 : 144907.dasm (-1.32% of base)
          -4 : 61806.dasm (-1.12% of base)
          -4 : 145158.dasm (-0.20% of base)
          -4 : 62005.dasm (-0.21% of base)
          -4 : 63621.dasm (-3.12% of base)

17 total files with Code Size differences (14 improved, 3 regressed), 1 unchanged.

Top method regressions (bytes):
           4 ( 1.43% of base) : 144905.dasm - System.Data.ExpressionParser:ScanString(ushort):this
           4 ( 0.44% of base) : 110810.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this
           4 ( 1.92% of base) : 138303.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this

Top method improvements (bytes):
         -12 (-0.85% of base) : 65791.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -8 (-0.33% of base) : 137933.dasm - <ReadDataAsync>d__504:MoveNext():this
          -8 (-2.63% of base) : 8603.dasm - NamespaceManager:ExitScope():this
          -8 (-2.38% of base) : 8639.dasm - NamespaceManager:ExitScope():this
          -8 (-1.69% of base) : 121961.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -4 (-0.21% of base) : 180160.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -4 (-0.21% of base) : 62005.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -4 (-1.18% of base) : 99894.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-3.12% of base) : 63621.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -4 (-0.95% of base) : 63613.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -4 (-1.32% of base) : 144907.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-0.20% of base) : 145158.dasm - System.Data.Select:CreateIndex():this
          -4 (-1.96% of base) : 165751.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -4 (-1.12% of base) : 61806.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this

Top method regressions (percentages):
           4 ( 1.92% of base) : 138303.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           4 ( 1.43% of base) : 144905.dasm - System.Data.ExpressionParser:ScanString(ushort):this
           4 ( 0.44% of base) : 110810.dasm - System.Globalization.HebrewCalendar:GetDatePart(long,int):int:this

Top method improvements (percentages):
          -4 (-3.12% of base) : 63621.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-2.63% of base) : 8603.dasm - NamespaceManager:ExitScope():this
          -8 (-2.38% of base) : 8639.dasm - NamespaceManager:ExitScope():this
          -4 (-1.96% of base) : 165751.dasm - System.Linq.Parallel.HashRepartitionStream`3:.ctor(int,System.Collections.Generic.IComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon],System.Collections.Generic.IEqualityComparer`1[System.__Canon]):this
          -8 (-1.69% of base) : 121961.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -4 (-1.32% of base) : 144907.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.18% of base) : 99894.dasm - HashtableEnumerator:MoveNext():bool:this
          -4 (-1.12% of base) : 61806.dasm - Utilities.Cache`2:GetFreeEntry():ushort:this
          -4 (-0.95% of base) : 63613.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
         -12 (-0.85% of base) : 65791.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -8 (-0.33% of base) : 137933.dasm - <ReadDataAsync>d__504:MoveNext():this
          -4 (-0.21% of base) : 180160.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -4 (-0.21% of base) : 62005.dasm - <ParsePgoData>d__6`1:MoveNext():bool:this
          -4 (-0.20% of base) : 145158.dasm - System.Data.Select:CreateIndex():this

17 total methods with Code Size differences (14 improved, 3 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 51524156 (overridden on cmd)
Total bytes of diff: 51524052 (overridden on cmd)
Total bytes of delta: -104 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 109691.dasm (1.72% of base)
           4 : 125138.dasm (1.96% of base)

Top file improvements (bytes):
         -12 : 102580.dasm (-0.95% of base)
          -8 : 120226.dasm (-2.86% of base)
          -8 : 219471.dasm (-0.86% of base)
          -8 : 105135.dasm (-6.67% of base)
          -8 : 127331.dasm (-0.84% of base)
          -8 : 120193.dasm (-2.67% of base)
          -8 : 137485.dasm (-2.11% of base)
          -4 : 189162.dasm (-2.17% of base)
          -4 : 105143.dasm (-0.93% of base)
          -4 : 231572.dasm (-0.23% of base)
          -4 : 103207.dasm (-1.89% of base)
          -4 : 129422.dasm (-1.89% of base)
          -4 : 141500.dasm (-0.23% of base)
          -4 : 231581.dasm (-0.23% of base)
          -4 : 109422.dasm (-0.23% of base)
          -4 : 82638.dasm (-1.19% of base)
          -4 : 109689.dasm (-1.82% of base)
          -4 : 189159.dasm (-2.08% of base)
          -4 : 141491.dasm (-0.23% of base)
          -4 : 203492.dasm (-0.36% of base)

22 total files with Code Size differences (20 improved, 2 regressed), 3 unchanged.

Top method regressions (bytes):
           4 ( 1.72% of base) : 109691.dasm - System.Data.ExpressionParser:ScanString(ushort):this
           4 ( 1.96% of base) : 125138.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this

Top method improvements (bytes):
         -12 (-0.95% of base) : 102580.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -8 (-2.86% of base) : 120226.dasm - NamespaceManager:ExitScope():this
          -8 (-2.67% of base) : 120193.dasm - NamespaceManager:ExitScope():this
          -8 (-6.67% of base) : 105135.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-0.86% of base) : 219471.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,long):this
          -8 (-2.11% of base) : 137485.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -8 (-0.84% of base) : 127331.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-0.23% of base) : 231572.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-0.23% of base) : 141491.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-0.23% of base) : 141500.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-0.23% of base) : 231581.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-0.93% of base) : 105143.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -4 (-1.89% of base) : 103207.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
          -4 (-1.82% of base) : 109689.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-0.23% of base) : 109422.dasm - System.Data.Select:CreateIndex():this
          -4 (-2.08% of base) : 189159.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-2.17% of base) : 189162.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-0.36% of base) : 203492.dasm - System.Uri:CreateUriInfo(long):this
          -4 (-1.89% of base) : 129422.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -4 (-1.19% of base) : 82638.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this

Top method regressions (percentages):
           4 ( 1.96% of base) : 125138.dasm - System.Xml.XmlTextReaderImpl:UnDecodeChars():this
           4 ( 1.72% of base) : 109691.dasm - System.Data.ExpressionParser:ScanString(ushort):this

Top method improvements (percentages):
          -8 (-6.67% of base) : 105135.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:EatWhitespace():this
          -8 (-2.86% of base) : 120226.dasm - NamespaceManager:ExitScope():this
          -8 (-2.67% of base) : 120193.dasm - NamespaceManager:ExitScope():this
          -4 (-2.17% of base) : 189162.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[Byte][System.Byte]:MoveNext():bool:this
          -8 (-2.11% of base) : 137485.dasm - System.Speech.Internal.Synthesis.AudioFileOut:.ctor(System.IO.Stream,System.Speech.AudioFormat.SpeechAudioFormatInfo,bool,System.Speech.Internal.IAsyncDispatch):this
          -4 (-2.08% of base) : 189159.dasm - System.Linq.Parallel.SynchronousChannelMergeEnumerator`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-1.89% of base) : 103207.dasm - Newtonsoft.Json.Utilities.CollectionUtils:FastReverse(System.Collections.Generic.List`1[Byte])
          -4 (-1.89% of base) : 129422.dasm - System.Xml.Schema.XmlSchemaValidator:Reset():this
          -4 (-1.82% of base) : 109689.dasm - System.Data.ExpressionParser:ScanDate():this
          -4 (-1.19% of base) : 82638.dasm - Utilities.Cache`2[Byte,__Canon][System.Byte,System.__Canon]:GetFreeEntry():ushort:this
         -12 (-0.95% of base) : 102580.dasm - Newtonsoft.Json.JsonTextReader:ParseComment(bool):this
          -4 (-0.93% of base) : 105143.dasm - Newtonsoft.Json.Linq.JsonPath.JPath:ReadRegexString():System.String:this
          -8 (-0.86% of base) : 219471.dasm - System.ServiceProcess.ServiceBase:ServiceMainCallback(int,long):this
          -8 (-0.84% of base) : 127331.dasm - System.Xml.DtdParser:ScanNmtoken():this
          -4 (-0.36% of base) : 203492.dasm - System.Uri:CreateUriInfo(long):this
          -4 (-0.23% of base) : 109422.dasm - System.Data.Select:CreateIndex():this
          -4 (-0.23% of base) : 231572.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-0.23% of base) : 141491.dasm - <ParsePgoData>d__6`1[__Canon][System.__Canon]:MoveNext():bool:this
          -4 (-0.23% of base) : 141500.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this
          -4 (-0.23% of base) : 231581.dasm - <ParsePgoData>d__6`1[Byte][System.Byte]:MoveNext():bool:this

22 total methods with Code Size differences (20 improved, 2 regressed), 3 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 117618140 (overridden on cmd)
Total bytes of diff: 117617828 (overridden on cmd)
Total bytes of delta: -312 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -152 : 276456.dasm (-70.37% of base)
        -148 : 325244.dasm (-38.54% of base)
          -4 : 104967.dasm (-0.19% of base)
          -4 : 118740.dasm (-0.99% of base)
          -4 : 352871.dasm (-1.47% of base)

5 total files with Code Size differences (5 improved, 0 regressed), 4 unchanged.

Top method improvements (bytes):
        -152 (-70.37% of base) : 276456.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -148 (-38.54% of base) : 325244.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -4 (-0.19% of base) : 104967.dasm - <TestData>d__7:MoveNext():bool:this
          -4 (-1.47% of base) : 352871.dasm - BufferWriter:Write(ushort):this
          -4 (-0.99% of base) : 118740.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this

Top method improvements (percentages):
        -152 (-70.37% of base) : 276456.dasm - System.ComponentModel.Tests.CancelEventArgsTests:Cancel_Set_GetReturnsExpected():this
        -148 (-38.54% of base) : 325244.dasm - System.Tests.PosixSignalContextTests:Cancel_Roundtrips():this
          -4 (-1.47% of base) : 352871.dasm - BufferWriter:Write(ushort):this
          -4 (-0.99% of base) : 118740.dasm - Microsoft.Build.Evaluation.Scanner:ParseInternalItemList():bool:this
          -4 (-0.19% of base) : 104967.dasm - <TestData>d__7:MoveNext():bool:this

5 total methods with Code Size differences (5 improved, 0 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

