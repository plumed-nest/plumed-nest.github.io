**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @103 : keyword ARG is compulsory for this action
[fv-az775-215:06385] *** Process received signal ***
[fv-az775-215:06385] Signal: Aborted (6)
[fv-az775-215:06385] Signal code:  (-6)
[fv-az775-215:06385] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb07b642520]
[fv-az775-215:06385] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb07b6969fc]
[fv-az775-215:06385] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb07b642476]
[fv-az775-215:06385] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb07b6287f3]
[fv-az775-215:06385] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb07baa2b9e]
[fv-az775-215:06385] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb07baae20c]
[fv-az775-215:06385] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb07baae277]
[fv-az775-215:06385] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb07baae52b]
[fv-az775-215:06385] [ 8] plumed_master(+0x14254)[0x55d6f05a6254]
[fv-az775-215:06385] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb07b629d90]
[fv-az775-215:06385] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb07b629e40]
[fv-az775-215:06385] [11] plumed_master(+0x14eb5)[0x55d6f05a6eb5]
[fv-az775-215:06385] *** End of error message ***
</pre>
{% endraw %}
