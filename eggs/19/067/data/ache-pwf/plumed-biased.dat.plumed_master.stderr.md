**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmeorf1:09534] *** Process received signal ***
[runnervmeorf1:09534] Signal: Aborted (6)
[runnervmeorf1:09534] Signal code:  (-6)
[runnervmeorf1:09534] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7565c45330]
[runnervmeorf1:09534] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7565c9eb2c]
[runnervmeorf1:09534] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7565c4527e]
[runnervmeorf1:09534] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7565c288ff]
[runnervmeorf1:09534] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75660a5ff5]
[runnervmeorf1:09534] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75660bb0da]
[runnervmeorf1:09534] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75660a5a55]
[runnervmeorf1:09534] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75660a5a6f]
[runnervmeorf1:09534] [ 8] plumed_master(+0x146dd)[0x562f1ea5d6dd]
[runnervmeorf1:09534] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7565c2a1ca]
[runnervmeorf1:09534] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7565c2a28b]
[runnervmeorf1:09534] [11] plumed_master(+0x15365)[0x562f1ea5e365]
[runnervmeorf1:09534] *** End of error message ***
</pre>
{% endraw %}
