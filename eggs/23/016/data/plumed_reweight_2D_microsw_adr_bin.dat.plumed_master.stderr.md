**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az802-461:04924] *** Process received signal ***
[fv-az802-461:04924] Signal: Aborted (6)
[fv-az802-461:04924] Signal code:  (-6)
[fv-az802-461:04924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbbf6042520]
[fv-az802-461:04924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbbf60969fc]
[fv-az802-461:04924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbbf6042476]
[fv-az802-461:04924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbbf60287f3]
[fv-az802-461:04924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbbf64a2b9e]
[fv-az802-461:04924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbbf64ae20c]
[fv-az802-461:04924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbbf64ae277]
[fv-az802-461:04924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbbf64ae52b]
[fv-az802-461:04924] [ 8] plumed_master(+0x14254)[0x558508cf3254]
[fv-az802-461:04924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbbf6029d90]
[fv-az802-461:04924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbbf6029e40]
[fv-az802-461:04924] [11] plumed_master(+0x14eb5)[0x558508cf3eb5]
[fv-az802-461:04924] *** End of error message ***
</pre>
{% endraw %}
