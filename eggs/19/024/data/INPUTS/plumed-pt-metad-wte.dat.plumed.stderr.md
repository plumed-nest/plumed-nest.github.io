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
[runnervmeorf1:11806] *** Process received signal ***
[runnervmeorf1:11806] Signal: Aborted (6)
[runnervmeorf1:11806] Signal code:  (-6)
[runnervmeorf1:11806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5599e45330]
[runnervmeorf1:11806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5599e9eb2c]
[runnervmeorf1:11806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5599e4527e]
[runnervmeorf1:11806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5599e288ff]
[runnervmeorf1:11806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f559a2a5ff5]
[runnervmeorf1:11806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f559a2bb0da]
[runnervmeorf1:11806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f559a2a5a55]
[runnervmeorf1:11806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f559a2a5a6f]
[runnervmeorf1:11806] [ 8] plumed(+0x146dd)[0x560a9d8a76dd]
[runnervmeorf1:11806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5599e2a1ca]
[runnervmeorf1:11806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5599e2a28b]
[runnervmeorf1:11806] [11] plumed(+0x15365)[0x560a9d8a8365]
[runnervmeorf1:11806] *** End of error message ***
</pre>
{% endraw %}
