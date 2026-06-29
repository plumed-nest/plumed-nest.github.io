**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06725] *** Process received signal ***
[runnervmmklqx:06725] Signal: Aborted (6)
[runnervmmklqx:06725] Signal code:  (-6)
[runnervmmklqx:06725] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5006e45330]
[runnervmmklqx:06725] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5006e9eb2c]
[runnervmmklqx:06725] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5006e4527e]
[runnervmmklqx:06725] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5006e288ff]
[runnervmmklqx:06725] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50072a5ff5]
[runnervmmklqx:06725] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50072bb0da]
[runnervmmklqx:06725] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50072a5a55]
[runnervmmklqx:06725] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50072a5a6f]
[runnervmmklqx:06725] [ 8] plumed_master(+0x146dd)[0x561acdae26dd]
[runnervmmklqx:06725] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5006e2a1ca]
[runnervmmklqx:06725] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5006e2a28b]
[runnervmmklqx:06725] [11] plumed_master(+0x15365)[0x561acdae3365]
[runnervmmklqx:06725] *** End of error message ***
</pre>
{% endraw %}
