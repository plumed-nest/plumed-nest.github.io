**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:05899] *** Process received signal ***
[pkrvmberfyhpb9w:05899] Signal: Aborted (6)
[pkrvmberfyhpb9w:05899] Signal code:  (-6)
[pkrvmberfyhpb9w:05899] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea8e645330]
[pkrvmberfyhpb9w:05899] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea8e69eb2c]
[pkrvmberfyhpb9w:05899] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea8e64527e]
[pkrvmberfyhpb9w:05899] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea8e6288ff]
[pkrvmberfyhpb9w:05899] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea8eaa5ff5]
[pkrvmberfyhpb9w:05899] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea8eabb0da]
[pkrvmberfyhpb9w:05899] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea8eaa5a55]
[pkrvmberfyhpb9w:05899] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea8eaa5a6f]
[pkrvmberfyhpb9w:05899] [ 8] plumed_master(+0x146dd)[0x5648445dc6dd]
[pkrvmberfyhpb9w:05899] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea8e62a1ca]
[pkrvmberfyhpb9w:05899] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea8e62a28b]
[pkrvmberfyhpb9w:05899] [11] plumed_master(+0x15365)[0x5648445dd365]
[pkrvmberfyhpb9w:05899] *** End of error message ***
</pre>
{% endraw %}
