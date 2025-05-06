**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az807-718:62576] *** Process received signal ***
[fv-az807-718:62576] Signal: Aborted (6)
[fv-az807-718:62576] Signal code:  (-6)
[fv-az807-718:62576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f78bd445330]
[fv-az807-718:62576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f78bd49eb2c]
[fv-az807-718:62576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f78bd44527e]
[fv-az807-718:62576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f78bd4288ff]
[fv-az807-718:62576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f78bd8a5ff5]
[fv-az807-718:62576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f78bd8bb0da]
[fv-az807-718:62576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f78bd8a5a55]
[fv-az807-718:62576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f78bd8a5a6f]
[fv-az807-718:62576] [ 8] plumed_master(+0x146dd)[0x5619dfa896dd]
[fv-az807-718:62576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f78bd42a1ca]
[fv-az807-718:62576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f78bd42a28b]
[fv-az807-718:62576] [11] plumed_master(+0x15365)[0x5619dfa8a365]
[fv-az807-718:62576] *** End of error message ***
</pre>
{% endraw %}
