**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_ala.dat   
Download: [zipped raw stdout](plumed_ala.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_ala.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library OPESmetad.so
OPESmetad.so: cannot open shared object file: No such file or directory
[runnervm76f27:04088] *** Process received signal ***
[runnervm76f27:04088] Signal: Aborted (6)
[runnervm76f27:04088] Signal code:  (-6)
[runnervm76f27:04088] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62b4645330]
[runnervm76f27:04088] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62b469ec0c]
[runnervm76f27:04088] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62b464527e]
[runnervm76f27:04088] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62b46288ff]
[runnervm76f27:04088] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62b4aa5ff5]
[runnervm76f27:04088] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62b4abb0da]
[runnervm76f27:04088] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62b4aa5a55]
[runnervm76f27:04088] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62b4aa5a6f]
[runnervm76f27:04088] [ 8] plumed_master(+0x146dd)[0x55dfd7ef96dd]
[runnervm76f27:04088] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62b462a1ca]
[runnervm76f27:04088] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62b462a28b]
[runnervm76f27:04088] [11] plumed_master(+0x15365)[0x55dfd7efa365]
[runnervm76f27:04088] *** End of error message ***
</pre>
{% endraw %}
