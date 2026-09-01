**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmgx7h7:06090] *** Process received signal ***
[runnervmgx7h7:06090] Signal: Aborted (6)
[runnervmgx7h7:06090] Signal code:  (-6)
[runnervmgx7h7:06090] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67fa445330]
[runnervmgx7h7:06090] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67fa49ec0c]
[runnervmgx7h7:06090] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67fa44527e]
[runnervmgx7h7:06090] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67fa4288ff]
[runnervmgx7h7:06090] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67fa8a5ff5]
[runnervmgx7h7:06090] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67fa8bb0da]
[runnervmgx7h7:06090] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67fa8a5a55]
[runnervmgx7h7:06090] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67fa8a5a6f]
[runnervmgx7h7:06090] [ 8] plumed_master(+0x146dd)[0x55d9a6fbd6dd]
[runnervmgx7h7:06090] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67fa42a1ca]
[runnervmgx7h7:06090] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67fa42a28b]
[runnervmgx7h7:06090] [11] plumed_master(+0x15365)[0x55d9a6fbe365]
[runnervmgx7h7:06090] *** End of error message ***
</pre>
{% endraw %}
