**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmbietmlfzoi:63963] *** Process received signal ***
[pkrvmbietmlfzoi:63963] Signal: Aborted (6)
[pkrvmbietmlfzoi:63963] Signal code:  (-6)
[pkrvmbietmlfzoi:63963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe28fa45330]
[pkrvmbietmlfzoi:63963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe28fa9eb2c]
[pkrvmbietmlfzoi:63963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe28fa4527e]
[pkrvmbietmlfzoi:63963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe28fa288ff]
[pkrvmbietmlfzoi:63963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe28fea5ff5]
[pkrvmbietmlfzoi:63963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe28febb0da]
[pkrvmbietmlfzoi:63963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe28fea5a55]
[pkrvmbietmlfzoi:63963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe28fea5a6f]
[pkrvmbietmlfzoi:63963] [ 8] plumed(+0x146dd)[0x5576bfc916dd]
[pkrvmbietmlfzoi:63963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe28fa2a1ca]
[pkrvmbietmlfzoi:63963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe28fa2a28b]
[pkrvmbietmlfzoi:63963] [11] plumed(+0x15365)[0x5576bfc92365]
[pkrvmbietmlfzoi:63963] *** End of error message ***
</pre>
{% endraw %}
