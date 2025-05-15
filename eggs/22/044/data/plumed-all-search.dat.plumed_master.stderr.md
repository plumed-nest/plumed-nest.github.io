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
[pkrvmberfyhpb9w:07844] *** Process received signal ***
[pkrvmberfyhpb9w:07844] Signal: Aborted (6)
[pkrvmberfyhpb9w:07844] Signal code:  (-6)
[pkrvmberfyhpb9w:07844] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5677445330]
[pkrvmberfyhpb9w:07844] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f567749eb2c]
[pkrvmberfyhpb9w:07844] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f567744527e]
[pkrvmberfyhpb9w:07844] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56774288ff]
[pkrvmberfyhpb9w:07844] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56778a5ff5]
[pkrvmberfyhpb9w:07844] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56778bb0da]
[pkrvmberfyhpb9w:07844] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56778a5a55]
[pkrvmberfyhpb9w:07844] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56778a5a6f]
[pkrvmberfyhpb9w:07844] [ 8] plumed_master(+0x146dd)[0x55ee4bc8e6dd]
[pkrvmberfyhpb9w:07844] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f567742a1ca]
[pkrvmberfyhpb9w:07844] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f567742a28b]
[pkrvmberfyhpb9w:07844] [11] plumed_master(+0x15365)[0x55ee4bc8f365]
[pkrvmberfyhpb9w:07844] *** End of error message ***
</pre>
{% endraw %}
