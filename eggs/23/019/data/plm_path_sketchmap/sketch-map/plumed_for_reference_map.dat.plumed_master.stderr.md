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
[runnervmeorf1:06423] *** Process received signal ***
[runnervmeorf1:06423] Signal: Aborted (6)
[runnervmeorf1:06423] Signal code:  (-6)
[runnervmeorf1:06423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f072f045330]
[runnervmeorf1:06423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f072f09eb2c]
[runnervmeorf1:06423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f072f04527e]
[runnervmeorf1:06423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f072f0288ff]
[runnervmeorf1:06423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f072f4a5ff5]
[runnervmeorf1:06423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f072f4bb0da]
[runnervmeorf1:06423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f072f4a5a55]
[runnervmeorf1:06423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f072f4a5a6f]
[runnervmeorf1:06423] [ 8] plumed_master(+0x146dd)[0x5581101856dd]
[runnervmeorf1:06423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f072f02a1ca]
[runnervmeorf1:06423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f072f02a28b]
[runnervmeorf1:06423] [11] plumed_master(+0x15365)[0x558110186365]
[runnervmeorf1:06423] *** End of error message ***
</pre>
{% endraw %}
