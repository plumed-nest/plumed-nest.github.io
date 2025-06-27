**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63248] *** Process received signal ***
[pkrvmbietmlfzoi:63248] Signal: Aborted (6)
[pkrvmbietmlfzoi:63248] Signal code:  (-6)
[pkrvmbietmlfzoi:63248] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c18445330]
[pkrvmbietmlfzoi:63248] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c1849eb2c]
[pkrvmbietmlfzoi:63248] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c1844527e]
[pkrvmbietmlfzoi:63248] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c184288ff]
[pkrvmbietmlfzoi:63248] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c188a5ff5]
[pkrvmbietmlfzoi:63248] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c188bb0da]
[pkrvmbietmlfzoi:63248] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c188a5a55]
[pkrvmbietmlfzoi:63248] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c188a5a6f]
[pkrvmbietmlfzoi:63248] [ 8] plumed_master(+0x146dd)[0x55e1697766dd]
[pkrvmbietmlfzoi:63248] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c1842a1ca]
[pkrvmbietmlfzoi:63248] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c1842a28b]
[pkrvmbietmlfzoi:63248] [11] plumed_master(+0x15365)[0x55e169777365]
[pkrvmbietmlfzoi:63248] *** End of error message ***
</pre>
{% endraw %}
