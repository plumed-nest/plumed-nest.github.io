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
[pkrvmbietmlfzoi:67193] *** Process received signal ***
[pkrvmbietmlfzoi:67193] Signal: Aborted (6)
[pkrvmbietmlfzoi:67193] Signal code:  (-6)
[pkrvmbietmlfzoi:67193] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f31a7645330]
[pkrvmbietmlfzoi:67193] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f31a769eb2c]
[pkrvmbietmlfzoi:67193] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f31a764527e]
[pkrvmbietmlfzoi:67193] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31a76288ff]
[pkrvmbietmlfzoi:67193] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31a7aa5ff5]
[pkrvmbietmlfzoi:67193] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31a7abb0da]
[pkrvmbietmlfzoi:67193] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31a7aa5a55]
[pkrvmbietmlfzoi:67193] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31a7aa5a6f]
[pkrvmbietmlfzoi:67193] [ 8] plumed_master(+0x146dd)[0x55d533fa36dd]
[pkrvmbietmlfzoi:67193] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f31a762a1ca]
[pkrvmbietmlfzoi:67193] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f31a762a28b]
[pkrvmbietmlfzoi:67193] [11] plumed_master(+0x15365)[0x55d533fa4365]
[pkrvmbietmlfzoi:67193] *** End of error message ***
</pre>
{% endraw %}
