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
[runnervm0kj6c:05465] *** Process received signal ***
[runnervm0kj6c:05465] Signal: Aborted (6)
[runnervm0kj6c:05465] Signal code:  (-6)
[runnervm0kj6c:05465] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf0ea45330]
[runnervm0kj6c:05465] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf0ea9eb2c]
[runnervm0kj6c:05465] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf0ea4527e]
[runnervm0kj6c:05465] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf0ea288ff]
[runnervm0kj6c:05465] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf0eea5ff5]
[runnervm0kj6c:05465] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf0eebb0da]
[runnervm0kj6c:05465] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf0eea5a55]
[runnervm0kj6c:05465] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf0eea5a6f]
[runnervm0kj6c:05465] [ 8] plumed(+0x146dd)[0x55b805b816dd]
[runnervm0kj6c:05465] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf0ea2a1ca]
[runnervm0kj6c:05465] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf0ea2a28b]
[runnervm0kj6c:05465] [11] plumed(+0x15365)[0x55b805b82365]
[runnervm0kj6c:05465] *** End of error message ***
</pre>
{% endraw %}
