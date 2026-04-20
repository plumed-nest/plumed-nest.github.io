**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmeorf1:11446] *** Process received signal ***
[runnervmeorf1:11446] Signal: Aborted (6)
[runnervmeorf1:11446] Signal code:  (-6)
[runnervmeorf1:11446] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ece645330]
[runnervmeorf1:11446] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ece69eb2c]
[runnervmeorf1:11446] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ece64527e]
[runnervmeorf1:11446] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ece6288ff]
[runnervmeorf1:11446] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8eceaa5ff5]
[runnervmeorf1:11446] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8eceabb0da]
[runnervmeorf1:11446] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8eceaa5a55]
[runnervmeorf1:11446] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8eceaa5a6f]
[runnervmeorf1:11446] [ 8] plumed_master(+0x146dd)[0x562135f046dd]
[runnervmeorf1:11446] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ece62a1ca]
[runnervmeorf1:11446] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ece62a28b]
[runnervmeorf1:11446] [11] plumed_master(+0x15365)[0x562135f05365]
[runnervmeorf1:11446] *** End of error message ***
</pre>
{% endraw %}
