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
[runnervmgx7h7:07335] *** Process received signal ***
[runnervmgx7h7:07335] Signal: Aborted (6)
[runnervmgx7h7:07335] Signal code:  (-6)
[runnervmgx7h7:07335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ed3a45330]
[runnervmgx7h7:07335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ed3a9ec0c]
[runnervmgx7h7:07335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ed3a4527e]
[runnervmgx7h7:07335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ed3a288ff]
[runnervmgx7h7:07335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ed3ea5ff5]
[runnervmgx7h7:07335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ed3ebb0da]
[runnervmgx7h7:07335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ed3ea5a55]
[runnervmgx7h7:07335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ed3ea5a6f]
[runnervmgx7h7:07335] [ 8] plumed(+0x146dd)[0x55e65cfaf6dd]
[runnervmgx7h7:07335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ed3a2a1ca]
[runnervmgx7h7:07335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ed3a2a28b]
[runnervmgx7h7:07335] [11] plumed(+0x15365)[0x55e65cfb0365]
[runnervmgx7h7:07335] *** End of error message ***
</pre>
{% endraw %}
