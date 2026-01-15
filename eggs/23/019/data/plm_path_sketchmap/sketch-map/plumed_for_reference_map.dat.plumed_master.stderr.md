**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmmtnos:33292] *** Process received signal ***
[runnervmmtnos:33292] Signal: Aborted (6)
[runnervmmtnos:33292] Signal code:  (-6)
[runnervmmtnos:33292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b58e45330]
[runnervmmtnos:33292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b58e9eb2c]
[runnervmmtnos:33292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b58e4527e]
[runnervmmtnos:33292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b58e288ff]
[runnervmmtnos:33292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b592a5ff5]
[runnervmmtnos:33292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b592bb0da]
[runnervmmtnos:33292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b592a5a55]
[runnervmmtnos:33292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b592a5a6f]
[runnervmmtnos:33292] [ 8] plumed_master(+0x146dd)[0x55978635b6dd]
[runnervmmtnos:33292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b58e2a1ca]
[runnervmmtnos:33292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b58e2a28b]
[runnervmmtnos:33292] [11] plumed_master(+0x15365)[0x55978635c365]
[runnervmmtnos:33292] *** End of error message ***
</pre>
{% endraw %}
