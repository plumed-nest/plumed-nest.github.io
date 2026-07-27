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
[runnervmvrwv9:06858] *** Process received signal ***
[runnervmvrwv9:06858] Signal: Aborted (6)
[runnervmvrwv9:06858] Signal code:  (-6)
[runnervmvrwv9:06858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ee2245330]
[runnervmvrwv9:06858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ee229eb2c]
[runnervmvrwv9:06858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ee224527e]
[runnervmvrwv9:06858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ee22288ff]
[runnervmvrwv9:06858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ee26a5ff5]
[runnervmvrwv9:06858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ee26bb0da]
[runnervmvrwv9:06858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ee26a5a55]
[runnervmvrwv9:06858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ee26a5a6f]
[runnervmvrwv9:06858] [ 8] plumed_master(+0x146dd)[0x558b5eb6f6dd]
[runnervmvrwv9:06858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ee222a1ca]
[runnervmvrwv9:06858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ee222a28b]
[runnervmvrwv9:06858] [11] plumed_master(+0x15365)[0x558b5eb70365]
[runnervmvrwv9:06858] *** End of error message ***
</pre>
{% endraw %}
