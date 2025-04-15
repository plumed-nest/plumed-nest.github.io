**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  1ad_multi/plumed.0.dat   
Download: [zipped raw stdout](plumed.0.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.0.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.Km1Jl5.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.Km1Jl5.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.Km1Jl5.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.Km1Jl5.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Km1Jl5.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.Km1Jl5.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Km1Jl5.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.Km1Jl5.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.Km1Jl5.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.Km1Jl5.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.Km1Jl5.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Km1Jl5.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.Km1Jl5.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/function/../core/Action.h:30,
from /home/runner/opt/include/plumed/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed/function/Function.h:25,
from ../PathCV.Km1Jl5.cpp:22:
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.Km1Jl5.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../PathCV.2.10b.so ../PathCV.cpp

[fv-az1277-646:64507] *** Process received signal ***
[fv-az1277-646:64507] Signal: Aborted (6)
[fv-az1277-646:64507] Signal code:  (-6)
[fv-az1277-646:64507] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb9f645330]
[fv-az1277-646:64507] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb9f69eb2c]
[fv-az1277-646:64507] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb9f64527e]
[fv-az1277-646:64507] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb9f6288ff]
[fv-az1277-646:64507] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb9faa5ff5]
[fv-az1277-646:64507] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb9fabb0da]
[fv-az1277-646:64507] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb9faa5a55]
[fv-az1277-646:64507] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb9faa5a6f]
[fv-az1277-646:64507] [ 8] plumed(+0x146dd)[0x563e286b66dd]
[fv-az1277-646:64507] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb9f62a1ca]
[fv-az1277-646:64507] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb9f62a28b]
[fv-az1277-646:64507] [11] plumed(+0x15365)[0x563e286b7365]
[fv-az1277-646:64507] *** End of error message ***
</pre>
{% endraw %}
