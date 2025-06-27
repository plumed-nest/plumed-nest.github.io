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
[pkrvmbietmlfzoi:65625] *** Process received signal ***
[pkrvmbietmlfzoi:65625] Signal: Aborted (6)
[pkrvmbietmlfzoi:65625] Signal code:  (-6)
[pkrvmbietmlfzoi:65625] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3055a45330]
[pkrvmbietmlfzoi:65625] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3055a9eb2c]
[pkrvmbietmlfzoi:65625] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3055a4527e]
[pkrvmbietmlfzoi:65625] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3055a288ff]
[pkrvmbietmlfzoi:65625] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3055ea5ff5]
[pkrvmbietmlfzoi:65625] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3055ebb0da]
[pkrvmbietmlfzoi:65625] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3055ea5a55]
[pkrvmbietmlfzoi:65625] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3055ea5a6f]
[pkrvmbietmlfzoi:65625] [ 8] plumed_master(+0x146dd)[0x56237f30c6dd]
[pkrvmbietmlfzoi:65625] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3055a2a1ca]
[pkrvmbietmlfzoi:65625] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3055a2a28b]
[pkrvmbietmlfzoi:65625] [11] plumed_master(+0x15365)[0x56237f30d365]
[pkrvmbietmlfzoi:65625] *** End of error message ***
</pre>
{% endraw %}
