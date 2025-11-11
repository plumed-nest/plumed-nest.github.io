**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
Stderr for source:  2-EMMI/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
EMMIVox.zfz9iW.cpp: In static member function ‘static void PLMD::isdb::EMMIVOX::registerKeywords(PLMD::Keywords&)’:
EMMIVox.zfz9iW.cpp:242:3: error: ‘componentsAreNotOptional’ was not declared in this scope
242 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:243:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
243 |   keys.addOutputComponent("scoreb","default","Bayesian score");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from EMMIVox.zfz9iW.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:244:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
244 |   keys.addOutputComponent("acc",   "NOISETYPE","MC acceptance for uncertainty");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:245:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
245 |   keys.addOutputComponent("accB",  "default", "Bfactor MC acceptance");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:246:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
246 |   keys.addOutputComponent("scale", "default","scale factor");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:247:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
247 |   keys.addOutputComponent("offset","default","offset");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:248:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
248 |   keys.addOutputComponent("accscale", "default","MC acceptance for scale");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp: In constructor ‘PLMD::isdb::EMMIVOX::EMMIVOX(const PLMD::ActionOptions&)’:
EMMIVox.zfz9iW.cpp:328:52: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
328 |   if(temp>0.0) kbt_=plumed.getAtoms().getKBoltzmann()*temp;
|                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from EMMIVox.zfz9iW.cpp:24:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:102:12: note: declared here
102 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp:329:37: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
329 |   else kbt_=plumed.getAtoms().getKbT();
|             ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:104:12: note: declared here
104 |     double getKbT() const ;
|            ^~~~~~
EMMIVox.zfz9iW.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.zfz9iW.cpp:536:17: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<double>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
536 |   for(int i=0; i<ovmd_.size(); ++i) {
|                ~^~~~~~~~~~~~~
EMMIVox.zfz9iW.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::string)’:
EMMIVox.zfz9iW.cpp:670:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
670 |       for(unsigned i=0; i<nexp; ++i) {
|                         ~^~~~~
EMMIVox.zfz9iW.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::string)’:
EMMIVox.zfz9iW.cpp:801:22: warning: comparison of integer expressions of different signedness: ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
801 |     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./EMMIVox.2.11.0-dev.so EMMIVox.cpp

[runnervmw9dnm:12991] *** Process received signal ***
[runnervmw9dnm:12991] Signal: Aborted (6)
[runnervmw9dnm:12991] Signal code:  (-6)
[runnervmw9dnm:12991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbe8645330]
[runnervmw9dnm:12991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbe869eb2c]
[runnervmw9dnm:12991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbe864527e]
[runnervmw9dnm:12991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbe86288ff]
[runnervmw9dnm:12991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbe8aa5ff5]
[runnervmw9dnm:12991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbe8abb0da]
[runnervmw9dnm:12991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbe8aa5a55]
[runnervmw9dnm:12991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbe8aa5a6f]
[runnervmw9dnm:12991] [ 8] plumed_master(+0x146dd)[0x558b4022a6dd]
[runnervmw9dnm:12991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbe862a1ca]
[runnervmw9dnm:12991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbe862a28b]
[runnervmw9dnm:12991] [11] plumed_master(+0x15365)[0x558b4022b365]
[runnervmw9dnm:12991] *** End of error message ***
</pre>
{% endraw %}
