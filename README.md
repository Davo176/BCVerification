This repository contains 14 submodules, therefore you should clone it using:

```*git clone --recurse-submodules git@github.com:Davo176/BCVerification.git*```

This repository is split into two sections

/bcSource contains the fork's of Bouncy Castles CSharp and Java repositories

/refSources contains round 3 or more recent versions of reference implementations

in /bcSource/bc-csharp, my additional testing is located in _/bcSource/bc-csharp/crypto/test/src/pqc/crypto/test/additionalTesting_

and additional test cases are located in: _/bcSource/bc-csharp/crypto/test/data/pqc_ 

Note that some additional test cases may be missing due to size constraints. The repository would not compile over a certain size limit. These files can be found in the respective reference repositories

in /bcSource/bc-java, my additional testing is located in _/bcSource/bc-java/core/src/test/java/org/bouncycastle/pqc/crypto/test/additionalTesting/tests_

and additional test cases are located in: _/bcSource/bc-java/core/src/test/java/org/bouncycastle/pqc/crypto/test/additionalTesting/resources_

These test cases were ran using NUnit / JUnit respectively, you should be able to run these from your IDE.

In each of the reference implementations, there is a readme that contains instructions on how to build the test cases. 

Interoperability testing is completed by copying and pasting files between reference and bouncy castle implementations
