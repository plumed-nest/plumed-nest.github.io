**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmmklqx:08443] *** Process received signal ***
[runnervmmklqx:08443] Signal: Aborted (6)
[runnervmmklqx:08443] Signal code:  (-6)
[runnervmmklqx:08443] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff041c45330]
[runnervmmklqx:08443] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff041c9eb2c]
[runnervmmklqx:08443] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff041c4527e]
[runnervmmklqx:08443] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff041c288ff]
[runnervmmklqx:08443] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0420a5ff5]
[runnervmmklqx:08443] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0420bb0da]
[runnervmmklqx:08443] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0420a5a55]
[runnervmmklqx:08443] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0420a5a6f]
[runnervmmklqx:08443] [ 8] plumed_master(+0x146dd)[0x55ac0753b6dd]
[runnervmmklqx:08443] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff041c2a1ca]
[runnervmmklqx:08443] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff041c2a28b]
[runnervmmklqx:08443] [11] plumed_master(+0x15365)[0x55ac0753c365]
[runnervmmklqx:08443] *** End of error message ***
</pre>
{% endraw %}
