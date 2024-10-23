**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az801-114:04962] *** Process received signal ***
[fv-az801-114:04962] Signal: Aborted (6)
[fv-az801-114:04962] Signal code:  (-6)
[fv-az801-114:04962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fee60242520]
[fv-az801-114:04962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fee602969fc]
[fv-az801-114:04962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fee60242476]
[fv-az801-114:04962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fee602287f3]
[fv-az801-114:04962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fee606a2b9e]
[fv-az801-114:04962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fee606ae20c]
[fv-az801-114:04962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fee606ae277]
[fv-az801-114:04962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fee606ae52b]
[fv-az801-114:04962] [ 8] plumed(+0x14254)[0x560b160d8254]
[fv-az801-114:04962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fee60229d90]
[fv-az801-114:04962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fee60229e40]
[fv-az801-114:04962] [11] plumed(+0x14eb5)[0x560b160d8eb5]
[fv-az801-114:04962] *** End of error message ***
</pre>
{% endraw %}
