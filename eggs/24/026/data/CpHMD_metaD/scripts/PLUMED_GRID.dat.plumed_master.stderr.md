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
[runnervmgx7h7:05628] *** Process received signal ***
[runnervmgx7h7:05628] Signal: Aborted (6)
[runnervmgx7h7:05628] Signal code:  (-6)
[runnervmgx7h7:05628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82d1445330]
[runnervmgx7h7:05628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82d149ec0c]
[runnervmgx7h7:05628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82d144527e]
[runnervmgx7h7:05628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82d14288ff]
[runnervmgx7h7:05628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82d18a5ff5]
[runnervmgx7h7:05628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82d18bb0da]
[runnervmgx7h7:05628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82d18a5a55]
[runnervmgx7h7:05628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82d18a5a6f]
[runnervmgx7h7:05628] [ 8] plumed_master(+0x146dd)[0x55aaaf8fd6dd]
[runnervmgx7h7:05628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82d142a1ca]
[runnervmgx7h7:05628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82d142a28b]
[runnervmgx7h7:05628] [11] plumed_master(+0x15365)[0x55aaaf8fe365]
[runnervmgx7h7:05628] *** End of error message ***
</pre>
{% endraw %}
