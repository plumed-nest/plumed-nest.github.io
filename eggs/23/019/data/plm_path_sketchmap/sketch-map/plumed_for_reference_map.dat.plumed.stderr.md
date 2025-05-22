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
[pkrvmf6wy0o8zjz:35645] *** Process received signal ***
[pkrvmf6wy0o8zjz:35645] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35645] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d16045330]
[pkrvmf6wy0o8zjz:35645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d1609eb2c]
[pkrvmf6wy0o8zjz:35645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d1604527e]
[pkrvmf6wy0o8zjz:35645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d160288ff]
[pkrvmf6wy0o8zjz:35645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d164a5ff5]
[pkrvmf6wy0o8zjz:35645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d164bb0da]
[pkrvmf6wy0o8zjz:35645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d164a5a55]
[pkrvmf6wy0o8zjz:35645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d164a5a6f]
[pkrvmf6wy0o8zjz:35645] [ 8] plumed(+0x146dd)[0x55e5061e26dd]
[pkrvmf6wy0o8zjz:35645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d1602a1ca]
[pkrvmf6wy0o8zjz:35645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d1602a28b]
[pkrvmf6wy0o8zjz:35645] [11] plumed(+0x15365)[0x55e5061e3365]
[pkrvmf6wy0o8zjz:35645] *** End of error message ***
</pre>
{% endraw %}
