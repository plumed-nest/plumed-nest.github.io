**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action PDB2CONSTANT with label @s1259 : argument O1O_lessthan was not set in pdb input
[fv-az1200-632:73431] *** Process received signal ***
[fv-az1200-632:73431] Signal: Aborted (6)
[fv-az1200-632:73431] Signal code:  (-6)
[fv-az1200-632:73431] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5520642520]
[fv-az1200-632:73431] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f55206969fc]
[fv-az1200-632:73431] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5520642476]
[fv-az1200-632:73431] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f55206287f3]
[fv-az1200-632:73431] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f5520aa4f26]
[fv-az1200-632:73431] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f5520ab6d9c]
[fv-az1200-632:73431] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f5520ab6e07]
[fv-az1200-632:73431] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5520ab70bb]
[fv-az1200-632:73431] [ 8] plumed_master(+0x12e7f)[0x5591eefcee7f]
[fv-az1200-632:73431] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5520629d90]
[fv-az1200-632:73431] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5520629e40]
[fv-az1200-632:73431] [11] plumed_master(+0x13115)[0x5591eefcf115]
[fv-az1200-632:73431] *** End of error message ***
</pre>
{% endraw %}
