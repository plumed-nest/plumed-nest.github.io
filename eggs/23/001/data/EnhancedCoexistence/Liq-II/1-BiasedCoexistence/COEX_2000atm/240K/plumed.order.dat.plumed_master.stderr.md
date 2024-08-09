**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az530-623:06355] *** Process received signal ***
[fv-az530-623:06355] Signal: Aborted (6)
[fv-az530-623:06355] Signal code:  (-6)
[fv-az530-623:06355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f31f2c42520]
[fv-az530-623:06355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f31f2c969fc]
[fv-az530-623:06355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f31f2c42476]
[fv-az530-623:06355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f31f2c287f3]
[fv-az530-623:06355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f31f30a2b9e]
[fv-az530-623:06355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f31f30ae20c]
[fv-az530-623:06355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f31f30ae277]
[fv-az530-623:06355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f31f30ae52b]
[fv-az530-623:06355] [ 8] plumed_master(+0x14274)[0x5574f110a274]
[fv-az530-623:06355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f31f2c29d90]
[fv-az530-623:06355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f31f2c29e40]
[fv-az530-623:06355] [11] plumed_master(+0x14ed5)[0x5574f110aed5]
[fv-az530-623:06355] *** End of error message ***
</pre>
{% endraw %}
