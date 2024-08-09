**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PDB2CONSTANT with label @s1259 : argument O1O_lessthan was not set in pdb input
[fv-az1530-541:10102] *** Process received signal ***
[fv-az1530-541:10102] Signal: Aborted (6)
[fv-az1530-541:10102] Signal code:  (-6)
[fv-az1530-541:10102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2ff3042520]
[fv-az1530-541:10102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2ff30969fc]
[fv-az1530-541:10102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2ff3042476]
[fv-az1530-541:10102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2ff30287f3]
[fv-az1530-541:10102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2ff34a2b9e]
[fv-az1530-541:10102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2ff34ae20c]
[fv-az1530-541:10102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2ff34ae277]
[fv-az1530-541:10102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2ff34ae52b]
[fv-az1530-541:10102] [ 8] plumed_master(+0x14274)[0x556abe76e274]
[fv-az1530-541:10102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2ff3029d90]
[fv-az1530-541:10102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2ff3029e40]
[fv-az1530-541:10102] [11] plumed_master(+0x14ed5)[0x556abe76eed5]
[fv-az1530-541:10102] *** End of error message ***
</pre>
{% endraw %}
