**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmi13qx:32933] *** Process received signal ***
[runnervmi13qx:32933] Signal: Aborted (6)
[runnervmi13qx:32933] Signal code:  (-6)
[runnervmi13qx:32933] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f792fa45330]
[runnervmi13qx:32933] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f792fa9eb2c]
[runnervmi13qx:32933] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f792fa4527e]
[runnervmi13qx:32933] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f792fa288ff]
[runnervmi13qx:32933] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f792fea5ff5]
[runnervmi13qx:32933] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f792febb0da]
[runnervmi13qx:32933] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f792fea5a55]
[runnervmi13qx:32933] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f792fea5a6f]
[runnervmi13qx:32933] [ 8] plumed_master(+0x146dd)[0x5645fc7d76dd]
[runnervmi13qx:32933] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f792fa2a1ca]
[runnervmi13qx:32933] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f792fa2a28b]
[runnervmi13qx:32933] [11] plumed_master(+0x15365)[0x5645fc7d8365]
[runnervmi13qx:32933] *** End of error message ***
</pre>
{% endraw %}
