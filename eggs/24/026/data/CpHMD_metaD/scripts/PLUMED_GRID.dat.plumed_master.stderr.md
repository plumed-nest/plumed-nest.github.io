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
[pkrvmbietmlfzoi:62078] *** Process received signal ***
[pkrvmbietmlfzoi:62078] Signal: Aborted (6)
[pkrvmbietmlfzoi:62078] Signal code:  (-6)
[pkrvmbietmlfzoi:62078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0322245330]
[pkrvmbietmlfzoi:62078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f032229eb2c]
[pkrvmbietmlfzoi:62078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f032224527e]
[pkrvmbietmlfzoi:62078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03222288ff]
[pkrvmbietmlfzoi:62078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03226a5ff5]
[pkrvmbietmlfzoi:62078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03226bb0da]
[pkrvmbietmlfzoi:62078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03226a5a55]
[pkrvmbietmlfzoi:62078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03226a5a6f]
[pkrvmbietmlfzoi:62078] [ 8] plumed_master(+0x146dd)[0x56528acae6dd]
[pkrvmbietmlfzoi:62078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f032222a1ca]
[pkrvmbietmlfzoi:62078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f032222a28b]
[pkrvmbietmlfzoi:62078] [11] plumed_master(+0x15365)[0x56528acaf365]
[pkrvmbietmlfzoi:62078] *** End of error message ***
</pre>
{% endraw %}
