**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  SF-prof/plumed_structure_factor_OO.dat   
Download: [zipped raw stdout](plumed_structure_factor_OO.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_sphericallyAveraged.3KtihZ.cpp: In constructor ‘PLMD::colvar::StructureFactor_sphericallyAveraged::StructureFactor_sphericallyAveraged(const PLMD::ActionOptions&)’:
../codes/StructureFactor_sphericallyAveraged.3KtihZ.cpp:184:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
184 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.3KtihZ.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.3KtihZ.cpp:190:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
190 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.nz8SID/../codes/StructureFactor_sphericallyAveraged.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_sphericallyAveraged.2.10.0.so ../codes/StructureFactor_sphericallyAveraged.cpp

[pkrvm7jw40e0xgp:11488] *** Process received signal ***
[pkrvm7jw40e0xgp:11488] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11488] Signal code:  (-6)
[pkrvm7jw40e0xgp:11488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc015a45330]
[pkrvm7jw40e0xgp:11488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc015a9eb2c]
[pkrvm7jw40e0xgp:11488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc015a4527e]
[pkrvm7jw40e0xgp:11488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc015a288ff]
[pkrvm7jw40e0xgp:11488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc015ea5ff5]
[pkrvm7jw40e0xgp:11488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc015ebb0da]
[pkrvm7jw40e0xgp:11488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc015ea5a55]
[pkrvm7jw40e0xgp:11488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc015ea5a6f]
[pkrvm7jw40e0xgp:11488] [ 8] plumed(+0x146dd)[0x5596199dc6dd]
[pkrvm7jw40e0xgp:11488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc015a2a1ca]
[pkrvm7jw40e0xgp:11488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc015a2a28b]
[pkrvm7jw40e0xgp:11488] [11] plumed(+0x15365)[0x5596199dd365]
[pkrvm7jw40e0xgp:11488] *** End of error message ***
</pre>
{% endraw %}
