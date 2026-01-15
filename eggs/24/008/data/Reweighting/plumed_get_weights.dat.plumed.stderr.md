**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmtnos:32919] *** Process received signal ***
[runnervmmtnos:32919] Signal: Aborted (6)
[runnervmmtnos:32919] Signal code:  (-6)
[runnervmmtnos:32919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4c2245330]
[runnervmmtnos:32919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4c229eb2c]
[runnervmmtnos:32919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4c224527e]
[runnervmmtnos:32919] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4c22288ff]
[runnervmmtnos:32919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4c26a5ff5]
[runnervmmtnos:32919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4c26bb0da]
[runnervmmtnos:32919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4c26a5a55]
[runnervmmtnos:32919] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4c26a5a6f]
[runnervmmtnos:32919] [ 8] plumed(+0x146dd)[0x55f2264616dd]
[runnervmmtnos:32919] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4c222a1ca]
[runnervmmtnos:32919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4c222a28b]
[runnervmmtnos:32919] [11] plumed(+0x15365)[0x55f226462365]
[runnervmmtnos:32919] *** End of error message ***
</pre>
{% endraw %}
