**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07314] *** Process received signal ***
[pkrvm7jw40e0xgp:07314] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07314] Signal code:  (-6)
[pkrvm7jw40e0xgp:07314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbf0645330]
[pkrvm7jw40e0xgp:07314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbf069eb2c]
[pkrvm7jw40e0xgp:07314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbf064527e]
[pkrvm7jw40e0xgp:07314] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbf06288ff]
[pkrvm7jw40e0xgp:07314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbf0aa5ff5]
[pkrvm7jw40e0xgp:07314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbf0abb0da]
[pkrvm7jw40e0xgp:07314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbf0aa5a55]
[pkrvm7jw40e0xgp:07314] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbf0aa5a6f]
[pkrvm7jw40e0xgp:07314] [ 8] plumed_master(+0x146dd)[0x55c888af06dd]
[pkrvm7jw40e0xgp:07314] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbf062a1ca]
[pkrvm7jw40e0xgp:07314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbf062a28b]
[pkrvm7jw40e0xgp:07314] [11] plumed_master(+0x15365)[0x55c888af1365]
[pkrvm7jw40e0xgp:07314] *** End of error message ***
</pre>
{% endraw %}
