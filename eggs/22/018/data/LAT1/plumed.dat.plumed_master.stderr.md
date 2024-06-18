**Project ID:** [plumID:22.018]({{ '/' | absolute_url }}eggs/22/018/)  
Stderr for source:  LAT1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
EMMIVox.U7qOOd.cpp: In static member function ‘static void PLMD::isdb::EMMIVOX::registerKeywords(PLMD::Keywords&)’:
EMMIVox.U7qOOd.cpp:242:3: error: ‘componentsAreNotOptional’ was not declared in this scope
242 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
EMMIVox.U7qOOd.cpp: In constructor ‘PLMD::isdb::EMMIVOX::EMMIVOX(const PLMD::ActionOptions&)’:
EMMIVox.U7qOOd.cpp:328:52: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
328 |   if(temp>0.0) kbt_=plumed.getAtoms().getKBoltzmann()*temp;
|                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from EMMIVox.U7qOOd.cpp:24:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:103:12: note: declared here
103 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
EMMIVox.U7qOOd.cpp:329:37: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
329 |   else kbt_=plumed.getAtoms().getKbT();
|             ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from EMMIVox.U7qOOd.cpp:24:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:105:12: note: declared here
105 |     double getKbT() const ;
|            ^~~~~~
EMMIVox.U7qOOd.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.U7qOOd.cpp:536:17: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<double>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
536 |   for(int i=0; i<ovmd_.size(); ++i) {
|                ~^~~~~~~~~~~~~
EMMIVox.U7qOOd.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::string)’:
EMMIVox.U7qOOd.cpp:670:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
670 |       for(unsigned i=0; i<nexp; ++i) {
|                         ~^~~~~
EMMIVox.U7qOOd.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::string)’:
EMMIVox.U7qOOd.cpp:801:22: warning: comparison of integer expressions of different signedness: ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
801 |     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./EMMIVox.2.10.0-dev.so EMMIVox.cpp

[fv-az1215-453:05423] *** Process received signal ***
[fv-az1215-453:05423] Signal: Aborted (6)
[fv-az1215-453:05423] Signal code:  (-6)
[fv-az1215-453:05423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ffbeee42520]
[fv-az1215-453:05423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ffbeee969fc]
[fv-az1215-453:05423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ffbeee42476]
[fv-az1215-453:05423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ffbeee287f3]
[fv-az1215-453:05423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ffbef2a2b9e]
[fv-az1215-453:05423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ffbef2ae20c]
[fv-az1215-453:05423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ffbef2ae277]
[fv-az1215-453:05423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ffbef2ae52b]
[fv-az1215-453:05423] [ 8] plumed_master(+0x14274)[0x557715202274]
[fv-az1215-453:05423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ffbeee29d90]
[fv-az1215-453:05423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ffbeee29e40]
[fv-az1215-453:05423] [11] plumed_master(+0x14ed5)[0x557715202ed5]
[fv-az1215-453:05423] *** End of error message ***
</pre>
{% endraw %}
