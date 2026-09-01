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
[runnervmgx7h7:04277] *** Process received signal ***
[runnervmgx7h7:04277] Signal: Aborted (6)
[runnervmgx7h7:04277] Signal code:  (-6)
[runnervmgx7h7:04277] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe981645330]
[runnervmgx7h7:04277] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe98169ec0c]
[runnervmgx7h7:04277] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe98164527e]
[runnervmgx7h7:04277] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9816288ff]
[runnervmgx7h7:04277] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe981aa5ff5]
[runnervmgx7h7:04277] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe981abb0da]
[runnervmgx7h7:04277] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe981aa5a55]
[runnervmgx7h7:04277] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe981aa5a6f]
[runnervmgx7h7:04277] [ 8] plumed(+0x146dd)[0x5591622576dd]
[runnervmgx7h7:04277] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe98162a1ca]
[runnervmgx7h7:04277] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe98162a28b]
[runnervmgx7h7:04277] [11] plumed(+0x15365)[0x559162258365]
[runnervmgx7h7:04277] *** End of error message ***
</pre>
{% endraw %}
