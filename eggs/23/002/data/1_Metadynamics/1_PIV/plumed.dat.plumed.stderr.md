**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63021] *** Process received signal ***
[pkrvmbietmlfzoi:63021] Signal: Aborted (6)
[pkrvmbietmlfzoi:63021] Signal code:  (-6)
[pkrvmbietmlfzoi:63021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2ef5a45330]
[pkrvmbietmlfzoi:63021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2ef5a9eb2c]
[pkrvmbietmlfzoi:63021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2ef5a4527e]
[pkrvmbietmlfzoi:63021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2ef5a288ff]
[pkrvmbietmlfzoi:63021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2ef5ea5ff5]
[pkrvmbietmlfzoi:63021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2ef5ebb0da]
[pkrvmbietmlfzoi:63021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2ef5ea5a55]
[pkrvmbietmlfzoi:63021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2ef5ea5a6f]
[pkrvmbietmlfzoi:63021] [ 8] plumed(+0x146dd)[0x55bce7b126dd]
[pkrvmbietmlfzoi:63021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2ef5a2a1ca]
[pkrvmbietmlfzoi:63021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2ef5a2a28b]
[pkrvmbietmlfzoi:63021] [11] plumed(+0x15365)[0x55bce7b13365]
[pkrvmbietmlfzoi:63021] *** End of error message ***
</pre>
{% endraw %}
