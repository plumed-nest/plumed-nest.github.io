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
[pkrvmxyh4eaekms:08288] *** Process received signal ***
[pkrvmxyh4eaekms:08288] Signal: Aborted (6)
[pkrvmxyh4eaekms:08288] Signal code:  (-6)
[pkrvmxyh4eaekms:08288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d9f445330]
[pkrvmxyh4eaekms:08288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d9f49eb2c]
[pkrvmxyh4eaekms:08288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d9f44527e]
[pkrvmxyh4eaekms:08288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d9f4288ff]
[pkrvmxyh4eaekms:08288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d9f8a5ff5]
[pkrvmxyh4eaekms:08288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d9f8bb0da]
[pkrvmxyh4eaekms:08288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d9f8a5a55]
[pkrvmxyh4eaekms:08288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d9f8a5a6f]
[pkrvmxyh4eaekms:08288] [ 8] plumed(+0x146dd)[0x5602abbc96dd]
[pkrvmxyh4eaekms:08288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d9f42a1ca]
[pkrvmxyh4eaekms:08288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d9f42a28b]
[pkrvmxyh4eaekms:08288] [11] plumed(+0x15365)[0x5602abbca365]
[pkrvmxyh4eaekms:08288] *** End of error message ***
</pre>
{% endraw %}
