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
[pkrvmq0rgcvqdmg:07179] *** Process received signal ***
[pkrvmq0rgcvqdmg:07179] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07179] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07179] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfbdc45330]
[pkrvmq0rgcvqdmg:07179] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfbdc9eb2c]
[pkrvmq0rgcvqdmg:07179] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfbdc4527e]
[pkrvmq0rgcvqdmg:07179] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfbdc288ff]
[pkrvmq0rgcvqdmg:07179] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfbe0a5ff5]
[pkrvmq0rgcvqdmg:07179] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfbe0bb0da]
[pkrvmq0rgcvqdmg:07179] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfbe0a5a55]
[pkrvmq0rgcvqdmg:07179] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfbe0a5a6f]
[pkrvmq0rgcvqdmg:07179] [ 8] plumed(+0x146dd)[0x56324b57d6dd]
[pkrvmq0rgcvqdmg:07179] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfbdc2a1ca]
[pkrvmq0rgcvqdmg:07179] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfbdc2a28b]
[pkrvmq0rgcvqdmg:07179] [11] plumed(+0x15365)[0x56324b57e365]
[pkrvmq0rgcvqdmg:07179] *** End of error message ***
</pre>
{% endraw %}
