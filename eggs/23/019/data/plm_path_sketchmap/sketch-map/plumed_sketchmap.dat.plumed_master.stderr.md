**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08252] *** Process received signal ***
[pkrvmbietmlfzoi:08252] Signal: Aborted (6)
[pkrvmbietmlfzoi:08252] Signal code:  (-6)
[pkrvmbietmlfzoi:08252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca22645330]
[pkrvmbietmlfzoi:08252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca2269eb2c]
[pkrvmbietmlfzoi:08252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca2264527e]
[pkrvmbietmlfzoi:08252] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca226288ff]
[pkrvmbietmlfzoi:08252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca22aa5ff5]
[pkrvmbietmlfzoi:08252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca22abb0da]
[pkrvmbietmlfzoi:08252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca22aa5a55]
[pkrvmbietmlfzoi:08252] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca22aa5a6f]
[pkrvmbietmlfzoi:08252] [ 8] plumed_master(+0x146dd)[0x559de2c666dd]
[pkrvmbietmlfzoi:08252] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca2262a1ca]
[pkrvmbietmlfzoi:08252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca2262a28b]
[pkrvmbietmlfzoi:08252] [11] plumed_master(+0x15365)[0x559de2c67365]
[pkrvmbietmlfzoi:08252] *** End of error message ***
</pre>
{% endraw %}
