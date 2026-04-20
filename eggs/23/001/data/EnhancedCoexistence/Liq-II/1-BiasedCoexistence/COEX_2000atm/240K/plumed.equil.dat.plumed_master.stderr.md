**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmeorf1:08665] *** Process received signal ***
[runnervmeorf1:08665] Signal: Aborted (6)
[runnervmeorf1:08665] Signal code:  (-6)
[runnervmeorf1:08665] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe99e245330]
[runnervmeorf1:08665] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe99e29eb2c]
[runnervmeorf1:08665] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe99e24527e]
[runnervmeorf1:08665] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe99e2288ff]
[runnervmeorf1:08665] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe99e6a5ff5]
[runnervmeorf1:08665] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe99e6bb0da]
[runnervmeorf1:08665] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe99e6a5a55]
[runnervmeorf1:08665] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe99e6a5a6f]
[runnervmeorf1:08665] [ 8] plumed_master(+0x146dd)[0x562f317b06dd]
[runnervmeorf1:08665] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe99e22a1ca]
[runnervmeorf1:08665] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe99e22a28b]
[runnervmeorf1:08665] [11] plumed_master(+0x15365)[0x562f317b1365]
[runnervmeorf1:08665] *** End of error message ***
</pre>
{% endraw %}
