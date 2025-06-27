**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmbietmlfzoi:63980] *** Process received signal ***
[pkrvmbietmlfzoi:63980] Signal: Aborted (6)
[pkrvmbietmlfzoi:63980] Signal code:  (-6)
[pkrvmbietmlfzoi:63980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c1d045330]
[pkrvmbietmlfzoi:63980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c1d09eb2c]
[pkrvmbietmlfzoi:63980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c1d04527e]
[pkrvmbietmlfzoi:63980] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c1d0288ff]
[pkrvmbietmlfzoi:63980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c1d4a5ff5]
[pkrvmbietmlfzoi:63980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c1d4bb0da]
[pkrvmbietmlfzoi:63980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c1d4a5a55]
[pkrvmbietmlfzoi:63980] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c1d4a5a6f]
[pkrvmbietmlfzoi:63980] [ 8] plumed_master(+0x146dd)[0x55de2490f6dd]
[pkrvmbietmlfzoi:63980] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c1d02a1ca]
[pkrvmbietmlfzoi:63980] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c1d02a28b]
[pkrvmbietmlfzoi:63980] [11] plumed_master(+0x15365)[0x55de24910365]
[pkrvmbietmlfzoi:63980] *** End of error message ***
</pre>
{% endraw %}
