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
[pkrvmbietmlfzoi:13022] *** Process received signal ***
[pkrvmbietmlfzoi:13022] Signal: Aborted (6)
[pkrvmbietmlfzoi:13022] Signal code:  (-6)
[pkrvmbietmlfzoi:13022] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f7fe45330]
[pkrvmbietmlfzoi:13022] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f7fe9eb2c]
[pkrvmbietmlfzoi:13022] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f7fe4527e]
[pkrvmbietmlfzoi:13022] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f7fe288ff]
[pkrvmbietmlfzoi:13022] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f802a5ff5]
[pkrvmbietmlfzoi:13022] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f802bb0da]
[pkrvmbietmlfzoi:13022] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f802a5a55]
[pkrvmbietmlfzoi:13022] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f802a5a6f]
[pkrvmbietmlfzoi:13022] [ 8] plumed_master(+0x146dd)[0x5605c66d16dd]
[pkrvmbietmlfzoi:13022] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f7fe2a1ca]
[pkrvmbietmlfzoi:13022] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f7fe2a28b]
[pkrvmbietmlfzoi:13022] [11] plumed_master(+0x15365)[0x5605c66d2365]
[pkrvmbietmlfzoi:13022] *** End of error message ***
</pre>
{% endraw %}
