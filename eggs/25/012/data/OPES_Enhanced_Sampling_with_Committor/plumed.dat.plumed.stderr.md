**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[pkrvmf6wy0o8zjz:33186] *** Process received signal ***
[pkrvmf6wy0o8zjz:33186] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33186] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6011245330]
[pkrvmf6wy0o8zjz:33186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f601129eb2c]
[pkrvmf6wy0o8zjz:33186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f601124527e]
[pkrvmf6wy0o8zjz:33186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60112288ff]
[pkrvmf6wy0o8zjz:33186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60116a5ff5]
[pkrvmf6wy0o8zjz:33186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60116bb0da]
[pkrvmf6wy0o8zjz:33186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60116a5a55]
[pkrvmf6wy0o8zjz:33186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60116a5a6f]
[pkrvmf6wy0o8zjz:33186] [ 8] plumed(+0x146dd)[0x5650e038b6dd]
[pkrvmf6wy0o8zjz:33186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f601122a1ca]
[pkrvmf6wy0o8zjz:33186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f601122a28b]
[pkrvmf6wy0o8zjz:33186] [11] plumed(+0x15365)[0x5650e038c365]
[pkrvmf6wy0o8zjz:33186] *** End of error message ***
</pre>
{% endraw %}
