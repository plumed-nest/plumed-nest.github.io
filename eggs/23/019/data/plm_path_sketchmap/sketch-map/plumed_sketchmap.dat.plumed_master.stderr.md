**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07257] *** Process received signal ***
[pkrvmberfyhpb9w:07257] Signal: Aborted (6)
[pkrvmberfyhpb9w:07257] Signal code:  (-6)
[pkrvmberfyhpb9w:07257] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a61045330]
[pkrvmberfyhpb9w:07257] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a6109eb2c]
[pkrvmberfyhpb9w:07257] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a6104527e]
[pkrvmberfyhpb9w:07257] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a610288ff]
[pkrvmberfyhpb9w:07257] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a614a5ff5]
[pkrvmberfyhpb9w:07257] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a614bb0da]
[pkrvmberfyhpb9w:07257] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a614a5a55]
[pkrvmberfyhpb9w:07257] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a614a5a6f]
[pkrvmberfyhpb9w:07257] [ 8] plumed_master(+0x146dd)[0x56380aebf6dd]
[pkrvmberfyhpb9w:07257] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a6102a1ca]
[pkrvmberfyhpb9w:07257] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a6102a28b]
[pkrvmberfyhpb9w:07257] [11] plumed_master(+0x15365)[0x56380aec0365]
[pkrvmberfyhpb9w:07257] *** End of error message ***
</pre>
{% endraw %}
