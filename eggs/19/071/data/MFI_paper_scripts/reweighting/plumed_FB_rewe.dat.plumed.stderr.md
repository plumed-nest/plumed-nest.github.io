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
[fv-az789-879:67145] *** Process received signal ***
[fv-az789-879:67145] Signal: Aborted (6)
[fv-az789-879:67145] Signal code:  (-6)
[fv-az789-879:67145] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec5ea45330]
[fv-az789-879:67145] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec5ea9eb2c]
[fv-az789-879:67145] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec5ea4527e]
[fv-az789-879:67145] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec5ea288ff]
[fv-az789-879:67145] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec5eea5ff5]
[fv-az789-879:67145] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec5eebb0da]
[fv-az789-879:67145] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec5eea5a55]
[fv-az789-879:67145] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec5eea5a6f]
[fv-az789-879:67145] [ 8] plumed(+0x146dd)[0x5608d4dd76dd]
[fv-az789-879:67145] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec5ea2a1ca]
[fv-az789-879:67145] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec5ea2a28b]
[fv-az789-879:67145] [11] plumed(+0x15365)[0x5608d4dd8365]
[fv-az789-879:67145] *** End of error message ***
</pre>
{% endraw %}
