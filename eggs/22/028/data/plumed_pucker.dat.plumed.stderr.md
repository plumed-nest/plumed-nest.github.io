**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmbietmlfzoi:08286] *** Process received signal ***
[pkrvmbietmlfzoi:08286] Signal: Aborted (6)
[pkrvmbietmlfzoi:08286] Signal code:  (-6)
[pkrvmbietmlfzoi:08286] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbcabc45330]
[pkrvmbietmlfzoi:08286] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbcabc9eb2c]
[pkrvmbietmlfzoi:08286] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbcabc4527e]
[pkrvmbietmlfzoi:08286] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbcabc288ff]
[pkrvmbietmlfzoi:08286] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbcac0a5ff5]
[pkrvmbietmlfzoi:08286] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbcac0bb0da]
[pkrvmbietmlfzoi:08286] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbcac0a5a55]
[pkrvmbietmlfzoi:08286] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbcac0a5a6f]
[pkrvmbietmlfzoi:08286] [ 8] plumed(+0x146dd)[0x55f7ef8926dd]
[pkrvmbietmlfzoi:08286] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbcabc2a1ca]
[pkrvmbietmlfzoi:08286] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbcabc2a28b]
[pkrvmbietmlfzoi:08286] [11] plumed(+0x15365)[0x55f7ef893365]
[pkrvmbietmlfzoi:08286] *** End of error message ***
</pre>
{% endraw %}
