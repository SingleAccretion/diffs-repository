## benchmarks.run.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 19484
Total bytes of diff: 19364
Total bytes of delta: -120 (-0.62% of base)
Total relative delta: -0.28
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -16 : 17817.dasm (-2.63% of base)
         -12 : 15976.dasm (-0.82% of base)
          -8 : 16805.dasm (-1.53% of base)
          -8 : 18671.dasm (-2.35% of base)
          -8 : 17873.dasm (-0.20% of base)
          -4 : 15972.dasm (-0.49% of base)
          -4 : 9177.dasm (-1.61% of base)
          -4 : 9262.dasm (-0.46% of base)
          -4 : 16533.dasm (-0.41% of base)
          -4 : 828.dasm (-0.44% of base)
          -4 : 16259.dasm (-0.38% of base)
          -4 : 17832.dasm (-2.50% of base)
          -4 : 7294.dasm (-1.59% of base)
          -4 : 15931.dasm (-0.32% of base)
          -4 : 17816.dasm (-0.62% of base)
          -4 : 9944.dasm (-2.33% of base)
          -4 : 15929.dasm (-0.72% of base)
          -4 : 5916.dasm (-0.93% of base)
          -4 : 16271.dasm (-0.20% of base)
          -4 : 16262.dasm (-0.30% of base)

22 total files with Code Size differences (22 improved, 0 regressed), 1 unchanged.

Top method improvements (bytes):
         -16 (-2.63% of base) : 17817.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[SerializedSection]:this
         -12 (-0.82% of base) : 15976.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,System.Nullable`1[SyntaxTokenList],byref):int
          -8 (-1.53% of base) : 16805.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -8 (-2.35% of base) : 18671.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -8 (-0.20% of base) : 17873.dasm - System.Reflection.PortableExecutable.PEBuilder:WritePEHeader(System.Reflection.Metadata.BlobBuilder,System.Reflection.PortableExecutable.PEDirectoriesBuilder,System.Collections.Immutable.ImmutableArray`1[SerializedSection]):this
          -4 (-0.49% of base) : 15972.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:.ctor(Microsoft.CodeAnalysis.CSharp.Symbols.NamespaceOrTypeSymbol,Microsoft.CodeAnalysis.CSharp.MergedTypeDeclaration,Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-1.61% of base) : 9177.dasm - System.Text.Json.BitStack:PushToArray(bool):this
          -4 (-0.46% of base) : 9262.dasm - BitOps:DoBitfieldIteration(System.Int32[],System.Int32[],int,byref):long
          -4 (-0.41% of base) : 16533.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberMethodSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.44% of base) : 828.dasm - System.Sha1ForNonSecretPurposes:Drain():this
          -4 (-0.38% of base) : 16259.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceModuleSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-2.50% of base) : 17832.dasm - System.Reflection.PortableExecutable.ManagedTextSection:CalculateOffsetToMappedFieldDataStream():int:this
          -4 (-1.59% of base) : 7294.dasm - System.Text.RegularExpressions.RegexParser:ScanOptions():this
          -4 (-0.32% of base) : 15931.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.62% of base) : 17816.dasm - System.Reflection.PortableExecutable.PEBuilder:Serialize(System.Reflection.Metadata.BlobBuilder):System.Reflection.Metadata.BlobContentId:this
          -4 (-2.33% of base) : 9944.dasm - System.Threading.ManualResetEventSlim:UpdateStateAtomically(int,int):this
          -4 (-0.72% of base) : 15929.dasm - Microsoft.CodeAnalysis.CSharp.Imports:Complete(System.Threading.CancellationToken):this
          -4 (-0.93% of base) : 5916.dasm - Internal.Cryptography.Pal.ChainPal:GetChainStatusInformation(int):System.Security.Cryptography.X509Certificates.X509ChainStatus[]
          -4 (-0.20% of base) : 16271.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.30% of base) : 16262.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamespaceSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this

Top method improvements (percentages):
          -4 (-5.88% of base) : 17878.dasm - System.Reflection.Metadata.BlobBuilder:Align(int):this
         -16 (-2.63% of base) : 17817.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[SerializedSection]:this
          -4 (-2.50% of base) : 17832.dasm - System.Reflection.PortableExecutable.ManagedTextSection:CalculateOffsetToMappedFieldDataStream():int:this
          -8 (-2.35% of base) : 18671.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -4 (-2.33% of base) : 9944.dasm - System.Threading.ManualResetEventSlim:UpdateStateAtomically(int,int):this
          -4 (-1.75% of base) : 6667.dasm - System.Text.Encodings.Web.OptimizedInboxTextEncoder:.ctor(System.Text.Encodings.Web.ScalarEscaperBase,byref,bool,System.ReadOnlySpan`1[Char]):this
          -4 (-1.61% of base) : 9177.dasm - System.Text.Json.BitStack:PushToArray(bool):this
          -4 (-1.59% of base) : 7294.dasm - System.Text.RegularExpressions.RegexParser:ScanOptions():this
          -8 (-1.53% of base) : 16805.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -4 (-0.93% of base) : 5916.dasm - Internal.Cryptography.Pal.ChainPal:GetChainStatusInformation(int):System.Security.Cryptography.X509Certificates.X509ChainStatus[]
         -12 (-0.82% of base) : 15976.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,System.Nullable`1[SyntaxTokenList],byref):int
          -4 (-0.72% of base) : 15929.dasm - Microsoft.CodeAnalysis.CSharp.Imports:Complete(System.Threading.CancellationToken):this
          -4 (-0.62% of base) : 17816.dasm - System.Reflection.PortableExecutable.PEBuilder:Serialize(System.Reflection.Metadata.BlobBuilder):System.Reflection.Metadata.BlobContentId:this
          -4 (-0.49% of base) : 15972.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberContainerTypeSymbol:.ctor(Microsoft.CodeAnalysis.CSharp.Symbols.NamespaceOrTypeSymbol,Microsoft.CodeAnalysis.CSharp.MergedTypeDeclaration,Microsoft.CodeAnalysis.DiagnosticBag):this
          -4 (-0.46% of base) : 9262.dasm - BitOps:DoBitfieldIteration(System.Int32[],System.Int32[],int,byref):long
          -4 (-0.44% of base) : 828.dasm - System.Sha1ForNonSecretPurposes:Drain():this
          -4 (-0.41% of base) : 16533.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceMemberMethodSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.38% of base) : 16259.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceModuleSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.32% of base) : 15931.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-0.30% of base) : 16262.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceNamespaceSymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this

22 total methods with Code Size differences (22 improved, 0 regressed), 1 unchanged.

```

</details>

--------------------------------------------------------------------------------

## coreclr_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 3231948
Total bytes of diff: 3140556
Total bytes of delta: -91392 (-2.83% of base)
Total relative delta: -702.61
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           8 : 120629.dasm (1.89% of base)
           8 : 29902.dasm (1.89% of base)
           8 : 120080.dasm (2.02% of base)
           4 : 23509.dasm (1.00% of base)

Top file improvements (bytes):
         -24 : 29894.dasm (-5.83% of base)
         -24 : 164349.dasm (-0.18% of base)
         -24 : 106445.dasm (-5.94% of base)
         -24 : 7216.dasm (-6.12% of base)
         -24 : 36349.dasm (-5.94% of base)
         -24 : 45686.dasm (-5.45% of base)
         -24 : 199034.dasm (-3.47% of base)
         -24 : 199096.dasm (-3.90% of base)
         -16 : 173683.dasm (-3.01% of base)
         -16 : 173701.dasm (-3.01% of base)
         -16 : 173719.dasm (-3.05% of base)
         -16 : 173737.dasm (-3.05% of base)
         -16 : 173755.dasm (-3.15% of base)
         -16 : 173773.dasm (-3.01% of base)
         -16 : 175915.dasm (-3.20% of base)
         -16 : 175916.dasm (-3.31% of base)
         -16 : 175934.dasm (-3.20% of base)
         -16 : 175935.dasm (-3.31% of base)
         -16 : 175953.dasm (-3.20% of base)
         -16 : 175954.dasm (-3.31% of base)

15779 total files with Code Size differences (15775 improved, 4 regressed), 0 unchanged.

Top method regressions (bytes):
           8 ( 1.89% of base) : 120629.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__ZipLow_Vector128_UInt16):this
           8 ( 1.89% of base) : 29902.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__MultiplyRoundedDoublingSaturateHigh_Vector128_Int32):this
           8 ( 2.02% of base) : 120080.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__TransposeOdd_Vector128_Double):this
           4 ( 1.00% of base) : 23509.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__SubtractWideningUpper_Vector128_Int16_Vector128_SByte):this

Top method improvements (bytes):
         -24 (-5.83% of base) : 29894.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__MultiplyRoundedDoublingSaturateHigh_Vector128_Int16):this
         -24 (-0.18% of base) : 164349.dasm - Internal.IL.ILImporter:ImportBasicBlock(BasicBlock):this
         -24 (-5.94% of base) : 106445.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.ImmBinaryOpTest__ShiftLeftAndInsert_Vector128_Int32):this
         -24 (-6.12% of base) : 7216.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.InsertTest__Insert_Vector64_Single_1):this
         -24 (-5.94% of base) : 36349.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.InsertSelectedScalarTest__InsertSelectedScalar_Vector128_Int32_3_Vector128_Int32_3):this
         -24 (-5.45% of base) : 45686.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.ImmBinaryOpTest__MultiplyBySelectedScalar_Vector128_Double_Vector128_Double_1):this
         -24 (-3.47% of base) : 199034.dasm - JIT.HardwareIntrinsics.X86.SimpleBinaryOpTest__MultipleSumAbsoluteDifferences:RunReflectionScenario_UnsafeRead():this
         -24 (-3.90% of base) : 199096.dasm - JIT.HardwareIntrinsics.X86.SimpleBinaryOpTest__CompareGreaterThanInt64:RunReflectionScenario_UnsafeRead():this
         -16 (-3.01% of base) : 173683.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector256Int32Single:RunReflectionScenario_UnsafeRead():this
         -16 (-3.01% of base) : 173701.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector256SingleInt32:RunReflectionScenario_UnsafeRead():this
         -16 (-3.05% of base) : 173719.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector256DoubleSingle:RunReflectionScenario_UnsafeRead():this
         -16 (-3.05% of base) : 173737.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector256DoubleInt32:RunReflectionScenario_UnsafeRead():this
         -16 (-3.15% of base) : 173755.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int32WithTruncationDouble:RunReflectionScenario_UnsafeRead():this
         -16 (-3.01% of base) : 173773.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector256Int32WithTruncationSingle:RunReflectionScenario_UnsafeRead():this
         -16 (-3.20% of base) : 175915.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64SByte:RunReflectionScenario_UnsafeRead():this
         -16 (-3.31% of base) : 175916.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64SByte:RunReflectionScenario_Ptr():this
         -16 (-3.20% of base) : 175934.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64UInt16:RunReflectionScenario_UnsafeRead():this
         -16 (-3.31% of base) : 175935.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64UInt16:RunReflectionScenario_Ptr():this
         -16 (-3.20% of base) : 175953.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64UInt32:RunReflectionScenario_UnsafeRead():this
         -16 (-3.31% of base) : 175954.dasm - JIT.HardwareIntrinsics.X86.SimpleUnaryOpTest__ConvertToVector128Int64UInt32:RunReflectionScenario_Ptr():this

Top method regressions (percentages):
           8 ( 2.02% of base) : 120080.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__TransposeOdd_Vector128_Double):this
           8 ( 1.89% of base) : 120629.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__ZipLow_Vector128_UInt16):this
           8 ( 1.89% of base) : 29902.dasm - TestStruct:RunStructFldScenario_Load(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__MultiplyRoundedDoublingSaturateHigh_Vector128_Int32):this
           4 ( 1.00% of base) : 23509.dasm - TestStruct:RunStructFldScenario(JIT.HardwareIntrinsics.Arm.SimpleBinaryOpTest__SubtractWideningUpper_Vector128_Int16_Vector128_SByte):this

Top method improvements (percentages):
          -4 (-16.67% of base) : 6751.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(long,long):long
          -4 (-16.67% of base) : 6758.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(long,long):long
          -4 (-16.67% of base) : 6801.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(int,int):int
          -4 (-16.67% of base) : 6808.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(int,int):int
          -4 (-12.50% of base) : 164327.dasm - Internal.IL.ILImporter:ClearPendingPrefix(int):this
          -4 (-11.11% of base) : 6787.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(short,short):short
          -4 (-11.11% of base) : 6794.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(ushort,ushort):ushort
          -4 (-11.11% of base) : 6837.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(byte,byte):byte
          -4 (-11.11% of base) : 6844.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(ubyte,ubyte):ubyte
          -4 (-11.11% of base) : 6849.dasm - DataTable:Align(long,long):long
          -4 (-9.09% of base) : 105339.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(float,float):float
          -4 (-9.09% of base) : 105340.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-9.09% of base) : 107222.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(float,float):float
          -4 (-9.09% of base) : 107223.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-9.09% of base) : 109041.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(float,float):float
          -4 (-9.09% of base) : 109042.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-9.09% of base) : 120007.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(float,float):float
          -4 (-9.09% of base) : 120008.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-9.09% of base) : 138254.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(float,float):float
          -4 (-9.09% of base) : 138255.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double

15779 total methods with Code Size differences (15775 improved, 4 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 65304
Total bytes of diff: 64792
Total bytes of delta: -512 (-0.78% of base)
Total relative delta: -3.69
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 99824.dasm (8.33% of base)
           4 : 99843.dasm (1.69% of base)
           4 : 99904.dasm (8.33% of base)
           4 : 99905.dasm (8.33% of base)

Top file improvements (bytes):
         -20 : 173565.dasm (-1.03% of base)
         -20 : 45342.dasm (-2.12% of base)
         -16 : 157577.dasm (-2.63% of base)
         -12 : 20817.dasm (-2.88% of base)
          -8 : 45321.dasm (-0.52% of base)
          -8 : 157574.dasm (-0.11% of base)
          -8 : 65597.dasm (-2.82% of base)
          -8 : 65628.dasm (-2.82% of base)
          -8 : 95259.dasm (-1.09% of base)
          -8 : 146928.dasm (-0.70% of base)
          -8 : 66776.dasm (-7.41% of base)
          -8 : 32376.dasm (-1.63% of base)
          -8 : 45035.dasm (-2.20% of base)
          -4 : 111353.dasm (-1.39% of base)
          -4 : 20766.dasm (-0.58% of base)
          -4 : 2886.dasm (-1.06% of base)
          -4 : 40237.dasm (-1.06% of base)
          -4 : 5998.dasm (-0.89% of base)
          -4 : 69070.dasm (-4.17% of base)
          -4 : 91551.dasm (-10.00% of base)

114 total files with Code Size differences (110 improved, 4 regressed), 5 unchanged.

Top method regressions (bytes):
           4 ( 8.33% of base) : 99824.dasm - System.Xml.Xsl.XPathConvert:IsSpecial(double):bool
           4 ( 1.69% of base) : 99843.dasm - SequenceType:Create(System.Xml.Xsl.XmlQueryType,System.Xml.Xsl.XmlQueryCardinality):System.Xml.Xsl.XmlQueryType
           4 ( 8.33% of base) : 99904.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeMany():bool:this
           4 ( 8.33% of base) : 99905.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeEmpty():bool:this

Top method improvements (bytes):
         -20 (-1.03% of base) : 173565.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -20 (-2.12% of base) : 45342.dasm - Microsoft.Cci.PeWriter:CreateSectionHeaders(Microsoft.Cci.MetadataSizes,int):System.Collections.Generic.List`1[Microsoft.Cci.SectionHeader]:this
         -16 (-2.63% of base) : 157577.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[System.Reflection.PortableExecutable.PEBuilder+SerializedSection]:this
         -12 (-2.88% of base) : 20817.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int
          -8 (-0.52% of base) : 45321.dasm - Microsoft.Cci.PeWriter:FillInNtHeader(System.Collections.Generic.List`1[Microsoft.Cci.SectionHeader],int,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,byref,byref):this
          -8 (-0.11% of base) : 157574.dasm - System.Reflection.PortableExecutable.PEBuilder:WritePEHeader(System.Reflection.Metadata.BlobBuilder,System.Reflection.PortableExecutable.PEDirectoriesBuilder,System.Collections.Immutable.ImmutableArray`1[System.Reflection.PortableExecutable.PEBuilder+SerializedSection]):this
          -8 (-2.82% of base) : 65597.dasm - System.MathF:Round(float):float
          -8 (-2.82% of base) : 65628.dasm - System.Math:Round(double):double
          -8 (-1.09% of base) : 95259.dasm - System.Xml.Serialization.XmlCustomFormatter:FromEnum(long,System.String[],System.Int64[],System.String):System.String
          -8 (-0.70% of base) : 146928.dasm - System.Runtime.Serialization.DataContract:ComputeHash(System.Byte[]):System.Byte[]
          -8 (-7.41% of base) : 66776.dasm - System.Numerics.Vector`1:ConditionalSelect(System.Numerics.Vector`1[System.UInt64],System.Numerics.Vector`1[System.UInt64],System.Numerics.Vector`1[System.UInt64]):System.Numerics.Vector`1[System.UInt64]
          -8 (-1.63% of base) : 32376.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -8 (-2.20% of base) : 45035.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -4 (-1.39% of base) : 111353.dasm - System.Text.Json.BitStack:PushToArray(bool):this
          -4 (-0.58% of base) : 20766.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SourceAssemblySymbol:ForceComplete(Microsoft.CodeAnalysis.SourceLocation,System.Threading.CancellationToken):this
          -4 (-1.06% of base) : 2886.dasm - TreePage:AllocSlot(System.Data.RBTree`1[System.__Canon]):int:this
          -4 (-1.06% of base) : 40237.dasm - Roslyn.Utilities.ObjectReader:ReadCompressedUInt():int:this
          -4 (-0.89% of base) : 5998.dasm - System.Data.RBTree`1:GetIndexOfPageWithFreeSlot(bool):int:this
          -4 (-4.17% of base) : 69070.dasm - Microsoft.Diagnostics.Tracing.Ctf.CtfReader:Align(int):this
          -4 (-10.00% of base) : 91551.dasm - Internal.JitInterface.InstructionSetFlags:RemoveInstructionSet(int):this

Top method regressions (percentages):
           4 ( 8.33% of base) : 99824.dasm - System.Xml.Xsl.XPathConvert:IsSpecial(double):bool
           4 ( 8.33% of base) : 99904.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeMany():bool:this
           4 ( 8.33% of base) : 99905.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeEmpty():bool:this
           4 ( 1.69% of base) : 99843.dasm - SequenceType:Create(System.Xml.Xsl.XmlQueryType,System.Xml.Xsl.XmlQueryCardinality):System.Xml.Xsl.XmlQueryType

Top method improvements (percentages):
          -4 (-14.29% of base) : 69165.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignDown(int,int):int
          -4 (-12.50% of base) : 91546.dasm - Internal.JitInterface.InstructionSetFlags:Remove(Internal.JitInterface.InstructionSetFlags):this
          -4 (-12.50% of base) : 173568.dasm - Xunit.Sdk.Sha1Digest:F(int,int,int):int
          -4 (-12.50% of base) : 195937.dasm - System.DirectoryServices.AccountManagement.Utils:ClearBit(byref,int)
          -4 (-11.11% of base) : 87066.dasm - Microsoft.Diagnostics.Tracing.BPerfEventSource:AlignUp(int,int):int
          -4 (-11.11% of base) : 69167.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignUp(int,int):int
          -4 (-10.00% of base) : 91551.dasm - Internal.JitInterface.InstructionSetFlags:RemoveInstructionSet(int):this
          -4 (-10.00% of base) : 19600.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SymbolCompletionState:get_NextIncompletePart():int:this
          -4 (-10.00% of base) : 91554.dasm - Internal.JitInterface.CORJIT_FLAGS:Clear(int):this
          -4 (-9.09% of base) : 43346.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveParameterOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-9.09% of base) : 43352.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveMemberOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-9.09% of base) : 43349.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveKindOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-9.09% of base) : 150443.dasm - System.Security.AccessControl.CommonSecurityDescriptor:RemoveControlFlags(int):this
          -4 (-8.33% of base) : 150445.dasm - System.Security.AccessControl.CommonSecurityDescriptor:UpdateControlFlags(int,int):this
          -4 (-7.69% of base) : 154802.dasm - System.Reflection.Internal.BitArithmetic:Align(int,int):int
          -4 (-7.69% of base) : 40581.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-7.69% of base) : 40582.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-7.69% of base) : 154803.dasm - System.Reflection.Internal.BitArithmetic:Align(int,int):int
          -8 (-7.41% of base) : 66776.dasm - System.Numerics.Vector`1:ConditionalSelect(System.Numerics.Vector`1[System.UInt64],System.Numerics.Vector`1[System.UInt64],System.Numerics.Vector`1[System.UInt64]):System.Numerics.Vector`1[System.UInt64]
          -4 (-7.14% of base) : 201808.dasm - System.Configuration.SimpleBitVector32:set_Item(int,bool):this

114 total methods with Code Size differences (110 improved, 4 regressed), 5 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 113844
Total bytes of diff: 112888
Total bytes of delta: -956 (-0.84% of base)
Total relative delta: -4.85
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           4 : 129224.dasm (9.09% of base)
           4 : 129287.dasm (1.41% of base)
           4 : 129306.dasm (10.00% of base)
           4 : 132536.dasm (0.53% of base)
           4 : 129225.dasm (9.09% of base)

Top file improvements (bytes):
         -32 : 167746.dasm (-2.10% of base)
         -24 : 186783.dasm (-2.18% of base)
         -20 : 233323.dasm (-1.04% of base)
         -20 : 74391.dasm (-1.98% of base)
         -20 : 227909.dasm (-0.47% of base)
         -16 : 26400.dasm (-1.66% of base)
         -16 : 209170.dasm (-2.63% of base)
         -12 : 227915.dasm (-0.54% of base)
         -12 : 167771.dasm (-1.52% of base)
         -12 : 40826.dasm (-1.96% of base)
         -12 : 227578.dasm (-0.80% of base)
          -8 : 26685.dasm (-1.49% of base)
          -8 : 144593.dasm (-1.31% of base)
          -8 : 100640.dasm (-0.47% of base)
          -8 : 74412.dasm (-0.58% of base)
          -8 : 117185.dasm (-0.67% of base)
          -8 : 209173.dasm (-0.20% of base)
          -8 : 74718.dasm (-2.35% of base)
          -4 : 100541.dasm (-11.11% of base)
          -4 : 110543.dasm (-1.03% of base)

204 total files with Code Size differences (199 improved, 5 regressed), 7 unchanged.

Top method regressions (bytes):
           4 ( 9.09% of base) : 129224.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeEmpty():bool:this
           4 ( 1.41% of base) : 129287.dasm - SequenceType:Create(System.Xml.Xsl.XmlQueryType,System.Xml.Xsl.XmlQueryCardinality):System.Xml.Xsl.XmlQueryType
           4 (10.00% of base) : 129306.dasm - System.Xml.Xsl.XPathConvert:IsSpecial(double):bool
           4 ( 0.53% of base) : 132536.dasm - System.Xml.Xsl.IlGen.TailCallAnalyzer:AnalyzeDefinition(System.Xml.Xsl.Qil.QilNode)
           4 ( 9.09% of base) : 129225.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeMany():bool:this

Top method improvements (bytes):
         -32 (-2.10% of base) : 167746.dasm - System.ComponentModel.MaskedTextProvider:Clone():System.Object:this
         -24 (-2.18% of base) : 186783.dasm - System.IO.Ports.SerialStream:InitializeDCB(int,int,int,int,bool):this
         -20 (-1.04% of base) : 233323.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -20 (-1.98% of base) : 74391.dasm - Microsoft.Cci.PeWriter:CreateSectionHeaders(Microsoft.Cci.MetadataSizes,int):System.Collections.Generic.List`1[[Microsoft.Cci.SectionHeader, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
         -20 (-0.47% of base) : 227909.dasm - ILCompiler.DependencyAnalysis.ReadyToRun.ArgIterator:GetNextOffset():int:this
         -16 (-1.66% of base) : 26400.dasm - Microsoft.CodeAnalysis.CSharp.DataFlowPass:SetSlotUnassigned(int,byref):this
         -16 (-2.63% of base) : 209170.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[SerializedSection]:this
         -12 (-0.54% of base) : 227915.dasm - ILCompiler.DependencyAnalysis.ReadyToRun.ArgIterator:GetArgLoc(int):System.Nullable`1[ArgLocDesc]:this
         -12 (-1.52% of base) : 167771.dasm - System.ComponentModel.MaskedTextProvider:.ctor(System.String,System.Globalization.CultureInfo,bool,ushort,ushort,bool):this
         -12 (-1.96% of base) : 40826.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int
         -12 (-0.80% of base) : 227578.dasm - ILCompiler.PEWriter.R2RPEBuilder:SerializeSection(System.String,System.Reflection.PortableExecutable.SectionLocation):System.Reflection.Metadata.BlobBuilder:this
          -8 (-1.49% of base) : 26685.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -8 (-1.31% of base) : 144593.dasm - Internal.TypeSystem.LayoutInt:AlignUp(Internal.TypeSystem.LayoutInt,Internal.TypeSystem.LayoutInt,Internal.TypeSystem.TargetDetails):Internal.TypeSystem.LayoutInt
          -8 (-0.47% of base) : 100640.dasm - Microsoft.Diagnostics.Tracing.Ctf.CtfReader:ReadTypeIntoBuffer(Microsoft.Diagnostics.Tracing.Ctf.CtfStruct,Microsoft.Diagnostics.Tracing.Ctf.CtfMetadataType):this
          -8 (-0.58% of base) : 74412.dasm - Microsoft.Cci.PeWriter:FillInNtHeader(System.Collections.Generic.List`1[[Microsoft.Cci.SectionHeader, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]],int,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,Microsoft.Cci.DirectoryEntry,byref,byref):this
          -8 (-0.67% of base) : 117185.dasm - System.Runtime.Serialization.DataContract:ComputeHash(System.Byte[]):System.Byte[]
          -8 (-0.20% of base) : 209173.dasm - System.Reflection.PortableExecutable.PEBuilder:WritePEHeader(System.Reflection.Metadata.BlobBuilder,System.Reflection.PortableExecutable.PEDirectoriesBuilder,System.Collections.Immutable.ImmutableArray`1[SerializedSection]):this
          -8 (-2.35% of base) : 74718.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -4 (-11.11% of base) : 100541.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignUp(int,int):int
          -4 (-1.03% of base) : 110543.dasm - System.Data.Common.UInt64Storage:Set(int,System.Object):this

Top method regressions (percentages):
           4 (10.00% of base) : 129306.dasm - System.Xml.Xsl.XPathConvert:IsSpecial(double):bool
           4 ( 9.09% of base) : 129224.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeEmpty():bool:this
           4 ( 9.09% of base) : 129225.dasm - System.Xml.Xsl.XmlQueryType:get_MaybeMany():bool:this
           4 ( 1.41% of base) : 129287.dasm - SequenceType:Create(System.Xml.Xsl.XmlQueryType,System.Xml.Xsl.XmlQueryCardinality):System.Xml.Xsl.XmlQueryType
           4 ( 0.53% of base) : 132536.dasm - System.Xml.Xsl.IlGen.TailCallAnalyzer:AnalyzeDefinition(System.Xml.Xsl.Qil.QilNode)

Top method improvements (percentages):
          -4 (-14.29% of base) : 100543.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignDown(int,int):int
          -4 (-14.29% of base) : 76488.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveParameterOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-14.29% of base) : 76516.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveMemberOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-14.29% of base) : 76519.dasm - Microsoft.CodeAnalysis.SymbolDisplayFormat:RemoveKindOptions(int):Microsoft.CodeAnalysis.SymbolDisplayFormat:this
          -4 (-12.50% of base) : 229100.dasm - Internal.JitInterface.InstructionSetFlags:Remove(Internal.JitInterface.InstructionSetFlags):this
          -4 (-12.50% of base) : 233320.dasm - Xunit.Sdk.Sha1Digest:F(int,int,int):int
          -4 (-12.50% of base) : 177061.dasm - System.DirectoryServices.AccountManagement.Utils:ClearBit(byref,int)
          -4 (-11.11% of base) : 100541.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignUp(int,int):int
          -4 (-11.11% of base) : 82571.dasm - Microsoft.Diagnostics.Tracing.BPerfEventSource:AlignUp(int,int):int
          -4 (-10.00% of base) : 229092.dasm - Internal.JitInterface.CORJIT_FLAGS:Clear(int):this
          -4 (-10.00% of base) : 229095.dasm - Internal.JitInterface.InstructionSetFlags:RemoveInstructionSet(int):this
          -4 (-10.00% of base) : 42052.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SymbolCompletionState:get_NextIncompletePart():int:this
          -4 (-9.09% of base) : 214254.dasm - System.Security.AccessControl.CommonSecurityDescriptor:RemoveControlFlags(int):this
          -4 (-8.33% of base) : 214252.dasm - System.Security.AccessControl.CommonSecurityDescriptor:UpdateControlFlags(int,int):this
          -4 (-7.69% of base) : 212056.dasm - System.Reflection.Internal.BitArithmetic:Align(int,int):int
          -4 (-7.69% of base) : 79503.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-7.69% of base) : 79504.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-7.69% of base) : 212055.dasm - System.Reflection.Internal.BitArithmetic:Align(int,int):int
          -4 (-7.14% of base) : 170546.dasm - System.Configuration.SimpleBitVector32:set_Item(int,bool):this
          -4 (-6.67% of base) : 166918.dasm - System.ComponentModel.InterlockedBitVector32:DangerousSet(int,bool):this

204 total methods with Code Size differences (199 improved, 5 regressed), 7 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.windows.arm64.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 22772
Total bytes of diff: 22584
Total bytes of delta: -188 (-0.83% of base)
Total relative delta: -1.40
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
          -8 : 270860.dasm (-1.32% of base)
          -8 : 3639.dasm (-2.11% of base)
          -8 : 122537.dasm (-0.86% of base)
          -8 : 270863.dasm (-1.44% of base)
          -4 : 1107.dasm (-7.69% of base)
          -4 : 12069.dasm (-0.48% of base)
          -4 : 179178.dasm (-0.97% of base)
          -4 : 227193.dasm (-0.97% of base)
          -4 : 350621.dasm (-6.67% of base)
          -4 : 9887.dasm (-16.67% of base)
          -4 : 109626.dasm (-1.02% of base)
          -4 : 12067.dasm (-0.48% of base)
          -4 : 136382.dasm (-2.56% of base)
          -4 : 206722.dasm (-6.25% of base)
          -4 : 1108.dasm (-7.69% of base)
          -4 : 12064.dasm (-12.50% of base)
          -4 : 128932.dasm (-1.41% of base)
          -4 : 19180.dasm (-2.78% of base)
          -4 : 270861.dasm (-0.51% of base)
          -4 : 12051.dasm (-12.50% of base)

43 total files with Code Size differences (43 improved, 0 regressed), 0 unchanged.

Top method improvements (bytes):
          -8 (-1.32% of base) : 270860.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_UnsetAllTest()
          -8 (-2.11% of base) : 3639.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -8 (-0.86% of base) : 122537.dasm - Microsoft.CodeAnalysis.CSharp.Simplification.Simplifiers.CastSimplifier:CastRemovalWouldCauseSignExtensionWarning(Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,System.Threading.CancellationToken):bool
          -8 (-1.44% of base) : 270863.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_SectionTest(int,Section)
          -4 (-7.69% of base) : 1107.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-0.48% of base) : 12069.dasm - HashBucket[Int32,Nullable`1][System.Int32,System.Nullable`1[System.Int32]]:Remove(int,int,System.Collections.Generic.IEqualityComparer`1[Int32]):Bucket[Int32,Nullable`1]:this
          -4 (-0.97% of base) : 179178.dasm - System.Net.Http.HPack.HPackDecoder:ParseLiteralHeaderField(System.ReadOnlySpan`1[Byte],byref,ubyte,ubyte,ubyte,bool,System.Net.Http.IHttpHeadersHandler):this
          -4 (-0.97% of base) : 227193.dasm - System.Net.Http.HPack.HPackDecoder:ParseLiteralHeaderField(System.ReadOnlySpan`1[Byte],byref,ubyte,ubyte,ubyte,bool,System.Net.Http.IHttpHeadersHandler):this
          -4 (-6.67% of base) : 350621.dasm - Microsoft.Test.ModuleCore.TestPropertyAttribute:SetFlag(int,bool):this
          -4 (-16.67% of base) : 9887.dasm - Microsoft.CodeAnalysis.Editing.DeclarationModifiers:op_Subtraction(Microsoft.CodeAnalysis.Editing.DeclarationModifiers,Microsoft.CodeAnalysis.Editing.DeclarationModifiers):Microsoft.CodeAnalysis.Editing.DeclarationModifiers
          -4 (-1.02% of base) : 109626.dasm - reflectShrinkObj@257-18:GenerateNext(byref):int:this
          -4 (-0.48% of base) : 12067.dasm - HashBucket[Int16,Nullable`1][System.Int16,System.Nullable`1[System.Int32]]:Remove(int,short,System.Collections.Generic.IEqualityComparer`1[Int16]):Bucket[Int16,Nullable`1]:this
          -4 (-2.56% of base) : 136382.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetChainStatusFlags(System.Security.Cryptography.X509Certificates.X509Certificate2,int,byref,byref)
          -4 (-6.25% of base) : 206722.dasm - System.Text.Encodings.Web.AllowedBmpCodePointsBitmap:ForbidChar(ushort):this
          -4 (-7.69% of base) : 1108.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-12.50% of base) : 12064.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:RemoveBit(int,int):int
          -4 (-1.41% of base) : 128932.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Remove(long):bool:this
          -4 (-2.78% of base) : 19180.dasm - System.Collections.Tests.BitArray_OperatorsTests:Unset_Visible_Bits(System.Collections.BitArray):System.Collections.BitArray
          -4 (-0.51% of base) : 270861.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_MultipleTest(int,int,System.Int32[])
          -4 (-12.50% of base) : 12051.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:RemoveBit(int,int):int

Top method improvements (percentages):
          -4 (-16.67% of base) : 9887.dasm - Microsoft.CodeAnalysis.Editing.DeclarationModifiers:op_Subtraction(Microsoft.CodeAnalysis.Editing.DeclarationModifiers,Microsoft.CodeAnalysis.Editing.DeclarationModifiers):Microsoft.CodeAnalysis.Editing.DeclarationModifiers
          -4 (-16.67% of base) : 8923.dasm - Microsoft.CodeAnalysis.Formatting.FormattingExtensions:RemoveFlag(int,int):int
          -4 (-12.50% of base) : 12064.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:RemoveBit(int,int):int
          -4 (-12.50% of base) : 12051.dasm - HashBucket[__Canon,Nullable`1][System.__Canon,System.Nullable`1[System.Int32]]:RemoveBit(int,int):int
          -4 (-9.09% of base) : 9867.dasm - Microsoft.CodeAnalysis.Editing.DeclarationModifiers:SetFlag(int,int,bool):int
          -4 (-7.69% of base) : 1107.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-7.69% of base) : 1108.dasm - Roslyn.Utilities.BitArithmeticUtilities:Align(int,int):int
          -4 (-6.67% of base) : 350621.dasm - Microsoft.Test.ModuleCore.TestPropertyAttribute:SetFlag(int,bool):this
          -4 (-6.67% of base) : 222235.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -4 (-6.67% of base) : 217904.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -4 (-6.25% of base) : 206722.dasm - System.Text.Encodings.Web.AllowedBmpCodePointsBitmap:ForbidChar(ushort):this
          -4 (-2.78% of base) : 19180.dasm - System.Collections.Tests.BitArray_OperatorsTests:Unset_Visible_Bits(System.Collections.BitArray):System.Collections.BitArray
          -4 (-2.56% of base) : 136382.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetChainStatusFlags(System.Security.Cryptography.X509Certificates.X509Certificate2,int,byref,byref)
          -8 (-2.11% of base) : 3639.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -4 (-1.61% of base) : 92296.dasm - System.Text.Json.BitStack:PushToArray(bool):this
          -4 (-1.59% of base) : 331508.dasm - System.Text.RegularExpressions.RegexParser:ScanOptions():this
          -8 (-1.44% of base) : 270863.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_SectionTest(int,Section)
          -4 (-1.41% of base) : 128932.dasm - Microsoft.Diagnostics.Runtime.ObjectSet:Remove(long):bool:this
          -8 (-1.32% of base) : 270860.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_UnsetAllTest()
          -4 (-1.03% of base) : 135104.dasm - NuGet.Packaging.NuGetExtractionFileIO:ApplyUMaskToUnixPermissionsFromLibc()

43 total methods with Code Size differences (43 improved, 0 regressed), 0 unchanged.

```

</details>

--------------------------------------------------------------------------------

