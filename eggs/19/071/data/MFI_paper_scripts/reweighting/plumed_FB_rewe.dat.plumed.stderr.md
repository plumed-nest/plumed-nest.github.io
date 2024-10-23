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
(tools/Grid.cpp:547) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[fv-az802-461:10756] *** Process received signal ***
[fv-az802-461:10756] Signal: Aborted (6)
[fv-az802-461:10756] Signal code:  (-6)
[fv-az802-461:10756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f90d9642520]
[fv-az802-461:10756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f90d96969fc]
[fv-az802-461:10756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f90d9642476]
[fv-az802-461:10756] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f90d96287f3]
[fv-az802-461:10756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f90d9aa2b9e]
[fv-az802-461:10756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f90d9aae20c]
[fv-az802-461:10756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f90d9aae277]
[fv-az802-461:10756] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f90d9aae52b]
[fv-az802-461:10756] [ 8] plumed(+0x14254)[0x55df101ca254]
[fv-az802-461:10756] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f90d9629d90]
[fv-az802-461:10756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f90d9629e40]
[fv-az802-461:10756] [11] plumed(+0x14eb5)[0x55df101caeb5]
[fv-az802-461:10756] *** End of error message ***
</pre>
{% endraw %}
