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
[fv-az2207-973:13813] *** Process received signal ***
[fv-az2207-973:13813] Signal: Aborted (6)
[fv-az2207-973:13813] Signal code:  (-6)
[fv-az2207-973:13813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf0e445330]
[fv-az2207-973:13813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf0e49eb2c]
[fv-az2207-973:13813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf0e44527e]
[fv-az2207-973:13813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf0e4288ff]
[fv-az2207-973:13813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf0e8a5ff5]
[fv-az2207-973:13813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf0e8bb0da]
[fv-az2207-973:13813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf0e8a5a55]
[fv-az2207-973:13813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf0e8a5a6f]
[fv-az2207-973:13813] [ 8] plumed(+0x146dd)[0x5620824cc6dd]
[fv-az2207-973:13813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf0e42a1ca]
[fv-az2207-973:13813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf0e42a28b]
[fv-az2207-973:13813] [11] plumed(+0x15365)[0x5620824cd365]
[fv-az2207-973:13813] *** End of error message ***
</pre>
{% endraw %}
