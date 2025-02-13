**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1657-925:07255] *** Process received signal ***
[fv-az1657-925:07255] Signal: Aborted (6)
[fv-az1657-925:07255] Signal code:  (-6)
[fv-az1657-925:07255] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c0f445330]
[fv-az1657-925:07255] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c0f49eb2c]
[fv-az1657-925:07255] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c0f44527e]
[fv-az1657-925:07255] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c0f4288ff]
[fv-az1657-925:07255] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c0f8a5ff5]
[fv-az1657-925:07255] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c0f8bb0da]
[fv-az1657-925:07255] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c0f8a5a55]
[fv-az1657-925:07255] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c0f8a5a6f]
[fv-az1657-925:07255] [ 8] plumed_master(+0x146dd)[0x563ec6b1a6dd]
[fv-az1657-925:07255] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c0f42a1ca]
[fv-az1657-925:07255] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c0f42a28b]
[fv-az1657-925:07255] [11] plumed_master(+0x15365)[0x563ec6b1b365]
[fv-az1657-925:07255] *** End of error message ***
</pre>
{% endraw %}
