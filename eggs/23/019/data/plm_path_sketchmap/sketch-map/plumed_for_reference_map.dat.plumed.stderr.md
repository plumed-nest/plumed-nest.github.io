**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[pkrvmberfyhpb9w:07159] *** Process received signal ***
[pkrvmberfyhpb9w:07159] Signal: Aborted (6)
[pkrvmberfyhpb9w:07159] Signal code:  (-6)
[pkrvmberfyhpb9w:07159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b53045330]
[pkrvmberfyhpb9w:07159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b5309eb2c]
[pkrvmberfyhpb9w:07159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b5304527e]
[pkrvmberfyhpb9w:07159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b530288ff]
[pkrvmberfyhpb9w:07159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b534a5ff5]
[pkrvmberfyhpb9w:07159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b534bb0da]
[pkrvmberfyhpb9w:07159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b534a5a55]
[pkrvmberfyhpb9w:07159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b534a5a6f]
[pkrvmberfyhpb9w:07159] [ 8] plumed(+0x146dd)[0x558305cf26dd]
[pkrvmberfyhpb9w:07159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b5302a1ca]
[pkrvmberfyhpb9w:07159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b5302a28b]
[pkrvmberfyhpb9w:07159] [11] plumed(+0x15365)[0x558305cf3365]
[pkrvmberfyhpb9w:07159] *** End of error message ***
</pre>
{% endraw %}
