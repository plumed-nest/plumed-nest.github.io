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
[runnervmw9dnm:11668] *** Process received signal ***
[runnervmw9dnm:11668] Signal: Aborted (6)
[runnervmw9dnm:11668] Signal code:  (-6)
[runnervmw9dnm:11668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0ff045330]
[runnervmw9dnm:11668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0ff09eb2c]
[runnervmw9dnm:11668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0ff04527e]
[runnervmw9dnm:11668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0ff0288ff]
[runnervmw9dnm:11668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0ff4a5ff5]
[runnervmw9dnm:11668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0ff4bb0da]
[runnervmw9dnm:11668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0ff4a5a55]
[runnervmw9dnm:11668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0ff4a5a6f]
[runnervmw9dnm:11668] [ 8] plumed_master(+0x146dd)[0x558fa31b16dd]
[runnervmw9dnm:11668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0ff02a1ca]
[runnervmw9dnm:11668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0ff02a28b]
[runnervmw9dnm:11668] [11] plumed_master(+0x15365)[0x558fa31b2365]
[runnervmw9dnm:11668] *** End of error message ***
</pre>
{% endraw %}
