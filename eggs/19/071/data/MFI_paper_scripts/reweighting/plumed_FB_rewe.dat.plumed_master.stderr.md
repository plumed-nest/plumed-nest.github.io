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
(tools/Grid.cpp:547) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[fv-az1215-453:08993] *** Process received signal ***
[fv-az1215-453:08993] Signal: Aborted (6)
[fv-az1215-453:08993] Signal code:  (-6)
[fv-az1215-453:08993] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0c3fc42520]
[fv-az1215-453:08993] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0c3fc969fc]
[fv-az1215-453:08993] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0c3fc42476]
[fv-az1215-453:08993] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0c3fc287f3]
[fv-az1215-453:08993] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0c400a2b9e]
[fv-az1215-453:08993] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0c400ae20c]
[fv-az1215-453:08993] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0c400ae277]
[fv-az1215-453:08993] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0c400ae52b]
[fv-az1215-453:08993] [ 8] plumed_master(+0x14274)[0x5580280df274]
[fv-az1215-453:08993] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0c3fc29d90]
[fv-az1215-453:08993] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0c3fc29e40]
[fv-az1215-453:08993] [11] plumed_master(+0x14ed5)[0x5580280dfed5]
[fv-az1215-453:08993] *** End of error message ***
</pre>
{% endraw %}
