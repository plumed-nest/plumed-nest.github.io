**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1567-223:04661] *** Process received signal ***
[fv-az1567-223:04661] Signal: Aborted (6)
[fv-az1567-223:04661] Signal code:  (-6)
[fv-az1567-223:04661] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f953ec42520]
[fv-az1567-223:04661] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f953ec969fc]
[fv-az1567-223:04661] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f953ec42476]
[fv-az1567-223:04661] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f953ec287f3]
[fv-az1567-223:04661] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f953f0a2b9e]
[fv-az1567-223:04661] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f953f0ae20c]
[fv-az1567-223:04661] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f953f0ae277]
[fv-az1567-223:04661] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f953f0ae52b]
[fv-az1567-223:04661] [ 8] plumed(+0x12f48)[0x556f271b9f48]
[fv-az1567-223:04661] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f953ec29d90]
[fv-az1567-223:04661] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f953ec29e40]
[fv-az1567-223:04661] [11] plumed(+0x131e5)[0x556f271ba1e5]
[fv-az1567-223:04661] *** End of error message ***
</pre>
{% endraw %}
