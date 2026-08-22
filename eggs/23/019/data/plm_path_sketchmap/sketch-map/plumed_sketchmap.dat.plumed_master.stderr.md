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
[runnervm76f27:04970] *** Process received signal ***
[runnervm76f27:04970] Signal: Aborted (6)
[runnervm76f27:04970] Signal code:  (-6)
[runnervm76f27:04970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f86c2645330]
[runnervm76f27:04970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f86c269ec0c]
[runnervm76f27:04970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f86c264527e]
[runnervm76f27:04970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86c26288ff]
[runnervm76f27:04970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86c2aa5ff5]
[runnervm76f27:04970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86c2abb0da]
[runnervm76f27:04970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86c2aa5a55]
[runnervm76f27:04970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86c2aa5a6f]
[runnervm76f27:04970] [ 8] plumed_master(+0x146dd)[0x5638eabad6dd]
[runnervm76f27:04970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f86c262a1ca]
[runnervm76f27:04970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f86c262a28b]
[runnervm76f27:04970] [11] plumed_master(+0x15365)[0x5638eabae365]
[runnervm76f27:04970] *** End of error message ***
</pre>
{% endraw %}
