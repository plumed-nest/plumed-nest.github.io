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
[runnervmmklqx:10796] *** Process received signal ***
[runnervmmklqx:10796] Signal: Aborted (6)
[runnervmmklqx:10796] Signal code:  (-6)
[runnervmmklqx:10796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa00ce45330]
[runnervmmklqx:10796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa00ce9eb2c]
[runnervmmklqx:10796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa00ce4527e]
[runnervmmklqx:10796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa00ce288ff]
[runnervmmklqx:10796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa00d2a5ff5]
[runnervmmklqx:10796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa00d2bb0da]
[runnervmmklqx:10796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa00d2a5a55]
[runnervmmklqx:10796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa00d2a5a6f]
[runnervmmklqx:10796] [ 8] plumed(+0x146dd)[0x5558386836dd]
[runnervmmklqx:10796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa00ce2a1ca]
[runnervmmklqx:10796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa00ce2a28b]
[runnervmmklqx:10796] [11] plumed(+0x15365)[0x555838684365]
[runnervmmklqx:10796] *** End of error message ***
</pre>
{% endraw %}
