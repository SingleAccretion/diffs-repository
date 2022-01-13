## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 10808619 (overridden on cmd)
Total bytes of diff: 10808517 (overridden on cmd)
Total bytes of delta: -102 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           1 : 1258.dasm (0.01% of base)
           1 : 12620.dasm (0.05% of base)

Top file improvements (bytes):
         -16 : 15086.dasm (-1.10% of base)
         -15 : 15112.dasm (-0.19% of base)
         -10 : 8133.dasm (-0.14% of base)
          -9 : 15266.dasm (-0.46% of base)
          -8 : 3893.dasm (-0.61% of base)
          -7 : 13179.dasm (-1.16% of base)
          -6 : 2904.dasm (-1.43% of base)
          -6 : 5993.dasm (-0.82% of base)
          -4 : 20915.dasm (-1.48% of base)
          -4 : 3002.dasm (-1.59% of base)
          -4 : 3086.dasm (-0.69% of base)
          -4 : 1429.dasm (-1.13% of base)
          -4 : 558.dasm (-1.24% of base)
          -4 : 36737.dasm (-0.57% of base)
          -3 : 13187.dasm (-0.20% of base)

17 total files with Code Size differences (15 improved, 2 regressed), 4547 unchanged.

Top method regressions (bytes):
           1 ( 0.05% of base) : 12620.dasm - DynamicClass:Regex1_Go(System.Text.RegularExpressions.RegexRunner)
           1 ( 0.01% of base) : 1258.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)

Top method improvements (bytes):
         -16 (-1.10% of base) : 15086.dasm - System.Number:TryParseUInt64IntegerStyle(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):int
         -15 (-0.19% of base) : 15112.dasm - DynamicClass:Regex1_Go(System.Text.RegularExpressions.RegexRunner)
         -10 (-0.14% of base) : 8133.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WriteLiteralStructMethod(System.Xml.Serialization.StructMapping):this
          -9 (-0.46% of base) : 15266.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
          -8 (-0.61% of base) : 3893.dasm - System.Buffers.Text.Utf8Formatter:TryFormatDateTimeO(System.DateTime,System.TimeSpan,System.Span`1[Byte],byref):bool
          -7 (-1.16% of base) : 13179.dasm - CriticalHelper:CreateObject(System.Runtime.Serialization.ClassDataContract):this
          -6 (-1.43% of base) : 2904.dasm - Jil.Common.ExtensionMethods:JsonEscape(ushort,bool):System.String
          -6 (-0.82% of base) : 5993.dasm - System.Net.HttpStatusDescription:Get(int):System.String
          -4 (-1.48% of base) : 20915.dasm - DynamicClass:Regex83_FindFirstChar(System.Text.RegularExpressions.RegexRunner):bool
          -4 (-1.13% of base) : 1429.dasm - ProtoBuf.Internal.DynamicStub:<SlowGet>g__ResolveProxies|9_1(System.Type):System.Type
          -4 (-0.57% of base) : 36737.dasm - System.Diagnostics.Tracing.EventSource:AddProviderEnumKind(System.Diagnostics.Tracing.ManifestBuilder,System.Reflection.FieldInfo,System.String)
          -4 (-1.59% of base) : 3002.dasm - System.Resources.ResourceManager:AddResourceSet(System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Resources.ResourceSet, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String,byref)
          -4 (-1.24% of base) : 558.dasm - System.String:Concat(System.String[]):System.String
          -4 (-0.69% of base) : 3086.dasm - System.Uri:ResolveHelper(System.Uri,System.Uri,byref,byref):System.Uri
          -3 (-0.20% of base) : 13187.dasm - CriticalHelper:ReadMembers(System.Runtime.Serialization.ClassDataContract,System.Boolean[],System.Reflection.Emit.Label[],System.Reflection.Emit.LocalBuilder,System.Reflection.Emit.LocalBuilder):int:this

Top method regressions (percentages):
           1 ( 0.05% of base) : 12620.dasm - DynamicClass:Regex1_Go(System.Text.RegularExpressions.RegexRunner)
           1 ( 0.01% of base) : 1258.dasm - DynamicClass:Regex2_Go(System.Text.RegularExpressions.RegexRunner)

Top method improvements (percentages):
          -4 (-1.59% of base) : 3002.dasm - System.Resources.ResourceManager:AddResourceSet(System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Resources.ResourceSet, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String,byref)
          -4 (-1.48% of base) : 20915.dasm - DynamicClass:Regex83_FindFirstChar(System.Text.RegularExpressions.RegexRunner):bool
          -6 (-1.43% of base) : 2904.dasm - Jil.Common.ExtensionMethods:JsonEscape(ushort,bool):System.String
          -4 (-1.24% of base) : 558.dasm - System.String:Concat(System.String[]):System.String
          -7 (-1.16% of base) : 13179.dasm - CriticalHelper:CreateObject(System.Runtime.Serialization.ClassDataContract):this
          -4 (-1.13% of base) : 1429.dasm - ProtoBuf.Internal.DynamicStub:<SlowGet>g__ResolveProxies|9_1(System.Type):System.Type
         -16 (-1.10% of base) : 15086.dasm - System.Number:TryParseUInt64IntegerStyle(System.ReadOnlySpan`1[Char],int,System.Globalization.NumberFormatInfo,byref):int
          -6 (-0.82% of base) : 5993.dasm - System.Net.HttpStatusDescription:Get(int):System.String
          -4 (-0.69% of base) : 3086.dasm - System.Uri:ResolveHelper(System.Uri,System.Uri,byref,byref):System.Uri
          -8 (-0.61% of base) : 3893.dasm - System.Buffers.Text.Utf8Formatter:TryFormatDateTimeO(System.DateTime,System.TimeSpan,System.Span`1[Byte],byref):bool
          -4 (-0.57% of base) : 36737.dasm - System.Diagnostics.Tracing.EventSource:AddProviderEnumKind(System.Diagnostics.Tracing.ManifestBuilder,System.Reflection.FieldInfo,System.String)
          -9 (-0.46% of base) : 15266.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
          -3 (-0.20% of base) : 13187.dasm - CriticalHelper:ReadMembers(System.Runtime.Serialization.ClassDataContract,System.Boolean[],System.Reflection.Emit.Label[],System.Reflection.Emit.LocalBuilder,System.Reflection.Emit.LocalBuilder):int:this
         -15 (-0.19% of base) : 15112.dasm - DynamicClass:Regex1_Go(System.Text.RegularExpressions.RegexRunner)
         -10 (-0.14% of base) : 8133.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WriteLiteralStructMethod(System.Xml.Serialization.StructMapping):this

17 total methods with Code Size differences (15 improved, 2 regressed), 4547 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 113514896 (overridden on cmd)
Total bytes of diff: 113514826 (overridden on cmd)
Total bytes of delta: -70 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          31 : 247360.dasm (0.93% of base)
          17 : 226419.dasm (0.88% of base)
           7 : 215129.dasm (0.35% of base)

Top file improvements (bytes):
         -32 : 234046.dasm (-1.25% of base)
         -32 : 234048.dasm (-1.25% of base)
         -24 : 234083.dasm (-1.20% of base)
          -4 : 87413.dasm (-1.09% of base)
          -4 : 96074.dasm (-0.52% of base)
          -4 : 206809.dasm (-1.92% of base)
          -4 : 172547.dasm (-1.88% of base)
          -4 : 206808.dasm (-1.78% of base)
          -4 : 219020.dasm (-1.78% of base)
          -4 : 219021.dasm (-1.92% of base)
          -3 : 200032.dasm (-0.19% of base)
          -3 : 244948.dasm (-0.17% of base)
          -3 : 250009.dasm (-0.09% of base)

16 total files with Code Size differences (13 improved, 3 regressed), 32879 unchanged.

Top method regressions (bytes):
          31 ( 0.93% of base) : 247360.dasm - Program:<Main>g__HuntFor|0_1(System.String,byref):bool
          17 ( 0.88% of base) : 226419.dasm - IntelHardwareIntrinsicTest:Main():int
           7 ( 0.35% of base) : 215129.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this

Top method improvements (bytes):
         -32 (-1.25% of base) : 234046.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -32 (-1.25% of base) : 234048.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -24 (-1.20% of base) : 234083.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
          -4 (-1.78% of base) : 206808.dasm - BinderTracingTests.Helpers:GetAssemblyInAppPath(System.String):System.String
          -4 (-1.78% of base) : 219020.dasm - BinderTracingTests.Helpers:GetAssemblyInAppPath(System.String):System.String
          -4 (-1.92% of base) : 206809.dasm - BinderTracingTests.Helpers:GetAssemblyInSubdirectoryPath(System.String):System.String
          -4 (-1.92% of base) : 219021.dasm - BinderTracingTests.Helpers:GetAssemblyInSubdirectoryPath(System.String):System.String
          -4 (-0.52% of base) : 96074.dasm - BoxTest.Test:Fibonacci2(System.Object,System.Object):System.Object:this
          -4 (-1.09% of base) : 87413.dasm - System.Collections.Generic.Dictionary`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:Remove(int):bool:this
          -4 (-1.88% of base) : 172547.dasm - TestAssemblyLoadContext:ExecuteAssemblyByName(System.String,System.String[]):int:this
          -3 (-0.19% of base) : 200032.dasm - EMFloatClass:InternalFPFToString(byref,InternalFPF):int
          -3 (-0.17% of base) : 244948.dasm - string1:ProcessJagged3DArray(System.String[][])
          -3 (-0.09% of base) : 250009.dasm - StringVersionClass:Main(System.String[]):int

Top method regressions (percentages):
          31 ( 0.93% of base) : 247360.dasm - Program:<Main>g__HuntFor|0_1(System.String,byref):bool
          17 ( 0.88% of base) : 226419.dasm - IntelHardwareIntrinsicTest:Main():int
           7 ( 0.35% of base) : 215129.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this

Top method improvements (percentages):
          -4 (-1.92% of base) : 206809.dasm - BinderTracingTests.Helpers:GetAssemblyInSubdirectoryPath(System.String):System.String
          -4 (-1.92% of base) : 219021.dasm - BinderTracingTests.Helpers:GetAssemblyInSubdirectoryPath(System.String):System.String
          -4 (-1.88% of base) : 172547.dasm - TestAssemblyLoadContext:ExecuteAssemblyByName(System.String,System.String[]):int:this
          -4 (-1.78% of base) : 206808.dasm - BinderTracingTests.Helpers:GetAssemblyInAppPath(System.String):System.String
          -4 (-1.78% of base) : 219020.dasm - BinderTracingTests.Helpers:GetAssemblyInAppPath(System.String):System.String
         -32 (-1.25% of base) : 234046.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -32 (-1.25% of base) : 234048.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
         -24 (-1.20% of base) : 234083.dasm - IntelHardwareIntrinsicTest.Program:Main(System.String[]):int
          -4 (-1.09% of base) : 87413.dasm - System.Collections.Generic.Dictionary`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:Remove(int):bool:this
          -4 (-0.52% of base) : 96074.dasm - BoxTest.Test:Fibonacci2(System.Object,System.Object):System.Object:this
          -3 (-0.19% of base) : 200032.dasm - EMFloatClass:InternalFPFToString(byref,InternalFPF):int
          -3 (-0.17% of base) : 244948.dasm - string1:ProcessJagged3DArray(System.String[][])
          -3 (-0.09% of base) : 250009.dasm - StringVersionClass:Main(System.String[]):int

16 total methods with Code Size differences (13 improved, 3 regressed), 32879 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 27767509 (overridden on cmd)
Total bytes of diff: 27767005 (overridden on cmd)
Total bytes of delta: -504 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -18 : 155786.dasm (-3.03% of base)
          -8 : 65191.dasm (-1.68% of base)
          -6 : 160122.dasm (-2.14% of base)
          -6 : 162923.dasm (-2.67% of base)
          -6 : 162972.dasm (-3.49% of base)
          -6 : 154977.dasm (-3.12% of base)
          -6 : 155071.dasm (-0.26% of base)
          -6 : 185014.dasm (-2.51% of base)
          -6 : 92344.dasm (-1.99% of base)
          -6 : 171539.dasm (-2.59% of base)
          -6 : 81968.dasm (-0.20% of base)
          -6 : 186457.dasm (-3.26% of base)
          -6 : 52185.dasm (-0.86% of base)
          -4 : 131832.dasm (-1.62% of base)
          -4 : 160120.dasm (-2.45% of base)
          -4 : 18041.dasm (-2.90% of base)
          -4 : 99204.dasm (-1.25% of base)
          -4 : 112597.dasm (-0.25% of base)
          -4 : 147851.dasm (-2.94% of base)
          -4 : 147868.dasm (-2.94% of base)

129 total files with Code Size differences (129 improved, 0 regressed), 31318 unchanged.

Top method improvements (bytes):
         -18 (-3.03% of base) : 155786.dasm - Microsoft.CodeAnalysis.CSharp.ExpressionLambdaRewriter:GetBinaryOperatorName(int,byref,byref,byref):System.String:this
          -8 (-1.68% of base) : 65191.dasm - System.Globalization.CultureInfo:get_Parent():System.Globalization.CultureInfo:this
          -6 (-2.51% of base) : 185014.dasm - ILCompiler.Reflection.ReadyToRun.StringTypeProviderBase`1:GetPrimitiveType(ubyte):System.String:this
          -6 (-2.14% of base) : 160122.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:BinaryOperatorNameFromSyntaxKindIfAny(ushort):System.String
          -6 (-3.12% of base) : 154977.dasm - Microsoft.CodeAnalysis.CSharp.SymbolDisplayVisitor:GetSpecialTypeName(byte):System.String
          -6 (-0.26% of base) : 155071.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
          -6 (-1.99% of base) : 92344.dasm - Microsoft.CodeAnalysis.VisualBasic.ExpressionLambdaRewriter:GetBinaryOperatorMethodName(int,bool):System.String:this
          -6 (-0.20% of base) : 81968.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:GetText(ushort):System.String
          -6 (-0.86% of base) : 52185.dasm - Microsoft.CSharp.RuntimeBinder.Syntax.TokenFacts:GetText(ubyte):System.String
          -6 (-3.26% of base) : 186457.dasm - Microsoft.Extensions.Logging.Console.AnsiParser:GetForegroundColorEscapeCode(int):System.String
          -6 (-2.59% of base) : 171539.dasm - System.Linq.ThrowHelper:GetArgumentString(int):System.String
          -6 (-3.49% of base) : 162972.dasm - System.Net.Http.Http2ProtocolException:GetName(int):System.String
          -6 (-2.67% of base) : 162923.dasm - System.Net.Http.Http3ProtocolException:GetName(long):System.String
          -4 (-1.53% of base) : 13460.dasm - <>c__DisplayClass32_0:<SetupCallbacks>b__47(Microsoft.Diagnostics.Tracing.Parsers.ClrPrivate.MulticoreJitMethodCodeReturnedPrivateTraceData):this
          -4 (-0.32% of base) : 140240.dasm - <GetEnumFieldsToEmit>d__66:MoveNext():bool:this
          -4 (-0.88% of base) : 76667.dasm - DocumentationCommentCompiler:GetElementNameOfWellKnownTag(int):System.String
          -4 (-2.45% of base) : 160120.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:UnaryOperatorNameFromSyntaxKindIfAny(ushort):System.String
          -4 (-2.94% of base) : 147653.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ConversionOperatorDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147851.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DelegateDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147868.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.EnumDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this

Top method improvements (percentages):
          -6 (-3.49% of base) : 162972.dasm - System.Net.Http.Http2ProtocolException:GetName(int):System.String
          -6 (-3.26% of base) : 186457.dasm - Microsoft.Extensions.Logging.Console.AnsiParser:GetForegroundColorEscapeCode(int):System.String
          -6 (-3.12% of base) : 154977.dasm - Microsoft.CodeAnalysis.CSharp.SymbolDisplayVisitor:GetSpecialTypeName(byte):System.String
         -18 (-3.03% of base) : 155786.dasm - Microsoft.CodeAnalysis.CSharp.ExpressionLambdaRewriter:GetBinaryOperatorName(int,byref,byref,byref):System.String:this
          -4 (-2.99% of base) : 86180.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExternalChecksumDirectiveTriviaSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.99% of base) : 89041.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147653.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ConversionOperatorDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147851.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DelegateDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147868.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.EnumDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147541.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.IndexerDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147670.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.OperatorDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.94% of base) : 147585.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.PropertyDeclarationSyntax:GetSlot(int):Microsoft.CodeAnalysis.GreenNode:this
          -4 (-2.90% of base) : 18041.dasm - Microsoft.Diagnostics.Tracing.Parsers.Clr.ThreadPoolWorkerThreadAdjustmentTraceData:PayloadValue(int):System.Object:this
          -4 (-2.88% of base) : 84242.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.ParameterSyntax:GetNodeSlot(int):Microsoft.CodeAnalysis.SyntaxNode:this
          -4 (-2.88% of base) : 15052.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftAntimalwareEngine.BehaviorMonitoringBmOpenProcessArgsTraceData:PayloadValue(int):System.Object:this
          -4 (-2.88% of base) : 24940.dasm - Microsoft.Diagnostics.Tracing.Parsers.Tpl.TaskCompletedArgs:PayloadValue(int):System.Object:this
          -4 (-2.86% of base) : 83342.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.ObjectCreationExpressionSyntax:GetNodeSlot(int):Microsoft.CodeAnalysis.SyntaxNode:this
          -4 (-2.86% of base) : 15731.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServer.Multidata35TemplateSATraceData:PayloadValue(int):System.Object:this
          -4 (-2.86% of base) : 15587.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServer.Multidata51TemplateATraceData:PayloadValue(int):System.Object:this
          -4 (-2.86% of base) : 15495.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServer.Multidata65TemplateATraceData:PayloadValue(int):System.Object:this

129 total methods with Code Size differences (129 improved, 0 regressed), 31318 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 36632879 (overridden on cmd)
Total bytes of diff: 36632520 (overridden on cmd)
Total bytes of delta: -359 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 166735.dasm (0.24% of base)
           7 : 16587.dasm (0.35% of base)
           1 : 209163.dasm (0.05% of base)
           1 : 92930.dasm (0.33% of base)
           1 : 92940.dasm (0.33% of base)
           1 : 93684.dasm (0.23% of base)

Top file improvements (bytes):
         -20 : 139408.dasm (-2.76% of base)
         -17 : 86253.dasm (-2.68% of base)
         -14 : 85840.dasm (-6.54% of base)
         -13 : 209176.dasm (-0.40% of base)
          -9 : 29743.dasm (-0.46% of base)
          -9 : 68300.dasm (-0.35% of base)
          -9 : 84419.dasm (-4.55% of base)
          -9 : 199313.dasm (-4.92% of base)
          -9 : 158737.dasm (-1.50% of base)
          -8 : 24733.dasm (-3.32% of base)
          -7 : 24739.dasm (-1.84% of base)
          -7 : 73821.dasm (-1.69% of base)
          -7 : 221620.dasm (-0.21% of base)
          -6 : 158105.dasm (-1.45% of base)
          -6 : 68765.dasm (-2.86% of base)
          -6 : 202208.dasm (-0.82% of base)
          -6 : 123217.dasm (-0.82% of base)
          -6 : 138773.dasm (-1.31% of base)
          -6 : 201366.dasm (-0.82% of base)
          -6 : 54544.dasm (-3.47% of base)

78 total files with Code Size differences (72 improved, 6 regressed), 5575 unchanged.

Top method regressions (bytes):
           8 ( 0.24% of base) : 166735.dasm - R2RTest.BuildFolderSet:WritePerFolderStatistics(System.IO.StreamWriter):this
           7 ( 0.35% of base) : 16587.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this
           1 ( 0.33% of base) : 92930.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.IpDadFailedArgs:PayloadValue(int):System.Object:this
           1 ( 0.33% of base) : 92940.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.IpDadSuccessfulArgs:PayloadValue(int):System.Object:this
           1 ( 0.23% of base) : 93684.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.task_0Args:PayloadValue(int):System.Object:this
           1 ( 0.05% of base) : 209163.dasm - System.Uri:GetUriPartsFromUserString(int):System.String:this

Top method improvements (bytes):
         -20 (-2.76% of base) : 139408.dasm - System.Xml.Schema.XmlNumeric10Converter:ToInt64(System.String):long:this
         -17 (-2.68% of base) : 86253.dasm - Microsoft.Diagnostics.Tracing.Stacks.TimeHistogramController:GetInfoForCharacterRange(int,int,Microsoft.Diagnostics.Tracing.Stacks.Histogram):System.String:this
         -14 (-6.54% of base) : 85840.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceActivity:ActivityKindToString(short):System.String
         -13 (-0.40% of base) : 209176.dasm - System.Uri:CombineUri(System.Uri,System.String,int):System.String
          -9 (-0.46% of base) : 29743.dasm - Microsoft.CodeAnalysis.CSharp.SyntaxFacts:GetText(ushort):System.String
          -9 (-0.35% of base) : 68300.dasm - Microsoft.CodeAnalysis.VisualBasic.SyntaxFacts:GetText(ushort):System.String
          -9 (-1.50% of base) : 158737.dasm - Microsoft.CSharp.RuntimeBinder.Syntax.TokenFacts:GetText(ubyte):System.String
          -9 (-4.55% of base) : 84419.dasm - PEFile.IMAGE_RESOURCE_DIRECTORY_ENTRY:GetTypeNameForTypeId(int):System.String
          -9 (-4.92% of base) : 199313.dasm - System.Linq.ThrowHelper:GetArgumentString(int):System.String
          -8 (-3.32% of base) : 24733.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:BinaryOperatorNameFromSyntaxKindIfAny(ushort):System.String
          -7 (-1.69% of base) : 73821.dasm - DocumentationCommentCompiler:GetElementNameOfWellKnownTag(int):System.String
          -7 (-1.84% of base) : 24739.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:BinaryOperatorNameFromOperatorKind(int):System.String
          -7 (-0.21% of base) : 221620.dasm - System.ServiceModel.Syndication.DateTimeHelper:NormalizeTimeZone(System.String,byref):System.String
          -6 (-3.06% of base) : 157071.dasm - ILCompiler.Reflection.ReadyToRun.StringTypeProviderBase`1[__Canon][System.__Canon]:GetPrimitiveType(ubyte):System.String:this
          -6 (-3.06% of base) : 157083.dasm - ILCompiler.Reflection.ReadyToRun.StringTypeProviderBase`1[Byte][System.Byte]:GetPrimitiveType(ubyte):System.String:this
          -6 (-2.86% of base) : 68765.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:TryGetOperatorName(int):System.String
          -6 (-3.47% of base) : 54544.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SpecialTypeExtensions:GetNativeCompilerVType(byte):System.String
          -6 (-1.45% of base) : 158105.dasm - Microsoft.CSharp.RuntimeBinder.BinderHelper:GetCLROperatorName(int):System.String
          -6 (-3.06% of base) : 200092.dasm - System.Management.ManagementClassGenerator:GetConversionFunction(int):System.String:this
          -6 (-0.82% of base) : 202208.dasm - System.Net.HttpStatusDescription:Get(int):System.String

Top method regressions (percentages):
           7 ( 0.35% of base) : 16587.dasm - Internal.TypeSystem.Ecma.EcmaField:InitializeFieldFlags(int):int:this
           1 ( 0.33% of base) : 92930.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.IpDadFailedArgs:PayloadValue(int):System.Object:this
           1 ( 0.33% of base) : 92940.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.IpDadSuccessfulArgs:PayloadValue(int):System.Object:this
           8 ( 0.24% of base) : 166735.dasm - R2RTest.BuildFolderSet:WritePerFolderStatistics(System.IO.StreamWriter):this
           1 ( 0.23% of base) : 93684.dasm - Microsoft.Diagnostics.Tracing.Parsers.MicrosoftWindowsTCPIP.task_0Args:PayloadValue(int):System.Object:this
           1 ( 0.05% of base) : 209163.dasm - System.Uri:GetUriPartsFromUserString(int):System.String:this

Top method improvements (percentages):
         -14 (-6.54% of base) : 85840.dasm - Microsoft.Diagnostics.Tracing.Etlx.TraceActivity:ActivityKindToString(short):System.String
          -9 (-4.92% of base) : 199313.dasm - System.Linq.ThrowHelper:GetArgumentString(int):System.String
          -9 (-4.55% of base) : 84419.dasm - PEFile.IMAGE_RESOURCE_DIRECTORY_ENTRY:GetTypeNameForTypeId(int):System.String
          -6 (-3.59% of base) : 223146.dasm - System.Text.RegularExpressions.ThrowHelper:GetStringForExceptionArgument(int):System.String
          -6 (-3.47% of base) : 54544.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SpecialTypeExtensions:GetNativeCompilerVType(byte):System.String
          -8 (-3.32% of base) : 24733.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:BinaryOperatorNameFromSyntaxKindIfAny(ushort):System.String
          -6 (-3.06% of base) : 157071.dasm - ILCompiler.Reflection.ReadyToRun.StringTypeProviderBase`1[__Canon][System.__Canon]:GetPrimitiveType(ubyte):System.String:this
          -6 (-3.06% of base) : 157083.dasm - ILCompiler.Reflection.ReadyToRun.StringTypeProviderBase`1[Byte][System.Byte]:GetPrimitiveType(ubyte):System.String:this
          -6 (-3.06% of base) : 200092.dasm - System.Management.ManagementClassGenerator:GetConversionFunction(int):System.String:this
          -4 (-2.94% of base) : 124439.dasm - System.Net.Http.Http2ProtocolException:GetName(int):System.String
          -4 (-2.90% of base) : 94877.dasm - Microsoft.Diagnostics.Tracing.Parsers.Kernel.CSwitchTraceData:ToString(int):System.Object:this
          -6 (-2.86% of base) : 68765.dasm - Microsoft.CodeAnalysis.VisualBasic.OverloadResolution:TryGetOperatorName(int):System.String
         -20 (-2.76% of base) : 139408.dasm - System.Xml.Schema.XmlNumeric10Converter:ToInt64(System.String):long:this
         -17 (-2.68% of base) : 86253.dasm - Microsoft.Diagnostics.Tracing.Stacks.TimeHistogramController:GetInfoForCharacterRange(int,int,Microsoft.Diagnostics.Tracing.Stacks.Histogram):System.String:this
          -4 (-2.01% of base) : 24738.dasm - Microsoft.CodeAnalysis.CSharp.OperatorFacts:UnaryOperatorNameFromOperatorKind(int):System.String
          -4 (-1.97% of base) : 208041.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 202569.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 204353.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 202069.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 200888.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String

78 total methods with Code Size differences (72 improved, 6 regressed), 5575 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 88283519 (overridden on cmd)
Total bytes of diff: 88282966 (overridden on cmd)
Total bytes of delta: -553 (-0.00 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           5 : 92677.dasm (0.25% of base)

Top file improvements (bytes):
         -21 : 327865.dasm (-0.89% of base)
         -16 : 293727.dasm (-2.14% of base)
         -12 : 199943.dasm (-2.33% of base)
          -9 : 304969.dasm (-1.51% of base)
          -9 : 11673.dasm (-3.05% of base)
          -9 : 308334.dasm (-1.51% of base)
          -9 : 182385.dasm (-1.51% of base)
          -9 : 132589.dasm (-4.55% of base)
          -9 : 60084.dasm (-1.51% of base)
          -9 : 309180.dasm (-1.51% of base)
          -7 : 334902.dasm (-0.26% of base)
          -7 : 128593.dasm (-1.68% of base)
          -7 : 335459.dasm (-1.40% of base)
          -6 : 10950.dasm (-1.39% of base)
          -6 : 152843.dasm (-0.21% of base)
          -6 : 299785.dasm (-0.82% of base)
          -6 : 178157.dasm (-0.82% of base)
          -6 : 187474.dasm (-2.82% of base)
          -6 : 5597.dasm (-3.68% of base)
          -6 : 256129.dasm (-2.32% of base)

127 total files with Code Size differences (126 improved, 1 regressed), 13224 unchanged.

Top method regressions (bytes):
           5 ( 0.25% of base) : 92677.dasm - System.Text.Json.Tests.JsonDocumentTests:EnsureResizeSucceeds()

Top method improvements (bytes):
         -21 (-0.89% of base) : 327865.dasm - System.Numerics.Tests.MyBigIntImp:DoUnaryOperatorMine(System.Numerics.BigInteger,System.String):System.Numerics.BigInteger
         -16 (-2.14% of base) : 293727.dasm - System.IO.Ports.Tests.ReadTo:Read_Timeout():this
         -12 (-2.33% of base) : 199943.dasm - System.Security.Cryptography.Tests.AsnEncodedDataTests:TestSubjectAlternativeName()
          -9 (-3.05% of base) : 11673.dasm - Microsoft.CodeAnalysis.CodeGeneration.CodeGenerationOperatorSymbol:GetMetadataName(int):System.String
          -9 (-4.55% of base) : 132589.dasm - Microsoft.Diagnostics.Runtime.Utilities.IMAGE_RESOURCE_DIRECTORY_ENTRY:GetTypeNameForTypeId(int):System.String
          -9 (-1.51% of base) : 304969.dasm - System.Net.Test.Common.LoopbackServer:GetStatusDescription(int):System.String
          -9 (-1.51% of base) : 308334.dasm - System.Net.Test.Common.LoopbackServer:GetStatusDescription(int):System.String
          -9 (-1.51% of base) : 182385.dasm - System.Net.Test.Common.LoopbackServer:GetStatusDescription(int):System.String
          -9 (-1.51% of base) : 60084.dasm - System.Net.Test.Common.LoopbackServer:GetStatusDescription(int):System.String
          -9 (-1.51% of base) : 309180.dasm - System.Net.Test.Common.LoopbackServer:GetStatusDescription(int):System.String
          -7 (-0.26% of base) : 334902.dasm - Emitter:GeneratePropMetadataInitFunc(System.Text.Json.SourceGeneration.TypeGenerationSpec):System.String:this
          -7 (-1.68% of base) : 128593.dasm - Microsoft.CodeAnalysis.VisualBasic.FindSymbols.VisualBasicDeclaredSymbolInfoFactoryService:GetSpecialTypeName(Microsoft.CodeAnalysis.VisualBasic.Syntax.PredefinedTypeSyntax):System.String
          -7 (-1.40% of base) : 335459.dasm - System.Text.RegularExpressions.Generator.RegexGenerator:DescribeLoop(System.Text.RegularExpressions.RegexNode):System.String
          -6 (-3.68% of base) : 5597.dasm - Microsoft.CodeAnalysis.Collections.Internal.ThrowHelper:GetArgumentName(int):System.String
          -6 (-1.39% of base) : 10950.dasm - Microsoft.CodeAnalysis.Diagnostics.Analyzers.NamingStyles.EditorConfigNamingStyleParser:ToEditorConfigString(SymbolKindOrTypeKind):System.String
          -6 (-2.32% of base) : 256129.dasm - Moq.ExpressionStringBuilder:ToStringOperator(int):System.String
          -6 (-0.21% of base) : 152843.dasm - System.Data.Tests.DataSetTest2:ReadXml_Strm5():this
          -6 (-0.82% of base) : 299785.dasm - System.Net.HttpStatusDescription:Get(int):System.String
          -6 (-0.82% of base) : 178157.dasm - System.Net.HttpStatusDescription:Get(int):System.String
          -6 (-2.82% of base) : 187474.dasm - System.Reflection.Metadata.Decoding.Tests.DisassemblingTypeProvider:GetPrimitiveType(ubyte):System.String:this

Top method regressions (percentages):
           5 ( 0.25% of base) : 92677.dasm - System.Text.Json.Tests.JsonDocumentTests:EnsureResizeSucceeds()

Top method improvements (percentages):
          -9 (-4.55% of base) : 132589.dasm - Microsoft.Diagnostics.Runtime.Utilities.IMAGE_RESOURCE_DIRECTORY_ENTRY:GetTypeNameForTypeId(int):System.String
          -6 (-3.68% of base) : 5597.dasm - Microsoft.CodeAnalysis.Collections.Internal.ThrowHelper:GetArgumentName(int):System.String
          -9 (-3.05% of base) : 11673.dasm - Microsoft.CodeAnalysis.CodeGeneration.CodeGenerationOperatorSymbol:GetMetadataName(int):System.String
          -4 (-3.01% of base) : 216048.dasm - System.Data.SqlClient.TdsEnums:GetSniContextEnumName(int):System.String
          -4 (-3.01% of base) : 220320.dasm - System.Data.SqlClient.TdsEnums:GetSniContextEnumName(int):System.String
          -4 (-2.92% of base) : 130486.dasm - ReduceTokensRewriter:GetTypeCharString(int):System.String
          -6 (-2.82% of base) : 187474.dasm - System.Reflection.Metadata.Decoding.Tests.DisassemblingTypeProvider:GetPrimitiveType(ubyte):System.String:this
         -12 (-2.33% of base) : 199943.dasm - System.Security.Cryptography.Tests.AsnEncodedDataTests:TestSubjectAlternativeName()
          -6 (-2.32% of base) : 256129.dasm - Moq.ExpressionStringBuilder:ToStringOperator(int):System.String
          -3 (-2.14% of base) : 118468.dasm - Microsoft.Build.Evaluation.Token:get_String():System.String:this
          -4 (-2.14% of base) : 128213.dasm - Microsoft.CodeAnalysis.VisualBasic.Extensions.SemanticModelExtensions:GenerateNameForArgumentWorker(Microsoft.CodeAnalysis.SemanticModel,Microsoft.CodeAnalysis.VisualBasic.Syntax.ArgumentSyntax,System.Threading.CancellationToken):System.String
         -16 (-2.14% of base) : 293727.dasm - System.IO.Ports.Tests.ReadTo:Read_Timeout():this
          -4 (-2.01% of base) : 345817.dasm - System.Xml.Tests.XmlBaseCharConvertTests1:XmlEncodeName4():int:this
          -4 (-2.01% of base) : 345824.dasm - System.Xml.Tests.XmlCombiningCharConvertTests1:XmlEncodeName1():int:this
          -4 (-2.01% of base) : 345833.dasm - System.Xml.Tests.XmlDigitCharConvertTests1:XmlEncodeName1():int:this
          -4 (-2.01% of base) : 345840.dasm - System.Xml.Tests.XmlEmbeddedNullCharConvertTests1:XmlEncodeName1():int:this
          -4 (-2.01% of base) : 345847.dasm - System.Xml.Tests.XmlIdeographicCharConvertTests1:XmlEncodeName():int:this
          -4 (-1.97% of base) : 225165.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 299636.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String
          -4 (-1.97% of base) : 177886.dasm - System.StringExtensions:SubstringTrim(System.String,int,int):System.String

127 total methods with Code Size differences (126 improved, 1 regressed), 13224 unchanged.

```

</details>

--------------------------------------------------------------------------------

