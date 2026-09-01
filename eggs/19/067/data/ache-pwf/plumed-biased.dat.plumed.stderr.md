**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmgx7h7:11301] *** Process received signal ***
[runnervmgx7h7:11301] Signal: Aborted (6)
[runnervmgx7h7:11301] Signal code:  (-6)
[runnervmgx7h7:11301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03a0645330]
[runnervmgx7h7:11301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03a069ec0c]
[runnervmgx7h7:11301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03a064527e]
[runnervmgx7h7:11301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03a06288ff]
[runnervmgx7h7:11301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03a0aa5ff5]
[runnervmgx7h7:11301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03a0abb0da]
[runnervmgx7h7:11301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03a0aa5a55]
[runnervmgx7h7:11301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03a0aa5a6f]
[runnervmgx7h7:11301] [ 8] plumed(+0x146dd)[0x557125f196dd]
[runnervmgx7h7:11301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03a062a1ca]
[runnervmgx7h7:11301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03a062a28b]
[runnervmgx7h7:11301] [11] plumed(+0x15365)[0x557125f1a365]
[runnervmgx7h7:11301] *** End of error message ***
</pre>
{% endraw %}
