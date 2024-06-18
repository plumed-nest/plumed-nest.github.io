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
[fv-az1215-453:08985] *** Process received signal ***
[fv-az1215-453:08985] Signal: Aborted (6)
[fv-az1215-453:08985] Signal code:  (-6)
[fv-az1215-453:08985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1ff7a42520]
[fv-az1215-453:08985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1ff7a969fc]
[fv-az1215-453:08985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1ff7a42476]
[fv-az1215-453:08985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1ff7a287f3]
[fv-az1215-453:08985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1ff7ea2b9e]
[fv-az1215-453:08985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1ff7eae20c]
[fv-az1215-453:08985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1ff7eae277]
[fv-az1215-453:08985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1ff7eae52b]
[fv-az1215-453:08985] [ 8] plumed(+0x12f48)[0x55d789efbf48]
[fv-az1215-453:08985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1ff7a29d90]
[fv-az1215-453:08985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1ff7a29e40]
[fv-az1215-453:08985] [11] plumed(+0x131e5)[0x55d789efc1e5]
[fv-az1215-453:08985] *** End of error message ***
</pre>
{% endraw %}
