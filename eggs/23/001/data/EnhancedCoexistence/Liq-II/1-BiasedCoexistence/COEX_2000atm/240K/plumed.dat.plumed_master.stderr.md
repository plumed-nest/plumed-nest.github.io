**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmvrwv9:06756] *** Process received signal ***
[runnervmvrwv9:06756] Signal: Aborted (6)
[runnervmvrwv9:06756] Signal code:  (-6)
[runnervmvrwv9:06756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4cb8a45330]
[runnervmvrwv9:06756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4cb8a9eb2c]
[runnervmvrwv9:06756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4cb8a4527e]
[runnervmvrwv9:06756] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4cb8a288ff]
[runnervmvrwv9:06756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4cb8ea5ff5]
[runnervmvrwv9:06756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4cb8ebb0da]
[runnervmvrwv9:06756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4cb8ea5a55]
[runnervmvrwv9:06756] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4cb8ea5a6f]
[runnervmvrwv9:06756] [ 8] plumed_master(+0x146dd)[0x561d2f88e6dd]
[runnervmvrwv9:06756] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4cb8a2a1ca]
[runnervmvrwv9:06756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4cb8a2a28b]
[runnervmvrwv9:06756] [11] plumed_master(+0x15365)[0x561d2f88f365]
[runnervmvrwv9:06756] *** End of error message ***
</pre>
{% endraw %}
