**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1215-275:05114] *** Process received signal ***
[fv-az1215-275:05114] Signal: Aborted (6)
[fv-az1215-275:05114] Signal code:  (-6)
[fv-az1215-275:05114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f62a0442520]
[fv-az1215-275:05114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f62a04969fc]
[fv-az1215-275:05114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f62a0442476]
[fv-az1215-275:05114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f62a04287f3]
[fv-az1215-275:05114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f62a08a2b9e]
[fv-az1215-275:05114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f62a08ae20c]
[fv-az1215-275:05114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f62a08ae277]
[fv-az1215-275:05114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f62a08ae52b]
[fv-az1215-275:05114] [ 8] plumed(+0x14254)[0x5588a0ed7254]
[fv-az1215-275:05114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f62a0429d90]
[fv-az1215-275:05114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f62a0429e40]
[fv-az1215-275:05114] [11] plumed(+0x14eb5)[0x5588a0ed7eb5]
[fv-az1215-275:05114] *** End of error message ***
</pre>
{% endraw %}
