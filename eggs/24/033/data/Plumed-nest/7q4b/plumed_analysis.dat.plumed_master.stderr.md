**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmbietmlfzoi:05943] *** Process received signal ***
[pkrvmbietmlfzoi:05943] Signal: Aborted (6)
[pkrvmbietmlfzoi:05943] Signal code:  (-6)
[pkrvmbietmlfzoi:05943] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf7dc45330]
[pkrvmbietmlfzoi:05943] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf7dc9eb2c]
[pkrvmbietmlfzoi:05943] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf7dc4527e]
[pkrvmbietmlfzoi:05943] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf7dc288ff]
[pkrvmbietmlfzoi:05943] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf7e0a5ff5]
[pkrvmbietmlfzoi:05943] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf7e0bb0da]
[pkrvmbietmlfzoi:05943] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf7e0a5a55]
[pkrvmbietmlfzoi:05943] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf7e0a5a6f]
[pkrvmbietmlfzoi:05943] [ 8] plumed_master(+0x146dd)[0x563e253076dd]
[pkrvmbietmlfzoi:05943] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf7dc2a1ca]
[pkrvmbietmlfzoi:05943] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf7dc2a28b]
[pkrvmbietmlfzoi:05943] [11] plumed_master(+0x15365)[0x563e25308365]
[pkrvmbietmlfzoi:05943] *** End of error message ***
</pre>
{% endraw %}
