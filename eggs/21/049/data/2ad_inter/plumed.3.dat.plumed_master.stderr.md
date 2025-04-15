**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
Stderr for source:  2ad_inter/plumed.3.dat   
Download: [zipped raw stdout](plumed.3.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.3.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
../PathCV.Lfq95j.cpp: In static member function ‘static void PLMD::function::PathCV::registerKeywords(PLMD::Keywords&)’:
../PathCV.Lfq95j.cpp:198:3: error: ‘componentsAreNotOptional’ was not declared in this scope
198 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../PathCV.Lfq95j.cpp:199:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
199 |   keys.addOutputComponent("s","default","the position on the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from ../PathCV.Lfq95j.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.Lfq95j.cpp:200:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
200 |   keys.addOutputComponent("z","default","the distance from the path");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../PathCV.Lfq95j.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
../PathCV.Lfq95j.cpp:208:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
208 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Lfq95j.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
../PathCV.Lfq95j.cpp:236:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
236 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Lfq95j.cpp:259:11: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
259 |       if(i==mw_id_) ifiles[i]->close();
|          ~^~~~~~~~
../PathCV.Lfq95j.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
../PathCV.Lfq95j.cpp:483:26: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
483 |     for(int inode=0;inode<nnodes;inode++){
|                     ~~~~~^~~~~~~
../PathCV.Lfq95j.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
../PathCV.Lfq95j.cpp:941:16: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
941 |   for(int i=0;i<mw_n_;++i){
|               ~^~~~~~
../PathCV.Lfq95j.cpp:942:9: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
942 |     if(i==mw_id_) continue;
|        ~^~~~~~~~
../PathCV.Lfq95j.cpp:957:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
957 |     comm.Barrier();
|     ^~~~
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed_master/function/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:30:
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../PathCV.Lfq95j.cpp:958:5: error: invalid use of incomplete type ‘class PLMD::Communicator’
958 |     multi_sim_comm.Barrier();
|     ^~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/function/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../PathCV.2.11.0-dev.so ../PathCV.cpp

[fv-az1277-646:65531] *** Process received signal ***
[fv-az1277-646:65531] Signal: Aborted (6)
[fv-az1277-646:65531] Signal code:  (-6)
[fv-az1277-646:65531] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19d6445330]
[fv-az1277-646:65531] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19d649eb2c]
[fv-az1277-646:65531] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19d644527e]
[fv-az1277-646:65531] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19d64288ff]
[fv-az1277-646:65531] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19d68a5ff5]
[fv-az1277-646:65531] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19d68bb0da]
[fv-az1277-646:65531] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19d68a5a55]
[fv-az1277-646:65531] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19d68a5a6f]
[fv-az1277-646:65531] [ 8] plumed_master(+0x146dd)[0x55ece7f9e6dd]
[fv-az1277-646:65531] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19d642a1ca]
[fv-az1277-646:65531] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19d642a28b]
[fv-az1277-646:65531] [11] plumed_master(+0x15365)[0x55ece7f9f365]
[fv-az1277-646:65531] *** End of error message ***
</pre>
{% endraw %}
