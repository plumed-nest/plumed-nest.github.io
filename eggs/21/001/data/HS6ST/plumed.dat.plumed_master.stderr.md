**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:11528] *** Process received signal ***
[pkrvmberfyhpb9w:11528] Signal: Aborted (6)
[pkrvmberfyhpb9w:11528] Signal code:  (-6)
[pkrvmberfyhpb9w:11528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95b4e45330]
[pkrvmberfyhpb9w:11528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95b4e9eb2c]
[pkrvmberfyhpb9w:11528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95b4e4527e]
[pkrvmberfyhpb9w:11528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95b4e288ff]
[pkrvmberfyhpb9w:11528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95b52a5ff5]
[pkrvmberfyhpb9w:11528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95b52bb0da]
[pkrvmberfyhpb9w:11528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95b52a5a55]
[pkrvmberfyhpb9w:11528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95b52a5a6f]
[pkrvmberfyhpb9w:11528] [ 8] plumed_master(+0x146dd)[0x558520f596dd]
[pkrvmberfyhpb9w:11528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95b4e2a1ca]
[pkrvmberfyhpb9w:11528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95b4e2a28b]
[pkrvmberfyhpb9w:11528] [11] plumed_master(+0x15365)[0x558520f5a365]
[pkrvmberfyhpb9w:11528] *** End of error message ***
</pre>
{% endraw %}
