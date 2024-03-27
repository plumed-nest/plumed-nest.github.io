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
[fv-az1535-957:72335] *** Process received signal ***
[fv-az1535-957:72335] Signal: Aborted (6)
[fv-az1535-957:72335] Signal code:  (-6)
[fv-az1535-957:72335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f335f242520]
[fv-az1535-957:72335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f335f2969fc]
[fv-az1535-957:72335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f335f242476]
[fv-az1535-957:72335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f335f2287f3]
[fv-az1535-957:72335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f335f6a4f26]
[fv-az1535-957:72335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f335f6b6d9c]
[fv-az1535-957:72335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f335f6b6e07]
[fv-az1535-957:72335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f335f6b70bb]
[fv-az1535-957:72335] [ 8] plumed_master(+0x12e7f)[0x55dfe08a9e7f]
[fv-az1535-957:72335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f335f229d90]
[fv-az1535-957:72335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f335f229e40]
[fv-az1535-957:72335] [11] plumed_master(+0x13115)[0x55dfe08aa115]
[fv-az1535-957:72335] *** End of error message ***
</pre>
{% endraw %}
