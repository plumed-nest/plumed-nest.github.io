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
[runnervmmtnos:33276] *** Process received signal ***
[runnervmmtnos:33276] Signal: Aborted (6)
[runnervmmtnos:33276] Signal code:  (-6)
[runnervmmtnos:33276] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ac9845330]
[runnervmmtnos:33276] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ac989eb2c]
[runnervmmtnos:33276] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ac984527e]
[runnervmmtnos:33276] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ac98288ff]
[runnervmmtnos:33276] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ac9ca5ff5]
[runnervmmtnos:33276] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ac9cbb0da]
[runnervmmtnos:33276] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ac9ca5a55]
[runnervmmtnos:33276] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ac9ca5a6f]
[runnervmmtnos:33276] [ 8] plumed(+0x146dd)[0x55b80a5d66dd]
[runnervmmtnos:33276] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ac982a1ca]
[runnervmmtnos:33276] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ac982a28b]
[runnervmmtnos:33276] [11] plumed(+0x15365)[0x55b80a5d7365]
[runnervmmtnos:33276] *** End of error message ***
</pre>
{% endraw %}
