**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
Stderr for source:  outside_path/plumed.1.dat   
Download: [zipped raw stdout](plumed.1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.8JLYyU.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.8JLYyU.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.8JLYyU.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.8JLYyU.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.8JLYyU.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.8JLYyU.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.8JLYyU.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.8JLYyU.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.8JLYyU.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.8JLYyU.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.8JLYyU.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.8JLYyU.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.8JLYyU.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.8JLYyU.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.8JLYyU.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.8JLYyU.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.10.0-dev.so ../PathCV.cpp

[fv-az1215-453:07385] *** Process received signal ***
[fv-az1215-453:07385] Signal: Aborted (6)
[fv-az1215-453:07385] Signal code:  (-6)
[fv-az1215-453:07385] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3983642520]
[fv-az1215-453:07385] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f39836969fc]
[fv-az1215-453:07385] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3983642476]
[fv-az1215-453:07385] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f39836287f3]
[fv-az1215-453:07385] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3983aa2b9e]
[fv-az1215-453:07385] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3983aae20c]
[fv-az1215-453:07385] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3983aae277]
[fv-az1215-453:07385] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3983aae52b]
[fv-az1215-453:07385] [ 8] plumed_master(+0x14274)[0x55cf3bfc6274]
[fv-az1215-453:07385] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3983629d90]
[fv-az1215-453:07385] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3983629e40]
[fv-az1215-453:07385] [11] plumed_master(+0x14ed5)[0x55cf3bfc6ed5]
[fv-az1215-453:07385] *** End of error message ***
</pre>
{% endraw %}
