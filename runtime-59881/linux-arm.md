## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 1600836
Total bytes of diff: 1572936
Total bytes of delta: -27900 (-1.74% of base)
Total relative delta: -510.58
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -12 : 161051.dasm (-0.10% of base)
         -12 : 205218.dasm (-1.75% of base)
         -10 : 207333.dasm (-1.61% of base)
          -6 : 118176.dasm (-1.58% of base)
          -6 : 118182.dasm (-1.60% of base)
          -6 : 118188.dasm (-1.58% of base)
          -6 : 118194.dasm (-1.58% of base)
          -6 : 118200.dasm (-1.58% of base)
          -6 : 129404.dasm (-1.00% of base)
          -6 : 141920.dasm (-1.00% of base)
          -6 : 141928.dasm (-1.00% of base)
          -6 : 141936.dasm (-1.00% of base)
          -6 : 141944.dasm (-1.00% of base)
          -6 : 141952.dasm (-1.00% of base)
          -6 : 141960.dasm (-1.00% of base)
          -6 : 141968.dasm (-1.00% of base)
          -6 : 156211.dasm (-1.01% of base)
          -6 : 156219.dasm (-1.01% of base)
          -6 : 156227.dasm (-1.01% of base)
          -6 : 156235.dasm (-1.01% of base)

11244 total files with Code Size differences (11244 improved, 0 regressed), 218 unchanged.

Top method improvements (bytes):
         -12 (-0.10% of base) : 161051.dasm - Internal.IL.ILImporter:ImportBasicBlock(BasicBlock):this
         -12 (-1.75% of base) : 205218.dasm - JIT.HardwareIntrinsics.X86.SimpleBinaryOpTest__MultipleSumAbsoluteDifferences:RunReflectionScenario_UnsafeRead():this
         -10 (-1.61% of base) : 207333.dasm - JIT.HardwareIntrinsics.X86.SimpleBinaryOpTest__CompareGreaterThanInt64:RunReflectionScenario_UnsafeRead():this
          -6 (-1.58% of base) : 118176.dasm - DataTable:.ctor(System.Int64[],System.Int64[],int):this
          -6 (-1.60% of base) : 118182.dasm - DataTable:.ctor(System.SByte[],System.SByte[],int):this
          -6 (-1.58% of base) : 118188.dasm - DataTable:.ctor(System.UInt16[],System.UInt16[],int):this
          -6 (-1.58% of base) : 118194.dasm - DataTable:.ctor(System.UInt32[],System.UInt32[],int):this
          -6 (-1.58% of base) : 118200.dasm - DataTable:.ctor(System.UInt64[],System.UInt64[],int):this
          -6 (-1.00% of base) : 129404.dasm - DataTable:.ctor(System.Double[],System.Double[],System.Double[],System.Double[],int):this
          -6 (-1.00% of base) : 141920.dasm - DataTable:.ctor(System.Int32[],System.Int32[],System.Int32[],System.Int32[],int):this
          -6 (-1.00% of base) : 141928.dasm - DataTable:.ctor(System.Int32[],System.Int32[],System.Int32[],System.Int32[],int):this
          -6 (-1.00% of base) : 141936.dasm - DataTable:.ctor(System.Int16[],System.Int16[],System.Int16[],System.Int16[],int):this
          -6 (-1.00% of base) : 141944.dasm - DataTable:.ctor(System.Int16[],System.Int16[],System.Int16[],System.Int16[],int):this
          -6 (-1.00% of base) : 141952.dasm - DataTable:.ctor(System.Int32[],System.Int32[],System.Int32[],System.Int32[],int):this
          -6 (-1.00% of base) : 141960.dasm - DataTable:.ctor(System.Int32[],System.Int32[],System.Int32[],System.Int32[],int):this
          -6 (-1.00% of base) : 141968.dasm - DataTable:.ctor(System.Int16[],System.Int16[],System.Int16[],System.Int16[],int):this
          -6 (-1.01% of base) : 156211.dasm - DataTable:.ctor(System.Int32[],System.SByte[],System.SByte[],System.Int32[],int):this
          -6 (-1.01% of base) : 156219.dasm - DataTable:.ctor(System.UInt32[],System.Byte[],System.Byte[],System.UInt32[],int):this
          -6 (-1.01% of base) : 156227.dasm - DataTable:.ctor(System.Int32[],System.SByte[],System.SByte[],System.Int32[],int):this
          -6 (-1.01% of base) : 156235.dasm - DataTable:.ctor(System.UInt32[],System.Byte[],System.Byte[],System.UInt32[],int):this

Top method improvements (percentages):
          -2 (-25.00% of base) : 7968.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(int,int):int
          -2 (-25.00% of base) : 8017.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(int,int):int
          -2 (-16.67% of base) : 161079.dasm - Internal.IL.ILImporter:ClearPendingPrefix(int):this
          -2 (-14.29% of base) : 7996.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(ubyte,ubyte):ubyte
          -2 (-14.29% of base) : 8003.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(short,short):short
          -2 (-14.29% of base) : 8010.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(ushort,ushort):ushort
          -2 (-14.29% of base) : 8045.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(byte,byte):byte
          -4 (-10.00% of base) : 159909.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 65941.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 141812.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 57517.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 79000.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 106208.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 129139.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 158601.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 62670.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 10850.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 121287.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 33289.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double
          -4 (-10.00% of base) : 51145.dasm - JIT.HardwareIntrinsics.Arm.Helpers:BitwiseClear(double,double):double

11244 total methods with Code Size differences (11244 improved, 0 regressed), 218 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.crossgen2.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 45212
Total bytes of diff: 45010
Total bytes of delta: -202 (-0.45% of base)
Total relative delta: -1.66
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -16 : 93728.dasm (-1.09% of base)
         -10 : 100819.dasm (-1.53% of base)
          -8 : 137902.dasm (-2.38% of base)
          -6 : 109521.dasm (-1.50% of base)
          -6 : 134581.dasm (-0.79% of base)
          -6 : 60508.dasm (-1.35% of base)
          -6 : 49345.dasm (-1.94% of base)
          -4 : 125572.dasm (-2.04% of base)
          -4 : 137871.dasm (-1.79% of base)
          -4 : 167975.dasm (-1.47% of base)
          -4 : 18323.dasm (-0.22% of base)
          -4 : 128380.dasm (-3.92% of base)
          -4 : 151296.dasm (-0.52% of base)
          -4 : 109518.dasm (-0.08% of base)
          -4 : 86298.dasm (-0.24% of base)
          -4 : 151415.dasm (-0.50% of base)
          -4 : 131659.dasm (-0.60% of base)
          -4 : 156598.dasm (-0.26% of base)
          -4 : 174443.dasm (-2.70% of base)
          -4 : 129070.dasm (-3.92% of base)

65 total files with Code Size differences (65 improved, 0 regressed), 45 unchanged.

Top method improvements (bytes):
         -16 (-1.09% of base) : 93728.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -10 (-1.53% of base) : 100819.dasm - Microsoft.Cci.PeWriter:CreateSectionHeaders(Microsoft.Cci.MetadataSizes,int):System.Collections.Generic.List`1[Microsoft.Cci.SectionHeader]:this
          -8 (-2.38% of base) : 137902.dasm - System.Math:Round(double):double
          -6 (-1.50% of base) : 109521.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[System.Reflection.PortableExecutable.PEBuilder+SerializedSection]:this
          -6 (-0.79% of base) : 134581.dasm - System.Number:AssembleFloatingPointBits(byref,long,int,bool):long
          -6 (-1.35% of base) : 60508.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -6 (-1.94% of base) : 49345.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int
          -4 (-2.04% of base) : 125572.dasm - System.Runtime.InteropServices.NativeMemory:AlignedRealloc(int,int,int):int
          -4 (-1.79% of base) : 137871.dasm - System.MathF:Round(float):float
          -4 (-1.47% of base) : 167975.dasm - System.Data.RBTree`1:GetIndexOfPageWithFreeSlot(bool):int:this
          -4 (-0.22% of base) : 18323.dasm - System.ComponentModel.EnumConverter:ConvertTo(System.ComponentModel.ITypeDescriptorContext,System.Globalization.CultureInfo,System.Object,System.Type):System.Object:this
          -4 (-3.92% of base) : 128380.dasm - ThreadCounts:SetInt16Value(short,ubyte):this
          -4 (-0.52% of base) : 151296.dasm - System.Runtime.Serialization.EnumDataContract:WriteEnumValue(System.Runtime.Serialization.XmlWriterDelegator,System.Object):this
          -4 (-0.08% of base) : 109518.dasm - System.Reflection.PortableExecutable.PEBuilder:WritePEHeader(System.Reflection.Metadata.BlobBuilder,System.Reflection.PortableExecutable.PEDirectoriesBuilder,System.Collections.Immutable.ImmutableArray`1[System.Reflection.PortableExecutable.PEBuilder+SerializedSection]):this
          -4 (-0.24% of base) : 86298.dasm - Microsoft.CodeAnalysis.VisualBasic.Symbols.SourceNamedTypeSymbol:CheckDeclarationModifiers(Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxNode,Microsoft.CodeAnalysis.VisualBasic.Binder,Microsoft.CodeAnalysis.DiagnosticBag,int):int:this
          -4 (-0.50% of base) : 151415.dasm - System.Runtime.Serialization.DataContract:ComputeHash(System.Byte[]):System.Byte[]
          -4 (-0.60% of base) : 131659.dasm - System.Sha1ForNonSecretPurposes:Drain():this
          -4 (-0.26% of base) : 156598.dasm - Internal.Cryptography.Pal.OpenSslX509ChainProcessor:FinishRevocation(int,int,int):this
          -4 (-2.70% of base) : 174443.dasm - System.Text.Encodings.Web.TextEncoderSettings:ForbidRange(System.Text.Unicode.UnicodeRange):this
          -4 (-3.92% of base) : 129070.dasm - Counts:SetUInt32Value(int,ubyte):this

Top method improvements (percentages):
          -2 (-20.00% of base) : 23455.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignDown(int,int):int
          -2 (-14.29% of base) : 41669.dasm - Microsoft.Diagnostics.Tracing.BPerfEventSource:AlignUp(int,int):int
          -2 (-14.29% of base) : 23457.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignUp(int,int):int
          -2 (-8.33% of base) : 154060.dasm - System.Configuration.SimpleBitVector32:set_Item(int,bool):this
          -2 (-7.69% of base) : 5382.dasm - Options:SetFlag(int,bool):this
          -2 (-7.69% of base) : 186995.dasm - System.Collections.Specialized.BitVector32:set_Item(int,bool):this
          -2 (-7.14% of base) : 48129.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SymbolCompletionState:get_NextIncompletePart():int:this
          -2 (-5.88% of base) : 18066.dasm - System.ComponentModel.InterlockedBitVector32:DangerousSet(int,bool):this
          -2 (-5.26% of base) : 182626.dasm - CacheEntryState:SetFlag(ubyte,bool):this
          -2 (-5.26% of base) : 140523.dasm - Internal.JitInterface.InstructionSetFlags:Remove(Internal.JitInterface.InstructionSetFlags):this
          -2 (-4.35% of base) : 156563.dasm - ErrorCollection:ClearError(Interop+Crypto+X509VerifyStatusCode):this
          -4 (-3.92% of base) : 128380.dasm - ThreadCounts:SetInt16Value(short,ubyte):this
          -4 (-3.92% of base) : 129070.dasm - Counts:SetUInt32Value(int,ubyte):this
          -2 (-3.45% of base) : 95946.dasm - Roslyn.Utilities.ThreadSafeFlagOperations:Clear(byref,int):bool
          -2 (-3.03% of base) : 181655.dasm - System.Runtime.Caching.SafeBitVector32:set_Item(int,bool):this
          -2 (-3.03% of base) : 154309.dasm - System.Configuration.SafeBitVector32:set_Item(int,bool):this
          -2 (-2.86% of base) : 17141.dasm - System.ComponentModel.Design.MenuCommand:SetStatus(int,bool):this
          -4 (-2.70% of base) : 174443.dasm - System.Text.Encodings.Web.TextEncoderSettings:ForbidRange(System.Text.Unicode.UnicodeRange):this
          -2 (-2.56% of base) : 181654.dasm - System.Runtime.Caching.SafeBitVector32:ChangeValue(int,bool):bool:this
          -8 (-2.38% of base) : 137902.dasm - System.Math:Round(double):double

65 total methods with Code Size differences (65 improved, 0 regressed), 45 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 72192
Total bytes of diff: 71866
Total bytes of delta: -326 (-0.45% of base)
Total relative delta: -2.11
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file improvements (bytes):
         -16 : 59705.dasm (-1.09% of base)
         -12 : 122712.dasm (-7.89% of base)
         -10 : 113394.dasm (-1.30% of base)
          -8 : 61442.dasm (-0.60% of base)
          -8 : 107451.dasm (-1.29% of base)
          -6 : 158318.dasm (-4.84% of base)
          -6 : 93885.dasm (-1.16% of base)
          -6 : 55891.dasm (-1.23% of base)
          -4 : 161244.dasm (-1.71% of base)
          -4 : 161740.dasm (-1.74% of base)
          -4 : 161782.dasm (-2.02% of base)
          -4 : 26879.dasm (-0.19% of base)
          -4 : 161768.dasm (-2.02% of base)
          -4 : 159225.dasm (-1.60% of base)
          -4 : 60345.dasm (-0.22% of base)
          -4 : 161754.dasm (-1.94% of base)
          -4 : 161861.dasm (-2.06% of base)
          -4 : 193361.dasm (-2.60% of base)
          -4 : 6796.dasm (-0.49% of base)
          -4 : 161877.dasm (-1.94% of base)

107 total files with Code Size differences (107 improved, 0 regressed), 79 unchanged.

Top method improvements (bytes):
         -16 (-1.09% of base) : 59705.dasm - Xunit.Sdk.Sha1Digest:ProcessBlock():this
         -12 (-7.89% of base) : 122712.dasm - System.Numerics.Vector`1[Byte][System.Byte]:ConditionalSelect(System.Numerics.Vector`1[Byte],System.Numerics.Vector`1[Byte],System.Numerics.Vector`1[Byte]):System.Numerics.Vector`1[Byte]
         -10 (-1.30% of base) : 113394.dasm - Microsoft.Cci.PeWriter:CreateSectionHeaders(Microsoft.Cci.MetadataSizes,int):System.Collections.Generic.List`1[[Microsoft.Cci.SectionHeader, Microsoft.CodeAnalysis, Version=1.1.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35]]:this
          -8 (-0.60% of base) : 61442.dasm - System.ComponentModel.MaskedTextProvider:Clone():System.Object:this
          -8 (-1.29% of base) : 107451.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.ModifierUtils:CheckModifiers(int,int,Microsoft.CodeAnalysis.Location,Microsoft.CodeAnalysis.DiagnosticBag,byref):int
          -6 (-4.84% of base) : 158318.dasm - TableChanges:set_Item(int,bool):this
          -6 (-1.16% of base) : 93885.dasm - Microsoft.CodeAnalysis.CSharp.DiagnosticsPass:CheckForBitwiseOrSignExtend(Microsoft.CodeAnalysis.CSharp.BoundExpression,int,Microsoft.CodeAnalysis.CSharp.BoundExpression,Microsoft.CodeAnalysis.CSharp.BoundExpression):this
          -6 (-1.23% of base) : 55891.dasm - System.Reflection.PortableExecutable.PEBuilder:SerializeSections():System.Collections.Immutable.ImmutableArray`1[SerializedSection]:this
          -4 (-1.71% of base) : 161244.dasm - System.Data.Common.DateTimeOffsetStorage:Copy(int,int):this
          -4 (-1.74% of base) : 161740.dasm - System.Data.Common.DecimalStorage:Copy(int,int):this
          -4 (-2.02% of base) : 161782.dasm - System.Data.Common.Int32Storage:Copy(int,int):this
          -4 (-0.19% of base) : 26879.dasm - Internal.Cryptography.Pal.OpenSslX509ChainProcessor:FinishRevocation(int,int,int):this
          -4 (-2.02% of base) : 161768.dasm - System.Data.Common.Int16Storage:Copy(int,int):this
          -4 (-1.60% of base) : 159225.dasm - System.Data.RBTree`1[Byte][System.Byte]:GetIndexOfPageWithFreeSlot(bool):int:this
          -4 (-0.22% of base) : 60345.dasm - System.ComponentModel.EnumConverter:ConvertTo(System.ComponentModel.ITypeDescriptorContext,System.Globalization.CultureInfo,System.Object,System.Type):System.Object:this
          -4 (-1.94% of base) : 161754.dasm - System.Data.Common.DoubleStorage:Copy(int,int):this
          -4 (-2.06% of base) : 161861.dasm - System.Data.Common.SByteStorage:Copy(int,int):this
          -4 (-2.60% of base) : 193361.dasm - System.Text.Encodings.Web.TextEncoderSettings:ForbidRange(System.Text.Unicode.UnicodeRange):this
          -4 (-0.49% of base) : 6796.dasm - Microsoft.Diagnostics.Tracing.Parsers.DynamicTraceEventData:PayloadString(int,System.IFormatProvider):System.String:this
          -4 (-1.94% of base) : 161877.dasm - System.Data.Common.SingleStorage:Copy(int,int):this

Top method improvements (percentages):
          -2 (-20.00% of base) : 23418.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignDown(int,int):int
          -2 (-14.29% of base) : 5011.dasm - Microsoft.Diagnostics.Tracing.BPerfEventSource:AlignUp(int,int):int
          -2 (-14.29% of base) : 23416.dasm - Microsoft.Diagnostics.Tracing.Ctf.IntHelpers:AlignUp(int,int):int
          -2 (-8.33% of base) : 63484.dasm - System.Configuration.SimpleBitVector32:set_Item(int,bool):this
         -12 (-7.89% of base) : 122712.dasm - System.Numerics.Vector`1[Byte][System.Byte]:ConditionalSelect(System.Numerics.Vector`1[Byte],System.Numerics.Vector`1[Byte],System.Numerics.Vector`1[Byte]):System.Numerics.Vector`1[Byte]
          -2 (-7.69% of base) : 77308.dasm - Options:SetFlag(int,bool):this
          -2 (-7.69% of base) : 184501.dasm - System.Collections.Specialized.BitVector32:set_Item(int,bool):this
          -2 (-7.14% of base) : 108674.dasm - Microsoft.CodeAnalysis.CSharp.Symbols.SymbolCompletionState:get_NextIncompletePart():int:this
          -2 (-5.88% of base) : 60596.dasm - System.ComponentModel.InterlockedBitVector32:DangerousSet(int,bool):this
          -2 (-5.26% of base) : 208613.dasm - CacheEntryState:SetFlag(ubyte,bool):this
          -6 (-4.84% of base) : 158318.dasm - TableChanges:set_Item(int,bool):this
          -2 (-3.70% of base) : 118826.dasm - Roslyn.Utilities.ThreadSafeFlagOperations:Clear(byref,int):bool
          -4 (-2.60% of base) : 193361.dasm - System.Text.Encodings.Web.TextEncoderSettings:ForbidRange(System.Text.Unicode.UnicodeRange):this
          -2 (-2.56% of base) : 26908.dasm - ErrorCollection:ClearError(X509VerifyStatusCode):this
          -2 (-2.56% of base) : 61572.dasm - System.ComponentModel.Design.MenuCommand:SetStatus(int,bool):this
          -4 (-2.06% of base) : 161861.dasm - System.Data.Common.SByteStorage:Copy(int,int):this
          -4 (-2.06% of base) : 160980.dasm - System.Data.Common.ByteStorage:Copy(int,int):this
          -4 (-2.06% of base) : 160966.dasm - System.Data.Common.BooleanStorage:Copy(int,int):this
          -4 (-2.02% of base) : 161782.dasm - System.Data.Common.Int32Storage:Copy(int,int):this
          -4 (-2.02% of base) : 161768.dasm - System.Data.Common.Int16Storage:Copy(int,int):this

107 total methods with Code Size differences (107 improved, 0 regressed), 79 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 19008
Total bytes of diff: 18930
Total bytes of delta: -78 (-0.41% of base)
Total relative delta: -0.70
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 242712.dasm (1.47% of base)
           2 : 242710.dasm (0.12% of base)

Top file improvements (bytes):
         -12 : 226985.dasm (-0.47% of base)
          -4 : 334227.dasm (-0.61% of base)
          -4 : 170784.dasm (-0.50% of base)
          -4 : 216289.dasm (-1.18% of base)
          -4 : 216294.dasm (-1.18% of base)
          -2 : 174321.dasm (-0.65% of base)
          -2 : 239202.dasm (-5.88% of base)
          -2 : 54546.dasm (-0.32% of base)
          -2 : 185053.dasm (-0.15% of base)
          -2 : 241508.dasm (-0.35% of base)
          -2 : 36538.dasm (-1.75% of base)
          -2 : 54550.dasm (-0.32% of base)
          -2 : 233920.dasm (-5.88% of base)
          -2 : 241509.dasm (-0.75% of base)
          -2 : 334229.dasm (-0.34% of base)
          -2 : 54531.dasm (-0.32% of base)
          -2 : 52351.dasm (-11.11% of base)
          -2 : 54548.dasm (-0.31% of base)
          -2 : 216284.dasm (-0.68% of base)
          -2 : 284448.dasm (-7.69% of base)

34 total files with Code Size differences (32 improved, 2 regressed), 9 unchanged.

Top method regressions (bytes):
           2 ( 1.47% of base) : 242712.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetChainStatusFlags(System.Security.Cryptography.X509Certificates.X509Certificate2,int,byref,byref)
           2 ( 0.12% of base) : 242710.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetCertificateChain(System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,NuGet.Common.ILogger,int):NuGet.Packaging.Signing.IX509CertificateChain

Top method improvements (bytes):
         -12 (-0.47% of base) : 226985.dasm - System.Reflection.Metadata.Tests.TagToTokenTests:ValidateTagToTokenConversion():this
          -4 (-0.61% of base) : 334227.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_UnsetAllTest()
          -4 (-0.50% of base) : 170784.dasm - Microsoft.CodeAnalysis.CSharp.Simplification.Simplifiers.CastSimplifier:CastRemovalWouldCauseSignExtensionWarning(Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,System.Threading.CancellationToken):bool
          -4 (-1.18% of base) : 216289.dasm - reflectShrinkObj@256-17:GenerateNext(byref):int:this
          -4 (-1.18% of base) : 216294.dasm - reflectShrinkObj@257-18:GenerateNext(byref):int:this
          -2 (-0.65% of base) : 174321.dasm - System.Net.Http.HPack.HPackDecoder:ParseLiteralHeaderField(System.ReadOnlySpan`1[Byte],byref,ubyte,ubyte,ubyte,bool,System.Net.Http.IHttpHeadersHandler):this
          -2 (-5.88% of base) : 239202.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -2 (-0.32% of base) : 54546.dasm - HashBucket[Double,Nullable`1][System.Double,System.Nullable`1[System.Int32]]:Remove(int,double,System.Collections.Generic.IEqualityComparer`1[Double]):Bucket[Double,Nullable`1]:this
          -2 (-0.15% of base) : 185053.dasm - DryIoc.Rules:ToString():System.String:this
          -2 (-0.35% of base) : 241508.dasm - NuGet.Packaging.NuGetExtractionFileIO:ApplyUMaskToUnixPermissionsFromProcess():bool
          -2 (-1.75% of base) : 36538.dasm - System.Collections.Tests.BitArray_OperatorsTests:Unset_Visible_Bits(System.Collections.BitArray):System.Collections.BitArray
          -2 (-0.32% of base) : 54550.dasm - HashBucket[Int64,Nullable`1][System.Int64,System.Nullable`1[System.Int32]]:Remove(int,long,System.Collections.Generic.IEqualityComparer`1[Int64]):Bucket[Int64,Nullable`1]:this
          -2 (-5.88% of base) : 233920.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -2 (-0.75% of base) : 241509.dasm - NuGet.Packaging.NuGetExtractionFileIO:ApplyUMaskToUnixPermissionsFromLibc()
          -2 (-0.34% of base) : 334229.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_Multiple_UnsetTest(int,int,System.Int32[])
          -2 (-0.32% of base) : 54531.dasm - HashBucket[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:Remove(int,ubyte,System.Collections.Generic.IEqualityComparer`1[Byte]):Bucket[Byte,Nullable`1]:this
          -2 (-11.11% of base) : 52351.dasm - Microsoft.CodeAnalysis.Editing.DeclarationModifiers:SetFlag(int,int,bool):int
          -2 (-0.31% of base) : 54548.dasm - HashBucket[Vector`1,Nullable`1][System.Numerics.Vector`1[System.Single],System.Nullable`1[System.Int32]]:Remove(int,System.Numerics.Vector`1[Single],System.Collections.Generic.IEqualityComparer`1[Vector`1]):Bucket[Vector`1,Nullable`1]:this
          -2 (-0.68% of base) : 216284.dasm - reflectShrinkObj@255-16:GenerateNext(byref):int:this
          -2 (-7.69% of base) : 284448.dasm - Microsoft.Test.ModuleCore.TestPropertyAttribute:SetFlag(int,bool):this

Top method regressions (percentages):
           2 ( 1.47% of base) : 242712.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetChainStatusFlags(System.Security.Cryptography.X509Certificates.X509Certificate2,int,byref,byref)
           2 ( 0.12% of base) : 242710.dasm - NuGet.Packaging.Signing.CertificateChainUtility:GetCertificateChain(System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,NuGet.Common.ILogger,int):NuGet.Packaging.Signing.IX509CertificateChain

Top method improvements (percentages):
          -2 (-25.00% of base) : 51395.dasm - Microsoft.CodeAnalysis.Formatting.FormattingExtensions:RemoveFlag(int,int):int
          -2 (-11.11% of base) : 52351.dasm - Microsoft.CodeAnalysis.Editing.DeclarationModifiers:SetFlag(int,int,bool):int
          -2 (-7.69% of base) : 284448.dasm - Microsoft.Test.ModuleCore.TestPropertyAttribute:SetFlag(int,bool):this
          -2 (-5.88% of base) : 239202.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -2 (-5.88% of base) : 233920.dasm - System.Data.SqlClient._SqlMetaData:Set(int,bool):this
          -2 (-1.75% of base) : 36538.dasm - System.Collections.Tests.BitArray_OperatorsTests:Unset_Visible_Bits(System.Collections.BitArray):System.Collections.BitArray
          -2 (-1.30% of base) : 282220.dasm - System.Text.RegularExpressions.RegexParser:ScanOptions():this
          -4 (-1.18% of base) : 216289.dasm - reflectShrinkObj@256-17:GenerateNext(byref):int:this
          -4 (-1.18% of base) : 216294.dasm - reflectShrinkObj@257-18:GenerateNext(byref):int:this
          -2 (-1.00% of base) : 74322.dasm - System.Text.Json.BitStack:PushToArray(bool):this
          -2 (-0.75% of base) : 241509.dasm - NuGet.Packaging.NuGetExtractionFileIO:ApplyUMaskToUnixPermissionsFromLibc()
          -2 (-0.68% of base) : 46011.dasm - Microsoft.CodeAnalysis.BitVector:set_Item(int,bool):this
          -2 (-0.68% of base) : 216284.dasm - reflectShrinkObj@255-16:GenerateNext(byref):int:this
          -2 (-0.68% of base) : 216279.dasm - reflectShrinkObj@254-15:GenerateNext(byref):int:this
          -2 (-0.65% of base) : 174321.dasm - System.Net.Http.HPack.HPackDecoder:ParseLiteralHeaderField(System.ReadOnlySpan`1[Byte],byref,ubyte,ubyte,ubyte,bool,System.Net.Http.IHttpHeadersHandler):this
          -2 (-0.65% of base) : 337442.dasm - System.Net.Http.HPack.HPackDecoder:ParseLiteralHeaderField(System.ReadOnlySpan`1[Byte],byref,ubyte,ubyte,ubyte,bool,System.Net.Http.IHttpHeadersHandler):this
          -4 (-0.61% of base) : 334227.dasm - System.Collections.Specialized.Tests.BitVector32Tests:Set_Mask_UnsetAllTest()
          -2 (-0.52% of base) : 179790.dasm - Microsoft.Diagnostics.Runtime.ParallelObjectSet:Remove(long):bool:this
          -4 (-0.50% of base) : 170784.dasm - Microsoft.CodeAnalysis.CSharp.Simplification.Simplifiers.CastSimplifier:CastRemovalWouldCauseSignExtensionWarning(Microsoft.CodeAnalysis.CSharp.Syntax.ExpressionSyntax,Microsoft.CodeAnalysis.SemanticModel,System.Threading.CancellationToken):bool
         -12 (-0.47% of base) : 226985.dasm - System.Reflection.Metadata.Tests.TagToTokenTests:ValidateTagToTokenConversion():this

34 total methods with Code Size differences (32 improved, 2 regressed), 9 unchanged.

```

</details>

--------------------------------------------------------------------------------

