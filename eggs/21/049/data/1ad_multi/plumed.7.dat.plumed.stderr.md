**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  1ad_multi/plumed.7.dat   
Download: [zipped raw stdout](plumed.7.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.7.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.QeIsCD.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.QeIsCD.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.QeIsCD.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.QeIsCD.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.QeIsCD.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.QeIsCD.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.QeIsCD.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.QeIsCD.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.QeIsCD.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.QeIsCD.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.QeIsCD.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.QeIsCD.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.QeIsCD.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.QeIsCD.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.QeIsCD.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.QeIsCD.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[fv-az1429-284:06212] *** Process received signal ***
[fv-az1429-284:06212] Signal: Aborted (6)
[fv-az1429-284:06212] Signal code:  (-6)
[fv-az1429-284:06212] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdd9e242520]
[fv-az1429-284:06212] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdd9e2969fc]
[fv-az1429-284:06212] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdd9e242476]
[fv-az1429-284:06212] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdd9e2287f3]
[fv-az1429-284:06212] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdd9e6a2b9e]
[fv-az1429-284:06212] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdd9e6ae20c]
[fv-az1429-284:06212] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdd9e6ae277]
[fv-az1429-284:06212] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdd9e6ae52b]
[fv-az1429-284:06212] [ 8] plumed(+0x14254)[0x56358341b254]
[fv-az1429-284:06212] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdd9e229d90]
[fv-az1429-284:06212] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdd9e229e40]
[fv-az1429-284:06212] [11] plumed(+0x14eb5)[0x56358341beb5]
[fv-az1429-284:06212] *** End of error message ***
</pre>
{% endraw %}