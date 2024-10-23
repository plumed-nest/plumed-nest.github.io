**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[fv-az585-767:04948] *** Process received signal ***
[fv-az585-767:04948] Signal: Aborted (6)
[fv-az585-767:04948] Signal code:  (-6)
[fv-az585-767:04948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2563642520]
[fv-az585-767:04948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f25636969fc]
[fv-az585-767:04948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2563642476]
[fv-az585-767:04948] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f25636287f3]
[fv-az585-767:04948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2563aa2b9e]
[fv-az585-767:04948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2563aae20c]
[fv-az585-767:04948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2563aae277]
[fv-az585-767:04948] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2563aae52b]
[fv-az585-767:04948] [ 8] plumed(+0x14254)[0x55f5a2af5254]
[fv-az585-767:04948] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2563629d90]
[fv-az585-767:04948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2563629e40]
[fv-az585-767:04948] [11] plumed(+0x14eb5)[0x55f5a2af5eb5]
[fv-az585-767:04948] *** End of error message ***
</pre>
{% endraw %}
