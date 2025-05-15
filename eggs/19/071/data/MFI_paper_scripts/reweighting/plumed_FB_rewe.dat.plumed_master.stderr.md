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
[pkrvmberfyhpb9w:12316] *** Process received signal ***
[pkrvmberfyhpb9w:12316] Signal: Aborted (6)
[pkrvmberfyhpb9w:12316] Signal code:  (-6)
[pkrvmberfyhpb9w:12316] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd66a045330]
[pkrvmberfyhpb9w:12316] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd66a09eb2c]
[pkrvmberfyhpb9w:12316] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd66a04527e]
[pkrvmberfyhpb9w:12316] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd66a0288ff]
[pkrvmberfyhpb9w:12316] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd66a4a5ff5]
[pkrvmberfyhpb9w:12316] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd66a4bb0da]
[pkrvmberfyhpb9w:12316] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd66a4a5a55]
[pkrvmberfyhpb9w:12316] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd66a4a5a6f]
[pkrvmberfyhpb9w:12316] [ 8] plumed_master(+0x146dd)[0x559e6533e6dd]
[pkrvmberfyhpb9w:12316] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd66a02a1ca]
[pkrvmberfyhpb9w:12316] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd66a02a28b]
[pkrvmberfyhpb9w:12316] [11] plumed_master(+0x15365)[0x559e6533f365]
[pkrvmberfyhpb9w:12316] *** End of error message ***
</pre>
{% endraw %}
