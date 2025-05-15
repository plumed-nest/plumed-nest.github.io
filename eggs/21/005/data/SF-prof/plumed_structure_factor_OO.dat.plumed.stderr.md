**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  SF-prof/plumed_structure_factor_OO.dat   
Download: [zipped raw stdout](plumed_structure_factor_OO.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_sphericallyAveraged.L0FxtQ.cpp: In constructor ‘PLMD::colvar::StructureFactor_sphericallyAveraged::StructureFactor_sphericallyAveraged(const PLMD::ActionOptions&)’:
../codes/StructureFactor_sphericallyAveraged.L0FxtQ.cpp:184:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
184 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.L0FxtQ.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.L0FxtQ.cpp:190:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
190 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.N2QEY3/../codes/StructureFactor_sphericallyAveraged.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_sphericallyAveraged.2.10b.so ../codes/StructureFactor_sphericallyAveraged.cpp

[pkrvmberfyhpb9w:11749] *** Process received signal ***
[pkrvmberfyhpb9w:11749] Signal: Aborted (6)
[pkrvmberfyhpb9w:11749] Signal code:  (-6)
[pkrvmberfyhpb9w:11749] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2318c45330]
[pkrvmberfyhpb9w:11749] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2318c9eb2c]
[pkrvmberfyhpb9w:11749] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2318c4527e]
[pkrvmberfyhpb9w:11749] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2318c288ff]
[pkrvmberfyhpb9w:11749] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23190a5ff5]
[pkrvmberfyhpb9w:11749] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23190bb0da]
[pkrvmberfyhpb9w:11749] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23190a5a55]
[pkrvmberfyhpb9w:11749] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23190a5a6f]
[pkrvmberfyhpb9w:11749] [ 8] plumed(+0x146dd)[0x55ebf1da36dd]
[pkrvmberfyhpb9w:11749] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2318c2a1ca]
[pkrvmberfyhpb9w:11749] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2318c2a28b]
[pkrvmberfyhpb9w:11749] [11] plumed(+0x15365)[0x55ebf1da4365]
[pkrvmberfyhpb9w:11749] *** End of error message ***
</pre>
{% endraw %}
