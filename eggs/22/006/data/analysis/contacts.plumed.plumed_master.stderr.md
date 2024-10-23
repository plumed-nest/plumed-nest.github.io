**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[fv-az775-215:06325] *** Process received signal ***
[fv-az775-215:06325] Signal: Aborted (6)
[fv-az775-215:06325] Signal code:  (-6)
[fv-az775-215:06325] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fcbb6042520]
[fv-az775-215:06325] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fcbb60969fc]
[fv-az775-215:06325] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fcbb6042476]
[fv-az775-215:06325] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fcbb60287f3]
[fv-az775-215:06325] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fcbb64a2b9e]
[fv-az775-215:06325] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fcbb64ae20c]
[fv-az775-215:06325] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fcbb64ae277]
[fv-az775-215:06325] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fcbb64ae52b]
[fv-az775-215:06325] [ 8] plumed_master(+0x14254)[0x564fc2fe7254]
[fv-az775-215:06325] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fcbb6029d90]
[fv-az775-215:06325] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fcbb6029e40]
[fv-az775-215:06325] [11] plumed_master(+0x14eb5)[0x564fc2fe7eb5]
[fv-az775-215:06325] *** End of error message ***
</pre>
{% endraw %}
