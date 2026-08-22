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
[runnervm76f27:11195] *** Process received signal ***
[runnervm76f27:11195] Signal: Aborted (6)
[runnervm76f27:11195] Signal code:  (-6)
[runnervm76f27:11195] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe2f9045330]
[runnervm76f27:11195] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe2f909ec0c]
[runnervm76f27:11195] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe2f904527e]
[runnervm76f27:11195] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2f90288ff]
[runnervm76f27:11195] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2f94a5ff5]
[runnervm76f27:11195] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2f94bb0da]
[runnervm76f27:11195] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2f94a5a55]
[runnervm76f27:11195] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2f94a5a6f]
[runnervm76f27:11195] [ 8] plumed_master(+0x146dd)[0x55fcf248f6dd]
[runnervm76f27:11195] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe2f902a1ca]
[runnervm76f27:11195] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe2f902a28b]
[runnervm76f27:11195] [11] plumed_master(+0x15365)[0x55fcf2490365]
[runnervm76f27:11195] *** End of error message ***
</pre>
{% endraw %}
