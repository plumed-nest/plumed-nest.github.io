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
[pkrvmpptgkbjq6m:06312] *** Process received signal ***
[pkrvmpptgkbjq6m:06312] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06312] Signal code:  (-6)
[pkrvmpptgkbjq6m:06312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2fccc45330]
[pkrvmpptgkbjq6m:06312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2fccc9eb2c]
[pkrvmpptgkbjq6m:06312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2fccc4527e]
[pkrvmpptgkbjq6m:06312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2fccc288ff]
[pkrvmpptgkbjq6m:06312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2fcd0a5ff5]
[pkrvmpptgkbjq6m:06312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2fcd0bb0da]
[pkrvmpptgkbjq6m:06312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2fcd0a5a55]
[pkrvmpptgkbjq6m:06312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2fcd0a5a6f]
[pkrvmpptgkbjq6m:06312] [ 8] plumed_master(+0x146dd)[0x55c33aaf46dd]
[pkrvmpptgkbjq6m:06312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2fccc2a1ca]
[pkrvmpptgkbjq6m:06312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2fccc2a28b]
[pkrvmpptgkbjq6m:06312] [11] plumed_master(+0x15365)[0x55c33aaf5365]
[pkrvmpptgkbjq6m:06312] *** End of error message ***
</pre>
{% endraw %}
