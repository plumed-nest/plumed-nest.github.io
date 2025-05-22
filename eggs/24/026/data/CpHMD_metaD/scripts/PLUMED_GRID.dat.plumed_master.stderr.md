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
[pkrvmf6wy0o8zjz:33260] *** Process received signal ***
[pkrvmf6wy0o8zjz:33260] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33260] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7755245330]
[pkrvmf6wy0o8zjz:33260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f775529eb2c]
[pkrvmf6wy0o8zjz:33260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f775524527e]
[pkrvmf6wy0o8zjz:33260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77552288ff]
[pkrvmf6wy0o8zjz:33260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77556a5ff5]
[pkrvmf6wy0o8zjz:33260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77556bb0da]
[pkrvmf6wy0o8zjz:33260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77556a5a55]
[pkrvmf6wy0o8zjz:33260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77556a5a6f]
[pkrvmf6wy0o8zjz:33260] [ 8] plumed_master(+0x146dd)[0x563b2bd5b6dd]
[pkrvmf6wy0o8zjz:33260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f775522a1ca]
[pkrvmf6wy0o8zjz:33260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f775522a28b]
[pkrvmf6wy0o8zjz:33260] [11] plumed_master(+0x15365)[0x563b2bd5c365]
[pkrvmf6wy0o8zjz:33260] *** End of error message ***
</pre>
{% endraw %}
