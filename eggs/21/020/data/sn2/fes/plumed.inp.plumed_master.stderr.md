**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[fv-az1215-275:08464] *** Process received signal ***
[fv-az1215-275:08464] Signal: Aborted (6)
[fv-az1215-275:08464] Signal code:  (-6)
[fv-az1215-275:08464] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8e57042520]
[fv-az1215-275:08464] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8e570969fc]
[fv-az1215-275:08464] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8e57042476]
[fv-az1215-275:08464] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8e570287f3]
[fv-az1215-275:08464] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8e574a2b9e]
[fv-az1215-275:08464] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8e574ae20c]
[fv-az1215-275:08464] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8e574ae277]
[fv-az1215-275:08464] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8e574ae52b]
[fv-az1215-275:08464] [ 8] plumed_master(+0x14254)[0x55a398a03254]
[fv-az1215-275:08464] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8e57029d90]
[fv-az1215-275:08464] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8e57029e40]
[fv-az1215-275:08464] [11] plumed_master(+0x14eb5)[0x55a398a03eb5]
[fv-az1215-275:08464] *** End of error message ***
</pre>
{% endraw %}
