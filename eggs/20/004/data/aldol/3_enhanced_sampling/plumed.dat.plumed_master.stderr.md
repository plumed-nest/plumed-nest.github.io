**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Contacts.nZj6AJ.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
Contacts.nZj6AJ.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const string&, const string&, const string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:27,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from Contacts.nZj6AJ.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:178:8: note: declared here
178 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
Contacts.nZj6AJ.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
Contacts.nZj6AJ.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
Contacts.nZj6AJ.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
Contacts.nZj6AJ.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
Contacts.nZj6AJ.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:221) void PLMD::Keywords::addFlag(const string&, bool, const string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1442-469:09282] *** Process received signal ***
[fv-az1442-469:09282] Signal: Aborted (6)
[fv-az1442-469:09282] Signal code:  (-6)
[fv-az1442-469:09282] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3eaf842520]
[fv-az1442-469:09282] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3eaf8969fc]
[fv-az1442-469:09282] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3eaf842476]
[fv-az1442-469:09282] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3eaf8287f3]
[fv-az1442-469:09282] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3eafca2b9e]
[fv-az1442-469:09282] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3eafcae20c]
[fv-az1442-469:09282] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3eafcae277]
[fv-az1442-469:09282] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3eafcae52b]
[fv-az1442-469:09282] [ 8] plumed_master(+0x14254)[0x5633da47b254]
[fv-az1442-469:09282] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3eaf829d90]
[fv-az1442-469:09282] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3eaf829e40]
[fv-az1442-469:09282] [11] plumed_master(+0x14eb5)[0x5633da47beb5]
[fv-az1442-469:09282] *** End of error message ***
</pre>
{% endraw %}
