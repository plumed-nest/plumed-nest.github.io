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
[pkrvmxyh4eaekms:15415] *** Process received signal ***
[pkrvmxyh4eaekms:15415] Signal: Aborted (6)
[pkrvmxyh4eaekms:15415] Signal code:  (-6)
[pkrvmxyh4eaekms:15415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f25cf245330]
[pkrvmxyh4eaekms:15415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f25cf29eb2c]
[pkrvmxyh4eaekms:15415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f25cf24527e]
[pkrvmxyh4eaekms:15415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25cf2288ff]
[pkrvmxyh4eaekms:15415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25cf6a5ff5]
[pkrvmxyh4eaekms:15415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25cf6bb0da]
[pkrvmxyh4eaekms:15415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25cf6a5a55]
[pkrvmxyh4eaekms:15415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25cf6a5a6f]
[pkrvmxyh4eaekms:15415] [ 8] plumed(+0x146dd)[0x55db86dc76dd]
[pkrvmxyh4eaekms:15415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f25cf22a1ca]
[pkrvmxyh4eaekms:15415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f25cf22a28b]
[pkrvmxyh4eaekms:15415] [11] plumed(+0x15365)[0x55db86dc8365]
[pkrvmxyh4eaekms:15415] *** End of error message ***
</pre>
{% endraw %}
