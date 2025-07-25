**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmpptgkbjq6m:08762] *** Process received signal ***
[pkrvmpptgkbjq6m:08762] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08762] Signal code:  (-6)
[pkrvmpptgkbjq6m:08762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3891445330]
[pkrvmpptgkbjq6m:08762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f389149eb2c]
[pkrvmpptgkbjq6m:08762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f389144527e]
[pkrvmpptgkbjq6m:08762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38914288ff]
[pkrvmpptgkbjq6m:08762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38918a5ff5]
[pkrvmpptgkbjq6m:08762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38918bb0da]
[pkrvmpptgkbjq6m:08762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38918a5a55]
[pkrvmpptgkbjq6m:08762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38918a5a6f]
[pkrvmpptgkbjq6m:08762] [ 8] plumed(+0x146dd)[0x55b5ee68a6dd]
[pkrvmpptgkbjq6m:08762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f389142a1ca]
[pkrvmpptgkbjq6m:08762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f389142a28b]
[pkrvmpptgkbjq6m:08762] [11] plumed(+0x15365)[0x55b5ee68b365]
[pkrvmpptgkbjq6m:08762] *** End of error message ***
</pre>
{% endraw %}
