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
[fv-az1909-454:60975] *** Process received signal ***
[fv-az1909-454:60975] Signal: Aborted (6)
[fv-az1909-454:60975] Signal code:  (-6)
[fv-az1909-454:60975] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d13445330]
[fv-az1909-454:60975] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d1349eb2c]
[fv-az1909-454:60975] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d1344527e]
[fv-az1909-454:60975] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d134288ff]
[fv-az1909-454:60975] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d138a5ff5]
[fv-az1909-454:60975] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d138bb0da]
[fv-az1909-454:60975] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d138a5a55]
[fv-az1909-454:60975] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d138a5a6f]
[fv-az1909-454:60975] [ 8] plumed_master(+0x146dd)[0x561f0be5b6dd]
[fv-az1909-454:60975] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d1342a1ca]
[fv-az1909-454:60975] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d1342a28b]
[fv-az1909-454:60975] [11] plumed_master(+0x15365)[0x561f0be5c365]
[fv-az1909-454:60975] *** End of error message ***
</pre>
{% endraw %}
