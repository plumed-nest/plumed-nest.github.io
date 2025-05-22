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
[pkrvmf6wy0o8zjz:38156] *** Process received signal ***
[pkrvmf6wy0o8zjz:38156] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38156] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38156] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1c5645330]
[pkrvmf6wy0o8zjz:38156] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1c569eb2c]
[pkrvmf6wy0o8zjz:38156] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1c564527e]
[pkrvmf6wy0o8zjz:38156] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1c56288ff]
[pkrvmf6wy0o8zjz:38156] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1c5aa5ff5]
[pkrvmf6wy0o8zjz:38156] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1c5abb0da]
[pkrvmf6wy0o8zjz:38156] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1c5aa5a55]
[pkrvmf6wy0o8zjz:38156] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1c5aa5a6f]
[pkrvmf6wy0o8zjz:38156] [ 8] plumed_master(+0x146dd)[0x562e15dd66dd]
[pkrvmf6wy0o8zjz:38156] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1c562a1ca]
[pkrvmf6wy0o8zjz:38156] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1c562a28b]
[pkrvmf6wy0o8zjz:38156] [11] plumed_master(+0x15365)[0x562e15dd7365]
[pkrvmf6wy0o8zjz:38156] *** End of error message ***
</pre>
{% endraw %}
