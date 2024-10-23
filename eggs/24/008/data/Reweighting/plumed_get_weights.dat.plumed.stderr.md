**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1215-275:05081] *** Process received signal ***
[fv-az1215-275:05081] Signal: Aborted (6)
[fv-az1215-275:05081] Signal code:  (-6)
[fv-az1215-275:05081] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f12e2a42520]
[fv-az1215-275:05081] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f12e2a969fc]
[fv-az1215-275:05081] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f12e2a42476]
[fv-az1215-275:05081] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f12e2a287f3]
[fv-az1215-275:05081] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f12e2ea2b9e]
[fv-az1215-275:05081] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f12e2eae20c]
[fv-az1215-275:05081] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f12e2eae277]
[fv-az1215-275:05081] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f12e2eae52b]
[fv-az1215-275:05081] [ 8] plumed(+0x14254)[0x55ef0c568254]
[fv-az1215-275:05081] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f12e2a29d90]
[fv-az1215-275:05081] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f12e2a29e40]
[fv-az1215-275:05081] [11] plumed(+0x14eb5)[0x55ef0c568eb5]
[fv-az1215-275:05081] *** End of error message ***
</pre>
{% endraw %}
