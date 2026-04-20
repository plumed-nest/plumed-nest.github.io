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
[runnervmeorf1:04337] *** Process received signal ***
[runnervmeorf1:04337] Signal: Aborted (6)
[runnervmeorf1:04337] Signal code:  (-6)
[runnervmeorf1:04337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5852c45330]
[runnervmeorf1:04337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5852c9eb2c]
[runnervmeorf1:04337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5852c4527e]
[runnervmeorf1:04337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5852c288ff]
[runnervmeorf1:04337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58530a5ff5]
[runnervmeorf1:04337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58530bb0da]
[runnervmeorf1:04337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58530a5a55]
[runnervmeorf1:04337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58530a5a6f]
[runnervmeorf1:04337] [ 8] plumed_master(+0x146dd)[0x558d3dd166dd]
[runnervmeorf1:04337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5852c2a1ca]
[runnervmeorf1:04337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5852c2a28b]
[runnervmeorf1:04337] [11] plumed_master(+0x15365)[0x558d3dd17365]
[runnervmeorf1:04337] *** End of error message ***
</pre>
{% endraw %}
