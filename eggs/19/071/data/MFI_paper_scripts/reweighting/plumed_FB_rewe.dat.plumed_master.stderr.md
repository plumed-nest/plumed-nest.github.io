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
[runnervmvrwv9:10288] *** Process received signal ***
[runnervmvrwv9:10288] Signal: Aborted (6)
[runnervmvrwv9:10288] Signal code:  (-6)
[runnervmvrwv9:10288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfe3645330]
[runnervmvrwv9:10288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfe369eb2c]
[runnervmvrwv9:10288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfe364527e]
[runnervmvrwv9:10288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfe36288ff]
[runnervmvrwv9:10288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfe3aa5ff5]
[runnervmvrwv9:10288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfe3abb0da]
[runnervmvrwv9:10288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfe3aa5a55]
[runnervmvrwv9:10288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfe3aa5a6f]
[runnervmvrwv9:10288] [ 8] plumed_master(+0x146dd)[0x55c2324076dd]
[runnervmvrwv9:10288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfe362a1ca]
[runnervmvrwv9:10288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfe362a28b]
[runnervmvrwv9:10288] [11] plumed_master(+0x15365)[0x55c232408365]
[runnervmvrwv9:10288] *** End of error message ***
</pre>
{% endraw %}
