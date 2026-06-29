**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT
[runnervmmklqx:09607] *** Process received signal ***
[runnervmmklqx:09607] Signal: Aborted (6)
[runnervmmklqx:09607] Signal code:  (-6)
[runnervmmklqx:09607] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f815a445330]
[runnervmmklqx:09607] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f815a49eb2c]
[runnervmmklqx:09607] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f815a44527e]
[runnervmmklqx:09607] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f815a4288ff]
[runnervmmklqx:09607] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f815a8a5ff5]
[runnervmmklqx:09607] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f815a8bb0da]
[runnervmmklqx:09607] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f815a8a5a55]
[runnervmmklqx:09607] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f815a8a5a6f]
[runnervmmklqx:09607] [ 8] plumed_master(+0x146dd)[0x5622321fd6dd]
[runnervmmklqx:09607] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f815a42a1ca]
[runnervmmklqx:09607] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f815a42a28b]
[runnervmmklqx:09607] [11] plumed_master(+0x15365)[0x5622321fe365]
[runnervmmklqx:09607] *** End of error message ***
</pre>
{% endraw %}
