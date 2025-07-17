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
[pkrvmq0rgcvqdmg:06528] *** Process received signal ***
[pkrvmq0rgcvqdmg:06528] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06528] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9070e45330]
[pkrvmq0rgcvqdmg:06528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9070e9eb2c]
[pkrvmq0rgcvqdmg:06528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9070e4527e]
[pkrvmq0rgcvqdmg:06528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9070e288ff]
[pkrvmq0rgcvqdmg:06528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90712a5ff5]
[pkrvmq0rgcvqdmg:06528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90712bb0da]
[pkrvmq0rgcvqdmg:06528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90712a5a55]
[pkrvmq0rgcvqdmg:06528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90712a5a6f]
[pkrvmq0rgcvqdmg:06528] [ 8] plumed_master(+0x146dd)[0x55d4615f96dd]
[pkrvmq0rgcvqdmg:06528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9070e2a1ca]
[pkrvmq0rgcvqdmg:06528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9070e2a28b]
[pkrvmq0rgcvqdmg:06528] [11] plumed_master(+0x15365)[0x55d4615fa365]
[pkrvmq0rgcvqdmg:06528] *** End of error message ***
</pre>
{% endraw %}
