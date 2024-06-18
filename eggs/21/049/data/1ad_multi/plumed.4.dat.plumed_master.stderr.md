**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  1ad_multi/plumed.4.dat   
Download: [zipped raw stdout](plumed.4.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.hQ7q9K.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.hQ7q9K.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.hQ7q9K.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.hQ7q9K.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.hQ7q9K.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.hQ7q9K.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.hQ7q9K.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.hQ7q9K.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.hQ7q9K.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.hQ7q9K.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.hQ7q9K.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.hQ7q9K.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.hQ7q9K.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.hQ7q9K.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.hQ7q9K.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.hQ7q9K.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.10.0-dev.so ../PathCV.cpp

[fv-az1272-851:07690] *** Process received signal ***
[fv-az1272-851:07690] Signal: Aborted (6)
[fv-az1272-851:07690] Signal code:  (-6)
[fv-az1272-851:07690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7cf8242520]
[fv-az1272-851:07690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7cf82969fc]
[fv-az1272-851:07690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7cf8242476]
[fv-az1272-851:07690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7cf82287f3]
[fv-az1272-851:07690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7cf86a2b9e]
[fv-az1272-851:07690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7cf86ae20c]
[fv-az1272-851:07690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7cf86ae277]
[fv-az1272-851:07690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7cf86ae52b]
[fv-az1272-851:07690] [ 8] plumed_master(+0x14274)[0x55e098dfc274]
[fv-az1272-851:07690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7cf8229d90]
[fv-az1272-851:07690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7cf8229e40]
[fv-az1272-851:07690] [11] plumed_master(+0x14ed5)[0x55e098dfced5]
[fv-az1272-851:07690] *** End of error message ***
</pre>
{% endraw %}
