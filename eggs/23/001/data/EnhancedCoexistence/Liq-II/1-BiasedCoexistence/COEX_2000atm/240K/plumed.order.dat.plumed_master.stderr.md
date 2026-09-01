**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmgx7h7:07437] *** Process received signal ***
[runnervmgx7h7:07437] Signal: Aborted (6)
[runnervmgx7h7:07437] Signal code:  (-6)
[runnervmgx7h7:07437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e6c645330]
[runnervmgx7h7:07437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e6c69ec0c]
[runnervmgx7h7:07437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e6c64527e]
[runnervmgx7h7:07437] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e6c6288ff]
[runnervmgx7h7:07437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e6caa5ff5]
[runnervmgx7h7:07437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e6cabb0da]
[runnervmgx7h7:07437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e6caa5a55]
[runnervmgx7h7:07437] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e6caa5a6f]
[runnervmgx7h7:07437] [ 8] plumed_master(+0x146dd)[0x5587fd7556dd]
[runnervmgx7h7:07437] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e6c62a1ca]
[runnervmgx7h7:07437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e6c62a28b]
[runnervmgx7h7:07437] [11] plumed_master(+0x15365)[0x5587fd756365]
[runnervmgx7h7:07437] *** End of error message ***
</pre>
{% endraw %}
