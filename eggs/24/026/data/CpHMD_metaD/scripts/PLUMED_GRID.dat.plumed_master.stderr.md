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
[runnervmi13qx:32676] *** Process received signal ***
[runnervmi13qx:32676] Signal: Aborted (6)
[runnervmi13qx:32676] Signal code:  (-6)
[runnervmi13qx:32676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa12be45330]
[runnervmi13qx:32676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa12be9eb2c]
[runnervmi13qx:32676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa12be4527e]
[runnervmi13qx:32676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa12be288ff]
[runnervmi13qx:32676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa12c2a5ff5]
[runnervmi13qx:32676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa12c2bb0da]
[runnervmi13qx:32676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa12c2a5a55]
[runnervmi13qx:32676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa12c2a5a6f]
[runnervmi13qx:32676] [ 8] plumed_master(+0x146dd)[0x5638edec96dd]
[runnervmi13qx:32676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa12be2a1ca]
[runnervmi13qx:32676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa12be2a28b]
[runnervmi13qx:32676] [11] plumed_master(+0x15365)[0x5638edeca365]
[runnervmi13qx:32676] *** End of error message ***
</pre>
{% endraw %}
