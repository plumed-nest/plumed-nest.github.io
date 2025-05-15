**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  NaCl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.PrKYSo.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.PrKYSo.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.PrKYSo.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.PrKYSo.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.3QJUG8/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10b.so ../codes/StructureFactor_descriptor.test.cpp

[pkrvmberfyhpb9w:11660] *** Process received signal ***
[pkrvmberfyhpb9w:11660] Signal: Aborted (6)
[pkrvmberfyhpb9w:11660] Signal code:  (-6)
[pkrvmberfyhpb9w:11660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6873445330]
[pkrvmberfyhpb9w:11660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f687349eb2c]
[pkrvmberfyhpb9w:11660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f687344527e]
[pkrvmberfyhpb9w:11660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68734288ff]
[pkrvmberfyhpb9w:11660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68738a5ff5]
[pkrvmberfyhpb9w:11660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68738bb0da]
[pkrvmberfyhpb9w:11660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68738a5a55]
[pkrvmberfyhpb9w:11660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68738a5a6f]
[pkrvmberfyhpb9w:11660] [ 8] plumed(+0x146dd)[0x561dea96f6dd]
[pkrvmberfyhpb9w:11660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f687342a1ca]
[pkrvmberfyhpb9w:11660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f687342a28b]
[pkrvmberfyhpb9w:11660] [11] plumed(+0x15365)[0x561dea970365]
[pkrvmberfyhpb9w:11660] *** End of error message ***
</pre>
{% endraw %}
