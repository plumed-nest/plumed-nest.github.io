**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:67257] *** Process received signal ***
[pkrvmbietmlfzoi:67257] Signal: Aborted (6)
[pkrvmbietmlfzoi:67257] Signal code:  (-6)
[pkrvmbietmlfzoi:67257] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6668e45330]
[pkrvmbietmlfzoi:67257] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6668e9eb2c]
[pkrvmbietmlfzoi:67257] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6668e4527e]
[pkrvmbietmlfzoi:67257] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6668e288ff]
[pkrvmbietmlfzoi:67257] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66692a5ff5]
[pkrvmbietmlfzoi:67257] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66692bb0da]
[pkrvmbietmlfzoi:67257] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66692a5a55]
[pkrvmbietmlfzoi:67257] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66692a5a6f]
[pkrvmbietmlfzoi:67257] [ 8] plumed(+0x146dd)[0x5621c3ab96dd]
[pkrvmbietmlfzoi:67257] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6668e2a1ca]
[pkrvmbietmlfzoi:67257] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6668e2a28b]
[pkrvmbietmlfzoi:67257] [11] plumed(+0x15365)[0x5621c3aba365]
[pkrvmbietmlfzoi:67257] *** End of error message ***
</pre>
{% endraw %}
