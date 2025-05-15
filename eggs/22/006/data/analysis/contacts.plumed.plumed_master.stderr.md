**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08530] *** Process received signal ***
[pkrvmberfyhpb9w:08530] Signal: Aborted (6)
[pkrvmberfyhpb9w:08530] Signal code:  (-6)
[pkrvmberfyhpb9w:08530] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f31f2245330]
[pkrvmberfyhpb9w:08530] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f31f229eb2c]
[pkrvmberfyhpb9w:08530] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f31f224527e]
[pkrvmberfyhpb9w:08530] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31f22288ff]
[pkrvmberfyhpb9w:08530] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31f26a5ff5]
[pkrvmberfyhpb9w:08530] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31f26bb0da]
[pkrvmberfyhpb9w:08530] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31f26a5a55]
[pkrvmberfyhpb9w:08530] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31f26a5a6f]
[pkrvmberfyhpb9w:08530] [ 8] plumed_master(+0x146dd)[0x562a43c976dd]
[pkrvmberfyhpb9w:08530] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f31f222a1ca]
[pkrvmberfyhpb9w:08530] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f31f222a28b]
[pkrvmberfyhpb9w:08530] [11] plumed_master(+0x15365)[0x562a43c98365]
[pkrvmberfyhpb9w:08530] *** End of error message ***
</pre>
{% endraw %}
