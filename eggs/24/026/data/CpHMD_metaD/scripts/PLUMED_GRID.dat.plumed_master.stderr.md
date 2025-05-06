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
[fv-az1781-652:61680] *** Process received signal ***
[fv-az1781-652:61680] Signal: Aborted (6)
[fv-az1781-652:61680] Signal code:  (-6)
[fv-az1781-652:61680] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a2d645330]
[fv-az1781-652:61680] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a2d69eb2c]
[fv-az1781-652:61680] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a2d64527e]
[fv-az1781-652:61680] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a2d6288ff]
[fv-az1781-652:61680] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a2daa5ff5]
[fv-az1781-652:61680] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a2dabb0da]
[fv-az1781-652:61680] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a2daa5a55]
[fv-az1781-652:61680] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a2daa5a6f]
[fv-az1781-652:61680] [ 8] plumed_master(+0x146dd)[0x55948dd056dd]
[fv-az1781-652:61680] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a2d62a1ca]
[fv-az1781-652:61680] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a2d62a28b]
[fv-az1781-652:61680] [11] plumed_master(+0x15365)[0x55948dd06365]
[fv-az1781-652:61680] *** End of error message ***
</pre>
{% endraw %}
