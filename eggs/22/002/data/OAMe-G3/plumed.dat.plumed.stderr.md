**Project ID:** [plumID:22.002]({{ '/' | absolute_url }}eggs/22/002/)  
Stderr for source:  OAMe-G3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
GAMBES_log_static_few.1UWqmO.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::prepare()’:
GAMBES_log_static_few.1UWqmO.cpp:232:37: warning: ‘void PLMD::PlumedMain::DeprecatedAtoms::setCollectEnergy(bool) const’ is deprecated [-Wdeprecated-declarations]
232 |   plumed.getAtoms().setCollectEnergy(true);
|   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
In file included from GAMBES_log_static_few.1UWqmO.cpp:22:
/home/runner/opt/include/plumed/core/PlumedMain.h:110:10: note: declared here
110 |     void setCollectEnergy(bool b) const;
|          ^~~~~~~~~~~~~~~~
GAMBES_log_static_few.1UWqmO.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::calculate()’:
GAMBES_log_static_few.1UWqmO.cpp:238:36: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
238 |   beta = 1/plumed.getAtoms().getKbT();
|            ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:104:12: note: declared here
104 |     double getKbT() const ;
|            ^~~~~~
GAMBES_log_static_few.1UWqmO.cpp:239:63: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
239 |   if(temp>0.0){ beta = 1/(temp*plumed.getAtoms().getKBoltzmann()) ; }
|                                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:102:12: note: declared here
102 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
GAMBES_log_static_few.1UWqmO.cpp:258:57: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
258 |   if(iter==0){energy_offset= plumed.getAtoms().getEnergy();}
|                              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:112:12: note: declared here
112 |     double getEnergy() const ;
|            ^~~~~~~~~
GAMBES_log_static_few.1UWqmO.cpp:259:44: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
259 |   double energy=plumed.getAtoms().getEnergy() - energy_offset;
|                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:112:12: note: declared here
112 |     double getEnergy() const ;
|            ^~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[pkrvmpptgkbjq6m:08614] *** Process received signal ***
[pkrvmpptgkbjq6m:08614] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08614] Signal code:  (-6)
[pkrvmpptgkbjq6m:08614] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3597245330]
[pkrvmpptgkbjq6m:08614] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f359729eb2c]
[pkrvmpptgkbjq6m:08614] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f359724527e]
[pkrvmpptgkbjq6m:08614] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35972288ff]
[pkrvmpptgkbjq6m:08614] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35976a5ff5]
[pkrvmpptgkbjq6m:08614] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35976bb0da]
[pkrvmpptgkbjq6m:08614] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35976a5a55]
[pkrvmpptgkbjq6m:08614] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35976a5a6f]
[pkrvmpptgkbjq6m:08614] [ 8] plumed(+0x146dd)[0x55e877fb06dd]
[pkrvmpptgkbjq6m:08614] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f359722a1ca]
[pkrvmpptgkbjq6m:08614] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f359722a28b]
[pkrvmpptgkbjq6m:08614] [11] plumed(+0x15365)[0x55e877fb1365]
[pkrvmpptgkbjq6m:08614] *** End of error message ***
</pre>
{% endraw %}
