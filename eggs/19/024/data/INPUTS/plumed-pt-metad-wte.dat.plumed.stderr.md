**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervmmklqx:12263] *** Process received signal ***
[runnervmmklqx:12263] Signal: Aborted (6)
[runnervmmklqx:12263] Signal code:  (-6)
[runnervmmklqx:12263] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f496f445330]
[runnervmmklqx:12263] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f496f49eb2c]
[runnervmmklqx:12263] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f496f44527e]
[runnervmmklqx:12263] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f496f4288ff]
[runnervmmklqx:12263] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f496f8a5ff5]
[runnervmmklqx:12263] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f496f8bb0da]
[runnervmmklqx:12263] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f496f8a5a55]
[runnervmmklqx:12263] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f496f8a5a6f]
[runnervmmklqx:12263] [ 8] plumed(+0x146dd)[0x55c47a9b06dd]
[runnervmmklqx:12263] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f496f42a1ca]
[runnervmmklqx:12263] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f496f42a28b]
[runnervmmklqx:12263] [11] plumed(+0x15365)[0x55c47a9b1365]
[runnervmmklqx:12263] *** End of error message ***
</pre>
{% endraw %}
