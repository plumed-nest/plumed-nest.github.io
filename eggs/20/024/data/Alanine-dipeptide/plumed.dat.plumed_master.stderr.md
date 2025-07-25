**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed_master/core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionWithValue.h:25,
from ../GAMBES.iR4p5Z.cpp:23:
/home/runner/opt/include/plumed_master/core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ../GAMBES.iR4p5Z.cpp:30:
/home/runner/opt/include/plumed_master/tools/Matrix.h:100: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
100 | #pragma acc enter data copyin(this[0:1],sz,data[0:sz])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:103: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
103 | #pragma acc exit data delete(data[0:sz],sz,this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:117: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
117 | #pragma acc enter data copyin(this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:123: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
123 | #pragma acc exit data delete( this[0:1])
|
../GAMBES.iR4p5Z.cpp: In static member function ‘static void PLMD::bias::GAMBES::registerKeywords(PLMD::Keywords&)’:
../GAMBES.iR4p5Z.cpp:98:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
98 |   keys.addOutputComponent("_factors","default","two or more weighing factors for bias"
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
99 |                           "these quantities will named with  the gaussian number followed by "
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
100 |                           "the character string _factors. These quantities tell the user the value of the factor ");
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../GAMBES.iR4p5Z.cpp:101:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
101 |   keys.addOutputComponent("_averages","AVERAGES","two or more the averages");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../GAMBES.iR4p5Z.cpp: In member function ‘virtual void PLMD::bias::GAMBES::prepare()’:
../GAMBES.iR4p5Z.cpp:224:37: warning: ‘void PLMD::PlumedMain::DeprecatedAtoms::setCollectEnergy(bool) const’ is deprecated [-Wdeprecated-declarations]
224 |   plumed.getAtoms().setCollectEnergy(true);
|   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
In file included from ../GAMBES.iR4p5Z.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:110:10: note: declared here
110 |     void setCollectEnergy(bool b) const;
|          ^~~~~~~~~~~~~~~~
../GAMBES.iR4p5Z.cpp: In member function ‘virtual void PLMD::bias::GAMBES::calculate()’:
../GAMBES.iR4p5Z.cpp:230:36: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
230 |   beta = 1/plumed.getAtoms().getKbT();
|            ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:104:12: note: declared here
104 |     double getKbT() const ;
|            ^~~~~~
../GAMBES.iR4p5Z.cpp:231:63: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
231 |   if(temp>0.0){ beta = 1/(temp*plumed.getAtoms().getKBoltzmann()) ; }
|                                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:102:12: note: declared here
102 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
../GAMBES.iR4p5Z.cpp:250:57: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
250 |   if(iter==0){energy_offset= plumed.getAtoms().getEnergy();}
|                              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:112:12: note: declared here
112 |     double getEnergy() const ;
|            ^~~~~~~~~
../GAMBES.iR4p5Z.cpp:251:44: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
251 |   double energy=plumed.getAtoms().getEnergy() - energy_offset;
|                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:112:12: note: declared here
112 |     double getEnergy() const ;
|            ^~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmpptgkbjq6m:11114] *** Process received signal ***
[pkrvmpptgkbjq6m:11114] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11114] Signal code:  (-6)
[pkrvmpptgkbjq6m:11114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f85cec45330]
[pkrvmpptgkbjq6m:11114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f85cec9eb2c]
[pkrvmpptgkbjq6m:11114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f85cec4527e]
[pkrvmpptgkbjq6m:11114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85cec288ff]
[pkrvmpptgkbjq6m:11114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85cf0a5ff5]
[pkrvmpptgkbjq6m:11114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85cf0bb0da]
[pkrvmpptgkbjq6m:11114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85cf0a5a55]
[pkrvmpptgkbjq6m:11114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85cf0a5a6f]
[pkrvmpptgkbjq6m:11114] [ 8] plumed_master(+0x146dd)[0x55fd5fc406dd]
[pkrvmpptgkbjq6m:11114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f85cec2a1ca]
[pkrvmpptgkbjq6m:11114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f85cec2a28b]
[pkrvmpptgkbjq6m:11114] [11] plumed_master(+0x15365)[0x55fd5fc41365]
[pkrvmpptgkbjq6m:11114] *** End of error message ***
</pre>
{% endraw %}
