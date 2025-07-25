**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
In file included from /home/runner/opt/include/plumed_master/core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.lC9Raq.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:27:
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:94: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
94 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:100: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
100 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:102: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
102 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:108: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
108 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:112: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
112 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:116: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
116 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:120: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
120 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/core/../tools/Pbc.h:123: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
123 | #pragma acc routine seq
|
In file included from /home/runner/opt/include/plumed_master/core/Colvar.h:27:
/home/runner/opt/include/plumed_master/core/../tools/Matrix.h:100: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
100 | #pragma acc enter data copyin(this[0:1],sz,data[0:sz])
|
/home/runner/opt/include/plumed_master/core/../tools/Matrix.h:103: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
103 | #pragma acc exit data delete(data[0:sz],sz,this[0:1])
|
/home/runner/opt/include/plumed_master/core/../tools/Matrix.h:117: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
117 | #pragma acc enter data copyin(this[0:1])
|
/home/runner/opt/include/plumed_master/core/../tools/Matrix.h:123: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
123 | #pragma acc exit data delete( this[0:1])
|
In file included from Contacts.lC9Raq.cpp:34:
/home/runner/opt/include/plumed_master/tools/SwitchingFunction.h:182: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
182 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/tools/SwitchingFunction.h:190: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
190 | #pragma acc routine seq
|
Contacts.lC9Raq.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.lC9Raq.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.lC9Raq.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.lC9Raq.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.lC9Raq.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.lC9Raq.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.lC9Raq.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmpptgkbjq6m:09074] *** Process received signal ***
[pkrvmpptgkbjq6m:09074] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09074] Signal code:  (-6)
[pkrvmpptgkbjq6m:09074] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfea045330]
[pkrvmpptgkbjq6m:09074] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfea09eb2c]
[pkrvmpptgkbjq6m:09074] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfea04527e]
[pkrvmpptgkbjq6m:09074] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfea0288ff]
[pkrvmpptgkbjq6m:09074] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfea4a5ff5]
[pkrvmpptgkbjq6m:09074] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfea4bb0da]
[pkrvmpptgkbjq6m:09074] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfea4a5a55]
[pkrvmpptgkbjq6m:09074] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfea4a5a6f]
[pkrvmpptgkbjq6m:09074] [ 8] plumed_master(+0x146dd)[0x55f56d6d26dd]
[pkrvmpptgkbjq6m:09074] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfea02a1ca]
[pkrvmpptgkbjq6m:09074] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfea02a28b]
[pkrvmpptgkbjq6m:09074] [11] plumed_master(+0x15365)[0x55f56d6d3365]
[pkrvmpptgkbjq6m:09074] *** End of error message ***
</pre>
{% endraw %}
