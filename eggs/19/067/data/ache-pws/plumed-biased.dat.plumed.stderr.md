**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:11764] *** Process received signal ***
[runnervmkj6or:11764] Signal: Aborted (6)
[runnervmkj6or:11764] Signal code:  (-6)
[runnervmkj6or:11764] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9724645330]
[runnervmkj6or:11764] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f972469eb2c]
[runnervmkj6or:11764] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f972464527e]
[runnervmkj6or:11764] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97246288ff]
[runnervmkj6or:11764] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9724aa5ff5]
[runnervmkj6or:11764] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9724abb0da]
[runnervmkj6or:11764] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9724aa5a55]
[runnervmkj6or:11764] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9724aa5a6f]
[runnervmkj6or:11764] [ 8] plumed(+0x146dd)[0x5628baf976dd]
[runnervmkj6or:11764] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f972462a1ca]
[runnervmkj6or:11764] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f972462a28b]
[runnervmkj6or:11764] [11] plumed(+0x15365)[0x5628baf98365]
[runnervmkj6or:11764] *** End of error message ***
</pre>
{% endraw %}
