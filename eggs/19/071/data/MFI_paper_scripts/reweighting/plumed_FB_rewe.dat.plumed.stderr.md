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
[pkrvmbietmlfzoi:65609] *** Process received signal ***
[pkrvmbietmlfzoi:65609] Signal: Aborted (6)
[pkrvmbietmlfzoi:65609] Signal code:  (-6)
[pkrvmbietmlfzoi:65609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7583045330]
[pkrvmbietmlfzoi:65609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f758309eb2c]
[pkrvmbietmlfzoi:65609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f758304527e]
[pkrvmbietmlfzoi:65609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75830288ff]
[pkrvmbietmlfzoi:65609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75834a5ff5]
[pkrvmbietmlfzoi:65609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75834bb0da]
[pkrvmbietmlfzoi:65609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75834a5a55]
[pkrvmbietmlfzoi:65609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75834a5a6f]
[pkrvmbietmlfzoi:65609] [ 8] plumed(+0x146dd)[0x5636ad4786dd]
[pkrvmbietmlfzoi:65609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f758302a1ca]
[pkrvmbietmlfzoi:65609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f758302a28b]
[pkrvmbietmlfzoi:65609] [11] plumed(+0x15365)[0x5636ad479365]
[pkrvmbietmlfzoi:65609] *** End of error message ***
</pre>
{% endraw %}
