**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[fv-az1215-275:10949] *** Process received signal ***
[fv-az1215-275:10949] Signal: Aborted (6)
[fv-az1215-275:10949] Signal code:  (-6)
[fv-az1215-275:10949] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f01fba42520]
[fv-az1215-275:10949] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f01fba969fc]
[fv-az1215-275:10949] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f01fba42476]
[fv-az1215-275:10949] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f01fba287f3]
[fv-az1215-275:10949] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f01fbea2b9e]
[fv-az1215-275:10949] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f01fbeae20c]
[fv-az1215-275:10949] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f01fbeae277]
[fv-az1215-275:10949] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f01fbeae52b]
[fv-az1215-275:10949] [ 8] plumed_master(+0x14254)[0x560e23d4b254]
[fv-az1215-275:10949] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f01fba29d90]
[fv-az1215-275:10949] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f01fba29e40]
[fv-az1215-275:10949] [11] plumed_master(+0x14eb5)[0x560e23d4beb5]
[fv-az1215-275:10949] *** End of error message ***
</pre>
{% endraw %}
