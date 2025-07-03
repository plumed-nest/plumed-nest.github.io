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
[pkrvmbietmlfzoi:13006] *** Process received signal ***
[pkrvmbietmlfzoi:13006] Signal: Aborted (6)
[pkrvmbietmlfzoi:13006] Signal code:  (-6)
[pkrvmbietmlfzoi:13006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc034a45330]
[pkrvmbietmlfzoi:13006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc034a9eb2c]
[pkrvmbietmlfzoi:13006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc034a4527e]
[pkrvmbietmlfzoi:13006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc034a288ff]
[pkrvmbietmlfzoi:13006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc034ea5ff5]
[pkrvmbietmlfzoi:13006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc034ebb0da]
[pkrvmbietmlfzoi:13006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc034ea5a55]
[pkrvmbietmlfzoi:13006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc034ea5a6f]
[pkrvmbietmlfzoi:13006] [ 8] plumed(+0x146dd)[0x55aecfa6c6dd]
[pkrvmbietmlfzoi:13006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc034a2a1ca]
[pkrvmbietmlfzoi:13006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc034a2a28b]
[pkrvmbietmlfzoi:13006] [11] plumed(+0x15365)[0x55aecfa6d365]
[pkrvmbietmlfzoi:13006] *** End of error message ***
</pre>
{% endraw %}
