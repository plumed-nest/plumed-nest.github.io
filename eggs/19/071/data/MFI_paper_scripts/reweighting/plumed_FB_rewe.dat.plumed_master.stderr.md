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
[pkrvmq0rgcvqdmg:12251] *** Process received signal ***
[pkrvmq0rgcvqdmg:12251] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12251] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd937045330]
[pkrvmq0rgcvqdmg:12251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd93709eb2c]
[pkrvmq0rgcvqdmg:12251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd93704527e]
[pkrvmq0rgcvqdmg:12251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9370288ff]
[pkrvmq0rgcvqdmg:12251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9374a5ff5]
[pkrvmq0rgcvqdmg:12251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9374bb0da]
[pkrvmq0rgcvqdmg:12251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9374a5a55]
[pkrvmq0rgcvqdmg:12251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9374a5a6f]
[pkrvmq0rgcvqdmg:12251] [ 8] plumed_master(+0x146dd)[0x5620b70266dd]
[pkrvmq0rgcvqdmg:12251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd93702a1ca]
[pkrvmq0rgcvqdmg:12251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd93702a28b]
[pkrvmq0rgcvqdmg:12251] [11] plumed_master(+0x15365)[0x5620b7027365]
[pkrvmq0rgcvqdmg:12251] *** End of error message ***
</pre>
{% endraw %}
