**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  outside_path/plumed.10.dat   
Download: [zipped raw stdout](plumed.10.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.10.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.iBX6MM.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.iBX6MM.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.iBX6MM.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.iBX6MM.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.iBX6MM.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.iBX6MM.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.iBX6MM.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.iBX6MM.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.iBX6MM.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.iBX6MM.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.iBX6MM.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.iBX6MM.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.iBX6MM.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.iBX6MM.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.iBX6MM.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[pkrvmpptgkbjq6m:11020] *** Process received signal ***
[pkrvmpptgkbjq6m:11020] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11020] Signal code:  (-6)
[pkrvmpptgkbjq6m:11020] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f393b845330]
[pkrvmpptgkbjq6m:11020] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f393b89eb2c]
[pkrvmpptgkbjq6m:11020] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f393b84527e]
[pkrvmpptgkbjq6m:11020] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f393b8288ff]
[pkrvmpptgkbjq6m:11020] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f393bca5ff5]
[pkrvmpptgkbjq6m:11020] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f393bcbb0da]
[pkrvmpptgkbjq6m:11020] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f393bca5a55]
[pkrvmpptgkbjq6m:11020] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f393bca5a6f]
[pkrvmpptgkbjq6m:11020] [ 8] plumed(+0x146dd)[0x55c8ea8556dd]
[pkrvmpptgkbjq6m:11020] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f393b82a1ca]
[pkrvmpptgkbjq6m:11020] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f393b82a28b]
[pkrvmpptgkbjq6m:11020] [11] plumed(+0x15365)[0x55c8ea856365]
[pkrvmpptgkbjq6m:11020] *** End of error message ***
</pre>
{% endraw %}
