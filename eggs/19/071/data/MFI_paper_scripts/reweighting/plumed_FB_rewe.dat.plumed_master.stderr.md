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
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[fv-az2035-366:11995] *** Process received signal ***
[fv-az2035-366:11995] Signal: Aborted (6)
[fv-az2035-366:11995] Signal code:  (-6)
[fv-az2035-366:11995] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b90645330]
[fv-az2035-366:11995] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b9069eb2c]
[fv-az2035-366:11995] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b9064527e]
[fv-az2035-366:11995] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b906288ff]
[fv-az2035-366:11995] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b90aa5ff5]
[fv-az2035-366:11995] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b90abb0da]
[fv-az2035-366:11995] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b90aa5a55]
[fv-az2035-366:11995] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b90aa5a6f]
[fv-az2035-366:11995] [ 8] plumed_master(+0x146dd)[0x55992d0876dd]
[fv-az2035-366:11995] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b9062a1ca]
[fv-az2035-366:11995] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b9062a28b]
[fv-az2035-366:11995] [11] plumed_master(+0x15365)[0x55992d088365]
[fv-az2035-366:11995] *** End of error message ***
</pre>
{% endraw %}
