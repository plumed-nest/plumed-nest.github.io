**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  CO2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../codes/StructureFactor_descriptor.test.3iHwP9.cpp: In constructor ‘PLMD::colvar::StructureFactor_descriptor_test::StructureFactor_descriptor_test(const PLMD::ActionOptions&)’:
../codes/StructureFactor_descriptor.test.3iHwP9.cpp:188:41: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
188 |     NumAtom_=plumed.getAtoms().getNatoms();
|              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../codes/StructureFactor_descriptor.test.3iHwP9.cpp:8:
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
../codes/StructureFactor_descriptor.test.3iHwP9.cpp:194:108: warning: ‘int PLMD::PlumedMain::DeprecatedAtoms::getNatoms() const’ is deprecated [-Wdeprecated-declarations]
194 |   log.printf("  over a total of N_tot=%d, considering a number of atoms N=%d\n",plumed.getAtoms().getNatoms(),NumAtom_);
|                                                                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:106:9: note: declared here
106 |     int getNatoms() const ;
|         ^~~~~~~~~
Assembler messages:
Fatal error: can't create plumed_mklib.R5JjFq/../codes/StructureFactor_descriptor.test.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/StructureFactor_descriptor.test.2.10b.so ../codes/StructureFactor_descriptor.test.cpp

[fv-az1277-646:67289] *** Process received signal ***
[fv-az1277-646:67289] Signal: Aborted (6)
[fv-az1277-646:67289] Signal code:  (-6)
[fv-az1277-646:67289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdb6045330]
[fv-az1277-646:67289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdb609eb2c]
[fv-az1277-646:67289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdb604527e]
[fv-az1277-646:67289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdb60288ff]
[fv-az1277-646:67289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdb64a5ff5]
[fv-az1277-646:67289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdb64bb0da]
[fv-az1277-646:67289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdb64a5a55]
[fv-az1277-646:67289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdb64a5a6f]
[fv-az1277-646:67289] [ 8] plumed(+0x146dd)[0x56129bed46dd]
[fv-az1277-646:67289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdb602a1ca]
[fv-az1277-646:67289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdb602a28b]
[fv-az1277-646:67289] [11] plumed(+0x15365)[0x56129bed5365]
[fv-az1277-646:67289] *** End of error message ***
</pre>
{% endraw %}
