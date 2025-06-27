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
[pkrvmbietmlfzoi:66015] *** Process received signal ***
[pkrvmbietmlfzoi:66015] Signal: Aborted (6)
[pkrvmbietmlfzoi:66015] Signal code:  (-6)
[pkrvmbietmlfzoi:66015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc317c45330]
[pkrvmbietmlfzoi:66015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc317c9eb2c]
[pkrvmbietmlfzoi:66015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc317c4527e]
[pkrvmbietmlfzoi:66015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc317c288ff]
[pkrvmbietmlfzoi:66015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3180a5ff5]
[pkrvmbietmlfzoi:66015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3180bb0da]
[pkrvmbietmlfzoi:66015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3180a5a55]
[pkrvmbietmlfzoi:66015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3180a5a6f]
[pkrvmbietmlfzoi:66015] [ 8] plumed(+0x146dd)[0x55cffa22f6dd]
[pkrvmbietmlfzoi:66015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc317c2a1ca]
[pkrvmbietmlfzoi:66015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc317c2a28b]
[pkrvmbietmlfzoi:66015] [11] plumed(+0x15365)[0x55cffa230365]
[pkrvmbietmlfzoi:66015] *** End of error message ***
</pre>
{% endraw %}
