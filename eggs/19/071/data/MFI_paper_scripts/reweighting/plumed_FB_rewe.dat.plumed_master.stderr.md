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
[runnervmkj6or:07459] *** Process received signal ***
[runnervmkj6or:07459] Signal: Aborted (6)
[runnervmkj6or:07459] Signal code:  (-6)
[runnervmkj6or:07459] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb84645330]
[runnervmkj6or:07459] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb8469eb2c]
[runnervmkj6or:07459] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb8464527e]
[runnervmkj6or:07459] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb846288ff]
[runnervmkj6or:07459] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb84aa5ff5]
[runnervmkj6or:07459] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb84abb0da]
[runnervmkj6or:07459] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb84aa5a55]
[runnervmkj6or:07459] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb84aa5a6f]
[runnervmkj6or:07459] [ 8] plumed_master(+0x146dd)[0x558299abb6dd]
[runnervmkj6or:07459] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb8462a1ca]
[runnervmkj6or:07459] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb8462a28b]
[runnervmkj6or:07459] [11] plumed_master(+0x15365)[0x558299abc365]
[runnervmkj6or:07459] *** End of error message ***
</pre>
{% endraw %}
