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
[runnervmvrwv9:10272] *** Process received signal ***
[runnervmvrwv9:10272] Signal: Aborted (6)
[runnervmvrwv9:10272] Signal code:  (-6)
[runnervmvrwv9:10272] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbe0045330]
[runnervmvrwv9:10272] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbe009eb2c]
[runnervmvrwv9:10272] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbe004527e]
[runnervmvrwv9:10272] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbe00288ff]
[runnervmvrwv9:10272] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbe04a5ff5]
[runnervmvrwv9:10272] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbe04bb0da]
[runnervmvrwv9:10272] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbe04a5a55]
[runnervmvrwv9:10272] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbe04a5a6f]
[runnervmvrwv9:10272] [ 8] plumed(+0x146dd)[0x563a205606dd]
[runnervmvrwv9:10272] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbe002a1ca]
[runnervmvrwv9:10272] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbe002a28b]
[runnervmvrwv9:10272] [11] plumed(+0x15365)[0x563a20561365]
[runnervmvrwv9:10272] *** End of error message ***
</pre>
{% endraw %}
