**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  meta_inputs/LJ-38/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az1153-362:70228] *** Process received signal ***
[fv-az1153-362:70228] Signal: Aborted (6)
[fv-az1153-362:70228] Signal code:  (-6)
[fv-az1153-362:70228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd4a0442520]
[fv-az1153-362:70228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd4a04969fc]
[fv-az1153-362:70228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd4a0442476]
[fv-az1153-362:70228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd4a04287f3]
[fv-az1153-362:70228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd4a08a4f26]
[fv-az1153-362:70228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd4a08b6d9c]
[fv-az1153-362:70228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd4a08b6e07]
[fv-az1153-362:70228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd4a08b70bb]
[fv-az1153-362:70228] [ 8] plumed(+0x12f48)[0x556c7d21af48]
[fv-az1153-362:70228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd4a0429d90]
[fv-az1153-362:70228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd4a0429e40]
[fv-az1153-362:70228] [11] plumed(+0x131e5)[0x556c7d21b1e5]
[fv-az1153-362:70228] *** End of error message ***
</pre>
{% endraw %}
