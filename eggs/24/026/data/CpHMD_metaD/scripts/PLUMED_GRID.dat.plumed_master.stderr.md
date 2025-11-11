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
[runnervmw9dnm:06410] *** Process received signal ***
[runnervmw9dnm:06410] Signal: Aborted (6)
[runnervmw9dnm:06410] Signal code:  (-6)
[runnervmw9dnm:06410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1fa045330]
[runnervmw9dnm:06410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1fa09eb2c]
[runnervmw9dnm:06410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1fa04527e]
[runnervmw9dnm:06410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1fa0288ff]
[runnervmw9dnm:06410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1fa4a5ff5]
[runnervmw9dnm:06410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1fa4bb0da]
[runnervmw9dnm:06410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1fa4a5a55]
[runnervmw9dnm:06410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1fa4a5a6f]
[runnervmw9dnm:06410] [ 8] plumed_master(+0x146dd)[0x56439a7376dd]
[runnervmw9dnm:06410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1fa02a1ca]
[runnervmw9dnm:06410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1fa02a28b]
[runnervmw9dnm:06410] [11] plumed_master(+0x15365)[0x56439a738365]
[runnervmw9dnm:06410] *** End of error message ***
</pre>
{% endraw %}
