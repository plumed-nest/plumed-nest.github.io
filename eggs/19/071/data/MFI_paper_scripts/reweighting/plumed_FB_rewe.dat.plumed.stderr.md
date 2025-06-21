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
[pkrvmxyh4eaekms:13395] *** Process received signal ***
[pkrvmxyh4eaekms:13395] Signal: Aborted (6)
[pkrvmxyh4eaekms:13395] Signal code:  (-6)
[pkrvmxyh4eaekms:13395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff620a45330]
[pkrvmxyh4eaekms:13395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff620a9eb2c]
[pkrvmxyh4eaekms:13395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff620a4527e]
[pkrvmxyh4eaekms:13395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff620a288ff]
[pkrvmxyh4eaekms:13395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff620ea5ff5]
[pkrvmxyh4eaekms:13395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff620ebb0da]
[pkrvmxyh4eaekms:13395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff620ea5a55]
[pkrvmxyh4eaekms:13395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff620ea5a6f]
[pkrvmxyh4eaekms:13395] [ 8] plumed(+0x146dd)[0x55c9f9a6f6dd]
[pkrvmxyh4eaekms:13395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff620a2a1ca]
[pkrvmxyh4eaekms:13395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff620a2a28b]
[pkrvmxyh4eaekms:13395] [11] plumed(+0x15365)[0x55c9f9a70365]
[pkrvmxyh4eaekms:13395] *** End of error message ***
</pre>
{% endraw %}
