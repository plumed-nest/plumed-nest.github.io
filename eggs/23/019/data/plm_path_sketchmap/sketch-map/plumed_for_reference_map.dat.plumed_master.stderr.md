**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08173] *** Process received signal ***
[pkrvmbietmlfzoi:08173] Signal: Aborted (6)
[pkrvmbietmlfzoi:08173] Signal code:  (-6)
[pkrvmbietmlfzoi:08173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8a9645330]
[pkrvmbietmlfzoi:08173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8a969eb2c]
[pkrvmbietmlfzoi:08173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8a964527e]
[pkrvmbietmlfzoi:08173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8a96288ff]
[pkrvmbietmlfzoi:08173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8a9aa5ff5]
[pkrvmbietmlfzoi:08173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8a9abb0da]
[pkrvmbietmlfzoi:08173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8a9aa5a55]
[pkrvmbietmlfzoi:08173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8a9aa5a6f]
[pkrvmbietmlfzoi:08173] [ 8] plumed_master(+0x146dd)[0x55dbd40be6dd]
[pkrvmbietmlfzoi:08173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8a962a1ca]
[pkrvmbietmlfzoi:08173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8a962a28b]
[pkrvmbietmlfzoi:08173] [11] plumed_master(+0x15365)[0x55dbd40bf365]
[pkrvmbietmlfzoi:08173] *** End of error message ***
</pre>
{% endraw %}
