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
(tools/Grid.cpp:564) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[fv-az1535-957:72327] *** Process received signal ***
[fv-az1535-957:72327] Signal: Aborted (6)
[fv-az1535-957:72327] Signal code:  (-6)
[fv-az1535-957:72327] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff199e42520]
[fv-az1535-957:72327] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff199e969fc]
[fv-az1535-957:72327] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff199e42476]
[fv-az1535-957:72327] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff199e287f3]
[fv-az1535-957:72327] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7ff19a2a4f26]
[fv-az1535-957:72327] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7ff19a2b6d9c]
[fv-az1535-957:72327] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7ff19a2b6e07]
[fv-az1535-957:72327] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff19a2b70bb]
[fv-az1535-957:72327] [ 8] plumed(+0x12f48)[0x564b071bff48]
[fv-az1535-957:72327] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff199e29d90]
[fv-az1535-957:72327] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff199e29e40]
[fv-az1535-957:72327] [11] plumed(+0x131e5)[0x564b071c01e5]
[fv-az1535-957:72327] *** End of error message ***
</pre>
{% endraw %}
