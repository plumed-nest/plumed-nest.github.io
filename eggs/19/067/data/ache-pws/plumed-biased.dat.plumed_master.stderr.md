**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:11780] *** Process received signal ***
[runnervmkj6or:11780] Signal: Aborted (6)
[runnervmkj6or:11780] Signal code:  (-6)
[runnervmkj6or:11780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda52645330]
[runnervmkj6or:11780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda5269eb2c]
[runnervmkj6or:11780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda5264527e]
[runnervmkj6or:11780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda526288ff]
[runnervmkj6or:11780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda52aa5ff5]
[runnervmkj6or:11780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda52abb0da]
[runnervmkj6or:11780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda52aa5a55]
[runnervmkj6or:11780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda52aa5a6f]
[runnervmkj6or:11780] [ 8] plumed_master(+0x146dd)[0x55ea57ed16dd]
[runnervmkj6or:11780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda5262a1ca]
[runnervmkj6or:11780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda5262a28b]
[runnervmkj6or:11780] [11] plumed_master(+0x15365)[0x55ea57ed2365]
[runnervmkj6or:11780] *** End of error message ***
</pre>
{% endraw %}
