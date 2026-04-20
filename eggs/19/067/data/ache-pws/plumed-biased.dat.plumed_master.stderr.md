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
[runnervmeorf1:09610] *** Process received signal ***
[runnervmeorf1:09610] Signal: Aborted (6)
[runnervmeorf1:09610] Signal code:  (-6)
[runnervmeorf1:09610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb21c845330]
[runnervmeorf1:09610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21c89eb2c]
[runnervmeorf1:09610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21c84527e]
[runnervmeorf1:09610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb21c8288ff]
[runnervmeorf1:09610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb21cca5ff5]
[runnervmeorf1:09610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb21ccbb0da]
[runnervmeorf1:09610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb21cca5a55]
[runnervmeorf1:09610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb21cca5a6f]
[runnervmeorf1:09610] [ 8] plumed_master(+0x146dd)[0x55967d8666dd]
[runnervmeorf1:09610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21c82a1ca]
[runnervmeorf1:09610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21c82a28b]
[runnervmeorf1:09610] [11] plumed_master(+0x15365)[0x55967d867365]
[runnervmeorf1:09610] *** End of error message ***
</pre>
{% endraw %}
