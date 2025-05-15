**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07537] *** Process received signal ***
[pkrvmberfyhpb9w:07537] Signal: Aborted (6)
[pkrvmberfyhpb9w:07537] Signal code:  (-6)
[pkrvmberfyhpb9w:07537] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51a7245330]
[pkrvmberfyhpb9w:07537] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51a729eb2c]
[pkrvmberfyhpb9w:07537] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51a724527e]
[pkrvmberfyhpb9w:07537] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51a72288ff]
[pkrvmberfyhpb9w:07537] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51a76a5ff5]
[pkrvmberfyhpb9w:07537] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51a76bb0da]
[pkrvmberfyhpb9w:07537] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51a76a5a55]
[pkrvmberfyhpb9w:07537] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51a76a5a6f]
[pkrvmberfyhpb9w:07537] [ 8] plumed(+0x146dd)[0x55f3e76b16dd]
[pkrvmberfyhpb9w:07537] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51a722a1ca]
[pkrvmberfyhpb9w:07537] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51a722a28b]
[pkrvmberfyhpb9w:07537] [11] plumed(+0x15365)[0x55f3e76b2365]
[pkrvmberfyhpb9w:07537] *** End of error message ***
</pre>
{% endraw %}
