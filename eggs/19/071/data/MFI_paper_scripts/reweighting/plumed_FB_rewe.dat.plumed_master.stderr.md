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
[runnervmmtnos:39220] *** Process received signal ***
[runnervmmtnos:39220] Signal: Aborted (6)
[runnervmmtnos:39220] Signal code:  (-6)
[runnervmmtnos:39220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f42bfa45330]
[runnervmmtnos:39220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f42bfa9eb2c]
[runnervmmtnos:39220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f42bfa4527e]
[runnervmmtnos:39220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42bfa288ff]
[runnervmmtnos:39220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42bfea5ff5]
[runnervmmtnos:39220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42bfebb0da]
[runnervmmtnos:39220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42bfea5a55]
[runnervmmtnos:39220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42bfea5a6f]
[runnervmmtnos:39220] [ 8] plumed_master(+0x146dd)[0x5646ae6546dd]
[runnervmmtnos:39220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f42bfa2a1ca]
[runnervmmtnos:39220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f42bfa2a28b]
[runnervmmtnos:39220] [11] plumed_master(+0x15365)[0x5646ae655365]
[runnervmmtnos:39220] *** End of error message ***
</pre>
{% endraw %}
