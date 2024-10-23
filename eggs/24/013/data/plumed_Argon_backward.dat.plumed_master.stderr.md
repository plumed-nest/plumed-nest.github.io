**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az801-114:04970] *** Process received signal ***
[fv-az801-114:04970] Signal: Aborted (6)
[fv-az801-114:04970] Signal code:  (-6)
[fv-az801-114:04970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb025842520]
[fv-az801-114:04970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb0258969fc]
[fv-az801-114:04970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb025842476]
[fv-az801-114:04970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb0258287f3]
[fv-az801-114:04970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb025ca2b9e]
[fv-az801-114:04970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb025cae20c]
[fv-az801-114:04970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb025cae277]
[fv-az801-114:04970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb025cae52b]
[fv-az801-114:04970] [ 8] plumed_master(+0x14254)[0x558f0c393254]
[fv-az801-114:04970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb025829d90]
[fv-az801-114:04970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb025829e40]
[fv-az801-114:04970] [11] plumed_master(+0x14eb5)[0x558f0c393eb5]
[fv-az801-114:04970] *** End of error message ***
</pre>
{% endraw %}
