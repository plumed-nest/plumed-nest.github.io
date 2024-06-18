**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1215-453:04055] *** Process received signal ***
[fv-az1215-453:04055] Signal: Aborted (6)
[fv-az1215-453:04055] Signal code:  (-6)
[fv-az1215-453:04055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3e29042520]
[fv-az1215-453:04055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3e290969fc]
[fv-az1215-453:04055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3e29042476]
[fv-az1215-453:04055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3e290287f3]
[fv-az1215-453:04055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3e294a2b9e]
[fv-az1215-453:04055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3e294ae20c]
[fv-az1215-453:04055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3e294ae277]
[fv-az1215-453:04055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3e294ae52b]
[fv-az1215-453:04055] [ 8] plumed_master(+0x14274)[0x560646236274]
[fv-az1215-453:04055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3e29029d90]
[fv-az1215-453:04055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3e29029e40]
[fv-az1215-453:04055] [11] plumed_master(+0x14ed5)[0x560646236ed5]
[fv-az1215-453:04055] *** End of error message ***
</pre>
{% endraw %}
