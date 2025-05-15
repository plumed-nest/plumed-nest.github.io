**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:12091] *** Process received signal ***
[pkrvmberfyhpb9w:12091] Signal: Aborted (6)
[pkrvmberfyhpb9w:12091] Signal code:  (-6)
[pkrvmberfyhpb9w:12091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe6fd645330]
[pkrvmberfyhpb9w:12091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe6fd69eb2c]
[pkrvmberfyhpb9w:12091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe6fd64527e]
[pkrvmberfyhpb9w:12091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6fd6288ff]
[pkrvmberfyhpb9w:12091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6fdaa5ff5]
[pkrvmberfyhpb9w:12091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6fdabb0da]
[pkrvmberfyhpb9w:12091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6fdaa5a55]
[pkrvmberfyhpb9w:12091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6fdaa5a6f]
[pkrvmberfyhpb9w:12091] [ 8] plumed(+0x146dd)[0x562f4d27a6dd]
[pkrvmberfyhpb9w:12091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe6fd62a1ca]
[pkrvmberfyhpb9w:12091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe6fd62a28b]
[pkrvmberfyhpb9w:12091] [11] plumed(+0x15365)[0x562f4d27b365]
[pkrvmberfyhpb9w:12091] *** End of error message ***
</pre>
{% endraw %}
