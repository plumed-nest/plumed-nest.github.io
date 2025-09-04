**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.3qGubu.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.3qGubu.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.3qGubu.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.3qGubu.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.Xdqwkh/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10.0.so ../codes/StructureFactor_descriptor.test.cpp

[pkrvm7jw40e0xgp:11308] *** Process received signal ***
[pkrvm7jw40e0xgp:11308] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11308] Signal code:  (-6)
[pkrvm7jw40e0xgp:11308] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9764645330]
[pkrvm7jw40e0xgp:11308] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f976469eb2c]
[pkrvm7jw40e0xgp:11308] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f976464527e]
[pkrvm7jw40e0xgp:11308] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97646288ff]
[pkrvm7jw40e0xgp:11308] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9764aa5ff5]
[pkrvm7jw40e0xgp:11308] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9764abb0da]
[pkrvm7jw40e0xgp:11308] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9764aa5a55]
[pkrvm7jw40e0xgp:11308] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9764aa5a6f]
[pkrvm7jw40e0xgp:11308] [ 8] plumed(+0x146dd)[0x564403cf36dd]
[pkrvm7jw40e0xgp:11308] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f976462a1ca]
[pkrvm7jw40e0xgp:11308] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f976462a28b]
[pkrvm7jw40e0xgp:11308] [11] plumed(+0x15365)[0x564403cf4365]
[pkrvm7jw40e0xgp:11308] *** End of error message ***
</pre>
{% endraw %}
