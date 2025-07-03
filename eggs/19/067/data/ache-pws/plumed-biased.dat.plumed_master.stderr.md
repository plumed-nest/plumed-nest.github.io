**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:12650] *** Process received signal ***
[pkrvmbietmlfzoi:12650] Signal: Aborted (6)
[pkrvmbietmlfzoi:12650] Signal code:  (-6)
[pkrvmbietmlfzoi:12650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7a1e45330]
[pkrvmbietmlfzoi:12650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7a1e9eb2c]
[pkrvmbietmlfzoi:12650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7a1e4527e]
[pkrvmbietmlfzoi:12650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7a1e288ff]
[pkrvmbietmlfzoi:12650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7a22a5ff5]
[pkrvmbietmlfzoi:12650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7a22bb0da]
[pkrvmbietmlfzoi:12650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7a22a5a55]
[pkrvmbietmlfzoi:12650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7a22a5a6f]
[pkrvmbietmlfzoi:12650] [ 8] plumed_master(+0x146dd)[0x561793fb26dd]
[pkrvmbietmlfzoi:12650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7a1e2a1ca]
[pkrvmbietmlfzoi:12650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7a1e2a28b]
[pkrvmbietmlfzoi:12650] [11] plumed_master(+0x15365)[0x561793fb3365]
[pkrvmbietmlfzoi:12650] *** End of error message ***
</pre>
{% endraw %}
