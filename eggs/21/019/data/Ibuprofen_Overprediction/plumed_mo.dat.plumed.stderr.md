**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE with label @0 : Number of specified atoms should be 2
[fv-az1272-851:09337] *** Process received signal ***
[fv-az1272-851:09337] Signal: Aborted (6)
[fv-az1272-851:09337] Signal code:  (-6)
[fv-az1272-851:09337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0cc5642520]
[fv-az1272-851:09337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0cc56969fc]
[fv-az1272-851:09337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0cc5642476]
[fv-az1272-851:09337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0cc56287f3]
[fv-az1272-851:09337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0cc5aa2b9e]
[fv-az1272-851:09337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0cc5aae20c]
[fv-az1272-851:09337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0cc5aae277]
[fv-az1272-851:09337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0cc5aae52b]
[fv-az1272-851:09337] [ 8] plumed(+0x12f48)[0x559defeb0f48]
[fv-az1272-851:09337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0cc5629d90]
[fv-az1272-851:09337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0cc5629e40]
[fv-az1272-851:09337] [11] plumed(+0x131e5)[0x559defeb11e5]
[fv-az1272-851:09337] *** End of error message ***
</pre>
{% endraw %}
