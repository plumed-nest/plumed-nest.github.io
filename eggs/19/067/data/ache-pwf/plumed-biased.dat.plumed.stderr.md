**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1108-992:73384] *** Process received signal ***
[fv-az1108-992:73384] Signal: Aborted (6)
[fv-az1108-992:73384] Signal code:  (-6)
[fv-az1108-992:73384] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd4c6642520]
[fv-az1108-992:73384] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd4c66969fc]
[fv-az1108-992:73384] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd4c6642476]
[fv-az1108-992:73384] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd4c66287f3]
[fv-az1108-992:73384] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd4c6aa4f26]
[fv-az1108-992:73384] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd4c6ab6d9c]
[fv-az1108-992:73384] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd4c6ab6e07]
[fv-az1108-992:73384] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd4c6ab70bb]
[fv-az1108-992:73384] [ 8] plumed(+0x12f48)[0x562b1124ef48]
[fv-az1108-992:73384] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd4c6629d90]
[fv-az1108-992:73384] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd4c6629e40]
[fv-az1108-992:73384] [11] plumed(+0x131e5)[0x562b1124f1e5]
[fv-az1108-992:73384] *** End of error message ***
</pre>
{% endraw %}
