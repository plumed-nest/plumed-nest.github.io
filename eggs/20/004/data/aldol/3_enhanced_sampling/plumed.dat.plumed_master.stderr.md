**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.iP3xMI.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.iP3xMI.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.iP3xMI.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.iP3xMI.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.iP3xMI.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.iP3xMI.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.iP3xMI.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.iP3xMI.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmkj6or:09149] *** Process received signal ***
[runnervmkj6or:09149] Signal: Aborted (6)
[runnervmkj6or:09149] Signal code:  (-6)
[runnervmkj6or:09149] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff6a045330]
[runnervmkj6or:09149] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff6a09eb2c]
[runnervmkj6or:09149] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff6a04527e]
[runnervmkj6or:09149] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff6a0288ff]
[runnervmkj6or:09149] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff6a4a5ff5]
[runnervmkj6or:09149] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff6a4bb0da]
[runnervmkj6or:09149] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff6a4a5a55]
[runnervmkj6or:09149] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff6a4a5a6f]
[runnervmkj6or:09149] [ 8] plumed_master(+0x146dd)[0x55e53a77d6dd]
[runnervmkj6or:09149] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff6a02a1ca]
[runnervmkj6or:09149] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff6a02a28b]
[runnervmkj6or:09149] [11] plumed_master(+0x15365)[0x55e53a77e365]
[runnervmkj6or:09149] *** End of error message ***
</pre>
{% endraw %}
