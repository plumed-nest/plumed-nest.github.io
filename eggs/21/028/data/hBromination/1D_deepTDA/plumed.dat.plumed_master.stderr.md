**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/1D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../Contacts.36YGK4.cpp: In static member function ‘static void PLMD::colvar::Contacts::registerKeywords(PLMD::Keywords&)’:
../Contacts.36YGK4.cpp:77:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
77 |   keys.addOutputComponent("c", "default", "contacts");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/core/Colvar.h:25,
from ../Contacts.36YGK4.cpp:22:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:268:8: note: declared here
268 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
../Contacts.36YGK4.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../Contacts.36YGK4.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
93 |   for(unsigned int i=0; i<num_atomsa; i++)
|                         ~^~~~~~~~~~~
../Contacts.36YGK4.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
99 |   for(unsigned int i=0; i<num_atomsb; i++)
|                         ~^~~~~~~~~~~
../Contacts.36YGK4.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
124 |   for(unsigned int i=0;i<num_atomsa;++i){
|                        ~^~~~~~~~~~~
../Contacts.36YGK4.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
129 |   for(unsigned int i=0;i<num_atomsb;++i){
|                        ~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10687] *** Process received signal ***
[runnervmw9dnm:10687] Signal: Aborted (6)
[runnervmw9dnm:10687] Signal code:  (-6)
[runnervmw9dnm:10687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02bca45330]
[runnervmw9dnm:10687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02bca9eb2c]
[runnervmw9dnm:10687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02bca4527e]
[runnervmw9dnm:10687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02bca288ff]
[runnervmw9dnm:10687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02bcea5ff5]
[runnervmw9dnm:10687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02bcebb0da]
[runnervmw9dnm:10687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02bcea5a55]
[runnervmw9dnm:10687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02bcea5a6f]
[runnervmw9dnm:10687] [ 8] plumed_master(+0x146dd)[0x5594185d96dd]
[runnervmw9dnm:10687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02bca2a1ca]
[runnervmw9dnm:10687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02bca2a28b]
[runnervmw9dnm:10687] [11] plumed_master(+0x15365)[0x5594185da365]
[runnervmw9dnm:10687] *** End of error message ***
</pre>
{% endraw %}
