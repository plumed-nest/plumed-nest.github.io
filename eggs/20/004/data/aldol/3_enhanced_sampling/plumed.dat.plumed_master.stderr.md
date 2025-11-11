**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.vxiU91.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.vxiU91.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.vxiU91.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.vxiU91.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.vxiU91.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.vxiU91.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.vxiU91.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.vxiU91.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10426] *** Process received signal ***
[runnervmw9dnm:10426] Signal: Aborted (6)
[runnervmw9dnm:10426] Signal code:  (-6)
[runnervmw9dnm:10426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05a4645330]
[runnervmw9dnm:10426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05a469eb2c]
[runnervmw9dnm:10426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05a464527e]
[runnervmw9dnm:10426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05a46288ff]
[runnervmw9dnm:10426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05a4aa5ff5]
[runnervmw9dnm:10426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05a4abb0da]
[runnervmw9dnm:10426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05a4aa5a55]
[runnervmw9dnm:10426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05a4aa5a6f]
[runnervmw9dnm:10426] [ 8] plumed_master(+0x146dd)[0x56456f04e6dd]
[runnervmw9dnm:10426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05a462a1ca]
[runnervmw9dnm:10426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05a462a28b]
[runnervmw9dnm:10426] [11] plumed_master(+0x15365)[0x56456f04f365]
[runnervmw9dnm:10426] *** End of error message ***
</pre>
{% endraw %}
