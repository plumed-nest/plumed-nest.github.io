**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07417] *** Process received signal ***
[pkrvm7jw40e0xgp:07417] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07417] Signal code:  (-6)
[pkrvm7jw40e0xgp:07417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2c6e45330]
[pkrvm7jw40e0xgp:07417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2c6e9eb2c]
[pkrvm7jw40e0xgp:07417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2c6e4527e]
[pkrvm7jw40e0xgp:07417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2c6e288ff]
[pkrvm7jw40e0xgp:07417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2c72a5ff5]
[pkrvm7jw40e0xgp:07417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2c72bb0da]
[pkrvm7jw40e0xgp:07417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2c72a5a55]
[pkrvm7jw40e0xgp:07417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2c72a5a6f]
[pkrvm7jw40e0xgp:07417] [ 8] plumed_master(+0x146dd)[0x55f9fb5336dd]
[pkrvm7jw40e0xgp:07417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2c6e2a1ca]
[pkrvm7jw40e0xgp:07417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2c6e2a28b]
[pkrvm7jw40e0xgp:07417] [11] plumed_master(+0x15365)[0x55f9fb534365]
[pkrvm7jw40e0xgp:07417] *** End of error message ***
</pre>
{% endraw %}
