**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az1272-851:10556] *** Process received signal ***
[fv-az1272-851:10556] Signal: Aborted (6)
[fv-az1272-851:10556] Signal code:  (-6)
[fv-az1272-851:10556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbb85e42520]
[fv-az1272-851:10556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbb85e969fc]
[fv-az1272-851:10556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbb85e42476]
[fv-az1272-851:10556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbb85e287f3]
[fv-az1272-851:10556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbb862a2b9e]
[fv-az1272-851:10556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbb862ae20c]
[fv-az1272-851:10556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbb862ae277]
[fv-az1272-851:10556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbb862ae52b]
[fv-az1272-851:10556] [ 8] plumed_master(+0x14274)[0x56545fa3a274]
[fv-az1272-851:10556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbb85e29d90]
[fv-az1272-851:10556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbb85e29e40]
[fv-az1272-851:10556] [11] plumed_master(+0x14ed5)[0x56545fa3aed5]
[fv-az1272-851:10556] *** End of error message ***
</pre>
{% endraw %}
