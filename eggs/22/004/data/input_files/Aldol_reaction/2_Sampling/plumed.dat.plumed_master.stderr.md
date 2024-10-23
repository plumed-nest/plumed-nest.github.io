**Project ID:** [plumID:22.004]({{ '/' | absolute_url }}eggs/22/004/)  
Stderr for source:  input_files/Aldol_reaction/2_Sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.cLIHcu.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.cLIHcu.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.cLIHcu.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.cLIHcu.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.cLIHcu.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.cLIHcu.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.cLIHcu.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.cLIHcu.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:221) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1429-284:05610] *** Process received signal ***
[fv-az1429-284:05610] Signal: Aborted (6)
[fv-az1429-284:05610] Signal code:  (-6)
[fv-az1429-284:05610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f002b242520]
[fv-az1429-284:05610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f002b2969fc]
[fv-az1429-284:05610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f002b242476]
[fv-az1429-284:05610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f002b2287f3]
[fv-az1429-284:05610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f002b6a2b9e]
[fv-az1429-284:05610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f002b6ae20c]
[fv-az1429-284:05610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f002b6ae277]
[fv-az1429-284:05610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f002b6ae52b]
[fv-az1429-284:05610] [ 8] plumed_master(+0x14254)[0x5596bd4c6254]
[fv-az1429-284:05610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f002b229d90]
[fv-az1429-284:05610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f002b229e40]
[fv-az1429-284:05610] [11] plumed_master(+0x14eb5)[0x5596bd4c6eb5]
[fv-az1429-284:05610] *** End of error message ***
</pre>
{% endraw %}
