## benchmarks.run.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 8966133 (overridden on cmd)
Total bytes of diff: 8956573 (overridden on cmd)
Total bytes of delta: -9560 (-0.11 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          93 : 8893.dasm (9.88% of base)
          29 : 10692.dasm (3.80% of base)
          17 : 14574.dasm (1.32% of base)
          11 : 25328.dasm (2.22% of base)
           8 : 12258.dasm (2.24% of base)
           5 : 7693.dasm (1.01% of base)
           5 : 12610.dasm (1.04% of base)
           4 : 9718.dasm (2.55% of base)
           4 : 24803.dasm (2.72% of base)
           3 : 12888.dasm (0.49% of base)
           3 : 8562.dasm (0.47% of base)
           2 : 273.dasm (0.36% of base)
           2 : 14962.dasm (0.14% of base)
           1 : 24741.dasm (0.40% of base)
           1 : 2183.dasm (0.08% of base)

Top file improvements (bytes):
        -152 : 25788.dasm (-1.27% of base)
         -89 : 8308.dasm (-0.75% of base)
         -84 : 4812.dasm (-48.84% of base)
         -81 : 4813.dasm (-27.00% of base)
         -64 : 6687.dasm (-2.06% of base)
         -54 : 9494.dasm (-1.48% of base)
         -53 : 7868.dasm (-0.59% of base)
         -53 : 12623.dasm (-0.59% of base)
         -52 : 25388.dasm (-5.05% of base)
         -51 : 26569.dasm (-1.10% of base)
         -47 : 26197.dasm (-3.12% of base)
         -46 : 26210.dasm (-1.72% of base)
         -46 : 27694.dasm (-1.40% of base)
         -45 : 27090.dasm (-4.05% of base)
         -44 : 28134.dasm (-0.52% of base)
         -44 : 12622.dasm (-0.46% of base)
         -43 : 8344.dasm (-1.80% of base)
         -42 : 27374.dasm (-1.26% of base)
         -41 : 26089.dasm (-1.10% of base)
         -41 : 6134.dasm (-0.23% of base)

2537 total files with Code Size differences (2522 improved, 15 regressed), 30 unchanged.

Top method regressions (bytes):
          93 ( 9.88% of base) : 8893.dasm - System.Buffers.TlsOverPerCoreLockedStacksArrayPool`1[__Canon][System.__Canon]:Trim():bool:this
          29 ( 3.80% of base) : 10692.dasm - System.Runtime.Serialization.Formatters.Binary.ObjectWriter:Write(System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.String[],System.Type[],System.Object[],System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo[]):this
          17 ( 1.32% of base) : 14574.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:WriteNullable(System.Reflection.MemberInfo,System.Type,bool):this
          11 ( 2.22% of base) : 25328.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:GetNetModuleAttributes(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.CSharpAttributeData, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
           8 ( 2.24% of base) : 12258.dasm - System.TimeZoneInfo:GetUtcOffset(System.DateTime,int,CachedData):System.TimeSpan:this
           5 ( 1.01% of base) : 7693.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:BuildFromStringWithNewDelegate(byref):Jil.Deserialize.StringThunkDelegate`1[__Canon]:this
           5 ( 1.04% of base) : 12610.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:BuildWithNewDelegate(byref):System.Func`3[__Canon,Int32,__Canon]:this
           4 ( 2.72% of base) : 24803.dasm - Roslyn.Utilities.TextKeyedCache`1[__Canon][System.__Canon]:FindSharedEntry(System.Char[],int,int,int):SharedEntryValue[__Canon]:this
           4 ( 2.55% of base) : 9718.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.DateTime[],int,int):this
           3 ( 0.49% of base) : 12888.dasm - MontgomeryReducer:reduce(V8.Crypto.BigInteger):this
           3 ( 0.47% of base) : 8562.dasm - System.Xml.Serialization.TempAssemblyCache:Add(System.String,System.Type,System.Xml.Serialization.TempAssembly):this
           2 ( 0.36% of base) : 273.dasm - MemberInfoCache`1[__Canon][System.__Canon]:Insert(byref,System.String,int):this
           2 ( 0.14% of base) : 14962.dasm - System.Number:NumberToFloatingPointBitsSlow(byref,byref,int,int,int):long
           1 ( 0.40% of base) : 24741.dasm - Roslyn.Utilities.StringTable:Add(System.Char[],int,int):System.String:this
           1 ( 0.08% of base) : 2183.dasm - System.Reflection.Emit.TypeNameBuilder:AddAssemblyQualifiedName(System.Type,int):this

Top method improvements (bytes):
        -152 (-1.27% of base) : 25788.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):this
         -89 (-0.75% of base) : 8308.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -84 (-48.84% of base) : 4812.dasm - System.Drawing.Graphics:DrawBezier(System.Drawing.Pen,float,float,float,float,float,float,float,float):this
         -81 (-27.00% of base) : 4813.dasm - Gdip:GdipDrawBezier(System.Runtime.InteropServices.HandleRef,System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float):int
         -64 (-2.06% of base) : 6687.dasm - System.Security.Cryptography.CryptoConfig:get_DefaultNameHT():System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Object, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]
         -54 (-1.48% of base) : 9494.dasm - System.Runtime.Serialization.CollectionDataContract:IsCollectionOrTryCreate(System.Type,bool,byref,byref,bool):bool
         -53 (-0.59% of base) : 12623.dasm - Jil.Deserialize.Methods:ParseISO8601Date(System.IO.TextReader,System.Char[],int,int):System.DateTime
         -53 (-0.59% of base) : 7868.dasm - Jil.Deserialize.Methods:ParseISO8601DateThunkReader(byref,System.Char[],int,int):System.DateTime
         -52 (-5.05% of base) : 25388.dasm - Microsoft.CodeAnalysis.CompilationOptions:ValidateOptions(Microsoft.CodeAnalysis.PooledObjects.ArrayBuilder`1[[Microsoft.CodeAnalysis.Diagnostic, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CommonMessageProvider):this
         -51 (-1.10% of base) : 26569.dasm - Microsoft.CodeAnalysis.CSharp.CodeGen.CodeGenerator:EmitCallExpression(Microsoft.CodeAnalysis.CSharp.BoundCall,int):this
         -47 (-3.12% of base) : 26197.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CreateConversion(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.Conversion,bool,bool,Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -46 (-1.40% of base) : 27694.dasm - DynamicClass:Regex1_TryMatchAtCurrentPosition(System.Text.RegularExpressions.RegexRunner,System.ReadOnlySpan`1[Char]):bool
         -46 (-1.72% of base) : 26210.dasm - Microsoft.CodeAnalysis.CSharp.Binder:CheckValEscape(Microsoft.CodeAnalysis.SyntaxNode,Microsoft.CodeAnalysis.CSharp.BoundExpression,int,int,bool,Microsoft.CodeAnalysis.DiagnosticBag):bool
         -45 (-4.05% of base) : 27090.dasm - Microsoft.Cci.MetadataWriter:PopulateDeclSecurityTableRowsFor(System.Reflection.Metadata.EntityHandle,System.Collections.Generic.IEnumerable`1[SecurityAttribute]):this
         -44 (-0.52% of base) : 28134.dasm - Jil.Deserialize.Methods:_ReadISO8601Date(System.IO.TextReader,System.Char[]):System.DateTime
         -44 (-0.46% of base) : 12622.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffset(System.IO.TextReader,System.Char[]):System.DateTimeOffset
         -43 (-1.80% of base) : 8344.dasm - System.Xml.Serialization.TempAssembly:GenerateRefEmitAssembly(System.Xml.Serialization.XmlMapping[],System.Type[],System.String):System.Reflection.Assembly
         -42 (-1.26% of base) : 27374.dasm - CriticalHelper:ReadCollection(System.Runtime.Serialization.CollectionDataContract):this
         -41 (-0.36% of base) : 32650.dasm - Jil.Deserialize.Methods:_ReadISO8601DateThunkReader(byref,System.Char[]):System.DateTime
         -41 (-0.34% of base) : 7867.dasm - Jil.Deserialize.Methods:_ReadISO8601DateWithOffsetThunkReader(byref,System.Char[]):System.DateTimeOffset

Top method regressions (percentages):
          93 ( 9.88% of base) : 8893.dasm - System.Buffers.TlsOverPerCoreLockedStacksArrayPool`1[__Canon][System.__Canon]:Trim():bool:this
          29 ( 3.80% of base) : 10692.dasm - System.Runtime.Serialization.Formatters.Binary.ObjectWriter:Write(System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.String[],System.Type[],System.Object[],System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo[]):this
           4 ( 2.72% of base) : 24803.dasm - Roslyn.Utilities.TextKeyedCache`1[__Canon][System.__Canon]:FindSharedEntry(System.Char[],int,int,int):SharedEntryValue[__Canon]:this
           4 ( 2.55% of base) : 9718.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.DateTime[],int,int):this
           8 ( 2.24% of base) : 12258.dasm - System.TimeZoneInfo:GetUtcOffset(System.DateTime,int,CachedData):System.TimeSpan:this
          11 ( 2.22% of base) : 25328.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:GetNetModuleAttributes(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.CSharpAttributeData, Microsoft.CodeAnalysis.CSharp, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          17 ( 1.32% of base) : 14574.dasm - Jil.Serialize.InlineSerializer`1[__Canon][System.__Canon]:WriteNullable(System.Reflection.MemberInfo,System.Type,bool):this
           5 ( 1.04% of base) : 12610.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:BuildWithNewDelegate(byref):System.Func`3[__Canon,Int32,__Canon]:this
           5 ( 1.01% of base) : 7693.dasm - Jil.Deserialize.InlineDeserializer`1[__Canon][System.__Canon]:BuildFromStringWithNewDelegate(byref):Jil.Deserialize.StringThunkDelegate`1[__Canon]:this
           3 ( 0.49% of base) : 12888.dasm - MontgomeryReducer:reduce(V8.Crypto.BigInteger):this
           3 ( 0.47% of base) : 8562.dasm - System.Xml.Serialization.TempAssemblyCache:Add(System.String,System.Type,System.Xml.Serialization.TempAssembly):this
           1 ( 0.40% of base) : 24741.dasm - Roslyn.Utilities.StringTable:Add(System.Char[],int,int):System.String:this
           2 ( 0.36% of base) : 273.dasm - MemberInfoCache`1[__Canon][System.__Canon]:Insert(byref,System.String,int):this
           2 ( 0.14% of base) : 14962.dasm - System.Number:NumberToFloatingPointBitsSlow(byref,byref,int,int,int):long
           1 ( 0.08% of base) : 2183.dasm - System.Reflection.Emit.TypeNameBuilder:AddAssemblyQualifiedName(System.Type,int):this

Top method improvements (percentages):
         -84 (-48.84% of base) : 4812.dasm - System.Drawing.Graphics:DrawBezier(System.Drawing.Pen,float,float,float,float,float,float,float,float):this
         -81 (-27.00% of base) : 4813.dasm - Gdip:GdipDrawBezier(System.Runtime.InteropServices.HandleRef,System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float):int
         -10 (-25.64% of base) : 6718.dasm - System.Tests.Perf_Single:ToString(float):System.String:this
         -10 (-23.26% of base) : 10456.dasm - System.Tests.Perf_Single:ToStringWithFormat(float,System.String):System.String:this
         -10 (-16.95% of base) : 3927.dasm - System.Text.Json.Tests.Perf_Get:GetJsonBytes(float):System.Byte[]
         -10 (-15.15% of base) : 9115.dasm - System.Tests.Perf_Single:ToStringWithCultureInfo(float,System.Globalization.CultureInfo):System.String:this
          -5 (-14.29% of base) : 247.dasm - System.RuntimeType:GetMethodImpl(System.String,int,System.Reflection.Binder,int,System.Type[],System.Reflection.ParameterModifier[]):System.Reflection.MethodInfo:this
         -25 (-13.37% of base) : 2126.dasm - System.Collections.Generic.LargeArrayBuilder`1[__Canon][System.__Canon]:ToArray():System.__Canon[]:this
         -25 (-13.37% of base) : 856.dasm - System.Collections.Generic.LargeArrayBuilder`1[Double][System.Double]:ToArray():System.Double[]:this
          -4 (-12.12% of base) : 2959.dasm - System.Text.DecoderNLS:GetChars(System.Byte[],int,int,System.Char[],int):int:this
         -28 (-11.34% of base) : 30282.dasm - System.Text.StringBuilder:AppendSpanFormattable(float):System.Text.StringBuilder:this
          -7 (-11.29% of base) : 15207.dasm - <>c__DisplayClass16_0`4[Int32,__Canon,Int32,__Canon][System.Int32,System.__Canon,System.Int32,System.__Canon]:<Define>b__1(Microsoft.Extensions.Logging.ILogger,int,System.__Canon,int,System.__Canon,System.Exception):this
         -16 (-11.27% of base) : 24974.dasm - Microsoft.CodeAnalysis.CSharp.CSharpCompilationOptions:.ctor(int,bool,System.String,System.String,System.String,System.Collections.Generic.IEnumerable`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],int,bool,bool,System.String,System.String,System.Collections.Immutable.ImmutableArray`1[Byte],System.Nullable`1[Boolean],int,int,int,System.Collections.Generic.IEnumerable`1[[System.Collections.Generic.KeyValuePair`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.CodeAnalysis.ReportDiagnostic, Microsoft.CodeAnalysis, Version=2.10.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]], System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool,bool,Microsoft.CodeAnalysis.XmlReferenceResolver,Microsoft.CodeAnalysis.SourceReferenceResolver,Microsoft.CodeAnalysis.MetadataReferenceResolver,Microsoft.CodeAnalysis.AssemblyIdentityComparer,Microsoft.CodeAnalysis.StrongNameProvider,bool,ubyte):this
          -3 (-11.11% of base) : 8119.dasm - System.Collections.ObjectModel.Collection`1[__Canon][System.__Canon]:CopyTo(System.__Canon[],int):this
          -3 (-11.11% of base) : 8117.dasm - System.Collections.ObjectModel.Collection`1[__Canon][System.__Canon]:InsertItem(int,System.__Canon):this
          -3 (-11.11% of base) : 2488.dasm - System.Collections.ObjectModel.ReadOnlyCollection`1[__Canon][System.__Canon]:CopyTo(System.__Canon[],int):this
         -11 (-10.58% of base) : 31898.dasm - System.IO.Pipes.PipeStream:BeginRead(System.Byte[],int,int,System.AsyncCallback,System.Object):System.IAsyncResult:this
         -11 (-10.58% of base) : 31909.dasm - System.IO.Pipes.PipeStream:BeginWrite(System.Byte[],int,int,System.AsyncCallback,System.Object):System.IAsyncResult:this
          -2 (-10.53% of base) : 17134.dasm - System.Globalization.Ordinal:CompareStringIgnoreCaseNonAscii(byref,int,byref,int):int
          -3 (-10.34% of base) : 24735.dasm - Microsoft.CodeAnalysis.Text.StringText:CopyTo(int,System.Char[],int,int):this

2537 total methods with Code Size differences (2522 improved, 15 regressed), 30 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 115674113 (overridden on cmd)
Total bytes of diff: 115637107 (overridden on cmd)
Total bytes of delta: -37006 (-0.03 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           5 : 41994.dasm (0.21% of base)
           5 : 34777.dasm (0.21% of base)
           5 : 34788.dasm (0.21% of base)
           5 : 34802.dasm (0.21% of base)
           2 : 138.dasm (0.31% of base)
           2 : 136.dasm (0.31% of base)
           1 : 245934.dasm (0.13% of base)
           1 : 246170.dasm (0.16% of base)

Top file improvements (bytes):
       -1274 : 41705.dasm (-16.65% of base)
       -1020 : 41695.dasm (-13.32% of base)
        -836 : 20621.dasm (-5.29% of base)
        -760 : 41675.dasm (-11.66% of base)
        -730 : 41700.dasm (-8.88% of base)
        -700 : 46078.dasm (-8.54% of base)
        -680 : 45863.dasm (-7.47% of base)
        -490 : 53797.dasm (-12.23% of base)
        -480 : 34457.dasm (-17.71% of base)
        -450 : 207243.dasm (-10.33% of base)
        -434 : 242030.dasm (-0.41% of base)
        -360 : 46100.dasm (-14.63% of base)
        -310 : 207237.dasm (-8.75% of base)
        -270 : 26518.dasm (-4.08% of base)
        -270 : 26581.dasm (-4.11% of base)
        -250 : 34305.dasm (-37.76% of base)
        -198 : 36463.dasm (-0.03% of base)
        -190 : 17696.dasm (-2.81% of base)
        -190 : 18948.dasm (-2.83% of base)
        -180 : 207287.dasm (-7.56% of base)

12001 total files with Code Size differences (11993 improved, 8 regressed), 4 unchanged.

Top method regressions (bytes):
           5 ( 0.21% of base) : 34777.dasm - Test_doublearr_InnerProd.doublemm:TestEntryPoint():int
           5 ( 0.21% of base) : 34788.dasm - Test_doublearr_InnerProd.doublemm:TestEntryPoint():int
           5 ( 0.21% of base) : 41994.dasm - Test_intarr_InnerProd.intmm:TestEntryPoint():int
           5 ( 0.21% of base) : 34802.dasm - Test_intarr_InnerProd.intmm:TestEntryPoint():int
           2 ( 0.31% of base) : 136.dasm - Kernel32:GetModuleBaseName(Microsoft.Win32.SafeHandles.SafeProcessHandle,int,System.Char[],int):int
           2 ( 0.31% of base) : 138.dasm - Kernel32:GetModuleFileNameEx(Microsoft.Win32.SafeHandles.SafeProcessHandle,int,System.Char[],int):int
           1 ( 0.13% of base) : 245934.dasm - Internal.TypeSystem.DebugNameFormatter:AppendNameForNamespaceType(System.Text.StringBuilder,Internal.TypeSystem.DefType,int):Void:this
           1 ( 0.16% of base) : 246170.dasm - Internal.TypeSystem.TypeNameFormatter`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:AppendName(System.Text.StringBuilder,Internal.TypeSystem.TypeDesc,System.Nullable`1[Int32]):double:this

Top method improvements (bytes):
       -1274 (-16.65% of base) : 41705.dasm - _sub:main(System.String[]):int
       -1020 (-13.32% of base) : 41695.dasm - _mul:main(System.String[]):int
        -836 (-5.29% of base) : 20621.dasm - GitHub_18582:Test()
        -760 (-11.66% of base) : 41675.dasm - _div:main(System.String[]):int
        -730 (-8.88% of base) : 41700.dasm - _rem:main(System.String[]):int
        -700 (-8.54% of base) : 46078.dasm - _rem:main(System.String[]):int
        -680 (-7.47% of base) : 45863.dasm - _rem:main(System.String[]):int
        -490 (-12.23% of base) : 53797.dasm - _add:main(System.String[]):int
        -480 (-17.71% of base) : 34457.dasm - Test_r4_cs.test:TestEntryPoint():int
        -450 (-10.33% of base) : 207243.dasm - GenericsTest:TestPoint4F()
        -434 (-0.41% of base) : 242030.dasm - Program:Main(System.String[]):int
        -360 (-14.63% of base) : 46100.dasm - SimpleVector3:Vector3GetHashCodeTest()
        -310 (-8.75% of base) : 207237.dasm - GenericsTest:TestPoint3F()
        -270 (-4.08% of base) : 26518.dasm - TestApp:RunAllTests():int
        -270 (-4.11% of base) : 26581.dasm - TestApp:RunAllTests():int
        -250 (-37.76% of base) : 34305.dasm - MathFusedMultiplyAddTest.Program:TestFloats()
        -198 (-0.03% of base) : 36463.dasm - Repro.Program:Test(int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int):int
        -190 (-2.81% of base) : 17696.dasm - TestApp:RunAllTests():int
        -190 (-2.83% of base) : 18948.dasm - TestApp:RunAllTests():int
        -180 (-7.56% of base) : 207287.dasm - GenericsTest:TestPoint2F()

Top method regressions (percentages):
           2 ( 0.31% of base) : 136.dasm - Kernel32:GetModuleBaseName(Microsoft.Win32.SafeHandles.SafeProcessHandle,int,System.Char[],int):int
           2 ( 0.31% of base) : 138.dasm - Kernel32:GetModuleFileNameEx(Microsoft.Win32.SafeHandles.SafeProcessHandle,int,System.Char[],int):int
           5 ( 0.21% of base) : 41994.dasm - Test_intarr_InnerProd.intmm:TestEntryPoint():int
           5 ( 0.21% of base) : 34802.dasm - Test_intarr_InnerProd.intmm:TestEntryPoint():int
           5 ( 0.21% of base) : 34777.dasm - Test_doublearr_InnerProd.doublemm:TestEntryPoint():int
           5 ( 0.21% of base) : 34788.dasm - Test_doublearr_InnerProd.doublemm:TestEntryPoint():int
           1 ( 0.16% of base) : 246170.dasm - Internal.TypeSystem.TypeNameFormatter`2[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:AppendName(System.Text.StringBuilder,Internal.TypeSystem.TypeDesc,System.Nullable`1[Int32]):double:this
           1 ( 0.13% of base) : 245934.dasm - Internal.TypeSystem.DebugNameFormatter:AppendNameForNamespaceType(System.Text.StringBuilder,Internal.TypeSystem.DefType,int):Void:this

Top method improvements (percentages):
         -80 (-38.65% of base) : 207118.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float,float,float,float,float,int)
         -10 (-38.46% of base) : 4400.dasm - TestLibrary.Logging:WriteLine(float)
         -80 (-38.10% of base) : 207120.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float,float,float,float,float):int
        -250 (-37.76% of base) : 34305.dasm - MathFusedMultiplyAddTest.Program:TestFloats()
         -80 (-35.24% of base) : 32436.dasm - ILStubClass:IL_STUB_PInvoke(byref,float,float,float,float,float,float,float,float):bool
        -120 (-34.78% of base) : 237674.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float,float,float,float,float,float,float,float,float):MCCTest.VType1
         -20 (-33.33% of base) : 55459.dasm - BringUpTest_FPRem:FPRem(float,float):float
         -20 (-30.77% of base) : 74215.dasm - _rem:R4(float,float,float):int
         -40 (-30.53% of base) : 55418.dasm - BringUpTest_FPCall2:FPCall2(float,float,float,float):float
         -60 (-29.85% of base) : 32435.dasm - ILStubClass:IL_STUB_PInvoke(byref,float,float,float,float,float,float):bool
         -90 (-29.70% of base) : 28748.dasm - ILStubClass:IL_STUB_PInvoke(System.Numerics.Vector3,float,float,float,float,float,float,float,System.Numerics.Vector3,float,float):float
        -100 (-28.57% of base) : 28749.dasm - ILStubClass:IL_STUB_PInvoke(System.Numerics.Vector3,float,float,float,float,float,float,float,System.Numerics.Vector3,float,float,System.Numerics.Vector3,float):float
         -40 (-25.81% of base) : 207117.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float,int)
         -10 (-25.64% of base) : 44039.dasm - JitInliningTest.Args1:f11a(float):System.String
         -40 (-25.32% of base) : 207157.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float):byref
         -40 (-25.32% of base) : 207119.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float):int
         -40 (-24.69% of base) : 41698.dasm - _rem:_rem(float,float,float):int
         -40 (-24.54% of base) : 32445.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float,byref)
         -40 (-23.12% of base) : 32440.dasm - ILStubClass:IL_STUB_PInvoke(float,float,float,float):System.Numerics.Vector4
         -40 (-22.86% of base) : 32434.dasm - ILStubClass:IL_STUB_PInvoke(byref,float,float,float,float):bool

12001 total methods with Code Size differences (11993 improved, 8 regressed), 4 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 27444769 (overridden on cmd)
Total bytes of diff: 27363518 (overridden on cmd)
Total bytes of delta: -81251 (-0.30 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          97 : 27807.dasm (10.23% of base)
          37 : 185673.dasm (2.83% of base)
          27 : 105931.dasm (16.17% of base)
          26 : 56551.dasm (3.59% of base)
          20 : 122720.dasm (5.31% of base)
          19 : 52579.dasm (6.11% of base)
          19 : 52580.dasm (6.11% of base)
          18 : 63732.dasm (1.08% of base)
          17 : 109889.dasm (6.64% of base)
          16 : 51997.dasm (7.92% of base)
          15 : 54154.dasm (6.73% of base)
          15 : 54155.dasm (7.08% of base)
          14 : 161176.dasm (3.77% of base)
          14 : 92933.dasm (0.88% of base)
          13 : 54153.dasm (5.91% of base)
          13 : 51424.dasm (7.30% of base)
          13 : 51360.dasm (4.44% of base)
          13 : 51361.dasm (4.44% of base)
          13 : 53386.dasm (7.18% of base)
          13 : 53473.dasm (7.18% of base)

Top file improvements (bytes):
        -491 : 82804.dasm (-0.72% of base)
        -186 : 80658.dasm (-0.67% of base)
        -132 : 82535.dasm (-0.69% of base)
        -117 : 82233.dasm (-0.65% of base)
         -99 : 58837.dasm (-0.45% of base)
         -98 : 97427.dasm (-1.57% of base)
         -90 : 170657.dasm (-1.18% of base)
         -88 : 170674.dasm (-1.10% of base)
         -86 : 140811.dasm (-2.85% of base)
         -85 : 162050.dasm (-18.76% of base)
         -84 : 164310.dasm (-36.68% of base)
         -84 : 161896.dasm (-42.21% of base)
         -81 : 164211.dasm (-12.46% of base)
         -80 : 162093.dasm (-27.30% of base)
         -80 : 144663.dasm (-4.60% of base)
         -80 : 163124.dasm (-41.67% of base)
         -80 : 163125.dasm (-21.86% of base)
         -80 : 164224.dasm (-14.87% of base)
         -80 : 162010.dasm (-36.36% of base)
         -80 : 140654.dasm (-1.80% of base)

27595 total files with Code Size differences (27442 improved, 153 regressed), 15 unchanged.

Top method regressions (bytes):
          97 (10.23% of base) : 27807.dasm - System.Buffers.TlsOverPerCoreLockedStacksArrayPool`1:Trim():bool:this
          37 ( 2.83% of base) : 185673.dasm - System.Net.HttpResponseStream:DisposeCore():this
          27 (16.17% of base) : 105931.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourcePropertySymbol:MakeModifiers(Microsoft.CodeAnalysis.SyntaxTokenList,bool,bool,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int:this
          26 ( 3.59% of base) : 56551.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParsePotentialQuery(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax:this
          20 ( 5.31% of base) : 122720.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindVariableType(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.Syntax.TypeSyntax,byref,byref,byref):Microsoft.CodeAnalysis.CSharp.Symbols.TypeSymbol:this
          19 ( 6.11% of base) : 52579.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArrayCreationExpressionSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          19 ( 6.11% of base) : 52580.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ArrayCreationExpressionSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          18 ( 1.08% of base) : 63732.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:BindUsingBlock(Microsoft.CodeAnalysis.VisualBasic.Syntax.UsingBlockSyntax,Microsoft.CodeAnalysis.DiagnosticBag):Microsoft.CodeAnalysis.VisualBasic.BoundStatement:this
          17 ( 6.64% of base) : 109889.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.NamespaceDeclarationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.NameSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          16 ( 7.92% of base) : 51997.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax):this
          15 ( 7.08% of base) : 54155.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.HandlesClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          15 ( 6.73% of base) : 54154.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ISyntaxFactoryContext,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.HandlesClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          14 ( 0.88% of base) : 92933.dasm - Microsoft.FSharp.Text.StructuredPrintfImpl.Display:fit@598(int,Microsoft.FSharp.Core.FSharpFunc`2[System.Object, Microsoft.FSharp.Text.StructuredPrintfImpl.TaggedText],Microsoft.FSharp.Text.StructuredPrintfImpl.Display+Breaks,int,Microsoft.FSharp.Text.StructuredPrintfImpl.Layout):System.Tuple`4[Microsoft.FSharp.Text.StructuredPrintfImpl.Display+Breaks, Microsoft.FSharp.Text.StructuredPrintfImpl.Layout, System.Int32, System.Int32]
          14 ( 3.77% of base) : 161176.dasm - System.Text.Json.JsonDocument:GetArrayIndexElement(int,int):System.Text.Json.JsonElement:this
          13 ( 7.30% of base) : 110472.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationAlignmentClauseSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationFormatClauseSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          13 ( 4.44% of base) : 51360.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetAnnotations(Microsoft.CodeAnalysis.SyntaxAnnotation[]):Microsoft.CodeAnalysis.GreenNode:this
          13 ( 4.44% of base) : 51361.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IfDirectiveTriviaSyntax:SetDiagnostics(Microsoft.CodeAnalysis.DiagnosticInfo[]):Microsoft.CodeAnalysis.GreenNode:this
          13 ( 7.30% of base) : 51424.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationAlignmentClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationFormatClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax):this
          13 ( 5.91% of base) : 54153.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.HandlesClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          13 ( 7.18% of base) : 53473.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MultiLineIfBlockSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IfStatementSyntax,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ElseBlockSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.EndBlockStatementSyntax):this

Top method improvements (bytes):
        -491 (-0.72% of base) : 82804.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServerTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -186 (-0.67% of base) : 80658.dasm - Microsoft.Diagnostics.Tracing.Parsers.KernelTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -132 (-0.69% of base) : 82535.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrPrivateTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
        -117 (-0.65% of base) : 82233.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrTraceEventParser:EnumerateTemplates(System.Func`3[System.String, System.String, Microsoft.Diagnostics.Tracing.EventFilterResponse],System.Action`1[Microsoft.Diagnostics.Tracing.TraceEvent]):this
         -99 (-0.45% of base) : 58837.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicCommandLineParser:Parse(System.Collections.Generic.IEnumerable`1[System.String],System.String,System.String,System.String):Microsoft.CodeAnalysis.VisualBasic.VisualBasicCommandLineArguments:this
         -98 (-1.57% of base) : 97427.dasm - System.Net.Http.Headers.QPackStaticTable:.cctor()
         -90 (-1.18% of base) : 170657.dasm - System.DirectoryServices.AccountManagement.SAMStoreCtx:.cctor()
         -88 (-1.10% of base) : 170674.dasm - System.DirectoryServices.AccountManagement.ADAMStoreCtx:.cctor()
         -86 (-2.85% of base) : 140811.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:ModObj(System.Object,System.Object):System.Object
         -85 (-18.76% of base) : 162050.dasm - Gdip:GdipDrawImageRectRect(System.Runtime.InteropServices.HandleRef,System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float,int,System.Runtime.InteropServices.HandleRef,System.Drawing.Graphics+DrawImageAbort,System.Runtime.InteropServices.HandleRef):int
         -84 (-42.21% of base) : 161896.dasm - Gdip:<GdipDrawImageRectRect>g____PInvoke__|438_0(int,int,float,float,float,float,float,float,float,float,int,int,int,int):int
         -84 (-36.68% of base) : 164310.dasm - System.Drawing.Graphics:DrawBezier(System.Drawing.Pen,float,float,float,float,float,float,float,float):this
         -81 (-12.46% of base) : 164211.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.Rectangle,float,float,float,float,int,System.Drawing.Imaging.ImageAttributes,System.Drawing.Graphics+DrawImageAbort,int):this
         -80 (-44.44% of base) : 161891.dasm - Gdip:<GdipAddPathBezier>g____PInvoke__|509_0(int,float,float,float,float,float,float,float,float):int
         -80 (-43.72% of base) : 161909.dasm - Gdip:<GdipDrawBezier>g____PInvoke__|392_0(int,int,float,float,float,float,float,float,float,float):int
         -80 (-36.36% of base) : 162010.dasm - Gdip:GdipAddPathBezier(System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float):int
         -80 (-27.30% of base) : 162093.dasm - Gdip:GdipDrawBezier(System.Runtime.InteropServices.HandleRef,System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float):int
         -80 (-4.60% of base) : 144663.dasm - Microsoft.CSharp.RuntimeBinder.SymbolTable:SetParameterAttributes(Microsoft.CSharp.RuntimeBinder.Semantics.MethodOrPropertySymbol,System.Reflection.ParameterInfo[],int)
         -80 (-1.80% of base) : 140654.dasm - Microsoft.VisualBasic.CompilerServices.Operators:ModObject(System.Object,System.Object):System.Object
         -80 (-41.67% of base) : 163124.dasm - System.Drawing.Drawing2D.GraphicsPath:AddBezier(float,float,float,float,float,float,float,float):this

Top method regressions (percentages):
          27 (16.17% of base) : 105931.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourcePropertySymbol:MakeModifiers(Microsoft.CodeAnalysis.SyntaxTokenList,bool,bool,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int:this
          97 (10.23% of base) : 27807.dasm - System.Buffers.TlsOverPerCoreLockedStacksArrayPool`1:Trim():bool:this
          16 ( 7.92% of base) : 51997.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.XmlDeclarationOptionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax):this
          13 ( 7.30% of base) : 110472.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationAlignmentClauseSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InterpolationFormatClauseSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          13 ( 7.30% of base) : 51424.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationAlignmentClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.InterpolationFormatClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax):this
          13 ( 7.30% of base) : 53503.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SingleLineIfStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SingleLineElseClauseSyntax):this
          13 ( 7.18% of base) : 53473.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MultiLineIfBlockSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IfStatementSyntax,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ElseBlockSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.EndBlockStatementSyntax):this
          13 ( 7.18% of base) : 53386.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TryBlockSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TryStatementSyntax,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.FinallyBlockSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.EndBlockStatementSyntax):this
          15 ( 7.08% of base) : 54155.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.HandlesClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          15 ( 6.73% of base) : 54154.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.MethodStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ISyntaxFactoryContext,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.HandlesClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          17 ( 6.64% of base) : 109889.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.NamespaceDeclarationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.NameSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          12 ( 6.59% of base) : 54103.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.DelegateStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.TypeParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax):this
          10 ( 6.49% of base) : 109871.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.AttributeListSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.AttributeTargetSpecifierSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          10 ( 6.49% of base) : 109990.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CatchClauseSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CatchDeclarationSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CatchFilterClauseSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.BlockSyntax,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          10 ( 6.49% of base) : 110311.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.GotoStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          10 ( 6.49% of base) : 110750.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ObjectCreationExpressionSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TypeSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.ArgumentListSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.InitializerExpressionSyntax,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          10 ( 6.49% of base) : 110007.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.TryStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxToken,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.BlockSyntax,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.FinallyClauseSyntax,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[]):this
          12 ( 6.49% of base) : 54055.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PropertyStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.GreenNode,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ParameterListSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.AsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.EqualsValueSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ImplementsClauseSyntax):this
          10 ( 6.37% of base) : 53343.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CatchStatementSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierNameSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SimpleAsClauseSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.CatchFilterClauseSyntax):this
          10 ( 6.37% of base) : 52254.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.FunctionAggregationSyntax:.ctor(ushort,Microsoft.CodeAnalysis.DiagnosticInfo[],Microsoft.CodeAnalysis.SyntaxAnnotation[],Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.IdentifierTokenSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.ExpressionSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.PunctuationSyntax):this

Top method improvements (percentages):
         -80 (-68.38% of base) : 23986.dasm - System.Runtime.Intrinsics.Vector256:Create(float,float,float,float,float,float,float,float):System.Runtime.Intrinsics.Vector256`1[System.Single]
         -20 (-54.05% of base) : 23820.dasm - System.Runtime.Intrinsics.Vector64:Create(float,float):System.Runtime.Intrinsics.Vector64`1[System.Single]
         -20 (-51.28% of base) : 163314.dasm - System.Drawing.Drawing2D.LinearGradientBrush:ScaleTransform(float,float):this
         -20 (-51.28% of base) : 163316.dasm - System.Drawing.Drawing2D.LinearGradientBrush:TranslateTransform(float,float):this
         -20 (-51.28% of base) : 163286.dasm - System.Drawing.Drawing2D.Matrix:Scale(float,float):this
         -20 (-51.28% of base) : 163288.dasm - System.Drawing.Drawing2D.Matrix:Translate(float,float):this
         -20 (-51.28% of base) : 163236.dasm - System.Drawing.Drawing2D.PathGradientBrush:ScaleTransform(float,float):this
         -20 (-51.28% of base) : 163238.dasm - System.Drawing.Drawing2D.PathGradientBrush:TranslateTransform(float,float):this
         -20 (-51.28% of base) : 164318.dasm - System.Drawing.Graphics:ScaleTransform(float,float):this
         -20 (-51.28% of base) : 164320.dasm - System.Drawing.Graphics:TranslateTransform(float,float):this
         -20 (-51.28% of base) : 164003.dasm - System.Drawing.Pen:ScaleTransform(float,float):this
         -20 (-51.28% of base) : 164005.dasm - System.Drawing.Pen:TranslateTransform(float,float):this
         -20 (-51.28% of base) : 163532.dasm - System.Drawing.TextureBrush:ScaleTransform(float,float):this
         -20 (-51.28% of base) : 163534.dasm - System.Drawing.TextureBrush:TranslateTransform(float,float):this
         -20 (-50.00% of base) : 38807.dasm - System.Collections.Generic.ComparisonComparer`1:Compare(float,float):int:this
         -43 (-47.78% of base) : 164212.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.Rectangle,float,float,float,float,int,System.Drawing.Imaging.ImageAttributes,System.Drawing.Graphics+DrawImageAbort):this
         -30 (-46.88% of base) : 32336.dasm - System.Single:FusedMultiplyAdd(float,float,float):float
         -80 (-44.44% of base) : 161891.dasm - Gdip:<GdipAddPathBezier>g____PInvoke__|509_0(int,float,float,float,float,float,float,float,float):int
         -80 (-43.72% of base) : 161909.dasm - Gdip:<GdipDrawBezier>g____PInvoke__|392_0(int,int,float,float,float,float,float,float,float,float):int
         -10 (-43.48% of base) : 36820.dasm - System.Decimal:.ctor(float):this

27595 total methods with Code Size differences (27442 improved, 153 regressed), 15 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 39462187 (overridden on cmd)
Total bytes of diff: 39384469 (overridden on cmd)
Total bytes of delta: -77718 (-0.20 % of base)
    diff is an improvement.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          78 : 8964.dasm (1.94% of base)
          75 : 76765.dasm (1.86% of base)
          57 : 17252.dasm (1.48% of base)
          55 : 76827.dasm (5.80% of base)
          38 : 41634.dasm (2.43% of base)
          33 : 149628.dasm (2.75% of base)
          33 : 37531.dasm (16.50% of base)
          32 : 182506.dasm (0.68% of base)
          27 : 77213.dasm (0.85% of base)
          24 : 231157.dasm (3.10% of base)
          21 : 137798.dasm (1.09% of base)
          21 : 234085.dasm (1.44% of base)
          17 : 9434.dasm (0.96% of base)
          16 : 50160.dasm (0.57% of base)
          16 : 16743.dasm (2.02% of base)
          13 : 28143.dasm (1.59% of base)
          13 : 49937.dasm (0.91% of base)
          12 : 15967.dasm (0.22% of base)
          11 : 9173.dasm (0.63% of base)
          11 : 90352.dasm (1.94% of base)

Top file improvements (bytes):
        -888 : 106385.dasm (-1.23% of base)
        -428 : 137639.dasm (-2.72% of base)
        -279 : 109064.dasm (-0.96% of base)
        -225 : 107325.dasm (-1.12% of base)
        -200 : 15855.dasm (-2.45% of base)
        -178 : 107598.dasm (-0.97% of base)
        -130 : 90707.dasm (-1.24% of base)
        -121 : 73311.dasm (-2.92% of base)
        -121 : 73324.dasm (-2.92% of base)
        -106 : 16048.dasm (-1.59% of base)
        -105 : 76902.dasm (-4.57% of base)
        -102 : 136466.dasm (-5.06% of base)
         -94 : 71576.dasm (-5.39% of base)
         -89 : 177915.dasm (-4.47% of base)
         -89 : 49351.dasm (-0.75% of base)
         -89 : 77014.dasm (-1.61% of base)
         -87 : 130334.dasm (-3.43% of base)
         -86 : 178001.dasm (-2.46% of base)
         -85 : 142680.dasm (-20.24% of base)
         -84 : 140670.dasm (-48.84% of base)

23907 total files with Code Size differences (23817 improved, 90 regressed), 71 unchanged.

Top method regressions (bytes):
          78 ( 1.94% of base) : 8964.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:PassArguments(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,byref,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          75 ( 1.86% of base) : 76765.dasm - Microsoft.CodeAnalysis.CSharp.LambdaRewriter:RewriteLambdaConversion(Microsoft.CodeAnalysis.CSharp.BoundLambda):Microsoft.CodeAnalysis.CSharp.BoundNode:this
          57 ( 1.48% of base) : 17252.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:ScanXmlString(ushort,ushort,bool):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxToken:this
          55 ( 5.80% of base) : 76827.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteExpressionUsingStatement(Microsoft.CodeAnalysis.CSharp.BoundUsingStatement,Microsoft.CodeAnalysis.CSharp.BoundBlock):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
          38 ( 2.43% of base) : 41634.dasm - System.Xml.Schema.Asttree:CompileXPath(System.String,bool,System.Xml.XmlNamespaceManager):this
          33 ( 2.75% of base) : 149628.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
          33 (16.50% of base) : 37531.dasm - System.Xml.XmlNamedNodeMap:InsertNodeAt(int,System.Xml.XmlNode):System.Xml.XmlNode:this
          32 ( 0.68% of base) : 182506.dasm - R2RDump.R2RDiff:ShowMethodDiff(System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.Int32, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],System.String):this
          27 ( 0.85% of base) : 77213.dasm - Microsoft.CodeAnalysis.CSharp.StateMachineRewriter:CreateNonReusableLocalProxies(System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.CSharp.Symbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],byref,byref):this
          24 ( 3.10% of base) : 231157.dasm - System.Runtime.Serialization.Formatters.Binary.ObjectWriter:Write(System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.String[],System.Type[],System.Object[],System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo[]):this
          21 ( 1.09% of base) : 137798.dasm - System.Data.SqlTypes.SqlDecimal:op_Multiply(System.Data.SqlTypes.SqlDecimal,System.Data.SqlTypes.SqlDecimal):System.Data.SqlTypes.SqlDecimal
          21 ( 1.44% of base) : 234085.dasm - System.Security.Cryptography.Xml.XmlLicenseTransform:DecryptEncryptedGrants(System.Xml.XmlNodeList,System.Security.Cryptography.Xml.IRelDecryptor):this
          17 ( 0.96% of base) : 9434.dasm - Microsoft.CodeAnalysis.VisualBasic.DocumentationCommentCrefBinder:BindInsideCrefAttributeValue(Microsoft.CodeAnalysis.VisualBasic.Syntax.CrefReferenceSyntax,bool,Microsoft.CodeAnalysis.DiagnosticBag,byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.Symbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          16 ( 2.02% of base) : 16743.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseOnErrorGoto(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.OnErrorGoToStatementSyntax:this
          16 ( 0.57% of base) : 50160.dasm - System.Xml.Serialization.XmlSerializationWriterCodeGen:WriteEnumAndArrayTypes():this
          13 ( 1.59% of base) : 28143.dasm - Microsoft.CodeAnalysis.VisualBasic.SymbolDisplayVisitor:VisitNamespace(Microsoft.CodeAnalysis.INamespaceSymbol,System.String):this
          13 ( 0.91% of base) : 49937.dasm - System.Xml.Serialization.XmlSerializationReaderILGen:WriteHashtable(System.Xml.Serialization.EnumMapping,System.String,byref):System.String:this
          12 ( 0.22% of base) : 15967.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:LateCallOrGet(Microsoft.CodeAnalysis.VisualBasic.BoundLateMemberAccess,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.VisualBasic.BoundExpression, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Immutable.ImmutableArray`1[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]],bool):Microsoft.CodeAnalysis.VisualBasic.BoundExpression:this
          11 ( 1.94% of base) : 90352.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:GetNetModuleAttributes(byref):System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.CSharp.Symbols.CSharpAttributeData, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          11 ( 0.63% of base) : 9173.dasm - Microsoft.CodeAnalysis.VisualBasic.Binder:ResolveMethodForDelegateInvokeFullOrRelaxed(Microsoft.CodeAnalysis.VisualBasic.BoundAddressOfOperator,Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol,bool,Microsoft.CodeAnalysis.DiagnosticBag,bool,byref):System.Collections.Generic.KeyValuePair`2[[Microsoft.CodeAnalysis.VisualBasic.Symbols.MethodSymbol, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35],[Microsoft.CodeAnalysis.VisualBasic.MethodConversionKind, Microsoft.CodeAnalysis.VisualBasic, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]

Top method improvements (bytes):
        -888 (-1.23% of base) : 106385.dasm - Microsoft.Diagnostics.Tracing.Parsers.ApplicationServerTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -428 (-2.72% of base) : 137639.dasm - System.Data.BinaryNode:EvalBinaryOp(int,System.Data.ExpressionNode,System.Data.ExpressionNode,System.Data.DataRow,int,System.Int32[]):System.Object:this
        -279 (-0.96% of base) : 109064.dasm - Microsoft.Diagnostics.Tracing.Parsers.KernelTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -225 (-1.12% of base) : 107325.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrPrivateTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -200 (-2.45% of base) : 15855.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:RewriteUnstructuredExceptionHandlingStatementIntoBlock(Microsoft.CodeAnalysis.VisualBasic.BoundUnstructuredExceptionHandlingStatement):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
        -178 (-0.97% of base) : 107598.dasm - Microsoft.Diagnostics.Tracing.Parsers.ClrTraceEventParser:EnumerateTemplates(System.Func`3[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[Microsoft.Diagnostics.Tracing.EventFilterResponse, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Action`1[[Microsoft.Diagnostics.Tracing.TraceEvent, Microsoft.Diagnostics.Tracing.TraceEvent, Version=2.0.65.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]]):this
        -130 (-1.24% of base) : 90707.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:AddNonTypeMembers(MembersAndInitializersBuilder,Microsoft.CodeAnalysis.SyntaxList`1[[Microsoft.CodeAnalysis.CSharp.Syntax.MemberDeclarationSyntax, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.DiagnosticBag):this
        -121 (-2.92% of base) : 73311.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeVisitor`2[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:VisitInternal(Microsoft.CodeAnalysis.CSharp.BoundNode,System.__Canon):System.Nullable`1[Int32]:this
        -121 (-2.92% of base) : 73324.dasm - Microsoft.CodeAnalysis.CSharp.BoundTreeVisitor`2[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:VisitInternal(Microsoft.CodeAnalysis.CSharp.BoundNode,int):System.Nullable`1[Int32]:this
        -106 (-1.59% of base) : 16048.dasm - Microsoft.CodeAnalysis.VisualBasic.LocalRewriter:FinishNonObjectForLoop(Microsoft.CodeAnalysis.VisualBasic.BoundForToStatement,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression,Microsoft.CodeAnalysis.VisualBasic.BoundExpression):Microsoft.CodeAnalysis.VisualBasic.BoundBlock:this
        -105 (-4.57% of base) : 76902.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:AddObjectInitializer(byref,byref,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundAssignmentOperator):this
        -102 (-5.06% of base) : 136466.dasm - System.Data.DataTable:SerializeConstraints(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,int,bool):this
         -94 (-5.39% of base) : 71576.dasm - Microsoft.CodeAnalysis.CSharp.Binder:BindMethodGroupInvocation(Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,System.String,Microsoft.CodeAnalysis.CSharp.BoundMethodGroup,Microsoft.CodeAnalysis.CSharp.AnalyzedArguments,Microsoft.CodeAnalysis.DiagnosticBag,Microsoft.CodeAnalysis.CSharp.CSharpSyntaxNode,bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -89 (-1.61% of base) : 77014.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:TransformCompoundAssignmentLHS(Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.BoundExpression, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],Microsoft.CodeAnalysis.ArrayBuilder`1[[Microsoft.CodeAnalysis.CSharp.Symbols.LocalSymbol, Microsoft.CodeAnalysis.CSharp, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],bool):Microsoft.CodeAnalysis.CSharp.BoundExpression:this
         -89 (-4.47% of base) : 177915.dasm - Microsoft.VisualBasic.CompilerServices.LikeOperator:MatchRange(System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],System.String,int,byref,Microsoft.VisualBasic.CompilerServices.LikeOperator+LigatureInfo[],byref,byref,byref,System.Globalization.CompareInfo,int,byref,System.Collections.Generic.List`1[Range],bool)
         -89 (-0.75% of base) : 49351.dasm - System.Xml.Serialization.XmlReflectionImporter:ImportAccessorMapping(System.Xml.Serialization.MemberMapping,System.Xml.Serialization.FieldModel,System.Xml.Serialization.XmlAttributes,System.String,System.Type,bool,bool,System.Xml.Serialization.RecursionLimiter):this
         -87 (-3.43% of base) : 130334.dasm - Microsoft.Build.BackEnd.Scheduler:DumpSchedulerState():this
         -86 (-2.46% of base) : 178001.dasm - Microsoft.VisualBasic.CompilerServices.ObjectType:ModObj(System.Object,System.Object):System.Object
         -85 (-20.24% of base) : 142680.dasm - Gdip:GdipDrawImageRectRect(System.Runtime.InteropServices.HandleRef,System.Runtime.InteropServices.HandleRef,float,float,float,float,float,float,float,float,int,System.Runtime.InteropServices.HandleRef,DrawImageAbort,System.Runtime.InteropServices.HandleRef):int
         -84 (-36.84% of base) : 142489.dasm - ILStubClass:IL_STUB_PInvoke(int,int,float,float,float,float,float,float,float,float,int,int,int,int):int

Top method regressions (percentages):
          33 (16.50% of base) : 37531.dasm - System.Xml.XmlNamedNodeMap:InsertNodeAt(int,System.Xml.XmlNode):System.Xml.XmlNode:this
          55 ( 5.80% of base) : 76827.dasm - Microsoft.CodeAnalysis.CSharp.LocalRewriter:RewriteExpressionUsingStatement(Microsoft.CodeAnalysis.CSharp.BoundUsingStatement,Microsoft.CodeAnalysis.CSharp.BoundBlock):Microsoft.CodeAnalysis.CSharp.BoundBlock:this
          24 ( 3.10% of base) : 231157.dasm - System.Runtime.Serialization.Formatters.Binary.ObjectWriter:Write(System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.Runtime.Serialization.Formatters.Binary.NameInfo,System.String[],System.Type[],System.Object[],System.Runtime.Serialization.Formatters.Binary.WriteObjectInfo[]):this
          33 ( 2.75% of base) : 149628.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
           4 ( 2.70% of base) : 151806.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Int32[],int,int):this
           4 ( 2.70% of base) : 151810.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Single[],int,int):this
           4 ( 2.68% of base) : 151802.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Boolean[],int,int):this
           4 ( 2.68% of base) : 151804.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Int16[],int,int):this
           4 ( 2.61% of base) : 151808.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Int64[],int,int):this
           4 ( 2.56% of base) : 101771.dasm - Roslyn.Utilities.TextKeyedCache`1[__Canon][System.__Canon]:FindSharedEntry(System.Char[],int,int,int):SharedEntryValue[__Canon]:this
           4 ( 2.55% of base) : 151816.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.DateTime[],int,int):this
           4 ( 2.55% of base) : 151820.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.TimeSpan[],int,int):this
           4 ( 2.48% of base) : 151812.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Double[],int,int):this
           4 ( 2.44% of base) : 151814.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Decimal[],int,int):this
           4 ( 2.44% of base) : 151818.dasm - System.Xml.XmlDictionaryWriter:WriteArray(System.String,System.String,System.String,System.Guid[],int,int):this
          38 ( 2.43% of base) : 41634.dasm - System.Xml.Schema.Asttree:CompileXPath(System.String,bool,System.Xml.XmlNamespaceManager):this
           8 ( 2.36% of base) : 14100.dasm - Microsoft.CodeAnalysis.VisualBasic.TypesOfImportedNamespacesMembersBinder:LookupInSingleBinder(Microsoft.CodeAnalysis.VisualBasic.LookupResult,System.String,int,int,Microsoft.CodeAnalysis.VisualBasic.Binder,byref):this
           7 ( 2.24% of base) : 177641.dasm - Microsoft.VisualBasic.CompilerServices.ConversionResolution:FindBestMatch(System.Type,System.Type,System.Collections.Generic.List`1[[Microsoft.VisualBasic.CompilerServices.Symbols+Method, Microsoft.VisualBasic.Core, Version=12.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],System.Collections.Generic.List`1[[Microsoft.VisualBasic.CompilerServices.Symbols+Method, Microsoft.VisualBasic.Core, Version=12.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a]],byref)
          11 ( 2.13% of base) : 211231.dasm - System.IO.Ports.SerialPort:ReadBufferIntoChars(System.Char[],int,int,bool):int:this
          16 ( 2.02% of base) : 16743.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Parser:ParseOnErrorGoto(Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax,Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.KeywordSyntax):Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.OnErrorGoToStatementSyntax:this

Top method improvements (percentages):
         -84 (-48.84% of base) : 140670.dasm - System.Drawing.Graphics:DrawBezier(System.Drawing.Pen,float,float,float,float,float,float,float,float):this
         -80 (-48.78% of base) : 141762.dasm - System.Drawing.Drawing2D.GraphicsPath:AddBezier(float,float,float,float,float,float,float,float):this
         -43 (-45.26% of base) : 140546.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.Rectangle,float,float,float,float,int,System.Drawing.Imaging.ImageAttributes,DrawImageAbort):this
         -60 (-43.48% of base) : 141758.dasm - System.Drawing.Drawing2D.GraphicsPath:AddArc(float,float,float,float,float,float):this
         -60 (-43.48% of base) : 141730.dasm - System.Drawing.Drawing2D.GraphicsPath:AddPie(float,float,float,float,float,float):this
         -60 (-42.25% of base) : 140666.dasm - System.Drawing.Graphics:DrawArc(System.Drawing.Pen,float,float,float,float,float,float):this
         -60 (-42.25% of base) : 140628.dasm - System.Drawing.Graphics:DrawPie(System.Drawing.Pen,float,float,float,float,float,float):this
         -60 (-42.25% of base) : 140606.dasm - System.Drawing.Graphics:FillPie(System.Drawing.Brush,float,float,float,float,float,float):this
         -42 (-38.89% of base) : 140545.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.Rectangle,float,float,float,float,int,System.Drawing.Imaging.ImageAttributes):this
         -41 (-38.68% of base) : 140544.dasm - System.Drawing.Graphics:DrawImage(System.Drawing.Image,System.Drawing.Rectangle,float,float,float,float,int):this
         -10 (-38.46% of base) : 43788.dasm - System.Xml.Schema.XmlUntypedConverter:ToString(float):System.String:this
         -10 (-38.46% of base) : 151733.dasm - System.Xml.XmlConverter:ToString(float):System.String
         -80 (-37.91% of base) : 142482.dasm - ILStubClass:IL_STUB_PInvoke(int,float,float,float,float,float,float,float,float):int
         -80 (-37.74% of base) : 142507.dasm - ILStubClass:IL_STUB_PInvoke(int,int,float,float,float,float,float,float,float,float):int
         -20 (-37.04% of base) : 140667.dasm - System.Drawing.Graphics:DrawArc(System.Drawing.Pen,System.Drawing.RectangleF,float,float):this
         -20 (-37.04% of base) : 140627.dasm - System.Drawing.Graphics:DrawPie(System.Drawing.Pen,System.Drawing.RectangleF,float,float):this
         -20 (-37.04% of base) : 140605.dasm - System.Drawing.Graphics:FillPie(System.Drawing.Brush,System.Drawing.RectangleF,float,float):this
         -84 (-36.84% of base) : 142489.dasm - ILStubClass:IL_STUB_PInvoke(int,int,float,float,float,float,float,float,float,float,int,int,int,int):int
         -40 (-35.71% of base) : 141726.dasm - System.Drawing.Drawing2D.GraphicsPath:AddEllipse(float,float,float,float):this
         -40 (-35.71% of base) : 141752.dasm - System.Drawing.Drawing2D.GraphicsPath:AddLine(float,float,float,float):this

23907 total methods with Code Size differences (23817 improved, 90 regressed), 73 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.x86.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 97042426 (overridden on cmd)
Total bytes of diff: 96928432 (overridden on cmd)
Total bytes of delta: -113994 (-0.12 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         226 : 182097.dasm (6.86% of base)
          83 : 182061.dasm (3.57% of base)
          61 : 237965.dasm (4.24% of base)
          51 : 168725.dasm (1.62% of base)
          41 : 322770.dasm (3.61% of base)
          33 : 186837.dasm (2.72% of base)
          33 : 217709.dasm (2.72% of base)
          23 : 11009.dasm (2.05% of base)
          23 : 182090.dasm (0.86% of base)
          21 : 38607.dasm (0.22% of base)
          21 : 38608.dasm (0.19% of base)
          18 : 303415.dasm (1.65% of base)
          15 : 300700.dasm (4.79% of base)
          11 : 220689.dasm (1.69% of base)
          10 : 71599.dasm (0.31% of base)
          10 : 71600.dasm (0.31% of base)
           9 : 280169.dasm (0.54% of base)
           8 : 58315.dasm (0.41% of base)
           8 : 52631.dasm (0.41% of base)
           8 : 52459.dasm (0.41% of base)

Top file improvements (bytes):
        -520 : 275368.dasm (-18.47% of base)
        -440 : 284045.dasm (-8.57% of base)
        -360 : 275271.dasm (-14.97% of base)
        -320 : 275550.dasm (-13.15% of base)
        -320 : 275551.dasm (-11.05% of base)
        -274 : 113418.dasm (-9.19% of base)
        -270 : 80476.dasm (-1.07% of base)
        -270 : 112596.dasm (-7.45% of base)
        -250 : 113419.dasm (-8.43% of base)
        -250 : 113412.dasm (-9.22% of base)
        -250 : 113416.dasm (-8.13% of base)
        -243 : 79148.dasm (-7.71% of base)
        -243 : 79184.dasm (-7.71% of base)
        -243 : 79112.dasm (-7.63% of base)
        -243 : 78911.dasm (-7.71% of base)
        -243 : 78947.dasm (-7.71% of base)
        -240 : 275188.dasm (-16.54% of base)
        -188 : 275563.dasm (-8.30% of base)
        -170 : 113770.dasm (-6.10% of base)
        -165 : 163468.dasm (-0.24% of base)

35839 total files with Code Size differences (35791 improved, 48 regressed), 33 unchanged.

Top method regressions (bytes):
         226 ( 6.86% of base) : 182097.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_TrimStart_Multi_Null()
          83 ( 3.57% of base) : 182061.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_Trim_Multi_Null()
          61 ( 4.24% of base) : 237965.dasm - NuGet.Packaging.Signing.AllowListVerificationProvider:IsSignatureAllowed(NuGet.Packaging.Signing.PrimarySignature,System.Collections.Generic.IReadOnlyCollection`1[[NuGet.Packaging.Signing.VerificationAllowListEntry, NuGet.Packaging, Version=5.8.0.6930, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):bool:this
          51 ( 1.62% of base) : 168725.dasm - System.Data.Tests.DataSetReadXmlSchemaTest:SingleElementTreatmentDifference():this
          41 ( 3.61% of base) : 322770.dasm - NuGet.Resolver.ResolverUtility:FindCircularDependency(NuGet.Resolver.ResolverPackage,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.HashSet`1[[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):System.Collections.Generic.List`1[[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
          33 ( 2.72% of base) : 186837.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
          33 ( 2.72% of base) : 217709.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
          23 ( 2.05% of base) : 11009.dasm - Microsoft.CodeAnalysis.Workspaces.Diagnostics.DiagnosticAnalysisResult:CreateFromBuild(Microsoft.CodeAnalysis.Project,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Diagnostics.DiagnosticData, Microsoft.CodeAnalysis.Workspaces, Version=4.3.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.DocumentId, Microsoft.CodeAnalysis.Workspaces, Version=4.3.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.Workspaces.Diagnostics.DiagnosticAnalysisResult
          23 ( 0.86% of base) : 182090.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_TrimEnd_Multi(System.Int32[],System.Int32[],System.Int32[])
          21 ( 0.22% of base) : 38607.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:WriteHelloWorld(bool,bool):this
          21 ( 0.19% of base) : 38608.dasm - System.Text.Json.Tests.Utf8JsonWriterTests:WriteHelloWorldEscaped(bool,bool):this
          18 ( 1.65% of base) : 303415.dasm - System.Xml.Tests.TC_SchemaSet_Add_SchemaSet:v10():this
          15 ( 4.79% of base) : 300700.dasm - XObjectBuilderTest:var_9():this
          11 ( 1.69% of base) : 220689.dasm - DryIoc.ReflectionFactory:MatchOpenGenericConstraints(System.Type[],System.Type[])
          10 ( 0.31% of base) : 71599.dasm - System.Dynamic.Tests.BinaryOperationTests:LiteralDoubleNaN():this
          10 ( 0.31% of base) : 71600.dasm - System.Dynamic.Tests.BinaryOperationTests:LiteralSingleNaN():this
           9 ( 0.54% of base) : 280169.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:ObfuscateWithExtraData(System.Byte[],bool):System.Byte[]
           8 ( 0.41% of base) : 58315.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.nullable.verify.verify.Verify:Check(System.Object,System.Object):int
           8 ( 0.41% of base) : 52631.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.IndexerOperator.Binary.verify.verify.Verify:Check(System.Object,System.Object):int
           8 ( 0.41% of base) : 52459.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.IndexerOperator.Unary.verify.verify.Verify:Check(System.Object,System.Object):int

Top method improvements (bytes):
        -520 (-18.47% of base) : 275368.dasm - System.Numerics.Tests.Vector4Tests:Vector4GetHashCodeTest():this
        -440 (-8.57% of base) : 284045.dasm - System.Tests.MathTests:Round_Float_Constant_Arg()
        -360 (-14.97% of base) : 275271.dasm - System.Numerics.Tests.Vector3Tests:Vector3GetHashCodeTest():this
        -320 (-13.15% of base) : 275550.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4IndexerGetTest(float,float,float,float,float,float,float,float,float,float,float,float,float,float,float,float):this
        -320 (-11.05% of base) : 275551.dasm - System.Numerics.Tests.Matrix4x4Tests:Matrix4x4IndexerSetTest(float,float,float,float,float,float,float,float,float,float,float,float,float,float,float,float):this
        -274 (-9.19% of base) : 113418.dasm - System.Drawing.Imaging.Tests.ColorMatrixTests:Ctor_SetValue_ReturnsExpected():this
        -270 (-7.45% of base) : 112596.dasm - MonoTests.System.Drawing.GraphicsTest:TranslateTransform_Order():this
        -270 (-1.07% of base) : 80476.dasm - System.Linq.Expressions.Tests.Compiler_Tests:Conversions(bool)
        -250 (-9.22% of base) : 113412.dasm - System.Drawing.Imaging.Tests.ColorMatrixTests:Ctor_Default():this
        -250 (-8.13% of base) : 113416.dasm - System.Drawing.Imaging.Tests.ColorMatrixTests:Ctor_TooBigArraySize_MapOnly4and4Elements():this
        -250 (-8.43% of base) : 113419.dasm - System.Drawing.Imaging.Tests.ColorMatrixTests:MatrixElement_SetValues_ReturnsExpected():this
        -243 (-7.71% of base) : 78911.dasm - System.Linq.Expressions.Tests.LambdaAddTests:VerifyAddFloat(float,float,bool)
        -243 (-7.71% of base) : 78947.dasm - System.Linq.Expressions.Tests.LambdaDivideTests:VerifyDivideFloat(float,float,bool)
        -243 (-7.63% of base) : 79112.dasm - System.Linq.Expressions.Tests.LambdaModuloTests:VerifyModuloFloat(float,float,bool)
        -243 (-7.71% of base) : 79148.dasm - System.Linq.Expressions.Tests.LambdaMultiplyTests:VerifyMultiplyFloat(float,float,bool)
        -243 (-7.71% of base) : 79184.dasm - System.Linq.Expressions.Tests.LambdaSubtractTests:VerifySubtractFloat(float,float,bool)
        -240 (-16.54% of base) : 275188.dasm - System.Numerics.Tests.Vector2Tests:Vector2GetHashCodeTest():this
        -188 (-8.30% of base) : 275563.dasm - System.Numerics.Tests.Matrix4x4Tests:DecomposeTest(float,float,float,System.Numerics.Vector3,System.Numerics.Vector3):this
        -170 (-6.10% of base) : 113770.dasm - System.Drawing.Drawing2D.Tests.PathGradientBrushTests:SetSigmaBellShape_FocusScale_Success(float):this
        -165 (-0.24% of base) : 163468.dasm - <ValidateIdentifiers_Valid_TestData>d__0:MoveNext():bool:this

Top method regressions (percentages):
         226 ( 6.86% of base) : 182097.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_TrimStart_Multi_Null()
          15 ( 4.79% of base) : 300700.dasm - XObjectBuilderTest:var_9():this
          61 ( 4.24% of base) : 237965.dasm - NuGet.Packaging.Signing.AllowListVerificationProvider:IsSignatureAllowed(NuGet.Packaging.Signing.PrimarySignature,System.Collections.Generic.IReadOnlyCollection`1[[NuGet.Packaging.Signing.VerificationAllowListEntry, NuGet.Packaging, Version=5.8.0.6930, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):bool:this
          41 ( 3.61% of base) : 322770.dasm - NuGet.Resolver.ResolverUtility:FindCircularDependency(NuGet.Resolver.ResolverPackage,System.Collections.Generic.Dictionary`2[[System.String, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e],[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.HashSet`1[[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):System.Collections.Generic.List`1[[NuGet.Resolver.ResolverPackage, NuGet.Resolver, Version=5.6.0.5, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]
          83 ( 3.57% of base) : 182061.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_Trim_Multi_Null()
          33 ( 2.72% of base) : 186837.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
          33 ( 2.72% of base) : 217709.dasm - System.Net.Http.HPack.HPackDecoder:Parse(System.ReadOnlySpan`1[Byte],byref,System.Net.Http.IHttpStreamHeadersHandler):this
          23 ( 2.05% of base) : 11009.dasm - Microsoft.CodeAnalysis.Workspaces.Diagnostics.DiagnosticAnalysisResult:CreateFromBuild(Microsoft.CodeAnalysis.Project,System.Collections.Immutable.ImmutableArray`1[[Microsoft.CodeAnalysis.Diagnostics.DiagnosticData, Microsoft.CodeAnalysis.Workspaces, Version=4.3.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],System.Collections.Generic.IEnumerable`1[[Microsoft.CodeAnalysis.DocumentId, Microsoft.CodeAnalysis.Workspaces, Version=4.3.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]):Microsoft.CodeAnalysis.Workspaces.Diagnostics.DiagnosticAnalysisResult
          11 ( 1.69% of base) : 220689.dasm - DryIoc.ReflectionFactory:MatchOpenGenericConstraints(System.Type[],System.Type[])
          18 ( 1.65% of base) : 303415.dasm - System.Xml.Tests.TC_SchemaSet_Add_SchemaSet:v10():this
          51 ( 1.62% of base) : 168725.dasm - System.Data.Tests.DataSetReadXmlSchemaTest:SingleElementTreatmentDifference():this
           5 ( 1.46% of base) : 7645.dasm - Microsoft.CodeAnalysis.Shared.Collections.TemporaryArray`1[__Canon][System.__Canon]:MoveInlineToBuilder():this
          23 ( 0.86% of base) : 182090.dasm - System.MemoryTests.MemoryTests:MemoryExtensions_TrimEnd_Multi(System.Int32[],System.Int32[],System.Int32[])
           7 ( 0.70% of base) : 168732.dasm - System.Data.Tests.DataSetReadXmlSchemaTest:LocaleOnRootWithoutIsDataSet():this
           4 ( 0.66% of base) : 300710.dasm - XObjectBuilderTest:var_19():this
           4 ( 0.65% of base) : 300711.dasm - XObjectBuilderTest:var_20():this
           3 ( 0.65% of base) : 7281.dasm - Microsoft.CodeAnalysis.Shared.Extensions.SourceTextExtensions:WriteChunksTo(Microsoft.CodeAnalysis.Text.SourceText,Roslyn.Utilities.ObjectWriter,int,System.Threading.CancellationToken)
           7 ( 0.62% of base) : 221254.dasm - Registry:Unregister(int,System.Type,System.Object,System.Func`2[[DryIoc.Factory, DryIoc, Version=4.7.0.0, Culture=neutral, PublicKeyToken=dfbf2bd50fcf7768],[System.Boolean, System.Private.CoreLib, Version=7.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]):Registry:this
           7 ( 0.59% of base) : 60210.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.basic.operate007a.operate007a.Test:Test5():bool
           9 ( 0.54% of base) : 280169.dasm - System.Reflection.Metadata.Tests.MetadataReaderTests:ObfuscateWithExtraData(System.Byte[],bool):System.Byte[]

Top method improvements (percentages):
         -40 (-47.62% of base) : 172586.dasm - BasicEventSourceTests.TestEventCounter:ValidateSingleEventCounter(BasicEventSourceTests.Event,System.String,int,float,float,float,float)
         -50 (-46.73% of base) : 283523.dasm - System.Tests.MathFTests:SinCos(float,float,float,float,float)
         -40 (-43.48% of base) : 283544.dasm - System.Tests.MathFTests:Atan2(float,float,float,float)
         -40 (-43.48% of base) : 283513.dasm - System.Tests.MathFTests:Pow(float,float,float,float)
         -10 (-38.46% of base) : 163122.dasm - <>c:<GeneratePrimitiveExpression_InvokeWithoutOutput_ThrowsNullRefereneException>b__112_1(float,System.Action`1[Single]):this
         -10 (-38.46% of base) : 256458.dasm - <>c:<Half>b__5_1(float):System.Half:this
         -10 (-38.46% of base) : 248594.dasm - ComparableHashtable:.ctor(int,float):this
         -30 (-37.97% of base) : 283539.dasm - System.Tests.MathFTests:Acos(float,float,float)
         -30 (-37.97% of base) : 283540.dasm - System.Tests.MathFTests:Acosh(float,float,float)
         -30 (-37.97% of base) : 283541.dasm - System.Tests.MathFTests:Asin(float,float,float)
         -30 (-37.97% of base) : 283542.dasm - System.Tests.MathFTests:Asinh(float,float,float)
         -30 (-37.97% of base) : 283543.dasm - System.Tests.MathFTests:Atan(float,float,float)
         -30 (-37.97% of base) : 283545.dasm - System.Tests.MathFTests:Atanh(float,float,float)
         -30 (-37.97% of base) : 283548.dasm - System.Tests.MathFTests:Cbrt(float,float,float)
         -30 (-37.97% of base) : 283551.dasm - System.Tests.MathFTests:Cos(float,float,float)
         -30 (-37.97% of base) : 283552.dasm - System.Tests.MathFTests:Cosh(float,float,float)
         -30 (-37.97% of base) : 283553.dasm - System.Tests.MathFTests:Exp(float,float,float)
         -30 (-37.97% of base) : 283505.dasm - System.Tests.MathFTests:Log(float,float,float)
         -30 (-37.97% of base) : 283508.dasm - System.Tests.MathFTests:Log10(float,float,float)
         -30 (-37.97% of base) : 283507.dasm - System.Tests.MathFTests:Log2(float,float,float)

35839 total methods with Code Size differences (35791 improved, 48 regressed), 33 unchanged.

```

</details>

--------------------------------------------------------------------------------

