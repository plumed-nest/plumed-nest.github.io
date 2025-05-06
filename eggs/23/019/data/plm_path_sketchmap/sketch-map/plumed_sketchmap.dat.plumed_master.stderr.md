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
[fv-az807-718:62652] *** Process received signal ***
[fv-az807-718:62652] Signal: Aborted (6)
[fv-az807-718:62652] Signal code:  (-6)
[fv-az807-718:62652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6470245330]
[fv-az807-718:62652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f647029eb2c]
[fv-az807-718:62652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f647024527e]
[fv-az807-718:62652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64702288ff]
[fv-az807-718:62652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64706a5ff5]
[fv-az807-718:62652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64706bb0da]
[fv-az807-718:62652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64706a5a55]
[fv-az807-718:62652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64706a5a6f]
[fv-az807-718:62652] [ 8] plumed_master(+0x146dd)[0x55e60147e6dd]
[fv-az807-718:62652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f647022a1ca]
[fv-az807-718:62652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f647022a28b]
[fv-az807-718:62652] [11] plumed_master(+0x15365)[0x55e60147f365]
[fv-az807-718:62652] *** End of error message ***
</pre>
{% endraw %}
