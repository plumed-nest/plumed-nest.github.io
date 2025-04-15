**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.rnSUll.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.rnSUll.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.rnSUll.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:256:8: note: declared here
256 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.rnSUll.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.rnSUll.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.rnSUll.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.rnSUll.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.rnSUll.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[fv-az1719-82:68482] *** Process received signal ***
[fv-az1719-82:68482] Signal: Aborted (6)
[fv-az1719-82:68482] Signal code:  (-6)
[fv-az1719-82:68482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b7d645330]
[fv-az1719-82:68482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b7d69eb2c]
[fv-az1719-82:68482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b7d64527e]
[fv-az1719-82:68482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b7d6288ff]
[fv-az1719-82:68482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b7daa5ff5]
[fv-az1719-82:68482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b7dabb0da]
[fv-az1719-82:68482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b7daa5a55]
[fv-az1719-82:68482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b7daa5a6f]
[fv-az1719-82:68482] [ 8] plumed_master(+0x146dd)[0x561d192066dd]
[fv-az1719-82:68482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b7d62a1ca]
[fv-az1719-82:68482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b7d62a28b]
[fv-az1719-82:68482] [11] plumed_master(+0x15365)[0x561d19207365]
[fv-az1719-82:68482] *** End of error message ***
</pre>
{% endraw %}
