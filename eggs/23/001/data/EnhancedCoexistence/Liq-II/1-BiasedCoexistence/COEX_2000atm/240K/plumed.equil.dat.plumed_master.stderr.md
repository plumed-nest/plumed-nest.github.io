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
[runnervmvrwv9:06807] *** Process received signal ***
[runnervmvrwv9:06807] Signal: Aborted (6)
[runnervmvrwv9:06807] Signal code:  (-6)
[runnervmvrwv9:06807] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe729a45330]
[runnervmvrwv9:06807] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe729a9eb2c]
[runnervmvrwv9:06807] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe729a4527e]
[runnervmvrwv9:06807] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe729a288ff]
[runnervmvrwv9:06807] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe729ea5ff5]
[runnervmvrwv9:06807] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe729ebb0da]
[runnervmvrwv9:06807] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe729ea5a55]
[runnervmvrwv9:06807] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe729ea5a6f]
[runnervmvrwv9:06807] [ 8] plumed_master(+0x146dd)[0x55ed402886dd]
[runnervmvrwv9:06807] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe729a2a1ca]
[runnervmvrwv9:06807] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe729a2a28b]
[runnervmvrwv9:06807] [11] plumed_master(+0x15365)[0x55ed40289365]
[runnervmvrwv9:06807] *** End of error message ***
</pre>
{% endraw %}
