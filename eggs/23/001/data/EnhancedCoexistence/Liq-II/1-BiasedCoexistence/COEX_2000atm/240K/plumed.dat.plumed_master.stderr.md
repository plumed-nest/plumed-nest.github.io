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
[pkrvmxyh4eaekms:08526] *** Process received signal ***
[pkrvmxyh4eaekms:08526] Signal: Aborted (6)
[pkrvmxyh4eaekms:08526] Signal code:  (-6)
[pkrvmxyh4eaekms:08526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faaa5e45330]
[pkrvmxyh4eaekms:08526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faaa5e9eb2c]
[pkrvmxyh4eaekms:08526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faaa5e4527e]
[pkrvmxyh4eaekms:08526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faaa5e288ff]
[pkrvmxyh4eaekms:08526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faaa62a5ff5]
[pkrvmxyh4eaekms:08526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faaa62bb0da]
[pkrvmxyh4eaekms:08526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faaa62a5a55]
[pkrvmxyh4eaekms:08526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faaa62a5a6f]
[pkrvmxyh4eaekms:08526] [ 8] plumed_master(+0x146dd)[0x55d5e7bfb6dd]
[pkrvmxyh4eaekms:08526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faaa5e2a1ca]
[pkrvmxyh4eaekms:08526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faaa5e2a28b]
[pkrvmxyh4eaekms:08526] [11] plumed_master(+0x15365)[0x55d5e7bfc365]
[pkrvmxyh4eaekms:08526] *** End of error message ***
</pre>
{% endraw %}
