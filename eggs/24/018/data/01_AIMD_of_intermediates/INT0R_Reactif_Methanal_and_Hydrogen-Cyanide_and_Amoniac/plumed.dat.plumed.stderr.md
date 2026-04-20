**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT0R_Reactif_Methanal_and_Hydrogen-Cyanide_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06556] *** Process received signal ***
[runnervmeorf1:06556] Signal: Aborted (6)
[runnervmeorf1:06556] Signal code:  (-6)
[runnervmeorf1:06556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f017f645330]
[runnervmeorf1:06556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f017f69eb2c]
[runnervmeorf1:06556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f017f64527e]
[runnervmeorf1:06556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f017f6288ff]
[runnervmeorf1:06556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f017faa5ff5]
[runnervmeorf1:06556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f017fabb0da]
[runnervmeorf1:06556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f017faa5a55]
[runnervmeorf1:06556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f017faa5a6f]
[runnervmeorf1:06556] [ 8] plumed(+0x146dd)[0x555ad9c796dd]
[runnervmeorf1:06556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f017f62a1ca]
[runnervmeorf1:06556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f017f62a28b]
[runnervmeorf1:06556] [11] plumed(+0x15365)[0x555ad9c7a365]
[runnervmeorf1:06556] *** End of error message ***
</pre>
{% endraw %}
