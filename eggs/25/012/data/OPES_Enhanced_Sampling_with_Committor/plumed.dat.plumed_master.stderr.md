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
[runnervm0kj6c:05480] *** Process received signal ***
[runnervm0kj6c:05480] Signal: Aborted (6)
[runnervm0kj6c:05480] Signal code:  (-6)
[runnervm0kj6c:05480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ff9845330]
[runnervm0kj6c:05480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ff989eb2c]
[runnervm0kj6c:05480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ff984527e]
[runnervm0kj6c:05480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ff98288ff]
[runnervm0kj6c:05480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ff9ca5ff5]
[runnervm0kj6c:05480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ff9cbb0da]
[runnervm0kj6c:05480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ff9ca5a55]
[runnervm0kj6c:05480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ff9ca5a6f]
[runnervm0kj6c:05480] [ 8] plumed_master(+0x146dd)[0x563913fb96dd]
[runnervm0kj6c:05480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ff982a1ca]
[runnervm0kj6c:05480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ff982a28b]
[runnervm0kj6c:05480] [11] plumed_master(+0x15365)[0x563913fba365]
[runnervm0kj6c:05480] *** End of error message ***
</pre>
{% endraw %}
