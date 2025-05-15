**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmberfyhpb9w:11527] *** Process received signal ***
[pkrvmberfyhpb9w:11527] Signal: Aborted (6)
[pkrvmberfyhpb9w:11527] Signal code:  (-6)
[pkrvmberfyhpb9w:11527] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2557445330]
[pkrvmberfyhpb9w:11527] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f255749eb2c]
[pkrvmberfyhpb9w:11527] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f255744527e]
[pkrvmberfyhpb9w:11527] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25574288ff]
[pkrvmberfyhpb9w:11527] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25578a5ff5]
[pkrvmberfyhpb9w:11527] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25578bb0da]
[pkrvmberfyhpb9w:11527] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25578a5a55]
[pkrvmberfyhpb9w:11527] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25578a5a6f]
[pkrvmberfyhpb9w:11527] [ 8] plumed_master(+0x146dd)[0x558bc15636dd]
[pkrvmberfyhpb9w:11527] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f255742a1ca]
[pkrvmberfyhpb9w:11527] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f255742a28b]
[pkrvmberfyhpb9w:11527] [11] plumed_master(+0x15365)[0x558bc1564365]
[pkrvmberfyhpb9w:11527] *** End of error message ***
</pre>
{% endraw %}
