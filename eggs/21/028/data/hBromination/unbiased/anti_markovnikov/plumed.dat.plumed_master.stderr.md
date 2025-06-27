**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[pkrvmbietmlfzoi:67547] *** Process received signal ***
[pkrvmbietmlfzoi:67547] Signal: Aborted (6)
[pkrvmbietmlfzoi:67547] Signal code:  (-6)
[pkrvmbietmlfzoi:67547] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2f3645330]
[pkrvmbietmlfzoi:67547] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2f369eb2c]
[pkrvmbietmlfzoi:67547] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2f364527e]
[pkrvmbietmlfzoi:67547] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2f36288ff]
[pkrvmbietmlfzoi:67547] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2f3aa5ff5]
[pkrvmbietmlfzoi:67547] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2f3abb0da]
[pkrvmbietmlfzoi:67547] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2f3aa5a55]
[pkrvmbietmlfzoi:67547] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2f3aa5a6f]
[pkrvmbietmlfzoi:67547] [ 8] plumed_master(+0x146dd)[0x5623c35626dd]
[pkrvmbietmlfzoi:67547] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2f362a1ca]
[pkrvmbietmlfzoi:67547] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2f362a28b]
[pkrvmbietmlfzoi:67547] [11] plumed_master(+0x15365)[0x5623c3563365]
[pkrvmbietmlfzoi:67547] *** End of error message ***
</pre>
{% endraw %}
