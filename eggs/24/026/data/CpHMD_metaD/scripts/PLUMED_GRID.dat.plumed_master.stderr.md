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
[runnervmkj6or:04762] *** Process received signal ***
[runnervmkj6or:04762] Signal: Aborted (6)
[runnervmkj6or:04762] Signal code:  (-6)
[runnervmkj6or:04762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95e7645330]
[runnervmkj6or:04762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95e769eb2c]
[runnervmkj6or:04762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95e764527e]
[runnervmkj6or:04762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95e76288ff]
[runnervmkj6or:04762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95e7aa5ff5]
[runnervmkj6or:04762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95e7abb0da]
[runnervmkj6or:04762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95e7aa5a55]
[runnervmkj6or:04762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95e7aa5a6f]
[runnervmkj6or:04762] [ 8] plumed_master(+0x146dd)[0x55f2a86466dd]
[runnervmkj6or:04762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95e762a1ca]
[runnervmkj6or:04762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95e762a28b]
[runnervmkj6or:04762] [11] plumed_master(+0x15365)[0x55f2a8647365]
[runnervmkj6or:04762] *** End of error message ***
</pre>
{% endraw %}
