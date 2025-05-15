**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[pkrvmberfyhpb9w:05449] *** Process received signal ***
[pkrvmberfyhpb9w:05449] Signal: Aborted (6)
[pkrvmberfyhpb9w:05449] Signal code:  (-6)
[pkrvmberfyhpb9w:05449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4643a45330]
[pkrvmberfyhpb9w:05449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4643a9eb2c]
[pkrvmberfyhpb9w:05449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4643a4527e]
[pkrvmberfyhpb9w:05449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4643a288ff]
[pkrvmberfyhpb9w:05449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4643ea5ff5]
[pkrvmberfyhpb9w:05449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4643ebb0da]
[pkrvmberfyhpb9w:05449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4643ea5a55]
[pkrvmberfyhpb9w:05449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4643ea5a6f]
[pkrvmberfyhpb9w:05449] [ 8] plumed(+0x146dd)[0x55f4cd7c86dd]
[pkrvmberfyhpb9w:05449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4643a2a1ca]
[pkrvmberfyhpb9w:05449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4643a2a28b]
[pkrvmberfyhpb9w:05449] [11] plumed(+0x15365)[0x55f4cd7c9365]
[pkrvmberfyhpb9w:05449] *** End of error message ***
</pre>
{% endraw %}
