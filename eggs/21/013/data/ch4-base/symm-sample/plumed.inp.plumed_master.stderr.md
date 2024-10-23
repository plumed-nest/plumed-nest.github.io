**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az802-461:09212] *** Process received signal ***
[fv-az802-461:09212] Signal: Aborted (6)
[fv-az802-461:09212] Signal code:  (-6)
[fv-az802-461:09212] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8adbe42520]
[fv-az802-461:09212] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8adbe969fc]
[fv-az802-461:09212] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8adbe42476]
[fv-az802-461:09212] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8adbe287f3]
[fv-az802-461:09212] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8adc2a2b9e]
[fv-az802-461:09212] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8adc2ae20c]
[fv-az802-461:09212] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8adc2ae277]
[fv-az802-461:09212] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8adc2ae52b]
[fv-az802-461:09212] [ 8] plumed_master(+0x14254)[0x55588680e254]
[fv-az802-461:09212] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8adbe29d90]
[fv-az802-461:09212] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8adbe29e40]
[fv-az802-461:09212] [11] plumed_master(+0x14eb5)[0x55588680eeb5]
[fv-az802-461:09212] *** End of error message ***
</pre>
{% endraw %}
