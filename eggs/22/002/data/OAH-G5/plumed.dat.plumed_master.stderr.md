**Project ID:** [plumID:22.002]({{ '/' | absolute_url }}eggs/22/002/)  
Stderr for source:  OAH-G5/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
GAMBES_log_static_few.I4ZFQB.cpp: In static member function ‘static void PLMD::bias::GAMBESL::registerKeywords(PLMD::Keywords&)’:
GAMBES_log_static_few.I4ZFQB.cpp:100:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
100 |   keys.addOutputComponent("_factors","default","two or more weighing factors for bias"
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
101 |                           "these quantities will named with  the gaussian number followed by "
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
102 |                           "the character string _factors. These quantities tell the user the value of the factor ");
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27,
from /home/runner/opt/include/plumed_master/core/ActionWithValue.h:25,
from GAMBES_log_static_few.I4ZFQB.cpp:23:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
GAMBES_log_static_few.I4ZFQB.cpp:103:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
103 |   keys.addOutputComponent("_averages","AVERAGES","two or more the averages");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27,
from /home/runner/opt/include/plumed_master/core/ActionWithValue.h:25,
from GAMBES_log_static_few.I4ZFQB.cpp:23:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
GAMBES_log_static_few.I4ZFQB.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::prepare()’:
GAMBES_log_static_few.I4ZFQB.cpp:232:37: warning: ‘void PLMD::PlumedMain::DeprecatedAtoms::setCollectEnergy(bool) const’ is deprecated [-Wdeprecated-declarations]
232 |   plumed.getAtoms().setCollectEnergy(true);
|   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
In file included from GAMBES_log_static_few.I4ZFQB.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:111:10: note: declared here
111 |     void setCollectEnergy(bool b) const;
|          ^~~~~~~~~~~~~~~~
GAMBES_log_static_few.I4ZFQB.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::calculate()’:
GAMBES_log_static_few.I4ZFQB.cpp:238:36: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
238 |   beta = 1/plumed.getAtoms().getKbT();
|            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from GAMBES_log_static_few.I4ZFQB.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:105:12: note: declared here
105 |     double getKbT() const ;
|            ^~~~~~
GAMBES_log_static_few.I4ZFQB.cpp:239:63: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
239 |   if(temp>0.0){ beta = 1/(temp*plumed.getAtoms().getKBoltzmann()) ; }
|                                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from GAMBES_log_static_few.I4ZFQB.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:103:12: note: declared here
103 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
GAMBES_log_static_few.I4ZFQB.cpp:258:57: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
258 |   if(iter==0){energy_offset= plumed.getAtoms().getEnergy();}
|                              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from GAMBES_log_static_few.I4ZFQB.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:113:12: note: declared here
113 |     double getEnergy() const ;
|            ^~~~~~~~~
GAMBES_log_static_few.I4ZFQB.cpp:259:44: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
259 |   double energy=plumed.getAtoms().getEnergy() - energy_offset;
|                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from GAMBES_log_static_few.I4ZFQB.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:113:12: note: declared here
113 |     double getEnergy() const ;
|            ^~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:168) void PLMD::Keywords::use(const string&)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az585-767:06021] *** Process received signal ***
[fv-az585-767:06021] Signal: Aborted (6)
[fv-az585-767:06021] Signal code:  (-6)
[fv-az585-767:06021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2860042520]
[fv-az585-767:06021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f28600969fc]
[fv-az585-767:06021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2860042476]
[fv-az585-767:06021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f28600287f3]
[fv-az585-767:06021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f28604a2b9e]
[fv-az585-767:06021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f28604ae20c]
[fv-az585-767:06021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f28604ae277]
[fv-az585-767:06021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f28604ae52b]
[fv-az585-767:06021] [ 8] plumed_master(+0x14254)[0x561cd8e2f254]
[fv-az585-767:06021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2860029d90]
[fv-az585-767:06021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2860029e40]
[fv-az585-767:06021] [11] plumed_master(+0x14eb5)[0x561cd8e2feb5]
[fv-az585-767:06021] *** End of error message ***
</pre>
{% endraw %}