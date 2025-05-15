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
[pkrvmberfyhpb9w:12300] *** Process received signal ***
[pkrvmberfyhpb9w:12300] Signal: Aborted (6)
[pkrvmberfyhpb9w:12300] Signal code:  (-6)
[pkrvmberfyhpb9w:12300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d16045330]
[pkrvmberfyhpb9w:12300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d1609eb2c]
[pkrvmberfyhpb9w:12300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d1604527e]
[pkrvmberfyhpb9w:12300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d160288ff]
[pkrvmberfyhpb9w:12300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d164a5ff5]
[pkrvmberfyhpb9w:12300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d164bb0da]
[pkrvmberfyhpb9w:12300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d164a5a55]
[pkrvmberfyhpb9w:12300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d164a5a6f]
[pkrvmberfyhpb9w:12300] [ 8] plumed(+0x146dd)[0x55556426c6dd]
[pkrvmberfyhpb9w:12300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d1602a1ca]
[pkrvmberfyhpb9w:12300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d1602a28b]
[pkrvmberfyhpb9w:12300] [11] plumed(+0x15365)[0x55556426d365]
[pkrvmberfyhpb9w:12300] *** End of error message ***
</pre>
{% endraw %}
