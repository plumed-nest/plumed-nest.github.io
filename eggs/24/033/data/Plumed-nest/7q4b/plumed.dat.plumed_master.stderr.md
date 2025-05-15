**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmberfyhpb9w:05579] *** Process received signal ***
[pkrvmberfyhpb9w:05579] Signal: Aborted (6)
[pkrvmberfyhpb9w:05579] Signal code:  (-6)
[pkrvmberfyhpb9w:05579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efccea45330]
[pkrvmberfyhpb9w:05579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efccea9eb2c]
[pkrvmberfyhpb9w:05579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efccea4527e]
[pkrvmberfyhpb9w:05579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efccea288ff]
[pkrvmberfyhpb9w:05579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcceea5ff5]
[pkrvmberfyhpb9w:05579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcceebb0da]
[pkrvmberfyhpb9w:05579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcceea5a55]
[pkrvmberfyhpb9w:05579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcceea5a6f]
[pkrvmberfyhpb9w:05579] [ 8] plumed_master(+0x146dd)[0x5635911326dd]
[pkrvmberfyhpb9w:05579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efccea2a1ca]
[pkrvmberfyhpb9w:05579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efccea2a28b]
[pkrvmberfyhpb9w:05579] [11] plumed_master(+0x15365)[0x563591133365]
[pkrvmberfyhpb9w:05579] *** End of error message ***
</pre>
{% endraw %}
