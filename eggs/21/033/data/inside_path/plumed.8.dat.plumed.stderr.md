**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  inside_path/plumed.8.dat   
Download: [zipped raw stdout](plumed.8.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.8.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.fcAA7n.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.fcAA7n.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.fcAA7n.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.fcAA7n.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.fcAA7n.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.fcAA7n.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.fcAA7n.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.fcAA7n.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.fcAA7n.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.fcAA7n.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.fcAA7n.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.fcAA7n.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.fcAA7n.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.fcAA7n.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.fcAA7n.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.fcAA7n.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[fv-az802-461:07590] *** Process received signal ***
[fv-az802-461:07590] Signal: Aborted (6)
[fv-az802-461:07590] Signal code:  (-6)
[fv-az802-461:07590] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f962d642520]
[fv-az802-461:07590] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f962d6969fc]
[fv-az802-461:07590] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f962d642476]
[fv-az802-461:07590] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f962d6287f3]
[fv-az802-461:07590] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f962daa2b9e]
[fv-az802-461:07590] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f962daae20c]
[fv-az802-461:07590] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f962daae277]
[fv-az802-461:07590] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f962daae52b]
[fv-az802-461:07590] [ 8] plumed(+0x14254)[0x55d4605f5254]
[fv-az802-461:07590] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f962d629d90]
[fv-az802-461:07590] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f962d629e40]
[fv-az802-461:07590] [11] plumed(+0x14eb5)[0x55d4605f5eb5]
[fv-az802-461:07590] *** End of error message ***
</pre>
{% endraw %}