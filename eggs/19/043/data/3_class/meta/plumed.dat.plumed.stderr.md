**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmeorf1:11430] *** Process received signal ***
[runnervmeorf1:11430] Signal: Aborted (6)
[runnervmeorf1:11430] Signal code:  (-6)
[runnervmeorf1:11430] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9439c45330]
[runnervmeorf1:11430] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9439c9eb2c]
[runnervmeorf1:11430] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9439c4527e]
[runnervmeorf1:11430] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9439c288ff]
[runnervmeorf1:11430] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f943a0a5ff5]
[runnervmeorf1:11430] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f943a0bb0da]
[runnervmeorf1:11430] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f943a0a5a55]
[runnervmeorf1:11430] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f943a0a5a6f]
[runnervmeorf1:11430] [ 8] plumed(+0x146dd)[0x55e3398a36dd]
[runnervmeorf1:11430] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9439c2a1ca]
[runnervmeorf1:11430] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9439c2a28b]
[runnervmeorf1:11430] [11] plumed(+0x15365)[0x55e3398a4365]
[runnervmeorf1:11430] *** End of error message ***
</pre>
{% endraw %}
