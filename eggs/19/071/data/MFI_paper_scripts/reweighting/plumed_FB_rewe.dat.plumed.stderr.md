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
[fv-az1567-223:09582] *** Process received signal ***
[fv-az1567-223:09582] Signal: Aborted (6)
[fv-az1567-223:09582] Signal code:  (-6)
[fv-az1567-223:09582] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7b4ae42520]
[fv-az1567-223:09582] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7b4ae969fc]
[fv-az1567-223:09582] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7b4ae42476]
[fv-az1567-223:09582] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7b4ae287f3]
[fv-az1567-223:09582] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7b4b2a2b9e]
[fv-az1567-223:09582] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7b4b2ae20c]
[fv-az1567-223:09582] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7b4b2ae277]
[fv-az1567-223:09582] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7b4b2ae52b]
[fv-az1567-223:09582] [ 8] plumed(+0x12f48)[0x564f665eaf48]
[fv-az1567-223:09582] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7b4ae29d90]
[fv-az1567-223:09582] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7b4ae29e40]
[fv-az1567-223:09582] [11] plumed(+0x131e5)[0x564f665eb1e5]
[fv-az1567-223:09582] *** End of error message ***
</pre>
{% endraw %}
