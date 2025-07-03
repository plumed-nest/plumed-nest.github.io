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
[pkrvmbietmlfzoi:05701] *** Process received signal ***
[pkrvmbietmlfzoi:05701] Signal: Aborted (6)
[pkrvmbietmlfzoi:05701] Signal code:  (-6)
[pkrvmbietmlfzoi:05701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9fd4645330]
[pkrvmbietmlfzoi:05701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9fd469eb2c]
[pkrvmbietmlfzoi:05701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9fd464527e]
[pkrvmbietmlfzoi:05701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9fd46288ff]
[pkrvmbietmlfzoi:05701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9fd4aa5ff5]
[pkrvmbietmlfzoi:05701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9fd4abb0da]
[pkrvmbietmlfzoi:05701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9fd4aa5a55]
[pkrvmbietmlfzoi:05701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9fd4aa5a6f]
[pkrvmbietmlfzoi:05701] [ 8] plumed_master(+0x146dd)[0x55aaf4fb26dd]
[pkrvmbietmlfzoi:05701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9fd462a1ca]
[pkrvmbietmlfzoi:05701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9fd462a28b]
[pkrvmbietmlfzoi:05701] [11] plumed_master(+0x15365)[0x55aaf4fb3365]
[pkrvmbietmlfzoi:05701] *** End of error message ***
</pre>
{% endraw %}
