**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  outside_path/plumed.4.dat   
Download: [zipped raw stdout](plumed.4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.io4CNY.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.io4CNY.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.io4CNY.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.io4CNY.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.io4CNY.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.io4CNY.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.io4CNY.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.io4CNY.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.io4CNY.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.io4CNY.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.io4CNY.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.io4CNY.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.io4CNY.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.io4CNY.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.io4CNY.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[pkrvmpptgkbjq6m:11377] *** Process received signal ***
[pkrvmpptgkbjq6m:11377] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11377] Signal code:  (-6)
[pkrvmpptgkbjq6m:11377] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66d3e45330]
[pkrvmpptgkbjq6m:11377] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66d3e9eb2c]
[pkrvmpptgkbjq6m:11377] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66d3e4527e]
[pkrvmpptgkbjq6m:11377] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66d3e288ff]
[pkrvmpptgkbjq6m:11377] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66d42a5ff5]
[pkrvmpptgkbjq6m:11377] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66d42bb0da]
[pkrvmpptgkbjq6m:11377] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66d42a5a55]
[pkrvmpptgkbjq6m:11377] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66d42a5a6f]
[pkrvmpptgkbjq6m:11377] [ 8] plumed(+0x146dd)[0x5585f33ea6dd]
[pkrvmpptgkbjq6m:11377] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66d3e2a1ca]
[pkrvmpptgkbjq6m:11377] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66d3e2a28b]
[pkrvmpptgkbjq6m:11377] [11] plumed(+0x15365)[0x5585f33eb365]
[pkrvmpptgkbjq6m:11377] *** End of error message ***
</pre>
{% endraw %}
