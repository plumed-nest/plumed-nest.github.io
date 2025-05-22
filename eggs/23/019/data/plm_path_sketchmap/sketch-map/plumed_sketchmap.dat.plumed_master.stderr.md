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
[pkrvmf6wy0o8zjz:35739] *** Process received signal ***
[pkrvmf6wy0o8zjz:35739] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35739] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd93c645330]
[pkrvmf6wy0o8zjz:35739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd93c69eb2c]
[pkrvmf6wy0o8zjz:35739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd93c64527e]
[pkrvmf6wy0o8zjz:35739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd93c6288ff]
[pkrvmf6wy0o8zjz:35739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd93caa5ff5]
[pkrvmf6wy0o8zjz:35739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd93cabb0da]
[pkrvmf6wy0o8zjz:35739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd93caa5a55]
[pkrvmf6wy0o8zjz:35739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd93caa5a6f]
[pkrvmf6wy0o8zjz:35739] [ 8] plumed_master(+0x146dd)[0x55cf104376dd]
[pkrvmf6wy0o8zjz:35739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd93c62a1ca]
[pkrvmf6wy0o8zjz:35739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd93c62a28b]
[pkrvmf6wy0o8zjz:35739] [11] plumed_master(+0x15365)[0x55cf10438365]
[pkrvmf6wy0o8zjz:35739] *** End of error message ***
</pre>
{% endraw %}
