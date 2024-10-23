**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.n9SCPP.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.n9SCPP.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.n9SCPP.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.n9SCPP.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.n9SCPP.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:107:9: note: declared here
107 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.GeRmlf/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10b.so ../codes/StructureFactor_descriptor.test.cpp

[fv-az975-395:06371] *** Process received signal ***
[fv-az975-395:06371] Signal: Aborted (6)
[fv-az975-395:06371] Signal code:  (-6)
[fv-az975-395:06371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f14f7242520]
[fv-az975-395:06371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f14f72969fc]
[fv-az975-395:06371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f14f7242476]
[fv-az975-395:06371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f14f72287f3]
[fv-az975-395:06371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f14f76a2b9e]
[fv-az975-395:06371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f14f76ae20c]
[fv-az975-395:06371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f14f76ae277]
[fv-az975-395:06371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f14f76ae52b]
[fv-az975-395:06371] [ 8] plumed(+0x14254)[0x55a51117a254]
[fv-az975-395:06371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f14f7229d90]
[fv-az975-395:06371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f14f7229e40]
[fv-az975-395:06371] [11] plumed(+0x14eb5)[0x55a51117aeb5]
[fv-az975-395:06371] *** End of error message ***
</pre>
{% endraw %}
