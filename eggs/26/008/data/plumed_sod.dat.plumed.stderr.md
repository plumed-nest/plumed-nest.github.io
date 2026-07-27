**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_sod.dat   
Download: [zipped raw stdout](plumed_sod.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sod.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/PytorchModelBiasVerletBox.so
../../plumed_so/PytorchModelBiasVerletBox.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04284] *** Process received signal ***
[runnervmvrwv9:04284] Signal: Aborted (6)
[runnervmvrwv9:04284] Signal code:  (-6)
[runnervmvrwv9:04284] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff980e45330]
[runnervmvrwv9:04284] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff980e9eb2c]
[runnervmvrwv9:04284] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff980e4527e]
[runnervmvrwv9:04284] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff980e288ff]
[runnervmvrwv9:04284] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9812a5ff5]
[runnervmvrwv9:04284] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9812bb0da]
[runnervmvrwv9:04284] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9812a5a55]
[runnervmvrwv9:04284] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9812a5a6f]
[runnervmvrwv9:04284] [ 8] plumed(+0x146dd)[0x557c07fa06dd]
[runnervmvrwv9:04284] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff980e2a1ca]
[runnervmvrwv9:04284] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff980e2a28b]
[runnervmvrwv9:04284] [11] plumed(+0x15365)[0x557c07fa1365]
[runnervmvrwv9:04284] *** End of error message ***
</pre>
{% endraw %}
