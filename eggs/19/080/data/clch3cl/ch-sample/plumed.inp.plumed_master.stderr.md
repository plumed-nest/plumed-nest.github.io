**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:12930] *** Process received signal ***
[pkrvmberfyhpb9w:12930] Signal: Aborted (6)
[pkrvmberfyhpb9w:12930] Signal code:  (-6)
[pkrvmberfyhpb9w:12930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff674e45330]
[pkrvmberfyhpb9w:12930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff674e9eb2c]
[pkrvmberfyhpb9w:12930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff674e4527e]
[pkrvmberfyhpb9w:12930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff674e288ff]
[pkrvmberfyhpb9w:12930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6752a5ff5]
[pkrvmberfyhpb9w:12930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6752bb0da]
[pkrvmberfyhpb9w:12930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6752a5a55]
[pkrvmberfyhpb9w:12930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6752a5a6f]
[pkrvmberfyhpb9w:12930] [ 8] plumed_master(+0x146dd)[0x555a9e0836dd]
[pkrvmberfyhpb9w:12930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff674e2a1ca]
[pkrvmberfyhpb9w:12930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff674e2a28b]
[pkrvmberfyhpb9w:12930] [11] plumed_master(+0x15365)[0x555a9e084365]
[pkrvmberfyhpb9w:12930] *** End of error message ***
</pre>
{% endraw %}
