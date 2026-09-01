**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervmgx7h7:10855] *** Process received signal ***
[runnervmgx7h7:10855] Signal: Aborted (6)
[runnervmgx7h7:10855] Signal code:  (-6)
[runnervmgx7h7:10855] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc264a45330]
[runnervmgx7h7:10855] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc264a9ec0c]
[runnervmgx7h7:10855] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc264a4527e]
[runnervmgx7h7:10855] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc264a288ff]
[runnervmgx7h7:10855] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc264ea5ff5]
[runnervmgx7h7:10855] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc264ebb0da]
[runnervmgx7h7:10855] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc264ea5a55]
[runnervmgx7h7:10855] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc264ea5a6f]
[runnervmgx7h7:10855] [ 8] plumed_master(+0x146dd)[0x562c16b6f6dd]
[runnervmgx7h7:10855] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc264a2a1ca]
[runnervmgx7h7:10855] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc264a2a28b]
[runnervmgx7h7:10855] [11] plumed_master(+0x15365)[0x562c16b70365]
[runnervmgx7h7:10855] *** End of error message ***
</pre>
{% endraw %}
