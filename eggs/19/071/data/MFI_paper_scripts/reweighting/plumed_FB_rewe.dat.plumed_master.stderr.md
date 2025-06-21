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
[pkrvmxyh4eaekms:13411] *** Process received signal ***
[pkrvmxyh4eaekms:13411] Signal: Aborted (6)
[pkrvmxyh4eaekms:13411] Signal code:  (-6)
[pkrvmxyh4eaekms:13411] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe20245330]
[pkrvmxyh4eaekms:13411] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe2029eb2c]
[pkrvmxyh4eaekms:13411] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe2024527e]
[pkrvmxyh4eaekms:13411] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe202288ff]
[pkrvmxyh4eaekms:13411] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe206a5ff5]
[pkrvmxyh4eaekms:13411] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe206bb0da]
[pkrvmxyh4eaekms:13411] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe206a5a55]
[pkrvmxyh4eaekms:13411] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe206a5a6f]
[pkrvmxyh4eaekms:13411] [ 8] plumed_master(+0x146dd)[0x56257d6c96dd]
[pkrvmxyh4eaekms:13411] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe2022a1ca]
[pkrvmxyh4eaekms:13411] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe2022a28b]
[pkrvmxyh4eaekms:13411] [11] plumed_master(+0x15365)[0x56257d6ca365]
[pkrvmxyh4eaekms:13411] *** End of error message ***
</pre>
{% endraw %}
