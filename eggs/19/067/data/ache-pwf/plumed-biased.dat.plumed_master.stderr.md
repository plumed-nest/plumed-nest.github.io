**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:12572] *** Process received signal ***
[pkrvmbietmlfzoi:12572] Signal: Aborted (6)
[pkrvmbietmlfzoi:12572] Signal code:  (-6)
[pkrvmbietmlfzoi:12572] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ffd845330]
[pkrvmbietmlfzoi:12572] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ffd89eb2c]
[pkrvmbietmlfzoi:12572] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ffd84527e]
[pkrvmbietmlfzoi:12572] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ffd8288ff]
[pkrvmbietmlfzoi:12572] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ffdca5ff5]
[pkrvmbietmlfzoi:12572] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ffdcbb0da]
[pkrvmbietmlfzoi:12572] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ffdca5a55]
[pkrvmbietmlfzoi:12572] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ffdca5a6f]
[pkrvmbietmlfzoi:12572] [ 8] plumed_master(+0x146dd)[0x55b27f0106dd]
[pkrvmbietmlfzoi:12572] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ffd82a1ca]
[pkrvmbietmlfzoi:12572] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ffd82a28b]
[pkrvmbietmlfzoi:12572] [11] plumed_master(+0x15365)[0x55b27f011365]
[pkrvmbietmlfzoi:12572] *** End of error message ***
</pre>
{% endraw %}
