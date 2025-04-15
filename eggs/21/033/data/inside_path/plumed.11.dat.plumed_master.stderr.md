**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  inside_path/plumed.11.dat   
Download: [zipped raw stdout](plumed.11.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.11.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.zkg7lZ.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.zkg7lZ.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.zkg7lZ.cpp:199:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
199 |   keys.addOutputComponent("s","default","the position on the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.zkg7lZ.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.zkg7lZ.cpp:200:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
200 |   keys.addOutputComponent("z","default","the distance from the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.zkg7lZ.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.zkg7lZ.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.zkg7lZ.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.zkg7lZ.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.zkg7lZ.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.zkg7lZ.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.zkg7lZ.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.zkg7lZ.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.zkg7lZ.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.zkg7lZ.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.zkg7lZ.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.zkg7lZ.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.11.0-dev.so ../PathCV.cpp

[fv-az1921-959:65011] *** Process received signal ***
[fv-az1921-959:65011] Signal: Aborted (6)
[fv-az1921-959:65011] Signal code:  (-6)
[fv-az1921-959:65011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e9cc45330]
[fv-az1921-959:65011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e9cc9eb2c]
[fv-az1921-959:65011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e9cc4527e]
[fv-az1921-959:65011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e9cc288ff]
[fv-az1921-959:65011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e9d0a5ff5]
[fv-az1921-959:65011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e9d0bb0da]
[fv-az1921-959:65011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e9d0a5a55]
[fv-az1921-959:65011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e9d0a5a6f]
[fv-az1921-959:65011] [ 8] plumed_master(+0x146dd)[0x55ebf52ef6dd]
[fv-az1921-959:65011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e9cc2a1ca]
[fv-az1921-959:65011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e9cc2a28b]
[fv-az1921-959:65011] [11] plumed_master(+0x15365)[0x55ebf52f0365]
[fv-az1921-959:65011] *** End of error message ***
</pre>
{% endraw %}
