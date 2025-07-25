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
[pkrvmpptgkbjq6m:12865] *** Process received signal ***
[pkrvmpptgkbjq6m:12865] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12865] Signal code:  (-6)
[pkrvmpptgkbjq6m:12865] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedcdc45330]
[pkrvmpptgkbjq6m:12865] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedcdc9eb2c]
[pkrvmpptgkbjq6m:12865] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedcdc4527e]
[pkrvmpptgkbjq6m:12865] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedcdc288ff]
[pkrvmpptgkbjq6m:12865] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedce0a5ff5]
[pkrvmpptgkbjq6m:12865] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedce0bb0da]
[pkrvmpptgkbjq6m:12865] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedce0a5a55]
[pkrvmpptgkbjq6m:12865] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedce0a5a6f]
[pkrvmpptgkbjq6m:12865] [ 8] plumed(+0x146dd)[0x561556d5e6dd]
[pkrvmpptgkbjq6m:12865] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedcdc2a1ca]
[pkrvmpptgkbjq6m:12865] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedcdc2a28b]
[pkrvmpptgkbjq6m:12865] [11] plumed(+0x15365)[0x561556d5f365]
[pkrvmpptgkbjq6m:12865] *** End of error message ***
</pre>
{% endraw %}
