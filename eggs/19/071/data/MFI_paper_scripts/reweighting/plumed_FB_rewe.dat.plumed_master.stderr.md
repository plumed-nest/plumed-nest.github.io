**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
(download [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Grid.cpp:565, function static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
+++ message follows +++
no column labelled metad.bias in in grid input
[fv-az95-172:60558] *** Process received signal ***
[fv-az95-172:60558] Signal: Aborted (6)
[fv-az95-172:60558] Signal code:  (-6)
[fv-az95-172:60558] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1f3706d210]
[fv-az95-172:60558] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1f3706d18b]
[fv-az95-172:60558] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1f3704c859]
[fv-az95-172:60558] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1f372d4911]
[fv-az95-172:60558] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1f372e038c]
[fv-az95-172:60558] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1f372e03f7]
[fv-az95-172:60558] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f1f372e06fd]
[fv-az95-172:60558] [ 7] plumed_master(+0xf5b5)[0x555f6211f5b5]
[fv-az95-172:60558] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1f3704e0b3]
[fv-az95-172:60558] [ 9] plumed_master(+0xf8be)[0x555f6211f8be]
[fv-az95-172:60558] *** End of error message ***
</pre>
{% endraw %}
