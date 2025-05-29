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
[pkrvmf6wy0o8zjz:69513] *** Process received signal ***
[pkrvmf6wy0o8zjz:69513] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69513] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69513] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7298a45330]
[pkrvmf6wy0o8zjz:69513] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7298a9eb2c]
[pkrvmf6wy0o8zjz:69513] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7298a4527e]
[pkrvmf6wy0o8zjz:69513] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7298a288ff]
[pkrvmf6wy0o8zjz:69513] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7298ea5ff5]
[pkrvmf6wy0o8zjz:69513] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7298ebb0da]
[pkrvmf6wy0o8zjz:69513] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7298ea5a55]
[pkrvmf6wy0o8zjz:69513] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7298ea5a6f]
[pkrvmf6wy0o8zjz:69513] [ 8] plumed(+0x146dd)[0x56157dbd16dd]
[pkrvmf6wy0o8zjz:69513] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7298a2a1ca]
[pkrvmf6wy0o8zjz:69513] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7298a2a28b]
[pkrvmf6wy0o8zjz:69513] [11] plumed(+0x15365)[0x56157dbd2365]
[pkrvmf6wy0o8zjz:69513] *** End of error message ***
</pre>
{% endraw %}
