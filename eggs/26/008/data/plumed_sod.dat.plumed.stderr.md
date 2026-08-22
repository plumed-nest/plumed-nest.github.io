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
[runnervm76f27:04228] *** Process received signal ***
[runnervm76f27:04228] Signal: Aborted (6)
[runnervm76f27:04228] Signal code:  (-6)
[runnervm76f27:04228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0cb645330]
[runnervm76f27:04228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0cb69ec0c]
[runnervm76f27:04228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0cb64527e]
[runnervm76f27:04228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0cb6288ff]
[runnervm76f27:04228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0cbaa5ff5]
[runnervm76f27:04228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0cbabb0da]
[runnervm76f27:04228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0cbaa5a55]
[runnervm76f27:04228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0cbaa5a6f]
[runnervm76f27:04228] [ 8] plumed(+0x146dd)[0x55e2b73de6dd]
[runnervm76f27:04228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0cb62a1ca]
[runnervm76f27:04228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0cb62a28b]
[runnervm76f27:04228] [11] plumed(+0x15365)[0x55e2b73df365]
[runnervm76f27:04228] *** End of error message ***
</pre>
{% endraw %}
