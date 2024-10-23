**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az802-461:04957] *** Process received signal ***
[fv-az802-461:04957] Signal: Aborted (6)
[fv-az802-461:04957] Signal code:  (-6)
[fv-az802-461:04957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6e3e242520]
[fv-az802-461:04957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6e3e2969fc]
[fv-az802-461:04957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6e3e242476]
[fv-az802-461:04957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6e3e2287f3]
[fv-az802-461:04957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6e3e6a2b9e]
[fv-az802-461:04957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6e3e6ae20c]
[fv-az802-461:04957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6e3e6ae277]
[fv-az802-461:04957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6e3e6ae52b]
[fv-az802-461:04957] [ 8] plumed_master(+0x14254)[0x563af5e10254]
[fv-az802-461:04957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6e3e229d90]
[fv-az802-461:04957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6e3e229e40]
[fv-az802-461:04957] [11] plumed_master(+0x14eb5)[0x563af5e10eb5]
[fv-az802-461:04957] *** End of error message ***
</pre>
{% endraw %}
