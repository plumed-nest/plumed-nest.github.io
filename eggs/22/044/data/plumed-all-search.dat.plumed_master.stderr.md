**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmf6wy0o8zjz:62610] *** Process received signal ***
[pkrvmf6wy0o8zjz:62610] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62610] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f749b045330]
[pkrvmf6wy0o8zjz:62610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f749b09eb2c]
[pkrvmf6wy0o8zjz:62610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f749b04527e]
[pkrvmf6wy0o8zjz:62610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f749b0288ff]
[pkrvmf6wy0o8zjz:62610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f749b4a5ff5]
[pkrvmf6wy0o8zjz:62610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f749b4bb0da]
[pkrvmf6wy0o8zjz:62610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f749b4a5a55]
[pkrvmf6wy0o8zjz:62610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f749b4a5a6f]
[pkrvmf6wy0o8zjz:62610] [ 8] plumed_master(+0x146dd)[0x55b3a00af6dd]
[pkrvmf6wy0o8zjz:62610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f749b02a1ca]
[pkrvmf6wy0o8zjz:62610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f749b02a28b]
[pkrvmf6wy0o8zjz:62610] [11] plumed_master(+0x15365)[0x55b3a00b0365]
[pkrvmf6wy0o8zjz:62610] *** End of error message ***
</pre>
{% endraw %}
