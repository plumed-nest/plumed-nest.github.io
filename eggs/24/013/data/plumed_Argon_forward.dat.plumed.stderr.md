**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az801-114:04994] *** Process received signal ***
[fv-az801-114:04994] Signal: Aborted (6)
[fv-az801-114:04994] Signal code:  (-6)
[fv-az801-114:04994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5aa2042520]
[fv-az801-114:04994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5aa20969fc]
[fv-az801-114:04994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5aa2042476]
[fv-az801-114:04994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5aa20287f3]
[fv-az801-114:04994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5aa24a2b9e]
[fv-az801-114:04994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5aa24ae20c]
[fv-az801-114:04994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5aa24ae277]
[fv-az801-114:04994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5aa24ae52b]
[fv-az801-114:04994] [ 8] plumed(+0x14254)[0x55fe44d43254]
[fv-az801-114:04994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5aa2029d90]
[fv-az801-114:04994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5aa2029e40]
[fv-az801-114:04994] [11] plumed(+0x14eb5)[0x55fe44d43eb5]
[fv-az801-114:04994] *** End of error message ***
</pre>
{% endraw %}