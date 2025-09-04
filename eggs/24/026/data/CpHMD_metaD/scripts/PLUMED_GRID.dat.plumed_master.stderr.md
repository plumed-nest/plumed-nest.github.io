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
[pkrvm7jw40e0xgp:07204] *** Process received signal ***
[pkrvm7jw40e0xgp:07204] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07204] Signal code:  (-6)
[pkrvm7jw40e0xgp:07204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b2e645330]
[pkrvm7jw40e0xgp:07204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b2e69eb2c]
[pkrvm7jw40e0xgp:07204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b2e64527e]
[pkrvm7jw40e0xgp:07204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b2e6288ff]
[pkrvm7jw40e0xgp:07204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b2eaa5ff5]
[pkrvm7jw40e0xgp:07204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b2eabb0da]
[pkrvm7jw40e0xgp:07204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b2eaa5a55]
[pkrvm7jw40e0xgp:07204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b2eaa5a6f]
[pkrvm7jw40e0xgp:07204] [ 8] plumed_master(+0x146dd)[0x55b8a55136dd]
[pkrvm7jw40e0xgp:07204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b2e62a1ca]
[pkrvm7jw40e0xgp:07204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b2e62a28b]
[pkrvm7jw40e0xgp:07204] [11] plumed_master(+0x15365)[0x55b8a5514365]
[pkrvm7jw40e0xgp:07204] *** End of error message ***
</pre>
{% endraw %}
