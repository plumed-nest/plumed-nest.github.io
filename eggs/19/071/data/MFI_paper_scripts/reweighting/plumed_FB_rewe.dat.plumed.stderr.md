**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed.stderr.txt.zip) 
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
[pkrvmpptgkbjq6m:10744] *** Process received signal ***
[pkrvmpptgkbjq6m:10744] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10744] Signal code:  (-6)
[pkrvmpptgkbjq6m:10744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4f2245330]
[pkrvmpptgkbjq6m:10744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4f229eb2c]
[pkrvmpptgkbjq6m:10744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4f224527e]
[pkrvmpptgkbjq6m:10744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4f22288ff]
[pkrvmpptgkbjq6m:10744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4f26a5ff5]
[pkrvmpptgkbjq6m:10744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4f26bb0da]
[pkrvmpptgkbjq6m:10744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4f26a5a55]
[pkrvmpptgkbjq6m:10744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4f26a5a6f]
[pkrvmpptgkbjq6m:10744] [ 8] plumed(+0x146dd)[0x55eb152236dd]
[pkrvmpptgkbjq6m:10744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4f222a1ca]
[pkrvmpptgkbjq6m:10744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4f222a28b]
[pkrvmpptgkbjq6m:10744] [11] plumed(+0x15365)[0x55eb15224365]
[pkrvmpptgkbjq6m:10744] *** End of error message ***
</pre>
{% endraw %}
