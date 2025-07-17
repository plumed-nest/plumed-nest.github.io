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
[pkrvmq0rgcvqdmg:12235] *** Process received signal ***
[pkrvmq0rgcvqdmg:12235] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12235] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12235] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc08ce45330]
[pkrvmq0rgcvqdmg:12235] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc08ce9eb2c]
[pkrvmq0rgcvqdmg:12235] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc08ce4527e]
[pkrvmq0rgcvqdmg:12235] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc08ce288ff]
[pkrvmq0rgcvqdmg:12235] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc08d2a5ff5]
[pkrvmq0rgcvqdmg:12235] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc08d2bb0da]
[pkrvmq0rgcvqdmg:12235] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc08d2a5a55]
[pkrvmq0rgcvqdmg:12235] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc08d2a5a6f]
[pkrvmq0rgcvqdmg:12235] [ 8] plumed(+0x146dd)[0x55d71f1b46dd]
[pkrvmq0rgcvqdmg:12235] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc08ce2a1ca]
[pkrvmq0rgcvqdmg:12235] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc08ce2a28b]
[pkrvmq0rgcvqdmg:12235] [11] plumed(+0x15365)[0x55d71f1b5365]
[pkrvmq0rgcvqdmg:12235] *** End of error message ***
</pre>
{% endraw %}
