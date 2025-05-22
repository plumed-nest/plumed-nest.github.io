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
[pkrvmf6wy0o8zjz:41445] *** Process received signal ***
[pkrvmf6wy0o8zjz:41445] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:41445] Signal code:  (-6)
[pkrvmf6wy0o8zjz:41445] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4eb9e45330]
[pkrvmf6wy0o8zjz:41445] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4eb9e9eb2c]
[pkrvmf6wy0o8zjz:41445] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4eb9e4527e]
[pkrvmf6wy0o8zjz:41445] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4eb9e288ff]
[pkrvmf6wy0o8zjz:41445] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4eba2a5ff5]
[pkrvmf6wy0o8zjz:41445] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4eba2bb0da]
[pkrvmf6wy0o8zjz:41445] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4eba2a5a55]
[pkrvmf6wy0o8zjz:41445] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4eba2a5a6f]
[pkrvmf6wy0o8zjz:41445] [ 8] plumed_master(+0x146dd)[0x55fce54936dd]
[pkrvmf6wy0o8zjz:41445] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4eb9e2a1ca]
[pkrvmf6wy0o8zjz:41445] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4eb9e2a28b]
[pkrvmf6wy0o8zjz:41445] [11] plumed_master(+0x15365)[0x55fce5494365]
[pkrvmf6wy0o8zjz:41445] *** End of error message ***
</pre>
{% endraw %}
