**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63284] *** Process received signal ***
[pkrvmbietmlfzoi:63284] Signal: Aborted (6)
[pkrvmbietmlfzoi:63284] Signal code:  (-6)
[pkrvmbietmlfzoi:63284] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f611ec45330]
[pkrvmbietmlfzoi:63284] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f611ec9eb2c]
[pkrvmbietmlfzoi:63284] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f611ec4527e]
[pkrvmbietmlfzoi:63284] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f611ec288ff]
[pkrvmbietmlfzoi:63284] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f611f0a5ff5]
[pkrvmbietmlfzoi:63284] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f611f0bb0da]
[pkrvmbietmlfzoi:63284] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f611f0a5a55]
[pkrvmbietmlfzoi:63284] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f611f0a5a6f]
[pkrvmbietmlfzoi:63284] [ 8] plumed(+0x146dd)[0x5613a40056dd]
[pkrvmbietmlfzoi:63284] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f611ec2a1ca]
[pkrvmbietmlfzoi:63284] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f611ec2a28b]
[pkrvmbietmlfzoi:63284] [11] plumed(+0x15365)[0x5613a4006365]
[pkrvmbietmlfzoi:63284] *** End of error message ***
</pre>
{% endraw %}
