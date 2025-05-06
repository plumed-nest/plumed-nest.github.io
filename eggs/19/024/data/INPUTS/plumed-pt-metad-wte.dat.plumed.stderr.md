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
[fv-az1278-681:67812] *** Process received signal ***
[fv-az1278-681:67812] Signal: Aborted (6)
[fv-az1278-681:67812] Signal code:  (-6)
[fv-az1278-681:67812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f936b845330]
[fv-az1278-681:67812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f936b89eb2c]
[fv-az1278-681:67812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f936b84527e]
[fv-az1278-681:67812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f936b8288ff]
[fv-az1278-681:67812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f936bca5ff5]
[fv-az1278-681:67812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f936bcbb0da]
[fv-az1278-681:67812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f936bca5a55]
[fv-az1278-681:67812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f936bca5a6f]
[fv-az1278-681:67812] [ 8] plumed(+0x146dd)[0x5592a95c56dd]
[fv-az1278-681:67812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f936b82a1ca]
[fv-az1278-681:67812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f936b82a28b]
[fv-az1278-681:67812] [11] plumed(+0x15365)[0x5592a95c6365]
[fv-az1278-681:67812] *** End of error message ***
</pre>
{% endraw %}
