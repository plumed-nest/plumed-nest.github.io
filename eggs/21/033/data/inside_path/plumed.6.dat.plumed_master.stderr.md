**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  inside_path/plumed.6.dat   
Download: [zipped raw stdout](plumed.6.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.6.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.Ihj0gy.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.Ihj0gy.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.Ihj0gy.cpp:199:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
199 |   keys.addOutputComponent("s","default","the position on the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.Ihj0gy.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.Ihj0gy.cpp:200:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
200 |   keys.addOutputComponent("z","default","the distance from the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.Ihj0gy.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.Ihj0gy.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.Ihj0gy.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Ihj0gy.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.Ihj0gy.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Ihj0gy.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.Ihj0gy.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.Ihj0gy.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.Ihj0gy.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.Ihj0gy.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Ihj0gy.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.Ihj0gy.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.Ihj0gy.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.Ihj0gy.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.Ihj0gy.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.11.0-dev.so ../PathCV.cpp

[fv-az802-461:07479] *** Process received signal ***
[fv-az802-461:07479] Signal: Aborted (6)
[fv-az802-461:07479] Signal code:  (-6)
[fv-az802-461:07479] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7338e42520]
[fv-az802-461:07479] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7338e969fc]
[fv-az802-461:07479] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7338e42476]
[fv-az802-461:07479] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7338e287f3]
[fv-az802-461:07479] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f73392a2b9e]
[fv-az802-461:07479] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f73392ae20c]
[fv-az802-461:07479] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f73392ae277]
[fv-az802-461:07479] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f73392ae52b]
[fv-az802-461:07479] [ 8] plumed_master(+0x14254)[0x55a499a65254]
[fv-az802-461:07479] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7338e29d90]
[fv-az802-461:07479] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7338e29e40]
[fv-az802-461:07479] [11] plumed_master(+0x14eb5)[0x55a499a65eb5]
[fv-az802-461:07479] *** End of error message ***
</pre>
{% endraw %}