## coreclr_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 163514792 (overridden on cmd)
Total bytes of diff: 163521912 (overridden on cmd)
Total bytes of delta: 7120 (0.00 % of base)
    diff is a regression.
    relative diff is a regression.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
         144 : 148093.dasm (0.01% of base)
          14 : 206081.dasm (2.51% of base)
          14 : 183593.dasm (2.51% of base)
          10 : 245104.dasm (0.12% of base)
           8 : 89867.dasm (0.36% of base)
           6 : 258796.dasm (0.32% of base)
           4 : 111492.dasm (1.35% of base)
           4 : 111494.dasm (1.30% of base)
           4 : 111642.dasm (1.12% of base)
           4 : 111647.dasm (1.18% of base)
           4 : 111652.dasm (0.90% of base)
           4 : 153957.dasm (0.93% of base)
           4 : 153983.dasm (0.92% of base)
           4 : 153999.dasm (0.90% of base)
           4 : 158126.dasm (1.18% of base)
           4 : 158128.dasm (0.93% of base)
           4 : 158130.dasm (0.92% of base)
           4 : 158148.dasm (1.28% of base)
           4 : 158158.dasm (2.02% of base)
           4 : 158172.dasm (0.96% of base)

Top file improvements (bytes):
        -866 : 129686.dasm (-0.95% of base)
        -250 : 209469.dasm (-1.36% of base)
        -190 : 209470.dasm (-1.14% of base)
        -158 : 243980.dasm (-1.12% of base)
        -158 : 243139.dasm (-1.12% of base)
        -142 : 228227.dasm (-2.43% of base)
        -130 : 209468.dasm (-1.01% of base)
         -94 : 209441.dasm (-0.94% of base)
         -90 : 209467.dasm (-0.96% of base)
         -78 : 209464.dasm (-1.09% of base)
         -58 : 193612.dasm (-5.24% of base)
         -58 : 193592.dasm (-4.23% of base)
         -56 : 256977.dasm (-1.63% of base)
         -56 : 254281.dasm (-1.63% of base)
         -54 : 87606.dasm (-2.81% of base)
         -50 : 205835.dasm (-1.06% of base)
         -46 : 209444.dasm (-0.90% of base)
         -46 : 93667.dasm (-5.11% of base)
         -46 : 93930.dasm (-5.09% of base)
         -46 : 93136.dasm (-5.09% of base)

8558 total files with Code Size differences (693 improved, 7865 regressed), 19264 unchanged.

Top method regressions (bytes):
         144 ( 0.01% of base) : 148093.dasm - NullableTest:And()
          14 ( 2.51% of base) : 206081.dasm - testout1:Func_0_1_1_1_1_1_1_1_1_1_1_1_1():int
          14 ( 2.51% of base) : 183593.dasm - testout1:Func_0_1_1_1_1_1_1_1_1_1_1_1_1():int
          10 ( 0.12% of base) : 245104.dasm - StrAccess1:Main():int
           8 ( 0.36% of base) : 89867.dasm - P:Main():int
           6 ( 0.32% of base) : 258796.dasm - EHTest:f1(int,long,long,int):int
           4 ( 9.52% of base) : 96423.dasm - _volatile:main(System.String[]):int
           4 ( 2.50% of base) : 259273.dasm - GitHub_18884:ReproUx(long,long,ushort,ubyte)
           4 ( 4.65% of base) : 96972.dasm - ILGEN_0x2e194c20:main():int
           4 ( 0.27% of base) : 253701.dasm - ShiftTest.ulong32Test:Main():int
           4 ( 2.11% of base) : 96449.dasm - test:main(System.String[]):int
           4 ( 0.08% of base) : 226136.dasm - testout1:Sub_Funclet_1():int
           4 ( 0.08% of base) : 231430.dasm - testout1:Sub_Funclet_1():int
           4 ( 0.90% of base) : 171954.dasm - testout1:Sub_Funclet_100():int
           4 ( 0.84% of base) : 154156.dasm - testout1:Sub_Funclet_100():int
           4 ( 1.63% of base) : 163172.dasm - testout1:Sub_Funclet_103():int
           4 ( 1.63% of base) : 158260.dasm - testout1:Sub_Funclet_103():int
           4 ( 1.12% of base) : 111614.dasm - testout1:Sub_Funclet_103():int
           4 ( 1.20% of base) : 154160.dasm - testout1:Sub_Funclet_104():int
           4 ( 1.16% of base) : 158263.dasm - testout1:Sub_Funclet_106():int

Top method improvements (bytes):
        -866 (-0.95% of base) : 129686.dasm - testout1:.cctor()
        -250 (-1.36% of base) : 209469.dasm - Dynamic.EventTest:MultipleHandlers():this
        -190 (-1.14% of base) : 209470.dasm - Dynamic.EventTest:MultipleSources():this
        -158 (-1.12% of base) : 243980.dasm - StrAccess2:Main():int
        -158 (-1.12% of base) : 243139.dasm - StrAccess2:Main():int
        -142 (-2.43% of base) : 228227.dasm - testout1:.cctor()
        -130 (-1.01% of base) : 209468.dasm - Dynamic.EventTest:DynamicEventHandler():this
         -94 (-0.94% of base) : 209441.dasm - Dynamic.BasicTest:ComObject():this
         -90 (-0.96% of base) : 209467.dasm - Dynamic.EventTest:FireEvent():this
         -78 (-1.09% of base) : 209464.dasm - Dynamic.CollectionTest:IndexChain():this
         -58 (-4.23% of base) : 193592.dasm - Neural:.cctor()
         -58 (-5.24% of base) : 193612.dasm - NeuralJagged:.cctor()
         -56 (-1.63% of base) : 256977.dasm - testout1:Func_0():double
         -56 (-1.63% of base) : 254281.dasm - testout1:Func_0():double
         -54 (-2.81% of base) : 87606.dasm - CCSE:Main():int
         -50 (-1.06% of base) : 205835.dasm - ABIStress.Program:.cctor()
         -46 (-5.11% of base) : 93667.dasm - array_tests:initialize()
         -46 (-5.09% of base) : 93930.dasm - array_tests:initialize()
         -46 (-5.09% of base) : 93136.dasm - array_tests:initialize()
         -46 (-0.90% of base) : 209444.dasm - Dynamic.BasicTest:UnknownWrapper(System.Object):this

Top method regressions (percentages):
           4 ( 9.52% of base) : 96423.dasm - _volatile:main(System.String[]):int
           4 ( 4.65% of base) : 96972.dasm - ILGEN_0x2e194c20:main():int
           2 ( 4.55% of base) : 248235.dasm - JitTest.Test:method_5_2(long):long
           4 ( 4.00% of base) : 90796.dasm - X:T(bool,System.Int32[])
           4 ( 3.51% of base) : 226138.dasm - testout1:Sub_Funclet_3():int
           4 ( 3.51% of base) : 231432.dasm - testout1:Sub_Funclet_3():int
           2 ( 3.23% of base) : 91052.dasm - foo:Main():int
          14 ( 2.51% of base) : 206081.dasm - testout1:Func_0_1_1_1_1_1_1_1_1_1_1_1_1():int
          14 ( 2.51% of base) : 183593.dasm - testout1:Func_0_1_1_1_1_1_1_1_1_1_1_1_1():int
           4 ( 2.50% of base) : 259273.dasm - GitHub_18884:ReproUx(long,long,ushort,ubyte)
           4 ( 2.11% of base) : 96449.dasm - test:main(System.String[]):int
           2 ( 2.08% of base) : 89705.dasm - GitHub_24159.Test:Main():int
           4 ( 2.02% of base) : 158158.dasm - testout1:Sub_Funclet_218():int
           4 ( 2.02% of base) : 163067.dasm - testout1:Sub_Funclet_218():int
           4 ( 2.02% of base) : 161190.dasm - testout1:Sub_Funclet_26():int
           4 ( 2.02% of base) : 111627.dasm - testout1:Sub_Funclet_26():int
           4 ( 2.02% of base) : 158053.dasm - testout1:Sub_Funclet_330():int
           4 ( 2.02% of base) : 162957.dasm - testout1:Sub_Funclet_330():int
           4 ( 2.02% of base) : 171720.dasm - testout1:Sub_Funclet_346():int
           4 ( 2.02% of base) : 153904.dasm - testout1:Sub_Funclet_346():int

Top method improvements (percentages):
         -14 (-23.33% of base) : 89255.dasm - Test_constructor:.ctor():this
         -14 (-22.58% of base) : 87364.dasm - Sandbox3.Foo`1[Byte][System.Byte]:Action(int)
         -14 (-21.88% of base) : 87363.dasm - Sandbox3.Foo`1[Byte][System.Byte]:Action(short)
         -14 (-21.88% of base) : 87362.dasm - Sandbox3.Foo`1[Byte][System.Byte]:Action(ubyte)
         -10 (-15.62% of base) : 83935.dasm - System.Threading.Tasks.Task`1[Byte][System.Byte]:.cctor()
         -14 (-14.29% of base) : 216929.dasm - TestLibrary.HostPolicyMock:Initialize(System.String,System.String)
         -10 (-12.20% of base) : 92071.dasm - foo:.cctor()
          -6 (-11.11% of base) : 91931.dasm - GitHub_26311.GenericClassOverInterface`1[Byte][System.Byte]:.cctor()
          -2 (-11.11% of base) : 243449.dasm - JitTest.Test:method_0_2(int):int
          -2 (-11.11% of base) : 249539.dasm - JitTest.Test:method_0_2(ushort):ushort
          -6 (-11.11% of base) : 86561.dasm - System.Collections.Generic.ArraySortHelper`1[Vector`1][System.Numerics.Vector`1[System.Single]]:.cctor()
          -6 (-11.11% of base) : 86611.dasm - System.Collections.Generic.ArraySortHelper`2[Byte,Nullable`1][System.Byte,System.Nullable`1[System.Int32]]:.cctor()
          -6 (-11.11% of base) : 4059.dasm - System.Runtime.Serialization.SerializationGuard:.cctor()
         -14 (-10.61% of base) : 28.dasm - FileDescriptors:.cctor()
          -6 (-10.34% of base) : 228936.dasm - NetClient.ArrayTests:.cctor()
          -6 (-10.00% of base) : 94626.dasm - _ldlen:initialize()
          -8 (-10.00% of base) : 94747.dasm - A:.cctor()
          -8 (-10.00% of base) : 94748.dasm - B:.cctor()
          -6 (-10.00% of base) : 89913.dasm - CuriouslyRecurringPatternThroughInterface.Program:Main(System.String[]):int
          -6 (-9.68% of base) : 95780.dasm - ILGEN_0x78389777:Method_0x440f1192(short,ubyte):int

8558 total methods with Code Size differences (693 improved, 7865 regressed), 19264 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 41223040 (overridden on cmd)
Total bytes of diff: 41213544 (overridden on cmd)
Total bytes of delta: -9496 (-0.02 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
           2 : 45771.dasm (0.21% of base)
           2 : 146170.dasm (3.03% of base)

Top file improvements (bytes):
        -934 : 149345.dasm (-3.19% of base)
        -640 : 87618.dasm (-4.96% of base)
        -480 : 88366.dasm (-3.11% of base)
        -246 : 157997.dasm (-6.58% of base)
        -226 : 146237.dasm (-6.74% of base)
        -170 : 214229.dasm (-6.83% of base)
        -158 : 108805.dasm (-2.66% of base)
        -150 : 148850.dasm (-4.23% of base)
        -118 : 145518.dasm (-6.88% of base)
        -118 : 148822.dasm (-6.88% of base)
        -104 : 87994.dasm (-2.39% of base)
         -86 : 92322.dasm (-4.11% of base)
         -78 : 207629.dasm (-6.64% of base)
         -78 : 223713.dasm (-6.00% of base)
         -78 : 18120.dasm (-8.74% of base)
         -58 : 120354.dasm (-7.84% of base)
         -54 : 220828.dasm (-4.92% of base)
         -50 : 119839.dasm (-2.04% of base)
         -46 : 18946.dasm (-8.42% of base)
         -42 : 106012.dasm (-3.01% of base)

648 total files with Code Size differences (646 improved, 2 regressed), 3362 unchanged.

Top method regressions (bytes):
           2 ( 0.21% of base) : 45771.dasm - System.Data.SqlTypes.SqlDateTime:.cctor()
           2 ( 3.03% of base) : 146170.dasm - System.Xml.Xsl.XmlQualifiedNameTest:.cctor()

Top method improvements (bytes):
        -934 (-3.19% of base) : 149345.dasm - System.Xml.Xsl.IlGen.XmlILMethods:.cctor()
        -640 (-4.96% of base) : 87618.dasm - <StartupCode$FSharp-Core>.$Query:.cctor()
        -480 (-3.11% of base) : 88366.dasm - <StartupCode$FSharp-Core>.$Linq:.cctor()
        -246 (-6.58% of base) : 157997.dasm - System.Runtime.Serialization.DictionaryGlobals:.cctor()
        -226 (-6.74% of base) : 146237.dasm - System.Xml.Xsl.XmlQueryTypeFactory:.cctor()
        -170 (-6.83% of base) : 214229.dasm - System.Runtime.Serialization.Formatters.Binary.Converter:.cctor()
        -158 (-2.66% of base) : 108805.dasm - System.Text.RegularExpressions.RegexCompiler:.cctor()
        -150 (-4.23% of base) : 148850.dasm - System.Xml.Xsl.Runtime.XsltMethods:.cctor()
        -118 (-6.88% of base) : 145518.dasm - System.Xml.Schema.XmlBaseConverter:.cctor()
        -118 (-6.88% of base) : 148822.dasm - System.Xml.Xsl.Runtime.XsltConvert:.cctor()
        -104 (-2.39% of base) : 87994.dasm - <StartupCode$FSharp-Core>.$QueryExtensions:.cctor()
         -86 (-4.11% of base) : 92322.dasm - <StartupCode$FSharp-Core>.$Sformat:.cctor()
         -78 (-8.74% of base) : 18120.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.DocumentationCommentXmlTokens:.cctor()
         -78 (-6.00% of base) : 223713.dasm - Microsoft.Internal.GenerationServices:.cctor()
         -78 (-6.64% of base) : 207629.dasm - System.Net.Mail.SmtpCommands:.cctor()
         -58 (-7.84% of base) : 120354.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.SyntaxFactory:.cctor()
         -54 (-4.92% of base) : 220828.dasm - System.Uri:.cctor()
         -50 (-2.04% of base) : 119839.dasm - Microsoft.CodeAnalysis.VisualBasic.Syntax.InternalSyntax.Scanner:.cctor()
         -46 (-8.42% of base) : 18946.dasm - Microsoft.CodeAnalysis.CSharp.Syntax.InternalSyntax.SyntaxFactory:.cctor()
         -42 (-3.01% of base) : 106012.dasm - System.Linq.Expressions.Utils:.cctor()

Top method regressions (percentages):
           2 ( 3.03% of base) : 146170.dasm - System.Xml.Xsl.XmlQualifiedNameTest:.cctor()
           2 ( 0.21% of base) : 45771.dasm - System.Data.SqlTypes.SqlDateTime:.cctor()

Top method improvements (percentages):
         -10 (-15.62% of base) : 72162.dasm - System.Threading.Tasks.Task`1[Byte][System.Byte]:.cctor()
         -10 (-13.51% of base) : 137206.dasm - MS.Internal.Xml.XPath.StringFunctions:.cctor()
         -10 (-13.51% of base) : 148848.dasm - System.Xml.Xsl.Runtime.XsltFunctions:.cctor()
          -8 (-13.33% of base) : 199990.dasm - Fcntl:.cctor()
         -10 (-12.50% of base) : 219350.dasm - System.Data.ProviderBase.DbConnectionFactory:.cctor()
         -10 (-12.20% of base) : 214650.dasm - System.Collections.Immutable.AllocFreeConcurrentStack`1[Byte][System.Byte]:.cctor()
         -10 (-12.20% of base) : 185942.dasm - System.ComponentModel.Composition.Registration.ImportBuilder:.cctor()
         -10 (-12.20% of base) : 36134.dasm - System.Configuration.AppSettingsReader:.cctor()
         -10 (-12.20% of base) : 220220.dasm - System.Data.Odbc.OdbcParameterCollection:.cctor()
         -10 (-12.20% of base) : 2538.dasm - System.Text.Json.Reflection.ReflectionExtensions:.cctor()
         -10 (-12.20% of base) : 3222.dasm - System.Text.Json.Serialization.Metadata.JsonTypeInfo:.cctor()
         -10 (-11.90% of base) : 190447.dasm - Microsoft.Extensions.FileProviders.Physical.PollingWildCardChangeToken:.cctor()
         -18 (-11.84% of base) : 145892.dasm - System.Xml.Schema.XsdValidator:.cctor()
          -8 (-11.76% of base) : 219858.dasm - System.Data.Odbc.OdbcConnection:.cctor()
         -18 (-11.54% of base) : 200169.dasm - System.IO.Pipes.PipeStream:.cctor()
          -8 (-11.43% of base) : 33157.dasm - System.Net.Http.Headers.CacheControlHeaderValue:.cctor()
          -8 (-11.43% of base) : 183227.dasm - System.Net.Sockets.SocketPal:.cctor()
         -14 (-11.29% of base) : 157660.dasm - System.Runtime.Serialization.CodeGenerator:get_SerializationModule():System.Reflection.Module
          -6 (-11.11% of base) : 155118.dasm - CultureInfoMapper:.cctor()
          -6 (-11.11% of base) : 108140.dasm - DynamicDelegateLightup:.cctor()

648 total methods with Code Size differences (646 improved, 2 regressed), 3362 unchanged.

```

</details>

--------------------------------------------------------------------------------

## libraries_tests.pmi.Linux.arm.checked.mch:

```

Summary of Code Size diffs:
(Lower is better)

Total bytes of base: 111200638 (overridden on cmd)
Total bytes of diff: 111104938 (overridden on cmd)
Total bytes of delta: -95700 (-0.09 % of base)
    diff is an improvement.
    relative diff is an improvement.
```
<details>

<summary>Detail diffs</summary>

```


Top file regressions (bytes):
          26 : 65968.dasm (1.68% of base)
          18 : 65980.dasm (1.64% of base)
           6 : 261158.dasm (2.42% of base)
           6 : 261161.dasm (2.42% of base)
           6 : 261165.dasm (2.42% of base)
           4 : 261162.dasm (1.60% of base)
           4 : 261168.dasm (1.60% of base)
           4 : 70582.dasm (4.44% of base)
           2 : 176569.dasm (0.22% of base)
           2 : 101722.dasm (0.93% of base)
           2 : 189786.dasm (0.42% of base)
           2 : 70643.dasm (11.11% of base)
           2 : 195750.dasm (0.54% of base)
           2 : 195758.dasm (0.54% of base)
           2 : 60786.dasm (3.23% of base)
           2 : 60939.dasm (2.86% of base)

Top file improvements (bytes):
       -1098 : 59151.dasm (-1.61% of base)
       -1082 : 59136.dasm (-1.55% of base)
        -562 : 60238.dasm (-2.00% of base)
        -488 : 66047.dasm (-2.15% of base)
        -398 : 59183.dasm (-2.95% of base)
        -394 : 59268.dasm (-1.94% of base)
        -394 : 59275.dasm (-1.94% of base)
        -394 : 59279.dasm (-1.93% of base)
        -362 : 66039.dasm (-1.86% of base)
        -322 : 59156.dasm (-2.31% of base)
        -322 : 59174.dasm (-2.37% of base)
        -298 : 59165.dasm (-2.50% of base)
        -282 : 59291.dasm (-1.64% of base)
        -274 : 333353.dasm (-1.80% of base)
        -250 : 68690.dasm (-1.83% of base)
        -246 : 18356.dasm (-6.53% of base)
        -246 : 96752.dasm (-6.53% of base)
        -242 : 189935.dasm (-5.80% of base)
        -242 : 119554.dasm (-6.59% of base)
        -230 : 59218.dasm (-2.04% of base)

7673 total files with Code Size differences (7657 improved, 16 regressed), 7419 unchanged.

Top method regressions (bytes):
          26 ( 1.68% of base) : 65968.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.formalParameter.cnstrctor009.cnstrctor009.Test:MainMethod(System.String[]):int
          18 ( 1.64% of base) : 65980.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.formalParameter.cnstrctor008.cnstrctor008.Test:MainMethod(System.String[]):int
           6 ( 2.42% of base) : 261158.dasm - System.Net.Tests.ServicePointManagerTest:CheckCertificateRevocationList_Roundtrips()
           6 ( 2.42% of base) : 261161.dasm - System.Net.Tests.ServicePointManagerTest:EnableDnsRoundRobin_Roundtrips()
           6 ( 2.42% of base) : 261165.dasm - System.Net.Tests.ServicePointManagerTest:ReusePort_Roundtrips()
           4 ( 4.44% of base) : 70582.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.dlgate006.dlgate006.nms.Foo:.cctor()
           4 ( 1.60% of base) : 261162.dasm - System.Net.Tests.ServicePointManagerTest:Expect100Continue_Roundtrips()
           4 ( 1.60% of base) : 261168.dasm - System.Net.Tests.ServicePointManagerTest:UseNagleAlgorithm_Roundtrips()
           2 (11.11% of base) : 70643.dasm - Dynamic.Tests.ExplicitlyImplementedInterfaceWithIndexer:Dynamic.Tests.InterfaceWithIndexer.get_Item(ubyte):long:this
           2 ( 2.86% of base) : 60939.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Oneclass2indexers.oneparamdifftypesconv011.oneparamdifftypesconv011.Target:get_Item(ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Oneclass2indexers.oneparamdifftypesconv011.oneparamdifftypesconv011.myStruct):System.String[]:this
           2 ( 3.23% of base) : 60786.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Twoclass2indexers.overload003.overload003.Base:get_Item(short):System.String[]:this
           2 ( 0.22% of base) : 176569.dasm - Microsoft.Build.Internal.XmlReaderExtension:GetXmlReader(System.String,System.IO.StreamReader,bool,byref):System.Xml.XmlReader
           2 ( 0.54% of base) : 195750.dasm - System.Reflection.Tests.TypeInfoFieldBaseClass:.cctor()
           2 ( 0.54% of base) : 195758.dasm - System.Reflection.Tests.TypeInfoMemberBaseClass:.cctor()
           2 ( 0.42% of base) : 189786.dasm - System.Security.Cryptography.X509Certificates.Tests.PfxFormatTests:.cctor()
           2 ( 0.93% of base) : 101722.dasm - System.Tests.ObjectTests:ReferenceEqualsTest()

Top method improvements (bytes):
       -1098 (-1.61% of base) : 59151.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.freach.freach001.freach001.Test:MainMethod():int
       -1082 (-1.55% of base) : 59136.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.freach.freach007.freach007.Test:MainMethod():int
        -562 (-2.00% of base) : 60238.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Methods.Oneclass2methods.literals01.literals01.A:MainMethod():int
        -488 (-2.15% of base) : 66047.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst001.cnst001.Test:MainMethod():int
        -398 (-2.95% of base) : 59183.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.cnst.readonly06.readonly06.Test:MainMethod():int
        -394 (-1.93% of base) : 59279.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.basic.enum004.enum004.Test:MainMethod():int
        -394 (-1.94% of base) : 59275.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.basic.enum004c.enum004c.Test:MainMethod():int
        -394 (-1.94% of base) : 59268.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.basic.enum004e.enum004e.Test:MainMethod():int
        -362 (-1.86% of base) : 66039.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.conversions.cnst002.cnst002.Test:MainMethod():int
        -322 (-2.37% of base) : 59174.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.cnst.readonly07.readonly07.Test:MainMethod():int
        -322 (-2.31% of base) : 59156.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.cnst.readonly09.readonly09.Test:MainMethod():int
        -298 (-2.50% of base) : 59165.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.cnst.readonly08.readonly08.Test:MainMethod():int
        -282 (-1.64% of base) : 59291.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Operators.basic.enum001.enum001.A:MainMethod():int
        -274 (-1.80% of base) : 333353.dasm - Microsoft.CSharp.RuntimeBinder.Tests.DefaultParameterTests:MarshalAsOptionalsCorrectDefault():this
        -250 (-1.83% of base) : 68690.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.operate.compound.basic.context01.context01.Test:MainMethod():int
        -246 (-6.53% of base) : 18356.dasm - SerializationTestTypes.Globals:.cctor()
        -246 (-6.53% of base) : 96752.dasm - SerializationTestTypes.Globals:.cctor()
        -242 (-6.59% of base) : 119554.dasm - RawData:.cctor()
        -242 (-5.80% of base) : 189935.dasm - System.Security.Cryptography.X509Certificates.Tests.TestData:.cctor()
        -230 (-2.04% of base) : 59218.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.statements.cnst.readonly01a.readonly01a.Test:MainMethod():int

Top method regressions (percentages):
           2 (11.11% of base) : 70643.dasm - Dynamic.Tests.ExplicitlyImplementedInterfaceWithIndexer:Dynamic.Tests.InterfaceWithIndexer.get_Item(ubyte):long:this
           4 ( 4.44% of base) : 70582.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.dlgateEvent.dlgate.dlgate006.dlgate006.nms.Foo:.cctor()
           2 ( 3.23% of base) : 60786.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Twoclass2indexers.overload003.overload003.Base:get_Item(short):System.String[]:this
           2 ( 2.86% of base) : 60939.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Oneclass2indexers.oneparamdifftypesconv011.oneparamdifftypesconv011.Target:get_Item(ManagedTests.DynamicCSharp.Conformance.dynamic.overloadResolution.Indexers.Oneclass2indexers.oneparamdifftypesconv011.oneparamdifftypesconv011.myStruct):System.String[]:this
           6 ( 2.42% of base) : 261158.dasm - System.Net.Tests.ServicePointManagerTest:CheckCertificateRevocationList_Roundtrips()
           6 ( 2.42% of base) : 261161.dasm - System.Net.Tests.ServicePointManagerTest:EnableDnsRoundRobin_Roundtrips()
           6 ( 2.42% of base) : 261165.dasm - System.Net.Tests.ServicePointManagerTest:ReusePort_Roundtrips()
          26 ( 1.68% of base) : 65968.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.formalParameter.cnstrctor009.cnstrctor009.Test:MainMethod(System.String[]):int
          18 ( 1.64% of base) : 65980.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.dynamicType.formalParameter.cnstrctor008.cnstrctor008.Test:MainMethod(System.String[]):int
           4 ( 1.60% of base) : 261162.dasm - System.Net.Tests.ServicePointManagerTest:Expect100Continue_Roundtrips()
           4 ( 1.60% of base) : 261168.dasm - System.Net.Tests.ServicePointManagerTest:UseNagleAlgorithm_Roundtrips()
           2 ( 0.93% of base) : 101722.dasm - System.Tests.ObjectTests:ReferenceEqualsTest()
           2 ( 0.54% of base) : 195750.dasm - System.Reflection.Tests.TypeInfoFieldBaseClass:.cctor()
           2 ( 0.54% of base) : 195758.dasm - System.Reflection.Tests.TypeInfoMemberBaseClass:.cctor()
           2 ( 0.42% of base) : 189786.dasm - System.Security.Cryptography.X509Certificates.Tests.PfxFormatTests:.cctor()
           2 ( 0.22% of base) : 176569.dasm - Microsoft.Build.Internal.XmlReaderExtension:GetXmlReader(System.String,System.IO.StreamReader,bool,byref):System.Xml.XmlReader

Top method improvements (percentages):
         -12 (-14.29% of base) : 329627.dasm - Lamar.Scanning.TypeRepository:ClearAll()
         -10 (-13.51% of base) : 68107.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.operate.regclass.regstrct012.regstrct012.Test:.cctor()
         -10 (-12.82% of base) : 68103.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.context.operate.regclass.regstrct013.regstrct013.Test:.cctor()
         -10 (-12.50% of base) : 154690.dasm - Microsoft.CodeAnalysis.VisualBasic.VisualBasicSyntaxTreeFactoryServiceFactory:.cctor()
         -10 (-12.20% of base) : 287014.dasm - Castle.DynamicProxy.Generators.CompositionInvocationTypeGenerator:.cctor()
         -10 (-12.20% of base) : 287033.dasm - Castle.DynamicProxy.Generators.InheritanceInvocationTypeGenerator:.cctor()
         -10 (-12.20% of base) : 64196.dasm - ManagedTests.DynamicCSharp.Conformance.dynamic.namedandoptional.decl.attributes.defaultParameter.default02c.default02c.Test:.cctor()
         -10 (-12.20% of base) : 47880.dasm - Microsoft.CodeAnalysis.Options.GlobalOptionService:.cctor()
         -10 (-12.20% of base) : 48051.dasm - Microsoft.CodeAnalysis.Options.OptionSet:.cctor()
         -10 (-12.20% of base) : 41458.dasm - Roslyn.Utilities.ReflectionUtilities:.cctor()
         -10 (-12.20% of base) : 114276.dasm - System.ComponentModel.Composition.CompositionServicesTests:.cctor()
         -10 (-12.20% of base) : 260403.dasm - System.Composition.UnitTests.ContractTests:.cctor()
         -10 (-12.20% of base) : 220295.dasm - System.Data.SqlClient.SqlParameterCollection:.cctor()
         -10 (-12.20% of base) : 171400.dasm - System.Data.SqlClient.SqlParameterCollection:.cctor()
         -10 (-12.20% of base) : 230329.dasm - System.IO.Tests.Directory_CreateDirectory:.cctor()
         -10 (-12.20% of base) : 89787.dasm - System.Net.Http.Functional.Tests.HttpProtocolTests:.cctor()
         -10 (-12.20% of base) : 80023.dasm - System.Text.Json.Serialization.Tests.InvalidTypeTests:.cctor()
         -10 (-12.20% of base) : 1712.dasm - UnknownTypeFactory:.cctor()
         -10 (-11.90% of base) : 110184.dasm - CultureInfoSubclassOverridesGetFormat:.cctor()
         -10 (-11.90% of base) : 110187.dasm - CultureInfoSubclassOverridesNumberFormat:.cctor()

7673 total methods with Code Size differences (7657 improved, 16 regressed), 7419 unchanged.

```

</details>

--------------------------------------------------------------------------------

