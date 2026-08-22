**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_chi.dat   
Download: [zipped raw stdout](plumed_chi.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_chi.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervm76f27:04175] *** Process received signal ***
[runnervm76f27:04175] Signal: Aborted (6)
[runnervm76f27:04175] Signal code:  (-6)
[runnervm76f27:04175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7bc8845330]
[runnervm76f27:04175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7bc889ec0c]
[runnervm76f27:04175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7bc884527e]
[runnervm76f27:04175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7bc88288ff]
[runnervm76f27:04175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7bc8ca5ff5]
[runnervm76f27:04175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7bc8cbb0da]
[runnervm76f27:04175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7bc8ca5a55]
[runnervm76f27:04175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7bc8ca5a6f]
[runnervm76f27:04175] [ 8] plumed(+0x146dd)[0x55853a0916dd]
[runnervm76f27:04175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7bc882a1ca]
[runnervm76f27:04175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7bc882a28b]
[runnervm76f27:04175] [11] plumed(+0x15365)[0x55853a092365]
[runnervm76f27:04175] *** End of error message ***
</pre>
{% endraw %}
