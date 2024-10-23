**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az801-114:05002] *** Process received signal ***
[fv-az801-114:05002] Signal: Aborted (6)
[fv-az801-114:05002] Signal code:  (-6)
[fv-az801-114:05002] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efcf0842520]
[fv-az801-114:05002] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efcf08969fc]
[fv-az801-114:05002] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efcf0842476]
[fv-az801-114:05002] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efcf08287f3]
[fv-az801-114:05002] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efcf0ca2b9e]
[fv-az801-114:05002] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efcf0cae20c]
[fv-az801-114:05002] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efcf0cae277]
[fv-az801-114:05002] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efcf0cae52b]
[fv-az801-114:05002] [ 8] plumed_master(+0x14254)[0x564ca6c0b254]
[fv-az801-114:05002] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efcf0829d90]
[fv-az801-114:05002] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efcf0829e40]
[fv-az801-114:05002] [11] plumed_master(+0x14eb5)[0x564ca6c0beb5]
[fv-az801-114:05002] *** End of error message ***
</pre>
{% endraw %}
