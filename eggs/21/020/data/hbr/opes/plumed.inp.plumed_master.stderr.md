**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/opes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1215-275:08676] *** Process received signal ***
[fv-az1215-275:08676] Signal: Aborted (6)
[fv-az1215-275:08676] Signal code:  (-6)
[fv-az1215-275:08676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3b15642520]
[fv-az1215-275:08676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3b156969fc]
[fv-az1215-275:08676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3b15642476]
[fv-az1215-275:08676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3b156287f3]
[fv-az1215-275:08676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3b15aa2b9e]
[fv-az1215-275:08676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3b15aae20c]
[fv-az1215-275:08676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3b15aae277]
[fv-az1215-275:08676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3b15aae52b]
[fv-az1215-275:08676] [ 8] plumed_master(+0x14254)[0x55f47bf8b254]
[fv-az1215-275:08676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3b15629d90]
[fv-az1215-275:08676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3b15629e40]
[fv-az1215-275:08676] [11] plumed_master(+0x14eb5)[0x55f47bf8beb5]
[fv-az1215-275:08676] *** End of error message ***
</pre>
{% endraw %}
