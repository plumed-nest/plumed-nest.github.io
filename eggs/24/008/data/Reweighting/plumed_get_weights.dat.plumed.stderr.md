**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1567-223:04630] *** Process received signal ***
[fv-az1567-223:04630] Signal: Aborted (6)
[fv-az1567-223:04630] Signal code:  (-6)
[fv-az1567-223:04630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc818a42520]
[fv-az1567-223:04630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc818a969fc]
[fv-az1567-223:04630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc818a42476]
[fv-az1567-223:04630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc818a287f3]
[fv-az1567-223:04630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc818ea2b9e]
[fv-az1567-223:04630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc818eae20c]
[fv-az1567-223:04630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc818eae277]
[fv-az1567-223:04630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc818eae52b]
[fv-az1567-223:04630] [ 8] plumed(+0x12f48)[0x556f12f10f48]
[fv-az1567-223:04630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc818a29d90]
[fv-az1567-223:04630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc818a29e40]
[fv-az1567-223:04630] [11] plumed(+0x131e5)[0x556f12f111e5]
[fv-az1567-223:04630] *** End of error message ***
</pre>
{% endraw %}
