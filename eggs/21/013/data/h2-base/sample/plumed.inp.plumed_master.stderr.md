**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[fv-az802-461:09772] *** Process received signal ***
[fv-az802-461:09772] Signal: Aborted (6)
[fv-az802-461:09772] Signal code:  (-6)
[fv-az802-461:09772] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1c07242520]
[fv-az802-461:09772] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1c072969fc]
[fv-az802-461:09772] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1c07242476]
[fv-az802-461:09772] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1c072287f3]
[fv-az802-461:09772] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1c076a2b9e]
[fv-az802-461:09772] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1c076ae20c]
[fv-az802-461:09772] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1c076ae277]
[fv-az802-461:09772] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1c076ae52b]
[fv-az802-461:09772] [ 8] plumed_master(+0x14254)[0x563c11e61254]
[fv-az802-461:09772] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1c07229d90]
[fv-az802-461:09772] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1c07229e40]
[fv-az802-461:09772] [11] plumed_master(+0x14eb5)[0x563c11e61eb5]
[fv-az802-461:09772] *** End of error message ***
</pre>
{% endraw %}
