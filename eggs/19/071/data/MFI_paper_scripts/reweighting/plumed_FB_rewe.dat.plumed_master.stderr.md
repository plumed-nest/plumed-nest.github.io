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
[fv-az789-879:67161] *** Process received signal ***
[fv-az789-879:67161] Signal: Aborted (6)
[fv-az789-879:67161] Signal code:  (-6)
[fv-az789-879:67161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3995045330]
[fv-az789-879:67161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f399509eb2c]
[fv-az789-879:67161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f399504527e]
[fv-az789-879:67161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39950288ff]
[fv-az789-879:67161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39954a5ff5]
[fv-az789-879:67161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39954bb0da]
[fv-az789-879:67161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39954a5a55]
[fv-az789-879:67161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39954a5a6f]
[fv-az789-879:67161] [ 8] plumed_master(+0x146dd)[0x559681dce6dd]
[fv-az789-879:67161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f399502a1ca]
[fv-az789-879:67161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f399502a28b]
[fv-az789-879:67161] [11] plumed_master(+0x15365)[0x559681dcf365]
[fv-az789-879:67161] *** End of error message ***
</pre>
{% endraw %}
