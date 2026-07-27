**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.7Wpe2B.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.7Wpe2B.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.7Wpe2B.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.7Wpe2B.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.7Wpe2B.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.7Wpe2B.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.7Wpe2B.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.7Wpe2B.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:08926] *** Process received signal ***
[runnervmvrwv9:08926] Signal: Aborted (6)
[runnervmvrwv9:08926] Signal code:  (-6)
[runnervmvrwv9:08926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8161645330]
[runnervmvrwv9:08926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f816169eb2c]
[runnervmvrwv9:08926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f816164527e]
[runnervmvrwv9:08926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81616288ff]
[runnervmvrwv9:08926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8161aa5ff5]
[runnervmvrwv9:08926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8161abb0da]
[runnervmvrwv9:08926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8161aa5a55]
[runnervmvrwv9:08926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8161aa5a6f]
[runnervmvrwv9:08926] [ 8] plumed_master(+0x146dd)[0x5576f43846dd]
[runnervmvrwv9:08926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f816162a1ca]
[runnervmvrwv9:08926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f816162a28b]
[runnervmvrwv9:08926] [11] plumed_master(+0x15365)[0x5576f4385365]
[runnervmvrwv9:08926] *** End of error message ***
</pre>
{% endraw %}
