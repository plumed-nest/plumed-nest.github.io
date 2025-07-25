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
[pkrvmpptgkbjq6m:07913] *** Process received signal ***
[pkrvmpptgkbjq6m:07913] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07913] Signal code:  (-6)
[pkrvmpptgkbjq6m:07913] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb17a445330]
[pkrvmpptgkbjq6m:07913] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb17a49eb2c]
[pkrvmpptgkbjq6m:07913] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb17a44527e]
[pkrvmpptgkbjq6m:07913] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb17a4288ff]
[pkrvmpptgkbjq6m:07913] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb17a8a5ff5]
[pkrvmpptgkbjq6m:07913] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb17a8bb0da]
[pkrvmpptgkbjq6m:07913] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb17a8a5a55]
[pkrvmpptgkbjq6m:07913] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb17a8a5a6f]
[pkrvmpptgkbjq6m:07913] [ 8] plumed(+0x146dd)[0x55fabf5216dd]
[pkrvmpptgkbjq6m:07913] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb17a42a1ca]
[pkrvmpptgkbjq6m:07913] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb17a42a28b]
[pkrvmpptgkbjq6m:07913] [11] plumed(+0x15365)[0x55fabf522365]
[pkrvmpptgkbjq6m:07913] *** End of error message ***
</pre>
{% endraw %}
