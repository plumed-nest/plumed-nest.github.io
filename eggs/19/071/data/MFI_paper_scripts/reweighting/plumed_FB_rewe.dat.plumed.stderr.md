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
[runnervmkj6or:07443] *** Process received signal ***
[runnervmkj6or:07443] Signal: Aborted (6)
[runnervmkj6or:07443] Signal code:  (-6)
[runnervmkj6or:07443] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd0ca45330]
[runnervmkj6or:07443] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd0ca9eb2c]
[runnervmkj6or:07443] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd0ca4527e]
[runnervmkj6or:07443] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd0ca288ff]
[runnervmkj6or:07443] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd0cea5ff5]
[runnervmkj6or:07443] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd0cebb0da]
[runnervmkj6or:07443] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd0cea5a55]
[runnervmkj6or:07443] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd0cea5a6f]
[runnervmkj6or:07443] [ 8] plumed(+0x146dd)[0x5644c9ff76dd]
[runnervmkj6or:07443] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd0ca2a1ca]
[runnervmkj6or:07443] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd0ca2a28b]
[runnervmkj6or:07443] [11] plumed(+0x15365)[0x5644c9ff8365]
[runnervmkj6or:07443] *** End of error message ***
</pre>
{% endraw %}
