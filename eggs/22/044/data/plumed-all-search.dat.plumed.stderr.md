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
[pkrvmberfyhpb9w:07828] *** Process received signal ***
[pkrvmberfyhpb9w:07828] Signal: Aborted (6)
[pkrvmberfyhpb9w:07828] Signal code:  (-6)
[pkrvmberfyhpb9w:07828] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f35b4445330]
[pkrvmberfyhpb9w:07828] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f35b449eb2c]
[pkrvmberfyhpb9w:07828] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f35b444527e]
[pkrvmberfyhpb9w:07828] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35b44288ff]
[pkrvmberfyhpb9w:07828] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35b48a5ff5]
[pkrvmberfyhpb9w:07828] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35b48bb0da]
[pkrvmberfyhpb9w:07828] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35b48a5a55]
[pkrvmberfyhpb9w:07828] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35b48a5a6f]
[pkrvmberfyhpb9w:07828] [ 8] plumed(+0x146dd)[0x56145efb56dd]
[pkrvmberfyhpb9w:07828] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f35b442a1ca]
[pkrvmberfyhpb9w:07828] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f35b442a28b]
[pkrvmberfyhpb9w:07828] [11] plumed(+0x15365)[0x56145efb6365]
[pkrvmberfyhpb9w:07828] *** End of error message ***
</pre>
{% endraw %}
