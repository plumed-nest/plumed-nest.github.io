**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
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
[pkrvmpptgkbjq6m:12881] *** Process received signal ***
[pkrvmpptgkbjq6m:12881] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12881] Signal code:  (-6)
[pkrvmpptgkbjq6m:12881] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf1a045330]
[pkrvmpptgkbjq6m:12881] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf1a09eb2c]
[pkrvmpptgkbjq6m:12881] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf1a04527e]
[pkrvmpptgkbjq6m:12881] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf1a0288ff]
[pkrvmpptgkbjq6m:12881] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf1a4a5ff5]
[pkrvmpptgkbjq6m:12881] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf1a4bb0da]
[pkrvmpptgkbjq6m:12881] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf1a4a5a55]
[pkrvmpptgkbjq6m:12881] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf1a4a5a6f]
[pkrvmpptgkbjq6m:12881] [ 8] plumed_master(+0x146dd)[0x55d9b532f6dd]
[pkrvmpptgkbjq6m:12881] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf1a02a1ca]
[pkrvmpptgkbjq6m:12881] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf1a02a28b]
[pkrvmpptgkbjq6m:12881] [11] plumed_master(+0x15365)[0x55d9b5330365]
[pkrvmpptgkbjq6m:12881] *** End of error message ***
</pre>
{% endraw %}
