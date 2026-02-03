**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  SF-prof/plumed_structure_factor_OO.dat   
Download: [zipped raw stdout](plumed_structure_factor_OO.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp: In static member function ‘static void PLMD::colvar::StructureFactor_sphericallyAveraged::registerKeywords(PLMD::Keywords&)’:
../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("Sk","default","the instantaneous structure factor averaged over a k-shell");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from ../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp:6:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp: In constructor ‘PLMD::colvar::StructureFactor_sphericallyAveraged::StructureFactor_sphericallyAveraged(const PLMD::ActionOptions&)’:
../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp:184:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
184 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp:8:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.Avv3V6.cpp:190:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
190 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.aDMI5L/../codes/StructureFactor_sphericallyAveraged.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/StructureFactor_sphericallyAveraged.2.11.0-dev.so ../codes/StructureFactor_sphericallyAveraged.cpp

[runnervmkj6or:08730] *** Process received signal ***
[runnervmkj6or:08730] Signal: Aborted (6)
[runnervmkj6or:08730] Signal code:  (-6)
[runnervmkj6or:08730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c5fe45330]
[runnervmkj6or:08730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c5fe9eb2c]
[runnervmkj6or:08730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c5fe4527e]
[runnervmkj6or:08730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c5fe288ff]
[runnervmkj6or:08730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c602a5ff5]
[runnervmkj6or:08730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c602bb0da]
[runnervmkj6or:08730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c602a5a55]
[runnervmkj6or:08730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c602a5a6f]
[runnervmkj6or:08730] [ 8] plumed_master(+0x146dd)[0x55fdf3a496dd]
[runnervmkj6or:08730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c5fe2a1ca]
[runnervmkj6or:08730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c5fe2a28b]
[runnervmkj6or:08730] [11] plumed_master(+0x15365)[0x55fdf3a4a365]
[runnervmkj6or:08730] *** End of error message ***
</pre>
{% endraw %}
