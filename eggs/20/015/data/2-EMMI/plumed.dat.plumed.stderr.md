**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
Stderr for source:  2-EMMI/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
EMMIVox.VMa3lA.cpp: In static member function ‘static void PLMD::isdb::EMMIVOX::registerKeywords(PLMD::Keywords&)’:
EMMIVox.VMa3lA.cpp:242:3: error: ‘componentsAreNotOptional’ was not declared in this scope
242 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
EMMIVox.VMa3lA.cpp: In constructor ‘PLMD::isdb::EMMIVOX::EMMIVOX(const PLMD::ActionOptions&)’:
EMMIVox.VMa3lA.cpp:328:52: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
328 |   if(temp>0.0) kbt_=plumed.getAtoms().getKBoltzmann()*temp;
|                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from EMMIVox.VMa3lA.cpp:24:
/home/runner/opt/include/plumed/core/PlumedMain.h:102:12: note: declared here
102 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
EMMIVox.VMa3lA.cpp:329:37: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
329 |   else kbt_=plumed.getAtoms().getKbT();
|             ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:104:12: note: declared here
104 |     double getKbT() const ;
|            ^~~~~~
EMMIVox.VMa3lA.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.VMa3lA.cpp:536:17: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<double>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
536 |   for(int i=0; i<ovmd_.size(); ++i) {
|                ~^~~~~~~~~~~~~
EMMIVox.VMa3lA.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::string)’:
EMMIVox.VMa3lA.cpp:670:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
670 |       for(unsigned i=0; i<nexp; ++i) {
|                         ~^~~~~
EMMIVox.VMa3lA.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::string)’:
EMMIVox.VMa3lA.cpp:801:22: warning: comparison of integer expressions of different signedness: ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
801 |     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./EMMIVox.2.10.0.so EMMIVox.cpp

[runnervmw9dnm:12957] *** Process received signal ***
[runnervmw9dnm:12957] Signal: Aborted (6)
[runnervmw9dnm:12957] Signal code:  (-6)
[runnervmw9dnm:12957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff6b5c45330]
[runnervmw9dnm:12957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff6b5c9eb2c]
[runnervmw9dnm:12957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff6b5c4527e]
[runnervmw9dnm:12957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6b5c288ff]
[runnervmw9dnm:12957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6b60a5ff5]
[runnervmw9dnm:12957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6b60bb0da]
[runnervmw9dnm:12957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6b60a5a55]
[runnervmw9dnm:12957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6b60a5a6f]
[runnervmw9dnm:12957] [ 8] plumed(+0x146dd)[0x563d1e94e6dd]
[runnervmw9dnm:12957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff6b5c2a1ca]
[runnervmw9dnm:12957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff6b5c2a28b]
[runnervmw9dnm:12957] [11] plumed(+0x15365)[0x563d1e94f365]
[runnervmw9dnm:12957] *** End of error message ***
</pre>
{% endraw %}
