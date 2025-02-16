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
[fv-az1112-175:70109] *** Process received signal ***
[fv-az1112-175:70109] Signal: Aborted (6)
[fv-az1112-175:70109] Signal code:  (-6)
[fv-az1112-175:70109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea0fc45330]
[fv-az1112-175:70109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea0fc9eb2c]
[fv-az1112-175:70109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea0fc4527e]
[fv-az1112-175:70109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea0fc288ff]
[fv-az1112-175:70109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea100a5ff5]
[fv-az1112-175:70109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea100bb0da]
[fv-az1112-175:70109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea100a5a55]
[fv-az1112-175:70109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea100a5a6f]
[fv-az1112-175:70109] [ 8] plumed(+0x146dd)[0x55eea5ab26dd]
[fv-az1112-175:70109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea0fc2a1ca]
[fv-az1112-175:70109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea0fc2a28b]
[fv-az1112-175:70109] [11] plumed(+0x15365)[0x55eea5ab3365]
[fv-az1112-175:70109] *** End of error message ***
</pre>
{% endraw %}
