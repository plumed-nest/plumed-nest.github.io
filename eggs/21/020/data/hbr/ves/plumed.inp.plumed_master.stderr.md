**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1215-275:08645] *** Process received signal ***
[fv-az1215-275:08645] Signal: Aborted (6)
[fv-az1215-275:08645] Signal code:  (-6)
[fv-az1215-275:08645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f21c3442520]
[fv-az1215-275:08645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f21c34969fc]
[fv-az1215-275:08645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f21c3442476]
[fv-az1215-275:08645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f21c34287f3]
[fv-az1215-275:08645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f21c38a2b9e]
[fv-az1215-275:08645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f21c38ae20c]
[fv-az1215-275:08645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f21c38ae277]
[fv-az1215-275:08645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f21c38ae52b]
[fv-az1215-275:08645] [ 8] plumed_master(+0x14254)[0x55c361bee254]
[fv-az1215-275:08645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f21c3429d90]
[fv-az1215-275:08645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f21c3429e40]
[fv-az1215-275:08645] [11] plumed_master(+0x14eb5)[0x55c361beeeb5]
[fv-az1215-275:08645] *** End of error message ***
</pre>
{% endraw %}