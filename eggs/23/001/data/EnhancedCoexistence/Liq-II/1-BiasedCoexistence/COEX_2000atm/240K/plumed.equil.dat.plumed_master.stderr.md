**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az585-767:04987] *** Process received signal ***
[fv-az585-767:04987] Signal: Aborted (6)
[fv-az585-767:04987] Signal code:  (-6)
[fv-az585-767:04987] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1efba42520]
[fv-az585-767:04987] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1efba969fc]
[fv-az585-767:04987] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1efba42476]
[fv-az585-767:04987] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1efba287f3]
[fv-az585-767:04987] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1efbea2b9e]
[fv-az585-767:04987] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1efbeae20c]
[fv-az585-767:04987] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1efbeae277]
[fv-az585-767:04987] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1efbeae52b]
[fv-az585-767:04987] [ 8] plumed_master(+0x14254)[0x55b4e766f254]
[fv-az585-767:04987] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1efba29d90]
[fv-az585-767:04987] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1efba29e40]
[fv-az585-767:04987] [11] plumed_master(+0x14eb5)[0x55b4e766feb5]
[fv-az585-767:04987] *** End of error message ***
</pre>
{% endraw %}
