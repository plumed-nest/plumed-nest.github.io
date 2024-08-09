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
[fv-az530-623:06324] *** Process received signal ***
[fv-az530-623:06324] Signal: Aborted (6)
[fv-az530-623:06324] Signal code:  (-6)
[fv-az530-623:06324] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6a58442520]
[fv-az530-623:06324] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6a584969fc]
[fv-az530-623:06324] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6a58442476]
[fv-az530-623:06324] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6a584287f3]
[fv-az530-623:06324] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6a588a2b9e]
[fv-az530-623:06324] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6a588ae20c]
[fv-az530-623:06324] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6a588ae277]
[fv-az530-623:06324] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6a588ae52b]
[fv-az530-623:06324] [ 8] plumed_master(+0x14274)[0x55b4d73f2274]
[fv-az530-623:06324] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6a58429d90]
[fv-az530-623:06324] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6a58429e40]
[fv-az530-623:06324] [11] plumed_master(+0x14ed5)[0x55b4d73f2ed5]
[fv-az530-623:06324] *** End of error message ***
</pre>
{% endraw %}
