**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1215-275:10972] *** Process received signal ***
[fv-az1215-275:10972] Signal: Aborted (6)
[fv-az1215-275:10972] Signal code:  (-6)
[fv-az1215-275:10972] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1418642520]
[fv-az1215-275:10972] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f14186969fc]
[fv-az1215-275:10972] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1418642476]
[fv-az1215-275:10972] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f14186287f3]
[fv-az1215-275:10972] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1418aa2b9e]
[fv-az1215-275:10972] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1418aae20c]
[fv-az1215-275:10972] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1418aae277]
[fv-az1215-275:10972] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1418aae52b]
[fv-az1215-275:10972] [ 8] plumed(+0x14254)[0x55d852fc2254]
[fv-az1215-275:10972] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1418629d90]
[fv-az1215-275:10972] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1418629e40]
[fv-az1215-275:10972] [11] plumed(+0x14eb5)[0x55d852fc2eb5]
[fv-az1215-275:10972] *** End of error message ***
</pre>
{% endraw %}
