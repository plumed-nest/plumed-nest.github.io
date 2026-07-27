**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.6O1zN6.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
../Contacts.6O1zN6.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from ../Contacts.6O1zN6.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../Contacts.6O1zN6.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.6O1zN6.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.6O1zN6.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.6O1zN6.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.6O1zN6.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:10349] *** Process received signal ***
[runnervmvrwv9:10349] Signal: Aborted (6)
[runnervmvrwv9:10349] Signal code:  (-6)
[runnervmvrwv9:10349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62bf245330]
[runnervmvrwv9:10349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62bf29eb2c]
[runnervmvrwv9:10349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62bf24527e]
[runnervmvrwv9:10349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62bf2288ff]
[runnervmvrwv9:10349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62bf6a5ff5]
[runnervmvrwv9:10349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62bf6bb0da]
[runnervmvrwv9:10349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62bf6a5a55]
[runnervmvrwv9:10349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62bf6a5a6f]
[runnervmvrwv9:10349] [ 8] plumed_master(+0x146dd)[0x55ac4a3e16dd]
[runnervmvrwv9:10349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62bf22a1ca]
[runnervmvrwv9:10349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62bf22a28b]
[runnervmvrwv9:10349] [11] plumed_master(+0x15365)[0x55ac4a3e2365]
[runnervmvrwv9:10349] *** End of error message ***
</pre>
{% endraw %}
