**Project ID:** [plumID:24.026]({{ '/' | absolute_url }}eggs/24/026/)  
Stderr for source:  CpHMD_metaD/scripts/PLUMED_GRID.dat   
Download: [zipped raw stdout](PLUMED_GRID.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](PLUMED_GRID.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[pkrvmberfyhpb9w:05885] *** Process received signal ***
[pkrvmberfyhpb9w:05885] Signal: Aborted (6)
[pkrvmberfyhpb9w:05885] Signal code:  (-6)
[pkrvmberfyhpb9w:05885] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f54ffa45330]
[pkrvmberfyhpb9w:05885] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f54ffa9eb2c]
[pkrvmberfyhpb9w:05885] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f54ffa4527e]
[pkrvmberfyhpb9w:05885] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f54ffa288ff]
[pkrvmberfyhpb9w:05885] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54ffea5ff5]
[pkrvmberfyhpb9w:05885] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54ffebb0da]
[pkrvmberfyhpb9w:05885] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54ffea5a55]
[pkrvmberfyhpb9w:05885] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54ffea5a6f]
[pkrvmberfyhpb9w:05885] [ 8] plumed_master(+0x146dd)[0x55ecb4a3f6dd]
[pkrvmberfyhpb9w:05885] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f54ffa2a1ca]
[pkrvmberfyhpb9w:05885] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f54ffa2a28b]
[pkrvmberfyhpb9w:05885] [11] plumed_master(+0x15365)[0x55ecb4a40365]
[pkrvmberfyhpb9w:05885] *** End of error message ***
</pre>
{% endraw %}
