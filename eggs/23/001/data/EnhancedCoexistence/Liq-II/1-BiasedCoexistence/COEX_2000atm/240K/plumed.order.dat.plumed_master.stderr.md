**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1370-99:62626] *** Process received signal ***
[fv-az1370-99:62626] Signal: Aborted (6)
[fv-az1370-99:62626] Signal code:  (-6)
[fv-az1370-99:62626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47d8045330]
[fv-az1370-99:62626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47d809eb2c]
[fv-az1370-99:62626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47d804527e]
[fv-az1370-99:62626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47d80288ff]
[fv-az1370-99:62626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47d84a5ff5]
[fv-az1370-99:62626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47d84bb0da]
[fv-az1370-99:62626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47d84a5a55]
[fv-az1370-99:62626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47d84a5a6f]
[fv-az1370-99:62626] [ 8] plumed_master(+0x146dd)[0x556bca7b16dd]
[fv-az1370-99:62626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47d802a1ca]
[fv-az1370-99:62626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47d802a28b]
[fv-az1370-99:62626] [11] plumed_master(+0x15365)[0x556bca7b2365]
[fv-az1370-99:62626] *** End of error message ***
</pre>
{% endraw %}
