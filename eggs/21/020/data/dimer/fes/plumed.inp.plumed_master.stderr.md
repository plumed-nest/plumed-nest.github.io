**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1215-275:08404] *** Process received signal ***
[fv-az1215-275:08404] Signal: Aborted (6)
[fv-az1215-275:08404] Signal code:  (-6)
[fv-az1215-275:08404] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5361e42520]
[fv-az1215-275:08404] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5361e969fc]
[fv-az1215-275:08404] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5361e42476]
[fv-az1215-275:08404] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5361e287f3]
[fv-az1215-275:08404] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f53622a2b9e]
[fv-az1215-275:08404] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f53622ae20c]
[fv-az1215-275:08404] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f53622ae277]
[fv-az1215-275:08404] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f53622ae52b]
[fv-az1215-275:08404] [ 8] plumed_master(+0x14254)[0x55f41ecbd254]
[fv-az1215-275:08404] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5361e29d90]
[fv-az1215-275:08404] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5361e29e40]
[fv-az1215-275:08404] [11] plumed_master(+0x14eb5)[0x55f41ecbdeb5]
[fv-az1215-275:08404] *** End of error message ***
</pre>
{% endraw %}
