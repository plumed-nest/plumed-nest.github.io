**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervmmklqx:10044] *** Process received signal ***
[runnervmmklqx:10044] Signal: Aborted (6)
[runnervmmklqx:10044] Signal code:  (-6)
[runnervmmklqx:10044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef75445330]
[runnervmmklqx:10044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef7549eb2c]
[runnervmmklqx:10044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef7544527e]
[runnervmmklqx:10044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef754288ff]
[runnervmmklqx:10044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef758a5ff5]
[runnervmmklqx:10044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef758bb0da]
[runnervmmklqx:10044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef758a5a55]
[runnervmmklqx:10044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef758a5a6f]
[runnervmmklqx:10044] [ 8] plumed_master(+0x146dd)[0x561686c106dd]
[runnervmmklqx:10044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef7542a1ca]
[runnervmmklqx:10044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef7542a28b]
[runnervmmklqx:10044] [11] plumed_master(+0x15365)[0x561686c11365]
[runnervmmklqx:10044] *** End of error message ***
</pre>
{% endraw %}
