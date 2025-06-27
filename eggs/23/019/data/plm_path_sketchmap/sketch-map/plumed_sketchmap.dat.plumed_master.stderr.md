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
[pkrvmbietmlfzoi:63670] *** Process received signal ***
[pkrvmbietmlfzoi:63670] Signal: Aborted (6)
[pkrvmbietmlfzoi:63670] Signal code:  (-6)
[pkrvmbietmlfzoi:63670] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa263845330]
[pkrvmbietmlfzoi:63670] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa26389eb2c]
[pkrvmbietmlfzoi:63670] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa26384527e]
[pkrvmbietmlfzoi:63670] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2638288ff]
[pkrvmbietmlfzoi:63670] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa263ca5ff5]
[pkrvmbietmlfzoi:63670] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa263cbb0da]
[pkrvmbietmlfzoi:63670] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa263ca5a55]
[pkrvmbietmlfzoi:63670] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa263ca5a6f]
[pkrvmbietmlfzoi:63670] [ 8] plumed_master(+0x146dd)[0x560ff2a3b6dd]
[pkrvmbietmlfzoi:63670] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa26382a1ca]
[pkrvmbietmlfzoi:63670] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa26382a28b]
[pkrvmbietmlfzoi:63670] [11] plumed_master(+0x15365)[0x560ff2a3c365]
[pkrvmbietmlfzoi:63670] *** End of error message ***
</pre>
{% endraw %}
