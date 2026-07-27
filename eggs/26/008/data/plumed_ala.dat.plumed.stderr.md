**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_ala.dat   
Download: [zipped raw stdout](plumed_ala.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ala.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library OPESmetad.so
OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04128] *** Process received signal ***
[runnervmvrwv9:04128] Signal: Aborted (6)
[runnervmvrwv9:04128] Signal code:  (-6)
[runnervmvrwv9:04128] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8cc3845330]
[runnervmvrwv9:04128] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8cc389eb2c]
[runnervmvrwv9:04128] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8cc384527e]
[runnervmvrwv9:04128] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8cc38288ff]
[runnervmvrwv9:04128] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8cc3ca5ff5]
[runnervmvrwv9:04128] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8cc3cbb0da]
[runnervmvrwv9:04128] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8cc3ca5a55]
[runnervmvrwv9:04128] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8cc3ca5a6f]
[runnervmvrwv9:04128] [ 8] plumed(+0x146dd)[0x55c35994f6dd]
[runnervmvrwv9:04128] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8cc382a1ca]
[runnervmvrwv9:04128] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8cc382a28b]
[runnervmvrwv9:04128] [11] plumed(+0x15365)[0x55c359950365]
[runnervmvrwv9:04128] *** End of error message ***
</pre>
{% endraw %}
