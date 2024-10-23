**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[fv-az802-461:08846] *** Process received signal ***
[fv-az802-461:08846] Signal: Aborted (6)
[fv-az802-461:08846] Signal code:  (-6)
[fv-az802-461:08846] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7855642520]
[fv-az802-461:08846] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f78556969fc]
[fv-az802-461:08846] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7855642476]
[fv-az802-461:08846] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f78556287f3]
[fv-az802-461:08846] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7855aa2b9e]
[fv-az802-461:08846] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7855aae20c]
[fv-az802-461:08846] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7855aae277]
[fv-az802-461:08846] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7855aae52b]
[fv-az802-461:08846] [ 8] plumed_master(+0x14254)[0x55a203118254]
[fv-az802-461:08846] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7855629d90]
[fv-az802-461:08846] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7855629e40]
[fv-az802-461:08846] [11] plumed_master(+0x14eb5)[0x55a203118eb5]
[fv-az802-461:08846] *** End of error message ***
</pre>
{% endraw %}
