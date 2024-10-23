**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  SF-prof/plumed_structure_factor_OO.dat   
Download: [zipped raw stdout](plumed_structure_factor_OO.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_sphericallyAveraged.kBUeDr.cpp: In constructor ‘PLMD::colvar::StructureFactor_sphericallyAveraged::StructureFactor_sphericallyAveraged(const PLMD::ActionOptions&)’:
../codes/StructureFactor_sphericallyAveraged.kBUeDr.cpp:184:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
184 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.kBUeDr.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_sphericallyAveraged.kBUeDr.cpp:190:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
190 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_sphericallyAveraged.kBUeDr.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.vYCgsJ/../codes/StructureFactor_sphericallyAveraged.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_sphericallyAveraged.2.10b.so ../codes/StructureFactor_sphericallyAveraged.cpp

[fv-az975-395:06580] *** Process received signal ***
[fv-az975-395:06580] Signal: Aborted (6)
[fv-az975-395:06580] Signal code:  (-6)
[fv-az975-395:06580] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbb42242520]
[fv-az975-395:06580] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbb422969fc]
[fv-az975-395:06580] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbb42242476]
[fv-az975-395:06580] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbb422287f3]
[fv-az975-395:06580] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbb426a2b9e]
[fv-az975-395:06580] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbb426ae20c]
[fv-az975-395:06580] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbb426ae277]
[fv-az975-395:06580] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbb426ae52b]
[fv-az975-395:06580] [ 8] plumed(+0x14254)[0x5623ee48c254]
[fv-az975-395:06580] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbb42229d90]
[fv-az975-395:06580] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbb42229e40]
[fv-az975-395:06580] [11] plumed(+0x14eb5)[0x5623ee48ceb5]
[fv-az975-395:06580] *** End of error message ***
</pre>
{% endraw %}
