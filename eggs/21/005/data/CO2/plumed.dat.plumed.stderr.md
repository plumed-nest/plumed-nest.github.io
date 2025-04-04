**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.SIOzwd.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.SIOzwd.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.SIOzwd.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.SIOzwd.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.2nrZLB/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10b.so ../codes/StructureFactor_descriptor.test.cpp

[fv-az805-507:11858] *** Process received signal ***
[fv-az805-507:11858] Signal: Aborted (6)
[fv-az805-507:11858] Signal code:  (-6)
[fv-az805-507:11858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcd7445330]
[fv-az805-507:11858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcd749eb2c]
[fv-az805-507:11858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcd744527e]
[fv-az805-507:11858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcd74288ff]
[fv-az805-507:11858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcd78a5ff5]
[fv-az805-507:11858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcd78bb0da]
[fv-az805-507:11858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcd78a5a55]
[fv-az805-507:11858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcd78a5a6f]
[fv-az805-507:11858] [ 8] plumed(+0x146dd)[0x55f25b9cb6dd]
[fv-az805-507:11858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcd742a1ca]
[fv-az805-507:11858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcd742a28b]
[fv-az805-507:11858] [11] plumed(+0x15365)[0x55f25b9cc365]
[fv-az805-507:11858] *** End of error message ***
</pre>
{% endraw %}
