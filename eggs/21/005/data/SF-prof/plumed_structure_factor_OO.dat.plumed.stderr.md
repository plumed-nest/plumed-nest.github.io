**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  SF-prof/plumed_structure_factor_OO.dat   
Download: [zipped raw stdout](plumed_structure_factor_OO.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_sphericallyAveraged.Fuh62t.cpp: In constructor ‘PLMD::colvar::StructureFactor_sphericallyAveraged::StructureFactor_sphericallyAveraged(const PLMD::ActionOptions&)’:
../codes/StructureFactor_sphericallyAveraged.Fuh62t.cpp:184:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
184 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.Fuh62t.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.Fuh62t.cpp:190:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
190 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.Berv6u/../codes/StructureFactor_sphericallyAveraged.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_sphericallyAveraged.2.10.1.so ../codes/StructureFactor_sphericallyAveraged.cpp

[runnervmgx7h7:09131] *** Process received signal ***
[runnervmgx7h7:09131] Signal: Aborted (6)
[runnervmgx7h7:09131] Signal code:  (-6)
[runnervmgx7h7:09131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68ff645330]
[runnervmgx7h7:09131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68ff69ec0c]
[runnervmgx7h7:09131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68ff64527e]
[runnervmgx7h7:09131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68ff6288ff]
[runnervmgx7h7:09131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68ffaa5ff5]
[runnervmgx7h7:09131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68ffabb0da]
[runnervmgx7h7:09131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68ffaa5a55]
[runnervmgx7h7:09131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68ffaa5a6f]
[runnervmgx7h7:09131] [ 8] plumed(+0x146dd)[0x561edfe976dd]
[runnervmgx7h7:09131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68ff62a1ca]
[runnervmgx7h7:09131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68ff62a28b]
[runnervmgx7h7:09131] [11] plumed(+0x15365)[0x561edfe98365]
[runnervmgx7h7:09131] *** End of error message ***
</pre>
{% endraw %}
