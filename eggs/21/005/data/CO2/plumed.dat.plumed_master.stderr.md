**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.r62fnE.cpp: In static member function ‘static void PLMD::colvar::StructureFactor_descriptor_test::registerKeywords(PLMD::Keywords&)’:
../codes/StructureFactor_descriptor.test.r62fnE.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("Sk","default","the instantaneous structure factor averaged over a k-shell"); //FIXME not true!
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from ../codes/StructureFactor_descriptor.test.r62fnE.cpp:6:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../codes/StructureFactor_descriptor.test.r62fnE.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.r62fnE.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.r62fnE.cpp:8:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.r62fnE.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.rixkvb/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.11.0-dev.so ../codes/StructureFactor_descriptor.test.cpp

[fv-az1983-395:65140] *** Process received signal ***
[fv-az1983-395:65140] Signal: Aborted (6)
[fv-az1983-395:65140] Signal code:  (-6)
[fv-az1983-395:65140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5257845330]
[fv-az1983-395:65140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f525789eb2c]
[fv-az1983-395:65140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f525784527e]
[fv-az1983-395:65140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52578288ff]
[fv-az1983-395:65140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5257ca5ff5]
[fv-az1983-395:65140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5257cbb0da]
[fv-az1983-395:65140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5257ca5a55]
[fv-az1983-395:65140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5257ca5a6f]
[fv-az1983-395:65140] [ 8] plumed_master(+0x146dd)[0x55e7b7bb46dd]
[fv-az1983-395:65140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f525782a1ca]
[fv-az1983-395:65140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f525782a28b]
[fv-az1983-395:65140] [11] plumed_master(+0x15365)[0x55e7b7bb5365]
[fv-az1983-395:65140] *** End of error message ***
</pre>
{% endraw %}
