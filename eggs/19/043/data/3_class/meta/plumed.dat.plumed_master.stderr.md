**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:13106] *** Process received signal ***
[pkrvmbietmlfzoi:13106] Signal: Aborted (6)
[pkrvmbietmlfzoi:13106] Signal code:  (-6)
[pkrvmbietmlfzoi:13106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c7f445330]
[pkrvmbietmlfzoi:13106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c7f49eb2c]
[pkrvmbietmlfzoi:13106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c7f44527e]
[pkrvmbietmlfzoi:13106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c7f4288ff]
[pkrvmbietmlfzoi:13106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c7f8a5ff5]
[pkrvmbietmlfzoi:13106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c7f8bb0da]
[pkrvmbietmlfzoi:13106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c7f8a5a55]
[pkrvmbietmlfzoi:13106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c7f8a5a6f]
[pkrvmbietmlfzoi:13106] [ 8] plumed_master(+0x146dd)[0x55cf81a6b6dd]
[pkrvmbietmlfzoi:13106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c7f42a1ca]
[pkrvmbietmlfzoi:13106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c7f42a28b]
[pkrvmbietmlfzoi:13106] [11] plumed_master(+0x15365)[0x55cf81a6c365]
[pkrvmbietmlfzoi:13106] *** End of error message ***
</pre>
{% endraw %}
