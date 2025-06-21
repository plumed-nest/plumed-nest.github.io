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
[pkrvmxyh4eaekms:06939] *** Process received signal ***
[pkrvmxyh4eaekms:06939] Signal: Aborted (6)
[pkrvmxyh4eaekms:06939] Signal code:  (-6)
[pkrvmxyh4eaekms:06939] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2af1845330]
[pkrvmxyh4eaekms:06939] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2af189eb2c]
[pkrvmxyh4eaekms:06939] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2af184527e]
[pkrvmxyh4eaekms:06939] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2af18288ff]
[pkrvmxyh4eaekms:06939] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2af1ca5ff5]
[pkrvmxyh4eaekms:06939] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2af1cbb0da]
[pkrvmxyh4eaekms:06939] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2af1ca5a55]
[pkrvmxyh4eaekms:06939] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2af1ca5a6f]
[pkrvmxyh4eaekms:06939] [ 8] plumed_master(+0x146dd)[0x55a9bf8266dd]
[pkrvmxyh4eaekms:06939] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2af182a1ca]
[pkrvmxyh4eaekms:06939] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2af182a28b]
[pkrvmxyh4eaekms:06939] [11] plumed_master(+0x15365)[0x55a9bf827365]
[pkrvmxyh4eaekms:06939] *** End of error message ***
</pre>
{% endraw %}
