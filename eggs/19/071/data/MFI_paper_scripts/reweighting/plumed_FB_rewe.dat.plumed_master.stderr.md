**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[pkrvm7jw40e0xgp:12983] *** Process received signal ***
[pkrvm7jw40e0xgp:12983] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12983] Signal code:  (-6)
[pkrvm7jw40e0xgp:12983] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe683445330]
[pkrvm7jw40e0xgp:12983] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe68349eb2c]
[pkrvm7jw40e0xgp:12983] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe68344527e]
[pkrvm7jw40e0xgp:12983] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6834288ff]
[pkrvm7jw40e0xgp:12983] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6838a5ff5]
[pkrvm7jw40e0xgp:12983] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6838bb0da]
[pkrvm7jw40e0xgp:12983] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6838a5a55]
[pkrvm7jw40e0xgp:12983] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6838a5a6f]
[pkrvm7jw40e0xgp:12983] [ 8] plumed_master(+0x146dd)[0x5648c00726dd]
[pkrvm7jw40e0xgp:12983] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe68342a1ca]
[pkrvm7jw40e0xgp:12983] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe68342a28b]
[pkrvm7jw40e0xgp:12983] [11] plumed_master(+0x15365)[0x5648c0073365]
[pkrvm7jw40e0xgp:12983] *** End of error message ***
</pre>
{% endraw %}
