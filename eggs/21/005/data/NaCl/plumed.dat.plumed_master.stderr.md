**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  NaCl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.2oLRBa.cpp: In static member function ‘static void PLMD::colvar::StructureFactor_descriptor_test::registerKeywords(PLMD::Keywords&)’:
../codes/StructureFactor_descriptor.test.2oLRBa.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("Sk","default","the instantaneous structure factor averaged over a k-shell"); //FIXME not true!
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from ../codes/StructureFactor_descriptor.test.2oLRBa.cpp:6:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../codes/StructureFactor_descriptor.test.2oLRBa.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.2oLRBa.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.2oLRBa.cpp:8:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.2oLRBa.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.5fw8i2/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.11.0-dev.so ../codes/StructureFactor_descriptor.test.cpp

[runnervmgx7h7:09077] *** Process received signal ***
[runnervmgx7h7:09077] Signal: Aborted (6)
[runnervmgx7h7:09077] Signal code:  (-6)
[runnervmgx7h7:09077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f736de45330]
[runnervmgx7h7:09077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f736de9ec0c]
[runnervmgx7h7:09077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f736de4527e]
[runnervmgx7h7:09077] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f736de288ff]
[runnervmgx7h7:09077] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f736e2a5ff5]
[runnervmgx7h7:09077] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f736e2bb0da]
[runnervmgx7h7:09077] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f736e2a5a55]
[runnervmgx7h7:09077] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f736e2a5a6f]
[runnervmgx7h7:09077] [ 8] plumed_master(+0x146dd)[0x55e4d0b406dd]
[runnervmgx7h7:09077] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f736de2a1ca]
[runnervmgx7h7:09077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f736de2a28b]
[runnervmgx7h7:09077] [11] plumed_master(+0x15365)[0x55e4d0b41365]
[runnervmgx7h7:09077] *** End of error message ***
</pre>
{% endraw %}
