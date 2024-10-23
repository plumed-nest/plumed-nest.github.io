**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1215-275:08525] *** Process received signal ***
[fv-az1215-275:08525] Signal: Aborted (6)
[fv-az1215-275:08525] Signal code:  (-6)
[fv-az1215-275:08525] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0b4ac42520]
[fv-az1215-275:08525] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0b4ac969fc]
[fv-az1215-275:08525] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0b4ac42476]
[fv-az1215-275:08525] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0b4ac287f3]
[fv-az1215-275:08525] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0b4b0a2b9e]
[fv-az1215-275:08525] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0b4b0ae20c]
[fv-az1215-275:08525] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0b4b0ae277]
[fv-az1215-275:08525] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0b4b0ae52b]
[fv-az1215-275:08525] [ 8] plumed_master(+0x14254)[0x5587e5f49254]
[fv-az1215-275:08525] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0b4ac29d90]
[fv-az1215-275:08525] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0b4ac29e40]
[fv-az1215-275:08525] [11] plumed_master(+0x14eb5)[0x5587e5f49eb5]
[fv-az1215-275:08525] *** End of error message ***
</pre>
{% endraw %}
