**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_cal.dat   
Download: [zipped raw stdout](plumed_cal.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_cal.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04196] *** Process received signal ***
[runnervmvrwv9:04196] Signal: Aborted (6)
[runnervmvrwv9:04196] Signal code:  (-6)
[runnervmvrwv9:04196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8043c45330]
[runnervmvrwv9:04196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8043c9eb2c]
[runnervmvrwv9:04196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8043c4527e]
[runnervmvrwv9:04196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8043c288ff]
[runnervmvrwv9:04196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80440a5ff5]
[runnervmvrwv9:04196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80440bb0da]
[runnervmvrwv9:04196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80440a5a55]
[runnervmvrwv9:04196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80440a5a6f]
[runnervmvrwv9:04196] [ 8] plumed_master(+0x146dd)[0x55a81b5196dd]
[runnervmvrwv9:04196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8043c2a1ca]
[runnervmvrwv9:04196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8043c2a28b]
[runnervmvrwv9:04196] [11] plumed_master(+0x15365)[0x55a81b51a365]
[runnervmvrwv9:04196] *** End of error message ***
</pre>
{% endraw %}
