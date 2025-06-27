**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmbietmlfzoi:63146] *** Process received signal ***
[pkrvmbietmlfzoi:63146] Signal: Aborted (6)
[pkrvmbietmlfzoi:63146] Signal code:  (-6)
[pkrvmbietmlfzoi:63146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3134845330]
[pkrvmbietmlfzoi:63146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f313489eb2c]
[pkrvmbietmlfzoi:63146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f313484527e]
[pkrvmbietmlfzoi:63146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31348288ff]
[pkrvmbietmlfzoi:63146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3134ca5ff5]
[pkrvmbietmlfzoi:63146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3134cbb0da]
[pkrvmbietmlfzoi:63146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3134ca5a55]
[pkrvmbietmlfzoi:63146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3134ca5a6f]
[pkrvmbietmlfzoi:63146] [ 8] plumed_master(+0x146dd)[0x565403d546dd]
[pkrvmbietmlfzoi:63146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f313482a1ca]
[pkrvmbietmlfzoi:63146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f313482a28b]
[pkrvmbietmlfzoi:63146] [11] plumed_master(+0x15365)[0x565403d55365]
[pkrvmbietmlfzoi:63146] *** End of error message ***
</pre>
{% endraw %}
