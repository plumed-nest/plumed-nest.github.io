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
[pkrvmxyh4eaekms:08632] *** Process received signal ***
[pkrvmxyh4eaekms:08632] Signal: Aborted (6)
[pkrvmxyh4eaekms:08632] Signal code:  (-6)
[pkrvmxyh4eaekms:08632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6194a45330]
[pkrvmxyh4eaekms:08632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6194a9eb2c]
[pkrvmxyh4eaekms:08632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6194a4527e]
[pkrvmxyh4eaekms:08632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6194a288ff]
[pkrvmxyh4eaekms:08632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6194ea5ff5]
[pkrvmxyh4eaekms:08632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6194ebb0da]
[pkrvmxyh4eaekms:08632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6194ea5a55]
[pkrvmxyh4eaekms:08632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6194ea5a6f]
[pkrvmxyh4eaekms:08632] [ 8] plumed_master(+0x146dd)[0x55867199c6dd]
[pkrvmxyh4eaekms:08632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6194a2a1ca]
[pkrvmxyh4eaekms:08632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6194a2a28b]
[pkrvmxyh4eaekms:08632] [11] plumed_master(+0x15365)[0x55867199d365]
[pkrvmxyh4eaekms:08632] *** End of error message ***
</pre>
{% endraw %}
