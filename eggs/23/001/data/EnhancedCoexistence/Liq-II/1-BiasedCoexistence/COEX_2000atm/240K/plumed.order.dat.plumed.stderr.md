**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az585-767:05010] *** Process received signal ***
[fv-az585-767:05010] Signal: Aborted (6)
[fv-az585-767:05010] Signal code:  (-6)
[fv-az585-767:05010] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff270842520]
[fv-az585-767:05010] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff2708969fc]
[fv-az585-767:05010] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff270842476]
[fv-az585-767:05010] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff2708287f3]
[fv-az585-767:05010] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff270ca2b9e]
[fv-az585-767:05010] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff270cae20c]
[fv-az585-767:05010] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff270cae277]
[fv-az585-767:05010] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff270cae52b]
[fv-az585-767:05010] [ 8] plumed(+0x14254)[0x55a21e48e254]
[fv-az585-767:05010] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff270829d90]
[fv-az585-767:05010] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff270829e40]
[fv-az585-767:05010] [11] plumed(+0x14eb5)[0x55a21e48eeb5]
[fv-az585-767:05010] *** End of error message ***
</pre>
{% endraw %}
