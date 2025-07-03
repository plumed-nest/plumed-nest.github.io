**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvmbietmlfzoi:10221] *** Process received signal ***
[pkrvmbietmlfzoi:10221] Signal: Aborted (6)
[pkrvmbietmlfzoi:10221] Signal code:  (-6)
[pkrvmbietmlfzoi:10221] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ec4845330]
[pkrvmbietmlfzoi:10221] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ec489eb2c]
[pkrvmbietmlfzoi:10221] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ec484527e]
[pkrvmbietmlfzoi:10221] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ec48288ff]
[pkrvmbietmlfzoi:10221] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ec4ca5ff5]
[pkrvmbietmlfzoi:10221] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ec4cbb0da]
[pkrvmbietmlfzoi:10221] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ec4ca5a55]
[pkrvmbietmlfzoi:10221] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ec4ca5a6f]
[pkrvmbietmlfzoi:10221] [ 8] plumed_master(+0x146dd)[0x5622164d06dd]
[pkrvmbietmlfzoi:10221] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ec482a1ca]
[pkrvmbietmlfzoi:10221] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ec482a28b]
[pkrvmbietmlfzoi:10221] [11] plumed_master(+0x15365)[0x5622164d1365]
[pkrvmbietmlfzoi:10221] *** End of error message ***
</pre>
{% endraw %}
