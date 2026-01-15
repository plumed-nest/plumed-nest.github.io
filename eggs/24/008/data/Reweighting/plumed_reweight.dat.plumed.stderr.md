**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmtnos:32973] *** Process received signal ***
[runnervmmtnos:32973] Signal: Aborted (6)
[runnervmmtnos:32973] Signal code:  (-6)
[runnervmmtnos:32973] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0306645330]
[runnervmmtnos:32973] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f030669eb2c]
[runnervmmtnos:32973] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f030664527e]
[runnervmmtnos:32973] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03066288ff]
[runnervmmtnos:32973] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0306aa5ff5]
[runnervmmtnos:32973] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0306abb0da]
[runnervmmtnos:32973] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0306aa5a55]
[runnervmmtnos:32973] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0306aa5a6f]
[runnervmmtnos:32973] [ 8] plumed(+0x146dd)[0x556d6c2fb6dd]
[runnervmmtnos:32973] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f030662a1ca]
[runnervmmtnos:32973] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f030662a28b]
[runnervmmtnos:32973] [11] plumed(+0x15365)[0x556d6c2fc365]
[runnervmmtnos:32973] *** End of error message ***
</pre>
{% endraw %}
