**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[fv-az1267-279:67054] *** Process received signal ***
[fv-az1267-279:67054] Signal: Aborted (6)
[fv-az1267-279:67054] Signal code:  (-6)
[fv-az1267-279:67054] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b3a445330]
[fv-az1267-279:67054] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b3a49eb2c]
[fv-az1267-279:67054] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b3a44527e]
[fv-az1267-279:67054] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b3a4288ff]
[fv-az1267-279:67054] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b3a8a5ff5]
[fv-az1267-279:67054] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b3a8bb0da]
[fv-az1267-279:67054] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b3a8a5a55]
[fv-az1267-279:67054] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b3a8a5a6f]
[fv-az1267-279:67054] [ 8] plumed(+0x146dd)[0x55a6d72ce6dd]
[fv-az1267-279:67054] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b3a42a1ca]
[fv-az1267-279:67054] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b3a42a28b]
[fv-az1267-279:67054] [11] plumed(+0x15365)[0x55a6d72cf365]
[fv-az1267-279:67054] *** End of error message ***
</pre>
{% endraw %}
