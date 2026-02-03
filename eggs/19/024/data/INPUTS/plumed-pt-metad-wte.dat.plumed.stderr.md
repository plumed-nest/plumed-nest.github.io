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
[runnervmkj6or:10019] *** Process received signal ***
[runnervmkj6or:10019] Signal: Aborted (6)
[runnervmkj6or:10019] Signal code:  (-6)
[runnervmkj6or:10019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99fd245330]
[runnervmkj6or:10019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99fd29eb2c]
[runnervmkj6or:10019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99fd24527e]
[runnervmkj6or:10019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99fd2288ff]
[runnervmkj6or:10019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99fd6a5ff5]
[runnervmkj6or:10019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99fd6bb0da]
[runnervmkj6or:10019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99fd6a5a55]
[runnervmkj6or:10019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99fd6a5a6f]
[runnervmkj6or:10019] [ 8] plumed(+0x146dd)[0x56204f0ac6dd]
[runnervmkj6or:10019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99fd22a1ca]
[runnervmkj6or:10019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99fd22a28b]
[runnervmkj6or:10019] [11] plumed(+0x15365)[0x56204f0ad365]
[runnervmkj6or:10019] *** End of error message ***
</pre>
{% endraw %}
