**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:10875] *** Process received signal ***
[runnervmmklqx:10875] Signal: Aborted (6)
[runnervmmklqx:10875] Signal code:  (-6)
[runnervmmklqx:10875] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9308645330]
[runnervmmklqx:10875] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f930869eb2c]
[runnervmmklqx:10875] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f930864527e]
[runnervmmklqx:10875] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93086288ff]
[runnervmmklqx:10875] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9308aa5ff5]
[runnervmmklqx:10875] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9308abb0da]
[runnervmmklqx:10875] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9308aa5a55]
[runnervmmklqx:10875] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9308aa5a6f]
[runnervmmklqx:10875] [ 8] plumed(+0x146dd)[0x56465f83e6dd]
[runnervmmklqx:10875] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f930862a1ca]
[runnervmmklqx:10875] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f930862a28b]
[runnervmmklqx:10875] [11] plumed(+0x15365)[0x56465f83f365]
[runnervmmklqx:10875] *** End of error message ***
</pre>
{% endraw %}
