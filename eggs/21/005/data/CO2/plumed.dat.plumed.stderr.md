**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.W1JzWX.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.W1JzWX.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.W1JzWX.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.W1JzWX.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.RlTbcU/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10.0.so ../codes/StructureFactor_descriptor.test.cpp

[runnervmw9dnm:09761] *** Process received signal ***
[runnervmw9dnm:09761] Signal: Aborted (6)
[runnervmw9dnm:09761] Signal code:  (-6)
[runnervmw9dnm:09761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8857645330]
[runnervmw9dnm:09761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f885769eb2c]
[runnervmw9dnm:09761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f885764527e]
[runnervmw9dnm:09761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88576288ff]
[runnervmw9dnm:09761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8857aa5ff5]
[runnervmw9dnm:09761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8857abb0da]
[runnervmw9dnm:09761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8857aa5a55]
[runnervmw9dnm:09761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8857aa5a6f]
[runnervmw9dnm:09761] [ 8] plumed(+0x146dd)[0x55d9387246dd]
[runnervmw9dnm:09761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f885762a1ca]
[runnervmw9dnm:09761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f885762a28b]
[runnervmw9dnm:09761] [11] plumed(+0x15365)[0x55d938725365]
[runnervmw9dnm:09761] *** End of error message ***
</pre>
{% endraw %}
