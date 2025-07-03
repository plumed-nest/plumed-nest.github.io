**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:12556] *** Process received signal ***
[pkrvmbietmlfzoi:12556] Signal: Aborted (6)
[pkrvmbietmlfzoi:12556] Signal code:  (-6)
[pkrvmbietmlfzoi:12556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd82a045330]
[pkrvmbietmlfzoi:12556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd82a09eb2c]
[pkrvmbietmlfzoi:12556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd82a04527e]
[pkrvmbietmlfzoi:12556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd82a0288ff]
[pkrvmbietmlfzoi:12556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd82a4a5ff5]
[pkrvmbietmlfzoi:12556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd82a4bb0da]
[pkrvmbietmlfzoi:12556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd82a4a5a55]
[pkrvmbietmlfzoi:12556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd82a4a5a6f]
[pkrvmbietmlfzoi:12556] [ 8] plumed(+0x146dd)[0x5571e33806dd]
[pkrvmbietmlfzoi:12556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd82a02a1ca]
[pkrvmbietmlfzoi:12556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd82a02a28b]
[pkrvmbietmlfzoi:12556] [11] plumed(+0x15365)[0x5571e3381365]
[pkrvmbietmlfzoi:12556] *** End of error message ***
</pre>
{% endraw %}
