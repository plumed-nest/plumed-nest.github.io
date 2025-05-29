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
[pkrvmf6wy0o8zjz:69529] *** Process received signal ***
[pkrvmf6wy0o8zjz:69529] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69529] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69529] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa128445330]
[pkrvmf6wy0o8zjz:69529] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa12849eb2c]
[pkrvmf6wy0o8zjz:69529] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa12844527e]
[pkrvmf6wy0o8zjz:69529] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1284288ff]
[pkrvmf6wy0o8zjz:69529] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1288a5ff5]
[pkrvmf6wy0o8zjz:69529] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1288bb0da]
[pkrvmf6wy0o8zjz:69529] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1288a5a55]
[pkrvmf6wy0o8zjz:69529] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1288a5a6f]
[pkrvmf6wy0o8zjz:69529] [ 8] plumed_master(+0x146dd)[0x5646839626dd]
[pkrvmf6wy0o8zjz:69529] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa12842a1ca]
[pkrvmf6wy0o8zjz:69529] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa12842a28b]
[pkrvmf6wy0o8zjz:69529] [11] plumed_master(+0x15365)[0x564683963365]
[pkrvmf6wy0o8zjz:69529] *** End of error message ***
</pre>
{% endraw %}
