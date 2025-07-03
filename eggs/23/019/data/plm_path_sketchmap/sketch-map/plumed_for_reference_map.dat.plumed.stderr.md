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
[pkrvmbietmlfzoi:08158] *** Process received signal ***
[pkrvmbietmlfzoi:08158] Signal: Aborted (6)
[pkrvmbietmlfzoi:08158] Signal code:  (-6)
[pkrvmbietmlfzoi:08158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04e9a45330]
[pkrvmbietmlfzoi:08158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04e9a9eb2c]
[pkrvmbietmlfzoi:08158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04e9a4527e]
[pkrvmbietmlfzoi:08158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04e9a288ff]
[pkrvmbietmlfzoi:08158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04e9ea5ff5]
[pkrvmbietmlfzoi:08158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04e9ebb0da]
[pkrvmbietmlfzoi:08158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04e9ea5a55]
[pkrvmbietmlfzoi:08158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04e9ea5a6f]
[pkrvmbietmlfzoi:08158] [ 8] plumed(+0x146dd)[0x55d71b93d6dd]
[pkrvmbietmlfzoi:08158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04e9a2a1ca]
[pkrvmbietmlfzoi:08158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04e9a2a28b]
[pkrvmbietmlfzoi:08158] [11] plumed(+0x15365)[0x55d71b93e365]
[pkrvmbietmlfzoi:08158] *** End of error message ***
</pre>
{% endraw %}
