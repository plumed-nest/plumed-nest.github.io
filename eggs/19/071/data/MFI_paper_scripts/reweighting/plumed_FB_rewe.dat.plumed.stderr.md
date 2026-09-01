**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed.stderr.txt.zip) 
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
[runnervmgx7h7:10839] *** Process received signal ***
[runnervmgx7h7:10839] Signal: Aborted (6)
[runnervmgx7h7:10839] Signal code:  (-6)
[runnervmgx7h7:10839] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a69a45330]
[runnervmgx7h7:10839] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a69a9ec0c]
[runnervmgx7h7:10839] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a69a4527e]
[runnervmgx7h7:10839] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a69a288ff]
[runnervmgx7h7:10839] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a69ea5ff5]
[runnervmgx7h7:10839] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a69ebb0da]
[runnervmgx7h7:10839] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a69ea5a55]
[runnervmgx7h7:10839] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a69ea5a6f]
[runnervmgx7h7:10839] [ 8] plumed(+0x146dd)[0x560d6440a6dd]
[runnervmgx7h7:10839] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a69a2a1ca]
[runnervmgx7h7:10839] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a69a2a28b]
[runnervmgx7h7:10839] [11] plumed(+0x15365)[0x560d6440b365]
[runnervmgx7h7:10839] *** End of error message ***
</pre>
{% endraw %}
