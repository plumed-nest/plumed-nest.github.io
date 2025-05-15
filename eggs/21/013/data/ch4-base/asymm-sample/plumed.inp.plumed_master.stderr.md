**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:11175] *** Process received signal ***
[pkrvmberfyhpb9w:11175] Signal: Aborted (6)
[pkrvmberfyhpb9w:11175] Signal code:  (-6)
[pkrvmberfyhpb9w:11175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff03be45330]
[pkrvmberfyhpb9w:11175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff03be9eb2c]
[pkrvmberfyhpb9w:11175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff03be4527e]
[pkrvmberfyhpb9w:11175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff03be288ff]
[pkrvmberfyhpb9w:11175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff03c2a5ff5]
[pkrvmberfyhpb9w:11175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff03c2bb0da]
[pkrvmberfyhpb9w:11175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff03c2a5a55]
[pkrvmberfyhpb9w:11175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff03c2a5a6f]
[pkrvmberfyhpb9w:11175] [ 8] plumed_master(+0x146dd)[0x55be250276dd]
[pkrvmberfyhpb9w:11175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff03be2a1ca]
[pkrvmberfyhpb9w:11175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff03be2a28b]
[pkrvmberfyhpb9w:11175] [11] plumed_master(+0x15365)[0x55be25028365]
[pkrvmberfyhpb9w:11175] *** End of error message ***
</pre>
{% endraw %}
