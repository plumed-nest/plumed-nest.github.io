**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1567-223:09501] *** Process received signal ***
[fv-az1567-223:09501] Signal: Aborted (6)
[fv-az1567-223:09501] Signal code:  (-6)
[fv-az1567-223:09501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0e7a642520]
[fv-az1567-223:09501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0e7a6969fc]
[fv-az1567-223:09501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0e7a642476]
[fv-az1567-223:09501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0e7a6287f3]
[fv-az1567-223:09501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0e7aaa2b9e]
[fv-az1567-223:09501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0e7aaae20c]
[fv-az1567-223:09501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0e7aaae277]
[fv-az1567-223:09501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0e7aaae52b]
[fv-az1567-223:09501] [ 8] plumed_master(+0x14274)[0x55897fb78274]
[fv-az1567-223:09501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0e7a629d90]
[fv-az1567-223:09501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0e7a629e40]
[fv-az1567-223:09501] [11] plumed_master(+0x14ed5)[0x55897fb78ed5]
[fv-az1567-223:09501] *** End of error message ***
</pre>
{% endraw %}
