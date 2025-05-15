**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:12108] *** Process received signal ***
[pkrvmberfyhpb9w:12108] Signal: Aborted (6)
[pkrvmberfyhpb9w:12108] Signal code:  (-6)
[pkrvmberfyhpb9w:12108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb8ea45330]
[pkrvmberfyhpb9w:12108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb8ea9eb2c]
[pkrvmberfyhpb9w:12108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb8ea4527e]
[pkrvmberfyhpb9w:12108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb8ea288ff]
[pkrvmberfyhpb9w:12108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb8eea5ff5]
[pkrvmberfyhpb9w:12108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb8eebb0da]
[pkrvmberfyhpb9w:12108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb8eea5a55]
[pkrvmberfyhpb9w:12108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb8eea5a6f]
[pkrvmberfyhpb9w:12108] [ 8] plumed_master(+0x146dd)[0x55fb28e976dd]
[pkrvmberfyhpb9w:12108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb8ea2a1ca]
[pkrvmberfyhpb9w:12108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb8ea2a28b]
[pkrvmberfyhpb9w:12108] [11] plumed_master(+0x15365)[0x55fb28e98365]
[pkrvmberfyhpb9w:12108] *** End of error message ***
</pre>
{% endraw %}
