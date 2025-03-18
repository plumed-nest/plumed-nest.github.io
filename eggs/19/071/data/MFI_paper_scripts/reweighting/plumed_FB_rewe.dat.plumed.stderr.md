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
[fv-az1267-279:66779] *** Process received signal ***
[fv-az1267-279:66779] Signal: Aborted (6)
[fv-az1267-279:66779] Signal code:  (-6)
[fv-az1267-279:66779] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f00ede45330]
[fv-az1267-279:66779] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f00ede9eb2c]
[fv-az1267-279:66779] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f00ede4527e]
[fv-az1267-279:66779] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00ede288ff]
[fv-az1267-279:66779] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00ee2a5ff5]
[fv-az1267-279:66779] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00ee2bb0da]
[fv-az1267-279:66779] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00ee2a5a55]
[fv-az1267-279:66779] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00ee2a5a6f]
[fv-az1267-279:66779] [ 8] plumed(+0x146dd)[0x558d072426dd]
[fv-az1267-279:66779] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f00ede2a1ca]
[fv-az1267-279:66779] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f00ede2a28b]
[fv-az1267-279:66779] [11] plumed(+0x15365)[0x558d07243365]
[fv-az1267-279:66779] *** End of error message ***
</pre>
{% endraw %}
