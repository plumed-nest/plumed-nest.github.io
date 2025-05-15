**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @94 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08596] *** Process received signal ***
[pkrvmberfyhpb9w:08596] Signal: Aborted (6)
[pkrvmberfyhpb9w:08596] Signal code:  (-6)
[pkrvmberfyhpb9w:08596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e89845330]
[pkrvmberfyhpb9w:08596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e8989eb2c]
[pkrvmberfyhpb9w:08596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e8984527e]
[pkrvmberfyhpb9w:08596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e898288ff]
[pkrvmberfyhpb9w:08596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e89ca5ff5]
[pkrvmberfyhpb9w:08596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e89cbb0da]
[pkrvmberfyhpb9w:08596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e89ca5a55]
[pkrvmberfyhpb9w:08596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e89ca5a6f]
[pkrvmberfyhpb9w:08596] [ 8] plumed_master(+0x146dd)[0x55dbb014b6dd]
[pkrvmberfyhpb9w:08596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e8982a1ca]
[pkrvmberfyhpb9w:08596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e8982a28b]
[pkrvmberfyhpb9w:08596] [11] plumed_master(+0x15365)[0x55dbb014c365]
[pkrvmberfyhpb9w:08596] *** End of error message ***
</pre>
{% endraw %}
