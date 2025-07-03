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
[pkrvmbietmlfzoi:07605] *** Process received signal ***
[pkrvmbietmlfzoi:07605] Signal: Aborted (6)
[pkrvmbietmlfzoi:07605] Signal code:  (-6)
[pkrvmbietmlfzoi:07605] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda47045330]
[pkrvmbietmlfzoi:07605] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda4709eb2c]
[pkrvmbietmlfzoi:07605] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda4704527e]
[pkrvmbietmlfzoi:07605] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda470288ff]
[pkrvmbietmlfzoi:07605] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda474a5ff5]
[pkrvmbietmlfzoi:07605] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda474bb0da]
[pkrvmbietmlfzoi:07605] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda474a5a55]
[pkrvmbietmlfzoi:07605] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda474a5a6f]
[pkrvmbietmlfzoi:07605] [ 8] plumed_master(+0x146dd)[0x55d8f17e66dd]
[pkrvmbietmlfzoi:07605] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda4702a1ca]
[pkrvmbietmlfzoi:07605] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda4702a28b]
[pkrvmbietmlfzoi:07605] [11] plumed_master(+0x15365)[0x55d8f17e7365]
[pkrvmbietmlfzoi:07605] *** End of error message ***
</pre>
{% endraw %}
