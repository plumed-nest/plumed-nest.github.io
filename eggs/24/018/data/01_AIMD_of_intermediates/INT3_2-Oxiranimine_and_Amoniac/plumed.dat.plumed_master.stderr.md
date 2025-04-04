**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:07452] *** Process received signal ***
[fv-az1360-658:07452] Signal: Aborted (6)
[fv-az1360-658:07452] Signal code:  (-6)
[fv-az1360-658:07452] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f292d245330]
[fv-az1360-658:07452] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f292d29eb2c]
[fv-az1360-658:07452] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f292d24527e]
[fv-az1360-658:07452] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f292d2288ff]
[fv-az1360-658:07452] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f292d6a5ff5]
[fv-az1360-658:07452] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f292d6bb0da]
[fv-az1360-658:07452] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f292d6a5a55]
[fv-az1360-658:07452] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f292d6a5a6f]
[fv-az1360-658:07452] [ 8] plumed_master(+0x146dd)[0x56423d8f06dd]
[fv-az1360-658:07452] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f292d22a1ca]
[fv-az1360-658:07452] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f292d22a28b]
[fv-az1360-658:07452] [11] plumed_master(+0x15365)[0x56423d8f1365]
[fv-az1360-658:07452] *** End of error message ***
</pre>
{% endraw %}
