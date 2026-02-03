**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  NaCl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.cPcbLv.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.cPcbLv.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.cPcbLv.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.cPcbLv.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.4XqApv/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10.0.so ../codes/StructureFactor_descriptor.test.cpp

[runnervmkj6or:08605] *** Process received signal ***
[runnervmkj6or:08605] Signal: Aborted (6)
[runnervmkj6or:08605] Signal code:  (-6)
[runnervmkj6or:08605] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fddd2245330]
[runnervmkj6or:08605] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fddd229eb2c]
[runnervmkj6or:08605] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fddd224527e]
[runnervmkj6or:08605] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fddd22288ff]
[runnervmkj6or:08605] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fddd26a5ff5]
[runnervmkj6or:08605] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fddd26bb0da]
[runnervmkj6or:08605] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fddd26a5a55]
[runnervmkj6or:08605] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fddd26a5a6f]
[runnervmkj6or:08605] [ 8] plumed(+0x146dd)[0x55c780e196dd]
[runnervmkj6or:08605] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fddd222a1ca]
[runnervmkj6or:08605] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fddd222a28b]
[runnervmkj6or:08605] [11] plumed(+0x15365)[0x55c780e1a365]
[runnervmkj6or:08605] *** End of error message ***
</pre>
{% endraw %}
