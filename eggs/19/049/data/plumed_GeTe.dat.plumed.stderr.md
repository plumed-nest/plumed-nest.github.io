**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvmbietmlfzoi:10205] *** Process received signal ***
[pkrvmbietmlfzoi:10205] Signal: Aborted (6)
[pkrvmbietmlfzoi:10205] Signal code:  (-6)
[pkrvmbietmlfzoi:10205] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa669e45330]
[pkrvmbietmlfzoi:10205] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa669e9eb2c]
[pkrvmbietmlfzoi:10205] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa669e4527e]
[pkrvmbietmlfzoi:10205] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa669e288ff]
[pkrvmbietmlfzoi:10205] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa66a2a5ff5]
[pkrvmbietmlfzoi:10205] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa66a2bb0da]
[pkrvmbietmlfzoi:10205] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa66a2a5a55]
[pkrvmbietmlfzoi:10205] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa66a2a5a6f]
[pkrvmbietmlfzoi:10205] [ 8] plumed(+0x146dd)[0x55f455f576dd]
[pkrvmbietmlfzoi:10205] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa669e2a1ca]
[pkrvmbietmlfzoi:10205] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa669e2a28b]
[pkrvmbietmlfzoi:10205] [11] plumed(+0x15365)[0x55f455f58365]
[pkrvmbietmlfzoi:10205] *** End of error message ***
</pre>
{% endraw %}
