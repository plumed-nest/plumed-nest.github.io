**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmq0rgcvqdmg:10379] *** Process received signal ***
[pkrvmq0rgcvqdmg:10379] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10379] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f401dc45330]
[pkrvmq0rgcvqdmg:10379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f401dc9eb2c]
[pkrvmq0rgcvqdmg:10379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f401dc4527e]
[pkrvmq0rgcvqdmg:10379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f401dc288ff]
[pkrvmq0rgcvqdmg:10379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f401e0a5ff5]
[pkrvmq0rgcvqdmg:10379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f401e0bb0da]
[pkrvmq0rgcvqdmg:10379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f401e0a5a55]
[pkrvmq0rgcvqdmg:10379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f401e0a5a6f]
[pkrvmq0rgcvqdmg:10379] [ 8] plumed_master(+0x146dd)[0x55b42bbac6dd]
[pkrvmq0rgcvqdmg:10379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f401dc2a1ca]
[pkrvmq0rgcvqdmg:10379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f401dc2a28b]
[pkrvmq0rgcvqdmg:10379] [11] plumed_master(+0x15365)[0x55b42bbad365]
[pkrvmq0rgcvqdmg:10379] *** End of error message ***
</pre>
{% endraw %}
