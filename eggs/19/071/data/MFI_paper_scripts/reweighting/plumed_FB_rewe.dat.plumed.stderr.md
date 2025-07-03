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
[pkrvmbietmlfzoi:12335] *** Process received signal ***
[pkrvmbietmlfzoi:12335] Signal: Aborted (6)
[pkrvmbietmlfzoi:12335] Signal code:  (-6)
[pkrvmbietmlfzoi:12335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca28845330]
[pkrvmbietmlfzoi:12335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca2889eb2c]
[pkrvmbietmlfzoi:12335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca2884527e]
[pkrvmbietmlfzoi:12335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca288288ff]
[pkrvmbietmlfzoi:12335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca28ca5ff5]
[pkrvmbietmlfzoi:12335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca28cbb0da]
[pkrvmbietmlfzoi:12335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca28ca5a55]
[pkrvmbietmlfzoi:12335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca28ca5a6f]
[pkrvmbietmlfzoi:12335] [ 8] plumed(+0x146dd)[0x55d6e81a36dd]
[pkrvmbietmlfzoi:12335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca2882a1ca]
[pkrvmbietmlfzoi:12335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca2882a28b]
[pkrvmbietmlfzoi:12335] [11] plumed(+0x15365)[0x55d6e81a4365]
[pkrvmbietmlfzoi:12335] *** End of error message ***
</pre>
{% endraw %}
