**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:13091] *** Process received signal ***
[pkrvmbietmlfzoi:13091] Signal: Aborted (6)
[pkrvmbietmlfzoi:13091] Signal code:  (-6)
[pkrvmbietmlfzoi:13091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d7d645330]
[pkrvmbietmlfzoi:13091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d7d69eb2c]
[pkrvmbietmlfzoi:13091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d7d64527e]
[pkrvmbietmlfzoi:13091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d7d6288ff]
[pkrvmbietmlfzoi:13091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d7daa5ff5]
[pkrvmbietmlfzoi:13091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d7dabb0da]
[pkrvmbietmlfzoi:13091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d7daa5a55]
[pkrvmbietmlfzoi:13091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d7daa5a6f]
[pkrvmbietmlfzoi:13091] [ 8] plumed(+0x146dd)[0x55c2ee7286dd]
[pkrvmbietmlfzoi:13091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d7d62a1ca]
[pkrvmbietmlfzoi:13091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d7d62a28b]
[pkrvmbietmlfzoi:13091] [11] plumed(+0x15365)[0x55c2ee729365]
[pkrvmbietmlfzoi:13091] *** End of error message ***
</pre>
{% endraw %}
