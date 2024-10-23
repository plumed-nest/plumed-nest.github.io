**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  meta_inputs/LJ-38/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:700) bool PLMD::Keywords::checkArgumentType(const size_t&, const bool&) const
WARNING: type for input argument has not been specified
[fv-az1016-35:08001] *** Process received signal ***
[fv-az1016-35:08001] Signal: Aborted (6)
[fv-az1016-35:08001] Signal code:  (-6)
[fv-az1016-35:08001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9de2e42520]
[fv-az1016-35:08001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9de2e969fc]
[fv-az1016-35:08001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9de2e42476]
[fv-az1016-35:08001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9de2e287f3]
[fv-az1016-35:08001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9de32a2b9e]
[fv-az1016-35:08001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9de32ae20c]
[fv-az1016-35:08001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9de32ae277]
[fv-az1016-35:08001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9de32ae52b]
[fv-az1016-35:08001] [ 8] plumed_master(+0x14254)[0x55ba36948254]
[fv-az1016-35:08001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9de2e29d90]
[fv-az1016-35:08001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9de2e29e40]
[fv-az1016-35:08001] [11] plumed_master(+0x14eb5)[0x55ba36948eb5]
[fv-az1016-35:08001] *** End of error message ***
</pre>
{% endraw %}
