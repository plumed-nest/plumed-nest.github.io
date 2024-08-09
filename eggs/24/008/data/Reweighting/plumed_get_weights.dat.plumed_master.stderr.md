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
[fv-az1567-223:04638] *** Process received signal ***
[fv-az1567-223:04638] Signal: Aborted (6)
[fv-az1567-223:04638] Signal code:  (-6)
[fv-az1567-223:04638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5c8a842520]
[fv-az1567-223:04638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5c8a8969fc]
[fv-az1567-223:04638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5c8a842476]
[fv-az1567-223:04638] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5c8a8287f3]
[fv-az1567-223:04638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5c8aca2b9e]
[fv-az1567-223:04638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5c8acae20c]
[fv-az1567-223:04638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5c8acae277]
[fv-az1567-223:04638] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5c8acae52b]
[fv-az1567-223:04638] [ 8] plumed_master(+0x14274)[0x55ed5d2ce274]
[fv-az1567-223:04638] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5c8a829d90]
[fv-az1567-223:04638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5c8a829e40]
[fv-az1567-223:04638] [11] plumed_master(+0x14ed5)[0x55ed5d2ceed5]
[fv-az1567-223:04638] *** End of error message ***
</pre>
{% endraw %}
