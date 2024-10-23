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
[fv-az975-395:07910] *** Process received signal ***
[fv-az975-395:07910] Signal: Aborted (6)
[fv-az975-395:07910] Signal code:  (-6)
[fv-az975-395:07910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f31f0842520]
[fv-az975-395:07910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f31f08969fc]
[fv-az975-395:07910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f31f0842476]
[fv-az975-395:07910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f31f08287f3]
[fv-az975-395:07910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f31f0ca2b9e]
[fv-az975-395:07910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f31f0cae20c]
[fv-az975-395:07910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f31f0cae277]
[fv-az975-395:07910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f31f0cae52b]
[fv-az975-395:07910] [ 8] plumed_master(+0x14254)[0x557840847254]
[fv-az975-395:07910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f31f0829d90]
[fv-az975-395:07910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f31f0829e40]
[fv-az975-395:07910] [11] plumed_master(+0x14eb5)[0x557840847eb5]
[fv-az975-395:07910] *** End of error message ***
</pre>
{% endraw %}
