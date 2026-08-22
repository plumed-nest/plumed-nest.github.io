**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_trp.dat   
Download: [zipped raw stdout](plumed_trp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_trp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervm76f27:04281] *** Process received signal ***
[runnervm76f27:04281] Signal: Aborted (6)
[runnervm76f27:04281] Signal code:  (-6)
[runnervm76f27:04281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93f2245330]
[runnervm76f27:04281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93f229ec0c]
[runnervm76f27:04281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93f224527e]
[runnervm76f27:04281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93f22288ff]
[runnervm76f27:04281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93f26a5ff5]
[runnervm76f27:04281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93f26bb0da]
[runnervm76f27:04281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93f26a5a55]
[runnervm76f27:04281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93f26a5a6f]
[runnervm76f27:04281] [ 8] plumed(+0x146dd)[0x55d9b3dc06dd]
[runnervm76f27:04281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93f222a1ca]
[runnervm76f27:04281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93f222a28b]
[runnervm76f27:04281] [11] plumed(+0x15365)[0x55d9b3dc1365]
[runnervm76f27:04281] *** End of error message ***
</pre>
{% endraw %}
