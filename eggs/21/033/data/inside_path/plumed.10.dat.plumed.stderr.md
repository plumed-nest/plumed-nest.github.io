**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  inside_path/plumed.10.dat   
Download: [zipped raw stdout](plumed.10.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.10.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.13ptWP.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.13ptWP.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.13ptWP.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.13ptWP.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.13ptWP.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.13ptWP.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.13ptWP.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.13ptWP.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.13ptWP.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.13ptWP.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.13ptWP.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.13ptWP.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.13ptWP.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.13ptWP.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.13ptWP.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[fv-az1921-959:64883] *** Process received signal ***
[fv-az1921-959:64883] Signal: Aborted (6)
[fv-az1921-959:64883] Signal code:  (-6)
[fv-az1921-959:64883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7febcc045330]
[fv-az1921-959:64883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7febcc09eb2c]
[fv-az1921-959:64883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7febcc04527e]
[fv-az1921-959:64883] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7febcc0288ff]
[fv-az1921-959:64883] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7febcc4a5ff5]
[fv-az1921-959:64883] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7febcc4bb0da]
[fv-az1921-959:64883] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7febcc4a5a55]
[fv-az1921-959:64883] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7febcc4a5a6f]
[fv-az1921-959:64883] [ 8] plumed(+0x146dd)[0x55b3814566dd]
[fv-az1921-959:64883] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7febcc02a1ca]
[fv-az1921-959:64883] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7febcc02a28b]
[fv-az1921-959:64883] [11] plumed(+0x15365)[0x55b381457365]
[fv-az1921-959:64883] *** End of error message ***
</pre>
{% endraw %}
