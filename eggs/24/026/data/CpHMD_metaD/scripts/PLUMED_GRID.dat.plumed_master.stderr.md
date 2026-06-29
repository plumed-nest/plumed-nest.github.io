**Project ID:** [plumID:24.026]({{ '/' | absolute_url }}eggs/24/026/)  
Stderr for source:  CpHMD_metaD/scripts/PLUMED_GRID.dat   
Download: [zipped raw stdout](PLUMED_GRID.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](PLUMED_GRID.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervmmklqx:04823] *** Process received signal ***
[runnervmmklqx:04823] Signal: Aborted (6)
[runnervmmklqx:04823] Signal code:  (-6)
[runnervmmklqx:04823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cae645330]
[runnervmmklqx:04823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cae69eb2c]
[runnervmmklqx:04823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cae64527e]
[runnervmmklqx:04823] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cae6288ff]
[runnervmmklqx:04823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1caeaa5ff5]
[runnervmmklqx:04823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1caeabb0da]
[runnervmmklqx:04823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1caeaa5a55]
[runnervmmklqx:04823] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1caeaa5a6f]
[runnervmmklqx:04823] [ 8] plumed_master(+0x146dd)[0x557bdb7ff6dd]
[runnervmmklqx:04823] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cae62a1ca]
[runnervmmklqx:04823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cae62a28b]
[runnervmmklqx:04823] [11] plumed_master(+0x15365)[0x557bdb800365]
[runnervmmklqx:04823] *** End of error message ***
</pre>
{% endraw %}
