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
from Contacts.jPycnx.cpp:22:
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
Contacts.jPycnx.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.jPycnx.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.jPycnx.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.jPycnx.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.jPycnx.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.jPycnx.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.jPycnx.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmf6wy0o8zjz:64216] *** Process received signal ***
[pkrvmf6wy0o8zjz:64216] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64216] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64216] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd1ea045330]
[pkrvmf6wy0o8zjz:64216] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd1ea09eb2c]
[pkrvmf6wy0o8zjz:64216] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd1ea04527e]
[pkrvmf6wy0o8zjz:64216] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1ea0288ff]
[pkrvmf6wy0o8zjz:64216] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1ea4a5ff5]
[pkrvmf6wy0o8zjz:64216] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1ea4bb0da]
[pkrvmf6wy0o8zjz:64216] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1ea4a5a55]
[pkrvmf6wy0o8zjz:64216] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1ea4a5a6f]
[pkrvmf6wy0o8zjz:64216] [ 8] plumed_master(+0x146dd)[0x561ffa8296dd]
[pkrvmf6wy0o8zjz:64216] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd1ea02a1ca]
[pkrvmf6wy0o8zjz:64216] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd1ea02a28b]
[pkrvmf6wy0o8zjz:64216] [11] plumed_master(+0x15365)[0x561ffa82a365]
[pkrvmf6wy0o8zjz:64216] *** End of error message ***
</pre>
{% endraw %}
