**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  2ad_inter/plumed.0.dat   
Download: [zipped raw stdout](plumed.0.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.0.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.RAesoi.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.RAesoi.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.RAesoi.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.RAesoi.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.RAesoi.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.RAesoi.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.RAesoi.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.RAesoi.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.RAesoi.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.RAesoi.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.RAesoi.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.RAesoi.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.RAesoi.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.RAesoi.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.RAesoi.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[fv-az1277-646:65228] *** Process received signal ***
[fv-az1277-646:65228] Signal: Aborted (6)
[fv-az1277-646:65228] Signal code:  (-6)
[fv-az1277-646:65228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8bb845330]
[fv-az1277-646:65228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8bb89eb2c]
[fv-az1277-646:65228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8bb84527e]
[fv-az1277-646:65228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8bb8288ff]
[fv-az1277-646:65228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8bbca5ff5]
[fv-az1277-646:65228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8bbcbb0da]
[fv-az1277-646:65228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8bbca5a55]
[fv-az1277-646:65228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8bbca5a6f]
[fv-az1277-646:65228] [ 8] plumed(+0x146dd)[0x556280ee36dd]
[fv-az1277-646:65228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8bb82a1ca]
[fv-az1277-646:65228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8bb82a28b]
[fv-az1277-646:65228] [11] plumed(+0x15365)[0x556280ee4365]
[fv-az1277-646:65228] *** End of error message ***
</pre>
{% endraw %}
