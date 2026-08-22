**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_cal.dat   
Download: [zipped raw stdout](plumed_cal.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_cal.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervm76f27:04124] *** Process received signal ***
[runnervm76f27:04124] Signal: Aborted (6)
[runnervm76f27:04124] Signal code:  (-6)
[runnervm76f27:04124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf61845330]
[runnervm76f27:04124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf6189ec0c]
[runnervm76f27:04124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf6184527e]
[runnervm76f27:04124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf618288ff]
[runnervm76f27:04124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf61ca5ff5]
[runnervm76f27:04124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf61cbb0da]
[runnervm76f27:04124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf61ca5a55]
[runnervm76f27:04124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf61ca5a6f]
[runnervm76f27:04124] [ 8] plumed(+0x146dd)[0x55acd2a686dd]
[runnervm76f27:04124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf6182a1ca]
[runnervm76f27:04124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf6182a28b]
[runnervm76f27:04124] [11] plumed(+0x15365)[0x55acd2a69365]
[runnervm76f27:04124] *** End of error message ***
</pre>
{% endraw %}
