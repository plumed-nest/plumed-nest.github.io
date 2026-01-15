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
[runnervmmtnos:39204] *** Process received signal ***
[runnervmmtnos:39204] Signal: Aborted (6)
[runnervmmtnos:39204] Signal code:  (-6)
[runnervmmtnos:39204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c51845330]
[runnervmmtnos:39204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c5189eb2c]
[runnervmmtnos:39204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c5184527e]
[runnervmmtnos:39204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c518288ff]
[runnervmmtnos:39204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c51ca5ff5]
[runnervmmtnos:39204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c51cbb0da]
[runnervmmtnos:39204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c51ca5a55]
[runnervmmtnos:39204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c51ca5a6f]
[runnervmmtnos:39204] [ 8] plumed(+0x146dd)[0x558b960876dd]
[runnervmmtnos:39204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c5182a1ca]
[runnervmmtnos:39204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c5182a28b]
[runnervmmtnos:39204] [11] plumed(+0x15365)[0x558b96088365]
[runnervmmtnos:39204] *** End of error message ***
</pre>
{% endraw %}
