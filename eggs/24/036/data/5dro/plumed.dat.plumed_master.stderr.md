**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @31 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:05721] *** Process received signal ***
[pkrvmberfyhpb9w:05721] Signal: Aborted (6)
[pkrvmberfyhpb9w:05721] Signal code:  (-6)
[pkrvmberfyhpb9w:05721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf4ee45330]
[pkrvmberfyhpb9w:05721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf4ee9eb2c]
[pkrvmberfyhpb9w:05721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf4ee4527e]
[pkrvmberfyhpb9w:05721] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf4ee288ff]
[pkrvmberfyhpb9w:05721] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf4f2a5ff5]
[pkrvmberfyhpb9w:05721] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf4f2bb0da]
[pkrvmberfyhpb9w:05721] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf4f2a5a55]
[pkrvmberfyhpb9w:05721] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf4f2a5a6f]
[pkrvmberfyhpb9w:05721] [ 8] plumed_master(+0x146dd)[0x5582b58c76dd]
[pkrvmberfyhpb9w:05721] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf4ee2a1ca]
[pkrvmberfyhpb9w:05721] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf4ee2a28b]
[pkrvmberfyhpb9w:05721] [11] plumed_master(+0x15365)[0x5582b58c8365]
[pkrvmberfyhpb9w:05721] *** End of error message ***
</pre>
{% endraw %}
