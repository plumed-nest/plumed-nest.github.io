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
[pkrvmf6wy0o8zjz:38140] *** Process received signal ***
[pkrvmf6wy0o8zjz:38140] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38140] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fddd1e45330]
[pkrvmf6wy0o8zjz:38140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fddd1e9eb2c]
[pkrvmf6wy0o8zjz:38140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fddd1e4527e]
[pkrvmf6wy0o8zjz:38140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fddd1e288ff]
[pkrvmf6wy0o8zjz:38140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fddd22a5ff5]
[pkrvmf6wy0o8zjz:38140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fddd22bb0da]
[pkrvmf6wy0o8zjz:38140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fddd22a5a55]
[pkrvmf6wy0o8zjz:38140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fddd22a5a6f]
[pkrvmf6wy0o8zjz:38140] [ 8] plumed(+0x146dd)[0x55a7124916dd]
[pkrvmf6wy0o8zjz:38140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fddd1e2a1ca]
[pkrvmf6wy0o8zjz:38140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fddd1e2a28b]
[pkrvmf6wy0o8zjz:38140] [11] plumed(+0x15365)[0x55a712492365]
[pkrvmf6wy0o8zjz:38140] *** End of error message ***
</pre>
{% endraw %}
