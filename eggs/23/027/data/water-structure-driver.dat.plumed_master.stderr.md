**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az1215-275:05551] *** Process received signal ***
[fv-az1215-275:05551] Signal: Aborted (6)
[fv-az1215-275:05551] Signal code:  (-6)
[fv-az1215-275:05551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f675a442520]
[fv-az1215-275:05551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f675a4969fc]
[fv-az1215-275:05551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f675a442476]
[fv-az1215-275:05551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f675a4287f3]
[fv-az1215-275:05551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f675a8a2b9e]
[fv-az1215-275:05551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f675a8ae20c]
[fv-az1215-275:05551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f675a8ae277]
[fv-az1215-275:05551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f675a8ae52b]
[fv-az1215-275:05551] [ 8] plumed_master(+0x14254)[0x5574f7167254]
[fv-az1215-275:05551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f675a429d90]
[fv-az1215-275:05551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f675a429e40]
[fv-az1215-275:05551] [11] plumed_master(+0x14eb5)[0x5574f7167eb5]
[fv-az1215-275:05551] *** End of error message ***
</pre>
{% endraw %}
