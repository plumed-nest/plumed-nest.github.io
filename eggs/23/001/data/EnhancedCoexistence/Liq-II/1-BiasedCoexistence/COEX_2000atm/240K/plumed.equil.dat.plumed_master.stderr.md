**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmgx7h7:07385] *** Process received signal ***
[runnervmgx7h7:07385] Signal: Aborted (6)
[runnervmgx7h7:07385] Signal code:  (-6)
[runnervmgx7h7:07385] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2aece45330]
[runnervmgx7h7:07385] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2aece9ec0c]
[runnervmgx7h7:07385] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2aece4527e]
[runnervmgx7h7:07385] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2aece288ff]
[runnervmgx7h7:07385] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2aed2a5ff5]
[runnervmgx7h7:07385] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2aed2bb0da]
[runnervmgx7h7:07385] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2aed2a5a55]
[runnervmgx7h7:07385] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2aed2a5a6f]
[runnervmgx7h7:07385] [ 8] plumed_master(+0x146dd)[0x55d20bf256dd]
[runnervmgx7h7:07385] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2aece2a1ca]
[runnervmgx7h7:07385] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2aece2a28b]
[runnervmgx7h7:07385] [11] plumed_master(+0x15365)[0x55d20bf26365]
[runnervmgx7h7:07385] *** End of error message ***
</pre>
{% endraw %}
