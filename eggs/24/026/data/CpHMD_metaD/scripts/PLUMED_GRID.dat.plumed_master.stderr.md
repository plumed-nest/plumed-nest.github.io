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
[fv-az1624-565:05630] *** Process received signal ***
[fv-az1624-565:05630] Signal: Aborted (6)
[fv-az1624-565:05630] Signal code:  (-6)
[fv-az1624-565:05630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3572a45330]
[fv-az1624-565:05630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3572a9eb2c]
[fv-az1624-565:05630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3572a4527e]
[fv-az1624-565:05630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3572a288ff]
[fv-az1624-565:05630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3572ea5ff5]
[fv-az1624-565:05630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3572ebb0da]
[fv-az1624-565:05630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3572ea5a55]
[fv-az1624-565:05630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3572ea5a6f]
[fv-az1624-565:05630] [ 8] plumed_master(+0x146dd)[0x5630eb08b6dd]
[fv-az1624-565:05630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3572a2a1ca]
[fv-az1624-565:05630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3572a2a28b]
[fv-az1624-565:05630] [11] plumed_master(+0x15365)[0x5630eb08c365]
[fv-az1624-565:05630] *** End of error message ***
</pre>
{% endraw %}
