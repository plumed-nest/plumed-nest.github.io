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
[pkrvmbietmlfzoi:69078] *** Process received signal ***
[pkrvmbietmlfzoi:69078] Signal: Aborted (6)
[pkrvmbietmlfzoi:69078] Signal code:  (-6)
[pkrvmbietmlfzoi:69078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f25c3a45330]
[pkrvmbietmlfzoi:69078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f25c3a9eb2c]
[pkrvmbietmlfzoi:69078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f25c3a4527e]
[pkrvmbietmlfzoi:69078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25c3a288ff]
[pkrvmbietmlfzoi:69078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25c3ea5ff5]
[pkrvmbietmlfzoi:69078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25c3ebb0da]
[pkrvmbietmlfzoi:69078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25c3ea5a55]
[pkrvmbietmlfzoi:69078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25c3ea5a6f]
[pkrvmbietmlfzoi:69078] [ 8] plumed(+0x146dd)[0x556b3e66d6dd]
[pkrvmbietmlfzoi:69078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f25c3a2a1ca]
[pkrvmbietmlfzoi:69078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f25c3a2a28b]
[pkrvmbietmlfzoi:69078] [11] plumed(+0x15365)[0x556b3e66e365]
[pkrvmbietmlfzoi:69078] *** End of error message ***
</pre>
{% endraw %}
