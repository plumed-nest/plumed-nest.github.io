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
[runnervmvrwv9:12688] *** Process received signal ***
[runnervmvrwv9:12688] Signal: Aborted (6)
[runnervmvrwv9:12688] Signal code:  (-6)
[runnervmvrwv9:12688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8f3845330]
[runnervmvrwv9:12688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8f389eb2c]
[runnervmvrwv9:12688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8f384527e]
[runnervmvrwv9:12688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8f38288ff]
[runnervmvrwv9:12688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8f3ca5ff5]
[runnervmvrwv9:12688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8f3cbb0da]
[runnervmvrwv9:12688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8f3ca5a55]
[runnervmvrwv9:12688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8f3ca5a6f]
[runnervmvrwv9:12688] [ 8] plumed(+0x146dd)[0x564b2fef36dd]
[runnervmvrwv9:12688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8f382a1ca]
[runnervmvrwv9:12688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8f382a28b]
[runnervmvrwv9:12688] [11] plumed(+0x15365)[0x564b2fef4365]
[runnervmvrwv9:12688] *** End of error message ***
</pre>
{% endraw %}
