**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1215-275:10980] *** Process received signal ***
[fv-az1215-275:10980] Signal: Aborted (6)
[fv-az1215-275:10980] Signal code:  (-6)
[fv-az1215-275:10980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0990e42520]
[fv-az1215-275:10980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0990e969fc]
[fv-az1215-275:10980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0990e42476]
[fv-az1215-275:10980] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0990e287f3]
[fv-az1215-275:10980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f09912a2b9e]
[fv-az1215-275:10980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f09912ae20c]
[fv-az1215-275:10980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f09912ae277]
[fv-az1215-275:10980] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f09912ae52b]
[fv-az1215-275:10980] [ 8] plumed_master(+0x14254)[0x55ea7638b254]
[fv-az1215-275:10980] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0990e29d90]
[fv-az1215-275:10980] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0990e29e40]
[fv-az1215-275:10980] [11] plumed_master(+0x14eb5)[0x55ea7638beb5]
[fv-az1215-275:10980] *** End of error message ***
</pre>
{% endraw %}
