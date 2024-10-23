**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1215-275:08613] *** Process received signal ***
[fv-az1215-275:08613] Signal: Aborted (6)
[fv-az1215-275:08613] Signal code:  (-6)
[fv-az1215-275:08613] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5d41e42520]
[fv-az1215-275:08613] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5d41e969fc]
[fv-az1215-275:08613] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5d41e42476]
[fv-az1215-275:08613] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5d41e287f3]
[fv-az1215-275:08613] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5d422a2b9e]
[fv-az1215-275:08613] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5d422ae20c]
[fv-az1215-275:08613] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5d422ae277]
[fv-az1215-275:08613] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5d422ae52b]
[fv-az1215-275:08613] [ 8] plumed_master(+0x14254)[0x561cbcad1254]
[fv-az1215-275:08613] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5d41e29d90]
[fv-az1215-275:08613] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5d41e29e40]
[fv-az1215-275:08613] [11] plumed_master(+0x14eb5)[0x561cbcad1eb5]
[fv-az1215-275:08613] *** End of error message ***
</pre>
{% endraw %}
