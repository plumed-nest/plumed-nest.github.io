**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
(download [zipped raw stdout](plumed_FB_rewe.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Grid.cpp:575, function static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
+++ message follows +++
no column labelled metad.bias in in grid input
[fv-az95-172:60550] *** Process received signal ***
[fv-az95-172:60550] Signal: Aborted (6)
[fv-az95-172:60550] Signal code:  (-6)
[fv-az95-172:60550] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f62aa024210]
[fv-az95-172:60550] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f62aa02418b]
[fv-az95-172:60550] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f62aa003859]
[fv-az95-172:60550] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f62aa28b911]
[fv-az95-172:60550] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f62aa29738c]
[fv-az95-172:60550] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f62aa2973f7]
[fv-az95-172:60550] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f62aa2976a9]
[fv-az95-172:60550] [ 7] plumed(+0xf47d)[0x55c77efdd47d]
[fv-az95-172:60550] [ 8] plumed(+0x14004)[0x55c77efe2004]
[fv-az95-172:60550] [ 9] plumed(+0xf698)[0x55c77efdd698]
[fv-az95-172:60550] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f62aa0050b3]
[fv-az95-172:60550] [11] plumed(+0xf76e)[0x55c77efdd76e]
[fv-az95-172:60550] *** End of error message ***
</pre>
{% endraw %}
