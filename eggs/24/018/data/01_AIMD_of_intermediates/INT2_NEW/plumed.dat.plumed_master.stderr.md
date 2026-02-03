**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmkj6or:07658] *** Process received signal ***
[runnervmkj6or:07658] Signal: Aborted (6)
[runnervmkj6or:07658] Signal code:  (-6)
[runnervmkj6or:07658] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0230645330]
[runnervmkj6or:07658] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f023069eb2c]
[runnervmkj6or:07658] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f023064527e]
[runnervmkj6or:07658] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02306288ff]
[runnervmkj6or:07658] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0230aa5ff5]
[runnervmkj6or:07658] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0230abb0da]
[runnervmkj6or:07658] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0230aa5a55]
[runnervmkj6or:07658] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0230aa5a6f]
[runnervmkj6or:07658] [ 8] plumed_master(+0x146dd)[0x5648bf91c6dd]
[runnervmkj6or:07658] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f023062a1ca]
[runnervmkj6or:07658] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f023062a28b]
[runnervmkj6or:07658] [11] plumed_master(+0x15365)[0x5648bf91d365]
[runnervmkj6or:07658] *** End of error message ***
</pre>
{% endraw %}
