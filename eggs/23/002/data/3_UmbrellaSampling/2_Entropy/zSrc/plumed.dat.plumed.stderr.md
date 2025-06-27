**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63336] *** Process received signal ***
[pkrvmbietmlfzoi:63336] Signal: Aborted (6)
[pkrvmbietmlfzoi:63336] Signal code:  (-6)
[pkrvmbietmlfzoi:63336] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f42c2845330]
[pkrvmbietmlfzoi:63336] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f42c289eb2c]
[pkrvmbietmlfzoi:63336] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f42c284527e]
[pkrvmbietmlfzoi:63336] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42c28288ff]
[pkrvmbietmlfzoi:63336] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42c2ca5ff5]
[pkrvmbietmlfzoi:63336] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42c2cbb0da]
[pkrvmbietmlfzoi:63336] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42c2ca5a55]
[pkrvmbietmlfzoi:63336] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42c2ca5a6f]
[pkrvmbietmlfzoi:63336] [ 8] plumed(+0x146dd)[0x55c3ad8506dd]
[pkrvmbietmlfzoi:63336] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f42c282a1ca]
[pkrvmbietmlfzoi:63336] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f42c282a28b]
[pkrvmbietmlfzoi:63336] [11] plumed(+0x15365)[0x55c3ad851365]
[pkrvmbietmlfzoi:63336] *** End of error message ***
</pre>
{% endraw %}
