**Project ID:** [plumID:22.018]({{ '/' | absolute_url }}eggs/22/018/)  
Stderr for source:  LAT1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
EMMIVox.jZx82R.cpp: In static member function ‘static void PLMD::isdb::EMMIVOX::registerKeywords(PLMD::Keywords&)’:
EMMIVox.jZx82R.cpp:242:3: error: ‘componentsAreNotOptional’ was not declared in this scope
242 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
EMMIVox.jZx82R.cpp: In constructor ‘PLMD::isdb::EMMIVOX::EMMIVOX(const PLMD::ActionOptions&)’:
EMMIVox.jZx82R.cpp:328:52: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
328 |   if(temp>0.0) kbt_=plumed.getAtoms().getKBoltzmann()*temp;
|                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from EMMIVox.jZx82R.cpp:24:
/home/runner/opt/include/plumed/core/PlumedMain.h:102:12: note: declared here
102 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
EMMIVox.jZx82R.cpp:329:37: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
329 |   else kbt_=plumed.getAtoms().getKbT();
|             ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:104:12: note: declared here
104 |     double getKbT() const ;
|            ^~~~~~
EMMIVox.jZx82R.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.jZx82R.cpp:536:17: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<double>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
536 |   for(int i=0; i<ovmd_.size(); ++i) {
|                ~^~~~~~~~~~~~~
EMMIVox.jZx82R.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::string)’:
EMMIVox.jZx82R.cpp:670:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
670 |       for(unsigned i=0; i<nexp; ++i) {
|                         ~^~~~~
EMMIVox.jZx82R.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::string)’:
EMMIVox.jZx82R.cpp:801:22: warning: comparison of integer expressions of different signedness: ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
801 |     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./EMMIVox.2.10b.so EMMIVox.cpp

[pkrvmbietmlfzoi:66026] *** Process received signal ***
[pkrvmbietmlfzoi:66026] Signal: Aborted (6)
[pkrvmbietmlfzoi:66026] Signal code:  (-6)
[pkrvmbietmlfzoi:66026] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2826c45330]
[pkrvmbietmlfzoi:66026] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2826c9eb2c]
[pkrvmbietmlfzoi:66026] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2826c4527e]
[pkrvmbietmlfzoi:66026] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2826c288ff]
[pkrvmbietmlfzoi:66026] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28270a5ff5]
[pkrvmbietmlfzoi:66026] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28270bb0da]
[pkrvmbietmlfzoi:66026] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28270a5a55]
[pkrvmbietmlfzoi:66026] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28270a5a6f]
[pkrvmbietmlfzoi:66026] [ 8] plumed(+0x146dd)[0x55c3b60696dd]
[pkrvmbietmlfzoi:66026] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2826c2a1ca]
[pkrvmbietmlfzoi:66026] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2826c2a28b]
[pkrvmbietmlfzoi:66026] [11] plumed(+0x15365)[0x55c3b606a365]
[pkrvmbietmlfzoi:66026] *** End of error message ***
</pre>
{% endraw %}
