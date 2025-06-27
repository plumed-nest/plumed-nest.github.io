**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:67656] *** Process received signal ***
[pkrvmbietmlfzoi:67656] Signal: Aborted (6)
[pkrvmbietmlfzoi:67656] Signal code:  (-6)
[pkrvmbietmlfzoi:67656] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32d1845330]
[pkrvmbietmlfzoi:67656] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32d189eb2c]
[pkrvmbietmlfzoi:67656] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32d184527e]
[pkrvmbietmlfzoi:67656] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32d18288ff]
[pkrvmbietmlfzoi:67656] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32d1ca5ff5]
[pkrvmbietmlfzoi:67656] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32d1cbb0da]
[pkrvmbietmlfzoi:67656] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32d1ca5a55]
[pkrvmbietmlfzoi:67656] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32d1ca5a6f]
[pkrvmbietmlfzoi:67656] [ 8] plumed_master(+0x146dd)[0x562a1152c6dd]
[pkrvmbietmlfzoi:67656] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32d182a1ca]
[pkrvmbietmlfzoi:67656] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32d182a28b]
[pkrvmbietmlfzoi:67656] [11] plumed_master(+0x15365)[0x562a1152d365]
[pkrvmbietmlfzoi:67656] *** End of error message ***
</pre>
{% endraw %}
