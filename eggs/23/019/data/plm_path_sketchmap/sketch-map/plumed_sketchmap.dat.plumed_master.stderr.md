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
[pkrvmf6wy0o8zjz:64275] *** Process received signal ***
[pkrvmf6wy0o8zjz:64275] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64275] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f935ba45330]
[pkrvmf6wy0o8zjz:64275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f935ba9eb2c]
[pkrvmf6wy0o8zjz:64275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f935ba4527e]
[pkrvmf6wy0o8zjz:64275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f935ba288ff]
[pkrvmf6wy0o8zjz:64275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f935bea5ff5]
[pkrvmf6wy0o8zjz:64275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f935bebb0da]
[pkrvmf6wy0o8zjz:64275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f935bea5a55]
[pkrvmf6wy0o8zjz:64275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f935bea5a6f]
[pkrvmf6wy0o8zjz:64275] [ 8] plumed_master(+0x146dd)[0x56041c0076dd]
[pkrvmf6wy0o8zjz:64275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f935ba2a1ca]
[pkrvmf6wy0o8zjz:64275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f935ba2a28b]
[pkrvmf6wy0o8zjz:64275] [11] plumed_master(+0x15365)[0x56041c008365]
[pkrvmf6wy0o8zjz:64275] *** End of error message ***
</pre>
{% endraw %}
