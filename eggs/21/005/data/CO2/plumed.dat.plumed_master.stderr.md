**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.wBKpbO.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.wBKpbO.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.wBKpbO.cpp:8:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.wBKpbO.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.wBKpbO.cpp:8:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.DRFwUA/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10.0-dev.so ../codes/StructureFactor_descriptor.test.cpp

[fv-az840-554:08032] *** Process received signal ***
[fv-az840-554:08032] Signal: Aborted (6)
[fv-az840-554:08032] Signal code:  (-6)
[fv-az840-554:08032] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f461fc42520]
[fv-az840-554:08032] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f461fc969fc]
[fv-az840-554:08032] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f461fc42476]
[fv-az840-554:08032] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f461fc287f3]
[fv-az840-554:08032] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f46200a2b9e]
[fv-az840-554:08032] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f46200ae20c]
[fv-az840-554:08032] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f46200ae277]
[fv-az840-554:08032] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f46200ae52b]
[fv-az840-554:08032] [ 8] plumed_master(+0x14274)[0x558422ca0274]
[fv-az840-554:08032] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f461fc29d90]
[fv-az840-554:08032] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f461fc29e40]
[fv-az840-554:08032] [11] plumed_master(+0x14ed5)[0x558422ca0ed5]
[fv-az840-554:08032] *** End of error message ***
</pre>
{% endraw %}
