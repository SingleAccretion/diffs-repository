## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 11398276 (overridden on cmd)
Total bytes of diff: 11392831 (overridden on cmd)
Total bytes of delta: -5445 (-0.05 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -196 : 16020.dasm (-9.12% of base)
         -92 : 6785.dasm (-6.31% of base)
         -60 : 5996.dasm (-7.54% of base)
         -36 : 2905.dasm (-7.88% of base)
         -17 : 1259.dasm (-0.17% of base)
         -17 : 11773.dasm (-3.66% of base)
         -16 : 38992.dasm (-1.06% of base)
         -13 : 23226.dasm (-0.91% of base)
         -12 : 18588.dasm (-0.30% of base)
         -12 : 20575.dasm (-0.66% of base)
         -12 : 7953.dasm (-0.10% of base)
         -10 : 4914.dasm (-0.84% of base)
          -8 : 18592.dasm (-0.36% of base)
          -8 : 13571.dasm (-0.23% of base)
          -8 : 3103.dasm (-0.37% of base)
          -7 : 20555.dasm (-1.38% of base)
          -7 : 6691.dasm (-5.65% of base)
          -7 : 6255.dasm (-0.32% of base)
          -6 : 19266.dasm (-0.27% of base)
          -6 : 18613.dasm (-0.19% of base)

4582 total files with Code Size differences (4582 improved, 0 regressed), 29 unchanged.

Top method improvements (bytes):
        -196 (-9.12% of base) : 16020.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
         -92 (-6.31% of base) : 6785.dasm - System.Text.RegularExpressions.RegexCharClass:OneToStringClass(ushort,System.Globalization.CultureInfo,byref):System.String
         -60 (-7.54% of base) : 5996.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -36 (-7.88% of base) : 2905.dasm - Jil.Common.ExtensionMethods:JsonEscape(ushort,bool):System.String
         -17 (-0.17% of base) : 1259.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)
         -17 (-3.66% of base) : 11773.dasm - System.Diagnostics.Tracing.ManifestBuilder:GetTypeName(System.Type):System.String:this
         -16 (-1.06% of base) : 38992.dasm - System.DateTimeParse:ParseFormatO(System.ReadOnlySpan`1[Char],byref):bool
         -13 (-0.91% of base) : 23226.dasm - System.DateTimeParse:ParseFormatR(System.ReadOnlySpan`1[Char],byref,byref):bool
         -12 (-0.66% of base) : 20575.dasm - DynamicClass:ReadCollectionsOfPrimitivesFromJson(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.Json.XmlObjectSerializerReadContextComplexJson,System.Xml.XmlDictionaryString,System.Xml.XmlDictionaryString[]):System.Object
         -12 (-0.30% of base) : 18588.dasm - DynamicClass:ReadMyEventsListerItemFromJson(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.Json.XmlObjectSerializerReadContextComplexJson,System.Xml.XmlDictionaryString,System.Xml.XmlDictionaryString[]):System.Object
         -12 (-0.10% of base) : 7953.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -10 (-0.84% of base) : 4914.dasm - System.Drawing.Imaging.ImageFormat:ToString():System.String:this
          -8 (-0.23% of base) : 13571.dasm - DynamicClass:ReadActiveOrUpcomingEventFromJson(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.Json.XmlObjectSerializerReadContextComplexJson,System.Xml.XmlDictionaryString,System.Xml.XmlDictionaryString[]):System.Object
          -8 (-0.36% of base) : 18592.dasm - DynamicClass:ReadMyEventsListerItemTaskFromJson(System.Runtime.Serialization.XmlReaderDelegator,System.Runtime.Serialization.Json.XmlObjectSerializerReadContextComplexJson,System.Xml.XmlDictionaryString,System.Xml.XmlDictionaryString[]):System.Object
          -8 (-0.37% of base) : 3103.dasm - System.Uri:GetUriPartsFromUserString(int):System.String:this
          -7 (-1.38% of base) : 20555.dasm - CriticalHelper:TryWritePrimitiveArray(System.Type,System.Type,System.Reflection.Emit.LocalBuilder,System.Reflection.Emit.LocalBuilder):bool:this
          -7 (-5.65% of base) : 6691.dasm - Newtonsoft.Json.JsonConvert:.cctor()
          -7 (-0.32% of base) : 6255.dasm - System.Reflection.Metadata.MetadataReader:InitializeStreamReaders(byref,System.Reflection.Metadata.Ecma335.StreamHeader[],byref,byref,byref):this
          -6 (-0.60% of base) : 20120.dasm - BenchmarksGame.RegexRedux_1:RunBench():int:this
          -6 (-0.19% of base) : 18613.dasm - CriticalHelper:ReadCollection(System.Runtime.Serialization.CollectionDataContract):this

Top method improvements (percentages):
          -1 (-14.29% of base) : 17915.dasm - Microsoft.Cci.RootModuleType:get_Name():System.String:this
          -1 (-14.29% of base) : 17913.dasm - Microsoft.Cci.RootModuleType:Microsoft.Cci.INamespaceTypeReference.get_NamespaceName():System.String:this
          -1 (-14.29% of base) : 17102.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SynthesizedInstanceConstructor:get_Name():System.String:this
          -1 (-14.29% of base) : 16350.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode:get_Language():System.String:this
          -1 (-14.29% of base) : 1908.dasm - System.Environment:get_NewLine():System.String
          -1 (-14.29% of base) : 13543.dasm - System.Runtime.Serialization.BooleanDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 12227.dasm - System.Runtime.Serialization.BooleanDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 20574.dasm - System.Runtime.Serialization.ByteArrayDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 9419.dasm - System.Runtime.Serialization.ByteArrayDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 13572.dasm - System.Runtime.Serialization.DateTimeDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 13529.dasm - System.Runtime.Serialization.DateTimeDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 11619.dasm - System.Runtime.Serialization.IntDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 9548.dasm - System.Runtime.Serialization.IntDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 13573.dasm - System.Runtime.Serialization.ShortDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 13531.dasm - System.Runtime.Serialization.ShortDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 11607.dasm - System.Runtime.Serialization.StringDataContract:get_ReadMethodName():System.String:this
          -1 (-14.29% of base) : 9549.dasm - System.Runtime.Serialization.StringDataContract:get_WriteMethodName():System.String:this
          -1 (-14.29% of base) : 10348.dasm - System.Security.Cryptography.HashAlgorithmName:get_SHA256():System.Security.Cryptography.HashAlgorithmName
          -1 (-14.29% of base) : 11226.dasm - System.Security.Cryptography.HashAlgorithmName:get_SHA384():System.Security.Cryptography.HashAlgorithmName
          -1 (-14.29% of base) : 12069.dasm - System.Security.Cryptography.HashAlgorithmName:get_SHA512():System.Security.Cryptography.HashAlgorithmName

4582 total methods with Code Size differences (4582 improved, 0 regressed), 29 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 113740422 (overridden on cmd)
Total bytes of diff: 113696421 (overridden on cmd)
Total bytes of delta: -44001 (-0.04 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -183 : 243381.dasm (-5.23% of base)
         -49 : 218538.dasm (-0.05% of base)
         -32 : 217469.dasm (-1.07% of base)
         -32 : 238041.dasm (-1.07% of base)
         -23 : 198436.dasm (-0.70% of base)
         -17 : 229231.dasm (-0.60% of base)
         -15 : 238151.dasm (-1.72% of base)
         -15 : 238206.dasm (-2.48% of base)
         -14 : 163830.dasm (-0.07% of base)
         -14 : 209778.dasm (-2.46% of base)
         -13 : 246002.dasm (-0.23% of base)
         -11 : 234358.dasm (-0.23% of base)
         -11 : 259972.dasm (-5.07% of base)
         -11 : 163851.dasm (-0.40% of base)
         -10 : 246839.dasm (-5.41% of base)
         -10 : 259960.dasm (-5.21% of base)
         -10 : 238264.dasm (-0.07% of base)
         -10 : 149915.dasm (-0.47% of base)
         -10 : 229226.dasm (-0.19% of base)
         -10 : 229227.dasm (-0.20% of base)

32908 total files with Code Size differences (32908 improved, 0 regressed), 19 unchanged.

Top method improvements (bytes):
        -183 (-5.23% of base) : 243381.dasm - StringVersionClass:Main(System.String[]):int
         -49 (-0.05% of base) : 218538.dasm - testout1:Func_0():int
         -32 (-1.07% of base) : 217469.dasm - FloatOvfToInt:PrintValues()
         -32 (-1.07% of base) : 238041.dasm - FloatOvfToInt:PrintValues()
         -23 (-0.70% of base) : 198436.dasm - TailcallVerify.Program:PrintOutRunTestsFile()
         -17 (-0.60% of base) : 229231.dasm - VectorTest:Main():int
         -15 (-1.72% of base) : 238151.dasm - Node:.ctor():this
         -15 (-2.48% of base) : 238206.dasm - Node:.ctor():this
         -14 (-2.46% of base) : 209778.dasm - Internal.IL.StackValue:TypeToStringForByRef(Internal.TypeSystem.TypeDesc):System.String
         -14 (-0.07% of base) : 163830.dasm - ReliabilityConfig:GetTestsToRun(System.String):this
         -13 (-0.23% of base) : 246002.dasm - EventPipeTests.EventPipe:ValidateAllTypesEvent(Microsoft.Diagnostics.Tracing.TraceEvent):bool
         -11 (-0.40% of base) : 163851.dasm - ReliabilityFramework:RunReliabilityTests(System.String,bool):int:this
         -11 (-0.23% of base) : 234358.dasm - ScanProjectFiles:ParseAndUpdateProj(System.String,bool):bool
         -11 (-5.07% of base) : 259972.dasm - Test_test3:Main():int
         -10 (-5.41% of base) : 246839.dasm - ConcatTest:.cctor()
         -10 (-1.00% of base) : 213236.dasm - HVATests`1[Byte][System.Byte]:Init_HVAs():this
         -10 (-5.71% of base) : 233302.dasm - StringConcat:.cctor()
         -10 (-5.21% of base) : 259960.dasm - Test_struct6_2:Main():int
         -10 (-0.07% of base) : 238264.dasm - testout1:Func_0():int
         -10 (-0.47% of base) : 149915.dasm - testout1:Func_0_5_6_2_5():double

Top method improvements (percentages):
          -1 (-14.29% of base) : 86959.dasm - <Module>:f()
          -1 (-14.29% of base) : 243493.dasm - A.T2Exp:Func2():System.String:this
          -1 (-14.29% of base) : 243494.dasm - A.T3_1:Func3():System.String:this
          -1 (-14.29% of base) : 60616.dasm - A:f1():System.String:this
          -1 (-14.29% of base) : 60625.dasm - A:f10():System.String:this
          -1 (-14.29% of base) : 60523.dasm - A:f100():System.String:this
          -1 (-14.29% of base) : 59631.dasm - A:f1000():System.String:this
          -1 (-14.29% of base) : 59632.dasm - A:f1001():System.String:this
          -1 (-14.29% of base) : 59633.dasm - A:f1002():System.String:this
          -1 (-14.29% of base) : 59634.dasm - A:f1003():System.String:this
          -1 (-14.29% of base) : 59635.dasm - A:f1004():System.String:this
          -1 (-14.29% of base) : 59636.dasm - A:f1005():System.String:this
          -1 (-14.29% of base) : 59637.dasm - A:f1006():System.String:this
          -1 (-14.29% of base) : 59638.dasm - A:f1007():System.String:this
          -1 (-14.29% of base) : 59639.dasm - A:f1008():System.String:this
          -1 (-14.29% of base) : 59640.dasm - A:f1009():System.String:this
          -1 (-14.29% of base) : 60524.dasm - A:f101():System.String:this
          -1 (-14.29% of base) : 59641.dasm - A:f1010():System.String:this
          -1 (-14.29% of base) : 59642.dasm - A:f1011():System.String:this
          -1 (-14.29% of base) : 59643.dasm - A:f1012():System.String:this

32908 total methods with Code Size differences (32908 improved, 0 regressed), 19 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 27895700 (overridden on cmd)
Total bytes of diff: 27852988 (overridden on cmd)
Total bytes of delta: -42712 (-0.15 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -255 : 72454.dasm (-7.69% of base)
        -205 : 132971.dasm (-4.94% of base)
        -195 : 20033.dasm (-7.69% of base)
        -175 : 212079.dasm (-5.08% of base)
         -97 : 105449.dasm (-7.57% of base)
         -93 : 128514.dasm (-5.53% of base)
         -69 : 132974.dasm (-1.28% of base)
         -61 : 160441.dasm (-2.44% of base)
         -59 : 165218.dasm (-6.38% of base)
         -59 : 169070.dasm (-6.38% of base)
         -59 : 198359.dasm (-6.38% of base)
         -55 : 123706.dasm (-7.30% of base)
         -44 : 35954.dasm (-7.39% of base)
         -43 : 134061.dasm (-2.48% of base)
         -41 : 175518.dasm (-5.36% of base)
         -41 : 169543.dasm (-5.36% of base)
         -39 : 144500.dasm (-5.38% of base)
         -37 : 153483.dasm (-4.17% of base)
         -36 : 31761.dasm (-0.25% of base)
         -35 : 140895.dasm (-1.75% of base)

31317 total files with Code Size differences (31317 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
        -255 (-7.69% of base) : 72454.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:GetText(ushort):System.String
        -205 (-4.94% of base) : 132971.dasm - Microsoft.CodeAnalysis.WellKnownTypes:.cctor()
        -195 (-7.69% of base) : 20033.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
        -175 (-5.08% of base) : 212079.dasm - System.Drawing.KnownColorNames:.cctor()
         -97 (-7.57% of base) : 105449.dasm - System.ThrowHelper:GetArgumentName(int):System.String
         -93 (-5.53% of base) : 128514.dasm - System.Text.RegularExpressions.RegexCharClass:OneToStringClass(ushort,System.Globalization.CultureInfo,byref):System.String
         -69 (-1.28% of base) : 132974.dasm - Microsoft.CodeAnalysis.WellKnownMembers:.cctor()
         -61 (-2.44% of base) : 160441.dasm - System.Runtime.Serialization.DictionaryGlobals:.cctor()
         -59 (-6.38% of base) : 165218.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -59 (-6.38% of base) : 169070.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -59 (-6.38% of base) : 198359.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -55 (-7.30% of base) : 123706.dasm - Microsoft.CSharp.RuntimeBinder.Syntax.TokenFacts:GetText(ubyte):System.String
         -44 (-7.39% of base) : 35954.dasm - System.Xml.Schema.XmlSchemaDatatype:TypeCodeToString(int):System.String:this
         -43 (-2.48% of base) : 134061.dasm - Microsoft.CodeAnalysis.SpecialTypes:.cctor()
         -41 (-5.36% of base) : 169543.dasm - HTTP_REQUEST_HEADER_ID:.cctor()
         -41 (-5.36% of base) : 175518.dasm - System.Net.HttpRequestHeaderExtensions:.cctor()
         -39 (-5.38% of base) : 144500.dasm - System.Data.Function:.cctor()
         -37 (-4.17% of base) : 153483.dasm - System.Linq.Expressions.DebugViewWriter:VisitBinary(System.Linq.Expressions.BinaryExpression):System.Linq.Expressions.Expression:this
         -36 (-0.25% of base) : 31761.dasm - System.Xml.Xsl.IlGen.XmlILMethods:.cctor()
         -35 (-1.75% of base) : 140895.dasm - System.Data.OleDb.OleDbSchemaGuid:GetTextFromValue(System.Guid):System.String

Top method improvements (percentages):
          -1 (-11.11% of base) : 177875.dasm - <>c:<get_ErrorsHeadingText>b__3_0():System.String:this
          -1 (-11.11% of base) : 177876.dasm - <>c:<get_RequiredWord>b__1_0():System.String:this
          -1 (-11.11% of base) : 177874.dasm - <>c:<get_UsageHeadingText>b__5_0():System.String:this
          -1 (-11.11% of base) : 177872.dasm - <>c:<get_VersionCommandText>b__9_0(bool):System.String:this
          -1 (-11.11% of base) : 67962.dasm - AnonymousDelegateTemplateSymbol:get_GeneratedNamePrefix():System.String:this
          -1 (-11.11% of base) : 5054.dasm - AnonymousTypePublicSymbol:get_MetadataName():System.String:this
          -1 (-11.11% of base) : 67933.dasm - AnonymousTypeTemplateSymbol:get_GeneratedNamePrefix():System.String:this
          -1 (-11.11% of base) : 129510.dasm - ArrayAddress:get_Name():System.String:this
          -1 (-11.11% of base) : 129513.dasm - ArrayConstructor:get_Name():System.String:this
          -1 (-11.11% of base) : 129512.dasm - ArrayGet:get_Name():System.String:this
          -1 (-11.11% of base) : 129508.dasm - ArraySet:get_Name():System.String:this
          -1 (-11.11% of base) : 66823.dasm - AsyncMethodToClassRewriter:get_ResumeLabelName():System.String:this
          -1 (-11.11% of base) : 129469.dasm - BasicBlock:GetDebuggerDisplay():System.String:this
          -1 (-11.11% of base) : 67477.dasm - BeginInvokeMethod:get_Name():System.String:this
          -1 (-11.11% of base) : 4749.dasm - BeginInvokeMethod:get_Name():System.String:this
          -1 (-11.11% of base) : 151746.dasm - Checked:get_InstructionName():System.String:this
          -1 (-11.11% of base) : 178485.dasm - CommandLine.Text.CopyrightInfo:get_CopyrightWord():System.String:this
          -1 (-11.11% of base) : 130553.dasm - ConstantValueBad:GetValueToDisplay():System.String:this
          -1 (-11.11% of base) : 67481.dasm - Constructor:get_Name():System.String:this
          -1 (-11.11% of base) : 4753.dasm - Constructor:get_Name():System.String:this

31317 total methods with Code Size differences (31317 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 36739058 (overridden on cmd)
Total bytes of diff: 36728562 (overridden on cmd)
Total bytes of delta: -10496 (-0.03 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
        -255 : 66691.dasm (-9.11% of base)
        -195 : 28119.dasm (-9.12% of base)
         -92 : 223719.dasm (-6.20% of base)
         -60 : 204394.dasm (-7.54% of base)
         -60 : 203555.dasm (-7.54% of base)
         -60 : 121652.dasm (-7.54% of base)
         -58 : 98982.dasm (-0.47% of base)
         -55 : 160157.dasm (-8.41% of base)
         -45 : 24265.dasm (-0.21% of base)
         -44 : 137218.dasm (-8.75% of base)
         -43 : 113760.dasm (-5.84% of base)
         -39 : 186460.dasm (-0.96% of base)
         -34 : 159527.dasm (-7.57% of base)
         -34 : 187002.dasm (-1.34% of base)
         -31 : 170008.dasm (-1.14% of base)
         -30 : 52408.dasm (-1.47% of base)
         -29 : 170157.dasm (-1.35% of base)
         -28 : 192734.dasm (-3.27% of base)
         -27 : 222451.dasm (-0.82% of base)
         -25 : 204642.dasm (-3.14% of base)

5630 total files with Code Size differences (5630 improved, 0 regressed), 39 unchanged.

Top method improvements (bytes):
        -255 (-9.11% of base) : 66691.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:GetText(ushort):System.String
        -195 (-9.12% of base) : 28119.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
         -92 (-6.20% of base) : 223719.dasm - System.Text.RegularExpressions.RegexCharClass:OneToStringClass(ushort,System.Globalization.CultureInfo,byref):System.String
         -60 (-7.54% of base) : 204394.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -60 (-7.54% of base) : 203555.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -60 (-7.54% of base) : 121652.dasm - System.Net.HttpStatusDescription:Get(int):System.String
         -58 (-0.47% of base) : 98982.dasm - Microsoft.Diagnostics.Tracing.Parsers.AspNet.AspNetTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
         -55 (-8.41% of base) : 160157.dasm - Microsoft.CSharp.RuntimeBinder.Syntax.TokenFacts:GetText(ubyte):System.String
         -45 (-0.21% of base) : 24265.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String,System.String,System.String):Microsoft.CodeAnalysis.CSharp.CSharpCommandLineArguments:this
         -44 (-8.75% of base) : 137218.dasm - System.Xml.Schema.XmlSchemaDatatype:TypeCodeToString(int):System.String:this
         -43 (-5.84% of base) : 113760.dasm - System.Data.Common.DbMetaDataColumnNames:.cctor()
         -39 (-0.96% of base) : 186460.dasm - System.Data.OleDb.NativeDBType:.cctor()
         -34 (-7.57% of base) : 159527.dasm - Microsoft.CSharp.RuntimeBinder.BinderHelper:GetCLROperatorName(int):System.String
         -34 (-1.34% of base) : 187002.dasm - System.Data.OleDb.OleDbSchemaGuid:GetTextFromValue(System.Guid):System.String
         -31 (-1.14% of base) : 170008.dasm - Microsoft.VisualBasic.VBCodeGenerator:GetBaseTypeOutput(System.CodeDom.CodeTypeReference,bool):System.String:this
         -30 (-1.47% of base) : 52408.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceMethodSymbol:GetMemberNameFromSyntax(Microsoft.CodeAnalysis.VisualBasic.Syntax.MethodBaseSyntax):System.String
         -29 (-1.35% of base) : 170157.dasm - Microsoft.CSharp.CSharpCodeGenerator:GetBaseTypeOutput(System.CodeDom.CodeTypeReference,bool):System.String:this
         -28 (-3.27% of base) : 192734.dasm - System.Drawing.ColorTranslator:ToHtml(System.Drawing.Color):System.String
         -27 (-0.82% of base) : 222451.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
         -25 (-3.14% of base) : 204642.dasm - System.Net.Http.WinHttpTraceHelper:GetStringFromInternetStatus(int):System.String

Top method improvements (percentages):
          -1 (-14.29% of base) : 156812.dasm - <>c:<get_ErrorsHeadingText>b__3_0():System.String:this
          -1 (-14.29% of base) : 156811.dasm - <>c:<get_RequiredWord>b__1_0():System.String:this
          -1 (-14.29% of base) : 156813.dasm - <>c:<get_UsageHeadingText>b__5_0():System.String:this
          -1 (-14.29% of base) : 156815.dasm - <>c:<get_VersionCommandText>b__9_0(bool):System.String:this
          -1 (-14.29% of base) : 71381.dasm - AnonymousDelegateTemplateSymbol:get_GeneratedNamePrefix():System.String:this
          -1 (-14.29% of base) : 71410.dasm - AnonymousTypeTemplateSymbol:get_GeneratedNamePrefix():System.String:this
          -1 (-14.29% of base) : 81957.dasm - ArrayAddress:get_Name():System.String:this
          -1 (-14.29% of base) : 81953.dasm - ArrayConstructor:get_Name():System.String:this
          -1 (-14.29% of base) : 81955.dasm - ArrayGet:get_Name():System.String:this
          -1 (-14.29% of base) : 81958.dasm - ArraySet:get_Name():System.String:this
          -1 (-14.29% of base) : 72482.dasm - AsyncMethodToClassRewriter:get_ResumeLabelName():System.String:this
          -1 (-14.29% of base) : 45989.dasm - BeginInvokeMethod:get_Name():System.String:this
          -1 (-14.29% of base) : 71868.dasm - BeginInvokeMethod:get_Name():System.String:this
          -1 (-14.29% of base) : 120102.dasm - Checked:get_InstructionName():System.String:this
          -1 (-14.29% of base) : 155912.dasm - CommandLine.Text.CopyrightInfo:get_CopyrightWord():System.String:this
          -1 (-14.29% of base) : 81145.dasm - ConstantValueBad:GetValueToDisplay():System.String:this
          -1 (-14.29% of base) : 71864.dasm - Constructor:get_Name():System.String:this
          -1 (-14.29% of base) : 195307.dasm - ContentTypeHelper:get_ContentTypeFileName():System.String
          -1 (-14.29% of base) : 221476.dasm - DSACng:get_SignatureAlgorithm():System.String:this
          -1 (-14.29% of base) : 45992.dasm - EndInvokeMethod:get_Name():System.String:this

5630 total methods with Code Size differences (5630 improved, 0 regressed), 39 unchanged.

```

</details>

--------------------------------------------------------------------------------

