**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:05860] *** Process received signal ***
[pkrvmberfyhpb9w:05860] Signal: Aborted (6)
[pkrvmberfyhpb9w:05860] Signal code:  (-6)
[pkrvmberfyhpb9w:05860] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f949ce45330]
[pkrvmberfyhpb9w:05860] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f949ce9eb2c]
[pkrvmberfyhpb9w:05860] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f949ce4527e]
[pkrvmberfyhpb9w:05860] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f949ce288ff]
[pkrvmberfyhpb9w:05860] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f949d2a5ff5]
[pkrvmberfyhpb9w:05860] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f949d2bb0da]
[pkrvmberfyhpb9w:05860] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f949d2a5a55]
[pkrvmberfyhpb9w:05860] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f949d2a5a6f]
[pkrvmberfyhpb9w:05860] [ 8] plumed_master(+0x146dd)[0x55593932a6dd]
[pkrvmberfyhpb9w:05860] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f949ce2a1ca]
[pkrvmberfyhpb9w:05860] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f949ce2a28b]
[pkrvmberfyhpb9w:05860] [11] plumed_master(+0x15365)[0x55593932b365]
[pkrvmberfyhpb9w:05860] *** End of error message ***
</pre>
{% endraw %}
