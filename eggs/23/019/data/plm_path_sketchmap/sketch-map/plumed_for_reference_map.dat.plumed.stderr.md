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
[pkrvmbietmlfzoi:63572] *** Process received signal ***
[pkrvmbietmlfzoi:63572] Signal: Aborted (6)
[pkrvmbietmlfzoi:63572] Signal code:  (-6)
[pkrvmbietmlfzoi:63572] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a54645330]
[pkrvmbietmlfzoi:63572] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a5469eb2c]
[pkrvmbietmlfzoi:63572] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a5464527e]
[pkrvmbietmlfzoi:63572] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a546288ff]
[pkrvmbietmlfzoi:63572] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a54aa5ff5]
[pkrvmbietmlfzoi:63572] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a54abb0da]
[pkrvmbietmlfzoi:63572] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a54aa5a55]
[pkrvmbietmlfzoi:63572] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a54aa5a6f]
[pkrvmbietmlfzoi:63572] [ 8] plumed(+0x146dd)[0x560136a626dd]
[pkrvmbietmlfzoi:63572] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a5462a1ca]
[pkrvmbietmlfzoi:63572] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a5462a28b]
[pkrvmbietmlfzoi:63572] [11] plumed(+0x15365)[0x560136a63365]
[pkrvmbietmlfzoi:63572] *** End of error message ***
</pre>
{% endraw %}
