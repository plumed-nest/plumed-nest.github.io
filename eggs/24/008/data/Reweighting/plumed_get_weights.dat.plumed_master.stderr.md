**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmtnos:32935] *** Process received signal ***
[runnervmmtnos:32935] Signal: Aborted (6)
[runnervmmtnos:32935] Signal code:  (-6)
[runnervmmtnos:32935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79c1445330]
[runnervmmtnos:32935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79c149eb2c]
[runnervmmtnos:32935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79c144527e]
[runnervmmtnos:32935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79c14288ff]
[runnervmmtnos:32935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79c18a5ff5]
[runnervmmtnos:32935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79c18bb0da]
[runnervmmtnos:32935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79c18a5a55]
[runnervmmtnos:32935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79c18a5a6f]
[runnervmmtnos:32935] [ 8] plumed_master(+0x146dd)[0x557c5c8ea6dd]
[runnervmmtnos:32935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79c142a1ca]
[runnervmmtnos:32935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79c142a28b]
[runnervmmtnos:32935] [11] plumed_master(+0x15365)[0x557c5c8eb365]
[runnervmmtnos:32935] *** End of error message ***
</pre>
{% endraw %}
