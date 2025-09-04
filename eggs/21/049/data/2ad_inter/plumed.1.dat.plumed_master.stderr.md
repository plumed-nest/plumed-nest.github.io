**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  2ad_inter/plumed.1.dat   
Download: [zipped raw stdout](plumed.1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.nySBnl.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
../PathCV.nySBnl.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.nySBnl.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.nySBnl.cpp:199:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
199 |   keys.addOutputComponent("s","default","the position on the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/Action.h:27:
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.nySBnl.cpp:200:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
200 |   keys.addOutputComponent("z","default","the distance from the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.nySBnl.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.nySBnl.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.nySBnl.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.nySBnl.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.nySBnl.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.nySBnl.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.nySBnl.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.nySBnl.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.nySBnl.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.nySBnl.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.nySBnl.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.nySBnl.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.11.0-dev.so ../PathCV.cpp

[pkrvm7jw40e0xgp:10354] *** Process received signal ***
[pkrvm7jw40e0xgp:10354] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10354] Signal code:  (-6)
[pkrvm7jw40e0xgp:10354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f751f645330]
[pkrvm7jw40e0xgp:10354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f751f69eb2c]
[pkrvm7jw40e0xgp:10354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f751f64527e]
[pkrvm7jw40e0xgp:10354] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f751f6288ff]
[pkrvm7jw40e0xgp:10354] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f751faa5ff5]
[pkrvm7jw40e0xgp:10354] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f751fabb0da]
[pkrvm7jw40e0xgp:10354] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f751faa5a55]
[pkrvm7jw40e0xgp:10354] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f751faa5a6f]
[pkrvm7jw40e0xgp:10354] [ 8] plumed_master(+0x146dd)[0x55ae125896dd]
[pkrvm7jw40e0xgp:10354] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f751f62a1ca]
[pkrvm7jw40e0xgp:10354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f751f62a28b]
[pkrvm7jw40e0xgp:10354] [11] plumed_master(+0x15365)[0x55ae1258a365]
[pkrvm7jw40e0xgp:10354] *** End of error message ***
</pre>
{% endraw %}
