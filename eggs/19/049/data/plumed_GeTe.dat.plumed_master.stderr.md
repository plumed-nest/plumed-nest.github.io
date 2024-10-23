**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1215-275:10919] *** Process received signal ***
[fv-az1215-275:10919] Signal: Aborted (6)
[fv-az1215-275:10919] Signal code:  (-6)
[fv-az1215-275:10919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff23ba42520]
[fv-az1215-275:10919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff23ba969fc]
[fv-az1215-275:10919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff23ba42476]
[fv-az1215-275:10919] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff23ba287f3]
[fv-az1215-275:10919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff23bea2b9e]
[fv-az1215-275:10919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff23beae20c]
[fv-az1215-275:10919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff23beae277]
[fv-az1215-275:10919] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff23beae52b]
[fv-az1215-275:10919] [ 8] plumed_master(+0x14254)[0x55a57d5eb254]
[fv-az1215-275:10919] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff23ba29d90]
[fv-az1215-275:10919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff23ba29e40]
[fv-az1215-275:10919] [11] plumed_master(+0x14eb5)[0x55a57d5ebeb5]
[fv-az1215-275:10919] *** End of error message ***
</pre>
{% endraw %}
