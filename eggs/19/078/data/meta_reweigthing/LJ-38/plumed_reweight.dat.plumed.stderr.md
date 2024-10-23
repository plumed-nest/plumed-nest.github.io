**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az1016-35:08909] *** Process received signal ***
[fv-az1016-35:08909] Signal: Aborted (6)
[fv-az1016-35:08909] Signal code:  (-6)
[fv-az1016-35:08909] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f37a8e42520]
[fv-az1016-35:08909] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f37a8e969fc]
[fv-az1016-35:08909] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f37a8e42476]
[fv-az1016-35:08909] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f37a8e287f3]
[fv-az1016-35:08909] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f37a92a2b9e]
[fv-az1016-35:08909] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f37a92ae20c]
[fv-az1016-35:08909] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f37a92ae277]
[fv-az1016-35:08909] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f37a92ae52b]
[fv-az1016-35:08909] [ 8] plumed(+0x14254)[0x556bbe77d254]
[fv-az1016-35:08909] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f37a8e29d90]
[fv-az1016-35:08909] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f37a8e29e40]
[fv-az1016-35:08909] [11] plumed(+0x14eb5)[0x556bbe77deb5]
[fv-az1016-35:08909] *** End of error message ***
</pre>
{% endraw %}
