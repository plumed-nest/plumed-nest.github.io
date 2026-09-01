**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmgx7h7:11078] *** Process received signal ***
[runnervmgx7h7:11078] Signal: Aborted (6)
[runnervmgx7h7:11078] Signal code:  (-6)
[runnervmgx7h7:11078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fecde645330]
[runnervmgx7h7:11078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fecde69ec0c]
[runnervmgx7h7:11078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fecde64527e]
[runnervmgx7h7:11078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fecde6288ff]
[runnervmgx7h7:11078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fecdeaa5ff5]
[runnervmgx7h7:11078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fecdeabb0da]
[runnervmgx7h7:11078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fecdeaa5a55]
[runnervmgx7h7:11078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fecdeaa5a6f]
[runnervmgx7h7:11078] [ 8] plumed(+0x146dd)[0x55bf8dd3a6dd]
[runnervmgx7h7:11078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fecde62a1ca]
[runnervmgx7h7:11078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fecde62a28b]
[runnervmgx7h7:11078] [11] plumed(+0x15365)[0x55bf8dd3b365]
[runnervmgx7h7:11078] *** End of error message ***
</pre>
{% endraw %}
