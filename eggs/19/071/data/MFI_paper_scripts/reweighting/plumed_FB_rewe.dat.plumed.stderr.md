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
[runnervmw9dnm:11652] *** Process received signal ***
[runnervmw9dnm:11652] Signal: Aborted (6)
[runnervmw9dnm:11652] Signal code:  (-6)
[runnervmw9dnm:11652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b32845330]
[runnervmw9dnm:11652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b3289eb2c]
[runnervmw9dnm:11652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b3284527e]
[runnervmw9dnm:11652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b328288ff]
[runnervmw9dnm:11652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b32ca5ff5]
[runnervmw9dnm:11652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b32cbb0da]
[runnervmw9dnm:11652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b32ca5a55]
[runnervmw9dnm:11652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b32ca5a6f]
[runnervmw9dnm:11652] [ 8] plumed(+0x146dd)[0x559abb5866dd]
[runnervmw9dnm:11652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b3282a1ca]
[runnervmw9dnm:11652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b3282a28b]
[runnervmw9dnm:11652] [11] plumed(+0x15365)[0x559abb587365]
[runnervmw9dnm:11652] *** End of error message ***
</pre>
{% endraw %}
