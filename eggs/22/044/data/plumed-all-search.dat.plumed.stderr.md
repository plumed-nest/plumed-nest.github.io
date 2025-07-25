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
[pkrvmpptgkbjq6m:09152] *** Process received signal ***
[pkrvmpptgkbjq6m:09152] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09152] Signal code:  (-6)
[pkrvmpptgkbjq6m:09152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2e67c45330]
[pkrvmpptgkbjq6m:09152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2e67c9eb2c]
[pkrvmpptgkbjq6m:09152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2e67c4527e]
[pkrvmpptgkbjq6m:09152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2e67c288ff]
[pkrvmpptgkbjq6m:09152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2e680a5ff5]
[pkrvmpptgkbjq6m:09152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2e680bb0da]
[pkrvmpptgkbjq6m:09152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2e680a5a55]
[pkrvmpptgkbjq6m:09152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2e680a5a6f]
[pkrvmpptgkbjq6m:09152] [ 8] plumed(+0x146dd)[0x55641f7c36dd]
[pkrvmpptgkbjq6m:09152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2e67c2a1ca]
[pkrvmpptgkbjq6m:09152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2e67c2a28b]
[pkrvmpptgkbjq6m:09152] [11] plumed(+0x15365)[0x55641f7c4365]
[pkrvmpptgkbjq6m:09152] *** End of error message ***
</pre>
{% endraw %}
