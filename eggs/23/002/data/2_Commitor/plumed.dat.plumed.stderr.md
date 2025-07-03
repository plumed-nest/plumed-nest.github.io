**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:08653] *** Process received signal ***
[pkrvmbietmlfzoi:08653] Signal: Aborted (6)
[pkrvmbietmlfzoi:08653] Signal code:  (-6)
[pkrvmbietmlfzoi:08653] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98b7245330]
[pkrvmbietmlfzoi:08653] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98b729eb2c]
[pkrvmbietmlfzoi:08653] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98b724527e]
[pkrvmbietmlfzoi:08653] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98b72288ff]
[pkrvmbietmlfzoi:08653] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98b76a5ff5]
[pkrvmbietmlfzoi:08653] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98b76bb0da]
[pkrvmbietmlfzoi:08653] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98b76a5a55]
[pkrvmbietmlfzoi:08653] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98b76a5a6f]
[pkrvmbietmlfzoi:08653] [ 8] plumed(+0x146dd)[0x55c0702496dd]
[pkrvmbietmlfzoi:08653] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98b722a1ca]
[pkrvmbietmlfzoi:08653] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98b722a28b]
[pkrvmbietmlfzoi:08653] [11] plumed(+0x15365)[0x55c07024a365]
[pkrvmbietmlfzoi:08653] *** End of error message ***
</pre>
{% endraw %}
