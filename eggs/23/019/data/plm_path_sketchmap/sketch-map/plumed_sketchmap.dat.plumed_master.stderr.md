**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmvrwv9:07916] *** Process received signal ***
[runnervmvrwv9:07916] Signal: Aborted (6)
[runnervmvrwv9:07916] Signal code:  (-6)
[runnervmvrwv9:07916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b6a645330]
[runnervmvrwv9:07916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b6a69eb2c]
[runnervmvrwv9:07916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b6a64527e]
[runnervmvrwv9:07916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b6a6288ff]
[runnervmvrwv9:07916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b6aaa5ff5]
[runnervmvrwv9:07916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b6aabb0da]
[runnervmvrwv9:07916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b6aaa5a55]
[runnervmvrwv9:07916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b6aaa5a6f]
[runnervmvrwv9:07916] [ 8] plumed_master(+0x146dd)[0x561d0a31f6dd]
[runnervmvrwv9:07916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b6a62a1ca]
[runnervmvrwv9:07916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b6a62a28b]
[runnervmvrwv9:07916] [11] plumed_master(+0x15365)[0x561d0a320365]
[runnervmvrwv9:07916] *** End of error message ***
</pre>
{% endraw %}
