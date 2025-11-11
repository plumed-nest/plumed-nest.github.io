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
[runnervmw9dnm:07776] *** Process received signal ***
[runnervmw9dnm:07776] Signal: Aborted (6)
[runnervmw9dnm:07776] Signal code:  (-6)
[runnervmw9dnm:07776] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f938f445330]
[runnervmw9dnm:07776] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f938f49eb2c]
[runnervmw9dnm:07776] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f938f44527e]
[runnervmw9dnm:07776] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f938f4288ff]
[runnervmw9dnm:07776] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f938f8a5ff5]
[runnervmw9dnm:07776] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f938f8bb0da]
[runnervmw9dnm:07776] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f938f8a5a55]
[runnervmw9dnm:07776] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f938f8a5a6f]
[runnervmw9dnm:07776] [ 8] plumed_master(+0x146dd)[0x5616e36b36dd]
[runnervmw9dnm:07776] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f938f42a1ca]
[runnervmw9dnm:07776] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f938f42a28b]
[runnervmw9dnm:07776] [11] plumed_master(+0x15365)[0x5616e36b4365]
[runnervmw9dnm:07776] *** End of error message ***
</pre>
{% endraw %}
